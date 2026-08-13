# AKINO's City Builder Pack

A city-building focused Minecraft modpack for **Minecraft 1.21.1** built on **Fabric Loader 0.19.3**, packed with transit, construction, and decoration tools for large-scale builds.

> **Important:** This modpack is **not synced/updated on CurseForge**. It is maintained and distributed via this GitHub repository only. Pull requests and issues are welcome.

## Requirements

| Item      | Requirement                          |
|-----------|--------------------------------------|
| Minecraft | 1.21.1                               |
| Loader    | Fabric Loader 0.19.3 + Fabric API    |
| Java      | 21 or newer                          |
| RAM       | 4 GB+ (6 GB recommended)             |
| Launcher  | CurseForge, Prism, ATLauncher, etc.  |

## Highlights

- **Transit & Railways** – MTR (Minecraft Transit Railway), MTA, and block-based rail/road kits for full transit networks.
- **Construction Tools** – WorldEdit, Litematica, Effortless Building, Axiom, Create-style block palettes, plus freecam and tweakeroo for precision work.
- **Building & Decoration** – Yuushya, Handcrafted, Beautify, Another Furniture, Supplementaries, Macaw's doors/windows/furniture/lights/stairs/fences, Paladin's Furniture.
- **Villagers & Cities** – More Villagers, Better Villages, Villager API for lively settlements.
- **Storage & Utility** – Tom's Storage, Elevators, Shulker Box Tooltip, Inventory Profiles Next, Xaero's Maps.
- **Performance** – Sodium, Lithium, FerriteCore, ModernFix, BadOptimizations, Dynamic FPS.

## Installation

1. Install a compatible launcher (e.g. CurseForge).
2. Download this modpack (as an archive or via the launcher's "Import" feature using `minecraftinstance.json`).
3. Ensure **Fabric Loader 0.19.3** for Minecraft 1.21.1 is installed.
4. Launch with **Java 21+** and at least **4 GB** of allocated RAM.

## Directory Structure

```
config/            Mod configuration files
mods/              All mod JARs (MTR is stored via Git LFS)
pfm/               Paladin's Furniture custom furniture pack
saros_road_blocks_mod/  Saros road blocks & signs mod resources
villagerpacks/     Villager texture packs
datapacks/         Custom data packs
```

## Notes

- The **MTR mod JAR exceeds GitHub's 100 MB per-file limit**, so it is distributed via **Git LFS**. When cloning, run `git lfs pull` (or clone normally if LFS is set up) to download it.
- World saves (`saves/`) and machine-specific files (logs, caches, `user-prefs.json`, `.fabric/` remap cache) are intentionally **excluded** from this repository via `.gitignore`.

## License

The modpack configuration is provided as-is. Individual mods, resource packs, and assets retain their own licenses; refer to each mod's page for redistribution terms.
