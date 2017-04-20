# npmtest-request-json

#### basic test coverage for  [request-json (v0.6.1)](https://github.com/mycozycloud/request-json/)  [![npm package](https://img.shields.io/npm/v/npmtest-request-json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-request-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-request-json.svg)](https://travis-ci.org/npmtest/node-npmtest-request-json)

#### HTTP request client for JSON APIs

[![NPM](https://nodei.co/npm/request-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-request-json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-request-json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-request-json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-request-json/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-request-json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-request-json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-request-json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-request-json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-request-json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-request-json/build/test-report.html](https://npmtest.github.io/node-npmtest-request-json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-request-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-request-json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-request-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-request-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-request-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "request-json",
    "description": "HTTP request client for JSON APIs",
    "keywords": [
        "requests",
        "request",
        "api",
        "http",
        "json",
        "client",
        "simple",
        "utility"
    ],
    "license": "MIT",
    "version": "0.6.1",
    "homepage": "https://github.com/mycozycloud/request-json/",
    "bugs": {
        "url": "https://github.com/mycozycloud/request-json/issues"
    },
    "author": "Cozy Cloud <contact@cozycloud.cc> (http://cozycloud.cc)",
    "contributors": [
        "Zoe Bellot",
        "Romain Foucault",
        "Googoid",
        "Dario Kondratiuk",
        "David Neal",
        "NickH-nz",
        "Frank Rousseau",
        "Alan Plum",
        "Fedor Shubin",
        "Fábio Santos",
        "Stephen Tweeddale",
        "Benjamin Woodruff"
    ],
    "engines": {
        "node": "*"
    },
    "main": "./main.js",
    "dependencies": {
        "depd": "1.1.0",
        "request": "2.74.0"
    },
    "devDependencies": {
        "body-parser": "1.15.2",
        "chai": "3.5.0",
        "coffee-script": "1.10.0",
        "coffeelint": "1.15.7",
        "connect-multiparty": "2.0.0",
        "express": "4.14.0",
        "lie": "3.1.0",
        "mocha": "2.5.3"
    },
    "scripts": {
        "prepublish": "./node_modules/coffee-script/bin/coffee -cb main.coffee",
        "test": "mocha tests.coffee --reporter spec --compilers coffee:coffee-script/register --colors",
        "build": "./node_modules/coffee-script/bin/coffee -cb main.coffee",
        "lint": "./node_modules/coffeelint/bin/coffeelint main.coffee tests.coffee"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mycozycloud/request-json.git"
    },
    "optionalDependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
