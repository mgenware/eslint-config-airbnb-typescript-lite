# eslint-config-airbnb-typescript-lite

[![Build Status](https://github.com/mgenware/eslint-config-airbnb-typescript-lite/workflows/Build/badge.svg)](https://github.com/mgenware/eslint-config-airbnb-typescript-lite/actions)
[![npm version](https://img.shields.io/npm/v/eslint-config-airbnb-typescript-lite.svg?style=flat-square)](https://npmjs.com/package/eslint-config-airbnb-typescript-lite)
[![Node.js Version](http://img.shields.io/node/v/eslint-config-airbnb-typescript-lite.svg?style=flat-square)](https://nodejs.org/en/)

Fork of https://github.com/iamturns/eslint-config-airbnb-typescript. Removed `eslint-config-airbnb` as a dependency.

If you have any questions regarding ESLint rules, please file issues or PRs to the [original repo](https://github.com/iamturns/eslint-config-airbnb-typescript).

## Usage

Install `eslint-config-airbnb-typescript-lite` and its peer dependencies:

```sh
yarn add eslint-config-airbnb-typescript-lite eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin -D
```

Use this fork in `.eslintrc.js`:

```js
module.exports = {
  extends: ['airbnb-typescript-lite', 'plugin:@typescript-eslint/recommended'],
  /** Omitted for simplicity */
};
```
