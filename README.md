# babel-preset-latest-node5 (DEPRECATED)
[![Dependency Status][depstat-image]][depstat-url]

> Babel preset including es2015, es2016, es2017 for Node.js 5.

**DEPRECATED: Use [babel-preset-env](https://github.com/babel/babel-preset-env) instead**

## Install

```bash
$ npm install --save-dev babel-preset-latest-node5
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["latest-node5"]
}
```

### Via CLI

```bash
$ babel script.js --presets latest-node5
```

### Via Node API

```js
require('babel-core').transform('code', {
  presets: ['latest-node5']
});
```

## License

[MIT](LICENSE.md) © [Timofey Dergachev](https://exeto.me/)

[depstat-url]: https://david-dm.org/exeto/babel-preset-latest-node5#info=Dependencies
[depstat-image]: https://img.shields.io/david/exeto/babel-preset-latest-node5.svg?style=flat-square
