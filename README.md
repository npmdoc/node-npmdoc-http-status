# api documentation for  [http-status (v1.0.1)](http://www.adaltas.com/projects/node-http-status)  [![npm package](https://img.shields.io/npm/v/npmdoc-http-status.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-http-status) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-http-status.svg)](https://travis-ci.org/npmdoc/node-npmdoc-http-status)
#### Interact with HTTP status code

[![NPM](https://nodei.co/npm/http-status.png?downloads=true)](https://www.npmjs.com/package/http-status)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-status/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-http-status_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-status/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-http-status/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-http-status/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Worms",
        "email": "david@adaltas.com"
    },
    "bugs": {
        "url": "http://github.com/wdavidw/node-http-status/issues",
        "email": "open@adaltas.com"
    },
    "contributors": [
        {
            "name": "David Worms",
            "email": "david@adaltas.com"
        },
        {
            "name": "Daniel Gasienica",
            "email": "daniel@gasienica.ch"
        }
    ],
    "dependencies": {},
    "description": "Interact with HTTP status code",
    "devDependencies": {
        "coffee-script": "latest",
        "mocha": "latest",
        "should": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "dc43001a8bfc50ac87d485a892f7578964bc94a2",
        "tarball": "https://registry.npmjs.org/http-status/-/http-status-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "ffc8111f5a427860ed2ee67066bfd8347328b35d",
    "homepage": "http://www.adaltas.com/projects/node-http-status",
    "keywords": [
        "http",
        "express",
        "connect"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "david",
            "email": "david@adaltas.com"
        }
    ],
    "name": "http-status",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wdavidw/node-http-status.git"
    },
    "scripts": {
        "coffee": "coffee -b -o lib src",
        "test": "NODE_ENV=test node_modules/.bin/mocha --compilers coffee:coffee-script/register --reporter dot"
    },
    "version": "1.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module http-status](#apidoc.module.http-status)
