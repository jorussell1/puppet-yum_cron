# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v8.0.0](https://github.com/treydock/puppet-yum_cron/tree/v8.0.0) (2025-05-29)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v7.1.0...v8.0.0)

### Changed

- Drop EL7 support [\#56](https://github.com/treydock/puppet-yum_cron/pull/56) ([treydock](https://github.com/treydock))

### Added

- feat\(reboot\): add reboot and reboot\_command configuration options for dnf-automatic service [\#51](https://github.com/treydock/puppet-yum_cron/pull/51) ([ManuelGago](https://github.com/ManuelGago))

## [v7.1.0](https://github.com/treydock/puppet-yum_cron/tree/v7.1.0) (2023-11-16)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v7.0.0...v7.1.0)

### Added

- Support stdlib 9.x [\#49](https://github.com/treydock/puppet-yum_cron/pull/49) ([treydock](https://github.com/treydock))

## [v7.0.0](https://github.com/treydock/puppet-yum_cron/tree/v7.0.0) (2023-05-03)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v6.2.0...v7.0.0)

### Changed

- Drop Puppet 6 support, Support Puppet 8 [\#47](https://github.com/treydock/puppet-yum_cron/pull/47) ([treydock](https://github.com/treydock))

### Added

- Support Amazon Linux 2022 and 2023 [\#48](https://github.com/treydock/puppet-yum_cron/pull/48) ([treydock](https://github.com/treydock))

## [v6.2.0](https://github.com/treydock/puppet-yum_cron/tree/v6.2.0) (2022-06-16)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v6.1.0...v6.2.0)

### Added

- Support EL9 and newer stdlib module numerous bug fixes [\#43](https://github.com/treydock/puppet-yum_cron/pull/43) ([treydock](https://github.com/treydock))

## [v6.1.0](https://github.com/treydock/puppet-yum_cron/tree/v6.1.0) (2021-09-14)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v6.0.0...v6.1.0)

### Added

- Support Amazon Linux 2 [\#38](https://github.com/treydock/puppet-yum_cron/pull/38) ([treydock](https://github.com/treydock))

## [v6.0.0](https://github.com/treydock/puppet-yum_cron/tree/v6.0.0) (2021-03-26)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v5.1.0...v6.0.0)

### Changed

- BREAKING: Major updates \(see description\) [\#33](https://github.com/treydock/puppet-yum_cron/pull/33) ([treydock](https://github.com/treydock))

### Added

- Numerous improvements to module code [\#36](https://github.com/treydock/puppet-yum_cron/pull/36) ([treydock](https://github.com/treydock))
- Add exclude\_packages parameter [\#35](https://github.com/treydock/puppet-yum_cron/pull/35) ([treydock](https://github.com/treydock))
- Add upgrade\_type parameter for EL8, EL8 improvements [\#34](https://github.com/treydock/puppet-yum_cron/pull/34) ([treydock](https://github.com/treydock))

## [v5.1.0](https://github.com/treydock/puppet-yum_cron/tree/v5.1.0) (2019-10-07)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v5.0.0...v5.1.0)

### Added

- Increase upper bound for supported stdlib [\#29](https://github.com/treydock/puppet-yum_cron/pull/29) ([treydock](https://github.com/treydock))
- EL8 support [\#28](https://github.com/treydock/puppet-yum_cron/pull/28) ([treydock](https://github.com/treydock))
- RHEL8 Support \(for dnf-automatic\) [\#26](https://github.com/treydock/puppet-yum_cron/pull/26) ([jadestorm](https://github.com/jadestorm))

### Fixed

- Fix spec tests from \#26 [\#27](https://github.com/treydock/puppet-yum_cron/pull/27) ([treydock](https://github.com/treydock))

## [v5.0.0](https://github.com/treydock/puppet-yum_cron/tree/v5.0.0) (2019-08-09)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/4.1.1...v5.0.0)

### Changed

- Only support Puppet 5 and 6 and bump module dependencies [\#25](https://github.com/treydock/puppet-yum_cron/pull/25) ([treydock](https://github.com/treydock))

### Added

- Convert module to use PDK [\#24](https://github.com/treydock/puppet-yum_cron/pull/24) ([treydock](https://github.com/treydock))
- Allow management of /etc/yum/yum-cron-hourly.conf [\#23](https://github.com/treydock/puppet-yum_cron/pull/23) ([treydock](https://github.com/treydock))

## [4.1.1](https://github.com/treydock/puppet-yum_cron/tree/4.1.1) (2019-04-29)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/4.1.0...4.1.1)

### Added

- Update inifile compatibility [\#20](https://github.com/treydock/puppet-yum_cron/pull/20) ([siebrand](https://github.com/siebrand))

## [4.1.0](https://github.com/treydock/puppet-yum_cron/tree/4.1.0) (2019-01-30)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/4.0.0...4.1.0)

### Added

- raise upper version bounds for recent dependencies [\#17](https://github.com/treydock/puppet-yum_cron/pull/17) ([mmoll](https://github.com/mmoll))
- update beaker to 4.x [\#16](https://github.com/treydock/puppet-yum_cron/pull/16) ([mmoll](https://github.com/mmoll))
- Fix hiera example of update\_messages [\#15](https://github.com/treydock/puppet-yum_cron/pull/15) ([yorickps](https://github.com/yorickps))

## [4.0.0](https://github.com/treydock/puppet-yum_cron/tree/4.0.0) (2018-02-13)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/3.0.0...4.0.0)

## [3.0.0](https://github.com/treydock/puppet-yum_cron/tree/3.0.0) (2018-02-10)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/2.0.0...3.0.0)

### Fixed

- Fix typo [\#6](https://github.com/treydock/puppet-yum_cron/pull/6) ([siebrand](https://github.com/siebrand))

## [2.0.0](https://github.com/treydock/puppet-yum_cron/tree/2.0.0) (2015-11-12)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/1.3.0...2.0.0)

## [1.3.0](https://github.com/treydock/puppet-yum_cron/tree/1.3.0) (2015-10-06)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/1.2.0...1.3.0)

### Added

- Support for CentOS 7 [\#5](https://github.com/treydock/puppet-yum_cron/pull/5) ([narbutas](https://github.com/narbutas))
- Parametrize option email\_host. [\#4](https://github.com/treydock/puppet-yum_cron/pull/4) ([moonwolf-github](https://github.com/moonwolf-github))

## [1.2.0](https://github.com/treydock/puppet-yum_cron/tree/1.2.0) (2015-03-02)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/1.1.1...1.2.0)

## [1.1.1](https://github.com/treydock/puppet-yum_cron/tree/1.1.1) (2014-11-07)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/1.1.0...1.1.1)

## [1.1.0](https://github.com/treydock/puppet-yum_cron/tree/1.1.0) (2014-11-03)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/1.0.0...1.1.0)

## [1.0.0](https://github.com/treydock/puppet-yum_cron/tree/1.0.0) (2013-12-12)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/0.1.1...1.0.0)

## [0.1.1](https://github.com/treydock/puppet-yum_cron/tree/0.1.1) (2013-12-09)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/0.1.0...0.1.1)

## [0.1.0](https://github.com/treydock/puppet-yum_cron/tree/0.1.0) (2013-09-18)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/v0.0.1...0.1.0)

## [v0.0.1](https://github.com/treydock/puppet-yum_cron/tree/v0.0.1) (2013-09-04)

[Full Changelog](https://github.com/treydock/puppet-yum_cron/compare/9aa4945e471387d8102ffa03f3f85d20a10d74f0...v0.0.1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
