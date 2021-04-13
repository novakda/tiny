# @dnovak/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@dnovak/tiny.svg)](https://www.npmjs.com/package/@dnovak/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@dnovak/tiny.svg)](https://www.npmjs.com/package/@dnovak/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @dnovak/tiny
```

## Usage

```js
const tiny = require("@dnovak/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
