# Changelog

All notable changes to `geekish/crap` will be documented in this file and follow the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## 1.0.0-beta.3 - 2017-01-08

### Added

- New command `info`; tells you what an alias is set to.

### Changed

- Improved dialog on `alias` command when overriding an existing alias.
- Interactive input on `alias` command when arguments are missing/swapped.

### Fixed

- Bumped PHPUnit version constraint to fix build failures.

### Removed

- Unnecessary command aliases: `list-aliases` (to `aliases`) and `define` (to `alias`).

## 1.0.0-beta.2 - 2016-12-03

### Fixed

- Composer commands were timing out after 60 seconds.

## 1.0.0-beta - 2016-11-23

Initial release.
