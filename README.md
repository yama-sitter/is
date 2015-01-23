# Is.js
"Is" is the method that make a determination of the type of the object strictly.

## Synopsis
It possible to determine the following type.
- String
- Number
- Array
- Object
- Boolean
- Undefined
- Null

## Usage
    var bool = is('Boolean', true); // true
    var arr = is('Array', 'text'); // false

    if (is('Object', {})) {
      // true
    }

### Node
    var is = require('./is');

### Browser
    <script type="text/javascript" src="is.js"></script>

### Test
    $ npm install
    $ npm test // run jshint & mocha
