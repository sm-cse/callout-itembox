# Changelog

All notable changes to **calloutbox** are documented here. The format is based
on [Keep a Changelog](https://keepachangelog.com/), and the project aims to
follow semantic versioning.

## [1.1] - 2026-06-07

### Added
- `shadow=on` / `shadow=off` option for a soft drop shadow (off by default).

### Changed
- Lighter `red` theme background (RGB 252,238,232).

## [1.0] - 2026-06-07

### Added
- Initial release.
- `\callout` (heading + body) and `\callout*` (body only) commands.
- Built-in themes: `blue`, `red`, `teal`, `green`, `purple`, `orange`, `slate`.
- White dot marker, or numbered marker via `number=<n>`.
- `corners=sharp` (default) / `corners=rounded`, plus custom `arc=<len>`;
  the colored bar is clipped to follow the corner radius.
- One-off color overrides: `barcolor`, `bgcolor`, `headcolor`.
- Geometry tweaks: `barwidth`, `gap`.
- Breakable boxes.
