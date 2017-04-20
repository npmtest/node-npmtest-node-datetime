# npmtest-node-datetime

#### basic test coverage for  [node-datetime (v1.0.0)](https://github.com/voltrue2/node-datetime)  [![npm package](https://img.shields.io/npm/v/npmtest-node-datetime.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-datetime) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-datetime.svg)](https://travis-ci.org/npmtest/node-npmtest-node-datetime)

#### An extended Date object for javascript. 1. Handles offests by days and hours. 2. Built-in formatting function. 3. Time based value calculation.

[![NPM](https://nodei.co/npm/node-datetime.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-datetime)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-datetime/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-datetime/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-datetime/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-datetime/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-datetime/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-datetime/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-datetime/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-datetime/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-datetime/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-datetime/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-datetime/build/test-report.html](https://npmtest.github.io/node-npmtest-node-datetime/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-datetime/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-datetime/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-datetime/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-datetime/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-datetime/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-datetime/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-datetime",
    "version": "1.0.0",
    "author": "Nobuyori Takahashi",
    "description": "An extended Date object for javascript. 1. Handles offests by days and hours. 2. Built-in formatting function. 3. Time based value calculation.",
    "devDependencies": {
        "mocha": "1.20.1"
    },
    "jshintConfig": {
        "node": true,
        "bitwise": false,
        "camelcase": true,
        "curly": true,
        "eqeqeq": true,
        "forin": false,
        "immed": true,
        "latedef": false,
        "newcap": true,
        "noarg": true,
        "noempty": true,
        "undef": true,
        "unused": true,
        "nonew": true,
        "white": true,
        "maxdepth": 5,
        "quotmark": "single",
        "globals": {
            "mocha": false,
            "describe": false,
            "it": false,
            "before": false,
            "beforeEach": false,
            "after": false,
            "afterEach": false
        }
    },
    "engine": "node >= 0.10.20",
    "contributors": [],
    "keywords": [
        "date",
        "datetime",
        "format",
        "time",
        "offset",
        "range"
    ],
    "license": "MIT",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "dependencies": {},
    "scripts": {
        "test": "mocha"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/voltrue2/node-datetime.git"
    },
    "bugs": {
        "url": "https://github.com/voltrue2/node-datetime/issues"
    },
    "homepage": "https://github.com/voltrue2/node-datetime"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
