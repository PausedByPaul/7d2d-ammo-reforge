# Ammo Reforge Mod for 7 Days to Die

A mod that allows players to convert ammunition between different calibers at a workbench.

**Version**: 1.0  
**Compatible with**: 7 Days to Die V2.4

## Features

- Convert between 9mm, 7.62mm, .44 Magnum, and Shotgun Shells
- Convert between Iron/Steel Arrows and Crossbow Bolts
- Creates vanilla ammo that works with all weapons
- Balanced conversion rates based on vanilla recipe yields with ~25% reforging penalty
- Requires a workbench and minimal additional resources (gunpowder or paper)
- Multiple alternative recipes for each ammo type based on what you have available

## Installation

1. Copy the entire `7d2d-ammo-reforge` folder to your 7 Days to Die Mods folder:
   - **Windows**: `%APPDATA%\7DaysToDie\Mods\` or `<Steam>\steamapps\common\7 Days To Die\Mods\`
   - **Linux**: `~/.local/share/7DaysToDie/Mods/`
   - **Mac**: `~/Library/Application Support/7DaysToDie/Mods/`

2. Restart the game if it's running

## Conversion Rates

The mod uses balanced conversion rates based on the vanilla crafting yields:

| From | To | Input | Output | Notes |
|------|----|----|--------|-------|
| 9mm | 7.62mm | 6 + 1 gunpowder | 3 | 9mm makes 6/recipe, 7.62 makes 4/recipe |
| 9mm | .44 Magnum | 6 + 1 gunpowder | 3 | |
| 9mm | Shotgun Shells | 6 + 1 paper | 3 | |
| 7.62mm | 9mm | 4 + 1 gunpowder | 5 | |
| 7.62mm | .44 Magnum | 4 + 1 gunpowder | 3 | |
| 7.62mm | Shotgun Shells | 4 + 1 paper | 3 | |
| .44 Magnum | 9mm | 4 + 1 gunpowder | 5 | |
| .44 Magnum | 7.62mm | 4 + 1 gunpowder | 3 | |
| .44 Magnum | Shotgun Shells | 4 + 1 paper | 3 | |
| Shotgun Shells | 9mm | 4 + 1 gunpowder | 5 | |
| Shotgun Shells | 7.62mm | 4 + 1 gunpowder | 3 | |
| Shotgun Shells | .44 Magnum | 4 + 1 gunpowder | 3 | |
| Iron Arrows | Iron Bolts | 5 | 4 | |
| Iron Bolts | Iron Arrows | 5 | 4 | |
| Steel Arrows | Steel Bolts | 5 | 4 | |
| Steel Bolts | Steel Arrows | 5 | 4 | |

## Balance Philosophy

- **Resource Parity**: Conversions respect the original crafting costs. If 1 recipe of 9mm uses the same resources as 1 recipe of 7.62mm, you get equivalent value out.
- **Reforge Penalty**: A ~25% material loss is applied to prevent infinite conversion loops from generating free ammo.
- **Additional Resources**: Conversions require 1 gunpowder or paper to represent the reforging process.
- **Vanilla Output**: All recipes create vanilla ammunition that works exactly like standard ammo - no compatibility issues with weapons.

## Requirements

- 7 Days to Die V2.4 (or compatible versions)
- A workbench to access the reforge recipes

## How to Use

1. Build or find a workbench
2. Collect ammunition of any caliber you want to convert
3. Gather gunpowder or paper as additional ingredients
4. Open the workbench crafting menu
5. Each ammo type will show alternative recipes based on different input ammunition
   - Example: 7.62mm ammo can be crafted from 9mm, .44 Magnum, or Shotgun Shells
   - Choose the recipe that uses the ammo type you have in surplus

No schematics or unlocks required - all conversion recipes are available immediately!

## Compatibility

This mod uses XPath appending to add alternative crafting recipes for vanilla ammunition items. It does not modify any existing vanilla items or recipes, making it compatible with most other mods.

**Technical Details**: The mod adds multiple recipes with the same output item (vanilla ammo) but different ingredients. The game shows these as alternative crafting options in the workbench menu.

## License

Free to use and modify. Attribution appreciated but not required.
