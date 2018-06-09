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

Lightweigh Code Editor, focused on Web Development. Usually I prefer the Insiders Build.

> Theme: **[Oceanic Next](https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext)**

<br>

### Extensions

The following are my extensions, the "must haves" are marked by a plus sign:

|       | Extension                                                                                                                         | Description          |
| :---: | --------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **+** | **[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)**                           | Extended autocomplete & info for Angular |
| **+** | **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                          | Automatically renames paired HTML tags |
| **+** | **[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)**                             | Colorizes comments based on type |
| **+** | **[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)**                | Colorizes matching brackets |
|       | **[Code Oultine](https://marketplace.visualstudio.com/items?itemName=patrys.vscode-code-outline)**                                | Shows code outline tree in explorer pane |
| **+** | **[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)**                       | Debug Chrome within Visual Studio Code |
| **+** | **[Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)**                                          | Generate JSDoc comments |
| **+** | **[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)**                                 | Apply settings defined in .editconfig file |
|       | **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**                                                | Enhanced Git support |
| **+** | **[Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)**                                                 | Adds indentation guide lines |
| **+** | **[JSON5 syntax](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-json5)**                                       | Adds JSON5 file support |
| **+** | **[Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)** | Markdown Preview Github Theme |
|       | **[Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)**                                                  | Captures beautiful code screenshots |
| **+** | **[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)**                            | Manages multiple projects |
| **+** | **[Sass](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented)**                                        | SASS file support |
| **+** | **[Sass Lint](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint)**                                            | SASS file linter |
| **+** | **[Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)**                                           | Quickly sort lines |
| **+** | **[SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)**                                      | SVG file support |
| **+** | **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**                             | Highlight TODOs, FIXMEs and similar |
|       | **[TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-treet)**                                       | Adds a TODO panel listing all TODO comments |
| **+** | **[Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)**                             | Highlight and remove trailing spaces |
| **+** | **[TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)**                                                      | TS file linter |
| **+** | **[Typescript Deporter](https://marketplace.visualstudio.com/items?itemName=Acr0most.ts-deporter)**                               | Remove ununsed TypeScript imports |
| **+** | **[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**                              | Show dependency version infos in package.json |
| **+** | **[View In Browser](https://marketplace.visualstudio.com/items?itemName=qinjia.view-in-browser)**                                 | Directly open file in browser |

<br>

### Settings

The following are my user settings, grouped by default - language - extensions:

``` json
{
    "editor.fontSize": 13,
    "editor.lineHeight": 20,
    "editor.minimap.maxColumn": 140,
    "editor.renderIndentGuides": false,
    "editor.roundedSelection": false,
    "editor.rulers": [
        140
    ],
    "files.trimTrailingWhitespace": true,
    "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
    "terminal.integrated.scrollback": 100000,
    "window.menuBarVisibility": "toggle",
    "workbench.colorTheme": "Oceanic Next (dimmed bg)",

    "html.format.indentInnerHtml": true,
    "html.format.wrapLineLength": 140,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,

    "docthis.includeMemberOfOnClassMembers": false,
    "docthis.includeMemberOfOnInterfaceMembers": false,
    "docthis.includeTypes": false
}
```

<br>

### Keybindings

The following are my user keybindings:

``` json
[
    {
        "key": "ctrl+shift+space",
        "command": "editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    }
]
```

<br><br><br>

## [Google Chrome](https://www.google.de/chrome/index.html)

Primary browser for development purposes.

<br>

### Extensions

The following are my extensions, the "must haves" are marked by a plus sign:

|       | Extension                                                                                                                         | Description          |
| :---: | --------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
|       | **[Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd)** | Adds tools for debugging and profiling Angular applications |
|       | **[Awesome Autocomplete for GitHub](https://chrome.google.com/webstore/detail/awesome-autocomplete-for/djkfdjpoelphhdclfjhnffmnlnoknfnd?utm_source=chrome-app-launcher-info-dialog)** | Enhances the GitHub search autocomplete |
|       | **[aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)** | Adds tools for accessibility testing |
|       | **[Baseliner](https://chrome.google.com/webstore/detail/baseliner/agoopbiflnjadjfbhimhlmcbgmdgldld)** | Show lines for vertical rhythm |
|       | **[ChromeLens](https://chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd/related)** | Simulates visual impairments |
| **+** | **[ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?utm_source=chrome-app-launcher-info-dialog)** | Color Picker |
|       | **[Contributors on GitHub](https://chrome.google.com/webstore/detail/contributors-on-github/cjbacdldhllelehomkmlniifaojgaeph?utm_source=chrome-app-launcher-info-dialog)** | Shows contribution details on GitHub PRs |
| **+** | **[Dimensions](https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj?utm_source=chrome-app-launcher-info-dialog)** | Measure dimensions of elements on hover |
|       | **[Fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?utm_source=chrome-app-launcher-info-dialog)** | Makes full-sized screenshots |
|       | **[Mindful](https://chrome.google.com/webstore/detail/mindful-beta/cieekmjjdkckhpidgaffphlaljdfhhab?utm_source=chrome-app-launcher-info-dialog)** | Shows a beautiful notepad as the new tab page |
|       | **[JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?utm_source=chrome-app-launcher-info-dialog)** | Formats JSON files opened in the browser |
| **+** | **[Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh?utm_source=chrome-app-launcher-info-dialog)** | Shows elements outlines |
|       | **[GitHub Hovercard](https://chrome.google.com/webstore/detail/github-hovercard/mmoahbbnojgkclgceahhakhnccimnplk?utm_source=chrome-app-launcher-info-dialog)** | Shows link information on hover |
|       | **[Tab Size on GitHub](https://chrome.google.com/webstore/detail/tab-size-on-github/ofjbgncegkdemndciafljngjbdpfmbkn?utm_source=chrome-app-launcher-info-dialog)** | Decreases GitHub indentation wideness |
| **+** | **[Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg?utm_source=chrome-app-launcher-info-dialog)** | Detects technologies used by a website |
|       | **[WAVE Evaluation Tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)** | Adds tools for accessibility testing |
| **+** | **[Web Developer](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm?utm_source=chrome-app-launcher-info-dialog)** | Toolbar with various development helpers |
| **+** | **[WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?utm_source=chrome-app-launcher-info-dialog)** | Shows used font family on hover |

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
- [`npm-check-updates`](https://github.com/tjunnone/npm-check-updates) checks for newer versions of npm packages

<br><br><br>

## ConEmu

TODO: Download link, Theme, Settings, PoshGit

<br><br><br>

## Creator

**Dominique Müller**

- E-Mail: **[dominique.m.mueller@gmail.com](mailto:dominique.m.mueller@gmail.com)**
- Website: **[www.devdom.io](https://www.devdom.io/)**
- Twitter: **[@itsdevdom](https://twitter.com/itsdevdom)**
