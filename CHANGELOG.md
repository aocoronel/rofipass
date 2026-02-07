# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-02-07

### Added

- Add comments to obscure variables.
- Adding a new OTP now will try to handle the manually copied secret code, instead of only relying on the QR code PNG, which allows to append without zbarimg. Although it's still supported.

### Changed

- **BREAKING CHANGE:** rofipass no longer wipes the cliphist database and closes all notifications. Only sets the clipboard to nothing.
- No longer requires a terminal to open the editor.
- Deleting a password now uses a tinier rofi window.
- Set rofi prompt to a key emoji.
