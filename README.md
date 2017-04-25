# npmtest-gulp-inline

#### basic test coverage for  [gulp-inline (v0.1.3)](https://github.com/ashaffer/gulp-inline)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-inline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-inline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-inline.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-inline)

#### Inline styles and scripts into an html file.

[![NPM](https://nodei.co/npm/gulp-inline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-inline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-inline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-inline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-inline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-inline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-inline/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-inline/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-inline/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-inline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-inline/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-inline/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-inline/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-inline/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-inline/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-inline/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-inline/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-inline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-inline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-inline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-inline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-inline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-inline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ashaffer"
    },
    "bugs": {
        "url": "https://github.com/ashaffer/gulp-inline/issues"
    },
    "dependencies": {
        "cheerio": "^0.22.0",
        "event-stream": "^3.3.4",
        "gulp-util": "^3.0.7",
        "through2": "^2.0.3"
    },
    "description": "Inline styles and scripts into an html file.",
    "devDependencies": {
        "eslint": "3.x",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "gulp": "^3.8.7",
        "istanbul": "x",
        "mocha": "x",
        "readable-stream": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "89876a9c934e451d76bbcb64cc0244ac0e59b47c",
        "tarball": "https://registry.npmjs.org/gulp-inline/-/gulp-inline-0.1.3.tgz"
    },
    "gitHead": "781658b276020776bc37aa0d6fada8d7f244d3a4",
    "homepage": "https://github.com/ashaffer/gulp-inline",
    "keywords": [
        "inline",
        "gulp",
        "gulpplugin",
        "gulp inline",
        "inline css",
        "inline js",
        "compress html"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ashaffer88"
        }
    ],
    "name": "gulp-inline",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ashaffer/gulp-inline.git"
    },
    "scripts": {
        "coverage": "'npm bin'/istanbul cover 'npm bin'/_mocha -- --reporter min",
        "lint": "'npm bin'/eslint ./",
        "test": "'npm bin'/mocha"
    },
    "standard": {
        "globals": [
            "it",
            "describe"
        ]
    },
    "version": "0.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
