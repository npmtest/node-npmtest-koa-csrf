# npmtest-koa-csrf

#### basic test coverage for  [koa-csrf (v3.0.5)](https://github.com/koajs/csrf)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-csrf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-csrf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-csrf.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-csrf)

#### CSRF tokens for koa

[![NPM](https://nodei.co/npm/koa-csrf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-csrf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-csrf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-csrf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-csrf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-csrf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-csrf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-csrf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-csrf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-csrf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-csrf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-csrf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-csrf/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-csrf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-csrf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-csrf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-csrf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-csrf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-csrf",
    "description": "CSRF tokens for koa",
    "version": "3.0.5",
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com",
        "twitter": "https://twitter.com/jongleberry"
    },
    "bugs": "koajs/csrf/issues",
    "contributors": [
        {
            "name": "Nick Baugh"
        }
    ],
    "dependencies": {
        "csrf": "^3.0.3"
    },
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-preset-crocodile": "^1.0.0",
        "chai": "^3.5.0",
        "codecov": "^1.0.1",
        "dirty-chai": "^1.2.2",
        "eslint": "^3.17.1",
        "eslint-config-crocodile": "^1.0.0",
        "istanbul": "^1.1.0-alpha.1",
        "koa": "^2.0.0-alpha.3",
        "koa-bodyparser": "^3.2.0",
        "koa-convert": "^1.2.0",
        "koa-generic-session": "^1.11.3",
        "mocha": "^3.0.2",
        "supertest": "^2.0.0"
    },
    "engines": {
        "node": ">= 6.x"
    },
    "homepage": "https://github.com/koajs/csrf",
    "keywords": [
        "cross",
        "csrf",
        "forgery",
        "koa",
        "koa2",
        "koa@2",
        "koa@next",
        "koanext",
        "next",
        "request",
        "security",
        "site"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "repository": "koajs/csrf",
    "scripts": {
        "analyze-coverage": "node_modules/.bin/babel-node node_modules/.bin/istanbul cover node_modules/.bin/_mocha",
        "check-coverage": "node_modules/.bin/babel-node node_modules/.bin/istanbul check-coverage",
        "compile": "rm -rf lib/ && babel -d lib src",
        "coverage": "rm -rf coverage/ && npm run analyze-coverage && npm run check-coverage && node_modules/.bin/codecov",
        "lint": "eslint .",
        "mocha": "NODE_ENV=test node_modules/.bin/_mocha",
        "prepublish": "npm run test",
        "test": "npm run lint && npm run compile && npm run coverage"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
