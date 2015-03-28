# Binary loader for webpack

Adapted from [raw loader](https://github.com/webpack/raw-loader).

## Installation

`npm install binary-loader`

## Usage

``` javascript
var fileContent = require("binary!./file.bin");
// => returns file.bin content as binary string
```

[Documentation: Using loaders](http://webpack.github.io/docs/using-loaders.html)

## License

MIT (http://www.opensource.org/licenses/mit-license.php)
