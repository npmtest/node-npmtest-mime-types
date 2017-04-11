# test coverage for  [mime-types (v2.1.15)](https://github.com/jshttp/mime-types#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mime-types.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mime-types) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mime-types.svg)](https://travis-ci.org/npmtest/node-npmtest-mime-types)
#### The ultimate javascript content-type utility.

[![NPM](https://nodei.co/npm/mime-types.png?downloads=true)](https://www.npmjs.com/package/mime-types)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mime-types/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mime-types/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mime-types/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mime-types/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mime-types/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mime-types/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mime-types/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mime-types/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-mime-types/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-mime-types/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-mime-types%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mime-types/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mime-types/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mime-types%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mime-types/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mime-types/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mime-types/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/mime-types/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "Jeremiah Senkpiel",
            "email": "fishrock123@rocketmail.com",
            "url": "https://searchbeam.jit.su"
        },
        {
            "name": "Jonathan Ong",
            "email": "me@jongleberry.com",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "mime-db": "~1.27.0"
    },
    "description": "The ultimate javascript content-type utility.",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "a4ebf5064094569237b8cf70046776d09fc92aed",
        "tarball": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.15.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "c44863eb0463ee16f3eb04576591cc4c4d6b214c",
    "homepage": "https://github.com/jshttp/mime-types#readme",
    "keywords": [
        "mime",
        "types"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        }
    ],
    "name": "mime-types",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/mime-types.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec test/test.js",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot test/test.js",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot test/test.js"
    },
    "version": "2.1.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
