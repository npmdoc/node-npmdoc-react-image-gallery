# api documentation for  [react-image-gallery (v0.7.15)](https://github.com/xiaolin/react-image-gallery)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-image-gallery.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-image-gallery) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-image-gallery.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-image-gallery)
#### Responsive and flexible carousel component with thumbnail support

[![NPM](https://nodei.co/npm/react-image-gallery.png?downloads=true)](https://www.npmjs.com/package/react-image-gallery)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-image-gallery/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-image-gallery_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-image-gallery/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-image-gallery/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-image-gallery/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Xiao Lin"
    },
    "bugs": {
        "url": "https://github.com/xiaolin/react-image-gallery/issues"
    },
    "dependencies": {
        "lodash.debounce": "^4.0.8",
        "lodash.throttle": "^4.1.1",
        "react-swipeable": "^3.5.1"
    },
    "description": "Responsive and flexible carousel component with thumbnail support",
    "devDependencies": {
        "babel-eslint": "^6.0.4",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.16.0",
        "babelify": "^7.3.0",
        "browserify": "^13.1.1",
        "eslint": "^2.10.2",
        "eslint-plugin-react": "^5.1.1",
        "gulp": "^3.8.11",
        "gulp-babel": "^6.1.2",
        "gulp-clean-css": "^2.3.1",
        "gulp-concat": "^2.6.0",
        "gulp-connect": "^3.2.2",
        "gulp-livereload": "^3.8.0",
        "gulp-rename": "^1.2.0",
        "gulp-sass": "^2.3.2",
        "gulp-uglify": "^1.5.3",
        "react": "^15.3.0",
        "react-dom": "^15.2.1",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0",
        "watchify": "^3.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8930b0b5d5c04b22dd69434d5497889fd7e9d5dc",
        "tarball": "https://registry.npmjs.org/react-image-gallery/-/react-image-gallery-0.7.15.tgz"
    },
    "email": "xiao@linxtion.com",
    "gitHead": "3871fdf1e74b0d6d2908f3c5fdc2afaf52e8f4ba",
    "homepage": "https://github.com/xiaolin/react-image-gallery",
    "keywords": [
        "react",
        "carousel",
        "react-component",
        "react-carousel",
        "react-slideshow",
        "react-gallery",
        "react carousel",
        "react slideshow",
        "react gallery",
        "image gallery",
        "image slider",
        "slideshow",
        "gallery",
        "slider"
    ],
    "license": "MIT",
    "main": "./build/image-gallery",
    "maintainers": [
        {
            "name": "linxtion",
            "email": "xiao@linxtion.com"
        }
    ],
    "name": "react-image-gallery",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/xiaolin/react-image-gallery.git"
    },
    "scripts": {
        "build": "gulp build",
        "lint": "eslint --ext .js,.jsx src",
        "start": "gulp dev"
    },
    "version": "0.7.15"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-image-gallery](#apidoc.module.react-image-gallery)
1.  [function <span class="apidocSignatureSpan">react-image-gallery.</span>default (props)](#apidoc.element.react-image-gallery.default)



# <a name="apidoc.module.react-image-gallery"></a>[module react-image-gallery](#apidoc.module.react-image-gallery)

#### <a name="apidoc.element.react-image-gallery.default"></a>[function <span class="apidocSignatureSpan">react-image-gallery.</span>default (props)](#apidoc.element.react-image-gallery.default)
- description and source-code
```javascript
function ImageGallery(props) {
  _classCallCheck(this, ImageGallery);

  var _this = _possibleConstructorReturn(this, Object.getPrototypeOf(ImageGallery).call(this, props));

  _this.state = {
    currentIndex: props.startIndex,
    thumbsTranslate: 0,
    offsetPercentage: 0,
    galleryWidth: 0,
    thumbnailsWrapperWidth: 0,
    thumbnailsWrapperHeight: 0,
    isFullscreen: false,
    isPlaying: false
  };

  if (props.lazyLoad) {
    _this._lazyLoaded = [];
  }
  return _this;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
