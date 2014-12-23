# rtcninja.js

**TODO:** Not yet done!

WebRTC library to make media management easier across different browsers.


## Installation

* With **npm**:
```bash
$ npm install rtcninja
```


## Usage in Node

```bash
$ npm install rtcninja
```

```javascript
var rtcninja = require('rtcninja');
```


## Browserified library

Take a browserified version of the library from the `dist/` folder:

* `dist/rtcninja-X.Y.Z.js`: The uncompressed version.
* `dist/rtcninja-X.Y.Z.min.js`: The compressed production-ready version.

They expose the global `window.rtcninja` module.


## Debugging

The library includes the Node [debug](https://github.com/visionmedia/debug) module. In order to enable debugging:

In Node set the `DEBUG=rtcninja*` environment variable before running the application, or set it at the top of the script:

```javascript
    process.env.DEBUG = 'rtcninja*';
```

In the browser run `rtcninja.debug.enable('rtcninja*');` and reload the page. Note that the debugging settings are stored into the browser LocalStorage. To disable it run `rtcninja.debug.disable('rtcninja*');`.


## Documentation

*TODO*


## Author

Iñaki Baz Castillo.


## License

ISC.
