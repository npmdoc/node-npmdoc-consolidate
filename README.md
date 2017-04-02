# api documentation for  [consolidate (v0.14.5)](https://github.com/visionmedia/consolidate.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-consolidate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-consolidate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-consolidate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-consolidate)
#### Template engine consolidation library

[![NPM](https://nodei.co/npm/consolidate.png?downloads=true)](https://www.npmjs.com/package/consolidate)

[![apidoc](https://npmdoc.github.io/node-npmdoc-consolidate/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-consolidate_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-consolidate/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-consolidate/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bugs": {
        "url": "https://github.com/visionmedia/consolidate.js/issues"
    },
    "dependencies": {
        "bluebird": "^3.1.1"
    },
    "description": "Template engine consolidation library",
    "devDependencies": {
        "arc-templates": "^0.5.1",
        "atpl": ">=0.7.6",
        "babel-core": "^6.7.6",
        "babel-preset-react": "^6.5.0",
        "bracket-template": "^1.0.3",
        "dot": "^1.0.1",
        "dust": "^0.3.0",
        "dustjs-helpers": "^1.1.1",
        "dustjs-linkedin": "^2.7.2",
        "eco": "^1.1.0-rc-3",
        "ect": "^0.5.9",
        "ejs": "^2.3.4",
        "eslint": "^3.7.1",
        "eslint-config-standard": "^6.2.0",
        "eslint-plugin-promise": "^3.3.1",
        "eslint-plugin-standard": "^2.0.1",
        "haml-coffee": "^1.4.0",
        "hamlet": "^0.3.3",
        "hamljs": "^0.6.1",
        "handlebars": "^4.0.5",
        "hogan.js": "^3.0.2",
        "htmling": "^0.0.7",
        "jade": "^1.9.1",
        "jazz": "^0.0.18",
        "jqtpl": "~1.1.0",
        "just": "^0.1.8",
        "liquor": "^0.0.5",
        "lodash": "^4.0.0",
        "marko": "^3.12.0",
        "mocha": "^3.1.2",
        "mote": "^0.2.0",
        "mustache": "^2.2.1",
        "nunjucks": "^3.0.0",
        "pug": "^2.0.0-beta6",
        "qejs": "^3.0.5",
        "ractive": "^0.8.4",
        "react": "^15.3.2",
        "react-dom": "^15.3.2",
        "should": "*",
        "slm": "^0.5.0",
        "swig": "^1.4.1",
        "templayed": ">=0.2.3",
        "tinyliquid": "^0.2.22",
        "toffee": "^0.1.12",
        "twig": "^0.10.0",
        "underscore": "^1.3.3",
        "vash": "^0.12.2",
        "walrus": "^0.10.1",
        "whiskers": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a25047bc76f73072667c8cb52c989888f494c63",
        "tarball": "https://registry.npmjs.org/consolidate/-/consolidate-0.14.5.tgz"
    },
    "gitHead": "894b0de2fa9dcd2bde72ee14d6b36aa4ffb65f27",
    "homepage": "https://github.com/visionmedia/consolidate.js#readme",
    "keywords": [
        "engine",
        "template",
        "view"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "bridgear",
            "email": "ruben@bridgewater.de"
        },
        {
            "name": "doowb",
            "email": "brian.woodward@gmail.com"
        },
        {
            "name": "niftylettuce",
            "email": "niftylettuce@gmail.com"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "consolidate",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/visionmedia/consolidate.js.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.14.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module consolidate](#apidoc.module.consolidate)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>arc-templates (path, options, fn)](#apidoc.element.consolidate.arc-templates)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>atpl (path, options, fn)](#apidoc.element.consolidate.atpl)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>bracket (path, options, fn)](#apidoc.element.consolidate.bracket)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>clearCache ()](#apidoc.element.consolidate.clearCache)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>dot (path, options, fn)](#apidoc.element.consolidate.dot)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>dust (path, options, fn)](#apidoc.element.consolidate.dust)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>eco (path, options, fn)](#apidoc.element.consolidate.eco)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>ect (path, options, fn)](#apidoc.element.consolidate.ect)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>ejs (path, options, fn)](#apidoc.element.consolidate.ejs)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>haml (path, options, fn)](#apidoc.element.consolidate.haml)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>haml-coffee (path, options, fn)](#apidoc.element.consolidate.haml-coffee)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>hamlet (path, options, fn)](#apidoc.element.consolidate.hamlet)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>handlebars (path, options, fn)](#apidoc.element.consolidate.handlebars)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>hogan (path, options, fn)](#apidoc.element.consolidate.hogan)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>htmling (path, options, fn)](#apidoc.element.consolidate.htmling)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>jade (path, options, fn)](#apidoc.element.consolidate.jade)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>jazz (path, options, fn)](#apidoc.element.consolidate.jazz)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>jqtpl (path, options, fn)](#apidoc.element.consolidate.jqtpl)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>just (path, options, fn)](#apidoc.element.consolidate.just)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>liquid (path, options, fn)](#apidoc.element.consolidate.liquid)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>liquor (path, options, fn)](#apidoc.element.consolidate.liquor)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>lodash (path, options, fn)](#apidoc.element.consolidate.lodash)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>marko (path, options, fn)](#apidoc.element.consolidate.marko)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>mote (path, options, fn)](#apidoc.element.consolidate.mote)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>mustache (path, options, fn)](#apidoc.element.consolidate.mustache)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>nunjucks (path, options, fn)](#apidoc.element.consolidate.nunjucks)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>pug (path, options, fn)](#apidoc.element.consolidate.pug)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>qejs (path, options, fn)](#apidoc.element.consolidate.qejs)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>ractive (path, options, fn)](#apidoc.element.consolidate.ractive)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>react (str, options, fn)](#apidoc.element.consolidate.react)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>requireReact (module, filename)](#apidoc.element.consolidate.requireReact)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>slm (path, options, fn)](#apidoc.element.consolidate.slm)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>swig (path, options, fn)](#apidoc.element.consolidate.swig)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>templayed (path, options, fn)](#apidoc.element.consolidate.templayed)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>toffee (path, options, fn)](#apidoc.element.consolidate.toffee)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>twig (path, options, fn)](#apidoc.element.consolidate.twig)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>underscore (path, options, fn)](#apidoc.element.consolidate.underscore)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>vash (path, options, fn)](#apidoc.element.consolidate.vash)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>walrus (path, options, fn)](#apidoc.element.consolidate.walrus)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>whiskers (path, options, fn)](#apidoc.element.consolidate.whiskers)
1.  object <span class="apidocSignatureSpan">consolidate.</span>requires

#### [module consolidate.arc-templates](#apidoc.module.consolidate.arc-templates)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>arc-templates (path, options, fn)](#apidoc.element.consolidate.arc-templates.arc-templates)
1.  [function <span class="apidocSignatureSpan">consolidate.arc-templates.</span>render (str, options, fn)](#apidoc.element.consolidate.arc-templates.render)

#### [module consolidate.atpl](#apidoc.module.consolidate.atpl)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>atpl (path, options, fn)](#apidoc.element.consolidate.atpl.atpl)
1.  [function <span class="apidocSignatureSpan">consolidate.atpl.</span>render (str, options, fn)](#apidoc.element.consolidate.atpl.render)

#### [module consolidate.bracket](#apidoc.module.consolidate.bracket)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>bracket (path, options, fn)](#apidoc.element.consolidate.bracket.bracket)
1.  [function <span class="apidocSignatureSpan">consolidate.bracket.</span>render (str, options, fn)](#apidoc.element.consolidate.bracket.render)

#### [module consolidate.dot](#apidoc.module.consolidate.dot)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>dot (path, options, fn)](#apidoc.element.consolidate.dot.dot)
1.  [function <span class="apidocSignatureSpan">consolidate.dot.</span>render (str, options, fn)](#apidoc.element.consolidate.dot.render)

#### [module consolidate.dust](#apidoc.module.consolidate.dust)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>dust (path, options, fn)](#apidoc.element.consolidate.dust.dust)
1.  [function <span class="apidocSignatureSpan">consolidate.dust.</span>render (str, options, fn)](#apidoc.element.consolidate.dust.render)

#### [module consolidate.eco](#apidoc.module.consolidate.eco)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>eco (path, options, fn)](#apidoc.element.consolidate.eco.eco)
1.  [function <span class="apidocSignatureSpan">consolidate.eco.</span>render (str, options, fn)](#apidoc.element.consolidate.eco.render)

#### [module consolidate.ect](#apidoc.module.consolidate.ect)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>ect (path, options, fn)](#apidoc.element.consolidate.ect.ect)
1.  [function <span class="apidocSignatureSpan">consolidate.ect.</span>render (str, options, fn)](#apidoc.element.consolidate.ect.render)

#### [module consolidate.ejs](#apidoc.module.consolidate.ejs)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>ejs (path, options, fn)](#apidoc.element.consolidate.ejs.ejs)
1.  [function <span class="apidocSignatureSpan">consolidate.ejs.</span>render (str, options, fn)](#apidoc.element.consolidate.ejs.render)

#### [module consolidate.haml](#apidoc.module.consolidate.haml)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>haml (path, options, fn)](#apidoc.element.consolidate.haml.haml)
1.  [function <span class="apidocSignatureSpan">consolidate.haml.</span>render (str, options, fn)](#apidoc.element.consolidate.haml.render)

#### [module consolidate.haml-coffee](#apidoc.module.consolidate.haml-coffee)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>haml-coffee (path, options, fn)](#apidoc.element.consolidate.haml-coffee.haml-coffee)
1.  [function <span class="apidocSignatureSpan">consolidate.haml-coffee.</span>render (str, options, fn)](#apidoc.element.consolidate.haml-coffee.render)

#### [module consolidate.hamlet](#apidoc.module.consolidate.hamlet)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>hamlet (path, options, fn)](#apidoc.element.consolidate.hamlet.hamlet)
1.  [function <span class="apidocSignatureSpan">consolidate.hamlet.</span>render (str, options, fn)](#apidoc.element.consolidate.hamlet.render)

#### [module consolidate.handlebars](#apidoc.module.consolidate.handlebars)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>handlebars (path, options, fn)](#apidoc.element.consolidate.handlebars.handlebars)
1.  [function <span class="apidocSignatureSpan">consolidate.handlebars.</span>render (str, options, fn)](#apidoc.element.consolidate.handlebars.render)

#### [module consolidate.hogan](#apidoc.module.consolidate.hogan)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>hogan (path, options, fn)](#apidoc.element.consolidate.hogan.hogan)
1.  [function <span class="apidocSignatureSpan">consolidate.hogan.</span>render (str, options, fn)](#apidoc.element.consolidate.hogan.render)

#### [module consolidate.htmling](#apidoc.module.consolidate.htmling)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>htmling (path, options, fn)](#apidoc.element.consolidate.htmling.htmling)
1.  [function <span class="apidocSignatureSpan">consolidate.htmling.</span>render (str, options, fn)](#apidoc.element.consolidate.htmling.render)

#### [module consolidate.jade](#apidoc.module.consolidate.jade)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>jade (path, options, fn)](#apidoc.element.consolidate.jade.jade)
1.  [function <span class="apidocSignatureSpan">consolidate.jade.</span>render (str, options, fn)](#apidoc.element.consolidate.jade.render)

#### [module consolidate.jazz](#apidoc.module.consolidate.jazz)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>jazz (path, options, fn)](#apidoc.element.consolidate.jazz.jazz)
1.  [function <span class="apidocSignatureSpan">consolidate.jazz.</span>render (str, options, fn)](#apidoc.element.consolidate.jazz.render)

#### [module consolidate.jqtpl](#apidoc.module.consolidate.jqtpl)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>jqtpl (path, options, fn)](#apidoc.element.consolidate.jqtpl.jqtpl)
1.  [function <span class="apidocSignatureSpan">consolidate.jqtpl.</span>render (str, options, fn)](#apidoc.element.consolidate.jqtpl.render)

#### [module consolidate.just](#apidoc.module.consolidate.just)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>just (path, options, fn)](#apidoc.element.consolidate.just.just)
1.  [function <span class="apidocSignatureSpan">consolidate.just.</span>render (str, options, fn)](#apidoc.element.consolidate.just.render)

#### [module consolidate.liquid](#apidoc.module.consolidate.liquid)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>liquid (path, options, fn)](#apidoc.element.consolidate.liquid.liquid)
1.  [function <span class="apidocSignatureSpan">consolidate.liquid.</span>render (str, options, fn)](#apidoc.element.consolidate.liquid.render)

#### [module consolidate.liquor](#apidoc.module.consolidate.liquor)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>liquor (path, options, fn)](#apidoc.element.consolidate.liquor.liquor)
1.  [function <span class="apidocSignatureSpan">consolidate.liquor.</span>render (str, options, fn)](#apidoc.element.consolidate.liquor.render)

#### [module consolidate.lodash](#apidoc.module.consolidate.lodash)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>lodash (path, options, fn)](#apidoc.element.consolidate.lodash.lodash)
1.  [function <span class="apidocSignatureSpan">consolidate.lodash.</span>render (str, options, fn)](#apidoc.element.consolidate.lodash.render)

#### [module consolidate.marko](#apidoc.module.consolidate.marko)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>marko (path, options, fn)](#apidoc.element.consolidate.marko.marko)
1.  [function <span class="apidocSignatureSpan">consolidate.marko.</span>render (str, options, fn)](#apidoc.element.consolidate.marko.render)

#### [module consolidate.mote](#apidoc.module.consolidate.mote)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>mote (path, options, fn)](#apidoc.element.consolidate.mote.mote)
1.  [function <span class="apidocSignatureSpan">consolidate.mote.</span>render (str, options, fn)](#apidoc.element.consolidate.mote.render)

#### [module consolidate.mustache](#apidoc.module.consolidate.mustache)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>mustache (path, options, fn)](#apidoc.element.consolidate.mustache.mustache)
1.  [function <span class="apidocSignatureSpan">consolidate.mustache.</span>render (str, options, fn)](#apidoc.element.consolidate.mustache.render)

#### [module consolidate.nunjucks](#apidoc.module.consolidate.nunjucks)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>nunjucks (path, options, fn)](#apidoc.element.consolidate.nunjucks.nunjucks)
1.  [function <span class="apidocSignatureSpan">consolidate.nunjucks.</span>render (str, options, fn)](#apidoc.element.consolidate.nunjucks.render)

#### [module consolidate.pug](#apidoc.module.consolidate.pug)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>pug (path, options, fn)](#apidoc.element.consolidate.pug.pug)
1.  [function <span class="apidocSignatureSpan">consolidate.pug.</span>render (str, options, fn)](#apidoc.element.consolidate.pug.render)

#### [module consolidate.qejs](#apidoc.module.consolidate.qejs)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>qejs (path, options, fn)](#apidoc.element.consolidate.qejs.qejs)
1.  [function <span class="apidocSignatureSpan">consolidate.qejs.</span>render (str, options, fn)](#apidoc.element.consolidate.qejs.render)

#### [module consolidate.ractive](#apidoc.module.consolidate.ractive)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>ractive (path, options, fn)](#apidoc.element.consolidate.ractive.ractive)
1.  [function <span class="apidocSignatureSpan">consolidate.ractive.</span>render (str, options, fn)](#apidoc.element.consolidate.ractive.render)

#### [module consolidate.react](#apidoc.module.consolidate.react)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>react (str, options, fn)](#apidoc.element.consolidate.react.react)
1.  [function <span class="apidocSignatureSpan">consolidate.react.</span>render (str, options, fn)](#apidoc.element.consolidate.react.render)

#### [module consolidate.slm](#apidoc.module.consolidate.slm)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>slm (path, options, fn)](#apidoc.element.consolidate.slm.slm)
1.  [function <span class="apidocSignatureSpan">consolidate.slm.</span>render (str, options, fn)](#apidoc.element.consolidate.slm.render)

#### [module consolidate.swig](#apidoc.module.consolidate.swig)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>swig (path, options, fn)](#apidoc.element.consolidate.swig.swig)
1.  [function <span class="apidocSignatureSpan">consolidate.swig.</span>render (str, options, fn)](#apidoc.element.consolidate.swig.render)

#### [module consolidate.templayed](#apidoc.module.consolidate.templayed)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>templayed (path, options, fn)](#apidoc.element.consolidate.templayed.templayed)
1.  [function <span class="apidocSignatureSpan">consolidate.templayed.</span>render (str, options, fn)](#apidoc.element.consolidate.templayed.render)

#### [module consolidate.toffee](#apidoc.module.consolidate.toffee)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>toffee (path, options, fn)](#apidoc.element.consolidate.toffee.toffee)
1.  [function <span class="apidocSignatureSpan">consolidate.toffee.</span>render (str, options, fn)](#apidoc.element.consolidate.toffee.render)

#### [module consolidate.twig](#apidoc.module.consolidate.twig)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>twig (path, options, fn)](#apidoc.element.consolidate.twig.twig)
1.  [function <span class="apidocSignatureSpan">consolidate.twig.</span>render (str, options, fn)](#apidoc.element.consolidate.twig.render)

#### [module consolidate.underscore](#apidoc.module.consolidate.underscore)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>underscore (path, options, fn)](#apidoc.element.consolidate.underscore.underscore)
1.  [function <span class="apidocSignatureSpan">consolidate.underscore.</span>render (str, options, fn)](#apidoc.element.consolidate.underscore.render)

#### [module consolidate.vash](#apidoc.module.consolidate.vash)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>vash (path, options, fn)](#apidoc.element.consolidate.vash.vash)
1.  [function <span class="apidocSignatureSpan">consolidate.vash.</span>render (str, options, fn)](#apidoc.element.consolidate.vash.render)

#### [module consolidate.walrus](#apidoc.module.consolidate.walrus)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>walrus (path, options, fn)](#apidoc.element.consolidate.walrus.walrus)
1.  [function <span class="apidocSignatureSpan">consolidate.walrus.</span>render (str, options, fn)](#apidoc.element.consolidate.walrus.render)

#### [module consolidate.whiskers](#apidoc.module.consolidate.whiskers)
1.  [function <span class="apidocSignatureSpan">consolidate.</span>whiskers (path, options, fn)](#apidoc.element.consolidate.whiskers.whiskers)
1.  [function <span class="apidocSignatureSpan">consolidate.whiskers.</span>render (str, options, fn)](#apidoc.element.consolidate.whiskers.render)



# <a name="apidoc.module.consolidate"></a>[module consolidate](#apidoc.module.consolidate)

#### <a name="apidoc.element.consolidate.arc-templates"></a>[function <span class="apidocSignatureSpan">consolidate.</span>arc-templates (path, options, fn)](#apidoc.element.consolidate.arc-templates)
- description and source-code
```javascript
arc-templates = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.atpl"></a>[function <span class="apidocSignatureSpan">consolidate.</span>atpl (path, options, fn)](#apidoc.element.consolidate.atpl)
- description and source-code
```javascript
atpl = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.bracket"></a>[function <span class="apidocSignatureSpan">consolidate.</span>bracket (path, options, fn)](#apidoc.element.consolidate.bracket)
- description and source-code
```javascript
bracket = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.clearCache"></a>[function <span class="apidocSignatureSpan">consolidate.</span>clearCache ()](#apidoc.element.consolidate.clearCache)
- description and source-code
```javascript
clearCache = function (){
  cacheStore = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.dot"></a>[function <span class="apidocSignatureSpan">consolidate.</span>dot (path, options, fn)](#apidoc.element.consolidate.dot)
- description and source-code
```javascript
dot = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.dust"></a>[function <span class="apidocSignatureSpan">consolidate.</span>dust (path, options, fn)](#apidoc.element.consolidate.dust)
- description and source-code
```javascript
dust = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.eco"></a>[function <span class="apidocSignatureSpan">consolidate.</span>eco (path, options, fn)](#apidoc.element.consolidate.eco)
- description and source-code
```javascript
eco = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.ect"></a>[function <span class="apidocSignatureSpan">consolidate.</span>ect (path, options, fn)](#apidoc.element.consolidate.ect)
- description and source-code
```javascript
ect = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.ect;
    if (!engine) {
      var ECT = require('ect');
      engine = requires.ect = new ECT(options);
    }
    engine.configure({ cache: options.cache });
    engine.render(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.ejs"></a>[function <span class="apidocSignatureSpan">consolidate.</span>ejs (path, options, fn)](#apidoc.element.consolidate.ejs)
- description and source-code
```javascript
ejs = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.haml"></a>[function <span class="apidocSignatureSpan">consolidate.</span>haml (path, options, fn)](#apidoc.element.consolidate.haml)
- description and source-code
```javascript
haml = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.haml-coffee"></a>[function <span class="apidocSignatureSpan">consolidate.</span>haml-coffee (path, options, fn)](#apidoc.element.consolidate.haml-coffee)
- description and source-code
```javascript
haml-coffee = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.hamlet"></a>[function <span class="apidocSignatureSpan">consolidate.</span>hamlet (path, options, fn)](#apidoc.element.consolidate.hamlet)
- description and source-code
```javascript
hamlet = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.handlebars"></a>[function <span class="apidocSignatureSpan">consolidate.</span>handlebars (path, options, fn)](#apidoc.element.consolidate.handlebars)
- description and source-code
```javascript
handlebars = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.hogan"></a>[function <span class="apidocSignatureSpan">consolidate.</span>hogan (path, options, fn)](#apidoc.element.consolidate.hogan)
- description and source-code
```javascript
hogan = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.htmling"></a>[function <span class="apidocSignatureSpan">consolidate.</span>htmling (path, options, fn)](#apidoc.element.consolidate.htmling)
- description and source-code
```javascript
htmling = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.jade"></a>[function <span class="apidocSignatureSpan">consolidate.</span>jade (path, options, fn)](#apidoc.element.consolidate.jade)
- description and source-code
```javascript
jade = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.jade;
    if (!engine) {
      try {
        engine = requires.jade = require('jade');
      } catch (err) {
        try {
          engine = requires.jade = require('then-jade');
        } catch (otherError) {
          throw err;
        }
      }
    }

    try {
      var tmpl = cache(options) || cache(options, engine.compileFile(path, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.jazz"></a>[function <span class="apidocSignatureSpan">consolidate.</span>jazz (path, options, fn)](#apidoc.element.consolidate.jazz)
- description and source-code
```javascript
jazz = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.jqtpl"></a>[function <span class="apidocSignatureSpan">consolidate.</span>jqtpl (path, options, fn)](#apidoc.element.consolidate.jqtpl)
- description and source-code
```javascript
jqtpl = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.just"></a>[function <span class="apidocSignatureSpan">consolidate.</span>just (path, options, fn)](#apidoc.element.consolidate.just)
- description and source-code
```javascript
just = function (path, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.just;
    if (!engine) {
      var JUST = require('just');
      engine = requires.just = new JUST();
    }
    engine.configure({ useCache: options.cache });
    engine.render(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.liquid"></a>[function <span class="apidocSignatureSpan">consolidate.</span>liquid (path, options, fn)](#apidoc.element.consolidate.liquid)
- description and source-code
```javascript
liquid = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.liquor"></a>[function <span class="apidocSignatureSpan">consolidate.</span>liquor (path, options, fn)](#apidoc.element.consolidate.liquor)
- description and source-code
```javascript
liquor = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.lodash"></a>[function <span class="apidocSignatureSpan">consolidate.</span>lodash (path, options, fn)](#apidoc.element.consolidate.lodash)
- description and source-code
```javascript
lodash = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.marko"></a>[function <span class="apidocSignatureSpan">consolidate.</span>marko (path, options, fn)](#apidoc.element.consolidate.marko)
- description and source-code
```javascript
marko = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.marko || (requires.marko = require('marko'));
    options.writeToDisk = !!options.cache;

    try {
      var tmpl = cache(options) || cache(options, engine.load(path, options));
      tmpl.render(options, fn)
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.mote"></a>[function <span class="apidocSignatureSpan">consolidate.</span>mote (path, options, fn)](#apidoc.element.consolidate.mote)
- description and source-code
```javascript
mote = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.mustache"></a>[function <span class="apidocSignatureSpan">consolidate.</span>mustache (path, options, fn)](#apidoc.element.consolidate.mustache)
- description and source-code
```javascript
mustache = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.nunjucks"></a>[function <span class="apidocSignatureSpan">consolidate.</span>nunjucks (path, options, fn)](#apidoc.element.consolidate.nunjucks)
- description and source-code
```javascript
nunjucks = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.pug"></a>[function <span class="apidocSignatureSpan">consolidate.</span>pug (path, options, fn)](#apidoc.element.consolidate.pug)
- description and source-code
```javascript
pug = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.pug;
    if (!engine) {
      try {
        engine = requires.pug = require('pug');
      } catch (err) {
        try {
          engine = requires.pug = require('then-pug');
        } catch (otherError) {
          throw err;
        }
      }
    }

    try {
      var tmpl = cache(options) || cache(options, engine.compileFile(path, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.qejs"></a>[function <span class="apidocSignatureSpan">consolidate.</span>qejs (path, options, fn)](#apidoc.element.consolidate.qejs)
- description and source-code
```javascript
qejs = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.ractive"></a>[function <span class="apidocSignatureSpan">consolidate.</span>ractive (path, options, fn)](#apidoc.element.consolidate.ractive)
- description and source-code
```javascript
ractive = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.react"></a>[function <span class="apidocSignatureSpan">consolidate.</span>react (str, options, fn)](#apidoc.element.consolidate.react)
- description and source-code
```javascript
react = function (str, options, fn) {
  return promisify(fn, function(fn) {
    // React Import
    var ReactDOM = requires.ReactDOM || (requires.ReactDOM = require('react-dom/server'));
    var react = requires.react || (requires.react = require('react'));

    // Assign HTML Base
    var base = options.base;
    delete options.base;

    var enableCache = options.cache;
    delete options.cache;

    var isNonStatic = options.isNonStatic;
    delete options.isNonStatic;

    // Start Conversion
    try {

      var Code;
      var Factory;

      var baseStr;
      var content;
      var parsed;

      if (!cache(options)){
        // Parsing
        Code = (type === 'path') ? require(resolve(str)) : requireReactString(str);
        Factory = cache(options, react.createFactory(Code));

      } else {
        Factory = cache(options);
      }

      parsed = new Factory(options);
      content = (isNonStatic) ? ReactDOM.renderToString(parsed) : ReactDOM.renderToStaticMarkup(parsed);

      if (base){
        baseStr = readCache[str] || fs.readFileSync(resolve(base), 'utf8');

        if (enableCache){
          readCache[str] = baseStr;
        }

        options.content = content;
        content = reactBaseTmpl(baseStr, options);
      }

      fn(null, content);

    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.requireReact"></a>[function <span class="apidocSignatureSpan">consolidate.</span>requireReact (module, filename)](#apidoc.element.consolidate.requireReact)
- description and source-code
```javascript
function requireReact(module, filename) {
  var babel = requires.babel || (requires.babel = require('babel-core'));

  var compiled = babel.transformFileSync(filename, { presets: [ 'react' ] }).code

  return module._compile(compiled, filename);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.slm"></a>[function <span class="apidocSignatureSpan">consolidate.</span>slm (path, options, fn)](#apidoc.element.consolidate.slm)
- description and source-code
```javascript
slm = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.swig"></a>[function <span class="apidocSignatureSpan">consolidate.</span>swig (path, options, fn)](#apidoc.element.consolidate.swig)
- description and source-code
```javascript
swig = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
...

All templates supported by this library may be rendered using the signature '(path[, locals], callback)' as shown below, which happens
 to be the signature that Express 3.x supports so any of these engines may be used within Express.

__NOTE__: All this example code uses cons.swig for the swig template engine. Replace swig with whatever templating you are using
. For example, use cons.hogan for hogan.js, cons.jade for jade, etc. 'console.log(cons)' for the full list of identifiers.

'''js
var cons = require('consolidate');
cons.swig('views/page.html', { user: 'tobi' }, function(err, html){
if (err) throw err;
console.log(html);
});
'''

Or without options / local variables:
...
```

#### <a name="apidoc.element.consolidate.templayed"></a>[function <span class="apidocSignatureSpan">consolidate.</span>templayed (path, options, fn)](#apidoc.element.consolidate.templayed)
- description and source-code
```javascript
templayed = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.toffee"></a>[function <span class="apidocSignatureSpan">consolidate.</span>toffee (path, options, fn)](#apidoc.element.consolidate.toffee)
- description and source-code
```javascript
toffee = function (path, options, fn){
  return promisify(fn, function (fn) {
    var toffee = requires.toffee || (requires.toffee = require('toffee'));
    toffee.__consolidate_engine_render(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.twig"></a>[function <span class="apidocSignatureSpan">consolidate.</span>twig (path, options, fn)](#apidoc.element.consolidate.twig)
- description and source-code
```javascript
twig = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.underscore"></a>[function <span class="apidocSignatureSpan">consolidate.</span>underscore (path, options, fn)](#apidoc.element.consolidate.underscore)
- description and source-code
```javascript
underscore = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.vash"></a>[function <span class="apidocSignatureSpan">consolidate.</span>vash (path, options, fn)](#apidoc.element.consolidate.vash)
- description and source-code
```javascript
vash = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.walrus"></a>[function <span class="apidocSignatureSpan">consolidate.</span>walrus (path, options, fn)](#apidoc.element.consolidate.walrus)
- description and source-code
```javascript
walrus = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.whiskers"></a>[function <span class="apidocSignatureSpan">consolidate.</span>whiskers (path, options, fn)](#apidoc.element.consolidate.whiskers)
- description and source-code
```javascript
whiskers = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.whiskers || (requires.whiskers = require('whiskers'));
    engine.__express(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.consolidate.arc-templates"></a>[module consolidate.arc-templates](#apidoc.module.consolidate.arc-templates)

#### <a name="apidoc.element.consolidate.arc-templates.arc-templates"></a>[function <span class="apidocSignatureSpan">consolidate.</span>arc-templates (path, options, fn)](#apidoc.element.consolidate.arc-templates.arc-templates)
- description and source-code
```javascript
arc-templates = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.arc-templates.render"></a>[function <span class="apidocSignatureSpan">consolidate.arc-templates.</span>render (str, options, fn)](#apidoc.element.consolidate.arc-templates.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  var readFileWithOptions = Promise.promisify(read);
  var consolidateFileSystem = {};
  consolidateFileSystem.readFile = function (path) {
    return readFileWithOptions(path, options);
  };

  return promisify(fn, function (fn) {
    try {
      var engine = requires['arc-templates'];
      if (!engine) {
        var Engine = require('arc-templates/dist/es5');
        engine = requires['arc-templates'] = new Engine({ filesystem: consolidateFileSystem });
      }

      var compiler = cache(options) || cache(options, engine.compileString(str, options.filename));
      compiler.then(function (func) { return func(options); })
          .then(function (result) { fn(null, result.content); })
          .catch(fn);
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.atpl"></a>[module consolidate.atpl](#apidoc.module.consolidate.atpl)

#### <a name="apidoc.element.consolidate.atpl.atpl"></a>[function <span class="apidocSignatureSpan">consolidate.</span>atpl (path, options, fn)](#apidoc.element.consolidate.atpl.atpl)
- description and source-code
```javascript
atpl = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.atpl.render"></a>[function <span class="apidocSignatureSpan">consolidate.atpl.</span>render (str, options, fn)](#apidoc.element.consolidate.atpl.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.atpl || (requires.atpl = require('atpl'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.bracket"></a>[module consolidate.bracket](#apidoc.module.consolidate.bracket)

#### <a name="apidoc.element.consolidate.bracket.bracket"></a>[function <span class="apidocSignatureSpan">consolidate.</span>bracket (path, options, fn)](#apidoc.element.consolidate.bracket.bracket)
- description and source-code
```javascript
bracket = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.bracket.render"></a>[function <span class="apidocSignatureSpan">consolidate.bracket.</span>render (str, options, fn)](#apidoc.element.consolidate.bracket.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.bracket || (requires.bracket = require('bracket-template'));
    try {
      var tmpl = cache(options) || cache(options, engine.default.compile(str));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.dot"></a>[module consolidate.dot](#apidoc.module.consolidate.dot)

#### <a name="apidoc.element.consolidate.dot.dot"></a>[function <span class="apidocSignatureSpan">consolidate.</span>dot (path, options, fn)](#apidoc.element.consolidate.dot.dot)
- description and source-code
```javascript
dot = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.dot.render"></a>[function <span class="apidocSignatureSpan">consolidate.dot.</span>render (str, options, fn)](#apidoc.element.consolidate.dot.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.dot || (requires.dot = require('dot'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options && options._def));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.dust"></a>[module consolidate.dust](#apidoc.module.consolidate.dust)

#### <a name="apidoc.element.consolidate.dust.dust"></a>[function <span class="apidocSignatureSpan">consolidate.</span>dust (path, options, fn)](#apidoc.element.consolidate.dust.dust)
- description and source-code
```javascript
dust = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.dust.render"></a>[function <span class="apidocSignatureSpan">consolidate.dust.</span>render (str, options, fn)](#apidoc.element.consolidate.dust.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.dust;
    if (!engine) {
      try {
        engine = requires.dust = require('dust');
      } catch (err) {
        try {
          engine = requires.dust = require('dustjs-helpers');
        } catch (err) {
          engine = requires.dust = require('dustjs-linkedin');
        }
      }
    }

    var ext = 'dust';
    var views = '.';

    if (options) {
      if (options.ext) ext = options.ext;
      if (options.views) views = options.views;
      if (options.settings && options.settings.views) views = options.settings.views;
    }
    if (!options || (options && !options.cache)) engine.cache = {};

    engine.onLoad = function(path, callback){
      if ('' === extname(path)) path += '.' + ext;
      if ('/' !== path[0]) path = views + '/' + path;
      read(path, options, callback);
    };

    try {
      var tmpl = cache(options) || cache(options, engine.compileFn(str));
      tmpl(options, fn);
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.eco"></a>[module consolidate.eco](#apidoc.module.consolidate.eco)

#### <a name="apidoc.element.consolidate.eco.eco"></a>[function <span class="apidocSignatureSpan">consolidate.</span>eco (path, options, fn)](#apidoc.element.consolidate.eco.eco)
- description and source-code
```javascript
eco = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.eco.render"></a>[function <span class="apidocSignatureSpan">consolidate.eco.</span>render (str, options, fn)](#apidoc.element.consolidate.eco.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.eco || (requires.eco = require('eco'));
    try {
      fn(null, engine.render(str, options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.ect"></a>[module consolidate.ect](#apidoc.module.consolidate.ect)

#### <a name="apidoc.element.consolidate.ect.ect"></a>[function <span class="apidocSignatureSpan">consolidate.</span>ect (path, options, fn)](#apidoc.element.consolidate.ect.ect)
- description and source-code
```javascript
ect = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.ect;
    if (!engine) {
      var ECT = require('ect');
      engine = requires.ect = new ECT(options);
    }
    engine.configure({ cache: options.cache });
    engine.render(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.ect.render"></a>[function <span class="apidocSignatureSpan">consolidate.ect.</span>render (str, options, fn)](#apidoc.element.consolidate.ect.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var ECT = require('ect');
    var engine = new ECT({ root: { page: str }});
    engine.render('page', options, fn);
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.ejs"></a>[module consolidate.ejs](#apidoc.module.consolidate.ejs)

#### <a name="apidoc.element.consolidate.ejs.ejs"></a>[function <span class="apidocSignatureSpan">consolidate.</span>ejs (path, options, fn)](#apidoc.element.consolidate.ejs.ejs)
- description and source-code
```javascript
ejs = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.ejs.render"></a>[function <span class="apidocSignatureSpan">consolidate.ejs.</span>render (str, options, fn)](#apidoc.element.consolidate.ejs.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.ejs || (requires.ejs = require('ejs'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.haml"></a>[module consolidate.haml](#apidoc.module.consolidate.haml)

#### <a name="apidoc.element.consolidate.haml.haml"></a>[function <span class="apidocSignatureSpan">consolidate.</span>haml (path, options, fn)](#apidoc.element.consolidate.haml.haml)
- description and source-code
```javascript
haml = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.haml.render"></a>[function <span class="apidocSignatureSpan">consolidate.haml.</span>render (str, options, fn)](#apidoc.element.consolidate.haml.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.haml || (requires.haml = require('hamljs'));
    try {
      options.locals = options;
      fn(null, engine.render(str, options).trimLeft());
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.haml-coffee"></a>[module consolidate.haml-coffee](#apidoc.module.consolidate.haml-coffee)

#### <a name="apidoc.element.consolidate.haml-coffee.haml-coffee"></a>[function <span class="apidocSignatureSpan">consolidate.</span>haml-coffee (path, options, fn)](#apidoc.element.consolidate.haml-coffee.haml-coffee)
- description and source-code
```javascript
haml-coffee = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.haml-coffee.render"></a>[function <span class="apidocSignatureSpan">consolidate.haml-coffee.</span>render (str, options, fn)](#apidoc.element.consolidate.haml-coffee.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires['haml-coffee'] || (requires['haml-coffee'] = require('haml-coffee'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.hamlet"></a>[module consolidate.hamlet](#apidoc.module.consolidate.hamlet)

#### <a name="apidoc.element.consolidate.hamlet.hamlet"></a>[function <span class="apidocSignatureSpan">consolidate.</span>hamlet (path, options, fn)](#apidoc.element.consolidate.hamlet.hamlet)
- description and source-code
```javascript
hamlet = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.hamlet.render"></a>[function <span class="apidocSignatureSpan">consolidate.hamlet.</span>render (str, options, fn)](#apidoc.element.consolidate.hamlet.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.hamlet || (requires.hamlet = require('hamlet'));
    try {
      options.locals = options;
      fn(null, engine.render(str, options).trimLeft());
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.handlebars"></a>[module consolidate.handlebars](#apidoc.module.consolidate.handlebars)

#### <a name="apidoc.element.consolidate.handlebars.handlebars"></a>[function <span class="apidocSignatureSpan">consolidate.</span>handlebars (path, options, fn)](#apidoc.element.consolidate.handlebars.handlebars)
- description and source-code
```javascript
handlebars = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.handlebars.render"></a>[function <span class="apidocSignatureSpan">consolidate.handlebars.</span>render (str, options, fn)](#apidoc.element.consolidate.handlebars.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function(fn) {
    var engine = requires.handlebars || (requires.handlebars = require('handlebars'));
    try {
      for (var partial in options.partials) {
        engine.registerPartial(partial, options.partials[partial]);
      }
      for (var helper in options.helpers) {
        engine.registerHelper(helper, options.helpers[helper]);
      }
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.hogan"></a>[module consolidate.hogan](#apidoc.module.consolidate.hogan)

#### <a name="apidoc.element.consolidate.hogan.hogan"></a>[function <span class="apidocSignatureSpan">consolidate.</span>hogan (path, options, fn)](#apidoc.element.consolidate.hogan.hogan)
- description and source-code
```javascript
hogan = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.hogan.render"></a>[function <span class="apidocSignatureSpan">consolidate.hogan.</span>render (str, options, fn)](#apidoc.element.consolidate.hogan.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.hogan || (requires.hogan = require('hogan.js'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl.render(options, options.partials));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.htmling"></a>[module consolidate.htmling](#apidoc.module.consolidate.htmling)

#### <a name="apidoc.element.consolidate.htmling.htmling"></a>[function <span class="apidocSignatureSpan">consolidate.</span>htmling (path, options, fn)](#apidoc.element.consolidate.htmling.htmling)
- description and source-code
```javascript
htmling = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.htmling.render"></a>[function <span class="apidocSignatureSpan">consolidate.htmling.</span>render (str, options, fn)](#apidoc.element.consolidate.htmling.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.htmling || (requires.htmling = require('htmling'));
    try {
      var tmpl = cache(options) || cache(options, engine.string(str));
      fn(null, tmpl.render(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.jade"></a>[module consolidate.jade](#apidoc.module.consolidate.jade)

#### <a name="apidoc.element.consolidate.jade.jade"></a>[function <span class="apidocSignatureSpan">consolidate.</span>jade (path, options, fn)](#apidoc.element.consolidate.jade.jade)
- description and source-code
```javascript
jade = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.jade;
    if (!engine) {
      try {
        engine = requires.jade = require('jade');
      } catch (err) {
        try {
          engine = requires.jade = require('then-jade');
        } catch (otherError) {
          throw err;
        }
      }
    }

    try {
      var tmpl = cache(options) || cache(options, engine.compileFile(path, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.jade.render"></a>[function <span class="apidocSignatureSpan">consolidate.jade.</span>render (str, options, fn)](#apidoc.element.consolidate.jade.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.jade;
    if (!engine) {
      try {
        engine = requires.jade = require('jade');
      } catch (err) {
        try {
          engine = requires.jade = require('then-jade');
        } catch (otherError) {
          throw err;
        }
      }
    }

    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.jazz"></a>[module consolidate.jazz](#apidoc.module.consolidate.jazz)

#### <a name="apidoc.element.consolidate.jazz.jazz"></a>[function <span class="apidocSignatureSpan">consolidate.</span>jazz (path, options, fn)](#apidoc.element.consolidate.jazz.jazz)
- description and source-code
```javascript
jazz = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.jazz.render"></a>[function <span class="apidocSignatureSpan">consolidate.jazz.</span>render (str, options, fn)](#apidoc.element.consolidate.jazz.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.jazz || (requires.jazz = require('jazz'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      tmpl.eval(options, function(str){
        fn(null, str);
      });
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.jqtpl"></a>[module consolidate.jqtpl](#apidoc.module.consolidate.jqtpl)

#### <a name="apidoc.element.consolidate.jqtpl.jqtpl"></a>[function <span class="apidocSignatureSpan">consolidate.</span>jqtpl (path, options, fn)](#apidoc.element.consolidate.jqtpl.jqtpl)
- description and source-code
```javascript
jqtpl = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.jqtpl.render"></a>[function <span class="apidocSignatureSpan">consolidate.jqtpl.</span>render (str, options, fn)](#apidoc.element.consolidate.jqtpl.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.jqtpl || (requires.jqtpl = require('jqtpl'));
    try {
      engine.template(str, str);
      fn(null, engine.tmpl(str, options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.just"></a>[module consolidate.just](#apidoc.module.consolidate.just)

#### <a name="apidoc.element.consolidate.just.just"></a>[function <span class="apidocSignatureSpan">consolidate.</span>just (path, options, fn)](#apidoc.element.consolidate.just.just)
- description and source-code
```javascript
just = function (path, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.just;
    if (!engine) {
      var JUST = require('just');
      engine = requires.just = new JUST();
    }
    engine.configure({ useCache: options.cache });
    engine.render(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.just.render"></a>[function <span class="apidocSignatureSpan">consolidate.just.</span>render (str, options, fn)](#apidoc.element.consolidate.just.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var JUST = require('just');
    var engine = new JUST({ root: { page: str }});
    engine.render('page', options, fn);
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.liquid"></a>[module consolidate.liquid](#apidoc.module.consolidate.liquid)

#### <a name="apidoc.element.consolidate.liquid.liquid"></a>[function <span class="apidocSignatureSpan">consolidate.</span>liquid (path, options, fn)](#apidoc.element.consolidate.liquid.liquid)
- description and source-code
```javascript
liquid = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.liquid.render"></a>[function <span class="apidocSignatureSpan">consolidate.liquid.</span>render (str, options, fn)](#apidoc.element.consolidate.liquid.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.liquid || (requires.liquid = require('tinyliquid'));
    try {
      var context = engine.newContext();
      var k;

<span class="apidocCodeCommentSpan">      /**
       * Note that there's a bug in the library that doesn't allow us to pass
       * the locals to newContext(), hence looping through the keys:
       */
</span>
      if (options.locals){
        for (k in options.locals){
          context.setLocals(k, options.locals[k]);
        }
        delete options.locals;
      }

      if (options.meta){
        context.setLocals('page', options.meta);
        delete options.meta;
      }

      /**
       * Add any defined filters:
       */

      if (options.filters){
        for (k in options.filters){
          context.setFilter(k, options.filters[k]);
        }
        delete options.filters;
      }

      /**
       * Set up a callback for the include directory:
       */

      var includeDir = options.includeDir || process.cwd();

      context.onInclude(function (name, callback) {
        var extname = path.extname(name) ? '' : '.liquid';
        var filename = path.resolve(includeDir, name + extname);

        fs.readFile(filename, {encoding: 'utf8'}, function (err, data){
          if (err) return callback(err);
          callback(null, engine.parse(data));
        });
      });
      delete options.includeDir;

      /**
       * The custom tag functions need to have their results pushed back
       * through the parser, so set up a shim before calling the provided
       * callback:
       */

      var compileOptions = {
        customTags: {}
      };

      if (options.customTags){
        var tagFunctions = options.customTags;

        for (k in options.customTags){
          /*Tell jshint there's no problem with having this function in the loop */
          /*jshint -W083 */
          compileOptions.customTags[k] = function (context, name, body){
            var tpl = tagFunctions[name](body.trim());
            context.astStack.push(engine.parse(tpl));
          };
          /*jshint +W083 */
        }
        delete options.customTags;
      }

      /**
       * Now anything left in 'options' becomes a local:
       */

      for (k in options){
        context.setLocals(k, options[k]);
      }

      /**
       * Finally, execute the template:
       */

      var tmpl = cache(context) || cache(context, engine.compile(str, compileOptions));
      tmpl(context, fn);
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.liquor"></a>[module consolidate.liquor](#apidoc.module.consolidate.liquor)

#### <a name="apidoc.element.consolidate.liquor.liquor"></a>[function <span class="apidocSignatureSpan">consolidate.</span>liquor (path, options, fn)](#apidoc.element.consolidate.liquor.liquor)
- description and source-code
```javascript
liquor = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.liquor.render"></a>[function <span class="apidocSignatureSpan">consolidate.liquor.</span>render (str, options, fn)](#apidoc.element.consolidate.liquor.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.liquor || (requires.liquor = require('liquor'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.lodash"></a>[module consolidate.lodash](#apidoc.module.consolidate.lodash)

#### <a name="apidoc.element.consolidate.lodash.lodash"></a>[function <span class="apidocSignatureSpan">consolidate.</span>lodash (path, options, fn)](#apidoc.element.consolidate.lodash.lodash)
- description and source-code
```javascript
lodash = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.lodash.render"></a>[function <span class="apidocSignatureSpan">consolidate.lodash.</span>render (str, options, fn)](#apidoc.element.consolidate.lodash.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.lodash || (requires.lodash = require('lodash'));
    try {
      var tmpl = cache(options) || cache(options, engine.template(str, options));
      fn(null, tmpl(options).replace(/\n$/, ''));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.marko"></a>[module consolidate.marko](#apidoc.module.consolidate.marko)

#### <a name="apidoc.element.consolidate.marko.marko"></a>[function <span class="apidocSignatureSpan">consolidate.</span>marko (path, options, fn)](#apidoc.element.consolidate.marko.marko)
- description and source-code
```javascript
marko = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.marko || (requires.marko = require('marko'));
    options.writeToDisk = !!options.cache;

    try {
      var tmpl = cache(options) || cache(options, engine.load(path, options));
      tmpl.render(options, fn)
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.marko.render"></a>[function <span class="apidocSignatureSpan">consolidate.marko.</span>render (str, options, fn)](#apidoc.element.consolidate.marko.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.marko || (requires.marko = require('marko'));
    options.writeToDisk = !!options.cache;

    try {
      var tmpl = cache(options) || cache(options, engine.load('string.marko', str, options));
      tmpl.render(options, fn)
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.mote"></a>[module consolidate.mote](#apidoc.module.consolidate.mote)

#### <a name="apidoc.element.consolidate.mote.mote"></a>[function <span class="apidocSignatureSpan">consolidate.</span>mote (path, options, fn)](#apidoc.element.consolidate.mote.mote)
- description and source-code
```javascript
mote = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.mote.render"></a>[function <span class="apidocSignatureSpan">consolidate.mote.</span>render (str, options, fn)](#apidoc.element.consolidate.mote.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.mote || (requires.mote = require('mote'));
    try {
      var tmpl = cache(options) || cache(options, engine.compile(str));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.mustache"></a>[module consolidate.mustache](#apidoc.module.consolidate.mustache)

#### <a name="apidoc.element.consolidate.mustache.mustache"></a>[function <span class="apidocSignatureSpan">consolidate.</span>mustache (path, options, fn)](#apidoc.element.consolidate.mustache.mustache)
- description and source-code
```javascript
mustache = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.mustache.render"></a>[function <span class="apidocSignatureSpan">consolidate.mustache.</span>render (str, options, fn)](#apidoc.element.consolidate.mustache.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.mustache || (requires.mustache = require('mustache'));
    try {
      fn(null, engine.to_html(str, options, options.partials));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.nunjucks"></a>[module consolidate.nunjucks](#apidoc.module.consolidate.nunjucks)

#### <a name="apidoc.element.consolidate.nunjucks.nunjucks"></a>[function <span class="apidocSignatureSpan">consolidate.</span>nunjucks (path, options, fn)](#apidoc.element.consolidate.nunjucks.nunjucks)
- description and source-code
```javascript
nunjucks = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.nunjucks.render"></a>[function <span class="apidocSignatureSpan">consolidate.nunjucks.</span>render (str, options, fn)](#apidoc.element.consolidate.nunjucks.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {

    try {

      var engine = options.nunjucksEnv || requires.nunjucks || (requires.nunjucks = require('nunjucks'));

      var env = engine;

      // deprecated fallback support for express
      // <https://github.com/tj/consolidate.js/pull/152>
      // <https://github.com/tj/consolidate.js/pull/224>
      if (options.settings && options.settings.views)
        env = engine.configure(options.settings.views);
      else if (options.nunjucks && options.nunjucks.configure)
        env = engine.configure.apply(engine, options.nunjucks.configure);

      //
      // because 'renderString' does not initiate loaders
      // we must manually create a loader for it based off
      // either 'options.settings.views' or 'options.nunjucks' or 'options.nunjucks.root'
      //
      // <https://github.com/mozilla/nunjucks/issues/730>
      // <https://github.com/crocodilejs/node-email-templates/issues/182>
      //

      //
      // note that the below code didn't work nor make sense before
      // because loaders should take different options from rendering
      //

<span class="apidocCodeCommentSpan">      /*
      var loader = options.loader;
      if (loader) {
        var env = new engine.Environment(new loader(options));
        env.renderString(str, options, fn);
      } else {
        engine.renderString(str, options, fn);
      }
      */
</span>
      // so instead we simply check if we passed a custom loader
      // otherwise we create a simple file based loader
      if (options.loader) {
        env = new engine.Environment(options.loader);
      } else if (options.settings && options.settings.views) {
        env = new engine.Environment(
          new engine.FileSystemLoader(options.settings.views)
        );
      } else if (options.nunjucks && options.nunjucks.loader) {
        if (typeof options.nunjucks.loader === 'string')
          env = new engine.Environment(new engine.FileSystemLoader(options.nunjucks.loader));
        else
          env = new engine.Environment(
            new engine.FileSystemLoader(
              options.nunjucks.loader[0],
              options.nunjucks.loader[1]
            )
          );
      }

      env.renderString(str, options, fn);

    } catch (err) {
      throw fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.pug"></a>[module consolidate.pug](#apidoc.module.consolidate.pug)

#### <a name="apidoc.element.consolidate.pug.pug"></a>[function <span class="apidocSignatureSpan">consolidate.</span>pug (path, options, fn)](#apidoc.element.consolidate.pug.pug)
- description and source-code
```javascript
pug = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.pug;
    if (!engine) {
      try {
        engine = requires.pug = require('pug');
      } catch (err) {
        try {
          engine = requires.pug = require('then-pug');
        } catch (otherError) {
          throw err;
        }
      }
    }

    try {
      var tmpl = cache(options) || cache(options, engine.compileFile(path, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.pug.render"></a>[function <span class="apidocSignatureSpan">consolidate.pug.</span>render (str, options, fn)](#apidoc.element.consolidate.pug.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.pug;
    if (!engine) {
      try {
        engine = requires.pug = require('pug');
      } catch (err) {
        try {
          engine = requires.pug = require('then-pug');
        } catch (otherError) {
          throw err;
        }
      }
    }

    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.qejs"></a>[module consolidate.qejs](#apidoc.module.consolidate.qejs)

#### <a name="apidoc.element.consolidate.qejs.qejs"></a>[function <span class="apidocSignatureSpan">consolidate.</span>qejs (path, options, fn)](#apidoc.element.consolidate.qejs.qejs)
- description and source-code
```javascript
qejs = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.qejs.render"></a>[function <span class="apidocSignatureSpan">consolidate.qejs.</span>render (str, options, fn)](#apidoc.element.consolidate.qejs.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    try {
      var engine = requires.qejs || (requires.qejs = require('qejs'));
      engine.render(str, options).then(function (result) {
        fn(null, result);
      }, function (err) {
        fn(err);
      }).done();
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.ractive"></a>[module consolidate.ractive](#apidoc.module.consolidate.ractive)

#### <a name="apidoc.element.consolidate.ractive.ractive"></a>[function <span class="apidocSignatureSpan">consolidate.</span>ractive (path, options, fn)](#apidoc.element.consolidate.ractive.ractive)
- description and source-code
```javascript
ractive = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.ractive.render"></a>[function <span class="apidocSignatureSpan">consolidate.ractive.</span>render (str, options, fn)](#apidoc.element.consolidate.ractive.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.ractive || (requires.ractive = require('ractive'));

    var template = cache(options) || cache(options, engine.parse(str));
    options.template = template;

    if (options.data === null || options.data === undefined)
    {
      var extend = (requires.extend || (requires.extend = require('util')._extend));

      // Shallow clone the options object
      options.data = extend({}, options);

      // Remove consolidate-specific properties from the clone
      var i, length;
      var properties = ["template", "filename", "cache", "partials"];
      for (i = 0, length = properties.length; i < length; i++) {
        var property = properties[i];
        delete options.data[property];
      }
    }

    try {
      fn(null, new engine(options).toHTML());
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.react"></a>[module consolidate.react](#apidoc.module.consolidate.react)

#### <a name="apidoc.element.consolidate.react.react"></a>[function <span class="apidocSignatureSpan">consolidate.</span>react (str, options, fn)](#apidoc.element.consolidate.react.react)
- description and source-code
```javascript
react = function (str, options, fn) {
  return promisify(fn, function(fn) {
    // React Import
    var ReactDOM = requires.ReactDOM || (requires.ReactDOM = require('react-dom/server'));
    var react = requires.react || (requires.react = require('react'));

    // Assign HTML Base
    var base = options.base;
    delete options.base;

    var enableCache = options.cache;
    delete options.cache;

    var isNonStatic = options.isNonStatic;
    delete options.isNonStatic;

    // Start Conversion
    try {

      var Code;
      var Factory;

      var baseStr;
      var content;
      var parsed;

      if (!cache(options)){
        // Parsing
        Code = (type === 'path') ? require(resolve(str)) : requireReactString(str);
        Factory = cache(options, react.createFactory(Code));

      } else {
        Factory = cache(options);
      }

      parsed = new Factory(options);
      content = (isNonStatic) ? ReactDOM.renderToString(parsed) : ReactDOM.renderToStaticMarkup(parsed);

      if (base){
        baseStr = readCache[str] || fs.readFileSync(resolve(base), 'utf8');

        if (enableCache){
          readCache[str] = baseStr;
        }

        options.content = content;
        content = reactBaseTmpl(baseStr, options);
      }

      fn(null, content);

    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.react.render"></a>[function <span class="apidocSignatureSpan">consolidate.react.</span>render (str, options, fn)](#apidoc.element.consolidate.react.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function(fn) {
    // React Import
    var ReactDOM = requires.ReactDOM || (requires.ReactDOM = require('react-dom/server'));
    var react = requires.react || (requires.react = require('react'));

    // Assign HTML Base
    var base = options.base;
    delete options.base;

    var enableCache = options.cache;
    delete options.cache;

    var isNonStatic = options.isNonStatic;
    delete options.isNonStatic;

    // Start Conversion
    try {

      var Code;
      var Factory;

      var baseStr;
      var content;
      var parsed;

      if (!cache(options)){
        // Parsing
        Code = (type === 'path') ? require(resolve(str)) : requireReactString(str);
        Factory = cache(options, react.createFactory(Code));

      } else {
        Factory = cache(options);
      }

      parsed = new Factory(options);
      content = (isNonStatic) ? ReactDOM.renderToString(parsed) : ReactDOM.renderToStaticMarkup(parsed);

      if (base){
        baseStr = readCache[str] || fs.readFileSync(resolve(base), 'utf8');

        if (enableCache){
          readCache[str] = baseStr;
        }

        options.content = content;
        content = reactBaseTmpl(baseStr, options);
      }

      fn(null, content);

    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.slm"></a>[module consolidate.slm](#apidoc.module.consolidate.slm)

#### <a name="apidoc.element.consolidate.slm.slm"></a>[function <span class="apidocSignatureSpan">consolidate.</span>slm (path, options, fn)](#apidoc.element.consolidate.slm.slm)
- description and source-code
```javascript
slm = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.slm.render"></a>[function <span class="apidocSignatureSpan">consolidate.slm.</span>render (str, options, fn)](#apidoc.element.consolidate.slm.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.slm || (requires.slm = require('slm'));

    try {
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.swig"></a>[module consolidate.swig](#apidoc.module.consolidate.swig)

#### <a name="apidoc.element.consolidate.swig.swig"></a>[function <span class="apidocSignatureSpan">consolidate.</span>swig (path, options, fn)](#apidoc.element.consolidate.swig.swig)
- description and source-code
```javascript
swig = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
...

All templates supported by this library may be rendered using the signature '(path[, locals], callback)' as shown below, which happens
 to be the signature that Express 3.x supports so any of these engines may be used within Express.

__NOTE__: All this example code uses cons.swig for the swig template engine. Replace swig with whatever templating you are using
. For example, use cons.hogan for hogan.js, cons.jade for jade, etc. 'console.log(cons)' for the full list of identifiers.

'''js
var cons = require('consolidate');
cons.swig('views/page.html', { user: 'tobi' }, function(err, html){
if (err) throw err;
console.log(html);
});
'''

Or without options / local variables:
...
```

#### <a name="apidoc.element.consolidate.swig.render"></a>[function <span class="apidocSignatureSpan">consolidate.swig.</span>render (str, options, fn)](#apidoc.element.consolidate.swig.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.swig || (requires.swig = require('swig'));

    try {
      if(options.cache === true) options.cache = 'memory';
      engine.setDefaults({ cache: options.cache });
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.templayed"></a>[module consolidate.templayed](#apidoc.module.consolidate.templayed)

#### <a name="apidoc.element.consolidate.templayed.templayed"></a>[function <span class="apidocSignatureSpan">consolidate.</span>templayed (path, options, fn)](#apidoc.element.consolidate.templayed.templayed)
- description and source-code
```javascript
templayed = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.templayed.render"></a>[function <span class="apidocSignatureSpan">consolidate.templayed.</span>render (str, options, fn)](#apidoc.element.consolidate.templayed.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.templayed || (requires.templayed = require('templayed'));
    try {
      var tmpl = cache(options) || cache(options, engine(str));
      fn(null, tmpl(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.toffee"></a>[module consolidate.toffee](#apidoc.module.consolidate.toffee)

#### <a name="apidoc.element.consolidate.toffee.toffee"></a>[function <span class="apidocSignatureSpan">consolidate.</span>toffee (path, options, fn)](#apidoc.element.consolidate.toffee.toffee)
- description and source-code
```javascript
toffee = function (path, options, fn){
  return promisify(fn, function (fn) {
    var toffee = requires.toffee || (requires.toffee = require('toffee'));
    toffee.__consolidate_engine_render(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.toffee.render"></a>[function <span class="apidocSignatureSpan">consolidate.toffee.</span>render (str, options, fn)](#apidoc.element.consolidate.toffee.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.toffee || (requires.toffee = require('toffee'));
    try {
      engine.str_render(str, options,fn);
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.twig"></a>[module consolidate.twig](#apidoc.module.consolidate.twig)

#### <a name="apidoc.element.consolidate.twig.twig"></a>[function <span class="apidocSignatureSpan">consolidate.</span>twig (path, options, fn)](#apidoc.element.consolidate.twig.twig)
- description and source-code
```javascript
twig = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.twig.render"></a>[function <span class="apidocSignatureSpan">consolidate.twig.</span>render (str, options, fn)](#apidoc.element.consolidate.twig.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.twig || (requires.twig = require('twig').twig);
    var templateData = {
      data: str
    };
    try {
      var tmpl = cache(templateData) || cache(templateData, engine(templateData));
      fn(null, tmpl.render(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.underscore"></a>[module consolidate.underscore](#apidoc.module.consolidate.underscore)

#### <a name="apidoc.element.consolidate.underscore.underscore"></a>[function <span class="apidocSignatureSpan">consolidate.</span>underscore (path, options, fn)](#apidoc.element.consolidate.underscore.underscore)
- description and source-code
```javascript
underscore = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.underscore.render"></a>[function <span class="apidocSignatureSpan">consolidate.underscore.</span>render (str, options, fn)](#apidoc.element.consolidate.underscore.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function(fn) {
    var engine = requires.underscore || (requires.underscore = require('underscore'));
    try {
      var tmpl = cache(options) || cache(options, engine.template(str, null, options));
      fn(null, tmpl(options).replace(/\n$/, ''));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.vash"></a>[module consolidate.vash](#apidoc.module.consolidate.vash)

#### <a name="apidoc.element.consolidate.vash.vash"></a>[function <span class="apidocSignatureSpan">consolidate.</span>vash (path, options, fn)](#apidoc.element.consolidate.vash.vash)
- description and source-code
```javascript
vash = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.vash.render"></a>[function <span class="apidocSignatureSpan">consolidate.vash.</span>render (str, options, fn)](#apidoc.element.consolidate.vash.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function(fn) {
    var engine = requires.vash || (requires.vash = require('vash'));

    try {
      // helper system : https://github.com/kirbysayshi/vash#helper-system
      if (options.helpers) {
        for (var key in options.helpers) {
          if (!options.helpers.hasOwnProperty(key) || typeof options.helpers[key] !== 'function') {
            continue;
          }
          engine.helpers[key] = options.helpers[key];
        }
      }
      var tmpl = cache(options) || cache(options, engine.compile(str, options));
      fn(null, tmpl(options).replace(/\n$/, ''));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.walrus"></a>[module consolidate.walrus](#apidoc.module.consolidate.walrus)

#### <a name="apidoc.element.consolidate.walrus.walrus"></a>[function <span class="apidocSignatureSpan">consolidate.</span>walrus (path, options, fn)](#apidoc.element.consolidate.walrus.walrus)
- description and source-code
```javascript
walrus = function (path, options, fn){
  options.filename = path;

  return promisify(fn, function(fn) {
    readPartials(path, options, function (err) {
      if (err) return fn(err);
      if (cache(options)) {
        exports[name].render('', options, fn);
      } else {
        read(path, options, function(err, str){
          if (err) return fn(err);
          exports[name].render(str, options, fn);
        });
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.walrus.render"></a>[function <span class="apidocSignatureSpan">consolidate.walrus.</span>render (str, options, fn)](#apidoc.element.consolidate.walrus.render)
- description and source-code
```javascript
render = function (str, options, fn) {
  return promisify(fn, function (fn) {
    var engine = requires.walrus || (requires.walrus = require('walrus'));
    try {
      var tmpl = cache(options) || cache(options, engine.parse(str));
      fn(null, tmpl.compile(options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# <a name="apidoc.module.consolidate.whiskers"></a>[module consolidate.whiskers](#apidoc.module.consolidate.whiskers)

#### <a name="apidoc.element.consolidate.whiskers.whiskers"></a>[function <span class="apidocSignatureSpan">consolidate.</span>whiskers (path, options, fn)](#apidoc.element.consolidate.whiskers.whiskers)
- description and source-code
```javascript
whiskers = function (path, options, fn){
  return promisify(fn, function (fn) {
    var engine = requires.whiskers || (requires.whiskers = require('whiskers'));
    engine.__express(path, options, fn);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.consolidate.whiskers.render"></a>[function <span class="apidocSignatureSpan">consolidate.whiskers.</span>render (str, options, fn)](#apidoc.element.consolidate.whiskers.render)
- description and source-code
```javascript
render = function (str, options, fn){
  return promisify(fn, function(fn) {
    var engine = requires.whiskers || (requires.whiskers = require('whiskers'));
    try {
      fn(null, engine.render(str, options));
    } catch (err) {
      fn(err);
    }
  });
}
```
- example usage
```shell
...

var users = [];
users.push({ name: 'tobi' });
users.push({ name: 'loki' });
users.push({ name: 'jane' });

app.get('/', function(req, res){
res.render('index', {
  title: 'Consolidate.js'
});
});

app.get('/users', function(req, res){
res.render('users', {
  title: 'Users',
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
