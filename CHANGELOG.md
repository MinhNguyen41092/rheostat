# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

- [Breaking] drop v0.13 support
- Add getNextHandlePosition prop to allow custom movement validation

## [2.1.3] - 2018-01-03

### Fixes

- revert jsnext:main extension removal (#135)

## [2.1.2] - 2018-01-02

### Fixes

- Slider: avoid key={0} (#106)
- Use math.round instead of math.floor for getting value with geometric algorithm (#131)

### Refactors

- Slider: use function refs instead of string refs (#112)
- Memoize pits styles (#123, #130)

## [2.1.1] - 2017-07-11

### Fixed

- use prop-types + create-react-class packages (#73)
- ensure `Object.assign` is transformed to `object.assign`

## [2.1.0] - 2016-11-10

### Changed

- Up/Down keys also move the slider now.

## [2.0.1] - 2016-10-19

### Fixed

- Eliminate slidingIndex of -1 (#33)

## [2.0.0] - 2016-08-22

### Changed

- A11y for tabbing between handles.
- Changed slider handles from div to button.

## [1.1.2] - 2016-07-08

### Fixed

- React v15 support.

## [1.1.1] - 2016-06-27

### Added

- A geometric algorithm.

## [1.1.0] - 2016-06-22

### Added

- New prop for disabling the slider.

## [1.0.0] - 2016-01-21

Initial Release
