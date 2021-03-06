# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.2] - 2020-07-28

### Added

- Demo of viewer using default Tailwind config

### Fixed

- Asset paths are now relative enabling static export to be hosted in subdirectories

## [1.1.1] - 2020-07-28

### Fixed

- Error due to missing lib directory in npm package [Issue](https://github.com/rogden/tailwind-config-viewer/issues/7)

## [1.1.0] - 2020-07-27

### Added

- `export` command to export the viewer for static hosting
- `serve` command to serve the viewer. This is the default command and equivalent to running `tailwind-config-viewer` without specifying a command.

## [1.0.0] - 2020-07-21

- Initial Release