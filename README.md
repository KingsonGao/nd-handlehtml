# nd-handlehtml [![npm](https://img.shields.io/npm/v/nd-handlehtml.svg)](https://npmjs.org/package/nd-handlehtml)

---

handle HTML with encode and decode

## Install

```
$ npm install nd-handlehtml --save
```

## Usage

```js
var handleHTML = require('nd-handlehtml');
// use handleHTML
// encode:
var encodeResult = handleHTML.encode(html);
console.log(encodeResult);
// decode:
var decodeResult = handleHTML.decode(encodeResult);
console.log(decodeResult);
```
