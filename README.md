# npmtest-pug-lint

#### basic test coverage for  [pug-lint (v2.4.0)](https://github.com/pugjs/pug-lint)  [![npm package](https://img.shields.io/npm/v/npmtest-pug-lint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pug-lint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pug-lint.svg)](https://travis-ci.org/npmtest/node-npmtest-pug-lint)

#### An unopinionated and configurable linter and style checker for Pug (formerly Jade)

[![NPM](https://nodei.co/npm/pug-lint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pug-lint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pug-lint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pug-lint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pug-lint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pug-lint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pug-lint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pug-lint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pug-lint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pug-lint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pug-lint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pug-lint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pug-lint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pug-lint/build/test-report.html](https://npmtest.github.io/node-npmtest-pug-lint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pug-lint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pug-lint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pug-lint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pug-lint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pug-lint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pug-lint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pug-lint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pug-lint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Edwards"
    },
    "bin": {
        "pug-lint": "./bin/pug-lint"
    },
    "bugs": {
        "url": "https://github.com/pugjs/pug-lint/issues"
    },
    "dependencies": {
        "acorn": "^4.0.1",
        "commander": "^2.9.0",
        "css-selector-parser": "^1.1.0",
        "find-line-column": "^0.5.2",
        "glob": "^7.0.3",
        "minimatch": "^3.0.3",
        "path-is-absolute": "^1.0.0",
        "pug-attrs": "^2.0.1",
        "pug-error": "^1.3.0",
        "pug-lexer": "^2.0.1",
        "resolve": "^1.1.7",
        "strip-json-comments": "^2.0.1",
        "void-elements": "^2.0.1"
    },
    "description": "An unopinionated and configurable linter and style checker for Pug (formerly Jade)",
    "devDependencies": {
        "camel-case": "^3.0.0",
        "changelog": "^1.0.7",
        "david": "^7.0.0",
        "docco": "^0.7.0",
        "istanbul": "^0.4.0",
        "jsinspect": "^0.8.0",
        "mocha": "^2.3.3",
        "moment": "^2.11.2",
        "no-case": "^2.3.0",
        "pliers": "^1.2.1",
        "pug-lint-config-clock": "^1.1.0",
        "rimraf": "^2.5.2",
        "semver-regex": "^1.0.0",
        "sinon": "^1.17.2",
        "xo": "^0.15.1",
        "yeoman-generator": "^0.23.3",
        "yo": "^1.8.4"
    },
    "directories": {},
    "dist": {
        "shasum": "1f584c1624fac48e5a0d03e40823caef736702e0",
        "tarball": "https://registry.npmjs.org/pug-lint/-/pug-lint-2.4.0.tgz"
    },
    "gitHead": "d87bbb3f8e7d95228c03e5ffac6a2c4dd7dc59b4",
    "homepage": "https://github.com/pugjs/pug-lint",
    "keywords": [
        "puglint",
        "jadelint",
        "pug-lint",
        "jade-lint",
        "pug",
        "jade",
        "lint",
        "code style",
        "formatter",
        "style guide",
        "validate",
        "lint pug",
        "lint jade",
        "pug lint",
        "jade lint",
        "linter",
        "linter pug",
        "linter jade",
        "pug linter",
        "jade linter",
        "pug-linter",
        "jade-linter",
        "linting",
        "linting pug",
        "linting jade",
        "pug linting",
        "jade linting",
        "pug-linting",
        "jade-linting",
        "hint",
        "hint pug",
        "hint jade",
        "pug hint",
        "jade hint",
        "pug-hint",
        "jade-hint",
        "hinter",
        "hinter pug",
        "hinter jade",
        "pug hinter",
        "jade hinter",
        "pug-hinter",
        "jade-hinter",
        "hinting",
        "hinting pug",
        "hinting jade",
        "pug hinting",
        "jade hinting",
        "pug-hinting",
        "jade-hinting"
    ],
    "license": "ISC",
    "main": "./lib/linter",
    "maintainers": [
        {
            "name": "benedfit"
        },
        {
            "name": "forbeslindesay"
        },
        {
            "name": "timothygu"
        }
    ],
    "name": "pug-lint",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "http://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/pugjs/pug-lint.git"
    },
    "scripts": {
        "changelog": "pliers buildChangelog",
        "coverage": "istanbul cover ./node_modules/mocha/bin/_mocha test",
        "depcheck": "david",
        "docs": "pliers buildRuleDocs",
        "inspect": "jsinspect",
        "lint": "xo",
        "posttest": "(istanbul check-coverage --statements 90 --branches 90 --functions 100 --lines 90 && rimraf coverage) || echo Look at 'coverage/lcov-report/index.html' to find out more",
        "pretest": "npm run docs && npm run schema && npm run lint",
        "schema": "pliers buildJsonSchema",
        "test": "npm run coverage"
    },
    "version": "2.4.0",
    "xo": {
        "space": true,
        "envs": [
            "node",
            "mocha"
        ],
        "ignores": [
            "generators/*-templates/**"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
