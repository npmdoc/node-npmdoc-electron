# api documentation for  [electron (v1.6.2)](https://github.com/electron-userland/electron-prebuilt#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron)
#### Install prebuilt electron binaries for the command-line using npm

[![NPM](https://nodei.co/npm/electron.png?downloads=true)](https://www.npmjs.com/package/electron)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-electron_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-electron/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus"
    },
    "bin": {
        "electron": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/electron-userland/electron-prebuilt/issues"
    },
    "dependencies": {
        "electron-download": "^3.0.1",
        "extract-zip": "^1.0.3"
    },
    "description": "Install prebuilt electron binaries for the command-line using npm",
    "devDependencies": {
        "home-path": "^0.1.1",
        "path-exists": "^2.0.0",
        "standard": "^5.4.1",
        "tape": "^3.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "b0ccd7703f86d09c4d2a7273455c3f993f158994",
        "tarball": "https://registry.npmjs.org/electron/-/electron-1.6.2.tgz"
    },
    "homepage": "https://github.com/electron-userland/electron-prebuilt#readme",
    "keywords": [
        "electron"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "electron",
            "email": "electron@github.com"
        },
        {
            "name": "jlord",
            "email": "to.jlord@gmail.com"
        },
        {
            "name": "kevinsawicki",
            "email": "kevinsawicki@gmail.com"
        },
        {
            "name": "mafintosh",
            "email": "mathiasbuus@gmail.com"
        },
        {
            "name": "mattdesl",
            "email": "dave.des@gmail.com"
        },
        {
            "name": "maxogden",
            "email": "max@maxogden.com"
        },
        {
            "name": "zcbenz",
            "email": "zcbenz@gmail.com"
        },
        {
            "name": "zeke",
            "email": "zeke@sikelianos.com"
        }
    ],
    "name": "electron",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/electron-userland/electron-prebuilt.git"
    },
    "scripts": {
        "cache-clean": "rm -rf ~/.electron && rm -rf dist",
        "postinstall": "node install.js",
        "pretest": "npm run cache-clean && npm run postinstall",
        "test": "tape test/*.js && standard"
    },
    "version": "1.6.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module electron](#apidoc.module.electron)
