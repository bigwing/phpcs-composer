# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Initial code from
[10up/phpcs-composer](https://github.com/10up/phpcs-composer/tree/2fcd33205f7742c46fa09b28829321d847cc472d) on 2020-08-05.

### Added

- Rule: base BigWing WordPress rules.
- Rule: flag TODO comments.
- Rule: no unused parameters in a function.
- Rule: force line after opening function comment.
- Annotated ruleset to show how to extend arrays as of PHP_CodeSniffer 3.4.0.
- Included `roave/security-advisories` as a required package.
- Exclude dist/build directories from sniffs.

### Changed

- Set base WP version to 5.0.
- Set base PHP version to 7.2.
- Updated exclusions to include Sass/SCSS and JSX files.

### Fixed

### Removed
