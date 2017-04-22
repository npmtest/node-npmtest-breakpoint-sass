# npmtest-breakpoint-sass

#### basic test coverage for  [breakpoint-sass (v2.7.1)](https://github.com/Team-Sass/breakpoint)  [![npm package](https://img.shields.io/npm/v/npmtest-breakpoint-sass.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-breakpoint-sass) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-breakpoint-sass.svg)](https://travis-ci.org/npmtest/node-npmtest-breakpoint-sass)

#### Really Simple Media Queries with Sass

[![NPM](https://nodei.co/npm/breakpoint-sass.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/breakpoint-sass)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-breakpoint-sass/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-breakpoint-sass/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-breakpoint-sass/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-breakpoint-sass/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-breakpoint-sass/build/test-report.html](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-breakpoint-sass/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-breakpoint-sass/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-breakpoint-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-breakpoint-sass/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-breakpoint-sass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "breakpoint-sass",
    "version": "2.7.1",
    "description": "Really Simple Media Queries with Sass",
    "main": "stylesheets/_breakpoint.scss",
    "eyeglass": {
        "needs": "^1.0.0",
        "exports": "eyeglass-exports.js",
        "name": "breakpoint"
    },
    "directories": {
        "test": "tests"
    },
    "keywords": [
        "sass",
        "responsive",
        "rwd",
        "eyeglass-module",
        "breakpoint"
    ],
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "bump:major": "node .bump.js --major",
        "bump:minor": "node .bump.js --minor",
        "bump:patch": "node .bump.js --patch",
        "publish": "node .gembuild.js && git push && git push origin --tags"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Team-Sass/breakpoint.git"
    },
    "author": "",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Team-Sass/breakpoint/issues"
    },
    "homepage": "https://github.com/Team-Sass/breakpoint",
    "devDependencies": {
        "diff": "^1.2.1",
        "fs-extra": "^0.14.0",
        "glob": "^4.3.2",
        "node-sass": "^3.0.0",
        "nodegit": "^0.11.2",
        "semver": "^5.1.0",
        "yargs": "^4.1.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
