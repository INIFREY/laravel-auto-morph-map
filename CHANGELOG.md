# Changelog

All Notable changes to `sebastiaanluca/laravel-auto-morph-map` will be documented in this file.

Updates should follow the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## Unreleased

## 3.0.0 (2019-03-01)

### Added

- Added support for Laravel 5.8

### Removed

- Dropped support for Laravel 5.7 and lower

## 2.1.0 (2018-09-04)

### Added

- Run tests against Laravel 5.7

## 2.0.0 (2018-08-10)

### Added

- Added naming scheme options
- Added conversion override option
- Added "none" case type
- Added slug case type

### Changed

- Moved `CaseTypes` to a sub namespace
- Cache command now writes an aliased list of models, in effect disabling changing the case type afterwards

## 1.0.0 (2018-08-07)

### Added

- Added automatic model morph mapping
- Added cache command
- Added clear cache command
