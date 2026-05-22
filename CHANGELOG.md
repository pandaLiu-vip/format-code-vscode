# Change Log

All notable changes to the "format-code" extension will be documented in this file.

## [Unreleased]

### Added

- Added the `Dos2Unix` command to convert Windows line endings `CRLF (\r\n)` to Unix line endings `LF (\n)`.
- Added support for processing the active editor file when no resource is selected in the explorer.
- Added recursive folder traversal so a selected directory can be converted in one run.
- Added progress feedback and summary notifications for batch conversions.
- Added binary-file skipping to reduce the risk of corrupting non-text files.

### Changed

- Improved the command implementation so opened documents are updated through the VS Code editor API and then saved automatically.
