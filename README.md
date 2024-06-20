[screenshot]:       https://saltssaumure.github.io/template-discord-theme/preview/preview.avif
[light]:            https://saltssaumure.github.io/template-discord-theme/preview/light.avif
[dark]:             https://saltssaumure.github.io/template-discord-theme/preview/dark.avif

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length

[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-css-dl]:    https://img.shields.io/github/downloads/Saltssaumure/template-discord-theme/Template.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/template-discord-theme/net.saltssaumure.Template.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/Saltssaumure/template-discord-theme?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/Saltssaumure/template-discord-theme
[issues]:           https://github.com/Saltssaumure/template-discord-theme/issues
[license]:          https://github.com/Saltssaumure/template-discord-theme/blob/main/LICENSE
[.theme.css]:       https://github.com/Saltssaumure/template-discord-theme/blob/main/Template.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Template "Replugged store page"
[release-css-gh]:   https://github.com/Saltssaumure/template-discord-theme/releases/latest/download/Template.theme.css "Get latest release"
[release-asar-gh]:  https://github.com/Saltssaumure/template-discord-theme/releases/latest/download/net.saltssaumure.Template.asar "Get latest release"

# Template Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![CSS GitHub downloads][shield-css-dl]][release-css-gh]
[![Asar GitHub downloads][shield-asar-dl]][release-asar-gh]
[![Total repository size][shield-repo-size]][github]

***A template Discord theme for multiple client mod support.***

![Template applied to Discord][screenshot]

|          Light mode           |          Dark mode          |
| :---------------------------: | :-------------------------: |
| ![Template light mode][light] | ![Template dark mode][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
<details><summary>Click to expand</summary>

1. Download `Template.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details><summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Template.asar`:
    - [GitHub][release-asar-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details><summary>Click to expand</summary>

#### Local
1. Download `Template.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltssaumure.github.io/template-discord-theme/Template.theme.css`
</details>

## Customisation

| Variable           | Description                    | Valid values                    | Default value |
| ------------------ | ------------------------------ | ------------------------------- | ------------- |
| `--temp-bg-color`  | Background colour              | Any [colour][css-color].        | `#000`        |
| `--temp-bg-height` | Background height              | Any [length][css-length].       | `100vh`       |
| `--temp-scanline`  | &#9936; Moving scanline on/off | `block` (on) or `none` (off).   | `block`       |
| `--temp-flicker`   | &#9888; Screen flicker on/off  | `flicker` (on) or `none` (off). | `none`        |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
<details><summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details><summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-20 of [`Template.theme.css`][.theme.css].
4. Edit the variable values and save.
</details>

### Vencord
<details><summary>Click to expand</summary>

#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `Template.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`Template.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
Copyright (c) 2024 Saltssaumure

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Affero General Public License][license] for more details.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].