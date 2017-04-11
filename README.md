# test coverage for  [acl (v0.4.10)](https://github.com/optimalbits/node_acl)  [![npm package](https://img.shields.io/npm/v/npmtest-acl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-acl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-acl.svg)](https://travis-ci.org/npmtest/node-npmtest-acl)
#### An Access Control List module, based on Redis with Express middleware support

[![NPM](https://nodei.co/npm/acl.png?downloads=true)](https://www.npmjs.com/package/acl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-acl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-acl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-acl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-acl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-acl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-acl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-acl/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-acl/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-acl/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-acl/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-acl%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-acl/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-acl/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-acl%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-acl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-acl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-acl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Manuel Astudillo",
        "email": "manuel@optimalbits.com"
    },
    "bugs": {
        "url": "https://github.com/optimalbits/node_acl/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "bluebird": "^3.0.2",
        "lodash": "^4.17.3",
        "mongodb": "^2.0.47",
        "redis": "^2.2.5"
    },
    "description": "An Access Control List module, based on Redis with Express middleware support",
    "devDependencies": {
        "chai": "^3.4.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f7aa672421cd1ef7da74674577b2c6a9052cf9bd",
        "tarball": "https://registry.npmjs.org/acl/-/acl-0.4.10.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "e69042e5c415830196f4872ee3b753ceb7adfa19",
    "homepage": "https://github.com/optimalbits/node_acl",
    "keywords": [
        "middleware",
        "acl",
        "web"
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "manast",
            "email": "manuel@optimalbits.com"
        }
    ],
    "name": "acl",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/optimalbits/node_acl.git"
    },
    "scripts": {
        "cover": "istanbul cover -- _mocha test/runner.js --reporter spec",
        "test": "mocha test/runner.js --reporter spec"
    },
    "version": "0.4.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
