# npmtest-gitter-cli

#### basic test coverage for  [gitter-cli (v0.8.5)](https://github.com/RodrigoEspinosa/gitter-cli)  [![npm package](https://img.shields.io/npm/v/npmtest-gitter-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gitter-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gitter-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-gitter-cli)

#### A gitter client for your console.

[![NPM](https://nodei.co/npm/gitter-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gitter-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gitter-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gitter-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gitter-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gitter-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gitter-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gitter-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gitter-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gitter-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gitter-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gitter-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gitter-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gitter-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-gitter-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gitter-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gitter-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gitter-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gitter-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gitter-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gitter-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gitter-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gitter-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gitter-cli",
    "version": "0.8.5",
    "description": "A gitter client for your console.",
    "main": ".lib/main.js",
    "bin": {
        "gitter-cli": "./bin/gitter-cli"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/RodrigoEspinosa/gitter-cli.git"
    },
    "keywords": [
        "gitter",
        "cli"
    ],
    "files": [
        "bin",
        "lib"
    ],
    "preferGlobal": true,
    "author": "rec <espinosacurbelo@gmail.com>",
    "contributors": [
        "mydigitalself <mike.bartlett@gmail.com>",
        "juliosueiras <juliosueiras@gmail.com>",
        "travs"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/RodrigoEspinosa/gitter-cli/issues"
    },
    "homepage": "https://github.com/RodrigoEspinosa/gitter-cli",
    "dependencies": {
        "blessed": "^0.1.60",
        "chalk": "^1.0.0",
        "commander": "^2.8.1",
        "html-to-text": "^1.3.0",
        "keychain": "0.0.4",
        "marked": "^0.3.3",
        "node-gitter": "^1.2.8",
        "q": "^1.4.1",
        "winston": "^1.0.0",
        "wordwrap": "0.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
