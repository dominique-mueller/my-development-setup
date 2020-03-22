<div align="center">

# My Development Setup

My personal development setup, for Frontend Development on Windows.

</div>

<br><br>

## Table of Contents

- **[Visual Studio Code](#visual-studio-code)**<br>Setup, Theme, Extensions, Settings, Key Bindings
- **[Google Chrome](#google-chrome)**<br>Extensions
- **[Git](#git)**<br>Settings, Alias, Commit Signing
- **[NodeJS](#nodejs)**<br>nvm, npm, global packages
- **[ConEmu](#conemu)**<br>Settings, PoshGit
- **[Other Software](#other-software)**<br>Browsers, FTP Client, ...

<br><br><br>

## [Visual Studio Code](https://code.visualstudio.com/)

Lightweight Code Editor, focused on and optimized for web development. If you want to participate in early tests, choose the "Insiders Build" variant.

<br>

### Installation

Download the latest version **[right here](https://code.visualstudio.com/#alt-downloads)**, preferrably

- the **64 Bit** version _(for the best performance)_
- the **User Installer** _(for automatic updates)_

<br>

### Theme

My favourite theme is **[Oceanic Next](https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext)**! It's simple, it's dark - it's fantastic!

<br>

### Extensions

The following are my must-have extensions for all kinds of web development.

| Extension                                                                                                                    | Description                                                       |
| ---------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                     | Automatically rename HTML tag pairs                               |
| **[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)**                        | Colorize comments based on type (e.g. info, alert, question, ...) |
| **[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)**         | Colorize matching brackets                                        |
| **[CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics)**                      | Analyze and show code complexity                                  |
| **[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)**                  | Debug Chrome within Visual Studio Code                            |
| **[Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)**                                | Docker file support & tooling                                     |
| **[Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)**                                     | Generate JSDoc comments                                           |
| **[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)**                            | Apply settings defined in .editconfig file                        |
| **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)**                                     | ESLint support                                                    |
| **[GitHub Actions](https://marketplace.visualstudio.com/items?itemName=OmarTawfik.github-actions-vscode)**                   | GitHub Actions file support                                       |
| **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**                                           | Enhanced Git support                                              |
| **[Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)**                                            | Add indentation guide lines                                       |
| **[Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)**                 | Add small image preview next to lines                             |
| **[JSON5 syntax](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-json5)**                                  | Add JSON5 file support                                            |
| **[Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)**            | Kubernetes tooling                                                |
| **[Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)**                             | Real-time collaboration                                           |
| **[Markdown Preview Github](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)**    | Markdown Preview in the Github Theme                              |
| **[Markdown Preview BitBucket](https://marketplace.visualstudio.com/items?itemName=hbrok.markdown-preview-bitbucket)**       | Markdown Preview in the BitBucket Theme                           |
| **[Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)**                            | Open HTML in browser(s)                                           |
| **[Prettier Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)**                    | Prettier support                                                  |
| **[Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)**                                  | Compare code blocks                                               |
| **[Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)**                                             | Capture beautiful code screenshots                                |
| **[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)**                       | Manage multiple projects                                          |
| **[Sass](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented)**                                   | SASS file support                                                 |
| **[Sass Lint](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint)**                                       | SASS linter                                                       |
| **[Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)**                                      | Quickly sort lines in different ways / by different criteria      |
| **[SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)**                                 | Add SVG file support                                              |
| **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**                        | Highlight TODOs, FIXMEs and similar                               |
| **[TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-treet)**                                  | Add a TODO panel listing all TODO comments                        |
| **[Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)**                        | Highlight and auto-remove trailing spaces                         |
| **[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**                         | Show dependency version infos in package.json                     |
| **[Vistual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)** | AI-assisted autocompletion                                        |
| **[YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)**                                           | YAML file support                                                 |

<br>

### Extensions (Angular)

The following are extensions which improve the workflow when working on **[Angular](https://angular.io/)** apps.

| Extension                                                                                               | Description                                          |
| ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)** | Improve editing experience in Angular HTML templates |

<br>

### Extensions (React)

TODO

<br>

### Settings

The following are my settings (includes settings for extensions):

```json
{
  "bracket-pair-colorizer-2.showHorizontalScopeLine": false,
  "bracket-pair-colorizer-2.showVerticalScopeLine": false,
  "docthis.includeMemberOfOnClassMembers": false,
  "docthis.includeMemberOfOnInterfaceMembers": false,
  "docthis.includeTypes": false,
  "editor.fontSize": 13,
  "editor.lineHeight": 19,
  "editor.minimap.maxColumn": 140,
  "editor.rulers": [140],
  "editor.tabSize": 2,
  "explorer.confirmDragAndDrop": false,
  "explorer.openEditors.visible": 0,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "git.enableCommitSigning": true,
  "html.format.endWithNewline": true,
  "html.format.indentHandlebars": true,
  "html.format.indentInnerHtml": true,
  "html.format.wrapLineLength": 140,
  "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
  "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
  "javascript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
  "javascript.implicitProjectConfig.checkJs": true,
  "javascript.implicitProjectConfig.experimentalDecorators": true,
  "javascript.preferences.importModuleSpecifier": "relative",
  "javascript.preferences.quoteStyle": "single",
  "terminal.external.windowsExec": "C:\\Program Files\\PowerShell\\7\\pwsh.exe",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.scrollback": 10000,
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
  "typescript.locale": "en",
  "typescript.preferences.importModuleSpecifier": "relative",
  "typescript.preferences.quoteStyle": "single",
  "window.newWindowDimensions": "maximized",
  "workbench.colorTheme": "Oceanic Next (dimmed bg)",
  "workbench.commandPalette.history": 1000,
  "workbench.editor.closeOnFileDelete": true,
  "workbench.tips.enabled": false,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "gitlens.blame.toggleMode": "window",
  "gitlens.currentLine.enabled": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "todo-tree.tree.showScanModeButton": false,
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "terminal.integrated.shell.windows": "C:\\Program Files\\PowerShell\\7\\pwsh.exe",
  "editor.highlightActiveIndentGuide": false,
  "editor.renderIndentGuides": false,
  "breadcrumbs.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.enabled": false
}
```

<br>

### Keyboard Shortcuts

The following are my keyboard shortcuts:

```javascript
[
  {
    key: "ctrl+shift+space",
    command: "editor.action.commentLine",
    when: "editorTextFocus && !editorReadonly"
  },
  {
    key: "ctrl+shift+alt+f4",
    command: "workbench.action.reloadWindow"
  }
];
```

<br><br><br>

## [Google Chrome](https://www.google.de/chrome/index.html)

Primary browser for development purposes.

<br>

### Extensions

The following are my must-have extensions for Frontend development in general.

| Extension                                                                                                                                                                  | Description                                           |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| **[aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)**                                                                                  | Adds tools for accessibility testing                  |
| **[Baseliner](https://chrome.google.com/webstore/detail/baseliner/agoopbiflnjadjfbhimhlmcbgmdgldld)**                                                                      | Show lines for vertical rhythm                        |
| **[ChromeLens](https://chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd/related)**                                                            | Simulates visual impairments                          |
| **[ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?utm_source=chrome-app-launcher-info-dialog)**                         | Color Picker                                          |
| **[Contributors on GitHub](https://chrome.google.com/webstore/detail/contributors-on-github/cjbacdldhllelehomkmlniifaojgaeph?utm_source=chrome-app-launcher-info-dialog)** | Shows contribution details on GitHub PRs              |
| **[Dimensions](https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj?utm_source=chrome-app-launcher-info-dialog)**                         | Measure dimensions of elements on hover               |
| **[Feature Queries Manager](https://chrome.google.com/webstore/detail/feature-queries-manager/fbhgnconlfgmienbmpbeeenffagggonp)**                                          | Manage CSS feature queries                            |
| **[Fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?utm_source=chrome-app-launcher-info-dialog)**             | Makes full-sized screenshots                          |
| **[Mindful](https://chrome.google.com/webstore/detail/mindful-beta/cieekmjjdkckhpidgaffphlaljdfhhab?utm_source=chrome-app-launcher-info-dialog)**                          | Shows a beautiful notepad as the new tab page         |
| **[JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?utm_source=chrome-app-launcher-info-dialog)**                 | Formats JSON files opened in the browser              |
| **[Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh?utm_source=chrome-app-launcher-info-dialog)**                | Shows elements outlines                               |
| **[GitHub Markdown Menu](https://chrome.google.com/webstore/detail/github-markdown-menu/jekgocfoijmbgcjejohdgmojaejofdpo)**                                                | Shows a markdown table of contents as a dropdown menu |
| **[Tab Size on GitHub](https://chrome.google.com/webstore/detail/tab-size-on-github/ofjbgncegkdemndciafljngjbdpfmbkn?utm_source=chrome-app-launcher-info-dialog)**         | Decreases GitHub indentation wideness                 |
| **[Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg?utm_source=chrome-app-launcher-info-dialog)**                         | Detects technologies used by a website                |
| **[WAVE Evaluation Tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)**                                                | Adds tools for accessibility testing                  |
| **[Web Developer](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm?utm_source=chrome-app-launcher-info-dialog)**                   | Toolbar with various development helpers              |
| **[WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?utm_source=chrome-app-launcher-info-dialog)**                             | Shows used font family on hover                       |

<br>

### Extensions (Angular)

The following are my extensions specifically for Angular development.

| Extension                                                                                       | Description                                                 |
| ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **[Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd)** | Adds tools for debugging and profiling Angular applications |

<br>

### Extensions (React)

The following are my extensions specifically for React development.

| Extension                                                                                                                     | Description                                               |
| ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| **[React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)** | Adds tools for debugging and profiling React applications |

<br><br><br>

## [Git](https://git-scm.com/)

Version Control Software, accessibly via command line.

<br>

### Settings

```conf
user.name=<NAME>
user.email=<EMAIL>
push.default=current # Simplify pushing new branches to remote
push.followtags=true # Always push tags along
status.showUntrackedFiles=all # Show all files when changing directories
credential.helper=wincred # Remember credentials
```

> Also read **[Better Git configuration](https://blog.scottnonnenberg.com/better-git-configuration/)**.

<br>

### Alias

Git aliases, for common actions:

#### Set upstream of current banch

```conf
alias.set-upstream=!git branch --set-upstream-to=origin/`git symbolic-ref --short HEAD`
```

#### Revert last commit (keeps the changes)

```conf
alias.pop=!git reset HEAD^
```

#### Clone without SSL certification verification

```conf
alias.clone-unsecure=!git -c http.sslVerify=false clone
```

<br>

### Commit Signing with GPG

When working on GitHub, I usually set up **[Commit Signing via GPG](https://help.github.com/articles/signing-commits-with-gpg/)**.

After installing **[GNU (for Windows)](https://gnupg.org/download/)**, continue **[generating a new GPG key and make it available to GitHub](https://help.github.com/articles/generating-a-new-gpg-key/)**. Then, use the following coniguration for Git:

```conf
user.signingkey=<KEY>
commit.gpgsign=true
gpg.program=C:\Program Files (x86)\GnuPG\bin\gpg.exe
```

<br><br><br>

## [NodeJS](https://nodejs.org/)

Installed via **[nvm for Windows](https://github.com/coreybutler/nvm-windows)**, preferrably

- using the "nvm-setup" variant (cause why not?)
- placing the installation to `C:\nvm`
- choosing `C:\nodejs` as the NodeJS versions root folder

Once nvm is installed, open a new console and setup the preferred NodeJS version:

```bash
nvm install <VERSION>   # The version can also be "latest"
nvm use <VERSION>
```

<br>

### npm

Upgrading npm itself is sometimes tricky, especially on Windows. Use **[this script for upgrading npm](https://gist.github.com/johnmcase/d31b799b9030327091a0e74880e4c530)**, adapt paths if necessary.

> Note: This script solves the **[nvm issue #300](https://github.com/coreybutler/nvm-windows/issues/300)** which is probably the reason for this issue.

<br>

### Global packages

- [`ts-node`](https://github.com/TypeStrong/ts-node) quickly compiles and runs TypeScript files, even outside of projects. Install together with `typescript`.

<br><br><br>

## [ConEmu](https://conemu.github.io/en/Downloads.html)

ConEmu is a terminal application which allowes for running multiple (even different) command lines tools within a tabbed window, while also enabling customizations and enhanced configuration.

<br>

### Settings

The following are my personal settings:

- **Color theme: Twilight**<br>At "General", select the theme below "Choose color scheme"
- **Increased console buffer**<br>At "General & Size & Pos" - "Console buffer height", activate "Long console output" and enter the biggest value possible (at the moment `32766`)
- **Default Task: PowerShell (Admin), with custom start directory**<br>At "Startup / Tasks", create a new task (e.g. named "Favourites::Development"). Activate "Default ask for new console", "Default shell", and "Taskbar jump lists". Define the default start directory within the task parameters, e.g. `/dir "C:\Projects"`. Use the command `powershell.exe -new_console:a`.

<br>

### [PoshGit](https://github.com/dahlbyk/posh-git) for PowerShell

Displays additional Git status information (e.g. current branch, changes) within the PowerShell at the beginning of lines. Set it up by running the following commands within the PowerShell:

1. Change the execution policy: `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Confirm`
2. Update `PowerShellGet` to its latest version: `Install-Module PowerShellGet -Scope CurrentUser -Force -AllowClobber`
3. Install PoshGit: `PowerShellGet\Install-Module posh-git -Scope CurrentUser -Force`
4. Add PoshGit to PowerShell profile: `Add-PoshGitToProfile -AllHosts`

<br><br><br>

## Other Software

The following is a list of further Software I usually get for development and testing purposes.

<br>

### Browsers

- **[Google Chrome](https://www.google.de/chrome/index.html)** as the primary browser
- **[Mozilla Firefox](https://www.mozilla.org/de/firefox/new/)** for testing purposes
- **[Opera](https://www.opera.com/)** for testing purposes
- **[Microsoft Edge](https://www.microsoft.com/en-us/edge)** for testing purposes

<br>

### Development

- **[Postman](https://www.getpostman.com/)** for HTTP API testing
- **[Postwoman](https://postwoman.io/)** for HTTP / WebSocket & SSE API testing
- **[Firecamp](https://firecamp.io/)** for HTTP / GraphQL / WebSocket API testing
- **[MQTT Explorer](http://mqtt-explorer.com/)** for MQTT testing
- **[FileZilla](https://filezilla-project.org/)** as a simple FTP Client
- **[MiniKube](https://github.com/kubernetes/minikube)** for running clusters locally
- **[kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)** for managing Kubernetes clusters
- **[Kube Forwarder](https://www.electronjs.org/apps/kube-forwarder)** for managing Kubernetes port-forwardings with a UI
- **[Notepad++](https://notepad-plus-plus.org/download/v7.7.1.html)** as a universal file editor

<br>

### Design

- **[ScreenToGif](https://www.screentogif.com/)** as a GIF screen recorder
- **[Just Color Picker](https://annystudio.com/software/colorpicker/)** as a global color picker

<br>

### Additional

- **[devhub](https://github.com/devhubapp/devhub)** as a GitHub notifications manager and activity watcher

<br><br><br>

## Creator

**Dominique Müller**

- E-Mail: **[dominique.m.mueller@gmail.com](mailto:dominique.m.mueller@gmail.com)**
- Website: **[www.devdom.io](https://www.devdom.io/)**
- Twitter: **[@itsdevdom](https://twitter.com/itsdevdom)**
