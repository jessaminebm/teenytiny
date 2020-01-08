# @jessaminnne/teenytiny

[![npm (scoped)](https://img.shields.io/npm/v/@jessaminnne/teeny.svg)](https://www.npmjs.com/package/@jessaminnne/teenytiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@jessaminnne/teenytiny.svg)](https://www.npmjs.com/package/@jessaminnne/teenytiny)

Removes all spaces from a string.

## Install

```
$ npm install @jessaminnne/teeny
```

## Usage

```js
const teeny = require("@jessaminnne/teenytiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Teeny wants a string!
//    at teeny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
