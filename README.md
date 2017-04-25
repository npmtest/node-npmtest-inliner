# npmtest-inliner

#### basic test coverage for  [inliner (v1.12.1)](http://github.com/remy/inliner)  [![npm package](https://img.shields.io/npm/v/npmtest-inliner.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-inliner) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-inliner.svg)](https://travis-ci.org/npmtest/node-npmtest-inliner)

#### Utility to inline images, CSS and JavaScript for a web page - useful for mobile sites

[![NPM](https://nodei.co/npm/inliner.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inliner)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-inliner/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-inliner/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-inliner/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-inliner/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-inliner/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-inliner/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-inliner/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-inliner/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-inliner/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-inliner/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-inliner/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-inliner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-inliner/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-inliner/build/test-report.html](https://npmtest.github.io/node-npmtest-inliner/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-inliner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-inliner/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-inliner/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inliner/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inliner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inliner/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-inliner/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-inliner/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Remy Sharp"
    },
    "bin": {
        "inliner": "cli/index.js"
    },
    "bugs": {
        "url": "https://github.com/remy/inliner/issues"
    },
    "config": {
        "validate-commit-msg": {
            "helpMessage": "\n-----------\n\nThere was a small validation problem with your commit message:\n\n> %s\n\nIt's not a huge problem, but a valid commit message will ensure\nwhether your commit triggers a release or not (and sometimes the\ncommit won't need to trigger a release). If you really need to, you\ncan skip the validation using 'git commit --no-verify'.\n\nIf your commit is a fix, it might want to be:\n\n> fix: storage bug\n\nOr a feature:\n\n> feat: added new storage process\n\nThere's also 'docs', 'test' and 'chore' and a few more. To read\nhow the commit message should be formatted, please see this short\npost: https://git.io/vVCIR\n"
        },
        "ghooks": {
            "commit-msg": "validate-commit-msg",
            "pre-push": "npm test"
        }
    },
    "dependencies": {
        "ansi-escapes": "^1.4.0",
        "ansi-styles": "^2.2.1",
        "chalk": "^1.1.3",
        "charset": "^1.0.0",
        "cheerio": "^0.19.0",
        "debug": "^2.2.0",
        "es6-promise": "^2.3.0",
        "iconv-lite": "^0.4.11",
        "jschardet": "^1.3.0",
        "lodash.assign": "^3.2.0",
        "lodash.defaults": "^3.1.2",
        "lodash.foreach": "^3.0.3",
        "mime": "^1.3.4",
        "minimist": "^1.1.3",
        "request": "^2.74.0",
        "svgo": "^0.6.6",
        "then-fs": "^2.0.0",
        "uglify-js": "^2.8.0",
        "update-notifier": "^0.5.0"
    },
    "description": "Utility to inline images, CSS and JavaScript for a web page - useful for mobile sites",
    "devDependencies": {
        "ghooks": "^1.1.1",
        "jscs": "^2.0.0",
        "semantic-release": "^4.0.0",
        "st": "^0.5.5",
        "tap": "^5.4.2",
        "tap-only": "0.0.5",
        "validate-commit-msg": "^2.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "60848eca6ad9d36228d2886721821b44bc5597d4",
        "tarball": "https://registry.npmjs.org/inliner/-/inliner-1.12.1.tgz"
    },
    "gitHead": "552851733ce175ab7f4e6397855159a08900d8a5",
    "homepage": "http://github.com/remy/inliner",
    "keywords": [
        "mobile",
        "inline",
        "production",
        "build",
        "minify"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "remy"
        }
    ],
    "name": "inliner",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/remy/inliner.git"
    },
    "scripts": {
        "cover": "tap test/*.test.js --cov --coverage-report=lcov",
        "lint": "jscs -v cli/*.js lib/*.js",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "tap": "tap test/*.test.js --cov -R spec",
        "test": "npm run lint && npm run tap"
    },
    "version": "1.12.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
