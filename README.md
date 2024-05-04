# @lambrioanpm/perferendis-rem-alias <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @lambrioanpm/perferendis-rem-alias
```

## Usage/Examples

```js
var regexTester = require('@lambrioanpm/perferendis-rem-alias');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@lambrioanpm/perferendis-rem-alias
[npm-version-svg]: https://versionbadg.es/ljharb/@lambrioanpm/perferendis-rem-alias.svg
[deps-svg]: https://david-dm.org/ljharb/@lambrioanpm/perferendis-rem-alias.svg
[deps-url]: https://david-dm.org/ljharb/@lambrioanpm/perferendis-rem-alias
[dev-deps-svg]: https://david-dm.org/ljharb/@lambrioanpm/perferendis-rem-alias/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@lambrioanpm/perferendis-rem-alias#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@lambrioanpm/perferendis-rem-alias.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@lambrioanpm/perferendis-rem-alias.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@lambrioanpm/perferendis-rem-alias.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@lambrioanpm/perferendis-rem-alias
[codecov-image]: https://codecov.io/gh/ljharb/@lambrioanpm/perferendis-rem-alias/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@lambrioanpm/perferendis-rem-alias/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@lambrioanpm/perferendis-rem-alias
[actions-url]: https://github.com/lambrioanpm/perferendis-rem-alias/actions
