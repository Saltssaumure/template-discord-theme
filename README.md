[light]:            https://user-images.githubusercontent.com/29710355/231909647-72871e7f-8763-4174-9c71-5f1bb7d401bc.png
[dark]:             https://user-images.githubusercontent.com/29710355/231909520-b24c4301-2d90-4c6c-9e5d-ca9ce20e3ba6.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/Saltssaumure/template-discord-theme/Template.theme.css?color=purple&label=BD%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/template-discord-theme/net.saltssaumure.Template.asar?color=purple&label=Replugged%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/Saltssaumure/template-discord-theme?style=flat-square "Total size"

[license]:          https://github.com/Saltssaumure/template-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/template-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/template-discord-theme/blob/main/Template.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-bd-gh]:    https://github.com/Saltssaumure/Squared/releases/latest/download/Template.theme.css "Latest release"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Template "Replugged store page"
[release-rp-gh]:    https://github.com/Saltssaumure/Squared/releases/latest/download/net.saltssaumure.Template.asar "Latest release"

# Template Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
![Total size][shield-repo-size]

***A something something Discord theme.***

| Light mode                                                 | Dark mode                                                |
| ---------------------------------------------------------- | -------------------------------------------------------- |
| ![Screenshot of Temp light mode applied to Discord][light] | ![Screenshot of Temp dark mode applied to Discord][dark] |

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the theme file:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
3. Place theme file in the theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [Replugged store][release-rp]
    - [GitHub][release-rp-gh]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/template-discord-theme/Template.theme.css`

## Customisation

| Description       | Variable name     | Valid values             | Default value |
| ----------------- | ----------------- | ------------------------ | ------------- |
| Background colour | `--temp-bg-color` | Any [colour][css-color]. | #000          |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste line 30-36 of [`Template.theme.css`][.theme.css].
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste line 30-36 of [`Template.theme.css`][.theme.css].
4. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
