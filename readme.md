# Large Backpack Mod

This project is a mod designed for 7 DAYS TO DIE, focusing on enhancing the backpack with 96 slots.
The mod uses XML patches to update player inventory stats, dropped-backpack storage, and the in-game backpack UI.
Updated for 7DTD V3.0.

## 🌟 Features

*   **Player Inventory Patch:** Increases `CarryCapacity` and `BagSize` in `entityclasses.xml`.
*   **Dropped Backpack Patch:** Resizes the `playerBackpack` loot container in `loot.xml`.
*   **V3.0 XUi Patch:** Updates the V3.0 `XUi_InGame` backpack and looting windows to display all 96 slots.

## 📁 Project Structure
<code>
The project follows a modular structure, with configuration files separated by concern:
└── Mods
    └── LargeBackpackMod
        ├── ModInfo.xml
        └── Config
            ├── entityclasses.xml
            ├── loot.xml
            └── XUi_InGame
                ├── windows.xml
                └── xui.xml
</code>

### Installation

1.  Place the `LargeBackpackMod` folder into your game's mods directory.
2.  Remove any older duplicate copy from `%AppData%\7DaysToDie\Mods` or the game can load that version first.
3.  Have fun being a pack rat!
