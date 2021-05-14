# VS. CODESTUDIO

- [VS. CODESTUDIO](#vs-codestudio)
  - [Introduction](#introduction)
  - [Install/Usage](#installusage)
  - [Recommending extensions in your project](#recommending-extensions-in-your-project)
    - [Custom components](#custom-components)
      - [VUE.JS recommendations](#vuejs-recommendations)
    - [Development](#development)
    - [Contributing](#contributing)
    - [Changelog](#changelog)
    - [Issues](#issues)
    - [License](#license)

## Introduction

I created this extension two reasons, the first to teach myself how to, the second to scratch an itch that I had to figure out the quickest to get VSCODE from install to work ready, I managed to do both, YAY me :)!

> **Performance note**. I have been able to comfortably run (39+) extensions on a `surfacebook pro i5 8gb of ram 256gb hd` , lets say I like pushing it. If you are multitasking or run a lot of memory hungry apps (Chrome...), I would recommend that you go with something a bit more powerful.

## Install/Usage

* **VSCode market place** <https://marketplace.visualstudio.com/items?itemName=shawnsandy.codestudio>
* Or go to your extensions panel `View > Extensions` and type `codestudio` in search box to find the extension than click install.
* The [VSCode ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) extension requires the latest version of, If you haven't installed ESLint either locally or globally do so by running `npm install eslint` in the workspace folder for a local install or `npm install -g eslint` for a global install.

**Tip**

You can optimize VSC performance by tweaking some of VSC settings, here's an example one of my custom project settings `./vscode/settings.json` .

``` json
{
  "files.associations": {
    "*.tag": "html",
    "*.cshtml": "html",
    "*.html": "html",
    "*.njk": "html",
    "*.mustache": "html",
    "*.html.md": "html"
  },
  "files.exclude": {
    "**/.git": true,
    "**/.DS_Store": true,
    "**/.vscode": true,
    "**/__pycache__": true,
    "**/.pytest_cache": true,
    "**/node_modules": true,
    "node_modules": true,
    "venv": true,
    "*.sublime-*": true,
    "env*": true
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/env": true,
    "**/venv": true
  },
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/**": true,
    "**/env/**": true,
    "**/venv/**": true,
    "env-*": true
  },
  "files.autoSave": "onFocusChange",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "editor.cursorBlinking": "phase",
  "window.title": "${dirty} ${activeEditorMedium}${separator}${rootName}",
  "editor.formatOnSave": true,
  "breadcrumbs.enabled": true,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.maxColumn": 200,
  "editor.minimap.showSlider": "always"
}
```

---

## Recommending extensions in your project

You can add recommend extensions to team members, users or contributors by adding the `extensions.json` to your project folder `./vscode` directory.

* Create and `extensions.json` file in `.vscode/` folder in you project
* Copy and paste the code below into the file
* Share the repo with others and they will be promoted to install your recommend extensions on first load.

### Custom components

``` json

{
  "recommendations": [
     "shawnsandy.codestudio",
    "dbaeumer.vscode-eslint",
    "mkaufman.HTMLHint",
    "humao.rest-client",
    "dsznajder.es7-react-js-snippets",
    "eseom.nunjucks-template",
    "douglaszaltron.nunjucks-vscode-extensionpack",
    "msjsdiag.debugger-for-chrome",
    "sdras.vue-vscode-extensionpack",
    "octref.vetur",
    "hollowtree.vue-snippets",
    "sdras.vue-vscode-snippets"
  ]
}

```

#### VUE.JS recommendations

``` json
{
  "recommendations": [
    "sdras.vue-vscode-extensionpack",
    "octref.vetur",
    "hollowtree.vue-snippets",
    "sdras.vue-vscode-snippets"
  ]
}

```

### Development

* Clone this repo
* Install Microsoft VSCE `npm install -g vsce` [extension manager](https://www.npmjs.com/package/vsce)
* Install Auto Changelog `npm install -g auto-changelog` [Auto Changelog](https://www.npmjs.com/package/auto-changelog)
* Install np `npm install --global np` [np](https://www.npmjs.com/package/np)
* Add/Remove extensions in the `extensionPack` section of the package.json
* Build extension `npm run build`
* `npm run changelog` to generate

### Contributing

If you would like to contribute to this extension

* Clone the repo `git clone https://github.com/shawn-sandy/codestudio`
* Add an extension to the `package.json` fix a bug/typo etc
* Submit a Pull request
* Approval subject to review

### Changelog

Latest change and updates read the [Changelog](./CHANGELOG.md)

### Issues

I you find any errors, bugs, typos, would like to recommend an extension, etc. Please open an issue here <https://github.com/shawn-sandy/codestudio/issues>

### License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**Enjoy!**
