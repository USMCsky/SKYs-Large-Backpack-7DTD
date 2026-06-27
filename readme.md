# Large Backpack Mod

This project is a mod designed for 7 DAYS TO DIE, focusing on enhancing the backpack with 96 slots. 
The mod utilizes XML configuration files to define entities, loot tables, and user interface elements.

## 🌟 Features

*   **Advanced Entity Definition:** Defines core game entities using `entityclasses.xml`.
*   **Custom Loot Generation:** Manages complex item drops and loot tables via `loot.xml`.
*   **Modular UI System (XUi):** Provides a structured way to build user interfaces through multiple XML definitions:
    *   `windows.xml`: Defines main window layouts.
    *   `controls.xml`: Specifies individual interactive controls.
    *   `xui.xml`: Contains general UI components and structures.
*   **Shared Styling:** Centralized styling for all UI elements in `XUi_Common/styles.xml`.

## 📁 Project Structure

The project follows a modular structure, with configuration files separated by concern:
└── Mods
    └── LargeBackpackMod
        ├── ModInfo.xml
        └── Config
            ├── entityclasses.xml
            ├── loot.xml
            ├── XUi
            │   ├── windows.xml
            │   ├── controls.xml
            │   └── xui.xml
            └── XUi_Common
                └── styles.xml


### Installation

1.  Place the `LargeBackpackMod` folder into your game's mods directory.
2.  Have fun being a pack rat!
