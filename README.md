# Attila

Attila is a clean, content-focused responsive theme for [Ghost](https://github.com/tryghost/ghost/). You can see it live [here](https://attila.peteramende.de/). If you find it useful and want to support its development, feel free to [tip](https://paypal.me/zutrinken) or contribute. Thank you for your support!

<img src="src/screenshot.webp" />

## Features

* Theme options
* Responsive layout
* Light and Dark Mode
* Search support
* Post reading progress
* Code highlight including line numbers
* Comments and Disqus (Theme option)
* Ghost accent color and custom fonts

## Local Fonts

This theme ships local font files in `assets/font/` and defines them in `src/sass/_fonts.scss`.
The default Ghost typography selector should remain on `Default` to avoid external CDN fonts.
Font assignment is controlled via `--gh-font-body` and `--gh-font-heading` in `src/sass/style.scss`.
Small, maintainable overrides live in `src/sass/_overrides.scss` (e.g. navigation font family).

## Listing Cards

Listing image sizing is tuned in `src/sass/_listing-cards.scss` using `clamp()` so cards stay
proportional across breakpoints without diverging from the upstream layout.
<img src="src/screenshot-listing.png" />

## Local Customizations (Non-Upstream Files)

These files contain project-specific changes to keep upstream updates low-friction and traceable:
- `src/sass/_fonts.scss`: local `@font-face` definitions for Libre Baskerville and Fira Sans.
- `assets/font/`: the corresponding local font files.
- `src/sass/_listing-cards.scss`: listing card image sizing tweaks using `clamp()` for stable proportions.
- `src/sass/_overrides.scss`: focused style overrides (e.g. UI in Fira Sans, article content in serif).

## Localization

🟢 Up to date  🟡 Missing strings

| Code | Flag | Language | Status | Translator |
| :--: | :--: | :------: | :----: | :--------: |
| `en` | 🇬🇧 | English | 🟢 | |
| `de` | 🇩🇪 | German | 🟢 | |
| `es` | 🇪🇸 | Spanish | 🟢 | [r1p](https://github.com/r1p) |
| `fr` | 🇫🇷 | French | 🟢 | [robink](https://github.com/robink), [alsyia](https://github.com/alsyia) |
| `it` | 🇮🇹 | Italian | 🟢 | [fmaida](https://github.com/fmaida), [undrivendev](https://github.com/undrivendev) |
| `no` | 🇳🇴 | Norwegian | 🟡 | [arthurnoerve](https://github.com/arthurnoerve), [oisann](https://github.com/oisann), [Givemeurcookies](https://github.com/givemeurcookies) |
| `zh` | 🇨🇳 | Chinese | 🟢 | [hao-lee](https://github.com/hao-lee), [izumiko](https://github.com/izumiko), [emperorjoker](https://github.com/emperorjoker) |
| `zh_tw` | 🇨🇳 | Chinese (Traditional) | 🟢 | [Petingo](https://github.com/Petingo)
| `id` | 🇮🇩 | Indonesian | 🟡 | [simplyeazy](https://github.com/simplyeazy), [ilhamfauzan](https://github.com/ilhamfauzan) |
| `ro` | 🇷🇴 | Romanian | 🟡 | [cdorin93](https://github.com/cdorin93) |
| `ru` | 🇷🇺 | Russian | 🟢 | [schamberg97](https://github.com/schamberg97), [atjanov](https://github.com/atjanov), [exeteres](https://github.com/exeteres) |
| `tr` | 🇹🇷 | Turkish | 🟢 | [cgrgrbz](https://github.com/cgrgrbz), [electricalgorithm](https://github.com/electricalgorithm) |
| `sv` | 🇸🇪 | Swedish | 🟢 | [martenj77](https://github.com/martenj77), [LarssonOliver](https://github.com/LarssonOliver) |
| `cs` | 🇨🇿 | Czech | 🟢 | [lunakv](https://github.com/lunakv), [rdolezel](https://github.com/rdolezel) |
| `pt` | 🇵🇹 | Portuguese | 🟡 | [matheusvanzan](https://github.com/matheusvanzan) |
| `vi` | 🇻🇳 | Vietnamese | 🟢 | [JustHmmmm](https://github.com/justhmmmm), [mastoduy](https://github.com/mastoduy) |
| `el` | 🇬🇷 | Greek | 🟡 | [thiodordelis](https://github.com/thiodordelis) |
| `dk` | 🇩🇰 | Danish | 🟢 | [jmayntzhusen](https://github.com/jmayntzhusen), [tmlmt](https://github.com/tmlmt) |
| `ar` | | Arabic | 🟢 | [pop-eax](https://github.com/pop-eax), [tayeh](https://github.com/tayeh)|
| `ca` | | Catalan | 🟡 | [arthurnoerve](https://github.com/arthurnoerve) |
| `lt` | 🇱🇹 | Lithuanian | 🟡 | [arthurnoerve](https://github.com/arthurnoerve) |
| `nl` | 🇳🇱 | Dutch | 🟡 | [gkdp](https://github.com/gkdp) |
| `pl` | 🇵🇱 | Polish | 🟢 | [filipolszewski](https://github.com/filipolszewski), [MrBoombastic](https://github.com/mrboombastic) |
| `eo` | | Esperanto | 🟡 | [ebanDev](https://github.com/ebanDev) |
| `ga` | | Galego | 🟢 | [r1p](https://github.com/r1p) |
| `uk` | 🇺🇦 | Ukrainian | 🟢 | [Rakanskiy](https://github.com/rakanskiy), [krupenik](https://github.com/krupenik), [vadimkin](https://github.com/vadimkin) |
| `ja` | 🇯🇵 | Japanese | 🟢 | [emperorjoker](https://github.com/emperorjoker) |
| `fa` | | Farsi | 🟢 | [ItsAminZamani](https://github.com/ItsAminZamani) |
| `fi` | 🇫🇮 | Finnish | 🟢 | [murtoM](https://github.com/murtoM) |
| `th` | 🇹🇭 | Thai | 🟢 | [GmBeHappy](https://github.com/GmBeHappy) |
| `hu` | 🇭🇺 | Hungarian | 🟢 | [ferivoq](https://github.com/ferivoq) |
| `ge` | 🇬🇪 | Georgian | 🟢 | [kiknaio](https://github.com/kiknaio) |
| `gd` | 🏴󠁧󠁢󠁳󠁣󠁴󠁿 | Scottish Gaelic | 🟢 | [angeidheal](https://github.com/angeidheal) |
| `pt_br` | 🇧🇷 | Portuguese (Brazilian) | 🟢 | [jobdiogenes](https://github.com/jobdiogenes) |

## Development

If you use nvm, a current Node.js LTS release (18 or 20) is recommended:
````bash
nvm install 18
nvm use 18
````
Install [Grunt](https://gruntjs.com/getting-started/):
````bash
npm install -g grunt-cli
````
Install dependencies:
````bash
npm install
````
Alternatively, you can do a clean, lockfile-based install (especially on CI):
````bash
npm ci
````
This installs exact versions from `package-lock.json` into a fresh `node_modules/` folder.
Run it once per environment, or again after dependency or lockfile changes.
Build project:
````bash
grunt build
````
The compress task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.
````bash
grunt compress
````
After running it, the zip is available at `dist/attila.zip`.
You can also run Grunt without a global install:
````bash
npx grunt build
npx grunt compress
````
If install steps fail with `node-gyp` errors, you may need to point npm at a local Python 3:
````bash
export npm_config_python="/opt/homebrew/opt/python@3.11/bin/python3.11"
````
## ⚖️ Copyright & License

Copyright (C) 2015-2025 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/attila/blob/master/LICENSE).
