# api documentation for  [swagger (v0.7.5)](https://github.com/swagger-api/swagger-node#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-swagger.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-swagger) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-swagger.svg)](https://travis-ci.org/npmdoc/node-npmdoc-swagger)
#### The Swagger command-line. Provides Swagger utilities and project lifecycle support.

[![NPM](https://nodei.co/npm/swagger.png?downloads=true)](https://www.npmjs.com/package/swagger)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-swagger_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-swagger/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Scott Ganyo",
        "email": "sganyo@apigee.com"
    },
    "bin": {
        "swagger": "bin/swagger.js",
        "swagger-project": "bin/swagger-project.js"
    },
    "bugs": {
        "url": "https://github.com/swagger-api/swagger-node/issues"
    },
    "dependencies": {
        "async": "^1.2.1",
        "commander": "^2.7.1",
        "connect": "^3.3.5",
        "debug": "^2.1.3",
        "fs-extra": "^0.24.0",
        "inquirer": "^0.10.0",
        "js-yaml": "^3.3.0",
        "lodash": "^3.10.0",
        "mocha": "^2.2.1",
        "nodemon": "^1.3.7",
        "serve-static": "^1.9.2",
        "swagger-converter": "^0.2.0",
        "swagger-editor": "^2.9.2",
        "swagger-test-templates": "^1.2.0",
        "swagger-tools": "^0.9.0"
    },
    "description": "The Swagger command-line. Provides Swagger utilities and project lifecycle support.",
    "devDependencies": {
        "chai": "^3.0.0",
        "mock-stdin": "^0.3.0",
        "proxyquire": "^1.4.0",
        "should": "^7.1.0",
        "sinon": "^1.15.4",
        "superagent": "^1.1.0",
        "supertest": "^1.1.0",
        "tmp": "^0.0.28",
        "z-schema": "^3.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3be6ee3d392c3b006fc7a9b5b2d60c7e834860fd",
        "tarball": "https://registry.npmjs.org/swagger/-/swagger-0.7.5.tgz"
    },
    "gitHead": "91356200dee38487f3ecb7d67df3cb9dfc34af60",
    "homepage": "https://github.com/swagger-api/swagger-node#readme",
    "keywords": [
        "swagger",
        "api",
        "apis",
        "connect",
        "express"
    ],
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wordnik",
            "email": "apiteam@helloreverb.com"
        },
        {
            "name": "swagger-api",
            "email": "apiteam@helloreverb.com"
        },
        {
            "name": "scottganyo",
            "email": "scott@ganyo.com"
        }
    ],
    "name": "swagger",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/swagger-api/swagger-node.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons",
        "start": "node app.js",
        "test": "mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons"
    },
    "version": "0.7.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module swagger](#apidoc.module.swagger)



# <a name="apidoc.module.swagger"></a>[module swagger](#apidoc.module.swagger)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
