# npmtest-sails-roles

#### basic test coverage for  [sails-roles (v0.1.3)](https://github.com/Cornik34/sails-roles)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-roles.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-roles) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-roles.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-roles)

#### roles and groups system management for sails and waterline

[![NPM](https://nodei.co/npm/sails-roles.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-roles)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-roles/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-roles/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-roles/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-roles/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-roles/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-roles/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-roles/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-roles/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-roles/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-roles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-roles/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-roles/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-roles/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-roles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-roles/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-roles/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-roles/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-roles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-roles/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-roles/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-roles/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sails-roles",
    "version": "0.1.3",
    "description": "roles and groups system management for sails and waterline",
    "main": "api/hooks/sails-roles.js",
    "scripts": {
        "test": "rm -rf .tmp && mocha --reporter spec"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Cornik34/sails-roles.git"
    },
    "keywords": [
        "sails",
        "sails.js",
        "waterline",
        "role",
        "roles",
        "group",
        "groupes",
        "permission",
        "permissions",
        "security",
        "entitlement",
        "access",
        "restriction"
    ],
    "author": "Lancelot Prigent <lancelot.prigent@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Cornik34/sails-roles/issues"
    },
    "homepage": "https://github.com/Cornik34/sails-roles",
    "sails": {
        "isHook": true
    },
    "devDependencies": {
        "eslint": "^1.1.0",
        "mocha": "^2.2.5",
        "sails": "^0.11.0",
        "supertest": "^1.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
