# npmdoc-express-http-proxy

#### api documentation for  express-http-proxy (v0.11.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-http-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-http-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-http-proxy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-http-proxy)

#### http proxy middleware for express

[![NPM](https://nodei.co/npm/express-http-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-http-proxy)

- [https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-http-proxy",
    "version": "0.11.0",
    "description": "http proxy middleware for express",
    "engines": {
        "node": ">=4.0.0"
    },
    "engineStrict": true,
    "main": "index.js",
    "scripts": {
        "test": "npm -s run mocha && npm run -s lint && npm run -s jscs",
        "test:debug": "mocha debug -R spec test/*.js",
        "mocha": "mocha -R spec test/*.js",
        "lint": "jshint index.js test/*.js",
        "jscs": "jscs index.js test/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/villadora/express-http-proxy.git"
    },
    "keywords": [
        "express-http-proxy"
    ],
    "author": {
        "name": "villadora"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/villadora/express-http-proxy/issues"
    },
    "devDependencies": {
        "body-parser": "^1.15.2",
        "express": "^4.3.1",
        "jscs": "^3.0.7",
        "jshint": "^2.5.5",
        "mocha": "^2.1.0",
        "supertest": "^1.2.0"
    },
    "dependencies": {
        "es6-promise": "^3.2.1",
        "raw-body": "^2.1.7"
    },
    "contributors": [
        {
            "name": "Liam Bennett"
        },
        {
            "name": "eldereal",
            "url": "https://github.com/eldereal"
        },
        {
            "name": "Saulius Menkevičius",
            "url": "https://github.com/razzmatazz"
        },
        {
            "name": "Jérémy Lal"
        },
        {
            "name": "Wei Gao"
        },
        {
            "name": "Nik Krimm",
            "url": "https://github.com/monkpow"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
