[![pages-build-deployment](https://github.com/PGNetHun/Latte-uOS-Connect/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/PGNetHun/Latte-uOS-Connect/actions/workflows/pages/pages-build-deployment)


# Latte/uOS Connect

Web application to configure devices running Latte/uOS:
- T-Watch-2020
- M5Stack Core2

URL: <https://pgnethun.github.io/Latte-uOS-Connect/>

Framework: [ReactJS](https://reactjs.org/) + [Material UI 5](https://mui.com/)\
Hosting: [GitHub Pages](https://pages.github.com/)

## Local development setup

1. Install [Git](https://git-scm.com/) and [NodeJS](https://nodejs.org/)
2. Clone this repository
3. Open project directory in your favorite code editor (for example: [Visual Studio Code](https://code.visualstudio.com/))
4. Open terminal, and go to project directory
5. Install pre-requirements: `npm install`
6. Start site: `npm start`

The site is started and opened in browser.\
Any change in source code triggers a rebuild, and site is reloaded in browser.

## Available Scripts

|Command| Description |
|:------|:------------|
|`npm install`|Install all dependency from `package.json` file|
|`npm start`|Starts app and opens it in browser|
|`npm test`|Launches the test runner in the interactive watch mode|
|`npm run build`|Builds the app for production to the `build` folder|
|`npm run deploy`|Deploy React app to GitHub Pages|

## Hosting in GitHub Pages

Repository is configured to automatically deploy to GitHub Pages.\
The build output from which the deployment is done is stored in `gh-pages` branch.

Example of hosting a React app in GitHub Pages: <https://github.com/gitname/react-gh-pages>

## Manifest & favicon generator

Tool: https://www.favicon-generator.org/
