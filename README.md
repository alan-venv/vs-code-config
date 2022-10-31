# Visual Studio Code
My custom visual studio code settings

## Extensions
* Better Comments
* Code Spell Checker
* Error Lens
* Go
* Material Icon Theme
* One Dark Pro
* Path Intellisense
* Thunder Client

## Fonts
* sudo apt install fonts-firacode

## Shortcuts
<pre>
• (CTRL + SHIFT + I)          Formatar o código
• (SELECT) + (CTRL + D)       Seleciona a proxima string igual que for localizada
• (ALT + CLICK)               Cria multiplos cursores
• (ALT + UP)                  Move current line to up
• (ALT + DOWN)                Move current line to down
• (CTRL + /)                  Comment current line
• (CTRL + RETURN)             Open terminal
</pre>
## Keybindings.json
```
[
  {
    "key": "ctrl+enter",
    "command": "workbench.action.terminal.toggleTerminal",
    "when": "terminal.active"
  }
]
```

## Settings.json
```
{
  // Workbench
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "One Dark Pro Darker",
  "workbench.startupEditor": "none",
  "workbench.editor.labelFormat": "short",
  // Editor
  "editor.tabSize": 2,
  "editor.fontFamily": "Fira Code",
  "editor.formatOnSave": true,
  "editor.inlineSuggest.enabled": true,
  "editor.semanticHighlighting.enabled": false,
  "editor.bracketPairColorization.enabled": true,
  "editor.fontSize": 16,
  "editor.rulers": [
    80,
    120
  ],
  "editor.suggestSelection": "first",
  "editor.renderLineHighlight": "gutter",
  "editor.lineHeight": 26,
  "editor.fontLigatures": true,
  // Files
  "files.encoding": "utf8",
  "files.eol": "\n",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  // Explorer
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  // Javascript && Typescript
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  // Terminal
  "terminal.integrated.fontSize": 14,
  // Extensions
  "extensions.ignoreRecommendations": true,
  "material-icon-theme.folders.associations": {
    "entities": "class",
    "use-cases": "functions",
    "migrations": "tools",
    "useCases": "functions",
    "eslint-config": "tools",
    "modules": "components",
    "infra": "app",
    "factories": "class",
    "repositories": "mappings",
    "sqlite": "database",
    "in-memory": "database",
  },
  "[go]": {
    "editor.defaultFormatter": "golang.go"
  },
  "cSpell.userWords": [
    "dbname",
    "gonic",
    "gorm",
    "pynput",
    "sslmode",
    "todos",
    "usecases"
  ]
}
```
