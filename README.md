# `react-ts-web-extension-template`

> This is a fork of [@aeksco](https://github.com/aeksco)'s [aeksco/react-typescript-web-extension-starter](https://github.com/aeksco/react-typescript-web-extension-starter.git) brilliant repo starter, along with [some modifications](https://github.com/capaj/react-typescript-web-extension-starter.git) by [@capaj](https://github.com/ca) that I merged into the original repo.
> Currently everything is in active development, and I just started working on it. So until I have a stable version, I will use the `dev` branch.

----------------------------------------------------------------------

[![GitHub stars](https://img.shields.io/github/stars/aeksco/react-typescript-web-extension-starter.svg?style=social&label=Stars&style=plastic)]()
[![GitHub watchers](https://img.shields.io/github/watchers/aeksco/react-typescript-web-extension-starter.svg?style=social&label=Watch&style=plastic)]()
[![GitHub forks](https://img.shields.io/github/forks/aeksco/react-typescript-web-extension-starter.svg?style=social&label=Fork&style=plastic)]()
[![GitHub contributors](https://img.shields.io/github/contributors/aeksco/react-typescript-web-extension-starter.svg)](https://github.com/aeksco/react-typescript-web-extension-starter/graphs/contributors)
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/aeksco/react-typescript-web-extension-starter/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/aeksco/react-typescript-web-extension-starter.svg)](https://github.com/aeksco/react-typescript-web-extension-starter/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/aeksco/react-typescript-web-extension-starter.svg)](https://github.com/aeksco/react-typescript-web-extension-starter/commits/master)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/aeksco/react-typescript-web-extension-starter.svg?style=flat)]()
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

[![HitCount](http://hits.dwyl.com/aeksco/react-typescript-web-extension-starter.svg)](http://hits.dwyl.com/aeksco/react-typescript-web-extension-starter)
[![Tweet](https://img.shields.io/twitter/url/https/github.com/aeksco/react-typescript-web-extension-starter.svg?style=social)](https://twitter.com/intent/tweet?text=https://github.com/aeksco/react-typescript-web-extension-starter)
[![Twitter Follow](https://img.shields.io/twitter/follow/aeksco.svg?style=social)](https://twitter.com/aeksco)

![React TypeScript Web Extension Starter](https://i.imgur.com/wjIiRSv.png)

:desktop_computer: A Web Extension starter kit built with React, TypeScript, EsLint, Prettier, Jest, TailwindCSS, &amp; Webpack. Compatible with Google Chrome, Mozilla Firefox, Brave, and Microsoft Edge.

![Example Extension Popup](https://i.imgur.com/Wp37usG.png 'Example Extension Popup')
![Example Extension Popup](https://i.imgur.com/UvOOWlv.png "Example Extension Popup")

**Getting Started**

Run the following commands to install dependencies and start developing

```
yarn install
yarn dev
```

**Scripts**

- `yarn dev` - run `webpack` in `watch` mode
- `yarn build` - builds the production-ready unpacked extension
- `yarn test -u` - runs Jest + updates test snapshots
- `yarn lint` - runs EsLint

<details>
  <summary>Loading the extension in Google Chrome</summary>

In [Google Chrome](https://www.google.com/chrome/), open up [chrome://extensions](chrome://extensions) in a new tab. Make sure the `Developer Mode` checkbox in the upper-right corner is turned on. Click `Load unpacked` and select the `dist` directory in this repository - your extension should now be loaded.

![Installed Extension in Google Chrome](https://i.imgur.com/ORuHbDR.png 'Installed Extension in Google Chrome')
![Installed Extension in Google Chrome](https://i.imgur.com/Y2dQFte.png "Installed Extension in Google Chrome")

</details>

<details>
  <summary>Loading the extension in Brave</summary>

In [Brave](https://brave.com/), open up [brave://extensions](brave://extensions) in a new tab. Make sure the `Developer Mode` checkbox in the upper-right corner is turned on. Click `Load unpacked` and select the `dist` directory in this repository - your extension should now be loaded.

![Installed Extension in Brave](https://i.imgur.com/z8lW02m.png 'Installed Extension in Brave')
![Installed Extension in Brave](https://i.imgur.com/rKsbtcO.png "Installed Extension in Brave")

</details>

<details>
  <summary>Loading the extension in Mozilla Firefox</summary>

In [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), open up the [about:debugging](about:debugging) page in a new tab. Click the `This Firefox` link in the sidebar. One the `This Firefox` page, click the `Load Temporary Add-on...` button and select the `manifest.json` from the `dist` directory in this repository - your extension should now be loaded.

![Installed Extension in Mozilla Firefox](https://i.imgur.com/FKfTw4B.png "Installed Extension in Mozilla Firefox")

</details>

<details>
  <summary>Loading the extension in Microsoft Edge</summary>

In [Microsoft Edge](https://www.microsoft.com/en-us/edge), open up [edge://extensions](edge://extensions) in a new tab. Make sure the `Developer Mode` checkbox in the lower-left corner is turned on. Click `Load unpacked` and select the `dist` directory in this repository - your extension should now be loaded.

![Installed Extension in Microsoft Edge](https://i.imgur.com/ykesx0g.png "Installed Extension in Microsoft Edge")

</details>

**Notes**

- Includes ESLint configured to work with TypeScript and Prettier.

- Includes tests with Jest - note that the `babel.config.js` and associated dependencies are only necessary for Jest to work with TypeScript.

- Recommended to use `Visual Studio Code` with the `Format on Save` setting turned on.

-   Example icons courtesy of [Heroicons](https://heroicons.com/).

- Includes Storybook configured to work with React + TypeScript. Note that it maintains its own `webpack.config.js` and `tsconfig.json` files. See example story in `src/components/hello/__tests__/hello.stories.tsx`

**Built with**

- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [Chakra-ui](https://chakra-ui.com/)
- [webextension-polyfill-ts](https://github.com/Lusito/webextension-polyfill-ts)

**Misc. References**

- [Chrome Extension Developer Guide](https://developer.chrome.com/extensions/devguide)
- [Firefox Extension Developer Guide](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
- [Eslint + Prettier + Typescript Guide](https://dev.to/robertcoopercode/using-eslint-and-prettier-in-a-typescript-project-53jb)
