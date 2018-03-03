<div align="center">

# My Development Setup

My personal development setup, for Frontend Development on Windows.

</div>

<br><br>

## [Visual Studio Code](https://code.visualstudio.com/)

Lightweigh Code Editor, focused on Web Development. Usually I prefer the Insiders Build.

### Theme

- **[Oceanic Next](https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext)**

### Extensions

|       | Extension                                                                                                                         | Description          |
| :---: | --------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **+** | **[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)**                           | Extended autocomplete & info for Angular |
| **+** | **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                          | Automatically renames paired HTML tags |
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
| **+** | **[Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)**                             | Highlight and remove trailing spaces |
| **+** | **[TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)**                                                      | TS file linter |
| **+** | **[Typescript Deporter](https://marketplace.visualstudio.com/items?itemName=Acr0most.ts-deporter)**                               | Remove ununsed TypeScript imports |
| **+** | **[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)**                              | Show dependency version infos in package.json |
| **+** | **[View In Browser](https://marketplace.visualstudio.com/items?itemName=qinjia.view-in-browser)**                                 | Directly open file in browser |

<br>

### Settings

``` json
{
    // Default settings
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

    // Languages
    "html.format.indentInnerHtml": true,
    "html.format.wrapLineLength": 140,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,

    // Extension settings
    "docthis.includeMemberOfOnClassMembers": false,
    "docthis.includeMemberOfOnInterfaceMembers": false,
    "docthis.includeTypes": false
}
```

### Keybindings

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

## 2

<br><br><br>

## Creator

**Dominique Müller**

- E-Mail: **[dominique.m.mueller@gmail.com](mailto:dominique.m.mueller@gmail.com)**
- Website: **[www.devdom.io](https://www.devdom.io/)**
- Twitter: **[@itsdevdom](https://twitter.com/itsdevdom)**
