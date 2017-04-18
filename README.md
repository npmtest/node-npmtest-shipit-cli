# npmtest-shipit-cli

#### test coverage for  [shipit-cli (v3.0.0)](https://github.com/shipitjs/shipit)  [![npm package](https://img.shields.io/npm/v/npmtest-shipit-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shipit-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shipit-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-shipit-cli)

#### Universal automation and deployment tool written in JavaScript.

[![NPM](https://nodei.co/npm/shipit-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shipit-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shipit-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shipit-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shipit-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shipit-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shipit-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shipit-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shipit-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shipit-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shipit-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shipit-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shipit-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shipit-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-shipit-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shipit-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shipit-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shipit-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shipit-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shipit-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shipit-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shipit-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shipit-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Greg Bergé"
    },
    "bin": {
        "shipit": "./bin/shipit"
    },
    "bugs": {
        "url": "https://github.com/shipitjs/shipit/issues"
    },
    "dependencies": {
        "bluebird": "^3.3.4",
        "chalk": "^1.0.0",
        "interpret": "^1.0.0",
        "liftoff": "^2.0.0",
        "lodash": "^4.6.1",
        "minimist": "^1.1.0",
        "orchestrator": "^0.3.7",
        "pretty-hrtime": "^1.0.0",
        "ssh-pool": "^1.0.0",
        "stream-line-wrapper": "^0.1.1",
        "v8flags": "^2.0.2"
    },
    "description": "Universal automation and deployment tool written in JavaScript.",
    "devDependencies": {
        "chai": "^3.0.0",
        "mocha": "^2.1.0",
        "mock-utf8-stream": "^0.1.1",
        "sinon": "^1.12.2",
        "sinon-chai": "^2.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a9ad1185146ddc80951a8eb6b762d9e8b6587cba",
        "tarball": "https://registry.npmjs.org/shipit-cli/-/shipit-cli-3.0.0.tgz"
    },
    "gitHead": "bdff0ccea49cf762942c4124ecefea1300fad885",
    "homepage": "https://github.com/shipitjs/shipit",
    "keywords": [
        "shipit",
        "automation",
        "deployment",
        "deploy",
        "ssh"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "neoziro"
        },
        {
            "name": "timkelty"
        }
    ],
    "name": "shipit-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/shipitjs/shipit.git"
    },
    "scripts": {
        "test": "mocha && ./bin/shipit staging test"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
