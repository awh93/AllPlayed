# AllPlayed

Tracks **time played**, **rested XP**, **gold**, and related stats for all characters (per realm/faction), with a LibDataBroker (LDB) feed and optional minimap button.

**Author:** IceDNicco (see `AllPlayed.toc`).

## Requirements

Bundled in this package:

- Ace3 (AceAddon, AceDB, AceConfig, AceGUI, AceLocale, …)
- LibAbacus-3.0, LibCrayon-3.0, LibQTip-1.0, LibDataBroker-1.1, LibDBIcon-1.0

Optional:

- **!ClassColors** — listed in `## OptionalDeps` for class color integration

## Commands

| Command     | Purpose                          |
|------------|-----------------------------------|
| `/ap`      | Open configuration / help         |
| `/allplayed` | Same as `/ap`                   |

Exact strings come from locale files (`L["/ap"]`, `L["/allplayed"]`).

## Configuration

- **Esc → Options → AddOns → AllPlayed**, or use `/ap` / the LDB minimap icon context menu.
- Settings are stored in `AllPlayedDB` (global saved variables).

## Files

| File            | Role                                      |
|-----------------|-------------------------------------------|
| `AllPlayed.toc` | Load order and metadata                   |
| `AllPlayed.lua` | Core addon logic                          |
| `Config.lua`    | Options UI (AceConfig + dropdown menus)   |
| `AllPlayed-*.lua` | Locale strings per client language    |
| `embeds.xml`    | Ace3 and other embedded libraries         |

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
