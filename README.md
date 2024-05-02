# @omegion1npm/eaque-consequuntur-modi <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has Symbol support. Supports spec, or shams.

## Example

```js
var hasSymbols = require('@omegion1npm/eaque-consequuntur-modi');

hasSymbols() === true; // if the environment has native Symbol support. Not polyfillable, not forgeable.

var hasSymbolsKinda = require('@omegion1npm/eaque-consequuntur-modi/shams');
hasSymbolsKinda() === true; // if the environment has a Symbol sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@omegion1npm/eaque-consequuntur-modi
[2]: https://versionbadg.es/inspect-js/@omegion1npm/eaque-consequuntur-modi.svg
[5]: https://david-dm.org/inspect-js/@omegion1npm/eaque-consequuntur-modi.svg
[6]: https://david-dm.org/inspect-js/@omegion1npm/eaque-consequuntur-modi
[7]: https://david-dm.org/inspect-js/@omegion1npm/eaque-consequuntur-modi/dev-status.svg
[8]: https://david-dm.org/inspect-js/@omegion1npm/eaque-consequuntur-modi#info=devDependencies
[11]: https://nodei.co/npm/@omegion1npm/eaque-consequuntur-modi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/eaque-consequuntur-modi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/eaque-consequuntur-modi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/eaque-consequuntur-modi
[codecov-image]: https://codecov.io/gh/inspect-js/@omegion1npm/eaque-consequuntur-modi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@omegion1npm/eaque-consequuntur-modi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@omegion1npm/eaque-consequuntur-modi
[actions-url]: https://github.com/omegion1npm/eaque-consequuntur-modi/actions
