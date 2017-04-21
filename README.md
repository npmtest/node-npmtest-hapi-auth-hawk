# npmtest-hapi-auth-hawk

#### basic test coverage for  hapi-auth-hawk (v3.0.1)  [![npm package](https://img.shields.io/npm/v/npmtest-hapi-auth-hawk.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hapi-auth-hawk) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hapi-auth-hawk.svg)](https://travis-ci.org/npmtest/node-npmtest-hapi-auth-hawk)

#### Hawk authentication plugin

[![NPM](https://nodei.co/npm/hapi-auth-hawk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hapi-auth-hawk)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hapi-auth-hawk/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hapi-auth-hawk/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/test-report.html](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hapi-auth-hawk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hapi-auth-hawk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hapi-auth-hawk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hapi-auth-hawk/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hapi-auth-hawk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hapi-auth-hawk",
    "description": "Hawk authentication plugin",
    "version": "3.0.1",
    "repository": "git://github.com/hapijs/hapi-auth-hawk",
    "main": "lib/index.js",
    "keywords": [
        "hapi",
        "plugin",
        "auth",
        "hawk",
        "bewit"
    ],
    "engines": {
        "node": ">=0.10.33"
    },
    "dependencies": {
        "boom": "2.x.x",
        "hoek": "2.x.x",
        "hawk": "3.x.x"
    },
    "peerDependencies": {
        "hapi": ">=8.x.x"
    },
    "devDependencies": {
        "code": "1.x.x",
        "hapi": "8.x.x",
        "lab": "6.x.x"
    },
    "scripts": {
        "test": "lab -r console -t 100 -a code -L",
        "test-cov-html": "lab -r html -o coverage.html -a code -L"
    },
    "license": "BSD-3-Clause"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
