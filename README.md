# Savage Requiem World (non-Requiem build), 0.2.0 pre-release

Animal and creature AI, factions, NPCs, survival foods, wild horse herds and spawn points for Skyrim Special Edition, with the Creature Behaviour SKSE plugin.

## What is in this repository
- `Savage Requiem World.esp` and `Savage Requiem World_LLOS.ini`: the plugin.
- `SKSE/Plugins/`: Creature Behaviour 0.2.0 (SKSE DLL, GPL-3.0), its rule file `enforce.json` and the spawn points.
- `Optional/`: the Wolf Pups add-on.
- `Source/CreatureBehaviour/`: source of the DLL (GPL-3.0).

## Requirements
- Skyrim Special Edition or Anniversary Edition 1.6.1170 or newer (including 1.7.x), SKSE64, Address Library for SKSE Plugins. The DLL is the new build only; there is no build for older Skyrim versions or Skyrim VR.
- The official masters (Skyrim, Update, Dawnguard, Hearthfires, Dragonborn). No Creation Club file, no Unofficial Patch, no other mod is a master.
- `Savage Requiem World.bsa` next to the plugin (the plugin and the archive share the name). It is not in this repository (1.69 GB).
- Savage Skyrim: the bear, wolf and fox coat variants use meshes that come with it. Without it those variants have no mesh.
- A new game: the horse herds moved, so an older save keeps the old herd positions.

## Optional
- `Optional/Savage World - Wolf Pups.esp`: no-stagger attack data for 36 young animals. Needs SkyTEST, Animallica, Savage Skyrim Std and Skyrim Immersive Creatures SE as masters. The base plugin does not need it.
- The lists the old `Savage World - Creature Lists.esp` made (creatures of Animallica, Skyrim Immersive Creatures, SkyTEST and SRW added to the vanilla creature lists) are now rules in the DLL: they apply to the mods you have and skip the others. Do not use the old plugin with this version.

## Changes in 0.2.0
- The plugin needs only the five official masters. The Creation Club and Unofficial Patch masters are gone; 214 dead links (210 of them pointed at Requiem records through the Curios file) were removed.
- Three horse herds that stood in Whiterun and near it moved to sites at least 4 cells from any settlement.
- Spawn points of wolves, cats, elk and generic prey inside the settlement zone were removed (55 in each points file).
- Creature Lists are rules in the DLL now.
- The DLL has rules for leveled lists, race and NPC spells and perks, and a Requiem layer that does nothing without Requiem.esp.

## Licence and credits
The DLL and its source are GPL-3.0 (see `SKSE/Plugins/CreatureBehaviour-LICENSE.txt`). See `CREDITS.txt`.
