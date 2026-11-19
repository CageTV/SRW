# Savage Requiem World (non-Requiem build), pre-release

Pre-release backup. Not yet reviewed for publication on Nexus.

## What is in this repository
- `Savage Requiem World.esp` and `Savage Requiem World_LLOS.ini`: the base plugin (animal and creature AI, factions, NPCs, survival foods, herds).
- `SKSE/Plugins/`: Creature Behaviour 0.1.0 (SKSE DLL, GPL-3.0) and its rule files. The DLL re-applies the plugin's records when another mod overrides them.
- `Optional/`: two add-on plugins that need extra mods (see below). The base plugin does not need them.
- `Source/CreatureBehaviour/`: source of the DLL (GPL-3.0).

## Not in this repository
`Savage Requiem World.bsa` (1.69 GB of meshes and textures) is too large for GitHub. It will be uploaded to Nexus. The plugin needs it next to it, with the same name.

## Requirements (base plugin)
Skyrim Special Edition, SKSE64, Address Library for SKSE Plugins, the four official DLCs, `ccBGSSSE001-Fish.esm`, `ccQDRSSE001-SurvivalMode.esl`, `ccEEJSSE001-Hstead.esm`, `ccBGSSSE037-Curios.esl`, and Unofficial Skyrim Special Edition Patch.

## Optional plugins
- `Savage World - Wolf Pups.esp`: no-stagger attack data for 36 young animals. Needs SkyTEST, Animallica, Savage Skyrim Std and Skyrim Immersive Creatures SE.
- `Savage World - Creature Lists.esp`: 28 creature lists. Needs the same four mods.

## Licence
The DLL and its source are GPL-3.0 (see `SKSE/Plugins/CreatureBehaviour-LICENSE.txt`).
