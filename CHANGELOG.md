# Changelog

This project follows semantic versioning.

Possible log types:

- `[added]` for new features.
- `[changed]` for changes in existing functionality.
- `[deprecated]` for once-stable features removed in upcoming releases.
- `[removed]` for deprecated features removed in this release.
- `[fixed]` for any bug fixes.
- `[security]` to invite users to upgrade in case of vulnerabilities.

## [Unreleased]

 - [removed] Dropped support for Python 2
 - ...

## [0.3.0] - 2017-07-12

 - [added] This library is now fully type annotated (#4, thanks @tyehle)
 - [added] Implementations for `__ne__`, `__hash__` and `__repr__`
 - [deprecated] Python 2 support is deprecated and will be removed in the 0.4 release

## [0.2.2] - 2016-09-21

 - [added] `__eq__` magic method

## [0.2.0] - 2016-05-05

 - [added] Convenience default: `Ok()` == `Ok(True)`

## [0.1.1] - 2015-12-14

 - [fixed] Import bugfix

## [0.1.0] - 2015-12-14

 - Initial version

[Unreleased]: https://github.com/dbrgn/result/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/dbrgn/result/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/dbrgn/result/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/dbrgn/result/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/dbrgn/result/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/dbrgn/result/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/dbrgn/result/compare/3ca7d83...v0.1.0
