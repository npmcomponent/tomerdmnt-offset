*This repository is a mirror of the [component](http://component.io) module [tomerdmnt/offset](http://github.com/tomerdmnt/offset). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/tomerdmnt-offset`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# offset

  Get element offset

  ```javascript
var offset = require('offset');

var o = offset(document.querySelector('div'));
console.log('x: ' + o.x);
console.log('y: ' + o.y);
  ```

## Installation

    $ component install tomerdmnt/offset

## API

### offset(el)
gets an element. returns an object with properties x and y.

## License

  MIT
