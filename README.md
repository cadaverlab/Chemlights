```text
 ▄████▄    ▄▄▄       ▓█████▄   ▄▄▄       ██▒   █▓  ▓█████  ██▀███  
▒██▀ ▀█   ▒████▄     ▒██▀ ██▌ ▒████▄     ▓██░   █▒ ▓█   ▀  ▓██ ▒ ██▒
▒▓█    ▄  ▒██  ▀█▄   ░██   █▌ ▒██  ▀█▄   ▓██  █▒░  ▒███    ▓██ ░▄█ ▒
▒▓▓▄ ▄██▒ ░██▄▄▄▄██  ░▓█▄   ▌ ░██▄▄▄▄██  ▒██ █░░   ▒▓█  ▄  ▒██▀▀█▄ 
▒ ▓███▀ ░  ▓█   ▓██▒ ░▒████▓   ▓█   ▓██▒  ▒▀█░  ░  ░▒████▒ ░██▓ ▒██▒
░ ░▒ ▒  ░  ▒▒   ▓▒█░  ▒▒▓  ▒   ▒▒   ▓▒█░   ░ ▐░    ░░ ▒░ ░ ░ ▒▓ ░▒▓░
  ░  ▒      ▒   ▒▒ ░  ░ ▒  ▒    ▒   ▒▒ ░   ░ ░░     ░ ░  ░   ░▒ ░ ▒░
░           ░   ▒     ░ ░  ░    ░   ▒        ░░       ░       ░░   ░ 
            ░   ░       ░       ░   ░         ░                ░    
```

# CHEMLIGHTS for Ostranauts
**By Cadaver** | [![Game: Ostranauts](https://img.shields.io/badge/Game-Ostranauts-blue.svg)](#)

> Phoebus-brand chemical lights in cyan, blue, red, and green. Sold in bundles of five at station supply kiosks, and found in derelicts and kits.

Hold one to light your way, or drop them to mark a safe route through a dark derelict.

---

## Features

* **Dynamic Lighting:** Crack one and it lights up fully within seconds.
* **Immersive Lifespan:** Stays bright for a while, then fades over 30 minutes of game time, goes out, and crumbles and disappears two minutes later.
* **Ambient Glow:** Light shines through backpacks and pockets at reduced brightness. *Will add more immersive states later.

> [!CAUTION]
> **You can eat it. Don't. But you can**

---

## Installation

This mod requires two parts to function properly: the data mod (adds the items) and the plugin (handles fading and burning out mechanics). **Install both.**

### 1. Data Mod
* **Steam Workshop:** Subscribe to the mod, then enable `ChemLights` in the game's Mods menu.
* **Manual Install:** Copy the `ChemLights` folder to `Ostranauts_Data/Mods/ChemLights` and add `"ChemLights"` to the `aLoadOrder` array in `Ostranauts_Data/Mods/loading_order.json`.

### 2. Plugin
*Requires [BepInEx 5](https://github.com/BepInEx/BepInEx) installed in your game folder.*
* Copy `ChemLights.dll` from this mod's `BepInEx/plugins/ChemLights/` folder into your game's `BepInEx/plugins/ChemLights/` directory.
* *Note: The Steam Workshop cannot install this .dll file for you automatically.*

> [!TIP]
> **Console Spawning**  
> Open the console (`` ` `` backtick key) and run:
> ```bash
> spawn ItmChemLightBundle01Cyan
> ```
> Replace `Cyan` with `Blue`, `Red`, or `Green` for other colors.

---

## Interactions & Controls

| Action | Description |
| :--- | :--- |
| **Bundle** | Open like a pill bottle and drag sticks out first. If you crack one inside the bundle, it drops to your feet. An empty bundle turns into trash. |
| **Crack** | Right-click a sealed stick and select **Crack**. |
| **Equip** | Hold a lit stick in your hands to fully illuminate the path in its color. |
| **Carry** | Lit sticks in pockets or on suit clips still glow dimly. Sticks inside a backpack glow through at minimal brightness. |
| **Drop** | Drag onto the floor next to your character, or right-click and select **Drop**. |
| **Eat** | Can be consumed on any stick, even with a helmet on. Strongly not recommended. |
| **Stacking** | Sealed sticks stack up to five in your inventory, matching pills. |
