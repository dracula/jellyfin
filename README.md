<h3 align="center">
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
    Catppuccin for <a href="https://jellyfin.org">Jellyfin</a>
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/adamperkowski/jellyfin/stargazers"><img src="https://img.shields.io/github/stars/adamperkowski/jellyfin?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/template/issues"><img src="https://img.shields.io/github/issues/adamperkowski/jellyfin?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/adamperkowski/jellyfin/contributors"><img src="https://img.shields.io/github/contributors/adamperkowski/jellyfin?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
    <img src="/assets/preview.webp"/>
</p>

## Previews

<details>
    <summary>🌻 Latte</summary>
    <img src="/assets/latte.webp"/>
</details>
<details>
    <summary>🪴 Frappé</summary>
    <img src="/assets/frappe.webp"/>
</details>
<details>
    <summary>🌺 Macchiato</summary>
    <img src="/assets/macchiato.webp"/>
</details>
<details>
    <summary>🌿 Mocha</summary>
    <img src="/assets/mocha.webp"/>
</details>

## Usage

1. Copy the theme import rule:
    ```css
    @import url('https://adamperkowski.github.io/jellyfin/theme.css');
    ```
2. Open settings, navigate to Display and paste the CSS into the section called "Custom CSS code"
3. Copy your preferred flavor's import rule and paste it **after** the theme import:
    ```css
    /* 🌻 Latte */
    @import url('https://adamperkowski.github.io/jellyfin/latte.css');
    /* 🪴 Frappé */
    @import url('https://adamperkowski.github.io/jellyfin/frappe.css');
    /* 🌺 Macchiato */
    @import url('https://adamperkowski.github.io/jellyfin/macchiato.css');
    /* 🌿 Mocha */
    @import url('https://adamperkowski.github.io/jellyfin/mocha.css');
    ```
4. Press save and you're done!

## Customization

The accent color can be overrided by adding the following **after** the imports:
```css
:root {
    --main-color: var(--mauve);
}
```

<details>
    <summary>Preview</summary>
    <img src="/assets/mauve.webp"/>
</details>

There is also an everything-rounded extension available:
```css
@import url('https://adamperkowski.github.io/jellyfin/rounding.css');
```
<details>
    <summary>Preview</summary>
    <img src="/assets/rounding0.webp"/>
    <img src="/assets/rounding1.webp"/>
</details>

## 💝 Thanks to

- [Isabel](https://github.com/isabelroses)
- [Adam](https://github.com/adamperkowski)

&nbsp;

<p align="center">
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
    Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
    <a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
