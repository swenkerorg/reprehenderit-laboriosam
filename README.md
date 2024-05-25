# @swenkerorg/reprehenderit-laboriosam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @swenkerorg/reprehenderit-laboriosam
```

## Usage/Examples

```js
var regexTester = require('@swenkerorg/reprehenderit-laboriosam');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@swenkerorg/reprehenderit-laboriosam
[npm-version-svg]: https://versionbadg.es/ljharb/@swenkerorg/reprehenderit-laboriosam.svg
[deps-svg]: https://david-dm.org/ljharb/@swenkerorg/reprehenderit-laboriosam.svg
[deps-url]: https://david-dm.org/ljharb/@swenkerorg/reprehenderit-laboriosam
[dev-deps-svg]: https://david-dm.org/ljharb/@swenkerorg/reprehenderit-laboriosam/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@swenkerorg/reprehenderit-laboriosam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@swenkerorg/reprehenderit-laboriosam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@swenkerorg/reprehenderit-laboriosam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@swenkerorg/reprehenderit-laboriosam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@swenkerorg/reprehenderit-laboriosam
[codecov-image]: https://codecov.io/gh/ljharb/@swenkerorg/reprehenderit-laboriosam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@swenkerorg/reprehenderit-laboriosam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@swenkerorg/reprehenderit-laboriosam
[actions-url]: https://github.com/swenkerorg/reprehenderit-laboriosam/actions
