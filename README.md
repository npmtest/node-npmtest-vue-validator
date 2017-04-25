# npmtest-vue-validator

#### basic test coverage for  [vue-validator (v2.1.7)](https://github.com/vuejs/vue-validator)  [![npm package](https://img.shields.io/npm/v/npmtest-vue-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue-validator.svg)](https://travis-ci.org/npmtest/node-npmtest-vue-validator)

#### Validator component for Vue.js

[![NPM](https://nodei.co/npm/vue-validator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-validator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue-validator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-validator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue-validator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue-validator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue-validator/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-vue-validator/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-vue-validator/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue-validator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue-validator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue-validator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue-validator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue-validator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue-validator/build/test-report.html](https://npmtest.github.io/node-npmtest-vue-validator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue-validator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue-validator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-validator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-validator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "kazuya kawaguchi"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vue-validator/issues"
    },
    "dependencies": {},
    "description": "Validator component for Vue.js",
    "devDependencies": {
        "babel-core": "^6.7.4",
        "babel-loader": "^6.2.2",
        "babel-plugin-espower": "^2.1.2",
        "babel-plugin-rewire": "^1.0.0-beta-5",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.7.4",
        "babel-polyfill": "^6.7.4",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-es2015-loose-rollup": "git+https://github.com/kazupon/babel-preset-es2015-loose-rollup.git#master",
        "component-classes": "^1.2.6",
        "conventional-changelog-cli": "^1.1.1",
        "conventional-github-releaser": "^1.1.2",
        "eslint": "^2.7.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-loader": "^1.3.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.2",
        "git-commit-message-convention": "git://github.com/kazupon/git-commit-message-convention.git",
        "istanbul-instrumenter-loader": "^0.2.0",
        "json-loader": "^0.5.4",
        "karma": "^0.13.22",
        "karma-chrome-launcher": "^0.2.0",
        "karma-coverage": "^0.5.5",
        "karma-coveralls": "^1.1.2",
        "karma-firefox-launcher": "^0.1.6",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^2.0.0",
        "karma-phantomjs-launcher": "^0.2.3",
        "karma-safari-launcher": "^0.1.1",
        "karma-sauce-launcher": "^0.3.1",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.4.5",
        "mocha-generators": "^1.2.0",
        "mocha-loader": "^0.7.1",
        "nightmare": "^2.1.6",
        "phantomjs": "^2.1.3",
        "power-assert": "^1.3.0",
        "rollup": "^0.25.2",
        "rollup-plugin-babel": "^2.2.0",
        "rollup-plugin-replace": "^1.1.0",
        "sinon": "^1.17.3",
        "uglify-js": "^2.6.1",
        "vue": "^1.0.20",
        "webpack": "^1.12.12",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "38a5fb0f7390b7f3df2ab2acd2e25055d9949228",
        "tarball": "https://registry.npmjs.org/vue-validator/-/vue-validator-2.1.7.tgz"
    },
    "files": [
        "dist/vue-validator.js",
        "dist/vue-validator.min.js",
        "dist/vue-validator.common.js",
        "src"
    ],
    "gitHead": "8c62914ce148109e6523b1fbe8399b044fb07938",
    "homepage": "https://github.com/vuejs/vue-validator",
    "jsnext:main": "src/index.js",
    "keywords": [
        "plugin",
        "validation",
        "vue",
        "vue.js"
    ],
    "license": "MIT",
    "main": "dist/vue-validator.common.js",
    "maintainers": [
        {
            "name": "kazupon"
        }
    ],
    "name": "vue-validator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vue-validator.git"
    },
    "scripts": {
        "browser": "VUE_VALIDATOR_TYPE=browser karma start config/karma.conf.js",
        "build": "node config/build.js",
        "changelog": "conventional-changelog -i CHANGELOG.md -s -n ./node_modules/git-commit-message-convention/convention.js",
        "ci": "npm run lint && npm run coverage && npm run coveralls && npm run e2e",
        "clean": "rm -rf coverage && rm -rf dist/*.js*",
        "coolkids": "VUE_VALIDATOR_TYPE=sauce SAUCE=batch1 karma start config/karma.conf.js",
        "coverage": "VUE_VALIDATOR_TYPE=coverage karma start config/karma.conf.js",
        "coveralls": "VUE_VALIDATOR_TYPE=coveralls karma start config/karma.conf.js",
        "dev": "webpack-dev-server --quite --config config/webpack.dev.conf.js --host 0.0.0.0",
        "dev-test": "webpack-dev-server --quiet --config config/webpack.test.conf.js --host 0.0.0.0",
        "docs": "cd docs && gitbook serve",
        "docs-deploy": "cd docs && rm -rf _book && gitbook build && cd _book && git init && git add -A && git commit -m 'update book' && git push -f git@github.com:vuejs/vue-validator.git master:gh-pages && cd .. && cd ..",
        "e2e": "webpack-dev-server --quiet --config config/webpack.e2e.conf.js & mocha --opts test/e2e/mocha.opts --harmony test/e2e/test.js && kill $! || (kill $! && exit 1)",
        "ie": "VUE_VALIDATOR_TYPE=sauce SAUCE=batch2 karma start config/karma.conf.js",
        "lint": "eslint src config test/specs",
        "mobile": "VUE_VALIDATOR_TYPE=sauce SAUCE=batch3 karma start config/karma.conf.js",
        "release": "conventional-github-releaser -n ./node_modules/git-commit-message-convention/convention.js",
        "sauce": "npm run coolkids && npm run ie && npm run mobile",
        "test": "npm run ci",
        "unit": "karma start config/karma.conf.js"
    },
    "version": "2.1.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
