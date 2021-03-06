# Change Log
All notable changes to this project will be documented in this file.

## Unreleased
No unreleased changes.

## 0.3.1 - 2014-12-06
### Added
- This new-format CHANGELOG, based on http://keepachangelog.com

### Changed
- AbstractShopUser.token now has a default value to allow easy resetting
- Improvements to README

## 0.3.0 - 2014-10-22
### Added
- Context processor to add common variables to templates

### Changed
- Major rewrite and update of README

## 0.2.5 - 2014-09-28
### Added
- Support for Django 1.7
- A `login_required` decorator to handle passing off Shopify authentication parameters to the login URL

### Removed
- Support for any version of Django < 1.7

### Fixed
- Numerous issues with packaging and distribution of templates

## 0.1.6 - 2014-08-25
### Fixed
- Move imports inside initialize() method so that we don’t break things on initial setup

## 0.1.5 - 2014-08-25
### Added
- Added `api` module for TastyPie-supported models
- Initialise properly
- Add dynamic `session` property to user

### Changed
- Swapped to setuptools for distribution

## 0.1.0 - 2014-04-04
### Added
- Initial package structure
- Custom models and decorators to support Shopify authentication
