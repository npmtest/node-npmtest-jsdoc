# npmtest-jsdoc

#### basic test coverage for  jsdoc (v3.4.3)  [![npm package](https://img.shields.io/npm/v/npmtest-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsdoc.svg)](https://travis-ci.org/npmtest/node-npmtest-jsdoc)

#### An API documentation generator for JavaScript.

[![NPM](https://nodei.co/npm/jsdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsdoc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsdoc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsdoc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsdoc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsdoc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsdoc/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jsdoc/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jsdoc/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsdoc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsdoc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsdoc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsdoc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsdoc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsdoc/build/test-report.html](https://npmtest.github.io/node-npmtest-jsdoc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsdoc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsdoc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jsdoc",
    "version": "3.4.3",
    "revision": "1478737510220",
    "description": "An API documentation generator for JavaScript.",
    "keywords": [
        "documentation",
        "javascript"
    ],
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "https://github.com/jsdoc3/jsdoc"
    },
    "dependencies": {
        "bluebird": "~3.4.6",
        "catharsis": "~0.8.8",
        "escape-string-regexp": "~1.0.5",
        "espree": "~3.1.7",
        "js2xmlparser": "~1.0.0",
        "klaw": "~1.3.0",
        "marked": "~0.3.6",
        "mkdirp": "~0.5.1",
        "requizzle": "~0.2.1",
        "strip-json-comments": "~2.0.1",
        "taffydb": "2.6.2",
        "underscore": "~1.8.3"
    },
    "devDependencies": {
        "gulp": "~3.9.1",
        "gulp-eslint": "~3.0.1",
        "gulp-json-editor": "~2.2.1",
        "istanbul": "~0.4.5",
        "tv4": "https://github.com/hegemonic/tv4/tarball/own-properties"
    },
    "engines": {
        "node": ">=0.10"
    },
    "scripts": {
        "test": "gulp lint; gulp test"
    },
    "bin": {
        "jsdoc": "./jsdoc.js"
    },
    "bugs": "https://github.com/jsdoc3/jsdoc/issues",
    "author": {
        "name": "Michael Mathews"
    },
    "contributors": [
        {
            "url": "https://github.com/jsdoc3/jsdoc/graphs/contributors"
        }
    ],
    "maintainers": {
        "name": "Jeff Williams"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
