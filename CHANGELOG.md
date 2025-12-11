# Changelog

All notable changes to the "code-eol" extension will be documented in this file.

## [1.0.2] - 2025-12-10

### Added
- Published to [Open VSX Registry](https://open-vsx.org/extension/skwonandy/vs-code-eol) for Cursor and other VS Code-compatible editors

## [1.0.1] - 2025-12-10

### Changed
- Updated version to 1.0.1

## [1.0.0] - 2025-12-10

### Changed
- Renamed extension from `code-eol` to `vs-code-eol`
- Changed display name to `vs-code-eol`
- Updated repository URL to https://github.com/skwonandy/code-eol

## [0.3.3] - 2025-12-09

### Changed
- Changed publisher from `sohamkamani` to `skwonandy`
- Updated TypeScript from `^2.5.3` to `^4.9.5`
- Updated `@types/node` to `^14.18.63`
- Replaced deprecated `vscode` package with `@types/vscode ^1.15.0`
- Updated build scripts to use relative paths instead of absolute paths
- Changed default EOL color to `#ccc` (light gray)

### Added
- Added LICENSE file with MIT license
- Added proper attribution to original work by sohamkamani
- Added `build` script for one-time compilation
- Updated README with fork information

### Fixed
- Fixed compilation issues caused by hardcoded absolute paths
- Modernized package dependencies for better compatibility

### Removed
- Removed obsolete `postinstall` script
- Removed `vsce` from dependencies (should be installed globally)
- Removed deprecated `vscode` package

---

Based on original work by [sohamkamani/code-eol](https://github.com/sohamkamani/code-eol)

