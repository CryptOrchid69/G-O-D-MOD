# G-O-D MOD Installation Guide

## Step-by-Step Installation

### Step 1: Locate No Man's Sky GAMEDATA Folder
- Open your file explorer
- Navigate to your No Man's Sky installation directory
  - **Default Windows location:** `C:\Program Files\Steam\steamapps\common\No Man's Sky`
  - **Default Epic Games location:** `C:\Program Files\Epic Games\NoMansSky`
- Open the `GAMEDATA` folder

### Step 2: Create G-O-D-MOD Folder
- Right-click in the GAMEDATA folder
- Create a new folder
- Name it exactly: `G-O-D-MOD`

### Step 3: Add Mod Files
- Clone or download all files from the G-O-D-MOD GitHub repository
- Copy all mod files into the `GAMEDATA/G-O-D-MOD` folder

### Step 4: Verify Installation
Your folder structure should look like:
```
No Man's Sky/
├── GAMEDATA/
│   ├── G-O-D-MOD/
│   │   ├── MODINFO.XML
│   │   ├── METADATA.XML
│   │   └── [other mod files]
│   └── [other game data folders]
└── [other game files]
```

### Step 5: Launch the Game
- Start No Man's Sky
- The mod will automatically load when the game initializes
- You should immediately notice the effects

## Verification Checklist

- [ ] G-O-D-MOD folder is in GAMEDATA
- [ ] All mod files are present
- [ ] No other conflicting mods in GAMEDATA
- [ ] Game launches without errors
- [ ] You have invincibility (test by taking damage)
- [ ] Exosuit shows max tech modifications
- [ ] Multitool shows max tech modifications

## Troubleshooting

**Mod not loading?**
- Ensure folder is named exactly `G-O-D-MOD` (case-sensitive on some systems)
- Check that all required files are present
- Verify GAMEDATA folder path is correct

**Game crashes on startup?**
- Remove the mod and verify the game runs normally
- Check that XML files are properly formatted
- Reinstall mod files fresh from repository

**Features not working?**
- Restart the game completely
- Create a new save file to ensure mod is applied
- Check in-game settings for any mod-related options

## Uninstallation

To remove the mod:
1. Delete the `GAMEDATA/G-O-D-MOD` folder
2. Restart No Man's Sky
3. Game will run with original settings

---

**Need help?** Check the README.md or create an issue on the GitHub repository.
