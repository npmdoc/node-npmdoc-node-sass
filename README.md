# api documentation for  [node-sass (v4.5.1)](https://github.com/sass/node-sass)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-sass.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-sass)
#### Wrapper around libsass

[![NPM](https://nodei.co/npm/node-sass.png?downloads=true)](https://www.npmjs.com/package/node-sass)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-sass/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-sass_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-sass/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-node-sass/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Nesbitt",
        "email": "andrewnez@gmail.com",
        "url": "http://andrew.github.com"
    },
    "bin": {
        "node-sass": "bin/node-sass"
    },
    "bugs": {
        "url": "https://github.com/sass/node-sass/issues"
    },
    "dependencies": {
        "async-foreach": "^0.1.3",
        "chalk": "^1.1.1",
        "cross-spawn": "^3.0.0",
        "gaze": "^1.0.0",
        "get-stdin": "^4.0.1",
        "glob": "^7.0.3",
        "in-publish": "^2.0.0",
        "lodash.assign": "^4.2.0",
        "lodash.clonedeep": "^4.3.2",
        "lodash.mergewith": "^4.6.0",
        "meow": "^3.7.0",
        "mkdirp": "^0.5.1",
        "nan": "^2.3.2",
        "node-gyp": "^3.3.1",
        "npmlog": "^4.0.0",
        "request": "^2.79.0",
        "sass-graph": "^2.1.1",
        "stdout-stream": "^1.4.0"
    },
    "description": "Wrapper around libsass",
    "devDependencies": {
        "coveralls": "^2.11.8",
        "eslint": "^3.4.0",
        "istanbul": "^0.4.2",
        "mocha": "^3.1.2",
        "mocha-lcov-reporter": "^1.2.0",
        "object-merge": "^2.5.1",
        "read-yaml": "^1.0.0",
        "rimraf": "^2.5.2",
        "sass-spec": "3.5.0-1"
    },
    "directories": {},
    "dist": {
        "shasum": "e8e119fe3c8213ad7e56ca618dd231e9e8b30f5b",
        "tarball": "https://registry.npmjs.org/node-sass/-/node-sass-4.5.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "bin",
        "binding.gyp",
        "lib",
        "scripts",
        "src",
        "test",
        "vendor"
    ],
    "gitHead": "f2b410b7ffecb8b48b11e59b2ce2aa9601367112",
    "gypfile": true,
    "homepage": "https://github.com/sass/node-sass",
    "keywords": [
        "css",
        "libsass",
        "preprocessor",
        "sass",
        "scss",
        "style"
    ],
    "libsass": "3.5.0.beta.2",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "am11",
            "email": "adeelbm@outlook.com"
        },
        {
            "name": "andrewnez",
            "email": "andrewnez@gmail.com"
        },
        {
            "name": "deanmao",
            "email": "deanmao@gmail.com"
        },
        {
            "name": "keithamus",
            "email": "npm@keithcirkel.co.uk"
        },
        {
            "name": "laurentgoderre",
            "email": "laurent.goderre@gmail.com"
        },
        {
            "name": "saperski",
            "email": "npm@saper.info"
        },
        {
            "name": "xzyfer",
            "email": "xzyfer@gmail.com"
        }
    ],
    "name": "node-sass",
    "nodeSassConfig": {
        "binarySite": "https://github.com/sass/node-sass/releases/download"
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sass/node-sass.git"
    },
    "scripts": {
        "build": "node scripts/build.js --force",
        "coverage": "node scripts/coverage.js",
        "install": "node scripts/install.js",
        "lint": "eslint bin/node-sass lib scripts test",
        "postinstall": "node scripts/build.js",
        "prepublish": "not-in-install && node scripts/prepublish.js || in-install",
        "test": "mocha test/{*,**/**}.js"
    },
    "version": "4.5.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-sass](#apidoc.module.node-sass)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>render (opts, cb)](#apidoc.element.node-sass.render)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>renderSync (opts)](#apidoc.element.node-sass.renderSync)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>types.Boolean ()](#apidoc.element.node-sass.types.Boolean)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>types.Color ()](#apidoc.element.node-sass.types.Color)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>types.List ()](#apidoc.element.node-sass.types.List)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>types.Map ()](#apidoc.element.node-sass.types.Map)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>types.Number ()](#apidoc.element.node-sass.types.Number)
