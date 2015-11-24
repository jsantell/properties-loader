# properties-loader
Loader for .properties files for Webpack

[![Build Status](http://img.shields.io/npm/v/properties-loader.svg?style=flat-square)](https://www.npmjs.org/package/properties-loader)

## Installation

`$ npm install properties-loader`

## Usage

The returned module of a properties-loader file is just a simple key value mapping via the [properties](https://www.npmjs.com/package/properties) module.

```.properties
# l10n.properties
greeting.hello=Hello!
```

```js
var L10N = require("properties-loader!./l10n.properties");
console.log(L10N.greeting.hello); // "Hello!"
```

## Testing

TODO

## License

MIT License, Copyright (c) 2015 Jordan Santell
