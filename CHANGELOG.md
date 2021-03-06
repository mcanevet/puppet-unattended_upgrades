# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]
### Changed
- CHANGELOG: Fixed comparison URL's for the releases
- CHANGELOG: Fixed changed header for 1.1.1

## Release 1.1.0 - 2016-01-08
### Added
- Support Raspbian
- Support for Debian Jessie and Ubuntu Wiley
- Documentation for `clean` parameter
- Clarification for `sleep`

### Fixed
- code is now `strict_variables` safe
- Fix bug that prevented us from working on Ubuntu

### Maintenance
- linter clean
- rubocop clean
- integrate in modulesync


## [1.0.3] - 2015-04-23
### Changed
- Tested on Puppet 4.
- Remove inclusion of `apt` class.

## [1.0.2] - 2015-04-22
### Changed
- Resolve some Travis related packaging issues.

## [1.0.1] - 2015-04-22
### Changed
- Resolve some Travis related packaging issues.

## 1.0.0 - 2015-04-22
### Added
- Full configuration of unattended-upgrades and all possible options for `APT::Periodic`.
- Test suite covering the current behaviour.
- README with full documentation.
- Boilerplate such as Gemfile, Travis configuration, LICENSE and so on.

[unreleased]: https://github.com/voxpupuli/puppet-unattended_upgrades/compare/HEAD...1.1.0
[1.1.0]: https://github.com/voxpupuli/puppet-unattended_upgrades/compare/1.1.0...1.0.2
[1.0.3]: https://github.com/voxpupuli/puppet-unattended_upgrades/compare/1.0.2...1.0.3
[1.0.2]: https://github.com/voxpupuli/puppet-unattended_upgrades/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/voxpupuli/puppet-unattended_upgrades/compare/1.0.0...1.0.1
