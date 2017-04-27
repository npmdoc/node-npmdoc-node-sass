# npmdoc-node-sass

#### basic api documentation for  [node-sass (v4.5.2)](https://github.com/sass/node-sass)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-sass.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-sass) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-sass.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-sass)

#### Wrapper around libsass

[![NPM](https://nodei.co/npm/node-sass.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-sass)

- [https://npmdoc.github.io/node-npmdoc-node-sass/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-sass/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-sass/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-sass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-sass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Nesbitt",
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
        "shasum": "4012fa2bd129b1d6365117e88d9da0500d99da64",
        "tarball": "https://registry.npmjs.org/node-sass/-/node-sass-4.5.2.tgz"
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
    "gitHead": "ae4f935f04ec1d3a5db2b5692f97171ec7ddb9a5",
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
            "name": "am11"
        },
        {
            "name": "andrewnez"
        },
        {
            "name": "deanmao"
        },
        {
            "name": "keithamus"
        },
        {
            "name": "laurentgoderre"
        },
        {
            "name": "saperski"
        },
        {
            "name": "xzyfer"
        }
    ],
    "name": "node-sass",
    "nodeSassConfig": {
        "binarySite": "https://github.com/sass/node-sass/releases/download"
    },
    "optionalDependencies": {},
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
    "version": "4.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
