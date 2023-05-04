[light]:            https://user-images.githubusercontent.com/29710355/231909647-72871e7f-8763-4174-9c71-5f1bb7d401bc.png
[dark]:             https://user-images.githubusercontent.com/29710355/231909520-b24c4301-2d90-4c6c-9e5d-ca9ce20e3ba6.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi
[ko-fi]:            https://ko-fi.com/saltssaumure "Any amount is much appreciated!"

[shield-total-dl]:  https://img.shields.io/github/downloads/saltssaumure/template-discord-theme/total?color=purple&label=Total%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/saltssaumure/template-discord-theme/latest/net.saltssaumure.Template.asar?color=purple&label=Replugged%20installs&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/saltssaumure/template-discord-theme?style=flat-square "Total size"

[license]:          https://github.com/Saltssaumure/template-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/template-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/template-discord-theme/blob/main/Template.theme.css

[release-gh]:       https://github.com/Saltssaumure/template-discord-theme/releases/latest "Latest release"
[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/install?identifier=Saltssaumure/template-discord-theme&source=github "Replugged addon installer"

# Template Discord Theme
[![Donate via ko-fi][shield-donate]][ko-fi]
[![Total downloads][shield-total-dl]][release-gh]
[![Replugged installs][shield-asar-dl]][release-gh]
![Total size][shield-repo-size]

***A something something Discord theme.***

| Light mode                                                  | Dark mode                                                 |
| ----------------------------------------------------------- | --------------------------------------------------------- |
| ![Screenshot of Temp light mode applied to Discord][light] | ![Screenshot of Temp dark mode applied to Discord][dark] |

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the theme file:
    - [GitHub][release-gh]
    - [BD Store][release-bd]
3. Place theme file in BetterDiscord's theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [GitHub][release-gh]
    - [Installer][release-rp]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/template-discord-theme/Template.theme.css`

## Customisation

| Description       | Variable name     | Valid values               | Default value |
|-------------------|-------------------|----------------------------|---------------|
| Background colour | `--temp-bg-color` | Any [colour][css-color]. | #000          |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste line 30-36 of [`Template.theme.css`](https://github.com/Saltssaumure/template-discord-theme/blob/main/Template.theme.css).
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste line 30-36 of [`Template.theme.css`](https://github.com/Saltssaumure/template-discord-theme/blob/main/Template.theme.css).
4. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
