# globals [![Build Status](https://travis-ci.org/sindresorhus/globals.svg?branch=master)](https://travis-ci.org/sindresorhus/globals)

> Global identifiers from different JavaScript environments

Extracted from [JSHint](https://github.com/jshint/jshint/blob/master/src/vars.js) and [ESLint](https://github.com/nzakas/eslint/blob/master/conf/environments.json) and merged.

It's just a [JSON file](globals.json), so use it in whatever environment you like.


## Install

```sh
$ npm install --save globals
```


## Usage

```js
var globals = require('globals');

console.log(globals.browser);
/*
{
	addEventListener: false,
	applicationCache: false,
	ArrayBuffer: false,
	atob: false,
	...
}
*/
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
