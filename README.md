# npmtest-http-signature

#### basic test coverage for  [http-signature (v1.1.1)](https://github.com/joyent/node-http-signature/)  [![npm package](https://img.shields.io/npm/v/npmtest-http-signature.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-http-signature) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-http-signature.svg)](https://travis-ci.org/npmtest/node-npmtest-http-signature)

#### Reference implementation of Joyent's HTTP Signature scheme.

[![NPM](https://nodei.co/npm/http-signature.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/http-signature)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-http-signature/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-signature/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-http-signature/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-http-signature/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-http-signature/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-http-signature/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-http-signature/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-http-signature/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-http-signature/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-signature/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-http-signature/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-http-signature/build/test-report.html](https://npmtest.github.io/node-npmtest-http-signature/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-http-signature/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-http-signature/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-http-signature/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-http-signature/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-signature/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-signature/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-http-signature/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-http-signature/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joyent, Inc"
    },
    "bugs": {
        "url": "https://github.com/joyent/node-http-signature/issues"
    },
    "contributors": [
        {
            "name": "Mark Cavage"
        },
        {
            "name": "David I. Lehn"
        },
        {
            "name": "Patrick Mooney"
        }
    ],
    "dependencies": {
        "assert-plus": "^0.2.0",
        "jsprim": "^1.2.2",
        "sshpk": "^1.7.0"
    },
    "description": "Reference implementation of Joyent's HTTP Signature scheme.",
    "devDependencies": {
        "node-uuid": "^1.4.1",
        "tap": "0.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "df72e267066cd0ac67fb76adf8e134a8fbcf91bf",
        "tarball": "https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.8",
        "npm": ">=1.3.7"
    },
    "gitHead": "74d3f35e3aa436d83723c53b01e266f448e8149a",
    "homepage": "https://github.com/joyent/node-http-signature/",
    "keywords": [
        "https",
        "request"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "arekinath"
        },
        {
            "name": "mcavage"
        },
        {
            "name": "pfmooney"
        }
    ],
    "name": "http-signature",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/joyent/node-http-signature.git"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
