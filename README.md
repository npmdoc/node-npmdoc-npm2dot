# npmdoc-npm2dot

#### basic api documentation for  [npm2dot (v1.0.2)](https://github.com/wyvernnot/npm2dot#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm2dot.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm2dot) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm2dot.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm2dot)

#### convert npm dependency list to graphviz format

[![NPM](https://nodei.co/npm/npm2dot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm2dot)

- [https://npmdoc.github.io/node-npmdoc-npm2dot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm2dot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm2dot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm2dot/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm2dot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm2dot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "wyvernnot"
    },
    "bin": {
        "npm2dot": "./bin/npm2dot"
    },
    "bugs": {
        "url": "https://github.com/wyvernnot/npm2dot/issues"
    },
    "dependencies": {},
    "description": "convert npm dependency list to graphviz format",
    "devDependencies": {
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "c5de49d8824599c6204505fb2e00ed1f8d050bfc",
        "tarball": "https://registry.npmjs.org/npm2dot/-/npm2dot-1.0.2.tgz"
    },
    "gitHead": "7c368e661d7befb67e161a5c2eaef3ed61215079",
    "homepage": "https://github.com/wyvernnot/npm2dot#readme",
    "keywords": [
        "graphviz"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wyvernnot"
        }
    ],
    "name": "npm2dot",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wyvernnot/npm2dot.git"
    },
    "scripts": {
        "publish-patch": "mocha && npm version patch && git push && git push --tags && npm publish",
        "test": "mocha ./test"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
