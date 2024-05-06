# Fallout 2 Adjustments

The mod is available to anyone, but it is not meant as a public release and might not adhere to all standards of one. It's something I wrote and used for myself in my own playthroughs.

This is a collection of minimalistic mods that aim to keep the game largely vanilla and either:

1. Fix certain game imbalances.
2. Add some quality of life features.
3. Put optional restrictions on the player for a more challenging playthrough.

The mod is fully modular. Each component can be disabled in the `.ini` file.

## Components

- Price cap
  - Prevents buying for a lower price than what you sell for, avoiding one of the ways to break the economy.
- Level cap
  - Puts an optional level cap on the player to make the game harder. You will still accumulate experience as normal after reaching the cap, but you won't get another level.

More explanations in `mods\fallout-2-adjustments.ini`.

## Installation

The mod requires [Sfall](https://github.com/sfall-team/sfall). Sfall is already included with [Restoration Project, updated](https://github.com/BGforgeNet/Fallout2_Restoration_Project).

To install the mod:

1. Put the contents of the `mods` folder (the `fallout-2-adjustments` folder and `fallout-2-adjustments.ini`) to your `mods` folder.
2. If you have `mods_order.txt` inside your `mods` folder, add `fallout-2-adjustments` to it.
3. To configure settings, edit `fallout-2-adjustments.ini`.

To uninstall, delete the files. To disable without deleting, remove the line from `mods_order.txt`.

## Compatibility

If two mods change the same thing, disable the affected component in one or the other. You can always disable any component in my mod. For example, if you are using custom keyboard controls in [FO2tweaks](https://github.com/BGforgeNet/FO2tweaks/), disable them in my mod.

## Recommended mods

- [Restoration Project, updated](https://github.com/BGforgeNet/Fallout2_Restoration_Project)
- [Pixote's updated RP maps](https://www.nma-fallout.com/threads/pixotes-updated-rp-maps.222207/)
  - Maps for Restoration Project that look closer to the original game.
- [FO2tweaks](https://github.com/BGforgeNet/FO2tweaks/)
  - Contains a good damage formula with options to disable everything else, if needed.