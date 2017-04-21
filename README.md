# npmdoc-module-alias

#### api documentation for  [module-alias (v2.0.0)](https://github.com/ilearnio/module-alias)  [![npm package](https://img.shields.io/npm/v/npmdoc-module-alias.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-module-alias) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-module-alias.svg)](https://travis-ci.org/npmdoc/node-npmdoc-module-alias)

#### Create aliases of directories and register custom module paths in NodeJS like a boss!

[![NPM](https://nodei.co/npm/module-alias.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/module-alias)

- [https://npmdoc.github.io/node-npmdoc-module-alias/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-module-alias/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-module-alias/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-module-alias/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-module-alias/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-module-alias/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "module-alias",
    "description": "Create aliases of directories and register custom module paths in NodeJS like a boss!",
    "version": "2.0.0",
    "author": {
        "name": "Nick Gavrilov"
    },
    "scripts": {
        "test": "npm run lint && npm run testonly",
        "testonly": "NODE_ENV=test mocha test/specs.js",
        "testonly-watch": "NODE_ENV=test mocha -w test/specs.js",
        "lint": "standard src"
    },
    "bugs": {
        "url": "https://github.com/ilearnio/module-alias/issues"
    },
    "homepage": "https://github.com/ilearnio/module-alias",
    "keywords": [
        "extend",
        "modules",
        "node",
        "path",
        "resolve"
    ],
    "license": "MIT",
    "main": "index.js",
    "files": [
        "index.js",
        "register.js",
        "README.md"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ilearnio/module-alias.git"
    },
    "dependencies": {},
    "devDependencies": {
        "chai": "^3.5.0",
        "hello-world-classic": "ilearnio/hello-world-classic",
        "mocha": "^2.4.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
