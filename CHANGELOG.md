# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added

### Changed

## [0.3.0] - 2017-02-21
### Added
- explicit timestamp synchronization for uploaded photos and videos

### Changed
- Python 3 compatibility
- Use flickrapi v2 for PyPI

## [0.2.2] - 2017-02-11
### Added
- added --fix-missing-description option (thanks jruusu)
- added --dry-run option (thanks jruusu)

## [0.2.1] - 2015-02-17
### Added
- added --custom-set-debug for testing custom sets output
- added --ignore-ext comma separated extensions to ignore

## [0.2.0] - 2015-02-15
### Added
- Add test cases that do a limited test of each class in isolation
- Add a sync-from=all command line option that allows a download of any remote file not on local, and upload of any local file not on remote as discussed in #22
- Add retries on uploads and downloads
- Add a file extension on download if one doesn't exist

### Changed
- Refactor code into sync, local and remote classes

### Fixed
- Incorporate pull request #32 which fixes #31 with slight changes
- Thanks thomascobb

## [0.1.18] - 2014-11-14
### Added
- browser-less authentication

## [0.1.17] - 2014-08-12
### Changed
- allow filtering files to upload by IPTC keyword (thanks ricardokirkner)
- updated flickrapi 1.4.4

## [0.1.16] - 2014-06-30
### Changed
- flickr api changes use https

## [0.1.15] - 2014-05-30
### Changed
- monitor folder support (--monitor)

## [0.1.14.3] - 2014-05-18
### Fixed
- encoding bug

## [0.1.14.2] - 2014-04-15
### Changed
- send script output to syslog for headless convience (thanks dahlb)

## [0.1.14] - 2014-02-25
### Added
- added --starts-with param
- added --version param

### Fixed
- bug fix not uploading files properly

## [0.1.12] - 2014-02-15
### Added
- added custom set title

### Fixed
- character encoding bugs

### Changed
- skip failures

## [0.1.11] - 2013-07-09
### Added
- added mts video
- added folder utf8 encoding to avoid dups
- added sorting for each folders

## [0.1.10] - 2013-07-07
### Changed
- sorted photo sets
- ignore files > 1gb

## [0.1.9] - 2013-06-28
### Added
- added --sync-path param

## [0.1.8] - 2013-06-25
### Added
- added video support
- added new params for skipping video/images

### Changed
- ignore hidden folders/folders

## [0.1.7] - 2013-06-15
### Added
- added run from source

## [0.1] - 2013-06-13
- initial version
