# @sha07/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sha07/tiny.svg)](https://www.npmjs.com/package/@sha07/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sha07/tiny.svg)](https://www.npmjs.com/package/@sha07/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @sha07/tiny
```

## Usage

```js
const tiny = require("@sha07/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
