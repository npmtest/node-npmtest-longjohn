# npmtest-longjohn

#### test coverage for  [longjohn (v0.2.12)](https://github.com/mattinsler/longjohn)  [![npm package](https://img.shields.io/npm/v/npmtest-longjohn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-longjohn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-longjohn.svg)](https://travis-ci.org/npmtest/node-npmtest-longjohn)

#### Long stack traces for node.js inspired by https://github.com/tlrobinson/long-stack-traces

[![NPM](https://nodei.co/npm/longjohn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/longjohn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-longjohn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-longjohn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-longjohn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-longjohn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-longjohn/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-longjohn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-longjohn/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-longjohn/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-longjohn/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-longjohn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-longjohn/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-longjohn/build/test-report.html](https://npmtest.github.io/node-npmtest-longjohn/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-longjohn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-longjohn/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-longjohn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-longjohn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-longjohn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-longjohn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-longjohn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-longjohn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Insler",
        "url": "http://www.mattinsler.com"
    },
    "bugs": {
        "url": "https://github.com/mattinsler/longjohn/issues"
    },
    "dependencies": {
        "source-map-support": "0.3.2 - 1.0.0"
    },
    "description": "Long stack traces for node.js inspired by https://github.com/tlrobinson/long-stack-traces",
    "devDependencies": {
        "coffee-script": "1.12.2",
        "grunt": "0.4.5",
        "grunt-cli": "1.2.0",
        "grunt-contrib-coffee": "0.7.0",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7ca7446b083655c377e7512213dc754d52a64a7e",
        "tarball": "https://registry.npmjs.org/longjohn/-/longjohn-0.2.12.tgz"
    },
    "engines": {
        "node": ">= 0.9.3"
    },
    "gitHead": "5c7a47963cd042253fff578cbb2d26555870f48c",
    "homepage": "https://github.com/mattinsler/longjohn",
    "keywords": [],
    "license": "MIT",
    "main": "dist/longjohn",
    "maintainers": [
        {
            "name": "mattinsler"
        }
    ],
    "name": "longjohn",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mattinsler/longjohn.git"
    },
    "scripts": {
        "test": "node_modules/mocha/bin/mocha --compilers coffee:coffee-script/register -R spec"
    },
    "version": "0.2.12"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
