# npmdoc-shower

#### api documentation for  [shower (v2.1.9)](https://github.com/shower/shower)  [![npm package](https://img.shields.io/npm/v/npmdoc-shower.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-shower) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-shower.svg)](https://travis-ci.org/npmdoc/node-npmdoc-shower)

#### Shower HTML presentation engine

[![NPM](https://nodei.co/npm/shower.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shower)

- [https://npmdoc.github.io/node-npmdoc-shower/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shower/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shower/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-shower/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-shower/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "shower",
    "description": "Shower HTML presentation engine",
    "version": "2.1.9",
    "author": {
        "name": "Vadim Makeev",
        "url": "http://pepelsbey.net/"
    },
    "homepage": "https://github.com/shower/shower",
    "repository": {
        "type": "git",
        "url": "git://github.com/shower/shower.git"
    },
    "bugs": {
        "url": "http://github.com/shower/shower/issues"
    },
    "license": "MIT",
    "keywords": [
        "shower",
        "presentation",
        "template"
    ],
    "files": [
        "pictures/**",
        "index.html",
        "LICENSE.md",
        "README.md"
    ],
    "dependencies": {
        "shower-core": "^2.1.0",
        "shower-material": "^1.0.11",
        "shower-ribbon": "^2.0.10"
    },
    "devDependencies": {
        "del": "^2.2.1",
        "fs": "0.0.2",
        "gulp": "^3.9.1",
        "gulp-gh-pages": "^0.5.4",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-rsync": "0.0.7",
        "gulp-zip": "^4.0.0",
        "merge-stream": "^1.0.0",
        "path-exists-cli": "^1.0.0",
        "run-sequence": "^1.2.2",
        "shower-core": "^2.0.8"
    },
    "scripts": {
        "prepare": "gulp prepare",
        "archive": "gulp archive",
        "publish": "gulp publish",
        "test": "npm run prepare && ls prepared && npm run archive && path-exists archive.zip"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
