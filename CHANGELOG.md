# Changelog

## 1.8.1

- Locale: unified string keys (corrected English key spellings) across `Config.lua` and all `AllPlayed-*.lua` files; removed duplicate `enUS` entries.
- `Config.lua`: use `AP_display_name` for `GetAddOnMetadata`; replace deprecated `getfenv(0)` with `local _G = _G`; comment typo fixes.
- `AllPlayed.lua`: same `_G` initialization; rename `curent_xp` parameter to `current_xp` in `EstimateRestedXP`; comment typo fixes.
- `AllPlayed.toc`: `## Version` 1.8.1, `## X-Category`, `## IconTexture`.
- `embeds.xml`: comment wording / “embedded” spelling.
- Added `README.md` and this changelog.

## Earlier

Prior history not tracked in this repository; see upstream project or release archives if applicable.
