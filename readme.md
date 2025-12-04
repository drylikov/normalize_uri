




# Normalize uri 





[![Build][build-badge]][build]
[![Coverage][coverage-badge]][coverage]
[![Downloads][downloads-badge]][downloads]
[![Size][size-badge]][size]

Normalize a URI.





## Install





This package is ESM only: Node 12+ is needed to use it and it must be `import`ed
instead of `require`d.

[npm][]:

```sh
npm install normalize_uri
```

## Use

```js
import {normalizeUri} from 'normalize_uri'

normalizeUri('foo bar') // => 'foo%20bar'
normalizeUri('foo%20bar') // => 'foo%20bar'
normalizeUri('👌') // => '%F0%9F%91%8C'
```





## API

This package exports the following identifiers: `normalizeUri`.
There is no default export.

### `normalizeUri(value)`

Normalize `uri`.
This only works when both `encodeURI` and `decodeURI` are available.


<!-- Definitions -->

[build-badge]: https://github.com/drylikov/`normalize_uri/workflows/main/badge.svg

[build]: https://github.com/drylikov/normalize_uri/actions

[coverage-badge]: https://img.shields.io/codecov/c/github/drylikov/normalize_uri.svg

[coverage]: https://codecov.io/github/drylikov/normalize_uri

[downloads-badge]: https://img.shields.io/npm/dm/normalize_uri.svg

[downloads]: https://www.npmjs.com/package/normalize_uri

[size-badge]: https://img.shields.io/bundlephobia/minzip/normalize_uri.svg

[size]: https://bundlephobia.com/result?p=normalize_uri

[npm]: https://docs.npmjs.com/cli/install
