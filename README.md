# modularize
[![Build Status](https://travis-ci.org/frisb/fdboost.png)](http://travis-ci.org/frisb/modularize)
[![Dependency Status](https://gemnasium.com/frisb/fdboost.svg)](https://gemnasium.com/frisb/modularize)
[![Code Climate](https://codeclimate.com/github/frisb/modularize/badges/gpa.svg)](https://codeclimate.com/github/frisb/modularize)
[![npm version](https://badge.fury.io/js/modularize.svg)](http://badge.fury.io/js/modularize)

> Provides AMD and CommonJS wrapping for traditional JavaScript.

All contributions are welcome.


## Usage

```js
var Modularize = require('modularize');
var output = Modularize({
	input: 'function MyClass() {}',
	deps: [
		'riot', // path and variable name are the same
		{'jquery': '$'},
		{'_': 'underscore'},
		{'/path/to/custom/module': 'CustomModule'}
	],
	exports: 'MyClass'
});
```


## Options




## License

(The MIT License)

Copyright (c) frisB.com &lt;play@frisb.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[![Analytics](https://ga-beacon.appspot.com/UA-40562957-13/modularize/readme)](https://github.com/igrigorik/ga-beacon)