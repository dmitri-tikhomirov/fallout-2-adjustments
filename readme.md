# Fallout 2 Adjustments

This is a collection of minimalistic mods that aim to keep the game largely vanilla and either:

1. Fix game imbalances.
2. Add quality of life features.
3. Put optional restrictions on the player for a more challenging playthrough.

The mod is fully modular. Each component can be disabled in the `.ini` file. Disabled components will not be running and won't take any resources.

## Components

- Price cap.
  - Prevents buying for a lower price than what you sell for, avoiding one of the ways to break the economy.
- Custom keyboard controls. Default settings:
  - Keys for opening Inventory and Skilldex now also close them.
  - `E`: Inventory.
  - `Q`: Pip-Boy. "Q" for "Quests".
  - `V`: Center camera on the player. "V" for "View".
  - Save and loading keys are changed to be further apart and harder to mix up:
    - `F4`: Save game (unchanged).
    - `F5`: Quick save.
    - `F8`: Quick load.
    - `F9`: Load game.
- Level cap.
  - Disabled by default. Puts an optional level cap on the player to make the game harder. You will still accumulate experience as normal after reaching the cap, but you won't get another level.
- Equipment restrictions.
  - Disabled by default. Puts optional restrictions on armor and weapons the player can use. For example, you can restrict all kinds of power armor for a "no power armor" playthrough.
- Party members' skills do not replace the player's skills.
  - Prevents a party member's barter skill replacing the player's barter skill. The unfixed mechanic in vanilla game made the barter skill largely irrelevant, allowing you to rely on companions instead of investing in your own skill.
- Settings transfer.
  - Disabled by default. A tool to help you automatically transfer settings between old and new `.ini` files. Useful when updating mods if you have a lot of custom settings. Do not enable if you are not sure what exactly this component does.

More explanations in `mods\fallout-2-adjustments.ini`.

## Installation

The mod requires [Sfall](https://github.com/sfall-team/sfall). Sfall is already included with [Restoration Project, updated](https://github.com/BGforgeNet/Fallout2_Restoration_Project).

To install the mod:

1. Download the mod: Above the list of files, click "<> Code" then "Download ZIP".
1. Put the contents of the `mods` folder (the `fallout-2-adjustments` folder and `fallout-2-adjustments.ini`) to your `mods` folder.
1. If you have `mods_order.txt` inside your `mods` folder, add `fallout-2-adjustments` (this exact line) to it.
1. To configure settings, edit `fallout-2-adjustments.ini`.

To uninstall, delete the files. To disable without deleting, remove the line from `mods_order.txt`.

## Compatibility

If two mods change the same thing, disable the affecting component in one or the other. You can always disable any component in my mod. For example, if you are using custom keyboard controls in [FO2tweaks](https://github.com/BGforgeNet/FO2tweaks), disable them in my mod.

## Recommended mods

For a close to vanilla but improved experience:

- [Restoration Project, updated](https://github.com/BGforgeNet/Fallout2_Restoration_Project)
- [Pixote's updated RP maps](https://www.nma-fallout.com/threads/pixotes-updated-rp-maps.222207)
  - Maps for Restoration Project that look closer to the original game.
- [FO2tweaks](https://github.com/BGforgeNet/FO2tweaks)
  - Contains a good damage formula with options to disable everything else, if needed.

For a different gameplay experience:

- [EcCo Gameplay Overhaul](https://github.com/phobos2077/fo2_ecco)
- [Fallout2MechanicsMiniRework](https://github.com/dekrus/Fallout2MechanicsMiniRework)