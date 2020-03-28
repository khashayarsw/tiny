# @khashi/tiny

[![NPM](https://img.shields.io/npm/l/@khashi/tiny?color=blue)](https://www.npmjs.com/package/@khashi/tiny)


Removes all spaces from a string.

## Install

```
$ npm install @khashi/tiny
```

## Usage

```js
const tiny = require("@khashi/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
## License

@khashi/tiny is released under the terms of the MIT License.