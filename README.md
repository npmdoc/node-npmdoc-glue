# npmdoc-glue

#### api documentation for  glue (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-glue.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-glue) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-glue.svg)](https://travis-ci.org/npmdoc/node-npmdoc-glue)

#### Server composer for hapi.js

[![NPM](https://nodei.co/npm/glue.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glue)

- [https://npmdoc.github.io/node-npmdoc-glue/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-glue/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-glue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-glue/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-glue/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-glue/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "glue",
    "description": "Server composer for hapi.js",
    "version": "4.1.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/glue"
    },
    "main": "lib/index.js",
    "keywords": [
        "server",
        "pack",
        "composer",
        "manifest",
        "hapi"
    ],
    "engines": {
        "node": ">=4.0"
    },
    "dependencies": {
        "hapi": "11.x.x || 12.x.x || 13.x.x || 14.x.x || 15.x.x || 16.x.x",
        "hoek": "4.x.x",
        "items": "2.x.x",
        "joi": "10.x.x"
    },
    "devDependencies": {
        "catbox-memory": "2.x.x",
        "code": "4.x.x",
        "lab": "11.x.x"
    },
    "scripts": {
        "test": "node node_modules/lab/bin/lab -a code -t 100 -L",
        "test-cov-html": "node node_modules/lab/bin/lab -a code -r html -o coverage.html"
    },
    "license": "BSD-3-Clause"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
