# Changelog

All notable changes to CS2 Flash FX are documented in this file.

---

## [0.1.4-alpha.1] - 2026-10-23

### Added

- Initial public alpha release
- Counter-Strike 2 flashbang detection using Game State Integration
- Elgato Key Light control over the local network
- Support for multiple Key Lights
- Configurable flash brightness and color temperature
- Configurable normal brightness and color temperature
- Configurable flash effect duration
- Automatic effect extension while CS2 continues reporting an active flash
- Built-in Counter-Strike 2 installation detection
- Manual Counter-Strike 2 path selection
- Built-in GSI configuration installation
- GSI configuration repair and removal
- Flash Effect lock when the required GSI integration is unavailable
- System tray mode
- Enable and disable Flash Effect from the tray
- Test Flash action from the tray
- Close-to-tray behavior
- Single-instance protection
- Existing instance restoration when launching the application again
- Automatic update checks through GitHub Releases
- Manual update checks from Settings
- Global update notification
- Formatted GitHub release notes
- Built-in self-update support
- SHA-256 update verification
- Portable self-contained single-file Windows release
- Local settings storage under `%APPDATA%\NK-Studios\CS2FlashFX`
- Dark user interface inspired by Counter-Strike 2 colors
- NiceKype branding and application metadata

### Changed

- Improved handling of consecutive or overlapping flash effects
- Improved Key Light HTTP communication
- Improved Counter-Strike 2 installation path normalization
- Improved Steam library detection
- Redesigned navigation tabs
- Added custom dark scrollbars and UI controls
- Converted all user-facing application text to English

### Known Limitations

- Alpha software may still contain bugs
- Elgato Key Lights must be reachable over the local network
- Counter-Strike 2 must be restarted after installing or repairing the GSI configuration if the game is already running
- The application is currently distributed for Windows x64 only
- The executable is currently unsigned and may trigger a Windows SmartScreen warning