1.  number <span class="apidocSignatureSpan">http-status.</span>ACCEPTED
1.  number <span class="apidocSignatureSpan">http-status.</span>ALREADY_REPORTED
1.  number <span class="apidocSignatureSpan">http-status.</span>BAD_GATEWAY
1.  number <span class="apidocSignatureSpan">http-status.</span>BAD_REQUEST
1.  number <span class="apidocSignatureSpan">http-status.</span>CONFLICT
1.  number <span class="apidocSignatureSpan">http-status.</span>CONTINUE
1.  number <span class="apidocSignatureSpan">http-status.</span>CREATED
1.  number <span class="apidocSignatureSpan">http-status.</span>EXPECTATION_FAILED
1.  number <span class="apidocSignatureSpan">http-status.</span>FAILED_DEPENDENCY
1.  number <span class="apidocSignatureSpan">http-status.</span>FORBIDDEN
1.  number <span class="apidocSignatureSpan">http-status.</span>FOUND
1.  number <span class="apidocSignatureSpan">http-status.</span>GATEWAY_TIMEOUT
1.  number <span class="apidocSignatureSpan">http-status.</span>GONE
1.  number <span class="apidocSignatureSpan">http-status.</span>HTTP_VERSION_NOT_SUPPORTED
1.  number <span class="apidocSignatureSpan">http-status.</span>IM_A_TEAPOT
1.  number <span class="apidocSignatureSpan">http-status.</span>IM_USED
1.  number <span class="apidocSignatureSpan">http-status.</span>INSUFFICIENT_STORAGE
1.  number <span class="apidocSignatureSpan">http-status.</span>INTERNAL_SERVER_ERROR
1.  number <span class="apidocSignatureSpan">http-status.</span>LENGTH_REQUIRED
1.  number <span class="apidocSignatureSpan">http-status.</span>LOCKED
1.  number <span class="apidocSignatureSpan">http-status.</span>LOOP_DETECTED
1.  number <span class="apidocSignatureSpan">http-status.</span>METHOD_NOT_ALLOWED
1.  number <span class="apidocSignatureSpan">http-status.</span>MISDIRECTED_REQUEST
1.  number <span class="apidocSignatureSpan">http-status.</span>MOVED_PERMANENTLY
1.  number <span class="apidocSignatureSpan">http-status.</span>MULTIPLE_CHOICES
1.  number <span class="apidocSignatureSpan">http-status.</span>MULTI_STATUS
1.  number <span class="apidocSignatureSpan">http-status.</span>NETWORK_AUTHENTICATION_REQUIRED
1.  number <span class="apidocSignatureSpan">http-status.</span>NON_AUTHORITATIVE_INFORMATION
1.  number <span class="apidocSignatureSpan">http-status.</span>NOT_ACCEPTABLE
1.  number <span class="apidocSignatureSpan">http-status.</span>NOT_EXTENDED
1.  number <span class="apidocSignatureSpan">http-status.</span>NOT_FOUND
1.  number <span class="apidocSignatureSpan">http-status.</span>NOT_IMPLEMENTED
1.  number <span class="apidocSignatureSpan">http-status.</span>NOT_MODIFIED
1.  number <span class="apidocSignatureSpan">http-status.</span>NO_CONTENT
1.  number <span class="apidocSignatureSpan">http-status.</span>OK
1.  number <span class="apidocSignatureSpan">http-status.</span>PARTIAL_CONTENT
1.  number <span class="apidocSignatureSpan">http-status.</span>PAYMENT_REQUIRED
1.  number <span class="apidocSignatureSpan">http-status.</span>PERMANENT_REDIRECT
1.  number <span class="apidocSignatureSpan">http-status.</span>PRECONDITION_FAILED
1.  number <span class="apidocSignatureSpan">http-status.</span>PRECONDITION_REQUIRED
1.  number <span class="apidocSignatureSpan">http-status.</span>PROXY_AUTHENTICATION_REQUIRED
1.  number <span class="apidocSignatureSpan">http-status.</span>REQUESTED_RANGE_NOT_SATISFIABLE
1.  number <span class="apidocSignatureSpan">http-status.</span>REQUEST_ENTITY_TOO_LARGE
1.  number <span class="apidocSignatureSpan">http-status.</span>REQUEST_HEADER_FIELDS_TOO_LARGE
1.  number <span class="apidocSignatureSpan">http-status.</span>REQUEST_TIMEOUT
1.  number <span class="apidocSignatureSpan">http-status.</span>REQUEST_URI_TOO_LONG
1.  number <span class="apidocSignatureSpan">http-status.</span>RESET_CONTENT
1.  number <span class="apidocSignatureSpan">http-status.</span>SEE_OTHER
1.  number <span class="apidocSignatureSpan">http-status.</span>SERVICE_UNAVAILABLE
1.  number <span class="apidocSignatureSpan">http-status.</span>SWITCHING_PROTOCOLS
1.  number <span class="apidocSignatureSpan">http-status.</span>SWITCH_PROXY
1.  number <span class="apidocSignatureSpan">http-status.</span>TEMPORARY_REDIRECT
1.  number <span class="apidocSignatureSpan">http-status.</span>TOO_MANY_REQUESTS
1.  number <span class="apidocSignatureSpan">http-status.</span>UNAUTHORIZED
1.  number <span class="apidocSignatureSpan">http-status.</span>UNAVAILABLE_FOR_LEGAL_REASONS
1.  number <span class="apidocSignatureSpan">http-status.</span>UNPROCESSABLE_ENTITY
1.  number <span class="apidocSignatureSpan">http-status.</span>UNSUPPORTED_MEDIA_TYPE
1.  number <span class="apidocSignatureSpan">http-status.</span>UPGRADE_REQUIRED
1.  number <span class="apidocSignatureSpan">http-status.</span>USE_PROXY
1.  number <span class="apidocSignatureSpan">http-status.</span>VARIANT_ALSO_NEGOTIATES
1.  string <span class="apidocSignatureSpan">http-status.</span>100
1.  string <span class="apidocSignatureSpan">http-status.</span>101
1.  string <span class="apidocSignatureSpan">http-status.</span>200
1.  string <span class="apidocSignatureSpan">http-status.</span>201
1.  string <span class="apidocSignatureSpan">http-status.</span>202
1.  string <span class="apidocSignatureSpan">http-status.</span>203
1.  string <span class="apidocSignatureSpan">http-status.</span>204
1.  string <span class="apidocSignatureSpan">http-status.</span>205
1.  string <span class="apidocSignatureSpan">http-status.</span>206
1.  string <span class="apidocSignatureSpan">http-status.</span>207
1.  string <span class="apidocSignatureSpan">http-status.</span>208
1.  string <span class="apidocSignatureSpan">http-status.</span>226
1.  string <span class="apidocSignatureSpan">http-status.</span>300
1.  string <span class="apidocSignatureSpan">http-status.</span>301
1.  string <span class="apidocSignatureSpan">http-status.</span>302
1.  string <span class="apidocSignatureSpan">http-status.</span>303
1.  string <span class="apidocSignatureSpan">http-status.</span>304
1.  string <span class="apidocSignatureSpan">http-status.</span>305
1.  string <span class="apidocSignatureSpan">http-status.</span>306
1.  string <span class="apidocSignatureSpan">http-status.</span>307
1.  string <span class="apidocSignatureSpan">http-status.</span>308
1.  string <span class="apidocSignatureSpan">http-status.</span>400
1.  string <span class="apidocSignatureSpan">http-status.</span>401
1.  string <span class="apidocSignatureSpan">http-status.</span>402
1.  string <span class="apidocSignatureSpan">http-status.</span>403
1.  string <span class="apidocSignatureSpan">http-status.</span>404
1.  string <span class="apidocSignatureSpan">http-status.</span>405
1.  string <span class="apidocSignatureSpan">http-status.</span>406
1.  string <span class="apidocSignatureSpan">http-status.</span>407
1.  string <span class="apidocSignatureSpan">http-status.</span>408
1.  string <span class="apidocSignatureSpan">http-status.</span>409
1.  string <span class="apidocSignatureSpan">http-status.</span>410
1.  string <span class="apidocSignatureSpan">http-status.</span>411
1.  string <span class="apidocSignatureSpan">http-status.</span>412
1.  string <span class="apidocSignatureSpan">http-status.</span>413
1.  string <span class="apidocSignatureSpan">http-status.</span>414
1.  string <span class="apidocSignatureSpan">http-status.</span>415
1.  string <span class="apidocSignatureSpan">http-status.</span>416
1.  string <span class="apidocSignatureSpan">http-status.</span>417
1.  string <span class="apidocSignatureSpan">http-status.</span>418
1.  string <span class="apidocSignatureSpan">http-status.</span>421
1.  string <span class="apidocSignatureSpan">http-status.</span>422
1.  string <span class="apidocSignatureSpan">http-status.</span>423
1.  string <span class="apidocSignatureSpan">http-status.</span>424
1.  string <span class="apidocSignatureSpan">http-status.</span>426
1.  string <span class="apidocSignatureSpan">http-status.</span>428
1.  string <span class="apidocSignatureSpan">http-status.</span>429
1.  string <span class="apidocSignatureSpan">http-status.</span>431
1.  string <span class="apidocSignatureSpan">http-status.</span>451
1.  string <span class="apidocSignatureSpan">http-status.</span>500
1.  string <span class="apidocSignatureSpan">http-status.</span>501
1.  string <span class="apidocSignatureSpan">http-status.</span>502
1.  string <span class="apidocSignatureSpan">http-status.</span>503
1.  string <span class="apidocSignatureSpan">http-status.</span>504
1.  string <span class="apidocSignatureSpan">http-status.</span>505
1.  string <span class="apidocSignatureSpan">http-status.</span>506
1.  string <span class="apidocSignatureSpan">http-status.</span>507
1.  string <span class="apidocSignatureSpan">http-status.</span>508
1.  string <span class="apidocSignatureSpan">http-status.</span>510
1.  string <span class="apidocSignatureSpan">http-status.</span>511



# <a name="apidoc.module.http-status"></a>[module http-status](#apidoc.module.http-status)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
