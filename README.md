# npmtest-electron-google-oauth

#### basic test coverage for  [electron-google-oauth (v2.0.0)](https://github.com/parro-it/electron-google-oauth#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-google-oauth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-google-oauth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-google-oauth.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-google-oauth)

#### Google api access token in electron

[![NPM](https://nodei.co/npm/electron-google-oauth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-google-oauth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-google-oauth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-electron-google-oauth/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-electron-google-oauth/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-google-oauth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-google-oauth/tree/gh-pages/build)|

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
    "author": {
        "name": "parro-it"
    },
    "bin": {
        "ego": "bin.js"
    },
    "bugs": {
        "url": "https://github.com/parro-it/electron-google-oauth/issues"
    },
    "dependencies": {
        "co": "^4.6.0",
        "googleapis": "^2.1.3",
        "node-fetch": "^1.3.2",
        "yargs": "^3.20.0"
    },
    "description": "Google api access token in electron",
    "devDependencies": {
        "electron-prebuilt": "^1.3.3",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d0853a755d166ad2ff4fbc33b3e23b1848fdd54f",
        "tarball": "https://registry.npmjs.org/electron-google-oauth/-/electron-google-oauth-2.0.0.tgz"
    },
    "files": [
        "bin.js",
        "index.js"
    ],
    "gitHead": "9e467c7566842111c65c1ab4ce939a3fd5e530a2",
    "homepage": "https://github.com/parro-it/electron-google-oauth#readme",
    "keywords": [
        "google api",
        "access token",
        "electron",
        "oauth",
        "oauth2"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "parroit"
        }
    ],
    "name": "electron-google-oauth",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/parro-it/electron-google-oauth.git"
    },
    "scripts": {
        "start": "electron bin.js --scopes https://www.google.com/m8/feeds --clientId $CLIENTID --clientSecret $CLIENTSECRET",
        "test": "xo"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
