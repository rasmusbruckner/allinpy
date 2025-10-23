# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

## [0.2.0] - 2025-10-23
### Added
- Extended **plotting utilities module** (`allinpy.plotting.plot_utils`) with tested functions for figure labeling, text centering, and schematic layout:
  - `get_text_coords`, `center_x`, `center_y` for accurate text placement  
  - `plot_image`, `plot_arrow`, `plot_rec`, `plot_table`, and `plot_centered_text` for compositional figure building  
- Added **pytest-based test suite** covering coordinate handling and layout logic.

### Changed
- Reworked coordinate management to ensure consistent use of `axes`, `data`, and blended transforms.
- Improved `plot_image` positioning logic; caption text now rendered in axes coordinates.

## [0.1.1] - 2025-07-03
### Added
- Added documentation URL to PyPI metadata.

## [0.1.0] - 2025-07-01
### Initial release
- First upload of allinpy package.
