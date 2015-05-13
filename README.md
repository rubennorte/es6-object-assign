[![npm](https://img.shields.io/npm/l/es6-object-assign.svg)](https://www.npmjs.org/package/es6-object-assign)
[![npm](https://img.shields.io/npm/v/es6-object-assign.svg)](https://www.npmjs.org/package/es6-object-assign)

# ES6 Object.assign()

ECMAScript 6 [Object.assign()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign) polyfill and ponyfill.

The main definition of this package has been copied from the polyfill defined in the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign).

## Installation

### Node 

```bash
npm install es6-object-assign
```

### Browser

The package is also available as a UMD module (compatible with AMD, CommonJS and exposing a global variable `ObjectAssign`) in `dist/object-assign.js` and `dist/object-assign.min.js` (833 bytes minified and gzipped).

It can be installed with npm or downloading the release from GitHub:

```bash
npm install es6-object-assign
```

## Usage

As a polyfill, defining Object.assign() if it is not already defined:

```javascript
require('es6-object-assign').polyfill();
// or
window.ObjectAssign.polyfill();
```

As a ponyfill, loading the assign function to a variable:

```javascript
var assign = require('es6-object-assign').assign;
// or
var assign = window.ObjectAssign.assign;
```

## License

The MIT License (MIT)

Copyright (c) 2015 Rubén Norte

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.