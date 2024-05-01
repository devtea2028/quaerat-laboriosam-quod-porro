# @devtea2028/quaerat-laboriosam-quod-porro [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Meet%20this%20awesome%20library&url=https://github.com/devtea2028/quaerat-laboriosam-quod-porro&via=nicolasvanhoren&hashtags=javascript,asyncawait,async,libraries,programming)

![logo](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/raw/master/img/facebook_cover_photo_2_680.png)

[![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/@devtea2028/quaerat-laboriosam-quod-porro?style=social)](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/stargazers) [![Website](https://img.shields.io/website.svg?url=http%3A%2F%2Fnicolas-van.github.io%2F@devtea2028/quaerat-laboriosam-quod-porro)](https://nicolas-van.github.io/@devtea2028/quaerat-laboriosam-quod-porro)
[![Node.js CI](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/workflows/Node.js%20CI/badge.svg)](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/actions) [![npm](https://img.shields.io/npm/v/@devtea2028/quaerat-laboriosam-quod-porro)](https://www.npmjs.com/package/@devtea2028/quaerat-laboriosam-quod-porro) [![Coverage Status](https://coveralls.io/repos/github/nicolas-van/@devtea2028/quaerat-laboriosam-quod-porro/badge.svg?branch=master)](https://coveralls.io/github/nicolas-van/@devtea2028/quaerat-laboriosam-quod-porro?branch=master) [![](https://data.jsdelivr.com/v1/package/npm/@devtea2028/quaerat-laboriosam-quod-porro/badge)](https://www.jsdelivr.com/package/npm/@devtea2028/quaerat-laboriosam-quod-porro)

A modern JavaScript tooling library for asynchronous operations using async/await, promises and async generators.

This library is a modernized alternative to a lot of libraries like [Async.js](https://caolan.github.io/async/v3/) that were created using the legacy callback style to handle asynchronous operations. Its goal is to be as complete as any of those libraries while being built from the very beginning with async/await and promises in mind.

[See the documentation](https://nicolas-van.github.io/@devtea2028/quaerat-laboriosam-quod-porro).

* Exclusively uses async/await, promises and async generators in its code, tests and documentation.
* Has low bundle size.
* Has 100% code coverage.
* Bundled for ESM modules, CommonJS and UMD.
* Works in node >= 8 and in the vast majority of browsers (very old browser compatibility can be achieved using Babel and shims).
* Has Typescript support.

[![Stargazers repo roster for @nicolas-van/@devtea2028/quaerat-laboriosam-quod-porro](https://reporoster.com/stars/nicolas-van/@devtea2028/quaerat-laboriosam-quod-porro)](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/stargazers)

## Installation

```bash
npm install --save @devtea2028/quaerat-laboriosam-quod-porro
```

Or use [jsDelivr](https://www.jsdelivr.com/package/npm/@devtea2028/quaerat-laboriosam-quod-porro) to get the UMD version. The content of the library will be available under the `modernAsync` global variable.

## Usage

```javascript
import { asyncMap, asyncSleep } from '@devtea2028/quaerat-laboriosam-quod-porro'

const array = [1, 2, 3]
const result = await asyncMap(array, async (v) => {
  await asyncSleep(10)
  return v * 2
})
console.log(result)
```

[See the documentation for the rest](https://nicolas-van.github.io/@devtea2028/quaerat-laboriosam-quod-porro).

## Migrating from version 1.X to version 2.X

[See the migration guide](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/blob/master/version-1-to-2-guide.md).

## Changelog

[The changelog](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/blob/master/CHANGELOG.md).

## Contribution Guide

[The contribution guide](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/blob/master/CONTRIBUTING.md)

## License

[The license](https://github.com/devtea2028/quaerat-laboriosam-quod-porro/blob/master/LICENSE.md).
