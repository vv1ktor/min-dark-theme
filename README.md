# Min Dark

A minimal VS Code theme, ported from [zed-min-theme](https://github.com/phibr0/zed-min-theme) by phibr0, which is itself inspired by Miguel Solorio's [Min Theme](https://github.com/miguelsolorio/min-theme).

![Min Dark screenshot](assets/screenshot.webp)

## Variants

| Theme | Description |
| --- | --- |
| Min Dark (Solid) | Dark, opaque title and status bars |
| Min Dark (Blurred) | Dark, translucent title and status bars |
| Min Light (Solid) | Light, opaque title and status bars |
| Min Light (Blurred) | Light, translucent title and status bars |

The Blurred variants are meant for setups that add window transparency or blur to VS Code.

## Install

> [!NOTE]
> Publishing to the VS Code Marketplace and Open VSX (used by Cursor) is in progress. Until then, install the prebuilt extension from the [latest release](https://github.com/vv1ktor/min-dark-theme/releases/latest):

```sh
curl -fsSLO https://github.com/vv1ktor/min-dark-theme/releases/latest/download/min-dark-vscode.vsix
code --install-extension min-dark-vscode.vsix
```

For Cursor, use `cursor --install-extension min-dark-vscode.vsix`. Then pick a variant: `Cmd/Ctrl+K Cmd/Ctrl+T`.

## License

[MIT](LICENSE)
