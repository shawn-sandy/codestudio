# CODESTUDIO

**A VSCODE extension-pack for UI/UX Frontend development**. I have been able to comfortably run (39+) extensions on a `surfacebook pro i5 8gb of ram 256gb hd` , lets say I like pushing it. If you are multitasking or run a lot of memory hungry apps (Chrome...), I would recommend that you go with something a bit more powerful.

### Install/Usage

- **VSCode market place** https://marketplace.visualstudio.com/items?itemName=shawnsandy.codestudio
- Or go to your extensions panel `View > Extensions` and type `codestudio` in search box to find the extension than click install.

**Tip**

You can optimize VSC performance by tweaking some of VSC settings, here's an example one of my custom project settings `./vscode/settings.json` .

```json
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

## Extensions Included

**GitLens — Git supercharged**

Supercharge the Git capabilities built into Visual Studio Code — Visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more
https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens

---

**ESLint**

Integrates ESLint JavaScript into VS Code.
https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint

---

**Debugger for Chrome**

Debug your JavaScript code in the Chrome browser, or any other target that supports the Chrome Debugger protocol.
https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome

---

**Vetur**

Vue tooling for VS Code
https://marketplace.visualstudio.com/items?itemName=octref.vetur

---

**Beautify**
Beautify code in place for VS Code
https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify

---

**Prettier - Code formatter**
VS Code plugin for prettier/prettier
https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

---

**Visual Studio IntelliCode**
AI-assisted development
https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode

---

**Bracket Pair Colorizer**
Id:

A customizable extension for colorizing matching brackets
https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer

---

**Markdown All in One**

All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one

---

**Code Spell Checker**

Spelling checker for source code
https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker

---

**HTML Snippets**

Full HTML tags including HTML5 Snippets
https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets

---

**Azure Account**

A common Sign-In and Subscription management extension for VS Code.
https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account

---

**HTML CSS Support**

CSS support for HTML documents
https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css

---

**Auto Rename Tag**

Auto rename paired HTML/XML tag
https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag

---

**Markdown Preview Enhanced**

Markdown Preview Enhanced ported to vscode
https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced

---

**Vue 2 Snippets**

A Vue.js 2 Extension
https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets

---

**Better Comments**

Improve your code commenting by annotating with alert, informational, TODOs, and more!
https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments

---

**CSS Peek**

Allow peeking to css ID and class strings as definitions from html files to respective CSS. Allows peek and goto definition.
https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek

---

**Vue VSCode Snippets**

Snippets that will supercharge your Vue workflow
https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets

---

**GitHub Pull Requests**

Pull Request Provider for GitHub
https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github

---

**indent-rainbow**

Makes indentation easier to read
https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow

---

**Babel JavaScript**

VSCode syntax highlighting for today's JavaScript, ported from gandm's language-babel for Atom.
https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel

---

**Node.js Modules Intellisense**

Autocompletes Node.js modules in import statements
https://marketplace.visualstudio.com/items?itemName=leizongmin.node-module-intellisense

---

**Vue VSCode Snippets**

Description: Snippets that will supercharge your Vue workflow
https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets

---

**Night Owl**

Description: A VS Code theme for the night owls out there. Now introducing Light Owl theme for daytime usage. Decisions were based on meaningful contrast for reading comprehension and for optimal razzle dazzle. ✨
https://marketplace.visualstudio.com/items?itemName=sdras.night-owl

---

**Color Highlight**

Description: Highlight web colors in your editor
https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight

---

**Sort lines**

Description: Sorts lines of text
https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines

---

**Highlight Matching Tag**

Description: Highlights matching closing or opening tag
https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag

---

**markdown-formatter**

Description: A Markdown Plugin for code artist
https://marketplace.visualstudio.com/items?itemName=mervin.markdown-formatter

---

### Development

- Clone this repo
- Install Microsoft VSCE `npm install -g vsce` [exension manager](https://www.npmjs.com/package/vsce)
- Install Auto Changelog `npm install -g auto-changelog` [Auto Changelog](https://www.npmjs.com/package/auto-changelog)
- Install np `npm install --global np` [np](https://www.npmjs.com/package/np)
- Add/Remove extensions in the `extensionPack` section of the package.json
- Build extension `npm run build`
- `npm run changelog` to generate changelogs

### Contributing

If you would like to contribute to this extension

- Clone the repo `git clone https://github.com/shawn-sandy/codestudio`
- Add an extension to the `package.json` fix a bug/typo etc
- Submit a Pull request
- Approval subject to review

### Issues

I you find any errors, bugs, typos, would like to recommend an extension, etc. Please open an issue here https://github.com/shawn-sandy/codestudio/issues

### License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**Enjoy!**
