# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.10] - 2024-08-01
### Deprecated
- This project is now deprecated in favor of the new Nice G.O. library, found [here](https://github.com/IceBotYT/nice-go)

## [0.2.9] - 2024-02-11
### Fixed
- Major makeover of all logic, removed WebSocketMonitor usage.

## [0.2.8] - 2024-01-30
### Fixed
- Added retry logic to `new_connection`

## [0.2.7] - 2023-08-09
### Fixed
- Bumped dependencies

## [0.2.6] - 2023-05-08
### Changed
- Updated how device states are fetched

## [0.2.5] - 2023-04-11
### Fixed
- Various bug fixes

## [0.2.4] - 2023-02-05
### Changed
- Removed `websocket-client` as a dependency

## [0.2.3] - 2023-02-04
### Fixed
- Added keepalive ping

## [0.2.2] - 2023-02-03
### Fixed
- Fixed the `unsupported operand type(s) for |: 'types.GenericAlias' and 'NoneType'` error when using this library below Python 3.10

## [0.2.1] - 2023-02-01
### Changed
- If custom session is passed in, do not close it when `close()` is called

## [0.2.0] - 2023-02-01
### Fixed
- Fixed dependency conflict for Home Assistant

### Added
- Added the option to pass in a ClientSession

## [0.1.0] - 2023-01-31
### Changed
- Initial functionality

[Unreleased]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.10...master
[0.2.10]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.9...0.2.10
[0.2.9]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.8...0.2.9
[0.2.8]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.7...0.2.8
[0.2.7]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.6...0.2.7
[0.2.6]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.5...0.2.6
[0.2.5]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.4...0.2.5
[0.2.4]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.3...0.2.4
[0.2.3]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.2...0.2.3
[0.2.2]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.1...0.2.2
[0.2.1]: https://github.com/IceBotYT/linear-garage-door/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/IceBotYT/linear-garage-door/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/IceBotYT/linear-garage-door/tree/0.1.0

