# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.0.7 - [Unreleased]

## [0.0.6] - 2018-12-05

### Changed
- Dont use mill's `assembly` (as sometimes it generated an executable) instead make `dockerJar` create its own fat jar. Fixes #5.

## [0.0.5] - 2018-11-20

### Added
- This CHANGELOG file

### Changed
- Upgrade to Mill 0.3.5
- Use `os-lib` instead of `ammonite.ops._`
- Make build time versions easier to manage.
  Scala and mill versions are managed from `.tool-versions` file.
  The VERSION specifies this project's version number.

[Unreleased]: https://github.com/vic/mill-docker/compare/0.0.6...HEAD
[0.0.6]: https://github.com/vic/mill-docker/compare/0.0.5...0.0.6
[0.0.5]: https://github.com/vic/mill-docker/compare/0.0.4...0.0.5
