# Change Log

The change log describes what is "Added", "Removed", "Changed" or "Fixed" between each release.

## UNRELEASED

## 1.2.0

* Support for PHP 8.1
* Drop support for PHP < 7.4
* Allow psr/cache: ^1.0 || ^2.0

## 1.1.0

### Added

* Support for PHP 8

## 1.0.0

### Added

* The `CachePoolChain` does now implement `Cache\TagInterop\TaggableCacheItemPoolInterface`

### Removed

* Removed deprecated function `clearTags`

## 0.5.1

### Fixed

* Fixed issue with generator
* Make sure `getItems` always save values back to previous pools

## 0.5.0

### Added

* Support for the new `TaggableCacheItemPoolInterface`.

## 0.4.0

### Changed

* `CachePoolChain::getPools` is protected instead of public

## 0.3.1

* No changelog before this version
