# Fallout 2 Adjustments

This is a collection of minimalistic mods that aim to keep the game largely vanilla and either:

1. Fix game imbalances.
2. Add quality of life features.
3. Put optional restrictions on the player for a more challenging playthrough.

The mod is fully modular. Each component can be disabled in the `.ini` file. Disabled components will not be running and won't take any resources.

## Components

- Custom keyboard controls. Default settings:
  - The keys for opening inventory and skilldex now also close them. The key for inventory also closes the "looting containers" window and the "use inventory item on" (the backpack icon) window.
  - `E`: Inventory.
  - `Q`: Pip-Boy. "Q" for "Quests".
  - `V`: Center camera on the player. "V" for "View".
  - Save and loading keys are changed to be further apart and harder to mix up accidentally:
    - `F4`: Save game (unchanged).
    - `F5`: Quick save.
    - `F8`: Quick load.
    - `F9`: Load game.
- Price cap.
  - Prevents buying for a lower price than what you sell for, avoiding one of the ways to break the economy.
- Level cap.
  - Disabled by default. Puts an optional level cap on the player to make the game harder. You will still accumulate experience as normal after reaching the cap, but you won't get another level.
- Equipment restrictions.
  - Disabled by default. Puts optional restrictions on armor and weapons the player can use. For example, you can restrict all kinds of power armor for a "no power armor" playthrough.
- Party members' skills do not replace the player's skills.
  - The unfixed mechanic in the vanilla game made certain skills largely irrelevant, allowing you to rely on companions instead of investing in your own skills.
  - Prevents a party member's barter skill replacing the player's barter skill.
  - Prevents a party member's outdoorsman skill replacing the player's outdoorsman skill.
- Armor penalty.
  - Heavy armor penalizes sneak skill, by a percentage, depending on armor weight. All kinds of leather armor are light enough for a 0% penalty. The heaviest armor in the game = 100% penalty (meaning sneak becomes 0). You won't be able to put on armor while in sneak mode.
  - To see the current penalty, open the character screen while in sneak mode. Once you do this, a text message will be added.
- Settings transfer.
  - Disabled by default. A tool to help you automatically transfer settings between old and new `.ini` files. Useful when updating mods if you have a lot of custom settings.

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

- [Restoration Project, updated](https://github.com/BGforgeNet/Fallout2_Restoration_Project). Recommended components:
  - NPC Armor Mod.
  - Talking Head for Cassidy.
  - Cassidy Voice by Joey Bracken.
  - Hero Appearance.
  - Alternative Explosions.
    - Explosion animations from Fallout Tactics.
  - Extended Flamer Attack Animations.
    - It fixes flamer attacks when increasing game speed in Sfall's settings.
- [Pixote's updated RP maps](https://www.nma-fallout.com/threads/pixotes-updated-rp-maps.222207). Also available on [Nexus Mods](https://www.nexusmods.com/fallout2/mods/73).
  - Maps for Restoration Project that look closer to the original game.
- [FO2tweaks](https://github.com/BGforgeNet/FO2tweaks).
  - Contains a good damage formula and some quality of life features. There are options to disable everything you don't need. Be careful when disabling changes to knockback, you need to put "-1" instead of "0".