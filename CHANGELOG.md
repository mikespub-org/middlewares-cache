# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [3.1.0] - 2025-03-21
### Added
- Support for PHP 8.4

## [3.0.0] - 2023-12-17
### Added
- New test cases for Cache using ETag

### Changed
- Replaced read-only `micheh/psr7-cache` with updated `mikespub/micheh-psr7-cache`
- Updated version constraints for dependencies

### Removed
- Support for PHP prior to 8.1.

## [2.1.0] - 2020-12-02
### Added
- New middleware `ClearSiteData`.
- Support for PHP 8

## [2.0.0] - 2019-12-01
### Added
- Added a second argument to `Cache` constructor to define a `ResponseFactoryInterface`

### Removed
- Support for PHP 7.0 and 7.1
- The `responseFactory()` option in `Cache` middleware. Use the constructor argument.

## [1.1.0] - 2018-08-04
### Added
- PSR-17 support
- New option `responseFactory`

## [1.0.0] - 2018-01-25
### Added
- Improved testing and added code coverage reporting
- Added tests for PHP 7.2

### Changed
- Upgraded to the final version of PSR-15 `psr/http-server-middleware`

### Fixed
- Updated license year

## [0.5.0] - 2017-11-13
### Changed
- Replaced `http-interop/http-middleware` with  `http-interop/http-server-middleware`.

### Removed
- Removed support for PHP 5.x.

## [0.4.0] - 2017-09-21
### Changed
- Append `.dist` suffix to phpcs.xml and phpunit.xml files
- Changed the configuration of phpcs and php_cs
- Upgraded phpunit to the latest version and improved its config file
- Updated to `http-interop/http-middleware#0.5`

## [0.3.1] - 2017-03-30
### Fixed
- `Middlewares\Cache` is executed only with `GET` and `HEAD` requests.

## [0.3.0] - 2016-12-26
### Changed
- Updated tests
- Updated to `http-interop/http-middleware#0.4`
- Updated `friendsofphp/php-cs-fixer#2.0`

## [0.2.0] - 2016-11-22
### Changed
- Updated to `http-interop/http-middleware#0.3`

## [0.1.0] - 2016-10-03
First version

[3.1.0]: https://github.com/middlewares/cache/compare/v3.0.0...v3.1.0
[3.0.0]: https://github.com/middlewares/cache/compare/v2.1.0...v3.0.0
[2.1.0]: https://github.com/middlewares/cache/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/middlewares/cache/compare/v1.1.0...v2.0.0
[1.1.0]: https://github.com/middlewares/cache/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/middlewares/cache/compare/v0.5.0...v1.0.0
[0.5.0]: https://github.com/middlewares/cache/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/middlewares/cache/compare/v0.3.1...v0.4.0
[0.3.1]: https://github.com/middlewares/cache/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/middlewares/cache/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/middlewares/cache/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/middlewares/cache/releases/tag/v0.1.0