1.  [function <span class="apidocSignatureSpan">node-sass.</span>types.String ()](#apidoc.element.node-sass.types.String)
1.  object <span class="apidocSignatureSpan">node-sass.</span>FALSE
1.  object <span class="apidocSignatureSpan">node-sass.</span>NULL
1.  object <span class="apidocSignatureSpan">node-sass.</span>TRUE
1.  object <span class="apidocSignatureSpan">node-sass.</span>errors
1.  object <span class="apidocSignatureSpan">node-sass.</span>extensions
1.  object <span class="apidocSignatureSpan">node-sass.</span>types
1.  object <span class="apidocSignatureSpan">node-sass.</span>types.Boolean.prototype
1.  object <span class="apidocSignatureSpan">node-sass.</span>types.Color.prototype
1.  object <span class="apidocSignatureSpan">node-sass.</span>types.List.prototype
1.  object <span class="apidocSignatureSpan">node-sass.</span>types.Map.prototype
1.  object <span class="apidocSignatureSpan">node-sass.</span>types.Number.prototype
1.  object <span class="apidocSignatureSpan">node-sass.</span>types.String.prototype
1.  string <span class="apidocSignatureSpan">node-sass.</span>info

#### [module node-sass.errors](#apidoc.module.node-sass.errors)
1.  [function <span class="apidocSignatureSpan">node-sass.errors.</span>missingBinary ()](#apidoc.element.node-sass.errors.missingBinary)
1.  [function <span class="apidocSignatureSpan">node-sass.errors.</span>unsupportedEnvironment ()](#apidoc.element.node-sass.errors.unsupportedEnvironment)

#### [module node-sass.extensions](#apidoc.module.node-sass.extensions)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryCachePath ()](#apidoc.element.node-sass.extensions.getBinaryCachePath)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryName ()](#apidoc.element.node-sass.extensions.getBinaryName)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryPath ()](#apidoc.element.node-sass.extensions.getBinaryPath)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryUrl ()](#apidoc.element.node-sass.extensions.getBinaryUrl)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getCachePathCandidates ()](#apidoc.element.node-sass.extensions.getCachePathCandidates)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getCachedBinary ()](#apidoc.element.node-sass.extensions.getCachedBinary)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getHumanEnvironment (env)](#apidoc.element.node-sass.extensions.getHumanEnvironment)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getInstalledBinaries ()](#apidoc.element.node-sass.extensions.getInstalledBinaries)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>getVersionInfo (binding)](#apidoc.element.node-sass.extensions.getVersionInfo)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>hasBinary (binaryPath)](#apidoc.element.node-sass.extensions.hasBinary)
1.  [function <span class="apidocSignatureSpan">node-sass.extensions.</span>isSupportedEnvironment (platform, arch, abi)](#apidoc.element.node-sass.extensions.isSupportedEnvironment)

#### [module node-sass.types](#apidoc.module.node-sass.types)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Boolean ()](#apidoc.element.node-sass.types.Boolean)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Color ()](#apidoc.element.node-sass.types.Color)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Error ()](#apidoc.element.node-sass.types.Error)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>List ()](#apidoc.element.node-sass.types.List)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Map ()](#apidoc.element.node-sass.types.Map)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Null ()](#apidoc.element.node-sass.types.Null)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Number ()](#apidoc.element.node-sass.types.Number)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>String ()](#apidoc.element.node-sass.types.String)

#### [module node-sass.types.Boolean](#apidoc.module.node-sass.types.Boolean)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Boolean ()](#apidoc.element.node-sass.types.Boolean.Boolean)
1.  object <span class="apidocSignatureSpan">node-sass.types.Boolean.</span>FALSE
1.  object <span class="apidocSignatureSpan">node-sass.types.Boolean.</span>TRUE

#### [module node-sass.types.Boolean.prototype](#apidoc.module.node-sass.types.Boolean.prototype)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Boolean.prototype.</span>getValue ()](#apidoc.element.node-sass.types.Boolean.prototype.getValue)

#### [module node-sass.types.Color](#apidoc.module.node-sass.types.Color)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Color ()](#apidoc.element.node-sass.types.Color.Color)

#### [module node-sass.types.Color.prototype](#apidoc.module.node-sass.types.Color.prototype)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getA ()](#apidoc.element.node-sass.types.Color.prototype.getA)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getB ()](#apidoc.element.node-sass.types.Color.prototype.getB)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getG ()](#apidoc.element.node-sass.types.Color.prototype.getG)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getR ()](#apidoc.element.node-sass.types.Color.prototype.getR)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setA ()](#apidoc.element.node-sass.types.Color.prototype.setA)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setB ()](#apidoc.element.node-sass.types.Color.prototype.setB)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setG ()](#apidoc.element.node-sass.types.Color.prototype.setG)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setR ()](#apidoc.element.node-sass.types.Color.prototype.setR)

#### [module node-sass.types.List](#apidoc.module.node-sass.types.List)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>List ()](#apidoc.element.node-sass.types.List.List)

#### [module node-sass.types.List.prototype](#apidoc.module.node-sass.types.List.prototype)
1.  [function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>getLength ()](#apidoc.element.node-sass.types.List.prototype.getLength)
1.  [function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>getSeparator ()](#apidoc.element.node-sass.types.List.prototype.getSeparator)
1.  [function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>getValue ()](#apidoc.element.node-sass.types.List.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>setSeparator ()](#apidoc.element.node-sass.types.List.prototype.setSeparator)
1.  [function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>setValue ()](#apidoc.element.node-sass.types.List.prototype.setValue)

#### [module node-sass.types.Map](#apidoc.module.node-sass.types.Map)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Map ()](#apidoc.element.node-sass.types.Map.Map)

#### [module node-sass.types.Map.prototype](#apidoc.module.node-sass.types.Map.prototype)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>getKey ()](#apidoc.element.node-sass.types.Map.prototype.getKey)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>getLength ()](#apidoc.element.node-sass.types.Map.prototype.getLength)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>getValue ()](#apidoc.element.node-sass.types.Map.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>setKey ()](#apidoc.element.node-sass.types.Map.prototype.setKey)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>setValue ()](#apidoc.element.node-sass.types.Map.prototype.setValue)

#### [module node-sass.types.Number](#apidoc.module.node-sass.types.Number)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>Number ()](#apidoc.element.node-sass.types.Number.Number)

#### [module node-sass.types.Number.prototype](#apidoc.module.node-sass.types.Number.prototype)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>getUnit ()](#apidoc.element.node-sass.types.Number.prototype.getUnit)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>getValue ()](#apidoc.element.node-sass.types.Number.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>setUnit ()](#apidoc.element.node-sass.types.Number.prototype.setUnit)
1.  [function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>setValue ()](#apidoc.element.node-sass.types.Number.prototype.setValue)

#### [module node-sass.types.String](#apidoc.module.node-sass.types.String)
1.  [function <span class="apidocSignatureSpan">node-sass.types.</span>String ()](#apidoc.element.node-sass.types.String.String)

#### [module node-sass.types.String.prototype](#apidoc.module.node-sass.types.String.prototype)
1.  [function <span class="apidocSignatureSpan">node-sass.types.String.prototype.</span>getValue ()](#apidoc.element.node-sass.types.String.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">node-sass.types.String.prototype.</span>setValue ()](#apidoc.element.node-sass.types.String.prototype.setValue)



# <a name="apidoc.module.node-sass"></a>[module node-sass](#apidoc.module.node-sass)

#### <a name="apidoc.element.node-sass.render"></a>[function <span class="apidocSignatureSpan">node-sass.</span>render (opts, cb)](#apidoc.element.node-sass.render)
- description and source-code
```javascript
render = function (opts, cb) {
  var options = getOptions(opts, cb);

  // options.error and options.success are for libsass binding
  options.error = function(err) {
    var payload = assign(new Error(), JSON.parse(err));

    if (cb) {
      options.context.callback.call(options.context, payload, null);
    }
  };

  options.success = function() {
    var result = options.result;
    var stats = endStats(result.stats);
    var payload = {
      css: result.css,
      map: result.map,
      stats: stats
    };

    if (cb) {
      options.context.callback.call(options.context, null, payload);
    }
  };

  var importer = options.importer;

  if (importer) {
    if (Array.isArray(importer)) {
      options.importer = [];
      importer.forEach(function(subject, index) {
        options.importer[index] = function(file, prev, bridge) {
          function done(result) {
            bridge.success(result === module.exports.NULL ? null : result);
          }

          var result = subject.call(options.context, file, prev, done);

          if (result !== undefined) {
            done(result);
          }
        };
      });
    } else {
      options.importer = function(file, prev, bridge) {
        function done(result) {
          bridge.success(result === module.exports.NULL ? null : result);
        }

        var result = importer.call(options.context, file, prev, done);

        if (result !== undefined) {
          done(result);
        }
      };
    }
  }

  var functions = clonedeep(options.functions);

  if (functions) {
    options.functions = {};

    Object.keys(functions).forEach(function(subject) {
      var cb = normalizeFunctionSignature(subject, functions[subject]);

      options.functions[cb.signature] = function() {
        var args = Array.prototype.slice.call(arguments),
          bridge = args.pop();

        function done(data) {
          bridge.success(data);
        }

        var result = tryCallback(cb.callback.bind(options.context), args.concat(done));

        if (result) {
          done(result);
        }
      };
    });
  }

  if (options.data) {
    binding.render(options);
  } else if (options.file) {
    binding.renderFile(options);
  } else {
    cb({status: 3, message: 'No input specified: provide a file name or a source string to process' });
  }
}
```
- example usage
```shell
...

**Having installation troubles? Check out our [Troubleshooting guide](/TROUBLESHOOTING.md).**

## Usage

'''javascript
var sass = require('node-sass');
sass.render({
file: scss_filename,
[, options..]
}, function(err, result) { /*...*/ });
// OR
var result = sass.renderSync({
data: scss_content
[, options..]
...
```

#### <a name="apidoc.element.node-sass.renderSync"></a>[function <span class="apidocSignatureSpan">node-sass.</span>renderSync (opts)](#apidoc.element.node-sass.renderSync)
- description and source-code
```javascript
renderSync = function (opts) {
  var options = getOptions(opts);
  var importer = options.importer;

  if (importer) {
    if (Array.isArray(importer)) {
      options.importer = [];
      importer.forEach(function(subject, index) {
        options.importer[index] = function(file, prev) {
          var result = subject.call(options.context, file, prev);

          return result === module.exports.NULL ? null : result;
        };
      });
    } else {
      options.importer = function(file, prev) {
        var result = importer.call(options.context, file, prev);

        return result === module.exports.NULL ? null : result;
      };
    }
  }

  var functions = clonedeep(options.functions);

  if (options.functions) {
    options.functions = {};

    Object.keys(functions).forEach(function(signature) {
      var cb = normalizeFunctionSignature(signature, functions[signature]);

      options.functions[cb.signature] = function() {
        return tryCallback(cb.callback.bind(options.context), arguments);
      };
    });
  }

  var status;
  if (options.data) {
    status = binding.renderSync(options);
  } else if (options.file) {
    status = binding.renderFileSync(options);
  } else {
    throw new Error('No input specified: provide a file name or a source string to process');
  }

  var result = options.result;

  if (status) {
    result.stats = endStats(result.stats);
    return result;
  }

  throw assign(new Error(), JSON.parse(result.error));
}
```
- example usage
```shell
...
'''javascript
var sass = require('node-sass');
sass.render({
  file: scss_filename,
  [, options..]
}, function(err, result) { /*...*/ });
// OR
var result = sass.renderSync({
  data: scss_content
  [, options..]
});
'''

## Options
### file
...
```

#### <a name="apidoc.element.node-sass.types.Boolean"></a>[function <span class="apidocSignatureSpan">node-sass.</span>types.Boolean ()](#apidoc.element.node-sass.types.Boolean)
- description and source-code
```javascript
function SassBoolean() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color"></a>[function <span class="apidocSignatureSpan">node-sass.</span>types.Color ()](#apidoc.element.node-sass.types.Color)
- description and source-code
```javascript
function SassColor() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.List"></a>[function <span class="apidocSignatureSpan">node-sass.</span>types.List ()](#apidoc.element.node-sass.types.List)
- description and source-code
```javascript
function SassList() { [native code] }
```
- example usage
```shell
...

'''javascript
sass.renderSync({
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
'headings($from: 0, $to: 6)': function(from, to) {
  var i, f = from.getValue(), t = to.getValue(),
      list = new sass.types.List(t - f + 1);

  for (i = f; i <= t; i++) {
    list.setValue(i - f, new sass.types.String('h' + i));
  }

  return list;
}
...
```

#### <a name="apidoc.element.node-sass.types.Map"></a>[function <span class="apidocSignatureSpan">node-sass.</span>types.Map ()](#apidoc.element.node-sass.types.Map)
- description and source-code
```javascript
function SassMap() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Number"></a>[function <span class="apidocSignatureSpan">node-sass.</span>types.Number ()](#apidoc.element.node-sass.types.Number)
- description and source-code
```javascript
function SassNumber() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.String"></a>[function <span class="apidocSignatureSpan">node-sass.</span>types.String ()](#apidoc.element.node-sass.types.String)
- description and source-code
```javascript
function SassString() { [native code] }
```
- example usage
```shell
...
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
      var i, f = from.getValue(), t = to.getValue(),
          list = new sass.types.List(t - f + 1);

      for (i = f; i <= t; i++) {
        list.setValue(i - f, new sass.types.String('h' + i));
      }

      return list;
    }
  }
});
'''
...
```



# <a name="apidoc.module.node-sass.errors"></a>[module node-sass.errors](#apidoc.module.node-sass.errors)

#### <a name="apidoc.element.node-sass.errors.missingBinary"></a>[function <span class="apidocSignatureSpan">node-sass.errors.</span>missingBinary ()](#apidoc.element.node-sass.errors.missingBinary)
- description and source-code
```javascript
missingBinary = function () {
  return [
    'Missing binding ' + sass.getBinaryPath(),
    'Node Sass could not find a binding for your current environment: ' + humanEnvironment(),
    '',
    foundBinaries(),
    '',
    missingBinaryFooter(),
  ].join('\n');
}
```
- example usage
```shell
...
 * Require binding
 */
module.exports = function(ext) {
  if (!ext.hasBinary(ext.getBinaryPath())) {
    if (!ext.isSupportedEnvironment()) {
      throw new Error(errors.unsupportedEnvironment());
    } else {
      throw new Error(errors.missingBinary());
    }
  }

  return require(ext.getBinaryPath());
};
...
```

#### <a name="apidoc.element.node-sass.errors.unsupportedEnvironment"></a>[function <span class="apidocSignatureSpan">node-sass.errors.</span>unsupportedEnvironment ()](#apidoc.element.node-sass.errors.unsupportedEnvironment)
- description and source-code
```javascript
unsupportedEnvironment = function () {
  return [
    'Node Sass does not yet support your current environment: ' + humanEnvironment(),
    'For more information on which environments are supported please see:',
    'https://github.com/sass/node-sass/releases/tag/v' + pkg.version
  ].join('\n');
}
```
- example usage
```shell
...

/**
 * Require binding
 */
module.exports = function(ext) {
  if (!ext.hasBinary(ext.getBinaryPath())) {
    if (!ext.isSupportedEnvironment()) {
      throw new Error(errors.unsupportedEnvironment());
    } else {
      throw new Error(errors.missingBinary());
    }
  }

  return require(ext.getBinaryPath());
};
...
```



# <a name="apidoc.module.node-sass.extensions"></a>[module node-sass.extensions](#apidoc.module.node-sass.extensions)

#### <a name="apidoc.element.node-sass.extensions.getBinaryCachePath"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryCachePath ()](#apidoc.element.node-sass.extensions.getBinaryCachePath)
- description and source-code
```javascript
function getBinaryCachePath() {
  var i,
    cachePath,
    cachePathCandidates = getCachePathCandidates();

  for (i = 0; i < cachePathCandidates.length; i++) {
    cachePath = path.join(cachePathCandidates[i], pkg.name, pkg.version);

    try {
      mkdir.sync(cachePath);
      return cachePath;
    } catch (e) {
      // Directory is not writable, try another
    }
  }

  return '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.extensions.getBinaryName"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryName ()](#apidoc.element.node-sass.extensions.getBinaryName)
- description and source-code
```javascript
function getBinaryName() {
  var binaryName,
    variant,
    platform = process.platform;

  if (getArgument('--sass-binary-name')) {
    binaryName = getArgument('--sass-binary-name');
  } else if (process.env.SASS_BINARY_NAME) {
    binaryName = process.env.SASS_BINARY_NAME;
  } else if (process.env.npm_config_sass_binary_name) {
    binaryName = process.env.npm_config_sass_binary_name;
  } else if (pkg.nodeSassConfig && pkg.nodeSassConfig.binaryName) {
    binaryName = pkg.nodeSassConfig.binaryName;
  } else {
    variant = getPlatformVariant();
    if (variant) {
      platform += '_' + variant;
    }

    binaryName = [
      platform, '-',
      process.arch, '-',
      process.versions.modules
    ].join('');
  }

  return [binaryName, 'binding.node'].join('_');
}
```
- example usage
```shell
...
 * node-sass: lib/errors.js
 */

var sass = require('./extensions'),
pkg = require('../package.json');

function humanEnvironment() {
return sass.getHumanEnvironment(sass.getBinaryName());
}

function foundBinaries() {
return [
  'Found bindings for the following environments:',
  foundBinariesList(),
].join('\n');
...
```

#### <a name="apidoc.element.node-sass.extensions.getBinaryPath"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryPath ()](#apidoc.element.node-sass.extensions.getBinaryPath)
- description and source-code
```javascript
function getBinaryPath() {
  var binaryPath;

  if (getArgument('--sass-binary-path')) {
    binaryPath = getArgument('--sass-binary-path');
  } else if (process.env.SASS_BINARY_PATH) {
    binaryPath = process.env.SASS_BINARY_PATH;
  } else if (process.env.npm_config_sass_binary_path) {
    binaryPath = process.env.npm_config_sass_binary_path;
  } else if (pkg.nodeSassConfig && pkg.nodeSassConfig.binaryPath) {
    binaryPath = pkg.nodeSassConfig.binaryPath;
  } else {
    binaryPath = path.join(defaultBinaryPath, getBinaryName().replace(/_(?=binding\.node)/, '/'));
  }

  return binaryPath;
}
```
- example usage
```shell
...

var errors = require('./errors');

/**
 * Require binding
 */
module.exports = function(ext) {
if (!ext.hasBinary(ext.getBinaryPath())) {
  if (!ext.isSupportedEnvironment()) {
    throw new Error(errors.unsupportedEnvironment());
  } else {
    throw new Error(errors.missingBinary());
  }
}
...
```

#### <a name="apidoc.element.node-sass.extensions.getBinaryUrl"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getBinaryUrl ()](#apidoc.element.node-sass.extensions.getBinaryUrl)
- description and source-code
```javascript
function getBinaryUrl() {
  var site = getArgument('--sass-binary-site') ||
             process.env.SASS_BINARY_SITE  ||
             process.env.npm_config_sass_binary_site ||
             (pkg.nodeSassConfig && pkg.nodeSassConfig.binarySite) ||
             'https://github.com/sass/node-sass/releases/download';

  return [site, 'v' + pkg.version, getBinaryName()].join('/');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.extensions.getCachePathCandidates"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getCachePathCandidates ()](#apidoc.element.node-sass.extensions.getCachePathCandidates)
- description and source-code
```javascript
function getCachePathCandidates() {
  return [
    process.env.npm_config_sass_binary_cache,
    process.env.npm_config_cache,
  ].filter(function(_) { return _; });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.extensions.getCachedBinary"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getCachedBinary ()](#apidoc.element.node-sass.extensions.getCachedBinary)
- description and source-code
```javascript
function getCachedBinary() {
  var i,
    cachePath,
    cacheBinary,
    cachePathCandidates = getCachePathCandidates(),
    binaryName = getBinaryName();

  for (i = 0; i < cachePathCandidates.length; i++) {
    cachePath = path.join(cachePathCandidates[i], pkg.name, pkg.version);
    cacheBinary = path.join(cachePath, binaryName);

    if (fs.existsSync(cacheBinary)) {
      return cacheBinary;
    }
  }

  return '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.extensions.getHumanEnvironment"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getHumanEnvironment (env)](#apidoc.element.node-sass.extensions.getHumanEnvironment)
- description and source-code
```javascript
function getHumanEnvironment(env) {
  var binding = env.replace(/_binding\.node$/, ''),
    parts = binding.split('-'),
    platform = getHumanPlatform(parts[0]),
    arch = getHumanArchitecture(parts[1]),
    runtime = getHumanNodeVersion(parts[2]);

  if (parts.length !== 3) {
    return 'Unknown environment (' + binding + ')';
  }

  if (!platform) {
    platform = 'Unsupported platform (' + parts[0] + ')';
  }

  if (!arch) {
    arch = 'Unsupported architecture (' + parts[1] + ')';
  }

  if (!runtime) {
    runtime = 'Unsupported runtime (' + parts[2] + ')';
  }

  return [
    platform, arch, 'with', runtime,
  ].join(' ');
}
```
- example usage
```shell
...
 * node-sass: lib/errors.js
 */

var sass = require('./extensions'),
pkg = require('../package.json');

function humanEnvironment() {
return sass.getHumanEnvironment(sass.getBinaryName());
}

function foundBinaries() {
return [
  'Found bindings for the following environments:',
  foundBinariesList(),
].join('\n');
...
```

#### <a name="apidoc.element.node-sass.extensions.getInstalledBinaries"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getInstalledBinaries ()](#apidoc.element.node-sass.extensions.getInstalledBinaries)
- description and source-code
```javascript
function getInstalledBinaries() {
  return fs.readdirSync(defaultBinaryPath);
}
```
- example usage
```shell
...
return [
  'Found bindings for the following environments:',
  foundBinariesList(),
].join('\n');
}

function foundBinariesList() {
return sass.getInstalledBinaries().map(function(env) {
  return '  - ' + sass.getHumanEnvironment(env);
}).join('\n');
}

function missingBinaryFooter() {
return [
  'This usually happens because your environment has changed since running 'npm install'.',
...
```

#### <a name="apidoc.element.node-sass.extensions.getVersionInfo"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>getVersionInfo (binding)](#apidoc.element.node-sass.extensions.getVersionInfo)
- description and source-code
```javascript
function getVersionInfo(binding) {
  return [
    ['node-sass', pkg.version, '(Wrapper)', '[JavaScript]'].join('\t'),
    ['libsass  ', binding.libsassVersion(), '(Sass Compiler)', '[C/C++]'].join('\t'),
  ].join(eol);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.extensions.hasBinary"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>hasBinary (binaryPath)](#apidoc.element.node-sass.extensions.hasBinary)
- description and source-code
```javascript
function hasBinary(binaryPath) {
  return fs.existsSync(binaryPath);
}
```
- example usage
```shell
...

var errors = require('./errors');

/**
 * Require binding
 */
module.exports = function(ext) {
if (!ext.hasBinary(ext.getBinaryPath())) {
  if (!ext.isSupportedEnvironment()) {
    throw new Error(errors.unsupportedEnvironment());
  } else {
    throw new Error(errors.missingBinary());
  }
}
...
```

#### <a name="apidoc.element.node-sass.extensions.isSupportedEnvironment"></a>[function <span class="apidocSignatureSpan">node-sass.extensions.</span>isSupportedEnvironment (platform, arch, abi)](#apidoc.element.node-sass.extensions.isSupportedEnvironment)
- description and source-code
```javascript
function isSupportedEnvironment(platform, arch, abi) {
  return (
    false !== getHumanPlatform(platform) &&
    false !== getHumanArchitecture(arch) &&
    false !== getHumanNodeVersion(abi)
  );
}
```
- example usage
```shell
...
var errors = require('./errors');

/**
 * Require binding
 */
module.exports = function(ext) {
if (!ext.hasBinary(ext.getBinaryPath())) {
  if (!ext.isSupportedEnvironment()) {
    throw new Error(errors.unsupportedEnvironment());
  } else {
    throw new Error(errors.missingBinary());
  }
}

return require(ext.getBinaryPath());
...
```



# <a name="apidoc.module.node-sass.types"></a>[module node-sass.types](#apidoc.module.node-sass.types)

#### <a name="apidoc.element.node-sass.types.Boolean"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Boolean ()](#apidoc.element.node-sass.types.Boolean)
- description and source-code
```javascript
function SassBoolean() { [native code] }
```
- example usage
```shell
...

'''javascript
var Color = require('node-sass').types.Color,
  c1 = new Color(255, 0, 0),
  c2 = new Color(0xff0088cc);
'''

#### types.Boolean(value)
* 'getValue()' : gets the enclosed boolean
* 'types.Boolean.TRUE' : Singleton instance of 'types.Boolean' that holds "true"
* 'types.Boolean.FALSE' : Singleton instance of 'types.Boolean' that holds "false"

#### types.List(length [, commaSeparator = true])
* 'getValue(index)' / 'setValue(index, value)' : 'value' must itself be an instance of one of the constructors in 'sass.types'.
* 'getSeparator()' / 'setSeparator(isComma)' : whether to use commas as a separator
...
```

#### <a name="apidoc.element.node-sass.types.Color"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Color ()](#apidoc.element.node-sass.types.Color)
- description and source-code
```javascript
function SassColor() { [native code] }
```
- example usage
```shell
...
#### types.Number(value [, unit = ""])
* 'getValue()'/ 'setValue(value)' : gets / sets the numerical portion of the number
* 'getUnit()' / 'setUnit(unit)' : gets / sets the unit portion of the number

#### types.String(value)
* 'getValue()' / 'setValue(value)' : gets / sets the enclosed string

#### types.Color(r, g, b [, a = 1.0]) or types.Color(argb)
* 'getR()' / 'setR(value)' : red component (integer from '0' to '255')
* 'getG()' / 'setG(value)' : green component (integer from '0' to '255')
* 'getB()' / 'setB(value)' : blue component (integer from '0' to '255')
* 'getA()' / 'setA(value)' : alpha component (number from '0' to '1.0')

Example:
...
```

#### <a name="apidoc.element.node-sass.types.Error"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Error ()](#apidoc.element.node-sass.types.Error)
- description and source-code
```javascript
function SassError() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.List"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>List ()](#apidoc.element.node-sass.types.List)
- description and source-code
```javascript
function SassList() { [native code] }
```
- example usage
```shell
...
'''

#### types.Boolean(value)
* 'getValue()' : gets the enclosed boolean
* 'types.Boolean.TRUE' : Singleton instance of 'types.Boolean' that holds "true"
* 'types.Boolean.FALSE' : Singleton instance of 'types.Boolean' that holds "false"

#### types.List(length [, commaSeparator = true])
* 'getValue(index)' / 'setValue(index, value)' : 'value' must itself be an instance of one of the constructors in 'sass.types'.
* 'getSeparator()' / 'setSeparator(isComma)' : whether to use commas as a separator
* 'getLength()'

#### types.Map(length)
* 'getKey(index)' / 'setKey(index, value)'
* 'getValue(index)' / 'setValue(index, value)'
...
```

#### <a name="apidoc.element.node-sass.types.Map"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Map ()](#apidoc.element.node-sass.types.Map)
- description and source-code
```javascript
function SassMap() { [native code] }
```
- example usage
```shell
...
* 'types.Boolean.FALSE' : Singleton instance of 'types.Boolean' that holds "false"

#### types.List(length [, commaSeparator = true])
* 'getValue(index)' / 'setValue(index, value)' : 'value' must itself be an instance of one of the constructors in 'sass.types'.
* 'getSeparator()' / 'setSeparator(isComma)' : whether to use commas as a separator
* 'getLength()'

#### types.Map(length)
* 'getKey(index)' / 'setKey(index, value)'
* 'getValue(index)' / 'setValue(index, value)'
* 'getLength()'

#### types.Null()
* 'types.Null.NULL' : Singleton instance of 'types.Null'.
...
```

#### <a name="apidoc.element.node-sass.types.Null"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Null ()](#apidoc.element.node-sass.types.Null)
- description and source-code
```javascript
function SassNull() { [native code] }
```
- example usage
```shell
...
* 'getLength()'

#### types.Map(length)
* 'getKey(index)' / 'setKey(index, value)'
* 'getValue(index)' / 'setValue(index, value)'
* 'getLength()'

#### types.Null()
* 'types.Null.NULL' : Singleton instance of 'types.Null'.

#### Example

'''javascript
sass.renderSync({
data: '#{headings(2,5)} { color: #08c; }',
...
```

#### <a name="apidoc.element.node-sass.types.Number"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Number ()](#apidoc.element.node-sass.types.Number)
- description and source-code
```javascript
function SassNumber() { [native code] }
```
- example usage
```shell
...

### functions (>= v3.0.0) - _experimental_

**This is an experimental LibSass feature. Use with caution.**

'functions' is an 'Object' that holds a collection of custom functions that may be invoked by the sass files being compiled. They
 may take zero or more input parameters and must return a value either synchronously ('return ...;') or asynchronously ('done();').
Those parameters will be instances of one of the constructors contained in the 'require('node-sass').types' hash. The return value
 must be of one of these types as well. See the list of available types below:

#### types.Number(value [, unit = ""])
* 'getValue()'/ 'setValue(value)' : gets / sets the numerical portion of the number
* 'getUnit()' / 'setUnit(unit)' : gets / sets the unit portion of the number

#### types.String(value)
* 'getValue()' / 'setValue(value)' : gets / sets the enclosed string

#### types.Color(r, g, b [, a = 1.0]) or types.Color(argb)
...
```

#### <a name="apidoc.element.node-sass.types.String"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>String ()](#apidoc.element.node-sass.types.String)
- description and source-code
```javascript
function SassString() { [native code] }
```
- example usage
```shell
...

'functions' is an 'Object' that holds a collection of custom functions that may be invoked by the sass files being compiled. They
 may take zero or more input parameters and must return a value either synchronously ('return ...;') or asynchronously ('done();').
Those parameters will be instances of one of the constructors contained in the 'require('node-sass').types' hash. The return value
 must be of one of these types as well. See the list of available types below:

#### types.Number(value [, unit = ""])
* 'getValue()'/ 'setValue(value)' : gets / sets the numerical portion of the number
* 'getUnit()' / 'setUnit(unit)' : gets / sets the unit portion of the number

#### types.String(value)
* 'getValue()' / 'setValue(value)' : gets / sets the enclosed string

#### types.Color(r, g, b [, a = 1.0]) or types.Color(argb)
* 'getR()' / 'setR(value)' : red component (integer from '0' to '255')
* 'getG()' / 'setG(value)' : green component (integer from '0' to '255')
* 'getB()' / 'setB(value)' : blue component (integer from '0' to '255')
* 'getA()' / 'setA(value)' : alpha component (number from '0' to '1.0')
...
```



# <a name="apidoc.module.node-sass.types.Boolean"></a>[module node-sass.types.Boolean](#apidoc.module.node-sass.types.Boolean)

#### <a name="apidoc.element.node-sass.types.Boolean.Boolean"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Boolean ()](#apidoc.element.node-sass.types.Boolean.Boolean)
- description and source-code
```javascript
function SassBoolean() { [native code] }
```
- example usage
```shell
...

'''javascript
var Color = require('node-sass').types.Color,
  c1 = new Color(255, 0, 0),
  c2 = new Color(0xff0088cc);
'''

#### types.Boolean(value)
* 'getValue()' : gets the enclosed boolean
* 'types.Boolean.TRUE' : Singleton instance of 'types.Boolean' that holds "true"
* 'types.Boolean.FALSE' : Singleton instance of 'types.Boolean' that holds "false"

#### types.List(length [, commaSeparator = true])
* 'getValue(index)' / 'setValue(index, value)' : 'value' must itself be an instance of one of the constructors in 'sass.types'.
* 'getSeparator()' / 'setSeparator(isComma)' : whether to use commas as a separator
...
```



# <a name="apidoc.module.node-sass.types.Boolean.prototype"></a>[module node-sass.types.Boolean.prototype](#apidoc.module.node-sass.types.Boolean.prototype)

#### <a name="apidoc.element.node-sass.types.Boolean.prototype.getValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.Boolean.prototype.</span>getValue ()](#apidoc.element.node-sass.types.Boolean.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
...
#### Example

'''javascript
sass.renderSync({
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
var i, f = from.getValue(), t = to.getValue(),
    list = new sass.types.List(t - f + 1);

for (i = f; i <= t; i++) {
  list.setValue(i - f, new sass.types.String('h' + i));
}

return list;
...
```



# <a name="apidoc.module.node-sass.types.Color"></a>[module node-sass.types.Color](#apidoc.module.node-sass.types.Color)

#### <a name="apidoc.element.node-sass.types.Color.Color"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Color ()](#apidoc.element.node-sass.types.Color.Color)
- description and source-code
```javascript
function SassColor() { [native code] }
```
- example usage
```shell
...
#### types.Number(value [, unit = ""])
* 'getValue()'/ 'setValue(value)' : gets / sets the numerical portion of the number
* 'getUnit()' / 'setUnit(unit)' : gets / sets the unit portion of the number

#### types.String(value)
* 'getValue()' / 'setValue(value)' : gets / sets the enclosed string

#### types.Color(r, g, b [, a = 1.0]) or types.Color(argb)
* 'getR()' / 'setR(value)' : red component (integer from '0' to '255')
* 'getG()' / 'setG(value)' : green component (integer from '0' to '255')
* 'getB()' / 'setB(value)' : blue component (integer from '0' to '255')
* 'getA()' / 'setA(value)' : alpha component (number from '0' to '1.0')

Example:
...
```



# <a name="apidoc.module.node-sass.types.Color.prototype"></a>[module node-sass.types.Color.prototype](#apidoc.module.node-sass.types.Color.prototype)

#### <a name="apidoc.element.node-sass.types.Color.prototype.getA"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getA ()](#apidoc.element.node-sass.types.Color.prototype.getA)
- description and source-code
```javascript
function getA() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.getB"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getB ()](#apidoc.element.node-sass.types.Color.prototype.getB)
- description and source-code
```javascript
function getB() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.getG"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getG ()](#apidoc.element.node-sass.types.Color.prototype.getG)
- description and source-code
```javascript
function getG() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.getR"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>getR ()](#apidoc.element.node-sass.types.Color.prototype.getR)
- description and source-code
```javascript
function getR() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.setA"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setA ()](#apidoc.element.node-sass.types.Color.prototype.setA)
- description and source-code
```javascript
function setA() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.setB"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setB ()](#apidoc.element.node-sass.types.Color.prototype.setB)
- description and source-code
```javascript
function setB() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.setG"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setG ()](#apidoc.element.node-sass.types.Color.prototype.setG)
- description and source-code
```javascript
function setG() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Color.prototype.setR"></a>[function <span class="apidocSignatureSpan">node-sass.types.Color.prototype.</span>setR ()](#apidoc.element.node-sass.types.Color.prototype.setR)
- description and source-code
```javascript
function setR() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-sass.types.List"></a>[module node-sass.types.List](#apidoc.module.node-sass.types.List)

#### <a name="apidoc.element.node-sass.types.List.List"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>List ()](#apidoc.element.node-sass.types.List.List)
- description and source-code
```javascript
function SassList() { [native code] }
```
- example usage
```shell
...
'''

#### types.Boolean(value)
* 'getValue()' : gets the enclosed boolean
* 'types.Boolean.TRUE' : Singleton instance of 'types.Boolean' that holds "true"
* 'types.Boolean.FALSE' : Singleton instance of 'types.Boolean' that holds "false"

#### types.List(length [, commaSeparator = true])
* 'getValue(index)' / 'setValue(index, value)' : 'value' must itself be an instance of one of the constructors in 'sass.types'.
* 'getSeparator()' / 'setSeparator(isComma)' : whether to use commas as a separator
* 'getLength()'

#### types.Map(length)
* 'getKey(index)' / 'setKey(index, value)'
* 'getValue(index)' / 'setValue(index, value)'
...
```



# <a name="apidoc.module.node-sass.types.List.prototype"></a>[module node-sass.types.List.prototype](#apidoc.module.node-sass.types.List.prototype)

#### <a name="apidoc.element.node-sass.types.List.prototype.getLength"></a>[function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>getLength ()](#apidoc.element.node-sass.types.List.prototype.getLength)
- description and source-code
```javascript
function getLength() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.List.prototype.getSeparator"></a>[function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>getSeparator ()](#apidoc.element.node-sass.types.List.prototype.getSeparator)
- description and source-code
```javascript
function getSeparator() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.List.prototype.getValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>getValue ()](#apidoc.element.node-sass.types.List.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
...
#### Example

'''javascript
sass.renderSync({
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
var i, f = from.getValue(), t = to.getValue(),
    list = new sass.types.List(t - f + 1);

for (i = f; i <= t; i++) {
  list.setValue(i - f, new sass.types.String('h' + i));
}

return list;
...
```

#### <a name="apidoc.element.node-sass.types.List.prototype.setSeparator"></a>[function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>setSeparator ()](#apidoc.element.node-sass.types.List.prototype.setSeparator)
- description and source-code
```javascript
function setSeparator() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.List.prototype.setValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.List.prototype.</span>setValue ()](#apidoc.element.node-sass.types.List.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
...
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
      var i, f = from.getValue(), t = to.getValue(),
          list = new sass.types.List(t - f + 1);

      for (i = f; i <= t; i++) {
        list.setValue(i - f, new sass.types.String('h' + i));
      }

      return list;
    }
  }
});
'''
...
```



# <a name="apidoc.module.node-sass.types.Map"></a>[module node-sass.types.Map](#apidoc.module.node-sass.types.Map)

#### <a name="apidoc.element.node-sass.types.Map.Map"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Map ()](#apidoc.element.node-sass.types.Map.Map)
- description and source-code
```javascript
function SassMap() { [native code] }
```
- example usage
```shell
...
* 'types.Boolean.FALSE' : Singleton instance of 'types.Boolean' that holds "false"

#### types.List(length [, commaSeparator = true])
* 'getValue(index)' / 'setValue(index, value)' : 'value' must itself be an instance of one of the constructors in 'sass.types'.
* 'getSeparator()' / 'setSeparator(isComma)' : whether to use commas as a separator
* 'getLength()'

#### types.Map(length)
* 'getKey(index)' / 'setKey(index, value)'
* 'getValue(index)' / 'setValue(index, value)'
* 'getLength()'

#### types.Null()
* 'types.Null.NULL' : Singleton instance of 'types.Null'.
...
```



# <a name="apidoc.module.node-sass.types.Map.prototype"></a>[module node-sass.types.Map.prototype](#apidoc.module.node-sass.types.Map.prototype)

#### <a name="apidoc.element.node-sass.types.Map.prototype.getKey"></a>[function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>getKey ()](#apidoc.element.node-sass.types.Map.prototype.getKey)
- description and source-code
```javascript
function getKey() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Map.prototype.getLength"></a>[function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>getLength ()](#apidoc.element.node-sass.types.Map.prototype.getLength)
- description and source-code
```javascript
function getLength() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Map.prototype.getValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>getValue ()](#apidoc.element.node-sass.types.Map.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
...
#### Example

'''javascript
sass.renderSync({
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
var i, f = from.getValue(), t = to.getValue(),
    list = new sass.types.List(t - f + 1);

for (i = f; i <= t; i++) {
  list.setValue(i - f, new sass.types.String('h' + i));
}

return list;
...
```

#### <a name="apidoc.element.node-sass.types.Map.prototype.setKey"></a>[function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>setKey ()](#apidoc.element.node-sass.types.Map.prototype.setKey)
- description and source-code
```javascript
function setKey() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Map.prototype.setValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.Map.prototype.</span>setValue ()](#apidoc.element.node-sass.types.Map.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
...
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
      var i, f = from.getValue(), t = to.getValue(),
          list = new sass.types.List(t - f + 1);

      for (i = f; i <= t; i++) {
        list.setValue(i - f, new sass.types.String('h' + i));
      }

      return list;
    }
  }
});
'''
...
```



# <a name="apidoc.module.node-sass.types.Number"></a>[module node-sass.types.Number](#apidoc.module.node-sass.types.Number)

#### <a name="apidoc.element.node-sass.types.Number.Number"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>Number ()](#apidoc.element.node-sass.types.Number.Number)
- description and source-code
```javascript
function SassNumber() { [native code] }
```
- example usage
```shell
...

### functions (>= v3.0.0) - _experimental_

**This is an experimental LibSass feature. Use with caution.**

'functions' is an 'Object' that holds a collection of custom functions that may be invoked by the sass files being compiled. They
 may take zero or more input parameters and must return a value either synchronously ('return ...;') or asynchronously ('done();').
Those parameters will be instances of one of the constructors contained in the 'require('node-sass').types' hash. The return value
 must be of one of these types as well. See the list of available types below:

#### types.Number(value [, unit = ""])
* 'getValue()'/ 'setValue(value)' : gets / sets the numerical portion of the number
* 'getUnit()' / 'setUnit(unit)' : gets / sets the unit portion of the number

#### types.String(value)
* 'getValue()' / 'setValue(value)' : gets / sets the enclosed string

#### types.Color(r, g, b [, a = 1.0]) or types.Color(argb)
...
```



# <a name="apidoc.module.node-sass.types.Number.prototype"></a>[module node-sass.types.Number.prototype](#apidoc.module.node-sass.types.Number.prototype)

#### <a name="apidoc.element.node-sass.types.Number.prototype.getUnit"></a>[function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>getUnit ()](#apidoc.element.node-sass.types.Number.prototype.getUnit)
- description and source-code
```javascript
function getUnit() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Number.prototype.getValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>getValue ()](#apidoc.element.node-sass.types.Number.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
...
#### Example

'''javascript
sass.renderSync({
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
var i, f = from.getValue(), t = to.getValue(),
    list = new sass.types.List(t - f + 1);

for (i = f; i <= t; i++) {
  list.setValue(i - f, new sass.types.String('h' + i));
}

return list;
...
```

#### <a name="apidoc.element.node-sass.types.Number.prototype.setUnit"></a>[function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>setUnit ()](#apidoc.element.node-sass.types.Number.prototype.setUnit)
- description and source-code
```javascript
function setUnit() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-sass.types.Number.prototype.setValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.Number.prototype.</span>setValue ()](#apidoc.element.node-sass.types.Number.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
...
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
      var i, f = from.getValue(), t = to.getValue(),
          list = new sass.types.List(t - f + 1);

      for (i = f; i <= t; i++) {
        list.setValue(i - f, new sass.types.String('h' + i));
      }

      return list;
    }
  }
});
'''
...
```



# <a name="apidoc.module.node-sass.types.String"></a>[module node-sass.types.String](#apidoc.module.node-sass.types.String)

#### <a name="apidoc.element.node-sass.types.String.String"></a>[function <span class="apidocSignatureSpan">node-sass.types.</span>String ()](#apidoc.element.node-sass.types.String.String)
- description and source-code
```javascript
function SassString() { [native code] }
```
- example usage
```shell
...

'functions' is an 'Object' that holds a collection of custom functions that may be invoked by the sass files being compiled. They
 may take zero or more input parameters and must return a value either synchronously ('return ...;') or asynchronously ('done();').
Those parameters will be instances of one of the constructors contained in the 'require('node-sass').types' hash. The return value
 must be of one of these types as well. See the list of available types below:

#### types.Number(value [, unit = ""])
* 'getValue()'/ 'setValue(value)' : gets / sets the numerical portion of the number
* 'getUnit()' / 'setUnit(unit)' : gets / sets the unit portion of the number

#### types.String(value)
* 'getValue()' / 'setValue(value)' : gets / sets the enclosed string

#### types.Color(r, g, b [, a = 1.0]) or types.Color(argb)
* 'getR()' / 'setR(value)' : red component (integer from '0' to '255')
* 'getG()' / 'setG(value)' : green component (integer from '0' to '255')
* 'getB()' / 'setB(value)' : blue component (integer from '0' to '255')
* 'getA()' / 'setA(value)' : alpha component (number from '0' to '1.0')
...
```



# <a name="apidoc.module.node-sass.types.String.prototype"></a>[module node-sass.types.String.prototype](#apidoc.module.node-sass.types.String.prototype)

#### <a name="apidoc.element.node-sass.types.String.prototype.getValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.String.prototype.</span>getValue ()](#apidoc.element.node-sass.types.String.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
...
#### Example

'''javascript
sass.renderSync({
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
var i, f = from.getValue(), t = to.getValue(),
    list = new sass.types.List(t - f + 1);

for (i = f; i <= t; i++) {
  list.setValue(i - f, new sass.types.String('h' + i));
}

return list;
...
```

#### <a name="apidoc.element.node-sass.types.String.prototype.setValue"></a>[function <span class="apidocSignatureSpan">node-sass.types.String.prototype.</span>setValue ()](#apidoc.element.node-sass.types.String.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
...
  data: '#{headings(2,5)} { color: #08c; }',
  functions: {
    'headings($from: 0, $to: 6)': function(from, to) {
      var i, f = from.getValue(), t = to.getValue(),
          list = new sass.types.List(t - f + 1);

      for (i = f; i <= t; i++) {
        list.setValue(i - f, new sass.types.String('h' + i));
      }

      return list;
    }
  }
});
'''
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