1.  string <span class="apidocSignatureSpan">electron.</span>0
1.  string <span class="apidocSignatureSpan">electron.</span>1
1.  string <span class="apidocSignatureSpan">electron.</span>10
1.  string <span class="apidocSignatureSpan">electron.</span>11
1.  string <span class="apidocSignatureSpan">electron.</span>12
1.  string <span class="apidocSignatureSpan">electron.</span>13
1.  string <span class="apidocSignatureSpan">electron.</span>14
1.  string <span class="apidocSignatureSpan">electron.</span>15
1.  string <span class="apidocSignatureSpan">electron.</span>16
1.  string <span class="apidocSignatureSpan">electron.</span>17
1.  string <span class="apidocSignatureSpan">electron.</span>18
1.  string <span class="apidocSignatureSpan">electron.</span>19
1.  string <span class="apidocSignatureSpan">electron.</span>2
1.  string <span class="apidocSignatureSpan">electron.</span>20
1.  string <span class="apidocSignatureSpan">electron.</span>21
1.  string <span class="apidocSignatureSpan">electron.</span>22
1.  string <span class="apidocSignatureSpan">electron.</span>23
1.  string <span class="apidocSignatureSpan">electron.</span>24
1.  string <span class="apidocSignatureSpan">electron.</span>25
1.  string <span class="apidocSignatureSpan">electron.</span>26
1.  string <span class="apidocSignatureSpan">electron.</span>27
1.  string <span class="apidocSignatureSpan">electron.</span>28
1.  string <span class="apidocSignatureSpan">electron.</span>29
1.  string <span class="apidocSignatureSpan">electron.</span>3
1.  string <span class="apidocSignatureSpan">electron.</span>30
1.  string <span class="apidocSignatureSpan">electron.</span>31
1.  string <span class="apidocSignatureSpan">electron.</span>32
1.  string <span class="apidocSignatureSpan">electron.</span>33
1.  string <span class="apidocSignatureSpan">electron.</span>34
1.  string <span class="apidocSignatureSpan">electron.</span>35
1.  string <span class="apidocSignatureSpan">electron.</span>36
1.  string <span class="apidocSignatureSpan">electron.</span>37
1.  string <span class="apidocSignatureSpan">electron.</span>38
1.  string <span class="apidocSignatureSpan">electron.</span>39
1.  string <span class="apidocSignatureSpan">electron.</span>4
1.  string <span class="apidocSignatureSpan">electron.</span>40
1.  string <span class="apidocSignatureSpan">electron.</span>41
1.  string <span class="apidocSignatureSpan">electron.</span>42
1.  string <span class="apidocSignatureSpan">electron.</span>43
1.  string <span class="apidocSignatureSpan">electron.</span>44
1.  string <span class="apidocSignatureSpan">electron.</span>45
1.  string <span class="apidocSignatureSpan">electron.</span>46
1.  string <span class="apidocSignatureSpan">electron.</span>47
1.  string <span class="apidocSignatureSpan">electron.</span>48
1.  string <span class="apidocSignatureSpan">electron.</span>49
1.  string <span class="apidocSignatureSpan">electron.</span>5
1.  string <span class="apidocSignatureSpan">electron.</span>50
1.  string <span class="apidocSignatureSpan">electron.</span>51
1.  string <span class="apidocSignatureSpan">electron.</span>52
1.  string <span class="apidocSignatureSpan">electron.</span>53
1.  string <span class="apidocSignatureSpan">electron.</span>54
1.  string <span class="apidocSignatureSpan">electron.</span>55
1.  string <span class="apidocSignatureSpan">electron.</span>56
1.  string <span class="apidocSignatureSpan">electron.</span>57
1.  string <span class="apidocSignatureSpan">electron.</span>58
1.  string <span class="apidocSignatureSpan">electron.</span>59
1.  string <span class="apidocSignatureSpan">electron.</span>6
1.  string <span class="apidocSignatureSpan">electron.</span>60
1.  string <span class="apidocSignatureSpan">electron.</span>61
1.  string <span class="apidocSignatureSpan">electron.</span>62
1.  string <span class="apidocSignatureSpan">electron.</span>63
1.  string <span class="apidocSignatureSpan">electron.</span>64
1.  string <span class="apidocSignatureSpan">electron.</span>65
1.  string <span class="apidocSignatureSpan">electron.</span>66
1.  string <span class="apidocSignatureSpan">electron.</span>67
1.  string <span class="apidocSignatureSpan">electron.</span>68
1.  string <span class="apidocSignatureSpan">electron.</span>69
1.  string <span class="apidocSignatureSpan">electron.</span>7
1.  string <span class="apidocSignatureSpan">electron.</span>70
1.  string <span class="apidocSignatureSpan">electron.</span>71
1.  string <span class="apidocSignatureSpan">electron.</span>72
1.  string <span class="apidocSignatureSpan">electron.</span>73
1.  string <span class="apidocSignatureSpan">electron.</span>74
1.  string <span class="apidocSignatureSpan">electron.</span>75
1.  string <span class="apidocSignatureSpan">electron.</span>76
1.  string <span class="apidocSignatureSpan">electron.</span>77
1.  string <span class="apidocSignatureSpan">electron.</span>78
1.  string <span class="apidocSignatureSpan">electron.</span>79
1.  string <span class="apidocSignatureSpan">electron.</span>8
1.  string <span class="apidocSignatureSpan">electron.</span>80
1.  string <span class="apidocSignatureSpan">electron.</span>81
1.  string <span class="apidocSignatureSpan">electron.</span>9



# <a name="apidoc.module.electron"></a>[module electron](#apidoc.module.electron)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
