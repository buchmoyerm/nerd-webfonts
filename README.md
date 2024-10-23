# nerd-webfonts

A simple css for adding https://github.com/ryanoasis/nerd-fonts to chrome's secure shell app

## Usage

In the **secure shell app** settings set the following

*   Set **font-family**: "DejaVu Sans Mono Nerd", monospace
*   Set **Custom CCS (URI)**:
    https://raw.githubusercontent.com/buchmoyerm/nerd-webfonts/main/NerdFonts.css

For **Crosh Window**

* Start crosh window then press `Ctrl+Shift+J`

```
term_.prefs_.set('font-family', '"DejaVu Sans Mono Nerd", monospace');
term_.prefs_.set('user-css', 'https://raw.githubusercontent.com/buchmoyerm/nerd-webfonts/main/NerdFonts.css');
```

## Supported fonts to use for font-family

* `DejaVu Sans Mono Nerd`
* `JetBrains Mone Nerd`
* `Source Code Pro Nerd`
* `Ubuntu Mono Nerd`
