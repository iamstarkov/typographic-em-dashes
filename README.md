# typographic-em-dashes

[![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Coveralls Status][coveralls-image]][coveralls-url]
[![Dependency Status][depstat-image]][depstat-url]
[![DevDependency Status][depstat-dev-image]][depstat-dev-url]

> [Use them, don’t confuse them][rtfm]

Micro module to help eliminate one of the [bad typewriter habits][habits].


## Install

```sh
npm install --save typographic-em-dashes
```


## Usage

```js
var emdashes = require('typographic-em-dashes');

emdashes(`--`); // —
emdashes(`foo -- bar`); // foo — bar
emdashes(`foo — bar`); // foo — bar
```

## License

MIT © [Vladimir Starkov](https://iamstarkov.com/)

[rtfm]: http://practicaltypography.com/hyphens-and-dashes.html
[habits]: http://practicaltypography.com/typewriter-habits.html

[npm-url]: https://npmjs.org/package/typographic-em-dashes
[npm-image]: http://img.shields.io/npm/v/typographic-em-dashes.svg

[travis-url]: https://travis-ci.org/iamstarkov/typographic-em-dashes
[travis-image]: http://img.shields.io/travis/iamstarkov/typographic-em-dashes.svg

[coveralls-url]: https://coveralls.io/r/iamstarkov/typographic-em-dashes
[coveralls-image]: http://img.shields.io/coveralls/iamstarkov/typographic-em-dashes.svg

[depstat-url]: https://david-dm.org/iamstarkov/typographic-em-dashes
[depstat-image]: https://david-dm.org/iamstarkov/typographic-em-dashes.svg

[depstat-dev-url]: https://david-dm.org/iamstarkov/typographic-em-dashes
[depstat-dev-image]: https://david-dm.org/iamstarkov/typographic-em-dashes/dev-status.svg
