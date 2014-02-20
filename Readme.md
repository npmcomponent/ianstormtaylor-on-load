*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/on-load](http://github.com/ianstormtaylor/on-load). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-on-load`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# load

  Callback when the document has loaded.

## Installation

    $ component install ianstormtaylor/on-load

## Example
  
```js
var onLoad = require('on-load');

onLoad(function () {
  console.log('load');
});
```

## API

### onLoad(handler)

  Call a `handler` when the document is loaded, calling on next tick if the document is already loaded.

## License

  MIT
