# Bootstrap 4 with CDN Boilerplate

<!-- markdownlint-disable MD037 MD024 -->

Ever been trying to start with a bootstrap template?

This is normally not an issue but I found it tedious with using `!` then add all CSS with font-awesome and jquery etc.

This extension will solve the issue for you with a simple `!bcdn` + `TAB` and your up and running with a full template

The extension also supports [Bootswatch](https://bootswatch.com/) themes

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/eventyret.bootstrap-4-cdn-snippet?style=for-the-badge&logo=visual-studio-code)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/eventyret.bootstrap-4-cdn-snippet?style=for-the-badge&logo=visual-studio-code)
![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/eventyret.bootstrap-4-cdn-snippet?style=for-the-badge&logo=visual-studio-code)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/eventyret.bootstrap-4-cdn-snippet?style=for-the-badge&logo=visual-studio-code)

![License](https://img.shields.io/github/license/Eventyret/vscode-bcdn?style=for-the-badge&logo=github)
![Maintenance](https://img.shields.io/maintenance/yes/2020?style=for-the-badge&logo=github)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge&logo=github)](https://github.com/Eventyret/vscode-bcdn/issues)

![Gif](https://i.imgur.com/6RmNOwu.gif)

## Shortcuts / Commands

### Main Commands

| **Command** | **Help Text **                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------------- |
| !bcdn       | Creates an Bootstrap 4 starter template. With Jquery, popper.js and Font-Awesome 5                |
| !bcdn5      | Creates an Bootstrap 5 starter template. With popper.js and Font-Awesome 5                        |
| !bcss       | Creates an Bootstrap 4 starter template. Only with CSS (No Jquery) and Font-Awesome 5             |
| !b3cdn      | Creates an Bootstrap 4 starter template. With Jquery, Font-Awesome 4.7                            |
| !bcdnajax   | Creates an Bootstrap 4 starter template. With Jquery, popper.js and Font-Awesome 5 (Ajax support) |
| !bcdnjs     | Creates all the script links for JS (Links only)                                                  |
| !bcdncss    | Creates all the style links for CSS (Links only)                                                  |

### Bootswatch Template variations

| **Command**    | **Help Text **                                                    |
| -------------- | ----------------------------------------------------------------- |
| !bcdncerulean  | Creates an Bootstrap 4 Template with Cerulean Bootswatch Colors   |
| !bcdncosmo     | Creates an Bootstrap 4 Template with Cosmo Bootswatch colors      |
| !bcdncyborg    | Creates an Bootstrap 4 Template with Cyborg Bootswatch colors     |
| !bcdndarkly    | Creates an Bootstrap 4 Template with Darkly Bootswatch colors     |
| !bcdnflatly    | Creates an Bootstrap 4 Template with Flatly Bootswatch colors     |
| !bcdnjournal   | Creates an Bootstrap 4 Template with Journal Bootswatch colors    |
| !bcdnlitera    | Creates an Bootstrap 4 Template with Litera Bootswatch colors     |
| !bcdnlumen     | Creates an Bootstrap 4 Template with Lumen Bootswatch colors      |
| !bcdnlux       | Creates an Bootstrap 4 Template with Lux Bootswatch colors        |
| !bcdnmateria   | Creates an Bootstrap 4 Template with Materia Bootswatch colors    |
| !bcdnminty     | Creates an Bootstrap 4 Template with Minty Bootswatch colors      |
| !bcdnpulse     | Creates an Bootstrap 4 Template with Pulse Bootswatch colors      |
| !bcdnsandstone | Creates an Bootstrap 4 Template with Sandstone Bootswatch colors  |
| !bcdnsimplex   | Creates an Bootstrap 4 Template with Simplex Bootswatch colors    |
| !bcdnsketchy   | Creates an Bootstrap 4 Template with Sketchy Bootswatch colors    |
| !bcdnslate     | Creates an Bootstrap 4 Template with Slate Bootswatch colors      |
| !bcdnsolar     | Creates an Bootstrap 4 Template with solar Bootswatch colors      |
| !bcdnspacelab  | Creates an Bootstrap 4 Template with Space Lab Bootswatch colors  |
| !bcdnsuperhero | Creates an Bootstrap 4 Template with Super Hero Bootswatch colors |
| !bcdnunited    | Creates an Bootstrap 4 Template with United Bootswatch colors     |
| !bcdnyeti      | Creates an Bootstrap 4 Template with Yeti Bootswatch colors       |

### Forms and misc Classes

| Command      | Help Text                                      |
| ------------ | ---------------------------------------------- |
| !bsnav       | Default Navigation for Bootstrap               |
| !bsnavcenter | Create a center logo navbar                    |
| !bsnavc      | Class to Align Navigation Center               |
| !bsnavr      | Class to Align Navigation Right                |
| !bsnavtab    | Class to Use Tab Style Navigation              |
| !bsnavsticky | Default Sticky Navigation for Bootstrap        |
| !bsnavpill   | Class to Use Pill Style Navigation             |
| !bsnavdd     | Default Dropdown Navigation (Requires Jquery)  |
| !bsnavj      | Class to Justify Navigation                    |
| !bfg         | Bootstrap Form Group parent element            |
| !bfc         | Bootstrap Form Control                         |
| !bsform      | Bootstrap form with input, select and textarea |

## Release Notes

| 🚀  | New Feature |
| --- | ----------- |
| ✅  | Minor Fix   |
| 🐛  | Bugfix      |

### [1.13.0]

### Added

- Upgraded Bootstrap from `5.0.1` to `5.1.0` ✅
- Upgraded Bootswatch from `5.0.1` to `5.1.0` ✅
- Upgraded Font Awesome to `5.15.14`

### Fixed

- Fixed some minor spelling and layout issues in readme

### [1.12.0]

### Added

- Upgraded Bootstrap 5-beta1 to 5.0.1` ✅
- Upgraded Font Awesome to `5.15.13`
- Added new bootswatch 5 themes 🚀

### [1.11.0]

### Added

- Upgraded Bootstrap 4.5.3 Alpha to 4.6.0` ✅
- Upgraded Font Awesome to `5.15.2`

### [1.10.0]

### Added

- Upgraded Bootstrap 5 Alpha to `Beta 1` ✅
- Upgraded Font Awesome to `5.15.1` (This introduces the free covid-19 icons) ✅

### [1.9.0]

### Added

- Upgraded Bootstrap 5 Alpha to `Alpha 2` ✅
- Upgraded Font Awesome to `5.15.0` (This introduces the free covid-19 icons) ✅
- Added new center bootstrap command `!bsnavcenter` (This will create a centered brand navbar) 🚀

### [1.8.2]

### Added

- Upgraded Bootstrap to `4.5.2` ✅

### [1.8.1]

### Added

- Upgraded Font Awesome to `5.14.0` ✅

### Fixed

- Upgraded `npm` dependency to `6.14.6` ✅

### [1.8.0]

### Added

- Added bootstrap 5 alpha support with new command `!bcdn5` 🚀
- Upgraded Font Awesome to `5.13.1` ✅

### Removed

- Removed jQuery as dependancy for Bootstrap 5 ✅

### [1.7.0]

### Added

- Added Meta Description element to initial block. 🚀 / Thanks [@betahope](https://github.com/BetaHope)

### [1.6.1]

### Fixed

- Fixed spelling mistake in the title of the plugin 🐛

### [1.6.0]

### Added

- Created a brand New Icon 🚀
- New Screencast 🚀
- New Shields added 🚀
- Added bug report template for Github 🚀
- Added feature request template for Github 🚀

### [1.5.0]

### Added

- Upgraded bootstrap to `4.5.0` 🚀
- Upgraded bootstrap to `3.5.1` ✅
- Upgraded bootstrap to `3.5.1` ✅
- Added sticky navbar with `!bsnavsticky` 🚀

### [1.4.1]

### Fixed

- Reverted jQuery to v.3.4.1 for compatibility issues with current Bootstrap version. ✅

### [1.4.0]

### Added

- Moved the paths for `style.css`to be a better standard now it will be `assets/css/style.css`
- Added support for Django templates `django-html` support requested in #15 🚀
- Added support for jinja templates `jinja-html` support requested in #15 🚀
- Updated jQuery to `3.5.0` ✅
- Updated popper.js to `1.16.1` ✅
- Updated Font Awesome to `5.13.0` ✅
- Added support for github actions 🚀

### Fixed

- Fixed an issue with the README with markdown errors.

### Removed

- Removed Azure-pipeline

### [1.3.0]

### Added

- Updated Bootstrap to `4.4.1` ✅
- Updated PopperJS to `1.16.0` ✅
- Added `!bcdncss` to add latest bootstrap and font awesome styles 🚀
- Emojis for better readability in changelog and README 🚀 😍
- Added [Bootswatch](https://bootswatch.com/) themes to be added with `!bcdnTHEMENAME` eg `!bcdnyeti` will give the Yeti bootswatch theme 🚀

### Fixed

- Fixed an issue where the wrong command was written in the README. 🐛
- Changed the structure of the tables in the readme to make it easier to read 🚀
- Added and removed comma structure in `package.json` as this was broken

### [1.2.3]

### Fixed

- Fixed a problem with versions and npm ✅

### [1.2.1]

### Added

- Added `bcdnjs` to the table in README 🚀
- Updated Font Awesome 5 to `5.11.2` ✅

### [1.2.0]

### Added

- Added `bcdnjs` this will give you the ability to just insert all the javascript at the footer. 🚀
- Updated FontAwesome 5 to `5.10.0-11` ✅

### [1.1.9]

### Added

- Updated FontAwesome 5 to `5.8.2` ✅
- Updated Jquery to `3.4.1` ✅
- Updated popper.js to `1.50.0` ✅

### Fixed

- Changed FontAwesome 4 to 5 on Bootstrap 3 Starter Template 🚀

### [1.1.8]

### Fixed

- Fixed issues with updating and publishing 🐛

### [1.1.7]

### Added

- Added AJAX Support with new command `!bcdnajax` - Thanks to [@alejandrogarciapalomo](https://github.com/alejandrogarciapalomo) 🚀

### [1.1.6]

### Added

- Updated Bootstrap to version `4.3.1` - Thanks to [@alejandrogarciapalomo](https://github.com/alejandrogarciapalomo) ✅
- Updated Fontawesome to version `5.7.2` - Thanks to [@alejandrogarciapalomo](https://github.com/alejandrogarciapalomo) ✅

### [1.1.5]

#### Fixed

Fixed some issues with readme 🐛

### [1.1.4]

#### Added

- Updated Bootstrap to version `4.2.1` ✅
- Updated Fontawesome to version `5.7.0` ✅
- Added Bootstrap 3 Template `!b3cdn` for the legacy people that wanted it. 🚀
- Added full form with input, select and textarea. #9 - Thanks to [@wings30306](https://github.com/Wings30306) 🚀

#### Fixed

- Added a license #8 - This plugin now has a GNU GENERAL PUBLIC LICENSE. 🚀
- Fixed the table in readme looking wrong. ✅

### [1.1.3]

#### Removed

- Removed Django and vue HTML as it was not working correctly 🐛

### [1.1.2]

#### Fixed

- Fixed where the javascript was `.map` file 🐛

### [1.1.1]

#### Fixed

- Fixed some minor spelling errors in readme and other files 🐛

### [1.1.0]

#### Added

- Added Support for JSX / ReactJS 🚀
- Added Support for Vue HTML 🚀
- Added Font Awesome 5 Free 🚀

#### Removed

- Removed Font Awesome 4.7 ✅

### [1.0.8]

#### Added

- Updated Bootstrap CSS to `4.1.2` 🚀
- Updated Bootstrap JS to `4.1.2` 🚀

### [1.0.7]

#### Added

- Added icon to plugin 🐛

### [1.0.6]

#### Fixed

- Space in Url for bootstrap. #5 🐛
- Fixed popper.js unexpected token error. #6 🐛
- Problems with badges not displaying. 🐛

#### Removed

- Removed Travis CI Build testing for now ✅

### [1.0.5]

#### Fixed

- Double text in readme. 🐛

### [1.0.4]

#### Added

- Readme badges 🚀

#### Fixed

- Fixed error in package.json version 🐛

### [1.0.3]

#### Added

- Added Navigation snippets - Thanks to [@karnthis](https://github.com/karnthis) #1 🚀
- Added Bootstrap4 CDN without jQuery - Thanks to [@nartc](https://github.com/nartc) #2 🚀
- Added 2 basic form snippets: form-group and form-control Thanks to [@nartc](https://github.com/nartc) #3 🚀
- Updated readme with table of commands. ✅
- Added travis CI testing (WIP) 🚀

#### Fixed

- Fixed spelling errors. 🐛

### [1.0.2]

- Minor adjustments to files ✅

### [1.0.0]

Initial release of Bootstrap 4 with CDN Boilerplate 😍 🚀

## Known Issues

No known issues so far.

## Credits

- [@karnthis](https://github.com/karnthis)
- [@nartc](https://github.com/nartc)
- [@wings30306](https://github.com/Wings30306)
- [@gbrachetta](https://github.com/GBrachetta)
- [@betahope](https://github.com/BetaHope)
