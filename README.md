# test coverage for  [cookie-session (v1.2.0)](https://github.com/expressjs/cookie-session)  [![npm package](https://img.shields.io/npm/v/npmtest-cookie-session.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cookie-session) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cookie-session.svg)](https://travis-ci.org/npmtest/node-npmtest-cookie-session)
#### cookie session middleware

[![NPM](https://nodei.co/npm/cookie-session.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cookie-session)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cookie-session/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookie-session/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cookie-session/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cookie-session/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cookie-session/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cookie-session/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cookie-session/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cookie-session/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cookie-session/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookie-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cookie-session/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cookie-session/build/test-report.html](https://npmtest.github.io/node-npmtest-cookie-session/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cookie-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cookie-session/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cookie-session/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cookie-session/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cookie-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cookie-session/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cookie-session/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cookie-session/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/cookie-session/issues"
    },
    "dependencies": {
        "cookies": "0.5.0",
        "debug": "~2.2.0",
        "on-headers": "~1.0.0"
    },
    "description": "cookie session middleware",
    "devDependencies": {
        "connect": "3",
        "istanbul": "0.3.17",
        "mocha": "2.2.5",
        "supertest": "1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9df2beb9e723998e70d1e31fda37b28a0bcf37ff",
        "tarball": "https://registry.npmjs.org/cookie-session/-/cookie-session-1.2.0.tgz"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "24334af3dd2da23b5cc6dc23ec75ed37a0de2bc3",
    "homepage": "https://github.com/expressjs/cookie-session",
    "keywords": [
        "connect",
        "express",
        "middleware",
        "session"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jongleberry"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "cookie-session",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/cookie-session.git"
    },
    "scripts": {
        "test": "mocha --check-leaks --reporter spec --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec test/"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
