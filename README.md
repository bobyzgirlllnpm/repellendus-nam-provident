# @bobyzgirlllnpm/repellendus-nam-provident <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@bobyzgirlllnpm/repellendus-nam-provident');
const Eval = require('@bobyzgirlllnpm/repellendus-nam-provident/eval');
const Range = require('@bobyzgirlllnpm/repellendus-nam-provident/range');
const Ref = require('@bobyzgirlllnpm/repellendus-nam-provident/ref');
const Syntax = require('@bobyzgirlllnpm/repellendus-nam-provident/syntax');
const Type = require('@bobyzgirlllnpm/repellendus-nam-provident/type');
const URI = require('@bobyzgirlllnpm/repellendus-nam-provident/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/repellendus-nam-provident
[npm-version-svg]: https://versionbadg.es/ljharb/@bobyzgirlllnpm/repellendus-nam-provident.svg
[deps-svg]: https://david-dm.org/ljharb/@bobyzgirlllnpm/repellendus-nam-provident.svg
[deps-url]: https://david-dm.org/ljharb/@bobyzgirlllnpm/repellendus-nam-provident
[dev-deps-svg]: https://david-dm.org/ljharb/@bobyzgirlllnpm/repellendus-nam-provident/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@bobyzgirlllnpm/repellendus-nam-provident#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/repellendus-nam-provident.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/repellendus-nam-provident.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/repellendus-nam-provident.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/repellendus-nam-provident
[codecov-image]: https://codecov.io/gh/ljharb/@bobyzgirlllnpm/repellendus-nam-provident/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@bobyzgirlllnpm/repellendus-nam-provident/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@bobyzgirlllnpm/repellendus-nam-provident
[actions-url]: https://github.com/bobyzgirlllnpm/repellendus-nam-provident/actions
