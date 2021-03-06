# Getting Started with React Started Project TypeScript

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Libraries used

```shell
yarn create react-app starter-project --template

cd starter-project

yarn add -D typescript @types/node @types/react 

yarn add -D typescript @types/react-dom @types/jest 

yarn add -D typescript @typescript-eslint/scope-manager

yarn add -D node-sass

yarn add -D scss-loader typings-for-scss-modules-loader

yarn add -D redux @reduxjs/toolkit react-redux @types/react-redux

yarn add recoil

yarn add -D @material-ui/core @material-ui/icons

yarn add boostrap@5

yarn add -D styled-components @types/styled-components

yarn add -D react-router-dom @types/react-router-dom

yarn add -D enzyme enzyme-adapter-react-16 react-test-renderer

yarn add -D enzyme-to-json

yarn add sinon @types/sinon

yarn add puppeteer jest-puppeteer ts-jest

yarn add yarn add @types/puppeteer @types/expect-puppeteer @types/jest-environment-puppeteer

```

## Component Folder Structure


```
– src/components 
– src/features
– src/layout
– src/pages
– src/redux
– src/recoil/atoms
```

```shell
mkdir src/components src/features src/layout src/pages src/redux src/
recoil/atoms
```

### Generate Templates

```shell
npx generate-react-cli component Header
```

### setup Eslint and Prettiers for Ts

```shell
yarn add -D --save-exact eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-prettier eslint-config-react-app eslint-import-resolver-typescript eslint-loader eslint-plugin-flowtype eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks babel-eslint eslint-plugin-jest @typescript-eslint/parser @typescript-eslint/eslint-plugin


yarn add -D --save-exact prettier prettier-eslint prettier-eslint-cli eslint-plugin-prettier
```

see @link https://medium.com/react-courses/react-create-react-app-v3-4-1-a55f3e7a8d6d

```shell
yarn run lint
yarn run format
```

## other useful libraries

```shell
yarn add -D classnames @types/classnames

yarn add -D prop-types

yarn add lodash

yarn add moment

yarn add serve

yarn add Precache React-snap to working offline

yarn add any-promise

yarn add source-map-explorer 

yarn add -D cra-bundle-analyzer

```



## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
