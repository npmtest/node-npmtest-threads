# npmtest-threads

#### basic test coverage for  [threads (v0.7.2)](https://github.com/andywer/thread.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-threads.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-threads) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-threads.svg)](https://travis-ci.org/npmtest/node-npmtest-threads)

#### Easy to use, yet powerful multi-threading library for node.js and the browser!

[![NPM](https://nodei.co/npm/threads.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/threads)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-threads/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-threads/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-threads/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-threads/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-threads/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-threads/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-threads/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-threads/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-threads/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-threads/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-threads/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-threads/build/test-report.html](https://npmtest.github.io/node-npmtest-threads/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-threads/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-threads/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-threads/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-threads/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-threads/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-threads/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-threads/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-threads/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andy Wermke"
    },
    "babel": {
        "presets": [
            "es2015",
            "es2015-loose"
        ]
    },
    "browser": {
        "child_process": false,
        "os": false,
        "path": false
    },
    "bugs": {
        "url": "https://github.com/andywer/thread.js/issues"
    },
    "dependencies": {
        "eventemitter3": "^2.0.2",
        "native-promise-only": "^0.8.1"
    },
    "description": "Easy to use, yet powerful multi-threading library for node.js and the browser!",
    "devDependencies": {
        "async": "^1.4.2",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-es2015-loose": "^8.0.0",
        "browserify": "^13.1.1",
        "codeclimate-test-reporter": "^0.4.0",
        "coveralls": "^2.11.4",
        "expect.js": "^0.3.1",
        "gulp": "^3.8.11",
        "gulp-babel": "^6.1.2",
        "gulp-concat": "^2.5.2",
        "gulp-eslint": "^3.0.1",
        "gulp-mocha": "^3.0.1",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-uglify": "^2.0.0",
        "istanbul": "^0.4.0",
        "karma": "^1.3.0",
        "karma-browserify": "^4.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-expect": "^1.1.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "mocha": "^3.1.2",
        "phantomjs": "^1.9.18",
        "sinon": "^1.16.1",
        "through2": "^2.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "852ab7053d43a1dd3b3ef88e1563abb6245068bf",
        "tarball": "https://registry.npmjs.org/threads/-/threads-0.7.2.tgz"
    },
    "gitHead": "d0c0f3e281cb8df233710860be95b075730e516e",
    "homepage": "https://github.com/andywer/thread.js#readme",
    "keywords": [
        "threads",
        "web worker",
        "cluster",
        "child_process",
        "threadpool",
        "spawn",
        "fork",
        "parallel"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "andywer"
        }
    ],
    "name": "threads",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andywer/thread.js.git"
    },
    "scripts": {
        "build": "gulp dist",
        "test": "gulp test"
    },
    "version": "0.7.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
