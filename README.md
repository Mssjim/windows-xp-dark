# Windows XP Dark Luna Theme for Visual Studio Code

> A theme extension for [Visual Studio Code](https://code.visualstudio.com/) based on the Windows XP "Luna" theme and the intelij darcula theme.

<p align="center">
  <img alt="" src="https://raw.githubusercontent.com/Mssjim/windows-xp-dark/main/preview.jpg"/>
</p>

### [Test it online!](https://vscode.dev/theme/mssjim.windows-xp-dark) 

## Install

### From VS Code

1. Select the extension tab.
2. Search for `Windows XP Dark Luna Theme`.
3. Click `Install`.

### From the Marketplace

1. Go to the [Windows XP Dark Luna Theme](https://marketplace.visualstudio.com/items?itemName=mssjim.windows-xp-dark) page on the Visual Studio Code Marketplace.
2. Click `Install`.

### From the Command Line

Run the following command:

```sh
code --install-extension mssjim.windows-xp-dark
```

## Activate

1. Click the gear icon in the lower left corner of the window.
2. Select `Color Theme`.
3. Select `Windows XP Dark Luna`.

## Want a Light Theme or Icons Too?

Check out the [vscode-windows-xp-theme](https://github.com/sinedied/vscode-windows-xp-theme) made by [sinedied](https://github.com/sinedied).

## Features

- A dark theme inspired by Windows XP's "Luna" theme.
- A color scheme derived from the intelij darcula theme.

## Override this theme

You can override this theme by creating a new theme file in your user settings. For example, to change the color of comments, you can add the following to your `settings.json` file:

```json
{
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "foreground": "#00FF00"
        }
      }
    ]
  }
}
```

## Credits

This theme was inspired by the default Windows XP "Luna" theme. The code editor color scheme was derived from the [vscode-windows-xp-theme](https://github.com/sinedied/vscode-windows-xp-theme) theme by [sinedied](https://github.com/sinedied).

## Contributing

If you would like to contribute to this project, please open an issue or a pull request.

## License

[MIT](./LICENSE)