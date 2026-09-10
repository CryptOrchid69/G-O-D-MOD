# G-O-D MOD Installation Guide

## Step-by-Step Installation

### Step 1: Locate No Man's Sky GAMEDATA/MODS Folder
- Open your file explorer
- Navigate to your No Man's Sky installation directory
  - **Default Windows location:** `C:\Program Files\Steam\steamapps\common\No Man's Sky`
  - **Default Epic Games location:** `C:\Program Files\Epic Games\NoMansSky`
- Open the `GAMEDATA` folder
- Open the `MODS` folder inside GAMEDATA

### Step 2: Add G-O-D-MOD Folder
- Clone or download all files from the G-O-D-MOD GitHub repository
- The repository is already structured as the `G-O-D-MOD` folder
- Copy the entire `G-O-D-MOD` folder into `GAMEDATA/MODS/`

### Step 3: Verify Installation
Your folder structure should look like:
```
No Man's Sky/
├── GAMEDATA/
│   ├── MODS/
│   │   ├── G-O-D-MOD/
│   │   │   ├── MODINFO.XML
│   │   │   ├── PlayerData.xml
│   │   │   ├── BuildingData.xml
│   │   │   ├── TechModifications.xml
│   │   │   ├── README.md
│   │   │   ├── INSTALLATION_GUIDE.md
│   │   │   └── FEATURES.md
│   │   └── [other mods if present]
│   └── [other GAMEDATA folders]
└── [other game files]
```

### Step 4: Launch the Game
- Start No Man's Sky
- The mod will automatically load when the game initializes
- You should immediately notice the effects
- Works in both single-player and multiplayer modes

## Verification Checklist

- [ ] G-O-D-MOD folder is in GAMEDATA/MODS
- [ ] All mod files are present in the G-O-D-MOD folder
- [ ] MODINFO.XML is present
- [ ] Game launches without errors
- [ ] You have invincibility (test by taking damage)
- [ ] Exosuit shows max tech modifications
- [ ] Multitool shows max tech modifications
- [ ] Unlimited ammo and jetpack are active
- [ ] Building works without materials

## Multiplayer Mode

The G-O-D MOD works fully in multiplayer mode:
- All features remain active when joining multiplayer sessions
- Invincibility, unlimited resources, and building work with other players
- Max tech modifications are visible to your character
- Compatible with No Man's Sky's multiplayer system

## Troubleshooting

**Mod not loading?**
- Ensure folder is named exactly `G-O-D-MOD` (case-sensitive on some systems)
- Check that all required files are present in the correct folder
- Verify GAMEDATA/MODS folder path is correct
- Ensure you copied the folder INTO MODS, not created a subfolder

**Game crashes on startup?**
- Remove the G-O-D-MOD folder from MODS and verify the game runs normally
- Check that XML files are properly formatted
- Reinstall mod files fresh from repository

**Features not working?**
- Restart the game completely
- Create a new save file to ensure mod is applied from the start
- Check in-game settings for any mod-related options

**Multiplayer issues?**
- Verify all mod files are intact
- Restart the game before joining multiplayer
- Check your internet connection

## Uninstallation

To remove the mod:
1. Delete the `GAMEDATA/MODS/G-O-D-MOD` folder
2. Restart No Man's Sky
3. Game will run with original settings

---

**Need help?** Check the README.md or FEATURES.md, or create an issue on the GitHub repository.
