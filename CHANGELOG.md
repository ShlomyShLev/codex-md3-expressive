# Changelog

## [0.1.0] - 2026-10-10

Initial Codex edition, derived from Claude MD3 Expressive 0.1.0.

### Added

- Codex skill with automatic discovery, explicit `$codex-md3-expressive` invocation, MCP dependency metadata, and six design references.
- Portable plugin manifest, Codex compatibility manifest, and repository marketplace.
- Local MCP wiring using the plugin working directory rather than Claude path variables.
- Eight MCP tools and 18 ready-made components retained from the original kit.
- Linter with 23 rules, contrast checker, design tokens, demo, screenshots, and generated CSS and JavaScript.
- Existing tests adapted to Codex packaging and installation documentation.
- Standalone skill and MCP installation instructions for Codex users who do not use plugin marketplaces.

The original project and MIT attribution are preserved. Local validation on Windows on 2026-10-10: generated asset build succeeded and all 49 tests passed, including MCP startup, handshake, and calls to all eight tools. Plugin installation inside Codex remains untested.
