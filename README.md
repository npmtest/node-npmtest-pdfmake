# test coverage for  [pdfmake (v0.1.27)](http://pdfmake.org)  [![npm package](https://img.shields.io/npm/v/npmtest-pdfmake.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pdfmake) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pdfmake.svg)](https://travis-ci.org/npmtest/node-npmtest-pdfmake)
#### Client/server side PDF printing in pure JavaScript

[![NPM](https://nodei.co/npm/pdfmake.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pdfmake)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pdfmake/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdfmake/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pdfmake/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pdfmake/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pdfmake/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pdfmake/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pdfmake/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdfmake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pdfmake/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-pdfmake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pdfmake/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdfmake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdfmake/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pdfmake/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pdfmake/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bartek Pampuch"
    },
    "bugs": {
        "url": "https://github.com/bpampuch/pdfmake/issues"
    },
    "config": {
        "blanket": {
            "pattern": "src",
            "data-cover-never": [
                "node_modules",
                "tests"
            ]
        }
    },
    "dependencies": {
        "linebreak": "^0.3.0",
        "lodash": "^4.17.4",
        "pdfkit": "^0.8.0"
    },
    "description": "Client/server side PDF printing in pure JavaScript",
    "devDependencies": {
        "brfs": "^1.4.3",
        "expose-loader": "^0.7.3",
        "gulp": "^3.9.1",
        "gulp-each": "^0.5.0",
        "gulp-file-contents-to-json": "^0.2.1",
        "gulp-header": "^1.8.8",
        "gulp-jshint": "^2.0.4",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-sourcemaps": "^2.4.1",
        "gulp-spawn-mocha": "^3.1.0",
        "gulp-uglify": "^2.1.2",
        "gulp-util": "^3.0.8",
        "iconv-lite": "^0.4.15",
        "jshint": "^2.9.4",
        "json-loader": "^0.5.4",
        "mocha": "^3.2.0",
        "sinon": "^2.1.0",
        "string-replace-webpack-plugin": "^0.1.3",
        "transform-loader": "^0.2.4",
        "webpack": "^2.3.2",
        "webpack-stream": "^3.2.0"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "7c146dabb20a28724fdb56bfd3d42f89bc7c431b",
        "tarball": "https://registry.npmjs.org/pdfmake/-/pdfmake-0.1.27.tgz"
    },
    "gitHead": "ebf896bb1d75c0da62a1cf46892478c6480cceb6",
    "homepage": "http://pdfmake.org",
    "keywords": [
        "pdf",
        "javascript",
        "printing",
        "layout"
    ],
    "license": "MIT",
    "main": "src/printer.js",
    "maintainers": [
        {
            "name": "bpampuch"
        },
        {
            "name": "danawoodman"
        },
        {
            "name": "liborm85"
        },
        {
            "name": "miltador"
        }
    ],
    "name": "pdfmake",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bpampuch/pdfmake.git"
    },
    "scripts": {
        "build": "gulp build",
        "test": "gulp"
    },
    "version": "0.1.27"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
