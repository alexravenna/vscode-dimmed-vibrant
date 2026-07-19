# Change Log

Structured according to [Keep a Changelog](http://keepachangelog.com/).

## [Unreleased]

### Added

- Theme icon
- Added badges for Open VSX Registry to readme
- Added VS Code extension recommendation for [Marketplace Preview](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-marketplace-preview)
- Dependabot configuration for GitHub Actions and npm ecosystems

### Changed

- Updated all Actions used in publishing workflow to current major versions
- Updated Node.js version used in publishing workflow to 24
- Replaced readme badges from [shields.io](https://shields.io) with ones from [badgen.net](https://badgen.net)
- Updated deprecated properties for `editorIndentGuide`

## [1.0.4] - 2023-08-26

### Added

- Publishing to the Open VSX Registry with the GitHub Action [HaaLeo/publish-vscode-extension](https://github.com/HaaLeo/publish-vscode-extension).
- Automatic publishing of a GitHub Release upon tagging of a new version using [softprops/action-gh-release](https://github.com/softprops/action-gh-release).
- MIT license.
- Links in the readme for previewing this theme.

## [1.0.3] - 2023-06-17

### Fixed

- Publishing Action by changing readme badge provider.

## [1.0.2] - 2023-06-10

### Fixed

- Update VS Code compatibility version.

## [1.0.1] - 2023-06-10

### Added

- GitHub Action for publishing the extension as artifact and to the VS Marketplace.
- Screenshot in readme.
- VS Marketplace badges in readme.
- Commitlint hook for enforcing commit conventions.

## [1.0.0] - 2020-03-08

- Initial release
