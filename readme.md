# My Visual Studio Code Settings

## Extensions List
1. <a href="https://github.com/usernamehw/vscode-error-lens" target="_blank">Error Lens:</a>&nbsp;Improve highlighting of errors, warnings and other language diagnostics.
2. <a href="https://github.com/topics/bookmarks" target="_blank">Bookmarks:</a>&nbsp;Excellent for making quick notes within the code.
3. <a href="https://github.com/aaron-bond/better-comments" target="_blank">Better Comments:</a>&nbsp;A powerful way to add custom comments to your codes.
4. <a href="https://github.com/topics/color-highlight" target="_blank">Color Highlight:</a>&nbsp;An extension that improves the reading of your color markings in CSS..
5.  <a href="https://github.com/willofindie/vscode-cssvar" target="_blank">CSS Var Complete:</a>&nbsp;Essentially it does the same thing as Color Highlight, but with color variables. A very good intellisense to work with css roots.
6. <a href="https://github.com/prettier/eslint-plugin-prettier" target="_blank">EsLint/Prettier:</a>&nbsp;While Eslint makes a detailed invoice to find possible errors involving JavaScript, Prettier identifies and standardizes the code in a quick and visually pleasing way.

<br/>

### Live Code Extensions
1. <a href="https://github.com/ritwickdey/vscode-live-server" target="_blank">Live Server:</a>&nbsp;Launch a development local Server with live reload feature for static & dynamic pages.
2. <a href="https://github.com/microsoft/vscode-livepreview" target="_blank">Live Preview:</a>&nbsp;An extension that hosts a local server for you to preview your web projects on!
3. <a href="https://github.com/microsoft/live-share" target="_blank">Live Share:</a>&nbsp;A code sharer to work on collaborative projects involving a team of developers!

<br/>

### My Favorites Customized

#### Theme
<a href="https://github.com/ayu-theme"> <img style="width: 50px" src="https://avatars.githubusercontent.com/u/22821360?s=200&v=4" alt="ayu"></a>

#### Icon Theme / Product Theme
<a href="https://github.com/miguelsolorio/vscode-symbols"> <img style="width: 50px" src="https://raw.githubusercontent.com/misolori/vscode-symbols/main/symbols.png" alt="symbols"></a>
<a href="https://github.com/miguelsolorio/vscode-fluent-icons"> <img style="width: 50px" src="https://raw.githubusercontent.com/misolori/vscode-fluent-icons/master/icon.png" alt="fluent-icons"></a>

#### My Favorite Font to Code
1. <a href="https://www.jetbrains.com/pt-br/lp/mono/" target="_blank">JetBrains Mono</a>&nbsp;A beautiful and modern mono spaced font. The best for reading codes in my opinion.
2. <a href="https://www.nerdfonts.com/font-downloads" target="_blank">JetBrainsMono Nerd Font</a>&nbsp;The Nerd Font version of JetBrains Mono for your terminal to look even better.

<br/>

## My User Settings (JSON)

```
{
  // VSCode Startup
  "workbench.startupEditor": "newUntitledFile",

  // Theme
  "workbench.colorTheme": "Ayu Mirage",

  // Font Family
  "editor.fontSize": 16,
  "editor.lineHeight": 1.8,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,

  // Font Family by Apc
  "apc.font.family": "Inter",

  // Folders
  "workbench.iconTheme": "symbols",
  "explorer.compactFolders": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,

  // Folders by Apc
  "apc.listRow": {
    "height": 24
  },

  // Product Theme
  "workbench.productIconTheme": "fluent-icons",

  // Interface
  "window.menuBarVisibility": "toggle",
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,

  // Code
  "breadcrumbs.enabled": false,
  "editor.minimap.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "editor.stickyScroll.enabled": false,
  "editor.wordWrap": "on",
  "editor.guides.bracketPairs": true,
  "editor.semanticHighlighting.enabled": false,

  // Code Save Configs
  "files.autoSave": "afterDelay",
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "always"
  },

  // Packages Configs
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.patterns": {
    "package.json": "package*, .eslint*, .prettierrc*,",
    "app.js": "app.json, babel.config.js"
  },

  // Terminal
  "terminal.integrated.env.windows": {},
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "terminal.integrated.cursorStyle": "line",

  // Terminal Font Family
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",

  // Others
  "liveServer.settings.donotShowInfoMsg": true,
  "symbols.hidesExplorerArrows": false,
}

```
