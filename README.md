# npmtest-electron-google-oauth

#### basic test coverage for  electron-google-oauth (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-google-oauth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-google-oauth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-google-oauth.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-google-oauth)

#### Google api access token in electron

[![NPM](https://nodei.co/npm/electron-google-oauth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-google-oauth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-google-oauth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-google-oauth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-google-oauth/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-google-oauth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-google-oauth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-google-oauth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-google-oauth/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-google-oauth",
    "description": "Google api access token in electron",
    "keywords": [
        "google api",
        "access token",
        "electron",
        "oauth",
        "oauth2"
    ],
    "repository": "parro-it/electron-google-oauth",
    "version": "2.0.0",
    "bin": {
        "ego": "bin.js"
    },
    "dependencies": {
        "co": "^4.6.0",
        "googleapis": "^2.1.3",
        "node-fetch": "^1.3.2",
        "yargs": "^3.20.0"
    },
    "files": [
        "bin.js",
        "index.js"
    ],
    "author": "parro-it",
    "scripts": {
        "test": "xo",
        "start": "electron bin.js --scopes https://www.google.com/m8/feeds --clientId $CLIENTID --clientSecret $CLIENTSECRET"
    },
    "devDependencies": {
        "electron-prebuilt": "^1.3.3",
        "xo": "^0.16.0"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
