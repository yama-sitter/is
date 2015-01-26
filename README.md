# Is.js
"Is" is the method that make a determination of the type of the object strictly.

## SYNOPSIS
It possible to determine the following type.
- String
- Number
- Array
- Object
- Boolean
- Undefined
- Null

## USAGE
    var bool = is('Boolean', true); // true
    var arr = is('Array', 'text'); // false

    if (is('Object', {})) {
      // true
    }

### Node
    var is = require('./is');

### Browser
    <script type="text/javascript" src="is.js"></script>

## OTHERS
### Set node modules path

    $ npm start // Export path of node modules.

### How to test

    $ npm test // Run jshint & mocha.
