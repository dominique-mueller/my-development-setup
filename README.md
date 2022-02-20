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

I am currently using my own custom theme **[Deep Ocean](https://marketplace.visualstudio.com/items?itemName=itsdevdom.theme-deep-ocean)**
which is based on the Oceanic Next color palette! It's simple, it's dark - it's fantastic!

<br>

### Font

I am currently using the **[MonoLisa](https://www.monolisa.dev/)** font (paid) and I really do enjoy it a lot.

> If you are looking for an alternative, I can highly recommend Microsoft's **[Cascadia Code](https://github.com/microsoft/cascadia-code)**
> font (free).

<br>

### Extensions

The following are my must-have extensions for all kinds of web development. Depending on the project I am currently working on, I sometimes
disable some extensions.

| Extension                                                                                                                           | Description                                                  |
| ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| **[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)**                             | Improve editing experience in Angular HTML templates         |
| **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                            | Automatically rename paired HTML / XML / JSX tags            |
| **[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)**                               | Improved comment colorization                                |
| **[CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics)**                             | Code complexity computation in JavaScript / TypeScript       |
| **[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)**                                   | Apply settings defined in .editconfig file                   |
| **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)**                                            | ESLint support                                               |
| **[Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)**                                      | Enhanced Git                                                 |
| **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**                                                  | Enhanced Git                                                 |
| **[Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)**                                                   | Indentation guide lines                                      |
| **[Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)**                        | Image previews within gutter                                 |
| **[JSON5 syntax](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-json5)**                                         | JSON5 language support                                       |
| **[Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)**                                    | Real-time collaboration                                      |
| **[GitHub Markdown Preview (Extension Pack)](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)** | Markdown Preview, using the Github Theme                     |
| **[Markdown Preview BitBucket](https://marketplace.visualstudio.com/items?itemName=hbrok.markdown-preview-bitbucket)**              | Markdown Preview, using the BitBucket Theme                  |
| **[MDX](https://marketplace.visualstudio.com/items?itemName=silvenon.mdx)**                                                         | MDX language support                                         |
| **[Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)**                                   | Open HTML files in browser(s)                                |
| **[Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)**                                         | Diffing tool                                                 |
| **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)**                                          | Prettier                                                     |
| **[Sass](https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented)**                                                 | SASS language support                                        |
| **[Sass Lint](https://marketplace.visualstudio.com/items?itemName=glen-84.sass-lint)**                                              | SASS linter                                                  |
| **[Sort JSON objects](https://marketplace.visualstudio.com/items?itemName=richie5um2.vscode-sort-json)**                            | Quickly sort JSON objects by key                             |
| **[Sort JS object keys](https://marketplace.visualstudio.com/items?itemName=zengxingxin.sort-js-object-keys)**                      | Quickly sort JS objects by key                               |
| **[Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)**                                             | Quickly sort lines in different ways / by different criteria |
| **[SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)**                                        | SVG file support                                             |
| **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**                               | Highlight TODOs, FIXMEs and similar comments                 |
| **[Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)**                                          | Panel listing all TODO comments                              |
| **[Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)**                               | Highlighting and auto-removal of trailing spaces             |
| **[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**                                | Dependency version infos in `package.json`                   |
| **[Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)**         | AI-assisted autocompletion                                   |
| **[XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)**                                                    | XML language support                                         |
| **[YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)**                                                  | YAML language support                                        |

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
  "[json5]": {
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
  "breadcrumbs.enabled": false,
  "debug.javascript.codelens.npmScripts": "never",
  "editor.accessibilitySupport": "off",
  "editor.bracketPairColorization.enabled": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.fontFamily": "'MonoLisa', Consolas, 'Courier New', monospace",
  "editor.fontSize": 13,
  "editor.highlightActiveIndentGuide": false,
  "editor.lineHeight": 22,
  "editor.linkedEditing": true,
  "editor.minimap.maxColumn": 140,
  "editor.renderIndentGuides": false,
  "editor.rulers": [140],
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "emmet.showExpandedAbbreviation": "never",
  "emmet.triggerExpansionOnTab": true,
  "explorer.confirmDragAndDrop": false,
  "explorer.openEditors.visible": 0,
  "extensions.ignoreRecommendations": true,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "git.enableCommitSigning": true,
  "gitlens.codeLens.enabled": false,
  "gitlens.currentLine.enabled": false,
  "html.format.endWithNewline": true,
  "html.format.indentHandlebars": true,
  "html.format.indentInnerHtml": true,
  "html.format.wrapLineLength": 140,
  "javascript.preferences.importModuleSpecifier": "relative",
  "javascript.preferences.quoteStyle": "single",
  "markdown-preview-github-styles.colorTheme": "light",
  "prettier.printWidth": 140,
  "prettier.singleQuote": true,
  "redhat.telemetry.enabled": true,
  "terminal.external.windowsExec": "C:\\Program Files\\PowerShell\\7\\pwsh.exe",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.scrollback": 10000,
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
  "typescript.locale": "en",
  "typescript.preferences.importModuleSpecifier": "relative",
  "typescript.preferences.quoteStyle": "single",
  "window.newWindowDimensions": "maximized",
  "workbench.colorTheme": "Deep Ocean",
  "workbench.editor.closeOnFileDelete": true,
  "workbench.editor.decorations.badges": false,
  "workbench.startupEditor": "none",
  "workbench.tips.enabled": false
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

| Extension                                                                                                                         | Description                                                 |
| --------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **[Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd)**                                   | Adds tools for debugging and profiling Angular applications |
| **[aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)**                                         | Adds tools for accessibility testing                        |
| **[Baseliner](https://chrome.google.com/webstore/detail/baseliner/agoopbiflnjadjfbhimhlmcbgmdgldld)**                             | Show lines for vertical rhythm                              |
| **[ChromeLens](https://chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd)**                           | Simulates visual impairments                                |
| **[ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp)**                           | Color Picker                                                |
| **[Contributors on GitHub](https://chrome.google.com/webstore/detail/contributors-on-github/cjbacdldhllelehomkmlniifaojgaeph)**   | Shows contribution details on GitHub PRs                    |
| **[Dimensions](https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj)**                           | Measure dimensions of elements on hover                     |
| **[Feature Queries Manager](https://chrome.google.com/webstore/detail/feature-queries-manager/fbhgnconlfgmienbmpbeeenffagggonp)** | Manage CSS feature queries                                  |
| **[Fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg)**               | Makes full-sized screenshots                                |
| **[Mindful](https://chrome.google.com/webstore/detail/mindful-beta/cieekmjjdkckhpidgaffphlaljdfhhab)**                            | Shows a beautiful notepad as the new tab page               |
| **[JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa)**                   | Formats JSON files opened in the browser                    |
| **[Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh)**                  | Shows elements outlines                                     |
| **[GitHub Markdown Menu](https://chrome.google.com/webstore/detail/github-markdown-menu/jekgocfoijmbgcjejohdgmojaejofdpo)**       | Shows a markdown table of contents as a dropdown menu       |
| **[React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)**     | Adds tools for debugging and profiling React applications   |
| **[Tab Size on GitHub](https://chrome.google.com/webstore/detail/tab-size-on-github/ofjbgncegkdemndciafljngjbdpfmbkn)**           | Decreases GitHub indentation wideness                       |
| **[VisBug](https://chrome.google.com/webstore/detail/visbug/cdockenadnadldjbbgcallicgledbeoc)**                                   | Design debugging tools                                      |
| **[Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg)**                           | Detects technologies used by a website                      |
| **[WAVE Evaluation Tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)**       | Adds tools for accessibility testing                        |
| **[Web Developer](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm)**                     | Toolbar with various development helpers                    |
| **[Web Vitals](https://chrome.google.com/webstore/detail/web-vitals/ahfhijdlegdabablpippeagghigmibma)**                           | Website health metrics                                      |
| **[WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm)**                               | Shows used font family on hover                             |

<br><br><br>

## [Git](https://git-scm.com/)

Version Control Software, accessibly via command line.

<br>

### Settings

Look at the current configuration using:

```bash
git config --global --list
```

Add options using:

```bash
git config --global user.name <NAME>
git config --global user.email <EMAIL>
git config --global core.ignorecase false # Respect casing in file names
git config --global push.default current # Simplify pushing new branches to remote
git config --global push.followtags true # Always push tags along
git config --global status.showUntrackedFiles all # Show all files when changing directories
git config --global credential.helper wincred # Remember credentials
```

> Also read **[Better Git configuration](https://blog.scottnonnenberg.com/better-git-configuration/)**.

I am currently still unsure about the following options:

```conf
core.autocrlf=false # Do not convert to Windows line feeds automatically
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

I manage multiple NodeJS versions via **[Volta](https://github.com/volta-cli/volta)**, a tool that's very similar to nvm but also runs on
lovely Windows. Once installed (using the latest GitHub release asset binary), open a new console and setup the preferred NodeJS version:

```bash
volta install node@<VERSION>
```

> Note: Windows developer mode needs to be enabled. See
> [this docs page](https://docs.microsoft.com/en-us/windows/apps/get-started/enable-your-device-for-development).

<br><br><br>

## [ConEmu](https://conemu.github.io/en/Downloads.html) with [PowerShell](https://github.com/PowerShell/PowerShell)

ConEmu is a terminal application which allowes for running multiple (even different) command lines tools within a tabbed window, while also enabling customizations and enhanced configuration.

<br>

### ConEmu Settings

The following are my personal settings:

- **Color theme: Twilight**<br>At _General_, select _Twilight_ below _Choose color scheme_
- **Default Task: PowerShell, with custom start directory**<br>At _Startup / Tasks_, create a new task (e.g. named "Development"). Activate _Default task for new console_, _Default shell_, and _Taskbar jump lists_. Use the command `pwsh.exe`. Click _Startup dir ..._ and select the folder that contains all projects. At _Startup_, define it as the default task by selecting it below _Specific named task_.

<br>

### Improved PowerShell autocomplete

Autocomplete based on command history can be enabled the following way:

Open PowerShell profile file (will be created if it does not exist):

```powershell
Notepad $profile
```

Then, configure autocomplete based on history via the arrow keys by adding:

```powershell
# Autocomple based on history, via arrow keys
Set-PSReadlineKeyHandler -Key UpArrow -Function HistorySearchBackward
Set-PSReadlineKeyHandler -Key DownArrow -Function HistorySearchForward
```

<br>

### [PoshGit](https://github.com/dahlbyk/posh-git) for PowerShell

Displays additional Git status information (e.g. current branch, changes) within the PowerShell at the beginning of lines. Git, obviously,
needs to be installed upfront. Set it up by running the following commands within the PowerShell:

Update `PowerShellGet` to its latest version (optional, might fail):

```powershell
Install-Module PowerShellGet -Scope CurrentUser -Force -AllowClobber
```

Now, install PoshGit:

```powershell
PowerShellGet\Install-Module posh-git -Scope CurrentUser -Force
```

Then, enable PoshGit by adding it to the PowerShell profile:

```powershell
Add-PoshGitToProfile -AllHosts
```

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

| Name                                                                                      | Description                                            |
| ----------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| **[Docker Desktop](https://hub.docker.com/editions/community/docker-ce-desktop-windows)** | Docker container management                            |
| **[Fiddler Classic](https://www.telerik.com/fiddler/fiddler-classic)**                    | Analyze HTTP / HTTPS traffic, simulate corporate proxy |
| **[FileZilla](https://filezilla-project.org)**                                            | Simple FTP Client                                      |
| **[Firecamp](https://firecamp.io)**                                                       | HTTP / GraphQL / WebSocket API testing                 |
| **[Hoppscotch (prev. Postwoman)](https://hoppscotch.io)**                                 | HTTP / WebSocket & SSE API testing                     |
| **[IntelliJ](https://www.jetbrains.com/de-de/idea/download/#section=windows)**            | IDE (for everything that I do not use VSCode for)      |
| **[Kube Forwarder](https://www.electronjs.org/apps/kube-forwarder)**                      | Manage Kubernetes port-forwardings with a UI           |
| **[kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl)**                     | Manage Kubernetes clusters                             |
| **[MiniKube](https://github.com/kubernetes/minikube)**                                    | Running Kubernetes clusters locally                    |
| **[MQTT Explorer](http://mqtt-explorer.com)**                                             | MQTT testing                                           |
| **[Notepad++](https://notepad-plus-plus.org/downloads)**                                  | Universal file editor                                  |
| **[NVDA](http://nvda.bhvd.de)**                                                           | Screenreader (for testing accessibility)               |
| **[pgAdmin](https://www.pgadmin.org/download/pgadmin-4-windows)**                         | PostgreSQL database tool                               |
| **[Postman](https://www.getpostman.com/)**                                                | HTTP API testing                                       |
| **[WinMerge](https://winmerge.org)**                                                      | Compare files and folders                              |
