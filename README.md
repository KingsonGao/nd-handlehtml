# nd-handlehtml [![spm version](http://spm.crossjs.com/badge/nd-handlehtml)](http://spm.crossjs.com/package/nd-handlehtml)

---

handle HTML with encode and decode

## Install

```
$ spm install nd-handlehtml --save
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
