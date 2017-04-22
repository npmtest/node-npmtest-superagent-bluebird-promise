# npmtest-superagent-bluebird-promise

#### basic test coverage for  [superagent-bluebird-promise (v4.2.0)](https://github.com/KyleAMathews/superagent-bluebird-promise)  [![npm package](https://img.shields.io/npm/v/npmtest-superagent-bluebird-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-superagent-bluebird-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-superagent-bluebird-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-superagent-bluebird-promise)

#### Add promise support to superagent using Bluebird

[![NPM](https://nodei.co/npm/superagent-bluebird-promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/superagent-bluebird-promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-superagent-bluebird-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-superagent-bluebird-promise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/test-report.html](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-superagent-bluebird-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-superagent-bluebird-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-superagent-bluebird-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-superagent-bluebird-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-superagent-bluebird-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Mathews"
    },
    "bugs": {
        "url": "https://github.com/KyleAMathews/superagent-bluebird-promise/issues"
    },
    "dependencies": {},
    "description": "Add promise support to superagent using Bluebird",
    "devDependencies": {
        "bluebird": "^3.0.5",
        "chai": "^3.3.0",
        "coffee-script": "^1.9.2",
        "coffeelint": "^1.9.3",
        "interfake": "^1.12.1",
        "jshint": "^2.7.0",
        "mocha": "^3.0.2",
        "mocha-unfunk-reporter": "^0.4.0",
        "pre-commit": "^1.0.6",
        "sinon": "^1.14.1",
        "superagent": "^2.2.0",
        "underscore": "^1.8.3"
    },
    "directories": {},
    "dist": {
        "shasum": "0b6a6872cc830371cb9f4172dd0510751abd16b2",
        "tarball": "https://registry.npmjs.org/superagent-bluebird-promise/-/superagent-bluebird-promise-4.2.0.tgz"
    },
    "gitHead": "31f8298e583b2cc5e70fb43a1c3a016d80755360",
    "homepage": "https://github.com/KyleAMathews/superagent-bluebird-promise",
    "keywords": [
        "superagent",
        "promise",
        "bluebird"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bmv437"
        },
        {
            "name": "kylemathews"
        },
        {
            "name": "markdalgleish"
        }
    ],
    "name": "superagent-bluebird-promise",
    "optionalDependencies": {},
    "peerDependencies": {
        "bluebird": "3.x",
        "superagent": ">=1.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/KyleAMathews/superagent-bluebird-promise.git"
    },
    "scripts": {
        "test": "coffeelint test/* & jshint *.json *.js && NODE_ENV=test node_modules/.bin/mocha --recursive --compilers coffee:coffee-script/register -R mocha-unfunk-reporter",
        "test-watch": "NODE_ENV=test node_modules/.bin/mocha -w --recursive --compilers coffee:coffee-script/register -R mocha-unfunk-reporter"
    },
    "version": "4.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
