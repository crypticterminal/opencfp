# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 1.5.9 - 2018-06-15

### Changed

- Environment now defaults to `production` if the environment variable has not been set
- Showing the contribution banner on the splash page now configurabler

## 1.5.8 - 2018-05-26

### Added

- Users can now delete their own accounts, which deletes all associated information

## 1.5.7 - 2018-05-18

### Added

- Privacy policy now exists
- README updated to request that collected data not be shared with third parties without explicit consent of users

### Changed

- User accounts cannot be created without acknowledging they have read and understand the privacy policy 

## 1.5.6 - 2018-05-15

### Added

- instructions on how to build OpenCFP in a Docker container
- instructions on running OpenCFP in Homestead

### Changed

- Now running local scripts using COmposer

## 1.5.5 - 2018-04-23

### Added

- Speakers' joind.in URL's are now being validated better

### Changed

- Moved code from `classes` to `src` to better adhere to Symfony standards

## 1.5.4 - 2018-04-09

### Added

- Support for phly/keep-a-changelog to help with creating releases
- 'Personal Skills' is now a talk category

### Changed  

- Updated documentation about when dev server is available
- Updated documentation about permissions for cache and log folders

## 1.5.3 - 2018-03-27

### Added

- Filters for category and type on the talks admin page

### Changed

- Updated PHPUnit to 6.5.7
- Updated PHP CS Fixer to 2.10.4
- Updated Infection to 0.7.1

### Removed

- No longer using Code Climate for analyzing code
