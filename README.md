# npmdoc-licenses

#### api documentation for  licenses (v0.0.20)  [![npm package](https://img.shields.io/npm/v/npmdoc-licenses.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-licenses) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-licenses.svg)](https://travis-ci.org/npmdoc/node-npmdoc-licenses)

#### A small tool that detects licensing information for a given Node.js module

[![NPM](https://nodei.co/npm/licenses.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/licenses)

- [https://npmdoc.github.io/node-npmdoc-licenses/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-licenses/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-licenses/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-licenses/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-licenses/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-licenses/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "licenses",
    "version": "0.0.20",
    "description": "A small tool that detects licensing information for a given Node.js module",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/3rd-Eden/licenses.git"
    },
    "scripts": {
        "test": "mocha $(find test -name '*.test.js')"
    },
    "keywords": [
        "licenses",
        "licensing",
        "license",
        "legal",
        "MIT",
        "Open Source"
    ],
    "author": "Arnout Kazemier",
    "license": "MIT",
    "dependencies": {
        "async": "0.6.x",
        "debug": "0.8.x",
        "fusing": "0.2.x",
        "githulk": "0.0.x",
        "npm-registry": "0.1.x"
    },
    "devDependencies": {
        "mocha": "1.18.x",
        "chai": "1.9.x",
        "pre-commit": "0.0.x",
        "argh": "0.1.x",
        "request": "2.34.x"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
