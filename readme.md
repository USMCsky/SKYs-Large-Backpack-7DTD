![Xml](https://img.shields.io/badge/XML?style=for-the-badge)
![7DTD](https://img.shields.io/badge/7DTD-Mod?style=for-the-badge)
![Author](https://img.shields.io/badge/USMCsky?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
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

LargeBackpackMod/
├── ModInfo.xml          # Core mod metadata file.
├── Config/
│   ├── entityclasses.xml  # Defines the core entities used in the mod.
│   ├── loot.xml           # Configuration for item drops and loot tables.
│   ├── XUi/               # UI definitions folder.
│   │   ├── windows.xml    # Main window layouts.
│   │   ├── controls.xml   # Specific control elements.
│   │   └── xui.xml        # General UI structure.
│   └── XUi_Common/        # Shared UI components and styles.
│       └── styles.xml     # Global styling definitions.

### Installation

1.  Place the `LargeBackpackMod` folder into your game's mods directory.
2.  Have fun being a pack rat!
