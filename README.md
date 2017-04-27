# npmdoc-appmetrics

#### basic api documentation for  [appmetrics (v3.0.1)](https://github.com/RuntimeTools/appmetrics#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-appmetrics.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-appmetrics) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-appmetrics.svg)](https://travis-ci.org/npmdoc/node-npmdoc-appmetrics)

#### Node Application Metrics

[![NPM](https://nodei.co/npm/appmetrics.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/appmetrics)

- [https://npmdoc.github.io/node-npmdoc-appmetrics/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-appmetrics/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-appmetrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-appmetrics/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-appmetrics/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-appmetrics/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bin": {
        "node-hc": "bin/appmetrics-cli.js"
    },
    "bugs": {
        "url": "https://github.com/RuntimeTools/appmetrics/issues"
    },
    "bundleDependencies": [
        "tar"
    ],
    "dependencies": {
        "jszip": "2.5.x",
        "nan": "2.x",
        "tar": "2.x"
    },
    "description": "Node Application Metrics",
    "devDependencies": {
        "node-gyp": "3.x",
        "semver": "^5.3.0",
        "tap": "7.x"
    },
    "directories": {
        "lib": "lib",
        "probes": "probes"
    },
    "dist": {
        "shasum": "949411e6e54c9740546103db7761fe571fb3f5a2",
        "tarball": "https://registry.npmjs.org/appmetrics/-/appmetrics-3.0.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "homepage": "https://github.com/RuntimeTools/appmetrics#readme",
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "colegate"
        },
        {
            "name": "seabaylea"
        },
        {
            "name": "stalleyj"
        },
        {
            "name": "tobycorbin"
        },
        {
            "name": "tunniclm"
        }
    ],
    "name": "appmetrics",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/RuntimeTools/appmetrics.git"
    },
    "scripts": {
        "install": "node extract_all_binaries.js || node-gyp rebuild",
        "test": "tap --reporter tap --timeout=120 tests/*tests.js tests/probes/http-outbound-probe-test.js tests/probes/http-probe-test.js tests/headless_test.js"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
