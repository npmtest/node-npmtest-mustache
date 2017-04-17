# test coverage for  [mustache (v2.3.0)](https://github.com/janl/mustache.js)  [![npm package](https://img.shields.io/npm/v/npmtest-mustache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mustache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mustache.svg)](https://travis-ci.org/npmtest/node-npmtest-mustache)
#### Logic-less {{mustache}} templates with JavaScript

[![NPM](https://nodei.co/npm/mustache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mustache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mustache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mustache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mustache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mustache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mustache/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mustache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mustache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mustache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mustache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mustache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mustache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mustache/build/test-report.html](https://npmtest.github.io/node-npmtest-mustache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mustache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mustache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mustache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mustache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mustache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mustache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mustache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mustache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mustache.js Authors"
    },
    "bin": {
        "mustache": "./bin/mustache"
    },
    "bugs": {
        "url": "https://github.com/janl/mustache.js/issues"
    },
    "dependencies": {},
    "description": "Logic-less {{mustache}} templates with JavaScript",
    "devDependencies": {
        "chai": "^3.4.0",
        "eslint": "^2.5.1",
        "mocha": "^3.0.2",
        "zuul": "^3.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4028f7778b17708a489930a6e52ac3bca0da41d0",
        "tarball": "https://registry.npmjs.org/mustache/-/mustache-2.3.0.tgz"
    },
    "engines": {
        "npm": ">=1.4.0"
    },
    "files": [
        "mustache.js",
        "mustache.min.js",
        "bin",
        "wrappers",
        "LICENSE"
    ],
    "gitHead": "23beb3a8805c9a857e3ea777431481599fab503e",
    "greenkeeper": {
        "ignore": [
            "eslint"
        ]
    },
    "homepage": "https://github.com/janl/mustache.js",
    "keywords": [
        "mustache",
        "template",
        "templates",
        "ejs"
    ],
    "license": "MIT",
    "main": "./mustache.js",
    "maintainers": [
        {
            "name": "dasilvacontin"
        },
        {
            "name": "flipp"
        },
        {
            "name": "jan"
        },
        {
            "name": "mjackson"
        },
        {
            "name": "nathan"
        }
    ],
    "name": "mustache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/janl/mustache.js.git"
    },
    "scripts": {
        "pre-test-browser": "node test/create-browser-suite.js",
        "pretest": "eslint mustache.js bin/mustache",
        "test": "mocha --reporter spec test/*-test.js",
        "test-browser": "npm run pre-test-browser && zuul -- test/context-test.js test/parse-test.js test/scanner-test.js test/render-test-browser.js",
        "test-browser-local": "npm run pre-test-browser && zuul --local 8080 -- test/context-test.js test/scanner-test.js test/parse-test.js test/render-test-browser.js",
        "test-render": "mocha  --reporter spec test/render-test"
    },
    "spm": {
        "main": "mustache.js",
        "ignore": [
            "test",
            "wrappers"
        ]
    },
    "version": "2.3.0",
    "volo": {
        "url": "https://raw.github.com/janl/mustache.js/{version}/mustache.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
