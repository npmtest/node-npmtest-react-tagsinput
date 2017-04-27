# npmtest-react-tagsinput

#### basic test coverage for  [react-tagsinput (v3.16.1)](https://github.com/olahol/react-tagsinput)  [![npm package](https://img.shields.io/npm/v/npmtest-react-tagsinput.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-tagsinput) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-tagsinput.svg)](https://travis-ci.org/npmtest/node-npmtest-react-tagsinput)

#### Highly customizable React component for inputing tags

[![NPM](https://nodei.co/npm/react-tagsinput.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-tagsinput)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-tagsinput/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tagsinput/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-tagsinput/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-tagsinput/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-tagsinput/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-tagsinput/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-tagsinput/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-tagsinput/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-tagsinput/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-tagsinput/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-tagsinput/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tagsinput/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-tagsinput/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-tagsinput/build/test-report.html](https://npmtest.github.io/node-npmtest-react-tagsinput/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-tagsinput/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-tagsinput/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-tagsinput/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-tagsinput/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-tagsinput/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-tagsinput/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-tagsinput/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-tagsinput/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ola Holmström"
    },
    "bugs": {
        "url": "https://github.com/olahol/react-tagsinput/issues"
    },
    "dependencies": {},
    "description": "Highly customizable React component for inputing tags",
    "devDependencies": {
        "babel-cli": "^6.8.0",
        "babel-core": "^6.8.0",
        "babel-eslint": "^6.0.4",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-plugin-transform-es2015-modules-umd": "^6.8.0",
        "babel-plugin-transform-react-remove-prop-types": "^0.3.3",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.8.0",
        "isparta": "^4.0.0",
        "jsdom": "^7.0.2",
        "mocha": "^2.3.3",
        "react": "15.x.x",
        "react-addons-test-utils": "^15.0.0",
        "react-autosuggest": "^8.0.0",
        "react-dom": "15.x.x",
        "react-input-autosize": "^1.0.0",
        "reactpack": "^0.9.0",
        "sinon": "^2.1.0",
        "standard": "^8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dfb3bcbe5fc4430f60c145716c17cdc2613ce117",
        "tarball": "https://registry.npmjs.org/react-tagsinput/-/react-tagsinput-3.16.1.tgz"
    },
    "gitHead": "39b1ce082615d95dc092c0f1d69dac6e16d65798",
    "homepage": "https://github.com/olahol/react-tagsinput",
    "keywords": [
        "react",
        "tags",
        "input",
        "component",
        "javascript",
        "react-component"
    ],
    "license": "MIT",
    "main": "react-tagsinput.js",
    "maintainers": [
        {
            "name": "olahol"
        }
    ],
    "name": "react-tagsinput",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0.0 || ^0.14.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/olahol/react-tagsinput.git"
    },
    "scripts": {
        "build": "babel --module-id ReactTagsInput -m umd src/index.js > react-tagsinput.js",
        "build-example": "reactpack --no-extract --no-source-map --no-html example/index.js example/",
        "build-example-watch": "reactpack -w --no-extract --no-source-map --no-html example/index.js example/",
        "coverage": "babel-node node_modules/.bin/isparta cover --report text --report html node_modules/.bin/_mocha -- --reporter dot",
        "prepublish": "npm run build",
        "test": "standard src/index.js && mocha --compilers js:babel-register"
    },
    "standard": {
        "parser": "babel-eslint"
    },
    "version": "3.16.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
