# White Winter

[![Version](https://vsmarketplacebadge.apphb.com/version-short/jker.white-winter.svg)](https://marketplace.visualstudio.com/items?itemName=jker.white-winter)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/jker.white-winter.svg)](https://marketplace.visualstudio.com/items?itemName=jker.white-winter)

**White Winter** is an almost pure white VS Code theme with plain color customization. The use of bold text and light accents was the principal idea.

![Screenshot](https://raw.githubusercontent.com/guidolee/jker-white-winter/master/screenshot.png)

I'm using [Victor Mono](https://rubjo.github.io/victor-mono/) font and [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) for icons/folders.

## VS Code config

I've added some configuration to visualize this as minimalistic as posible. Feel free to change these settings

```js
{
    // ...
    "editor.fontSize": 14,
    "editor.fontLigatures": true,
    "editor.lineHeight": 20,
    "editor.letterSpacing": 0.3,
    "editor.minimap.renderCharacters": false,
    "editor.minimap.maxColumn": 200,
    "editor.minimap.showSlider": "always",
    "editor.tabSize": 4,
    "window.zoomLevel": 0,
    "workbench.colorTheme": "White Winter",
    "workbench.iconTheme": "material-icon-theme",
    "material-icon-theme.folders.color": "#777777",
    "material-icon-theme.activeIconPack": "react",
    "material-icon-theme.folders.theme": "classic",
    "material-icon-theme.showUpdateMessage": false,
    "material-icon-theme.hidesExplorerArrows": true,
    "material-icon-theme.showWelcomeMessage": false,
    "material-icon-theme.showReloadMessage": false,
}
```

## License

MIT
