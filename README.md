# Saklash Theme for [Windows Terminal](https://github.com/microsoft/terminal)

> Popular Vscode theme for [Windows Terminal](https://github.com/microsoft/terminal).

## Install

- Download using the [GitHub .zip download](https://github.com/SahilChandravanshi/Saklash-Theme-WT/archive/refs/heads/main.zip) option.
- Start Windows Terminal and click on the down arrow symbol `˅` from menu bar. This will open a drop down menu from which select Settings option. Alternatively use `Ctrl + ,` to open Settings directly.
- In the `settings.json` settings file for Windows Terminal, find the `schemes` section and paste the content of `Saklash-Theme-WT (GunMetal).json` , `Saklash-Theme-WT (Oceanic).json` , `Saklash-Theme-WT (Plain).json` , `Saklash-Theme-WT (Soothing).json`.

Example:

```json
"schemes": [
{
  "name": "Saklash-Theme-Soothing",
  "background": "#1f2023",
  "foreground": "#bcb28d",
  "cursorColor": "#bcb28d",
  "black": "#000000",
  "blue": "#2b7ed9",
  "brightBlack": "#666666",
  "brightBlue": "#5ca9ff",
  "brightCyan": "#27c5ec",
  "brightGreen": "#27ec9d",
  "brightPurple": "#de75de",
  "brightRed": "#ff5555",
  "brightWhite": "#cccccc",
  "brightYellow": "#ffff58",
  "cyan": "#07aed7",
  "green": "#22b87f",
  "purple": "#f248f2",
  "red": "#ee2626",
  "white": "#cccccc",
  "yellow": "#f5f525",
  "selectionBackground": "#535353",
  "inactiveSelectionBackground": "#535353"
}
]
```

#### Activate

Once the color scheme has been defined, it's time to enable it. Find the `profiles` section and add a `colorScheme` value to the default profile.

Example:

```json
"profiles": {
    "defaults": {
        "colorScheme" : "Saklash-Theme-Soothing"
    }
}
```

- You can also set color theme from terminal appearance settings after defining the theme in settings.json

## License

[MIT License](./LICENSE)
