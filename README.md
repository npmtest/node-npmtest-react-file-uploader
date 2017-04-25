# npmtest-react-file-uploader

#### basic test coverage for  [react-file-uploader (v0.3.3)](https://github.com/lionng429/react-file-uploader)  [![npm package](https://img.shields.io/npm/v/npmtest-react-file-uploader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-file-uploader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-file-uploader.svg)](https://travis-ci.org/npmtest/node-npmtest-react-file-uploader)

#### A set of file-upload-components with React.js.

[![NPM](https://nodei.co/npm/react-file-uploader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-file-uploader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-file-uploader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-file-uploader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-file-uploader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-file-uploader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-file-uploader/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-file-uploader/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-file-uploader/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-file-uploader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-file-uploader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-file-uploader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-file-uploader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-file-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-file-uploader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-file-uploader/build/test-report.html](https://npmtest.github.io/node-npmtest-react-file-uploader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-file-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-file-uploader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-file-uploader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-file-uploader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-file-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-file-uploader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-file-uploader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-file-uploader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marston Ng"
    },
    "bugs": {
        "url": "https://github.com/lionng429/react-file-uploader/issues"
    },
    "dependencies": {
        "classnames": "^2.2.0",
        "debug": "^2.2.0",
        "invariant": "^2.2.0",
        "lodash": ">=3.10.1",
        "shortid": "^2.2.6",
        "superagent": "^1.4.0"
    },
    "description": "A set of file-upload-components with React.js.",
    "devDependencies": {
        "babel": "^6.1.18",
        "babel-cli": "^6.2.0",
        "babel-jest": "*",
        "babel-preset-es2015": "^6.1.18",
        "babel-preset-react": "^6.1.18",
        "babel-preset-stage-0": "^6.1.18",
        "eslint": "^2.11.1",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.8.1",
        "eslint-plugin-jsx-a11y": "^1.3.0",
        "eslint-plugin-react": "^5.1.1",
        "jest-cli": "*",
        "jsdom": "^7.0.2",
        "nock": "^8.0.0",
        "react-addons-test-utils": "^0.14.8 || ^15.0.0",
        "react-dom": "^0.14.8 || ^15.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9040adabc9243fadd7a60cff332d1c1c2149d685",
        "tarball": "https://registry.npmjs.org/react-file-uploader/-/react-file-uploader-0.3.3.tgz"
    },
    "gitHead": "7c1089fba4765e1c3c9763fc3edb31fc8cfd4ff2",
    "homepage": "https://github.com/lionng429/react-file-uploader",
    "jest": {
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "testPathDirs": [
            "<rootDir>/src"
        ],
        "unmockedModulePathPatterns": [
            "<rootDir>/node_modules/react",
            "<rootDir>/node_modules/react-dom",
            "<rootDir>/node_modules/react-addons-test-utils",
            "<rootDir>/node_modules/jsdom",
            "<rootDir>/node_modules/lodash",
            "<rootDir>/node_modules/debug",
            "<rootDir>/node_modules/superagent",
            "<rootDir>/node_modules/nock"
        ]
    },
    "keywords": [
        "react",
        "file",
        "upload",
        "uploader",
        "file-upload",
        "file-uploader"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "marstonng"
        }
    ],
    "name": "react-file-uploader",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.8 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lionng429/react-file-uploader.git"
    },
    "scripts": {
        "build": "npm run eslint && npm run test && npm run clean && npm run build:lib",
        "build:lib": "babel src --out-dir lib",
        "clean": "rm -rf lib",
        "eslint": "eslint ./src/*.js ./src/**/*.js",
        "test": "jest",
        "test:report": "jest --coverage"
    },
    "version": "0.3.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
