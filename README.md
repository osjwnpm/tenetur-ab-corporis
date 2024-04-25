# @osjwnpm/tenetur-ab-corporis <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

ECMAScript spec abstract operations.

Every operation is available by edition/year and by name - for example, `@osjwnpm/tenetur-ab-corporis/2020/Call` gives you the `Call` operation from ES2020, `@osjwnpm/tenetur-ab-corporis/5/Type` gives you the `Type` operation from ES5.

All abstract operations are also available under an `es5`/`es2015`/`es2016`/`es2017`/`es2018`/`es2019`/`es2020`/`es2021` entry point, and as a property on the `main` export, but using deep imports is highly encouraged for bundle size and performance reasons. Non-deep entry points will be removed in the next semver-major release.

## Example

```js
var ES = require('@osjwnpm/tenetur-ab-corporis');
var assert = require('assert');

assert(ES.isCallable(function () {}));
assert(!ES.isCallable(/a/g));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@osjwnpm/tenetur-ab-corporis
[npm-version-svg]: https://versionbadg.es/ljharb/@osjwnpm/tenetur-ab-corporis.svg
[deps-svg]: https://david-dm.org/ljharb/@osjwnpm/tenetur-ab-corporis.svg
[deps-url]: https://david-dm.org/ljharb/@osjwnpm/tenetur-ab-corporis
[dev-deps-svg]: https://david-dm.org/ljharb/@osjwnpm/tenetur-ab-corporis/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@osjwnpm/tenetur-ab-corporis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@osjwnpm/tenetur-ab-corporis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@osjwnpm/tenetur-ab-corporis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@osjwnpm/tenetur-ab-corporis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@osjwnpm/tenetur-ab-corporis
