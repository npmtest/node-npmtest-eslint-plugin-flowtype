# npmtest-eslint-plugin-flowtype

#### basic test coverage for  [eslint-plugin-flowtype (v2.32.1)](https://github.com/gajus/eslint-plugin-flowtype#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-flowtype.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-flowtype) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-flowtype.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-flowtype)

#### Flowtype linting rules for ESLint.

[![NPM](https://nodei.co/npm/eslint-plugin-flowtype.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-flowtype)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-flowtype/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-flowtype/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-flowtype/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-flowtype/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-flowtype/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-flowtype/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-flowtype/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gajus Kuizinas",
        "url": "http://gajus.com"
    },
    "bugs": {
        "url": "https://github.com/gajus/eslint-plugin-flowtype/issues"
    },
    "dependencies": {
        "lodash": "^4.15.0"
    },
    "description": "Flowtype linting rules for ESLint.",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-eslint": "^6.1.2",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-object-rest-spread": "^6.23.0",
        "babel-preset-env": "^1.1.10",
        "babel-register": "^6.14.0",
        "chai": "^3.5.0",
        "eslint": "^3.16.0",
        "eslint-config-canonical": "1.8.1",
        "gitdown": "^2.5.0",
        "husky": "^0.11.7",
        "jsonlint": "^1.6.2",
        "mocha": "^3.0.2",
        "semantic-release": "^6.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "bbee185dedf97e5f63ec975cdcddd199bd2a2501",
        "tarball": "https://registry.npmjs.org/eslint-plugin-flowtype/-/eslint-plugin-flowtype-2.32.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "bb444dbf2301d870eea820a2e4ee69295e3a3dd8",
    "homepage": "https://github.com/gajus/eslint-plugin-flowtype#readme",
    "keywords": [
        "eslint",
        "plugin",
        "flowtype"
    ],
    "license": "BSD-3-Clause",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "gajus"
        }
    ],
    "name": "eslint-plugin-flowtype",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": ">=2.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gajus/eslint-plugin-flowtype.git"
    },
    "scripts": {
        "build": "babel ./src --out-dir ./dist --copy-files",
        "documentation": "gitdown ./.README/README.md --output-file ./README.md; npm run documentation-add-assertions",
        "documentation-add-assertions": "babel-node ./bin/readmeAssertions",
        "format-json": "jsonlint --sort-keys --in-place --indent '  ' ./src/configs/recommended.json && echo '' >> ./src/configs/recommended.json",
        "lint": "eslint ./src ./tests",
        "precommit": "npm run lint && npm run test && npm run format-json",
        "test": "mocha --compilers js:babel-register ./tests/rules/index.js"
    },
    "version": "2.32.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
