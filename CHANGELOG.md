# Changelog

All notable changes to this project are documented in this file, based on [Keep a Changelog][keepachangelog].

## [Unreleased]

## [0.2.0] - 2024-02-03
### Changed
- `Registry` is now a trait, with a single built-in implementation: `MapRegistry`.
- The type of identifiers is now generic, defaulting to `&'static str`.
- `deserialize_trait_object` is now a method on `Registry`.

### Added
- Added convenience `register_type` and `register_id_type` methods to `Registry`.

[Unreleased]: https://github.com/Gohla/serde_flexitos/compare/release/serde_flexitos/0.2.0...HEAD
[0.2.0]: https://github.com/Gohla/serde_flexitos/compare/release/serde_flexitos/0.1.0...release/serde_flexitos/0.2.0
[0.1.0]: https://github.com/Gohla/serde_flexitos/compare/...release/serde_flexitos/0.1.0

[keepachangelog]: https://keepachangelog.com/en/1.0.0/