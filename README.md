# npmtest-fresh

#### basic test coverage for  fresh (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmtest-fresh.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fresh) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fresh.svg)](https://travis-ci.org/npmtest/node-npmtest-fresh)

#### HTTP response freshness testing

[![NPM](https://nodei.co/npm/fresh.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fresh)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fresh/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fresh/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fresh/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fresh/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fresh/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fresh/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fresh/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fresh/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fresh/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fresh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fresh/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fresh/build/test-report.html](https://npmtest.github.io/node-npmtest-fresh/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fresh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fresh/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fresh/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fresh/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fresh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fresh/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fresh/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fresh/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fresh",
    "description": "HTTP response freshness testing",
    "version": "0.5.0",
    "author": "TJ Holowaychuk <tj@vision-media.ca> (http://tjholowaychuk.com)",
    "contributors": [
        "Douglas Christopher Wilson <doug@somethingdoug.com>",
        "Jonathan Ong <me@jongleberry.com> (http://jongleberry.com)"
    ],
    "license": "MIT",
    "keywords": [
        "fresh",
        "http",
        "conditional",
        "cache"
    ],
    "repository": "jshttp/fresh",
    "devDependencies": {
        "eslint": "3.16.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-promise": "3.4.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "engines": {
        "node": ">= 0.6"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
