# Changelog

All notable changes to the Varbase API Base recipe are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0-rc2] - 2026-09-02
### Added
- Require the `vardot/swagger-ui` library (`^5.32.14`), so the recipe brings the Swagger UI
  files `drupal/openapi_ui_swagger` loads. The package replaces the upstream
  `swagger-api/swagger-ui`, which is published as composer type `library` and cannot be
  placed in `web/libraries`.
### Changed
- Update the version badge to `1.0.0-rc2` in `README.md`.

## [1.0.0-rc1] - 2026-08-15
### Changed
- Release the recipe with the Varbase 11.0.0-rc1 suite. No functional changes since 1.0.0-beta1.
- Update the version badge to `1.0.0-rc1` in `README.md`.

## [1.0.0-beta1] - 2026-07-09
### Changed
- Update Drupal Core from ~11.3.0 to ~11.4.0 in the Varbase API Base recipe.
- Update the version badge to `1.0.0-beta1` in `README.md`.
- Run CI on tag pushes and add the README pipeline and release badges.

## [1.0.0-alpha2] - 2026-06-21
### Changed
- Maintenance and dependency updates for the Varbase API Base recipe.

## [1.0.0-alpha1]
### Added
- Initial release of the Varbase API Base recipe.

[Unreleased]: https://git.drupalcode.org/project/varbase_api_base/-/compare/1.0.0-rc2...1.0.x
[1.0.0-rc2]: https://git.drupalcode.org/project/varbase_api_base/-/compare/1.0.0-rc1...1.0.0-rc2
[1.0.0-rc1]: https://git.drupalcode.org/project/varbase_api_base/-/compare/1.0.0-beta1...1.0.0-rc1
[1.0.0-beta1]: https://git.drupalcode.org/project/varbase_api_base/-/compare/1.0.0-alpha2...1.0.0-beta1
[1.0.0-alpha2]: https://git.drupalcode.org/project/varbase_api_base/-/compare/1.0.0-alpha1...1.0.0-alpha2
[1.0.0-alpha1]: https://git.drupalcode.org/project/varbase_api_base/-/tags/1.0.0-alpha1
