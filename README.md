# npmdoc-gulp-ruby-haml

#### api documentation for  gulp-ruby-haml (v0.0.9)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-ruby-haml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-ruby-haml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-ruby-haml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-ruby-haml)

#### Compile Haml to HTML with Ruby Haml

[![NPM](https://nodei.co/npm/gulp-ruby-haml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-ruby-haml)

- [https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-ruby-haml",
    "version": "0.0.9",
    "description": "Compile Haml to HTML with Ruby Haml",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/cheshire137/gulp-ruby-haml.git"
    },
    "author": {
        "name": "Sarah Vessels",
        "url": "http://www.sarahvessels.com"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "npm run-script style && npm run-script unit-test",
        "jscs": "node_modules/.bin/jscs index.js test/test.js",
        "jshint": "node_modules/.bin/jshint index.js test/test.js",
        "style": "npm run-script jscs && npm run-script jshint",
        "unit-test": "if [ -d \"tmp\" ]; then if find tmp -mindepth 1 -print -quit | grep -q .; then rm tmp/*; fi; fi; node_modules/.bin/mocha test/test.js"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "gulpplugin",
        "haml",
        "html",
        "compile",
        "preprocessor",
        "markup",
        "ruby"
    ],
    "dependencies": {
        "gulp-util": "~2.2.0",
        "through2": "~0.4.0",
        "win-spawn": "~2.0.0",
        "clone": "~0.1.11"
    },
    "devDependencies": {
        "gulp": "~3.5.2",
        "jscs": "^1.13.1",
        "jshint": "^2.8.0",
        "mocha": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
