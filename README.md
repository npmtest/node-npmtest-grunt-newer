# test coverage for  [grunt-newer (v1.3.0)](https://github.com/tschaub/grunt-newer)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-newer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-newer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-newer.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-newer)
#### Run Grunt tasks with only those source files modified since the last successful run.

[![NPM](https://nodei.co/npm/grunt-newer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-newer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-newer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-newer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-newer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-newer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-newer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-newer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-newer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-newer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-newer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-newer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-newer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-newer/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-newer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-newer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-newer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-newer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-newer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-newer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-newer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-newer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-newer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Schaub",
        "url": "http://tschaub.net/"
    },
    "bugs": {
        "url": "https://github.com/tschaub/grunt-newer/issues"
    },
    "dependencies": {
        "async": "^1.5.2",
        "rimraf": "^2.5.2"
    },
    "description": "Run Grunt tasks with only those source files modified since the last successful run.",
    "devDependencies": {
        "chai": "^3.5.0",
        "grunt": "1.0.1",
        "grunt-cafe-mocha": "0.1.13",
        "grunt-cli": "^1.1.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "mock-fs": "^3.8.0",
        "tmp": "0.0.31",
        "wrench": "1.5.8"
    },
    "directories": {},
    "dist": {
        "shasum": "83ccb7a1dda7cbd8ab23b059024ebe614ad2f342",
        "tarball": "https://registry.npmjs.org/grunt-newer/-/grunt-newer-1.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "54484d394f22e2841b94b7fb76eee42a0b4d0f63",
    "homepage": "https://github.com/tschaub/grunt-newer",
    "keywords": [
        "files",
        "grunt",
        "gruntplugin",
        "newer"
    ],
    "license": "MIT",
    "main": "gruntfile.js",
    "maintainers": [
        {
            "name": "tschaub"
        }
    ],
    "name": "grunt-newer",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/tschaub/grunt-newer.git"
    },
    "scripts": {
        "start": "grunt test watch",
        "test": "grunt test"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
