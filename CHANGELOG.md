# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- MQTT
  - added --saic-uri configuration option
  - automatically register for all alarm types
  - create Docker image
  - create Debian package
### Fixed
- API
  - support messages with DispatcherBody data longer than 256 bytes

## [0.0.3] - 2022-12-19
### Changed
- properly initialize Messages in the MessageCoder

## [0.0.2] - 2022-12-14
### Added
- Initial support for SAIC API
- Initial MQTT Gateway
  - Support for A Better Routeplaner Telemetry update
- Initial HTTP Gateway