# Change Log
All notable changes to this project will be documented in this file.

## 0.6.4 - 2017-04-24 [in progress]

### Added

- Added question marks to the MSqRob GUI that link the user to a page with extra info on how to use the input terms.

### Changed

- Added support for calculating degrees of freedom in 4 different ways: "residual", "Satterthwaite", "exp_between" and "custom". Removed the separate "Satterthwaite" argument from all functions that test contrasts. Instead, "Satterthwaite" is now an option in the new argument "type_dfs".

- Improved preprocessing_wide and preprocessing_long functions by adding default settings and updating their descriptions. Fixed some minor issues that could lead to errors.

### Fixed

- Added an error message when trying to calculate Satterthwaite degrees of freedom with ANOVA, as this is not yet implemented.

## 0.6.3 - 2017-04-14

### Added
- This CHANGELOG file.