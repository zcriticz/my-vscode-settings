<div align="center">
   <img style="width: 80px" src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/visual-studio-code-icon.png"></img><br/><br/>
   <h1>
      <strong>My VSCode Settings!</strong>
   </h1>

   <h4><a href="https://code.visualstudio.com" target="_blank">Visual Studio Code</a> is without a doubt the most popular IDE today, especially essential for web developers. Here I list    my main settings.</h4>
</div>

<br/>
<br/>

## Extensions List
1. <a href="https://github.com/topics/bookmarks" target="_blank">Bookmarks:</a>&nbsp;Excellent for making quick notes within the code.
2. <a href="https://github.com/aaron-bond/better-comments" target="_blank">Better Comments:</a>&nbsp;A powerful way to add custom comments to your codes.
3. <a href="https://github.com/topics/color-highlight" target="_blank">Color Highlight:</a>&nbsp;An extension that improves the reading of your color markings in CSS..
4. <a href="https://github.com/willofindie/vscode-cssvar" target="_blank">CSS Var Complete:</a>&nbsp;Essentially it does the same thing as Color Highlight, but with color variables.
5. <a href="https://github.com/usernamehw/vscode-error-lens" target="_blank">Error Lens:</a>&nbsp;Improve highlighting of errors, warnings and other language diagnostics.
6. <a href="https://github.com/prettier/eslint-plugin-prettier" target="_blank">EsLint/Prettier:</a>&nbsp;While Eslint makes a detailed invoice to find possible errors involving JavaScript, Prettier identifies and standardizes the code in a quick and visually pleasing way.
7. <a href="https://github.com/usernamehw/vscode-error-lens" target="_blank">Git Leans:</a>&nbsp;A real-time commit history so you always know who made certain changes to your code.
   
<br/>

### Live Code Extensions
1. <a href="https://github.com/ritwickdey/vscode-live-server" target="_blank">Live Server:</a>&nbsp;Launch a development local Server with live reload feature for static & dynamic pages.
2. <a href="https://github.com/microsoft/vscode-livepreview" target="_blank">Live Preview:</a>&nbsp;An extension that hosts a local server for you to preview your web projects on!
3. <a href="https://github.com/microsoft/live-share" target="_blank">Live Share:</a>&nbsp;A code sharer to work on collaborative projects involving a team of developers!

<br/>

#### Note
The extensions above are the ones I consider essential for any web developer. However, VSCode offers a huge variety of extensions that you can try and use according to your needs.

<br/>
<br/>

## My Favorite Customizations

#### Theme & Icon Theme
<a href="https://github.com/ayu-theme"> <img style="width: 50px" src="https://avatars.githubusercontent.com/u/22821360?s=200&v=4" alt="ayu"></a>
<a href="https://github.com/vscode-icons/vscode-icons?tab=readme-ov-file"> <img style="width: 50px" src="https://raw.githubusercontent.com/vscode-icons/vscode-icons/master/images/logo@3x.png" alt="symbols"></a>

<br/>

#### My Favorite Font to Code
1. <a href="https://github.com/microsoft/cascadia-code" target="_blank">Cascadia Code</a>&nbsp;The best font for reading code in my opinion!
2. <a href="https://www.nerdfonts.com/font-downloads" target="_blank">CaskaydiaCove Nerd Font</a>&nbsp;The Nerd Font version of Cascadia Code for your terminal to look even better.
   
<br/>

#### Others Customizations
<a href="https://github.com/drcika/apc-extension?tab=readme-ov-file"> <img style="width: 50px" src="https://drcika.gallerycdn.vsassets.io/extensions/drcika/apc-extension/0.3.9/1709478442827/Microsoft.VisualStudio.Services.Icons.Default" alt="apc-customize"></a><br/>

<p>Apc Customize UI++ is a powerful tool capable of changing Electron properties (VSCode technology) and thus creating various customizations to the user's taste.</p>

<a href="https://github.com/hikarin522/GlassIt-VSC"> <img style="width: 50px" src="https://drcika.gallerycdn.vsassets.io/extensions/drcika/apc-extension/0.3.9/1709478442827/Microsoft.VisualStudio.Services.Icons.Default" alt="apc-customize"></a><br/>

<p>GlassIt-VSC is an extension that makes your VSCode background completely transparent.</p>

<br/>
<br/>

## My User Settings (JSON)

```
{
  // Zoom
  "window.zoomLevel": 1,

  // VSCode Startup
  "workbench.startupEditor": "newUntitledFile",

  // Theme
  "workbench.colorTheme": "Ayu Dark",

  // Font Family
  "editor.fontSize": 16,
  "editor.lineHeight": 1.8,
  "editor.fontFamily": "Cascadia Code",
  "editor.fontLigatures": true,

  // Folders
  "workbench.iconTheme": "vscode-icons",
  "explorer.compactFolders": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,

  // Folders by Apc
  "apc.listRow": {
    "height": 24
  },

  // Interface
  "window.menuBarVisibility": "toggle",
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
  "editor.cursorBlinking": "expand",

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

  // Terminal Font 16y
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.fontFamily": "CaskaydiaCove Nerd Font",

  // Others
  "liveServer.settings.donotShowInfoMsg": true,
  "glassit.alpha": 220
}

```
<br/>
<br/>

## Final Result 📷
![image](https://github.com/zcriticz/my-vscode-settings/assets/111531548/cac0e318-dbad-42ca-b212-e451aed9693c)
