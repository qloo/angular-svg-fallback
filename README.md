[![Build Status](https://travis-ci.org/qloo/angular-svg-fallback.png)](https://travis-ci.org/qloo/angular-svg-fallback)

# AngularJS SVG Fallback Module

Provides a mechanism for SVG(Z) fallback to bitmap images.  
http://qloo.github.io/angular-svg-fallback/  
https://github.com/qloo/angular-svg-fallback/

## Stability

```
Stability: 3 - Stable
```

For more information you can view the Node.js [stability index](http://nodejs.org/api/all.html#all_stability_index).

## Build

To install all the necessary dependencies for the the example you'll need to run the following commands:

```
$ npm install -g grunt-cli && npm install && grunt bootstrap
```

If you have problems with [Grunt](http://gruntjs.com/) you may need to [uninstall a previously installed version](http://gruntjs.com/getting-started), you may also need to run the `grunt-cli` installation using `sudo`.

This will ensure that all of the necessary node and bower modules are installed, documentation is built, and the example has been bootstrapped.

## Web Server for the Example Application

You can run the test server with the following command:

```
$ grunt server
```

## Tests

It is important that you have already run the `grunt bootstrap` task before testing.

```
grunt test
```

### Unit

```
grunt test:unit
```

### End to End

```
grunt test:e2e
```

### Continuous Integration Unit

```
grunt cont:unit
```

### Continuous Integration e2e

```
grunt cont:e2e

## More Grunt Tasks

To LINT the JS:

```
grunt lint
```

To run unit tests and LINT the JS

```
grunt check
```

Build documentation:

```
grunt doc
```

Cleanup:

```
grunt clean
```

Lint, documentation, bootstrap, and test:

```
grunt
```

## License

Copyright (c) 2013 Qloo Inc., Michael Diolosa <[michael.diolosa@gmail.com](mailto:michael.diolosa@gmail.com)>

This library is licensed under the [MIT license](http://opensource.org/licenses/MIT).
