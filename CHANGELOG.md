# Changelog

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] – 2025-08-06

### Added
- LICENSE.md containing the SIL Open Font License v1.1.

### Changed
- Restructured project layout:  
  - Renamed `assets/` → `Assets/` and reorganized image/PDF assets.  
  - Consolidated font sources: moved from `font/` and `src/Victorianna/` into `src/Victorianna/…` and `Source/Victorianna/…`.  
- Updated README.md examples to point at specimen images in their new locations.

### Removed
• Legacy LICENSE.txt.

## [1.0.0] – 2025-08-06

### Added
- Introduce `info.toml` to centralize project metadata (license, publication date, foundry, summary, links, contributors).
- Add local `example.png` (renamed from `specimen.png`) for offline documentation.

### Changed
- Rename image reference in `README.md` from GitHub URL to local `./example.png`.
- Refactor `README.md`: remove legacy contribution instructions, embedded license text, and repository layout section.

### Removed
- Delete legacy metadata files `FONTLOG.md` and `METADATA.yml`.
- Remove all source–drawing artifacts under `sources/1-drawing/victorianna_thin.ufo/` (features, fontinfo, and all `.glif` glyph files).

---

[Unreleased]: https://github.com/your-user/your-repo/compare/v1.1.0...HEAD
[1.1.0]:      https://github.com/your-user/your-repo/compare/v1.0.0...v1.1.0
[1.0.0]:      https://github.com/REPO_OWNER/PROJECT_NAME/compare/...v1.0.0 (Comparing agaisnt the start of the project)
