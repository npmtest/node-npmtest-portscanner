# npmtest-portscanner

#### basic test coverage for  [portscanner (v2.1.1)](https://github.com/baalexander/node-portscanner)  [![npm package](https://img.shields.io/npm/v/npmtest-portscanner.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-portscanner) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-portscanner.svg)](https://travis-ci.org/npmtest/node-npmtest-portscanner)

#### Asynchronous port scanner for Node.js

[![NPM](https://nodei.co/npm/portscanner.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/portscanner)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-portscanner/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-portscanner/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-portscanner/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-portscanner/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-portscanner/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-portscanner/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-portscanner/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-portscanner/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-portscanner/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-portscanner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-portscanner/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-portscanner/build/test-report.html](https://npmtest.github.io/node-npmtest-portscanner/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-portscanner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-portscanner/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-portscanner/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-portscanner/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-portscanner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-portscanner/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-portscanner/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-portscanner/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "portscanner",
    "description": "Asynchronous port scanner for Node.js",
    "scripts": {
        "test": "ava",
        "lint": "standard"
    },
    "keywords": [
        "portscanner",
        "port",
        "scanner",
        "checker",
        "status"
    ],
    "version": "2.1.1",
    "preferGlobal": false,
    "homepage": "https://github.com/baalexander/node-portscanner",
    "author": [
        "Brandon Alexander <baalexander@gmail.com> (https://github.com/baalexander)",
        "Sean Massa <endangeredmassa@gmail.com> (http://massalabs.com)"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/baalexander/node-portscanner.git"
    },
    "bugs": {
        "url": "https://github.com/baalexander/node-portscanner/issues"
    },
    "directories": {
        "lib": "./lib"
    },
    "main": "./lib/portscanner.js",
    "dependencies": {
        "async": "1.5.2",
        "is-number-like": "^1.0.3"
    },
    "devDependencies": {
        "ava": "^0.4.2",
        "eslint": "^3.10.2",
        "eslint-config-standard": "^6.2.1",
        "standard": "^8.5.0"
    },
    "engines": {
        "node": ">=0.4",
        "npm": ">=1.0.0"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
