# npmdoc-node-couchdb

#### api documentation for  [node-couchdb (v1.1.1)](https://github.com/1999/node-couchdb)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-couchdb.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-couchdb) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-couchdb.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-couchdb)

#### ES2015-compatible package to interact with CouchDB

[![NPM](https://nodei.co/npm/node-couchdb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-couchdb)

- [https://npmdoc.github.io/node-npmdoc-node-couchdb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-couchdb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-couchdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-couchdb/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-couchdb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-couchdb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dmitry Sorin"
    },
    "bugs": {
        "url": "https://github.com/1999/node-couchdb/issues"
    },
    "contributors": [
        {
            "name": "Eric Scouten"
        },
        {
            "name": "Pascal Vomhoff"
        },
        {
            "name": "Peter Olson"
        }
    ],
    "dependencies": {
        "request": "^2.79.0"
    },
    "description": "ES2015-compatible package to interact with CouchDB",
    "devDependencies": {
        "babel-cli": "^6.7.5",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-plugin-array-includes": "^2.0.3",
        "babel-plugin-transform-es2015-destructuring": "^6.6.5",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.7.4",
        "babel-plugin-transform-es2015-parameters": "^6.7.0",
        "babel-plugin-transform-es2015-spread": "^6.6.5",
        "babel-plugin-transform-object-rest-spread": "^6.6.5",
        "babel-preset-es2015": "^6.6.0",
        "babel-register": "^6.7.2",
        "chai": "^3.5.0",
        "mocha": "^2.4.5",
        "node-couchdb-plugin-memory": "^0.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "90f50058b2d4e08cc46814b623754eb5eb1141b2",
        "tarball": "https://registry.npmjs.org/node-couchdb/-/node-couchdb-1.1.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "b8eb978091e748c780cd6aa25b76d4d708f25c70",
    "homepage": "https://github.com/1999/node-couchdb",
    "keywords": [
        "couchdb",
        "nosql"
    ],
    "license": "MIT",
    "main": "./dist/es2015.js",
    "maintainers": [
        {
            "name": "1999"
        }
    ],
    "name": "node-couchdb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/1999/node-couchdb.git"
    },
    "scripts": {
        "prepublish": "npm run release:legacy && npm run release:es2015",
        "release:es2015": "babel lib/node-couchdb.js --out-file dist/es2015.js",
        "release:legacy": "babel lib/node-couchdb.js --out-file dist/legacy.js --no-babelrc --presets es2015 --plugins array-includes",
        "test": "mocha --compilers js:babel-register --timeout 10000 --slow 10000 test/"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
