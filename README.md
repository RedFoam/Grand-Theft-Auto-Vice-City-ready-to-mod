# GTA Vice City — Ready to Mod 🌴

## Everything You Need in One Place

This project was created to make modding **Grand Theft Auto: Vice City Classic (PC)** easier.

Instead of searching across multiple websites, tracking down individual patches, finding dependencies, and figuring out which files you need to get the game running properly on modern hardware, this repository brings essential files and useful mods together in one convenient place.

The goal is simple: **download the pack, copy the files into your GTA Vice City game folder, and get ready to play.**

This setup targets the **retail v1.0 executable** and combines compatibility improvements, bug fixes, controller support, widescreen support, extended draw distance, and extra gameplay features.

## 🔗 Check Out My GTA III Mod Pack

Looking to mod Liberty City instead? Check out the companion project!

🌆 **[GTA III — Ready to Mod](https://github.com/RedFoam/GTA-III-Ready-To-Mod)**

A convenient collection of fixes, modding tools, and improvements for the classic GTA III PC version.

## 📌 Game Version — Retail v1.0 Included

The **retail v1.0 executable (`gta-vc.exe`) is included in this pack** for compatibility with the intended classic PC setup.

Want the original download separately, or need another copy?

- **[GTA Vice City Original v1.0 EXE — ModDB](https://www.moddb.com/games/grand-theft-auto-vice-city/downloads/grand-theft-auto-vice-city-original-10-exe)**

Back up your existing executable before replacing it. This project is intended for the classic PC version, not Grand Theft Auto: Vice City — The Definitive Edition.

## 📦 Included Mods

### 🛠️ Core Modding Tools

| Mod | What It Does | Source |
|---|---|---|
| **Ultimate ASI Loader** | Loads ASI plugins required by many Vice City mods. | [GitHub](https://github.com/ThirteenAG/Ultimate-ASI-Loader) |
| **Mod Loader v0.3.10** | Organizes compatible mods into separate folders for easier installation and removal. | [Official v0.3.10 release](https://github.com/thelink2012/modloader/releases/tag/v0.3.10) |

### 🔧 Fixes and Modern Hardware Support

| Mod | What It Does | Source |
|---|---|---|
| **SilentPatchVC** | Fixes game bugs and improves stability and compatibility with modern systems. | [Silent's Blog](https://silentsblog.com/mods/gta-vc/#silentpatch) |
| **GInputVC** | Improves gamepad support, including XInput controller compatibility. | [Silent's Blog](https://silentsblog.com/mods/gta-vc/#ginput) |
| **VBDec** | Enables native playback of VB-format audio files. | [Silent's Blog](https://silentsblog.com/mods/gta-vc/#vbdec) · [GitHub](https://github.com/CookiePLMonster/VBdec) |
| **Widescreen Fix** | Improves support for widescreen monitors, modern resolutions, and HUD positioning. | [Documentation](https://github.fusionfix.io/wfp#gtavc) · [GitHub releases](https://github.com/ThirteenAG/WidescreenFixesPack/releases) |
| **Project2DFX** | Extends the draw distance of lights and other distant objects for a more detailed city at a distance. | [GitHub](https://github.com/ThirteenAG/III.VC.SA.IV.Project2DFX/releases/tag/gtavc) |
| **VCUnlock** | Provides higher rendering frame-rate options while maintaining the original game's simulation timing. | [GitHub](https://github.com/ilkaydnc/VCUnlock) |

### 🎮 Gameplay Additions

| Mod | What It Does | Source |
|---|---|---|
| **Money Messages** | Displays money notifications during gameplay. | [Silent's Blog](https://silentsblog.com/mods/gta-vc/#money-messages) · [GitHub](https://github.com/CookiePLMonster/Money-Messages) |
| **Destroyable Airtrain** | Allows the airtrain to be destroyed. | [Silent's Blog](https://silentsblog.com/mods/gta-vc/#destroyable-airtrain) · [GitHub](https://github.com/CookiePLMonster/Destroyable-Airtrain) |

## 🚀 Installation

Getting started is designed to be simple!

1. Download this repository.
2. Back up your existing GTA Vice City game files and saves.
3. Open your GTA Vice City installation folder — the folder containing `gta-vc.exe`.
4. **Copy the files and folders from this pack into your GTA Vice City game folder.**
5. Allow folders to merge where appropriate, and preserve the included folder structure.
6. Review any overwrite prompts carefully. Do not blindly replace existing DLLs or loader files.
7. Launch the game and verify that it works before adding any further modifications.

### Mod Loader Folder Structure

Mod Loader v0.3.10 requires Ultimate ASI Loader. For the standard installation layout, the relevant files should be arranged like this:

```text
GTA Vice City/
├── gta-vc.exe
├── dinput8.dll              (ASI loader, if using this filename)
├── modloader/
│   └── [individual mod folders]
└── scripts/
    └── modloader.asi
```

The actual loader filename may vary depending on the installed configuration. Avoid installing duplicate or competing ASI loaders.

When adding mods through Mod Loader, place each compatible mod in its own folder under `modloader/` and preserve the directory structure required by that mod.

## ⚙️ Requirements

- A legitimate PC copy of Grand Theft Auto: Vice City Classic.
- The **retail v1.0 executable**, included in this pack.
- A Windows PC.
- Ultimate ASI Loader for Mod Loader and other compatible ASI plugins.
- Any additional dependencies specified by individual mod authors.

## ⚠️ Important Notes

- Back up your original game files before installing or updating.
- This pack targets the retail v1.0 executable; other versions may not be compatible with every included mod.
- Avoid installing competing ASI loaders or graphics wrappers without checking compatibility.
- Do not blindly overwrite `dinput8.dll`, `d3d8.dll`, or other loader and wrapper files.
- Keep all mod files in their required folders.
- **SkyGfx is not included.**
- VCUnlock may conflict with other frame-rate or limit-adjustment modifications. Check its documentation before combining them.
- Some mods may require separate dependencies or additional configuration.
- If the game crashes, test the core setup first and add optional modifications one at a time.
- Compatibility can vary across systems. Do not assume every combination has been tested unless it has been verified.

## ❤️ Credits

Huge thanks to the developers and contributors who make the Vice City modding community possible, including Silent, CookiePLMonster, ThirteenAG, LINK/2012, and the VCUnlock developer.

Please visit the original mod pages for documentation, updates, support, and licensing information.

This is an unofficial community project and is not affiliated with or endorsed by Rockstar Games.

## 📜 License and Distribution

Third-party mods remain subject to their original licenses and redistribution terms. Please review those licenses before redistributing their files.

Where redistribution is not permitted, download the component directly from its original source. The external v1.0 executable link is provided for anyone who wants to obtain a separate copy.

---

## 🌆 More Classic GTA Mods

Want to explore Liberty City instead?

**[GTA III — Ready to Mod](https://github.com/RedFoam/GTA-III-Ready-To-Mod)**

The mission is simple: make getting GTA Vice City ready for modern hardware straightforward, convenient, and beginner-friendly — without forcing players to hunt through a dozen different websites just to get started.
