# Changelog

All notable changes to Hell Pine are documented here.

## [0.0.5] - 2026-11-09

### Added
- Semantic highlighting support (`semanticTokenColors`) so language servers (TypeScript, Rust, Java, …) match the TextMate colors.
- Token colors for functions, operators, regex, escape sequences, JSON/YAML keys and Markdown (headings, links, inline code, quotes, lists).

### Changed
- Brighter pine (`#5d7e80` → `#658789`) so keywords pass WCAG AA contrast.
- Brighter line numbers, cursor, text selection, keyboard focus border and menu hover.
- Unified background shades into four levels (mantle / base / raised / surface); removes the gutter seam.
- Breakpoints are now red; warning validation text is yellow instead of blue.
- Lowered minimum VS Code version to 1.70.
- Smaller icon; preview images no longer bundled in the extension.

### Fixed
- README manual-install instructions.
- Duplicate `entity.other.attribute-name` rule.

## [0.0.3]
- Preview images and README updates.

## [0.0.2]
- Initial public release.
