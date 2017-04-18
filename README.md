# npmtest-zuul

#### test coverage for  [zuul (v3.11.1)](https://github.com/shtylman/zuul#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-zuul.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-zuul) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-zuul.svg)](https://travis-ci.org/npmtest/node-npmtest-zuul)

#### simple browser testing

[![NPM](https://nodei.co/npm/zuul.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zuul)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-zuul/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-zuul/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-zuul/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-zuul/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-zuul/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-zuul/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-zuul/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-zuul/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-zuul/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-zuul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-zuul/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-zuul/build/test-report.html](https://npmtest.github.io/node-npmtest-zuul/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-zuul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-zuul/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-zuul/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zuul/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zuul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zuul/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-zuul/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-zuul/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roman Shtylman"
    },
    "bin": {
        "zuul": "./bin/zuul"
    },
    "bugs": {
        "url": "https://github.com/shtylman/zuul/issues"
    },
    "dependencies": {
        "JSON2": "0.1.0",
        "batch": "0.5.0",
        "browserify": "13.0.0",
        "browserify-istanbul": "0.1.5",
        "char-split": "0.2.0",
        "colors": "0.6.2",
        "commander": "2.1.0",
        "compression": "1.5.0",
        "convert-source-map": "1.0.0",
        "debug": "2.1.0",
        "express": "3.4.8",
        "express-state": "1.0.3",
        "find-nearest-file": "1.0.0",
        "firefox-profile": "0.2.7",
        "globs-to-files": "1.0.0",
        "hbs": "2.4.0",
        "highlight.js": "7.5.0",
        "http-proxy": "1.11.2",
        "humanize-duration": "2.4.0",
        "istanbul-middleware": "0.2.2",
        "load-script": "0.0.5",
        "lodash": "3.10.1",
        "opener": "1.4.0",
        "osenv": "0.0.3",
        "shallow-copy": "0.0.1",
        "shell-quote": "1.4.1",
        "stack-mapper": "0.2.2",
        "stacktrace-js": "http://github.com/defunctzombie/stacktrace.js/tarball/07e7b9516f1449f5c209e4f67f11a43f738c1712",
        "superagent": "0.15.7",
        "tap-finished": "0.0.1",
        "tap-parser": "0.7.0",
        "watchify": "3.7.0",
        "wd": "0.3.11",
        "xtend": "2.1.2",
        "yamljs": "0.1.4",
        "zuul-localtunnel": "1.1.0"
    },
    "description": "simple browser testing",
    "devDependencies": {
        "after": "~0.8.1",
        "browzers": "1.2.0",
        "bulk-require": "0.2.1",
        "mocha": "~1.16.2",
        "phantomjs-prebuilt": "2.1.4",
        "tape": "3.5.0",
        "through2": "0.6.3",
        "zuul-ngrok": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7080bbbf22a6d97f60879b3b8f2a823c5a99bab2",
        "tarball": "https://registry.npmjs.org/zuul/-/zuul-3.11.1.tgz"
    },
    "gitHead": "f021cf3b53dac1c373e70a9f435804a557a6d2ce",
    "homepage": "https://github.com/shtylman/zuul#readme",
    "keywords": [
        "zuul",
        "testing",
        "browser",
        "qunit",
        "mocha",
        "saucelabs"
    ],
    "license": "MIT",
    "main": "lib/zuul.js",
    "maintainers": [
        {
            "name": "defunctzombie"
        },
        {
            "name": "feross"
        },
        {
            "name": "vvo"
        }
    ],
    "name": "zuul",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shtylman/zuul.git"
    },
    "scripts": {
        "test": "DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js"
    },
    "version": "3.11.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
