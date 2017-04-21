# npmtest-winston-loggly

#### basic test coverage for  winston-loggly (v1.3.1)  [![npm package](https://img.shields.io/npm/v/npmtest-winston-loggly.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-winston-loggly) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-winston-loggly.svg)](https://travis-ci.org/npmtest/node-npmtest-winston-loggly)

#### A Loggly transport for winston

[![NPM](https://nodei.co/npm/winston-loggly.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/winston-loggly)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-winston-loggly/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-winston-loggly/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-winston-loggly/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-winston-loggly/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-winston-loggly/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-winston-loggly/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-winston-loggly/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-winston-loggly/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-winston-loggly/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-winston-loggly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-winston-loggly/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-winston-loggly/build/test-report.html](https://npmtest.github.io/node-npmtest-winston-loggly/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-winston-loggly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-winston-loggly/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-winston-loggly/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-winston-loggly/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winston-loggly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winston-loggly/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-winston-loggly/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-winston-loggly/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "winston-loggly",
    "version": "1.3.1",
    "description": "A Loggly transport for winston",
    "author": "Charlie Robbins <charlie.robbins@gmail.com>",
    "repository": {
        "type": "git",
        "url": "http://github.com/indexzero/winston-loggly.git"
    },
    "keywords": [
        "logging",
        "sysadmin",
        "tools"
    ],
    "dependencies": {
        "loggly": "~1.1.0"
    },
    "devDependencies": {
        "winston": "1.0.x",
        "vows": "0.8.0"
    },
    "main": "./lib/winston-loggly",
    "scripts": {
        "test": "vows --spec"
    },
    "engines": {
        "node": ">= 0.8.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
