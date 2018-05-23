# check-is-empty-js

A Node.js package that checks whether a given string is null or empty. Install it and use it.
## Usage

First, install the package using npm:

    npm install check-is-empty-js --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('check-is-empty-js');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT