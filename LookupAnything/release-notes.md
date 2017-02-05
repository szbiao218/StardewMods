﻿[← back to readme](README.md)

# Release notes

## 1.10
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.9...lookup-anything/1.10).

* You can now lookup an item from the kitchen cooking menu.
* You can now lookup map tile info (disabled by default).
* Updated to SMAPI 1.8.
* Updated new-version-available check.

## 1.9
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.8...lookup-anything/1.8).

* Villager lookups now highlight gifts you carry or own.
* Added optional data mining fields which show raw game data.
* You can now click on the up/down arrows to scroll content.
* Improved controller support:
  * You can now lookup what's directly in front of you using a separate hotkey. (Not bound by default.)
  * Fixed controller thumbsticks scrolling content too slowly.
  * Fixed controller button conventions not respected by lookup menu.
* Fixed a rare error caused by the game duplicating an NPC.
* Fixed fruit tree quality schedule being wrong in some cases.
* Fixed input bindings in `config.json` being case-sensitive.
* Fixed input bindings in `config.json` being discarded silently if invalid.

## 1.8
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.7...lookup-anything/1.8).

* Added museum donations to item 'needed for' field.
* You can now lookup things behind trees when you're behind them.
* You can now close the lookup UI by clicking outside it.
* Updated to SMAPI 1.3.
* Fixed incorrect farmer luck message when the spirits are feeling neutral.
* Fixed social menu lookup sometimes showing the wrong villager.

## 1.7
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.6...lookup-anything/1.7).

* You can now lookup a villager from the social page.
* You can now lookup an item from the toolbar.
* Console logs are now less verbose.
* Updated to SMAPI 1.1.
* Fixed some cases where the item 'number owned' field was inacurate.
* Fixed iridium prices being shown for items that can't have iridium quality.
* `F2` debug mode is no longer suppressed (removed in latest version of SMAPI).

## 1.6
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.5...lookup-anything/1.6).

* Added support for Linux and Mac.
* Added item 'needed for' field for community center bundles, full shipment achievement, and polyculture achievement.
* Added item 'sells to' field.
* Added item number owned field.
* Added fruit tree quality schedule.
* Added support for looking up shop items.
* Added `data.json` validation on startup.
* Disabled lookups when game rendering mode breaks Lookup Anything (only known to happen in the Stardew Valley Fair).
* Fixed sale price shown for unsellable items.
* Fixed update-check error on startup adding scary error text in console.
* Fixed incorrect gift tastes by deferring more to the game code (slower but more accurate).
* Fixed error when looking up a villager you haven't met.
* Fixed error when looking up certain NPCs with no social data.

## 1.5
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.4...lookup-anything/1.5).

* You can now lookup a villager from the calendar.
* You can now lookup items from an open chest.
* Added cask aging schedule.
* Added better NPC friendship fields which account for dating and marriage.
* Added marriage stardrop to heart meter.
* Added support for new iridium quality.
* Added debug log.
* Added option to suppress SMAPI's `F2` debug hotkey, which can have unintended consequences like skipping an entire season or teleporting into walls.
* Fixed gift tastes not handling precedence when NPCs are conflicted about how they feel.
* Fixed error when screen resolution is too small to display lookup UI.
* Fixed error when calculating a day offset that wraps into the next year.
* Fixed errors crashing the game in rare cases.

## 1.4
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.3...lookup-anything/1.4).

* Updated for Stardew Valley 1.1:
  * added new fertile weeds (forest farm) and geode stones (hilltop farm);
  * added new recipes for coffee, mead, sugar, void mayonnaise, and wheat flour;
  * updated for Gold Clock preventing fence decay;
  * updated to latest binaries & increased minimum versions.
* Fixed a few missing stones & weeds.

## 1.3
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.2...lookup-anything/1.3).

* Added possible drops and their probability to monster lookup.
* Added item icons to crafting output, farm animal produce, and monster drops.
* Fixed item gift tastes being wrong in some cases.
* Fixed monster drops showing 'error item' in rare cases.
* Fixed fields being shown for dead crops.
* Internal refactoring.

## 1.2
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.1...lookup-anything/1.2).

* On item lookup:
  * added crop info for seeds;
  * added recipes for the charcoal kiln, cheese press, keg, loom, mayonnaise machine, oil maker,
    preserves jar, recycling machine, and slime egg-press;
  * merged recipe fields;
  * fixed an error when displaying certain recipes.
* Added optional mode which hides the lookup UI when you release the button.
* `F1` now toggles the lookup UI (i.e. will close the lookup if it's already open).

## 1.1
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/1.0...lookup-anything/1.1).

* On item lookup:
  * removed crafting recipe;
  * added crafting, cooking, and furnace recipes which use this item as an ingredient.
* Added error if game or SMAPI are out of date.

## 1.0
See [log](https://github.com/Pathoschild/StardewMods/compare/lookup-anything/601d3c7964c5f2448f2791cd6f7205cb0b2f0835...lookup-anything/1.0).

* Initial version.
* Added support for NPCs (villagers, pets, farm animals, monsters, and players), items (crops and
   inventory), and map objects (crafting objects, fences, trees, and mine objects).
* Added controller support and configurable bindings.
* Added hidden debug mode.
* Added version check on load.
* Let players lookup a target from any visible part of its sprite.
