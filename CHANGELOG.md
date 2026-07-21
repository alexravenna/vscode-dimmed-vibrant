# Change Log

Structured according to [Keep a Changelog](http://keepachangelog.com/).

[Semantic versioning](https://semver.org) is followed to the best of my ability.

## [2.0.0] - 2026-07-21

### Added

- Theme icon
- Badges for Open VSX Registry to readme
- VS Code extension recommendations
- Dependabot configuration for GitHub Actions and npm ecosystems
- [Devcontainer](https://containers.dev) [configuration](/.devcontainer/devcontainer.json)
for remote development

### Changed

- Rebranded theme name from "Monokai Dimmed+Vibrant" to just "Dimmed+Vibrant"
- Extended .vscodeignore to trim out files irrelevant to packaged theme
- Updated all Actions used in publishing workflow to current major versions
- Updated Node.js version used in publishing workflow to 24
- Replaced readme badges from [shields.io](https://shields.io) with ones from [badgen.net](https://badgen.net)
- Updated deprecated properties for `editorIndentGuide`

### Security

- Update npm dependencies

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
