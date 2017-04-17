# api documentation for  [dyson (v1.0.2)](https://github.com/webpro/dyson#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-dyson.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dyson) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dyson.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dyson)
#### Node server for dynamic, fake JSON.

[![NPM](https://nodei.co/npm/dyson.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dyson)

- [https://npmdoc.github.io/node-npmdoc-dyson/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dyson/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dyson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dyson/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dyson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dyson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lars Kappert"
    },
    "bin": {
        "dyson": "./bin/dyson.js"
    },
    "bugs": {
        "url": "https://github.com/webpro/dyson/issues"
    },
    "dependencies": {
        "body-parser": "1.16.0",
        "cookie-parser": "1.4.3",
        "cors": "2.8.1",
        "express": "4.14.1",
        "lodash": "4.17.4",
        "request": "^2.79.0",
        "require-directory": "2.1.1",
        "serve-favicon": "2.3.0",
        "when": "3.7.7"
    },
    "description": "Node server for dynamic, fake JSON.",
    "devDependencies": {
        "cross-env": "3.1.4",
        "dyson-generators": "0.1.1",
        "dyson-image": "0.1.3",
        "eslint": "3.15.0",
        "mocha": "3.2.0",
        "should": "8.4.0",
        "sinon": "1.17.7",
        "supertest": "3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8769cd667017371336b7d12716341441cfc8be8e",
        "tarball": "https://registry.npmjs.org/dyson/-/dyson-1.0.2.tgz"
    },
    "engines": {
        "node": ">=6"
    },
    "gitHead": "69ec9fa6d9e05c810f7736d0c5ebb006d5356cff",
    "homepage": "https://github.com/webpro/dyson#readme",
    "keywords": [
        "API",
        "JSON",
        "REST",
        "data",
        "dummy",
        "dynamic",
        "fake",
        "generator",
        "proxy",
        "response",
        "server"
    ],
    "license": "MIT",
    "main": "./lib/dyson.js",
    "maintainers": [
        {
            "name": "webpro"
        }
    ],
    "name": "dyson",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/webpro/dyson.git"
    },
    "scripts": {
        "fix": "eslint lib test --fix",
        "lint": "eslint lib test",
        "test": "make test"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
