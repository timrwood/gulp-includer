(PLUGIN AUTHOR: Please read [Plugin README conventions](https://github.com/wearefractal/gulp/wiki/Plugin-README-Conventions), then delete this line)

# gulp-includer
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status](coveralls-image)](coveralls-url) [![Dependency Status][depstat-image]][depstat-url]

> includer plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-includer` as a development dependency:

```shell
npm install --save-dev gulp-includer
```

Then, add it to your `gulpfile.js`:

```javascript
var includer = require("gulp-includer");

gulp.src("./src/*.ext")
	.pipe(includer({
		msg: "Hello Gulp!"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### includer(options)

#### options.msg
Type: `String`  
Default: `Hello World`

The message you wish to attach to file.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[npm-url]: https://npmjs.org/package/gulp-includer
[npm-image]: https://badge.fury.io/js/gulp-includer.png

[travis-url]: http://travis-ci.org/timrwood/gulp-includer
[travis-image]: https://secure.travis-ci.org/timrwood/gulp-includer.png?branch=master

[coveralls-url]: https://coveralls.io/r/timrwood/gulp-includer
[coveralls-image]: https://coveralls.io/repos/timrwood/gulp-includer/badge.png

[depstat-url]: https://david-dm.org/timrwood/gulp-includer
[depstat-image]: https://david-dm.org/timrwood/gulp-includer.png
