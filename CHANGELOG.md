# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## 0.2.1 - 01.12.2024
### Fixed
- Fix submission of the solution due to using old challenge interface

## 0.2.0 - 30.11.2024
### Added
- Extend cli with possibility to specify directories for: templates, challenges solutions, and data
- Extend cli and `BaseChallenge` interface with possibility to specify custom input file
- Add support for multiple years

### Fixed
- Fixed typing in cli module
- Adapt ruff config for a newer version
- Fix day template to consider also the year of the challenge
- Fix tests to include the year of the challenge
- Fix `SmartSmartFileInputProvider` to use data directory relative to the working directory
- Add working directory to sys.path when running through CLI

### Changed
- Update repository to the newest cookiecutter template
- Make the project year-independent by removing hardcoded 2023 year
- Extend the challenge interface to include also the year
