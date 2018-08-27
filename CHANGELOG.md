# Change Log
All notable changes to the "outrun" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## [0.2.2] - 2018-08-27
### Added
- Styling for Peek View editor
- Styling for indent guides and rulers
- General color improvements

## [0.2.1] - 2018-08-26
### Added
- Styling for Editor Widgets in both Night and Electric
- `this` keyword styling for TypeScript

### Changed
- Function names are no longer orange since we cannot scope to only declarations (See https://github.com/Microsoft/vscode-textmate/issues/52) :/

## [0.2.0] - 2018-08-26
### Added
- Outrun Night theme. This is a less-intense version of the original Outrun theme
- Outrun Electric theme. This is the original, high-contrast Outrun theme

### Changed
- Theme colors have been completely re-worked from the ground up. Editor features have been refined. Some features may be missing and will be implemented as noticed. Thank you for your patience :)

### Removed
- Outrun theme. The original Outrun theme has been split into Outrun Night and Outrun Electric. Choose one depending on your preferences.

## [0.1.3] - 2018-07-02
### Changed
- Changed Marketplace banner theme to `dark` even though docs reference this as the "font color". :/

## [0.1.2] - 2018-07-02
### Added
- Add icon and other marketplace niceties

## [0.1.0] - 2018-07-02
### Added
- Add orange foreground on library functions 
- Add cyan foreground and italic font on PHP `this` keyword
### Changed
- Remove foreground color from function calls

## [0.0.2] - 2018-07-02
### Added
- JavaScript scopes `variable.language.this.js` and `variable.language.super.js` are now styled in italic with a cyan foreground.

## [0.0.1] - 2018-06-29
- Initial release
