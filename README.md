# npmtest-csv-streamify

#### basic test coverage for  [csv-streamify (v3.0.4)](https://github.com/klaemo/csv-stream#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-csv-streamify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csv-streamify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csv-streamify.svg)](https://travis-ci.org/npmtest/node-npmtest-csv-streamify)

#### Streaming CSV Parser. Made entirely out of streams.

[![NPM](https://nodei.co/npm/csv-streamify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csv-streamify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csv-streamify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv-streamify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csv-streamify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csv-streamify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csv-streamify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-csv-streamify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-csv-streamify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csv-streamify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csv-streamify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csv-streamify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csv-streamify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv-streamify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csv-streamify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csv-streamify/build/test-report.html](https://npmtest.github.io/node-npmtest-csv-streamify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csv-streamify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csv-streamify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csv-streamify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csv-streamify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csv-streamify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csv-streamify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csv-streamify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csv-streamify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Clemens Stolle"
    },
    "bin": {
        "csv-streamify": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/klaemo/csv-stream/issues"
    },
    "dependencies": {
        "through2": "2.0.1"
    },
    "description": "Streaming CSV Parser. Made entirely out of streams.",
    "devDependencies": {
        "csv-spectrum": "^1.0.0",
        "mocha": "^2.3.3",
        "standard": "^7.1.0",
        "string-to-stream": "^1.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "4cb614c57e3f299cca17b63fdcb4ad167777f47a",
        "tarball": "https://registry.npmjs.org/csv-streamify/-/csv-streamify-3.0.4.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "8b882afdf1156b8be52d7ff9c82a0d72b544ed72",
    "homepage": "https://github.com/klaemo/csv-stream#readme",
    "keywords": [
        "csv",
        "parser",
        "stream",
        "cli"
    ],
    "license": "BSD-2-Clause",
    "main": "csv-streamify.js",
    "maintainers": [
        {
            "name": "klaemo"
        }
    ],
    "name": "csv-streamify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/klaemo/csv-stream.git"
    },
    "scripts": {
        "test": "standard && mocha -R spec"
    },
    "version": "3.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
