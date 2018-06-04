# npmdoc-electron

#### basic api documentation for  [electron (2.0.2)](https://github.com/electron/electron#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron)

#### Build cross platform desktop apps with JavaScript, HTML, and CSS

[![NPM](https://nodei.co/npm/electron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron)

- [https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Electron Community"
    },
    "bin": {
        "electron": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/electron/electron/issues"
    },
    "dependencies": {
        "@types/node": "^8.0.24",
        "electron-download": "^3.0.1",
        "extract-zip": "^1.0.3"
    },
    "description": "Build cross platform desktop apps with JavaScript, HTML, and CSS",
    "devDependencies": {
        "home-path": "^0.1.1",
        "path-exists": "^2.0.0",
        "standard": "^5.4.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "integrity": "sha512-XmkGVoHLOqmjZ2nU/0zEzMl3TZEz452Q1fTJFKjylg4pLYaq7na7V2uxzydVQNQukZGbERoA7ayjxXzTsXbtdA==",
        "shasum": "b77e05f83419cc5ec921a2d21f35b55e4bfc3d68",
        "tarball": "https://registry.npmjs.org/electron/-/electron-2.0.2.tgz",
        "fileCount": 7,
        "unpackedSize": 375084,
        "npm-signature": "-----BEGIN PGP SIGNATURE-----\r\nVersion: OpenPGP.js v3.0.4\r\nComment: https://openpgpjs.org\r\n\r\nwsFcBAEBCAAQBQJbBHpnCRA9TVsSAnZWagAAsskP/11It6D5ghKW312kIsgc\nHWH+Sqv/lsTFErvGMxlwty6LVykwrlKSBQUJFO/qEX3mIlKBTb8/ZlImj0tK\nokK3d/xBnCvthXDYr9e2bKVZ2ePmca4VfhWHHinvnbzaJ+km64xqIL1DDyBi\n4L0rdHR4Tjs0+owVxMhuJyDYVwjVgNzlgJnxxHUg+M7+Jwrt1ABeMPjsmsCQ\nL5LoHUFWF7c9dsza3w+yj1odMmY7pDMIeG66Kv7q4f2Qfmc2VY0jaWI60lf1\nXG3Y3iMU8xMLqS0rnf3x+kOyFK0C1yh4rFvkejPiKyOTHOGosQrQClaq+A75\nMZ3ziiIoQYaKLqrEvLixUp0ZJFVZ+5KVIamUjtijkcS9UoCZYWzTjC+nZkY9\nxMfCdH8SS2litOHuCFsnOXgoqEU81VypKbPlXEvRoPtSiwIsVNnYZqLm4+Xx\nQ3o3v7D+C5GXYEFWnqqVobl2ZpZmUmuiSGsljG8/19yT4P3yplOg4mzhkNb8\n+pKEzfWMPwtlp3xDIlOEmWyPslCT4BLZCYIABtM/0DL594tevmB+fcqXBl4g\nLTrDhwimgSlKrHVB1D11XvvAMmmzLResw3rK+VNXR2rEANoOeEpF0fabk3GA\nxkQPhpzbr2b/lmEzRgRPKptpm9OJbPD2HnIjHFV4EZWpls6dyW5Brv0XcquF\nNaVq\r\n=WRCy\r\n-----END PGP SIGNATURE-----\r\n"
    },
    "homepage": "https://github.com/electron/electron#readme",
    "keywords": [
        "electron"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "electron"
        },
        {
            "name": "zeke"
        }
    ],
    "name": "electron",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/electron/electron.git"
    },
    "scripts": {
        "cache-clean": "rm -rf ~/.electron && rm -rf dist",
        "postinstall": "node install.js",
        "pretest": "npm run cache-clean",
        "test": "standard"
    },
    "types": "electron.d.ts",
    "version": "2018.6.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
