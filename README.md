# npmtest-express-rate-limit

#### basic test coverage for  [express-rate-limit (v2.6.0)](https://github.com/nfriedly/express-rate-limit)  [![npm package](https://img.shields.io/npm/v/npmtest-express-rate-limit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-rate-limit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-rate-limit.svg)](https://travis-ci.org/npmtest/node-npmtest-express-rate-limit)

#### Basic IP rate-limiting middleware for Express. Use to limit repeated requests to public APIs and/or endpoints such as password reset.

[![NPM](https://nodei.co/npm/express-rate-limit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-rate-limit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-rate-limit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-rate-limit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-rate-limit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-rate-limit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-rate-limit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-rate-limit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-rate-limit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-rate-limit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-rate-limit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-rate-limit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-rate-limit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-rate-limit/build/test-report.html](https://npmtest.github.io/node-npmtest-express-rate-limit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-rate-limit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-rate-limit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-rate-limit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-rate-limit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-rate-limit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-rate-limit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-rate-limit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-rate-limit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-rate-limit",
    "version": "2.6.0",
    "description": "Basic IP rate-limiting middleware for Express. Use to limit repeated requests to public APIs and/or endpoints such as password reset.",
    "homepage": "https://github.com/nfriedly/express-rate-limit",
    "author": {
        "name": "Nathan Friedly",
        "url": "http://nfriedly.com/"
    },
    "repository": "nfriedly/express-rate-limit",
    "license": "MIT",
    "main": "lib/express-rate-limit.js",
    "files": [
        "lib/"
    ],
    "keywords": [
        "express-rate-limit",
        "express",
        "rate",
        "limit",
        "ratelimit",
        "rate-limit",
        "middleware",
        "ip",
        "auth",
        "authorization",
        "security",
        "brute",
        "force",
        "bruteforce",
        "brute-force",
        "attack"
    ],
    "dependencies": {
        "defaults": "^1.0.3"
    },
    "devDependencies": {
        "express": "^4.13.3",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-mocha-cli": "^3.0.0",
        "jshint-stylish": "^2.1.0",
        "load-grunt-tasks": "^3.5.0",
        "supertest": "^2.0.0",
        "time-grunt": "^1.3.0"
    },
    "scripts": {
        "test": "grunt"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
