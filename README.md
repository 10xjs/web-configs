# postcss-shopify

[![NPM version][npm-image]][npm-url]
[![Circle CI](https://circleci.com/gh/Shopify/postcss-shopify.svg?style=shield)](https://circleci.com/gh/Shopify/postcss-shopify)

All of Shopify’s preferred [PostCSS](https://github.com/postcss/postcss) plugins wrapped up in a single, easy-to-use plugin.

## Installation

```bash
yarn add --dev postcss-shopify

# or, with npm

npm i postcss-shopify --save-dev
```

## Features

This plugin wraps around the following PostCSS transformations:

- [`postcss-calc`](https://github.com/postcss/postcss-calc)
- [`postcss-flexbugs-fixes`](https://github.com/luisrudge/postcss-flexbugs-fixes)
- [`postcss-selector-matches`](https://github.com/postcss/postcss-selector-matches)
- [`postcss-will-change`](https://github.com/postcss/postcss-will-change)
- [`autoprefixer`](https://github.com/postcss/autoprefixer)
- [`postcss-discard-comments`](https://github.com/ben-eb/postcss-discard-comments)

## Options

This plugin accepts a single option, `minimize`. Passing `minimize: true` will turn on CSS minification via [cssnano](https://cssnano.co).

[npm-url]: https://npmjs.org/package/postcss-shopify
[npm-image]: http://img.shields.io/npm/v/postcss-shopify.svg?style=shield
