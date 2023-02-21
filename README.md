# James Q Quick 🏃

About this theme, and some of the considerations made while creating it (as well as how to create it should you want to make your own): https://selfteach.me/blog/creating-a-vs-code-theme/

![]()

## Installation

1. Install **[Visual Studio Code](https://code.visualstudio.com/)**
2. Launch Visual Studio Code
3. Choose **Extensions** from menu
4. Search for **James Q Quick**
5. Click Install to install it
6. Click Reload to reload the Code
7. From the menu bar click: **Code > Preferences > Theme > Color Theme > James Q Quick**

## Separate the Editor from the Sidebar

```json
"workbench.colorCustomizations": {
  "[Night Owl]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "editorGroup.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  },
  "[Night Owl (No Italics)]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "editorGroup.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  }
},
```

## Preferences shown in the preview

The font in the preview image is Dank Mono, [available here](https://dank.sh/). Editor settings to activate font ligatures:

```json
"editor.fontFamily": "Dank Mono",
"editor.fontLigatures": true,
```

The preview image is using [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer), a really cool extension that highlights matching brackets. This can help reduce unwanted errors.

I use this setting:

```json
"bracketPairColorizer.forceIterationColorCycle": true,
```

![]()

## Miscellaneous

This is my first foray into creating a theme, so if you see something amiss, please feel free to file an issue! I'm sure there are things I missed.

Any relevant changes for each version are documented in the changelog. Please update and check the changelog before filing any issues, as they may have already been taken care of.

## Acknowledgements

This theme stands on the shoulders on those that have gone before me, borrowing from [Wes Bos's Cobalt2 theme](https://github.com/wesbos/cobalt2-vscode) and [Sarah Drasner's Night Owl theme.](https://github.com/sdras/night-owl-vscode-theme)
