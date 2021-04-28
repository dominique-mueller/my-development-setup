<div align="center">

# My Development Setup

My personal development setup, for Frontend Development on Windows.

</div>

<br><br>

## [Visual Studio Code](https://code.visualstudio.com/)

Lightweight Code Editor, focused on and optimized for web development.

> If I have to look into code that is not Frontend, I usually install and use
> **[IntelliJ](https://www.jetbrains.com/de-de/idea/download/#section=windows)** for that.

<br>

### Installation

Download the latest version **[right here](https://code.visualstudio.com/#alt-downloads)**, preferrably

- the **64 Bit** version _(for the best performance)_
- the **User Installer** _(for automatic updates)_

<br>

### Theme

My favourite theme is **[Oceanic Next](https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext)**! It's simple, it's
dark - it's fantastic!

<br>

### Font

A custom font? Yes, please! I'm currently a huge fan of Microsoft's **[Cascadia Code](https://github.com/microsoft/cascadia-code)**.
Download the latest font zip file from the GitHub release page, unzip it and install every font within the "ttf" folder. Don't forget to
restart Visual Studio Code so that it knows about the font.

<br>

### Extensions

The following are my must-have extensions for all kinds of web development. Depending on the project I am currently working on, I sometimes
disable some extensions.

| Extension                                                                                                                    | Description                                                                     |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)**                      | Improve editing experience in Angular HTML templates                            |
| **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                     | Rename HTML / XML / JSX tag pairs (in addition to the "linked editing" setting) |
| **[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)**                        | Colorize comments based on type (e.g. info, alert, question, ...)               |
| **[Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)**       | Colorize matching brackets                                                      |
| **[CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics)**                      | Analyze and show code complexity                                                |
| **[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)**                  | Debug Chrome from within Visual Studio Code                                     |
| **[Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug)**        | Debug Firefox from within Visual Studio Code                                    |
| **[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)**                            | Apply settings defined in .editconfig file                                      |
| **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)**                                     | ESLint support                                                                  |
| **[Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)**                               | Enhanced Git support                                                            |
| **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**                                           | Enhanced Git support                                                            |
| **[Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)**                                            | Add indentation guide lines                                                     |
| **[Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)**                 | Add small image preview next to lines                                           |
| **[JSON5 syntax](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-json5)**                                  | Add JSON5 file support                                                          |
| **[Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)**                             | Real-time collaboration                                                         |
| **[Markdown Preview Github](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)**    | Markdown Preview in the Github Theme                                            |
| **[Markdown Preview BitBucket](https://marketplace.visualstudio.com/items?itemName=hbrok.markdown-preview-bitbucket)**       | Markdown Preview in the BitBucket Theme                                         |
| **[Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)**                            | Open HTML in browser(s)                                                         |
| **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)**                                   | Prettier support                                                                |
| **[Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)**                                  | Compare code blocks                                                             |
| **[Sass](https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented)**                                          | SASS file support                                                               |
| **[Sass Lint](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint)**                                       | SASS linter                                                                     |
| **[Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)**                                      | Quickly sort lines in different ways / by different criteria                    |
| **[SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)**                                 | Add SVG file support                                                            |
| **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**                        | Highlight TODOs, FIXMEs and similar                                             |
| **[TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)**                                   | Add a TODO panel listing all TODO comments                                      |
| **[Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)**                        | Highlight and auto-remove trailing spaces                                       |
| **[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**                         | Show dependency version infos in package.json                                   |
| **[Vistual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)** | AI-assisted autocompletion                                                      |
| **[YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)**                                           | YAML file support                                                               |

<br>

### Settings

The following are my settings (includes settings for extensions, theme, font, ...):

```json
{
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.wordWrap": "off",
    "editor.quickSuggestions": false
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "bracket-pair-colorizer-2.showHorizontalScopeLine": false,
  "bracket-pair-colorizer-2.showVerticalScopeLine": false,
  "breadcrumbs.enabled": false,
  "editor.accessibilitySupport": "off",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.highlightActiveIndentGuide": false,
  "editor.lineHeight": 20,
  "editor.linkedEditing": true,
  "editor.minimap.maxColumn": 140,
  "editor.renderIndentGuides": false,
  "editor.rulers": [140],
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "explorer.confirmDragAndDrop": false,
  "explorer.openEditors.visible": 0,
  "extensions.ignoreRecommendations": true,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "git.enableCommitSigning": true,
  "gitlens.blame.toggleMode": "window",
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.enabled": false,
  "gitlens.currentLine.enabled": false,
  "html.format.endWithNewline": true,
  "html.format.indentHandlebars": true,
  "html.format.indentInnerHtml": true,
  "html.format.wrapLineLength": 140,
  "javascript.preferences.importModuleSpecifier": "relative",
  "javascript.preferences.quoteStyle": "single",
  "prettier.printWidth": 140,
  "prettier.singleQuote": true,
  "terminal.external.windowsExec": "C:\\Program Files\\PowerShell\\7\\pwsh.exe",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.scrollback": 10000,
  "terminal.integrated.shell.windows": "C:\\Program Files\\PowerShell\\7\\pwsh.exe",
  "todo-tree.tree.showScanModeButton": false,
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
  "typescript.locale": "en",
  "typescript.preferences.importModuleSpecifier": "relative",
  "typescript.preferences.quoteStyle": "single",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "window.newWindowDimensions": "maximized",
  "workbench.commandPalette.history": 1000,
  "workbench.editor.closeOnFileDelete": true,
  "workbench.tips.enabled": false,
  "editor.fontSize": 13,
  "emmet.showExpandedAbbreviation": "never",
  "workbench.colorTheme": "Oceanic Next (dimmed bg)",
  "[json5]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.editor.decorations.badges": false,
  "workbench.startupEditor": "none",
  "debug.javascript.codelens.npmScripts": "never"
}
```

<br>

### Keyboard Shortcuts

The following are my keyboard shortcuts:

```javascript
[
  {
    key: 'ctrl+shift+space',
    command: 'editor.action.commentLine',
    when: 'editorTextFocus && !editorReadonly',
  },
  {
    key: 'ctrl+shift+alt+f4',
    command: 'workbench.action.reloadWindow',
  },
];
```

<br><br><br>

## [Google Chrome](https://www.google.de/chrome/index.html)

Primary browser for development purposes.

<br>

### Extensions

The following are my must-have extensions for Frontend development in general. Depending on the project I am currently working on, I
sometimes disable some extensions.

| Extension                                                                                                                                                                  | Description                                                 |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **[Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd)**                                                                            | Adds tools for debugging and profiling Angular applications |
| **[aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)**                                                                                  | Adds tools for accessibility testing                        |
| **[Baseliner](https://chrome.google.com/webstore/detail/baseliner/agoopbiflnjadjfbhimhlmcbgmdgldld)**                                                                      | Show lines for vertical rhythm                              |
| **[ChromeLens](https://chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd/related)**                                                            | Simulates visual impairments                                |
| **[ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?utm_source=chrome-app-launcher-info-dialog)**                         | Color Picker                                                |
| **[Contributors on GitHub](https://chrome.google.com/webstore/detail/contributors-on-github/cjbacdldhllelehomkmlniifaojgaeph?utm_source=chrome-app-launcher-info-dialog)** | Shows contribution details on GitHub PRs                    |
| **[Dimensions](https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj?utm_source=chrome-app-launcher-info-dialog)**                         | Measure dimensions of elements on hover                     |
| **[Feature Queries Manager](https://chrome.google.com/webstore/detail/feature-queries-manager/fbhgnconlfgmienbmpbeeenffagggonp)**                                          | Manage CSS feature queries                                  |
| **[Fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?utm_source=chrome-app-launcher-info-dialog)**             | Makes full-sized screenshots                                |
| **[Mindful](https://chrome.google.com/webstore/detail/mindful-beta/cieekmjjdkckhpidgaffphlaljdfhhab?utm_source=chrome-app-launcher-info-dialog)**                          | Shows a beautiful notepad as the new tab page               |
| **[JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?utm_source=chrome-app-launcher-info-dialog)**                 | Formats JSON files opened in the browser                    |
| **[Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh?utm_source=chrome-app-launcher-info-dialog)**                | Shows elements outlines                                     |
| **[GitHub Markdown Menu](https://chrome.google.com/webstore/detail/github-markdown-menu/jekgocfoijmbgcjejohdgmojaejofdpo)**                                                | Shows a markdown table of contents as a dropdown menu       |
| **[React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)**                                              | Adds tools for debugging and profiling React applications   |
| **[Tab Size on GitHub](https://chrome.google.com/webstore/detail/tab-size-on-github/ofjbgncegkdemndciafljngjbdpfmbkn?utm_source=chrome-app-launcher-info-dialog)**         | Decreases GitHub indentation wideness                       |
| **[Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg?utm_source=chrome-app-launcher-info-dialog)**                         | Detects technologies used by a website                      |
| **[WAVE Evaluation Tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)**                                                | Adds tools for accessibility testing                        |
| **[Web Developer](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm?utm_source=chrome-app-launcher-info-dialog)**                   | Toolbar with various development helpers                    |
| **[WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?utm_source=chrome-app-launcher-info-dialog)**                             | Shows used font family on hover                             |

<br><br><br>

## [Git](https://git-scm.com/)

Version Control Software, accessibly via command line.

<br>

### Settings

```conf
user.name=<NAME>
user.email=<EMAIL>
core.autocrlf=false # Do not convert to Windows line feeds automatically (can lead to issues)
push.default=current # Simplify pushing new branches to remote
push.followtags=true # Always push tags along
status.showUntrackedFiles=all # Show all files when changing directories
credential.helper=wincred # Remember credentials
```

> Also read **[Better Git configuration](https://blog.scottnonnenberg.com/better-git-configuration/)**.

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

Installed via **[nvm for Windows](https://github.com/coreybutler/nvm-windows)**, preferrably using the "nvm-setup" variant.

Once nvm is installed, open a new console and setup the preferred NodeJS version:

```bash
nvm install <VERSION>
nvm use <VERSION>
```

> Note: Upgrading npm by using npm is still an issue! See **[nvm-windows#300](https://github.com/coreybutler/nvm-windows/issues/300)**.

<br><br><br>

## [ConEmu](https://conemu.github.io/en/Downloads.html) with [PowerShell](https://github.com/PowerShell/PowerShell)

ConEmu is a terminal application which allowes for running multiple (even different) command lines tools within a tabbed window, while also enabling customizations and enhanced configuration.

<br>

### Settings

The following are my personal settings:

- **Color theme: Twilight**<br>At _General_, select _Twilight_ below _Choose color scheme_
- **Increased console buffer**<br>At _General / Size & Pos / Console buffer height_, activate _Long console output_ and enter the biggest value possible (at the moment `32766`)
- **Default Task: PowerShell, with custom start directory**<br>At _Startup / Tasks_, create a new task (e.g. named "Favourites::Development"). Activate _Default task for new console_, _Default shell_, and _Taskbar jump lists_. Define the default start directory within the task parameters, e.g. `/dir C:\Projects`. Use the command `pwsh.exe`. At _Startup_, define it as the default task by selecting it below _Specific named task_.

<br>

### [PoshGit](https://github.com/dahlbyk/posh-git) for PowerShell

Displays additional Git status information (e.g. current branch, changes) within the PowerShell at the beginning of lines. Set it up by running the following commands within the PowerShell:

1. Change the execution policy: `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Confirm`
2. Update `PowerShellGet` to its latest version: `Install-Module PowerShellGet -Scope CurrentUser -Force -AllowClobber`
3. Install PoshGit: `PowerShellGet\Install-Module posh-git -Scope CurrentUser -Force`
4. Add PoshGit to PowerShell profile: `Add-PoshGitToProfile -AllHosts`

> Some preparation steps might be optional depending on the system.

<br><br><br>

## Other Software

The following is a list of further Software I usually get for development and testing purposes.

<br>

### Browsers

| Name                                                           | Description                             |
| -------------------------------------------------------------- | --------------------------------------- |
| **[Google Chrome](https://www.google.de/chrome/index.html)**   | Primary browser                         |
| **[Mozilla Firefox](https://www.mozilla.org/de/firefox/new/)** | Additional browser for testing purposes |
| **[Microsoft Edge](https://www.microsoft.com/en-us/edge)**     | Additional browser for testing purposes |
| **[Opera](https://www.opera.com/)**                            | Additional browser for testing purposes |

<br>

### Design

| Name                                                                  | Description                              |
| --------------------------------------------------------------------- | ---------------------------------------- |
| **[ScreenToGif](https://www.screentogif.com/)**                       | GIF screen recorder (e.g. for docs, PRs) |
| **[Just Color Picker](https://annystudio.com/software/colorpicker/)** | Global color picker                      |

<br>

### Development Tools

| Name                                                                                       | Description                                       |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------- |
| **[IntelliJ](https://www.jetbrains.com/de-de/idea/download/#section=windows)**             | IDE (for everything that I do not use VSCode for) |
| **[NVDA](http://nvda.bhvd.de/)**                                                           | Screenreader (for testing accessibility)          |
| **[Postman](https://www.getpostman.com/)**                                                 | HTTP API testing                                  |
| **[Postwoman](https://postwoman.io/)**                                                     | HTTP / WebSocket & SSE API testing                |
| **[Firecamp](https://firecamp.io/)**                                                       | HTTP / GraphQL / WebSocket API testing            |
| **[MQTT Explorer](http://mqtt-explorer.com/)**                                             | MQTT testing                                      |
| **[FileZilla](https://filezilla-project.org/)**                                            | Simple FTP Client                                 |
| **[Docker Desktop](https://hub.docker.com/editions/community/docker-ce-desktop-windows/)** | Docker container management                       |
| **[MiniKube](https://github.com/kubernetes/minikube)**                                     | Running Kubernetes clusters locally               |
| **[kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)**                     | Manage Kubernetes clusters                        |
| **[Kube Forwarder](https://www.electronjs.org/apps/kube-forwarder)**                       | Manage Kubernetes port-forwardings with a UI      |
| **[Notepad++](https://notepad-plus-plus.org/download/v7.7.1.html)**                        | Universal file editor                             |
| **[WinMerge](https://winmerge.org/)**                                                      | Compare files and folders                         |
