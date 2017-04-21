# npmdoc-web-audio-analyser

#### api documentation for  web-audio-analyser (v2.0.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-web-audio-analyser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-web-audio-analyser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-web-audio-analyser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-web-audio-analyser)

#### A thin wrapper around the Web Audio API that lets you take some audio and get its waveform/frequency data in return.

[![NPM](https://nodei.co/npm/web-audio-analyser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web-audio-analyser)

- [https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "web-audio-analyser",
    "version": "2.0.1",
    "description": "A thin wrapper around the Web Audio API that lets you take some audio and get its waveform/frequency data in return.",
    "main": "index.js",
    "scripts": {
        "test": "npm start",
        "start": "beefy demo.js:bundle.js --live -- -t brfs",
        "prepublish": "browserify -t brfs demo.js > bundle.js"
    },
    "author": "Hugh Kennedy <hughskennedy@gmail.com> (http://hughskennedy.com/)",
    "license": "MIT",
    "devDependencies": {
        "beefy": "^2.1.5",
        "brfs": "~0.0.8",
        "game-shell-orbit-camera": "0.0.0",
        "gl-buffer": "~0.1.1",
        "gl-matrix": "~2.0.0",
        "gl-now": "0.0.4",
        "gl-shader": "0.0.6",
        "gl-vao": "0.0.2",
        "soundcloud-badge": "0.0.0"
    },
    "dependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/web-audio-analyser.git"
    },
    "keywords": [
        "audio",
        "web",
        "api",
        "browserify",
        "analysis",
        "fft",
        "waveform",
        "reactive"
    ],
    "bugs": {
        "url": "https://github.com/hughsk/web-audio-analyser/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
