# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.7.2] - 2018-10-28

### Fixed
- Missing activation event to push local commits.

## [1.7.1] - 2018-10-28

### Changed
- Update readme.

### Fixed
- Missing changelog data for v1.7.0.

## [1.7.0] - 2018-10-28

### Added
- Push local commits command.

## [1.6.0] - 2018-05-29

### Added
- More npm, webpack, editorconfig & vscode patterns in default settings.

### Fixed
- Regex support in patterns.
- Exact regex-s in default settings patterns.

## [1.5.4] - 2018-05-28

### Fixed
- Fix "command 'extension.vscode-git-add-and-commit.addAndCommitCurrentFile' not found" error.

## [1.5.3] - 2018-05-28

_Please do **NOT** use this release._

## [1.5.2] - 2018-05-28

_Please do **NOT** use this release._

## [1.5.1] - 2018-05-28

### Fixed
- Apply dependencies security patches.

### Changed
- Improve errors catching.
- Update readme (roadmap).

## [1.5.0] - 2018-05-26

### Changed
- Switch to vscode user/workspace settings instead of a custom "vscode-git-add-and-commit.json" file.

## [1.4.2] - 2018-05-10

### Fixed
- Fix MacOS key bindings.

### Changed
- Update dependencies.

## [1.4.1] - 2018-01-11

### Changed
- Update readme.

## [1.4.0] - 2018-01-11

### Added
- Add a `withGuessedCustomActions` setting to prefill the commit message for certain file - action associations.

### Changed
- Improve the multiple files commit auto-prefill by checking the possible common path.
- Update readme.

### Fixed
- Handle empty Git status case (nothing added).

## [1.3.1] - 2018-01-10

### Fixed
- Fix status bar message.
- Fix unnecessary double quotes in commit message.

## [1.3.0] - 2018-01-10

### Added
- Add a `disableOptionalMessages` setting to move optional messages to the status bar.

### Changed
- Update readme.

## [1.2.2] - 2018-01-10

_Please do **NOT** use this release._

## [1.2.1] - 2018-01-10

### Changed
- Remove background of icon.

## [1.2.0] - 2018-01-10

### Added
- Add commit message auto-prefill feature.

### Changed
- Update readme

### Fixed
- Fix Git warnings considered as errors.

## [1.1.3] - 2018-01-10

### Changed
- Update readme.

## [1.1.2] - 2018-01-10

### Changed
- Fix Visual Studio Marketplace badge.

## [1.1.1] - 2018-01-10

### Removed
- Remove a package keyword.

## [1.1.0] - 2018-01-10

### Added
- Add extension icon.

### Changed
- Upgrade depedencies.

## [1.0.0] - 2018-01-09

### Added
- Initial release.
- Add git add & commit all edited files command.
- Add git add & commit current file command.
- Add git reset fallback on cancel or errors.
