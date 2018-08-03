<div align="center">

# My Development Setup

My personal development setup, for Frontend Development on Windows.

</div>

<br><br>

## Table of Contents

- **[Visual Studio Code](#visual-studio-code)**<br>Theme, Extensions, Settings, Keybinding
- **[Google Chrome](#google-chrome)**<br>Extensions
- **[Git](#git)**<br>Settings, Commit Signing
- **[NodeJS](#nodejs)**<br>Global Packages
- **[ConEmu](#conemu)**<br>TODO

<br><br><br>

## [Visual Studio Code](https://code.visualstudio.com/)

Lightweigh Code Editor, focused on web development. Usually I prefer the Insiders Build.

<br>

### Theme

My favourite theme is **[Oceanic Next](https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext)**!

<br>

### Extensions

The following are my extensions, the "must haves" are marked by a heart:

|         | Extension                                                                                                                           | Description          |
| :-----: | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| :heart: | **[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)**                             | Add autocomplete to Angular templates |
| :heart: | **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                            | Automatically renames paired HTML tags |
| :heart: | **[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)**                               | Colorizes comments based on type |
| :heart: | **[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)**                  | Colorizes matching brackets |
|         | **[CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics)**                             | Shows code complexity |
| :heart: | **[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)**                         | Debug Chrome within Visual Studio Code |
| :heart: | **[Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)**                                            | Generate JSDoc comments |
| :heart: | **[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)**                                   | Apply settings defined in .editconfig file |
|         | **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**                                                  | Enhanced Git support |
| :heart: | **[Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)**                                                   | Adds indentation guide lines |
|         | **[Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)**                        | Adds image preview next to lines |
|         | **[JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts)**                                | Creates TypeScript interfaces from JSON |
| :heart: | **[JSON5 syntax](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-json5)**                                         | Adds JSON5 file support |
| :heart: | **[Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)**   | Markdown Preview Github Theme |
|         | **[Markdown Preview with BitBucket Styling](https://marketplace.visualstudio.com/items?itemName=hbrok.markdown-preview-bitbucket)** | Markdown Preview Github Theme |
| :heart: | **[Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)**                                   | Open HTML in browser (default vs. select) |
|         | **[Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)**                                         | Compare things |
|         | **[Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)**                                                    | Captures beautiful code screenshots |
| :heart: | **[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)**                              | Manages multiple projects |
| :heart: | **[Sass](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented)**                                          | SASS file support |
| :heart: | **[Sass Lint](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint)**                                              | SASS file linter |
| :heart: | **[Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)**                                             | Quickly sort lines |
| :heart: | **[SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)**                                        | SVG file support |
| :heart: | **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**                               | Highlight TODOs, FIXMEs and similar |
| :heart: | **[TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-treet)**                                         | Adds a TODO panel listing all TODO comments |
| :heart: | **[Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)**                               | Highlight and remove trailing spaces |
| :heart: | **[TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)**                                                        | TS file linter |
| :heart: | **[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**                                | Show dependency version infos in package.json |

<br>

### Settings

The following are my user settings, ordered by default - then language-related - then extensions:

``` javascript
{

    // Window
    "window.menuBarVisibility": "toggle",
    "window.newWindowDimensions": "maximized",

    // Editor
    "editor.detectIndentation": false,
    "editor.fontSize": 13,
    "editor.lineHeight": 19,
    "editor.formatOnSave": false,
    "editor.rulers": [
        140
    ],
    "editor.roundedSelection": false,
    "editor.renderIndentGuides": false,
    "editor.tabSize": 2,
    "editor.minimap.enabled": true,
    "editor.wordWrap": "on",

    // Explorer
    "explorer.openEditors.visible": 0,
    "explorer.confirmDragAndDrop": false,

    // Workbench
    "workbench.colorTheme": "Oceanic Next (dimmed bg)",
    "workbench.iconTheme": "vs-seti",
    "workbench.statusBar.feedback.visible": false,

    // Terminal
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
    "terminal.integrated.scrollback": 100000,
    "terminal.integrated.cursorBlinking": true,

    // Insert new line
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,

    // HTML
    "html.format.indentInnerHtml": true,
    "html.format.endWithNewline": true,
    "html.format.wrapLineLength": 140,

    // TypeScript
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
    "typescript.format.insertSpaceAfterTypeAssertion": true,
    "typescript.preferences.quoteStyle": "single",
    "typescript.preferences.importModuleSpecifier": "relative",

    // JavaScript
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "javascript.preferences.quoteStyle": "single",
    "javascript.preferences.importModuleSpecifier": "relative",

    // TSlint
    "tslint.autoFixOnSave": true,
    "tslint.alwaysShowStatus": true,
    "tslint.jsEnable": true,

    // TODO highlight
    "todohighlight.isCaseSensitive": false,

    // TODO tree
    "todo-tree.expanded": true,
    "todo-tree.flat": true,

    // Document This
    "docthis.includeMemberOfOnClassMembers": false,
    "docthis.includeMemberOfOnInterfaceMembers": false,
    "docthis.includeTypes": false,

    // Git Lens
    "gitlens.keymap": "alternate",
    "gitlens.advanced.messages": {
      "suppressCommitHasNoPreviousCommitWarning": false,
      "suppressCommitNotFoundWarning": false,
      "suppressFileNotUnderSourceControlWarning": false,
      "suppressGitVersionWarning": false,
      "suppressLineUncommittedWarning": false,
      "suppressNoRepositoryWarning": false,
      "suppressResultsExplorerNotice": false,
      "suppressShowKeyBindingsNotice": true
    },
    "gitlens.historyExplorer.enabled": true

}
```

<br>

### Keybindings

The following are my user keybindings:

``` javascript
[
    {
        "key": "ctrl+shift+space",
        "command": "editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+alt+f4",
        "command": "workbench.action.reloadWindow"
    }
]
```

<br><br><br>

## [Google Chrome](https://www.google.de/chrome/index.html)

Primary browser for development purposes.

<br>

### Extensions

The following are my extensions, the "must haves" are marked by a heart:

|         | Extension                                                                                                                         | Description          |
| :-----: | --------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
|         | **[Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd)**                                                                                       | Adds tools for debugging and profiling Angular applications |
|         | **[Awesome Autocomplete for GitHub](https://chrome.google.com/webstore/detail/awesome-autocomplete-for/djkfdjpoelphhdclfjhnffmnlnoknfnd?utm_source=chrome-app-launcher-info-dialog)** | Enhances the GitHub search autocomplete |
|         | **[aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)**                                                                                             | Adds tools for accessibility testing |
|         | **[Baseliner](https://chrome.google.com/webstore/detail/baseliner/agoopbiflnjadjfbhimhlmcbgmdgldld)**                                                                                 | Show lines for vertical rhythm |
|         | **[ChromeLens](https://chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd/related)**                                                                       | Simulates visual impairments |
| :heart: | **[ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?utm_source=chrome-app-launcher-info-dialog)**                                    | Color Picker |
|         | **[Contributors on GitHub](https://chrome.google.com/webstore/detail/contributors-on-github/cjbacdldhllelehomkmlniifaojgaeph?utm_source=chrome-app-launcher-info-dialog)**            | Shows contribution details on GitHub PRs |
|         | **[Dimensions](https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj?utm_source=chrome-app-launcher-info-dialog)**                                    | Measure dimensions of elements on hover |
|         | **[Fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?utm_source=chrome-app-launcher-info-dialog)**                        | Makes full-sized screenshots |
| :heart: | **[Mindful](https://chrome.google.com/webstore/detail/mindful-beta/cieekmjjdkckhpidgaffphlaljdfhhab?utm_source=chrome-app-launcher-info-dialog)**                                     | Shows a beautiful notepad as the new tab page |
|         | **[JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?utm_source=chrome-app-launcher-info-dialog)**                            | Formats JSON files opened in the browser |
|         | **[Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh?utm_source=chrome-app-launcher-info-dialog)**                           | Shows elements outlines |
|         | **[GitHub Hovercard](https://chrome.google.com/webstore/detail/github-hovercard/mmoahbbnojgkclgceahhakhnccimnplk?utm_source=chrome-app-launcher-info-dialog)**                        | Shows link information on hover |
|         | **[GitHub Repository Size](https://chrome.google.com/webstore/detail/github-repository-size/apnjnioapinblneaedefcnopcjepgkci)**                                                       | Shows file sizes in repository view |
|         | **[GitHub Markdown Menu](https://chrome.google.com/webstore/detail/github-markdown-menu/jekgocfoijmbgcjejohdgmojaejofdpo)**                                                           | Shows a markdown table of contents as a dropdown menu |
|         | **[Tab Size on GitHub](https://chrome.google.com/webstore/detail/tab-size-on-github/ofjbgncegkdemndciafljngjbdpfmbkn?utm_source=chrome-app-launcher-info-dialog)**                    | Decreases GitHub indentation wideness |
| :heart: | **[Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg?utm_source=chrome-app-launcher-info-dialog)**                                    | Detects technologies used by a website |
|         | **[WAVE Evaluation Tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)**                                                           | Adds tools for accessibility testing |
| :heart: | **[Web Developer](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm?utm_source=chrome-app-launcher-info-dialog)**                              | Toolbar with various development helpers |
|         | **[WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?utm_source=chrome-app-launcher-info-dialog)**                                        | Shows used font family on hover |

<br><br><br>

## [Git](https://git-scm.com/)

Version Control Software, accessibly via command line.

<br>

### Settings

``` conf
user.name=<NAME>
user.email=<EMAIL>
push.default=simple # Simplify pushing to remote
push.followtags=true # Always push tags along
status.showUntrackedFiles=all # Show all files when changing directories
credential.helper=wincred # Remember credentials
```

> Also read **[Better Git configuration](https://blog.scottnonnenberg.com/better-git-configuration/)**.

<br>

### Alias

Git aliases, for common actions:

#### Set upstream of current banch

``` conf
alias.set-upstream=!git branch --set-upstream-to=origin/`git symbolic-ref --short HEAD`
```

#### Revert last commit (keeps the changes)

``` conf
alias.pop=!git reset HEAD^
```

#### Clone without SSL certification verification

``` conf
alias.clone-unsecure=!git -c http.sslVerify=false clone
```

<br>

### Commit Signing with GPG

When working on GitHub, I usually set up **[Commit Signing via GPG](https://help.github.com/articles/signing-commits-with-gpg/)**. The
following coniguration is needed:

``` conf
user.signingkey=<KEY>
commit.gpgsign=true
gpg.program=C:/Program Files (x86)/GNU/GnuPG/gpg2.exe
```

<br><br><br>

## [NodeJS](https://nodejs.org/)

If possible, installed via **[nvm for Windows](https://github.com/coreybutler/nvm-windows)**.

<br>

### Global packages

Useful global packages:

- [`ts-node`](https://github.com/TypeStrong/ts-node) quickly compiles and runs TypeScript files

<br><br><br>

## ConEmu

TODO: Download link, Theme, Settings, PoshGit

<br><br><br>

## Creator

**Dominique Müller**

- E-Mail: **[dominique.m.mueller@gmail.com](mailto:dominique.m.mueller@gmail.com)**
- Website: **[www.devdom.io](https://www.devdom.io/)**
- Twitter: **[@itsdevdom](https://twitter.com/itsdevdom)**
