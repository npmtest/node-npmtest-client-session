# npmtest-client-session

#### basic test coverage for  [client-session (v0.1.7)](https://github.com/DoubleSpout/nodeClientSession)  [![npm package](https://img.shields.io/npm/v/npmtest-client-session.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-client-session) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-client-session.svg)](https://travis-ci.org/npmtest/node-npmtest-client-session)

#### cookie session for nodejs, store session in client browers's cookie, support Cross Process session without database store

[![NPM](https://nodei.co/npm/client-session.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/client-session)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-client-session/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-client-session/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-client-session/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-client-session/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-client-session/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-client-session/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-client-session/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-client-session/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-client-session/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-client-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-client-session/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-client-session/build/test-report.html](https://npmtest.github.io/node-npmtest-client-session/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-client-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-client-session/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-client-session/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-client-session/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-client-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-client-session/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-client-session/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-client-session/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "doublespout",
        "url": "http://snoopyxdy.blog.163.com"
    },
    "name": "client-session",
    "description": "cookie session for nodejs, store session in client browers's cookie, support Cross Process session without database store",
    "keywords": [
        "cookie session",
        "cookie",
        "session",
        "client session",
        "cookie",
        "process",
        "Cross Process"
    ],
    "version": "0.1.7",
    "url": "https://github.com/DoubleSpout/nodeClientSession",
    "homepage": "https://github.com/DoubleSpout/nodeClientSession",
    "repository": {
        "type": "git",
        "url": "https://github.com/DoubleSpout/nodeClientSession.git"
    },
    "main": "index.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "cookie": "0.1.2"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "tset": "node ./test/main.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
