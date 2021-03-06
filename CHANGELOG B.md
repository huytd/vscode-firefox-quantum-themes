# Beta Changelog

Beta changelogs document every beta build which is published to GitHub, before release. Beta releases can be cloned from the `beta` branch, or else from the releases [here](https://github.com/beastdestroyer/vscode-firefox-quantum-themes/releases) and look for the ones labelled `Pre-release` or 'Beta' in the title

## Beta-1.1.x-5

- FINAL Preparation stages for 1.1.0
- Better Screenshots
- Return operator `new` back to purple

## Beta-1.1.x-4

- Operators now coloured the same as types (light grey) to maintain consistency with DevTools, and to stop the amount of blue! 

## Beta-1.1.x-3

- Symbols in Clojure changed to green
- Updated `SCREENSHOTS.md` with a few new and improved images
- Maintaining Parity with Firefox DevTools [#28](https://github.com/beastdestroyer/vscode-firefox-quantum-themes/issues/28)

## Beta-1.1.x-2

- CONSISTENCY Background colour changed on tabs to match DevTools, Light
- CONSISTENCY Tab border changed, Light
- CONSISTENCY Selection now transparent to match DevTools and for better visibility

## Beta-1.1.x-1

- Maintaining parity with Firefox DevTools [#28](https://github.com/beastdestroyer/vscode-firefox-quantum-themes/issues/28)
  - Variable colours now blue instead of red
  - Property colours now green
  - Numbers and interpolation now a more vibrant blue
  - Support types and CSS Pseudos now a lighter/darker grey for dark/light themes respectively

---

## Beta 1.0.x-4

- Language improvements:
  - R
  - Razor (cshtml) \[there are a few glitches with highlighting, but it appears to be with VSCode itself not the theme after further investigation]

- Theme title is not the same as name of extension [#25](https://github.com/beastdestroyer/vscode-firefox-quantum-themes/issues/25)
- Yellow not visible in Quantum Light [#22](https://github.com/beastdestroyer/vscode-firefox-quantum-themes/issues/22)

## Beta-1.0.x-3

### Features:

- Improved Language Support for:
  - Perl/Perl6
  - PHP
  - Python
  - PowerShell
  - log

- Select in Dropdowns now grey again! (Quantum Light)

## Beta-1.0.x-2

- Fixed types and pseudo classes being invisible in Quantum Light
- Bracket matching now matches Firefox Quantum
- Selection background is now more transparent for easier visibility (funnily enough, this transparency shows up in their editors for DevTools :P)
- Numbers darker in Quantum Light

## Beta-1.0.x-1

- Pre-emptive build for new cycles of betas

(RELEASED AS 1.0.2)

---

## Beta-1.0.0-8

- Fix errors in `package.json`
- Titlebars etc now whiter
- Release in Marketplace!

## Beta-1.0.0-7

- Status Bar debugging colours now red and text is white

## Beta-1.0.0-6

### Features

- Support for more languages (without extensions)
- Updated README with brief list of colours
- Screenshots moved to SCREENSHOTS.md, better screenshots will come eventually
- Added Firefox Developer Edition Icon
- Debug Widget Backgrounds exist!
- Quantum Light:
  - Fixed UI Issues.
  - Adjusted syntax highlighting

### Changes/Fixes

- Reverted colour of titlebar back to darker grey, edited this to sidebar titles (not the header titles)
- Fixed editor header being white (Quantum Light)
- Changed colour of inputs to be better viewable (Both)
- Fixed Markdown Link Names being lighter (both)

Guess what? ONE STEP CLOSER TO OFFICIAL 1.0.0 :)

## Beta-1.0.0-5

- Support for more languages (without extensions)
- Started adding in Quantum Light

## Beta-1.0.0-4

- Badges now lighter
- A few UI changes related to tokens. (Hopefully) all UI colours in sync now.
- Pseudo classes/elements in CSS have now changed from Firefox DevTools' grey to the yellow, this is to avoid confusion with normal text and people thinking the theme is "broken" with highlighting
- Types, Entities, Annotations are now yellow
- Menu bar changes
  - Menu items lighter [#9](https://github.com/beastdestroyer/vscode-firefox-quantum-themes/issues/9)
  - Changed blur colours
- Improve language support:
  - Groovy function calls highlighted

## Beta-1.0.0-3

- All Variable values now red
  - for SCSS, CSS etc.
- More screenshots and docs
- Change line highlight to dark variant #3
- Added new theme configs introduced for VSCode 1.29
- Changed up a few hover colours #2
- Change button colours #5
- Fixed errors not being red on hover #7

## Beta-1.0.0-2

- Change some syntax highlighting:
  - Variables and Object Keys are now red.
  - Interpolation
- Improved Clojure highlighting
- Improve CSS/SCSS Highlighting
  - Media Constants
- Add some more screenshots and docs to `README.md`

## Beta-1.0.0-1

- Add test files
- Improve Markdown
- Improve CSS Preprocessors:
  - Improve Interpolation
  - Improve Attributes
  - Highlight vendor prefixes separately
- Improve JSON/JS/TS
  - Highlight interpolation
  - Better object literals
