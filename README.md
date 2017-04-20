# npmtest-on-headers

#### basic test coverage for  on-headers (v1.0.1)  [![npm package](https://img.shields.io/npm/v/npmtest-on-headers.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-on-headers) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-on-headers.svg)](https://travis-ci.org/npmtest/node-npmtest-on-headers)

#### Execute a listener when a response is about to write headers

[![NPM](https://nodei.co/npm/on-headers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/on-headers)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-on-headers/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-on-headers/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-on-headers/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-on-headers/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-on-headers/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-on-headers/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-on-headers/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-on-headers/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-on-headers/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-on-headers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-on-headers/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-on-headers/build/test-report.html](https://npmtest.github.io/node-npmtest-on-headers/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-on-headers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-on-headers/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-on-headers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-on-headers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-on-headers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-on-headers/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-on-headers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-on-headers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "on-headers",
    "description": "Execute a listener when a response is about to write headers",
    "version": "1.0.1",
    "author": "Douglas Christopher Wilson <doug@somethingdoug.com>",
    "license": "MIT",
    "keywords": [
        "event",
        "headers",
        "http",
        "onheaders"
    ],
    "repository": "jshttp/on-headers",
    "dependencies": {},
    "devDependencies": {
        "istanbul": "0.3.21",
        "mocha": "2.3.3",
        "supertest": "1.1.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "engines": {
        "node": ">= 0.8"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
