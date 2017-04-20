# npmtest-uglifyify

#### basic test coverage for  uglifyify (v3.0.4)  [![npm package](https://img.shields.io/npm/v/npmtest-uglifyify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-uglifyify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-uglifyify.svg)](https://travis-ci.org/npmtest/node-npmtest-uglifyify)

#### A browserify transform which minifies your code using UglifyJS2

[![NPM](https://nodei.co/npm/uglifyify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/uglifyify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-uglifyify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-uglifyify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-uglifyify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-uglifyify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-uglifyify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-uglifyify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-uglifyify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-uglifyify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-uglifyify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-uglifyify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-uglifyify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-uglifyify/build/test-report.html](https://npmtest.github.io/node-npmtest-uglifyify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-uglifyify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-uglifyify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-uglifyify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-uglifyify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-uglifyify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-uglifyify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-uglifyify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-uglifyify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "uglifyify",
    "version": "3.0.4",
    "description": "A browserify transform which minifies your code using UglifyJS2",
    "main": "index.js",
    "dependencies": {
        "convert-source-map": "~1.1.0",
        "extend": "^1.2.1",
        "minimatch": "^3.0.2",
        "through": "~2.3.4",
        "uglify-js": "2.x.x"
    },
    "devDependencies": {
        "bl": "^0.9.3",
        "browserify": "^8.1.1",
        "from2": "^1.3.0",
        "tap-spec": "^2.1.2",
        "tape": "^3.2.0",
        "wrap-stream": "^2.0.0"
    },
    "scripts": {
        "test": "node test | tap-spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/uglifyify.git"
    },
    "keywords": [
        "uglify",
        "minify",
        "compress",
        "compile",
        "browserify",
        "transform",
        "stream"
    ],
    "author": "Hugh Kennedy <hughskennedy@gmail.com> (http://hughskennedy.com/)",
    "license": "MIT",
    "readmeFilename": "README.md"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
