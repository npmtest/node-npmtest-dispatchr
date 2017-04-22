# npmtest-dispatchr

#### basic test coverage for  [dispatchr (v1.1.1)](https://github.com/yahoo/fluxible#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dispatchr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dispatchr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dispatchr.svg)](https://travis-ci.org/npmtest/node-npmtest-dispatchr)

#### A Flux dispatcher for applications that run on the server and the client.

[![NPM](https://nodei.co/npm/dispatchr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dispatchr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dispatchr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dispatchr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dispatchr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dispatchr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dispatchr/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dispatchr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dispatchr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dispatchr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dispatchr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dispatchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dispatchr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dispatchr/build/test-report.html](https://npmtest.github.io/node-npmtest-dispatchr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dispatchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dispatchr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dispatchr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dispatchr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dispatchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dispatchr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dispatchr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dispatchr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Ridgway"
    },
    "bugs": {
        "url": "https://github.com/yahoo/fluxible/issues"
    },
    "dependencies": {
        "debug": "^2.0.0",
        "eventemitter3": "^2.0.0",
        "inherits": "^2.0.1"
    },
    "description": "A Flux dispatcher for applications that run on the server and the client.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "b48373a7d1b0e86d82c8f8b572e3bf8b66a96158",
        "tarball": "https://registry.npmjs.org/dispatchr/-/dispatchr-1.1.1.tgz"
    },
    "homepage": "https://github.com/yahoo/fluxible#readme",
    "keywords": [
        "yahoo",
        "flux",
        "react",
        "dispatcher"
    ],
    "licenses": [
        {
            "type": "BSD-3-Clause",
            "url": "https://github.com/yahoo/fluxible/blob/master/LICENSE.md"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "mridgway"
        },
        {
            "name": "vijar"
        },
        {
            "name": "redonkulus"
        },
        {
            "name": "lingyan"
        }
    ],
    "name": "dispatchr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/yahoo/fluxible.git"
    },
    "scripts": {
        "cover": "../../node_modules/.bin/istanbul cover --dir artifacts -- ../../node_modules/.bin/_mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec",
        "lint": "../../node_modules/.bin/eslint lib/ addons/ utils/ index.js",
        "test": "../../node_modules/.bin/mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
