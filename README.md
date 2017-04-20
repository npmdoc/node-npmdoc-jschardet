# npmdoc-jschardet

#### api documentation for  [jschardet (v1.4.2)](https://github.com/aadsm/jschardet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-jschardet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jschardet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jschardet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jschardet)

#### Character encoding auto-detection in JavaScript (port of python's chardet)

[![NPM](https://nodei.co/npm/jschardet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jschardet)

- [https://npmdoc.github.io/node-npmdoc-jschardet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jschardet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jschardet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jschardet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jschardet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jschardet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "António Afonso"
    },
    "bugs": {
        "url": "https://github.com/aadsm/jschardet/issues"
    },
    "dependencies": {},
    "description": "Character encoding auto-detection in JavaScript (port of python's chardet)",
    "devDependencies": {
        "browserify": "~12.0.1",
        "google-closure-compiler": "20151015.0.0"
    },
    "directories": {
        "lib": "./lib",
        "test": "./test"
    },
    "dist": {
        "shasum": "2aa107f142af4121d145659d44f50830961e699a",
        "tarball": "https://registry.npmjs.org/jschardet/-/jschardet-1.4.2.tgz"
    },
    "engines": {
        "node": ">=0.1.90"
    },
    "homepage": "https://github.com/aadsm/jschardet#readme",
    "keywords": [
        "encoding",
        "charset"
    ],
    "license": "LGPL-2.1+",
    "main": "src/init",
    "maintainers": [
        {
            "name": "aadsm"
        }
    ],
    "name": "jschardet",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aadsm/jschardet.git"
    },
    "scripts": {
        "dist": "npm run dist-dev && java -jar node_modules/google-closure-compiler/compiler.jar --warning_level QUIET --compilation_level SIMPLE_OPTIMIZATIONS --js dist/jschardet.js > dist/jschardet.min.js",
        "dist-dev": "mkdir -p dist && browserify index.js -s jschardet --detect-globals false -o dist/jschardet.js"
    },
    "version": "1.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
