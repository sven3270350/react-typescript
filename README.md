# `react-scripts-ts` [![npm version](https://badge.fury.io/js/react-scripts-ts.svg)](https://badge.fury.io/js/react-scripts-ts)

Create React apps (with Typescript) with no build configuration.

_Do you know react and want to try out typescript? Or do you know typescript and want to try out react?_ Get all the benefits from `create-react-app` but you use typescript! 🚀

## tl;dr

```sh
npm install -g create-react-app

create-react-app my-app --scripts-version=react-scripts-ts
cd my-app/
npm start
```

## Features

### Code highlighting on error
When you run `npm run build` the terminal will output the error, including the highlighted sourecode (like babel)! 

![CodeHighlight](https://cloud.githubusercontent.com/assets/175278/22310149/1ee66ccc-e346-11e6-83ff-e3a053701fb4.gif)

## Changelog

### 1.1.7
* Merge facebookincubator/create-react-app@0.9.5 into react-scripts-ts
* Merge facebookincubator/create-react-app@0.9.4 into react-scripts-ts
* Merge facebookincubator/create-react-app@0.9.3 into react-scripts-ts
* Merge facebookincubator/create-react-app@0.9.2 into react-scripts-ts
* Merge facebookincubator/create-react-app@0.9.1 into react-scripts-ts

### 1.1.6
* Merge facebookincubator/create-react-app@0.9.0 into react-scripts-ts

### 1.0.6
* Add missing `cli-highlight` dependency

### 1.0.5
* Print file names when running `npm run build`
* Add support for `setupTest.ts`
* Highlight source code when erroring in `npm run build`

### 1.0.4
* Change mentions of `eslint` to `tslint`

### 1.0.3
* Remove hidden character from `tsconfig.json`

### 1.0.2
* Copy `typescriptTransform.js` when running `npm run eject`
