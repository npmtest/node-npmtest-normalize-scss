# npmtest-normalize-scss

#### basic test coverage for  [normalize-scss (v6.0.0)](https://github.com/JohnAlbin/normalize-scss)  [![npm package](https://img.shields.io/npm/v/npmtest-normalize-scss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-normalize-scss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-normalize-scss.svg)](https://travis-ci.org/npmtest/node-npmtest-normalize-scss)

#### This is the Sass version of Normalize.css, a collection of HTML element and attribute rulesets to normalize styles across all browsers. This port aims to use a light dusting of Sass to make Normalize even easier to integrate with your website.

[![NPM](https://nodei.co/npm/normalize-scss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/normalize-scss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-normalize-scss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-normalize-scss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-normalize-scss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-normalize-scss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-normalize-scss/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-normalize-scss/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-normalize-scss/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-normalize-scss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-normalize-scss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-normalize-scss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-normalize-scss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-normalize-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-normalize-scss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-normalize-scss/build/test-report.html](https://npmtest.github.io/node-npmtest-normalize-scss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-normalize-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-normalize-scss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-normalize-scss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-normalize-scss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-normalize-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-normalize-scss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-normalize-scss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-normalize-scss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "normalize-scss",
    "version": "6.0.0",
    "description": "This is the Sass version of Normalize.css, a collection of HTML element and attribute rulesets to normalize styles across all browsers. This port aims to use a light dusting of Sass to make Normalize even easier to integrate with your website.",
    "homepage": "https://github.com/JohnAlbin/normalize-scss",
    "bugs": {
        "url": "https://github.com/JohnAlbin/normalize-scss/issues"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/JohnAlbin/normalize-scss.git"
    },
    "author": "John Albin Wilkins <virtually.johnalbin@gmail.com> (http://john.albin.net/)",
    "keywords": [
        "eyeglass-module",
        "sass",
        "normalize"
    ],
    "main": "sass/_normalize.scss",
    "style": "sass/_normalize.scss",
    "eyeglass": {
        "sassDir": "sass",
        "exports": false,
        "name": "normalize",
        "needs": "*"
    },
    "directories": {
        "lib": "sass",
        "test": "test"
    },
    "scripts": {
        "test": "mocha",
        "posttest": "eslint test",
        "test-only": "mocha"
    },
    "license": "(MIT OR GPL-2.0)",
    "devDependencies": {
        "chai": "^3.5.0",
        "chroma-sass": "^1.2.3",
        "eslint": "^3.8.0",
        "eyeglass": "^1.1.2",
        "mocha": "^3.1.2",
        "sassy-test": "^3.0.0",
        "typey": "^1.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
