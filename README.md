# npmdoc-browser-pack

#### api documentation for  [browser-pack (v6.0.2)](https://github.com/substack/browser-pack)  [![npm package](https://img.shields.io/npm/v/npmdoc-browser-pack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browser-pack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browser-pack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browser-pack)

#### pack node-style source files from a json stream into a browser bundle

[![NPM](https://nodei.co/npm/browser-pack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-pack)

- [https://npmdoc.github.io/node-npmdoc-browser-pack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-pack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-pack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-pack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browser-pack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browser-pack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "browser-pack": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/browser-pack/issues"
    },
    "dependencies": {
        "JSONStream": "^1.0.3",
        "combine-source-map": "~0.7.1",
        "defined": "^1.0.0",
        "through2": "^2.0.0",
        "umd": "^3.0.0"
    },
    "description": "pack node-style source files from a json stream into a browser bundle",
    "devDependencies": {
        "concat-stream": "~1.5.1",
        "convert-source-map": "~1.1.0",
        "parse-base64vlq-mappings": "~0.1.1",
        "tap": "^2.2.0",
        "uglify-js": "1.3.5"
    },
    "directories": {},
    "dist": {
        "shasum": "f86cd6cef4f5300c8e63e07a4d512f65fbff4531",
        "tarball": "https://registry.npmjs.org/browser-pack/-/browser-pack-6.0.2.tgz"
    },
    "gitHead": "d8f408fd1408ad1fbe02830792caa1354bf48188",
    "homepage": "https://github.com/substack/browser-pack",
    "keywords": [
        "browser",
        "bundle",
        "commonjs",
        "commonj-esque",
        "exports",
        "module.exports",
        "require"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        },
        {
            "name": "forbeslindesay"
        },
        {
            "name": "zertosh"
        }
    ],
    "name": "browser-pack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/browser-pack.git"
    },
    "scripts": {
        "prepublish": "node bin/prepublish.js",
        "test": "tap test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8",
            "ie/9",
            "ie/10",
            "chrome/15",
            "chrome/latest",
            "firefox/10",
            "firefox/latest",
            "safari/latest",
            "opera/latest"
        ]
    },
    "version": "6.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
