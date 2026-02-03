# Ammo Reforge Mod for 7 Days to Die

A mod that allows players to convert ammunition between different calibers at a workbench.

## Features

- Convert between 9mm, 7.62mm, .44 Magnum, and Shotgun Shells
- Convert between Iron/Steel Arrows and Crossbow Bolts
- Balanced conversion rates based on vanilla recipe yields
- Small reforging penalty (approximately 10-25% loss) to prevent infinite conversion exploits
- Requires a workbench and minimal additional resources

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
- **Reforge Penalty**: A ~10-25% material loss is applied to prevent infinite conversion loops from generating free ammo.
- **Additional Resources**: Most conversions require 1 gunpowder or paper to represent the reforging process and prevent exploits.

## Requirements

- 7 Days to Die
- A workbench to craft reforge recipes

## How to Use

1. **Learn base ammo recipes** through normal gameplay (perks, schematics, or by crafting)
2. **Reforge recipes unlock automatically** when you learn to craft both ammo types involved
   - Example: Once you can craft 9mm AND 7.62mm, the "9mm to 7.62mm" reforge unlocks
3. Build or find a workbench
4. Open the workbench crafting menu and search for "Reforge"

No additional schematics needed - reforge recipes unlock as you progress naturally!

## Compatibility

This mod uses XPath appending and should be compatible with most other mods. It does not modify any vanilla items or recipes directly.

## License

Free to use and modify. Attribution appreciated but not required.
