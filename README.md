# npmdoc-plugman

#### api documentation for  plugman (v1.4.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-plugman.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-plugman) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-plugman.svg)](https://travis-ci.org/npmdoc/node-npmdoc-plugman)

#### install/uninstall Cordova plugins

[![NPM](https://nodei.co/npm/plugman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/plugman)

- [https://npmdoc.github.io/node-npmdoc-plugman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-plugman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-plugman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-plugman/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-plugman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-plugman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Andrew Lunny <alunny@gmail.com>",
    "name": "plugman",
    "description": "install/uninstall Cordova plugins",
    "version": "1.4.1",
    "repository": {
        "type": "git",
        "url": "git://git-wip-us.apache.org/repos/asf/cordova-plugman.git"
    },
    "bugs": {
        "url": "https://issues.apache.org/jira/browse/CB"
    },
    "main": "plugman.js",
    "engines": {
        "node": ">=0.9.9"
    },
    "engineStrict": true,
    "dependencies": {
        "cordova-lib": "6.5.0",
        "nopt": "1.0.9",
        "q": "1.0.1"
    },
    "devDependencies": {
        "jshint": "2.5.8",
        "jasmine-node": "1.14.5"
    },
    "bin": {
        "plugman": "./main.js"
    },
    "scripts": {
        "test": "npm run jasmine && npm run jshint",
        "jshint": "node node_modules/jshint/bin/jshint src",
        "jasmine": "jasmine-node --captureExceptions --color spec"
    },
    "license": "Apache-2.0",
    "contributors": [
        {
            "name": "Anis Kadri"
        },
        {
            "name": "Tim Kim"
        },
        {
            "name": "Braden Shepherdson"
        },
        {
            "name": "Ryan Willoughby"
        },
        {
            "name": "Brett Rudd"
        },
        {
            "name": "Mike Reinstein"
        },
        {
            "name": "Shazron Abdullah"
        },
        {
            "name": "Steve Gill"
        },
        {
            "name": "Fil Maj"
        },
        {
            "name": "Michael Brooks"
        },
        {
            "name": "Jesse MacFadyen"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
