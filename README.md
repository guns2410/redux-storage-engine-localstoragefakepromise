# [redux-storage-engine-localstoragefakepromise][]

[![build](https://travis-ci.org/react-stack/redux-storage-engine-localstoragefakepromise.svg?branch=master)](https://travis-ci.org/react-stack/redux-storage-engine-localstoragefakepromise)
[![dependencies](https://david-dm.org/react-stack/redux-storage-engine-localstoragefakepromise.svg)](https://david-dm.org/react-stack/redux-storage-engine-localstoragefakepromise)
[![devDependencies](https://david-dm.org/react-stack/redux-storage-engine-localstoragefakepromise/dev-status.svg)](https://david-dm.org/react-stack/redux-storage-engine-localstoragefakepromise#info=devDependencies)

[![license](https://img.shields.io/npm/l/redux-storage-engine-localstoragefakepromise.svg?style=flat-square)](https://www.npmjs.com/package/redux-storage-engine-localstoragefakepromise)
[![npm version](https://img.shields.io/npm/v/redux-storage-engine-localstoragefakepromise.svg?style=flat-square)](https://www.npmjs.com/package/redux-storage-engine-localstoragefakepromise)
[![npm downloads](https://img.shields.io/npm/dm/redux-storage-engine-localstoragefakepromise.svg?style=flat-square)](https://www.npmjs.com/package/redux-storage-engine-localstoragefakepromise)

`window.localStorage` based engine for [redux-storage][] - like
[redux-storage-engine-localstorage][] - but it does not require a environment
with ES6 Promises.

## Warning

In contrast to [redux-storage-engine-localstorage][] this engine can be used
with old browsers like IE<=11. **BUT** the best solution for you would be to
use a Promise polyfill like [es6-promise][].

## Installation

    npm install --save redux-storage-engine-localstoragefakepromise

## Usage

Similar to [redux-storage-engine-localstorage][]:

```js
import createEngine from 'redux-storage-engine-localstoragefakepromise';
const engine = createEngine('my-save-key');
```

# A fork of [redux-storage-engine-localstoragefakepromise](https://github.com/michaelcontento/redux-storage-engine-localstoragefakepromise)

The original author of the package [redux-storage-engine-localstoragefakepromise](https://github.com/michaelcontento/redux-storage-engine-localstoragefakepromise) has decided to deprecate the project and no longer maintained. The package will now be maintained here.

Thank you [michaelcontento](https://github.com/michaelcontento) for a great library!

## License

    The MIT License (MIT)

    Copyright (c) 2016- Gunjan Soni <gunjan.soni2002@gmail.com> 
    Copyright (c) 2015-2016 Michael Contento <mail@michaelcontento.de> 

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
    the Software, and to permit persons to whom the Software is furnished to do so,
    subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
    FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
    IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

  [redux-storage]: https://github.com/react-stack/redux-storage
  [redux-storage-engine-localstorage]: https://github.com/react-stack/redux-storage-engine-localstorage
  [redux-storage-engine-localstoragefakepromise]: https://github.com/react-stack/redux-storage-engine-localstoragefakepromise
  [es6-promise]: https://www.npmjs.com/package/es6-promise
