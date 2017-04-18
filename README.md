# npmdoc-request-json

#### api documentation for  [request-json (v0.6.1)](https://github.com/mycozycloud/request-json/)  [![npm package](https://img.shields.io/npm/v/npmdoc-request-json.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-request-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-request-json.svg)](https://travis-ci.org/npmdoc/node-npmdoc-request-json)

#### HTTP request client for JSON APIs

[![NPM](https://nodei.co/npm/request-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-json)

- [https://npmdoc.github.io/node-npmdoc-request-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-json/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-request-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-request-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cozy Cloud",
        "url": "http://cozycloud.cc"
    },
    "bugs": {
        "url": "https://github.com/mycozycloud/request-json/issues"
    },
    "contributors": [
        {
            "name": "Zoe Bellot"
        },
        {
            "name": "Romain Foucault"
        },
        {
            "name": "Googoid"
        },
        {
            "name": "Dario Kondratiuk"
        },
        {
            "name": "David Neal"
        },
        {
            "name": "NickH-nz"
        },
        {
            "name": "Frank Rousseau"
        },
        {
            "name": "Alan Plum"
        },
        {
            "name": "Fedor Shubin"
        },
        {
            "name": "Fábio Santos"
        },
        {
            "name": "Stephen Tweeddale"
        },
        {
            "name": "Benjamin Woodruff"
        }
    ],
    "dependencies": {
        "depd": "1.1.0",
        "request": "2.74.0"
    },
    "description": "HTTP request client for JSON APIs",
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
    "directories": {},
    "dist": {
        "shasum": "2e7dfccf3d3d41bfb13130d75fa50fb4781c3a32",
        "tarball": "https://registry.npmjs.org/request-json/-/request-json-0.6.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "52c4e858db0c9fd47152e43f609f6efad03f106b",
    "homepage": "https://github.com/mycozycloud/request-json/",
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
    "main": "./main.js",
    "maintainers": [
        {
            "name": "mycozycloud"
        }
    ],
    "name": "request-json",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mycozycloud/request-json.git"
    },
    "scripts": {
        "build": "./node_modules/coffee-script/bin/coffee -cb main.coffee",
        "lint": "./node_modules/coffeelint/bin/coffeelint main.coffee tests.coffee",
        "prepublish": "./node_modules/coffee-script/bin/coffee -cb main.coffee",
        "test": "mocha tests.coffee --reporter spec --compilers coffee:coffee-script/register --colors"
    },
    "version": "0.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
