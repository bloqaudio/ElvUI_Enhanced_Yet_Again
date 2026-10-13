[![Package and release](https://github.com/bloqaudio/ElvUI_Enhanced_Yet_Again/actions/workflows/main.yml/badge.svg)](https://github.com/bloqaudio/ElvUI_Enhanced_Yet_Again/actions/workflows/main.yml)

# ElvUI Enhanced (Yet) Again

A lightweight plugin for [ElvUI](http://www.tukui.org) that adds essential quality-of-life features without duplicating what ElvUI already does well.

**Requires ElvUI version 13.54 or higher.**

**Current Version:** 4.3.23

**Supported WoW Versions:** Retail (Midnight 12.x), Wrath Classic (limited feature set, see [Version Support](#version-support))

## Installation

Install via [CurseForge](https://www.curseforge.com/wow/addons/elvui-enhanced-yet-again) or [Wago](https://addons.wago.io/addons/elvui-enhanced-yet-again), or clone this repository into your `Interface/AddOns` directory.

## Features

### Minimap
- **Location Panel** — Zone name and coordinates displayed above the minimap.
- **Minimap Button Bar** — Collects and skins addon minimap buttons into a movable bar with mouseover fade support.
- **Great Vault Launcher** — Optional minimap button that opens the Great Vault, plus a `/vault` slash command.

### Raiding
- **Raid Marker Bar** — Quick-access bar for placing target icons and world markers with modifier-key support.

### Equipment Manager
- **Spec-Based Gear Swap** — Automatically equips a configured equipment set when switching specializations.
- **Battleground Gear Swap** — Automatically equips a configured equipment set when entering PvP instances.
- **Equipment Set Overlay** — Displays equipment set names on bag and bank item slots.

### Paperdoll
- **Item Level Display** — Shows item levels on each slot in the character and inspect frames, color-coded relative to your average equipped item level.
- **Durability Display** — Shows durability percentages on your own equipped items with a color gradient, optionally for damaged items only.

### Tooltip
- **Raid Progression** — Shows raid kill progression on player tooltips (hold Shift) for Mythic, Heroic, Normal, and LFR, with short or long raid names. Each raid can be toggled individually:
  - **Battle for Azeroth** — Uldir, Battle of Dazar'alor, Crucible of Storms, The Eternal Palace, Ny'alotha
  - **Shadowlands** — Castle Nathria, Sanctum of Domination, Sepulcher of the First Ones
  - **Dragonflight** — Vault of the Incarnates, Aberrus the Shadowed Crucible, Amirdrassil the Dream's Hope
  - **The War Within** — Nerub-ar Palace, Liberation of Undermine, Manaforge Omega
  - **Midnight** — The Voidspire, The Dreamrift, March on Quel'Danas, Sporefall, The Venomous Abyss, The Unbinding of Kith'ix

### Datatext
- **Range** — Displays the distance to your current target.

## Configuration

All settings are located under the **ElvUI Enhanced (Yet) Again** section in the ElvUI configuration panel (`/ec`). Features are disabled by default. The addon registers its own ElvUI mover group for positioning the Minimap Button Bar and Raid Marker Bar.

## Version Support

- **Retail (Midnight 12.x)** — Full feature set.
- **Wrath Classic (3.4.3)** — Location Panel, Minimap Button Bar, Raid Marker Bar, and Range datatext only.

## Contributing

- Report bugs or request features: [GitHub Issues](https://github.com/bloqaudio/ElvUI_Enhanced_Yet_Again/issues)
- Source code: [GitHub Repository](https://github.com/bloqaudio/ElvUI_Enhanced_Yet_Again)

If you'd like an old v3 feature brought back, open an issue and it will be considered.

## License

MIT — see [LICENSE](LICENSE).
