# npmtest-backoff

#### basic test coverage for  [backoff (v2.5.0)](https://github.com/MathieuTurcotte/node-backoff#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-backoff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-backoff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-backoff.svg)](https://travis-ci.org/npmtest/node-npmtest-backoff)

#### Fibonacci and exponential backoffs.

[![NPM](https://nodei.co/npm/backoff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/backoff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-backoff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-backoff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-backoff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-backoff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-backoff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-backoff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-backoff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-backoff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-backoff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-backoff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-backoff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-backoff/build/test-report.html](https://npmtest.github.io/node-npmtest-backoff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-backoff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-backoff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-backoff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-backoff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-backoff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-backoff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-backoff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-backoff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathieu Turcotte"
    },
    "bugs": {
        "url": "https://github.com/MathieuTurcotte/node-backoff/issues"
    },
    "dependencies": {
        "precond": "0.2"
    },
    "description": "Fibonacci and exponential backoffs.",
    "devDependencies": {
        "nodeunit": "0.9",
        "sinon": "1.10"
    },
    "directories": {},
    "dist": {
        "shasum": "f616eda9d3e4b66b8ca7fca79f695722c5f8e26f",
        "tarball": "https://registry.npmjs.org/backoff/-/backoff-2.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "index.js",
        "lib",
        "tests"
    ],
    "gitHead": "811118fd1f89e9ca4e6b67292b9ef5da6c4f60e9",
    "homepage": "https://github.com/MathieuTurcotte/node-backoff#readme",
    "keywords": [
        "backoff",
        "retry",
        "fibonacci",
        "exponential"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "mathieu"
        }
    ],
    "name": "backoff",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MathieuTurcotte/node-backoff.git"
    },
    "scripts": {
        "docco": "docco lib/*.js lib/strategy/* index.js",
        "pretest": "jshint lib/ tests/ examples/ index.js",
        "test": "node_modules/nodeunit/bin/nodeunit tests/"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
