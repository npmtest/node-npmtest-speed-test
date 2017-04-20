# npmtest-speed-test

#### basic test coverage for  [speed-test (v1.8.0)](https://github.com/sindresorhus/speed-test#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-speed-test.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-speed-test) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-speed-test.svg)](https://travis-ci.org/npmtest/node-npmtest-speed-test)

#### Test your internet connection speed and ping using speedtest.net from the CLI

[![NPM](https://nodei.co/npm/speed-test.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/speed-test)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-speed-test/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-speed-test/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-speed-test/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-speed-test/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-speed-test/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-speed-test/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-speed-test/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-speed-test/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-speed-test/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-speed-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-speed-test/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-speed-test/build/test-report.html](https://npmtest.github.io/node-npmtest-speed-test/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-speed-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-speed-test/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-speed-test/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-speed-test/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-speed-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-speed-test/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-speed-test/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-speed-test/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "speed-test": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/speed-test/issues"
    },
    "dependencies": {
        "chalk": "^1.1.0",
        "log-symbols": "^1.0.2",
        "log-update": "^1.0.0",
        "meow": "^3.3.0",
        "ora": "^0.2.1",
        "round-to": "^1.0.0",
        "speedtest-net": "^1.2.4",
        "update-notifier": "^0.6.0"
    },
    "description": "Test your internet connection speed and ping using speedtest.net from the CLI",
    "devDependencies": {
        "ava": "*",
        "execa": "^0.1.1",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "e9f8641c17797b6ea49b42546ced25a4c5d49497",
        "tarball": "https://registry.npmjs.org/speed-test/-/speed-test-1.8.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "cli.js"
    ],
    "gitHead": "e849d4b783287979cd76d333da2edd9be9163f09",
    "homepage": "https://github.com/sindresorhus/speed-test#readme",
    "keywords": [
        "cli-app",
        "cli",
        "speed",
        "test",
        "tester",
        "speed-test",
        "speedtest",
        "connection",
        "internet",
        "bandwidth",
        "ping",
        "measure",
        "check"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "speed-test",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/speed-test.git"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "version": "1.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
