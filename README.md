# test coverage for  [applicationinsights (v0.19.0)](https://github.com/Microsoft/ApplicationInsights-node.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-applicationinsights.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-applicationinsights) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-applicationinsights.svg)](https://travis-ci.org/npmtest/node-npmtest-applicationinsights)
#### Microsoft Application Insights module for Node.JS

[![NPM](https://nodei.co/npm/applicationinsights.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/applicationinsights)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-applicationinsights/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-applicationinsights/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-applicationinsights/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-applicationinsights/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-applicationinsights/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-applicationinsights/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-applicationinsights/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-applicationinsights/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-applicationinsights/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-applicationinsights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-applicationinsights/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-applicationinsights/build/test-report.html](https://npmtest.github.io/node-npmtest-applicationinsights/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-applicationinsights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-applicationinsights/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-applicationinsights/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-applicationinsights/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-applicationinsights/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Microsoft/ApplicationInsights-node.js/issues"
    },
    "contributors": [
        {
            "name": "Application Insights Developer Support"
        },
        {
            "name": "kszostak"
        },
        {
            "name": "southwood",
            "url": "https://github.com/southwood"
        },
        {
            "name": "bogdanbe"
        },
        {
            "name": "lukim"
        }
    ],
    "dependencies": {
        "zone.js": "0.7.6"
    },
    "description": "Microsoft Application Insights module for Node.JS",
    "devDependencies": {
        "mocha": "3.1.2",
        "node-mocks-http": "1.2.3",
        "sinon": "1.17.6",
        "typescript": "2.0.10",
        "typings": "2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8b3af3d4df05429c127cd64431cb81e406097d83",
        "tarball": "https://registry.npmjs.org/applicationinsights/-/applicationinsights-0.19.0.tgz"
    },
    "gitHead": "2116076baa278dc52b1668ebd5aab96975fb33ec",
    "homepage": "https://github.com/Microsoft/ApplicationInsights-node.js#readme",
    "keywords": [
        "exception monitoring",
        "request monitoring",
        "performance monitoring",
        "application insights",
        "microsoft",
        "azure"
    ],
    "license": "MIT",
    "main": "applicationinsights",
    "maintainers": [
        {
            "name": "msftapplicationinsights"
        }
    ],
    "name": "applicationinsights",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Microsoft/ApplicationInsights-node.js.git"
    },
    "scripts": {
        "prepublish": "tsc --module commonjs --declaration applicationinsights.ts",
        "pretest": "find Tests -type f -name \"*.ts\" | xargs tsc --module commonjs",
        "test": "./node_modules/mocha/bin/mocha ./Tests --recursive"
    },
    "version": "0.19.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
