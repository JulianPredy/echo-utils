## Changelog 
## v1.0.0 - 2025-11-01 
### Added 
-New CLI command: echo-utils reverse 
### Fixed 
- Fix echo-utils reverse output trailing space 
## v1.2.0 - 2026-05-01 
### Added
-New 'ECHO_UTILS_TIMEOUT' environment variable to control request timeout. (#50)

### Fixed
- Handle empty input gracefully, avoiding crash when no data is piped. (#51)

### Security
- Prevent command injection via arguments by sanitising input. (#52)

### Breaking Changes
- Remove the legacy '--json' flag. Use '--format json' instead. (#53)

