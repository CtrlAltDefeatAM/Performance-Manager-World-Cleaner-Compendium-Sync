# Performance-Manager-World-Cleaner-Compendium-Sync
Foundry VTT performance toolkit with world cleanup, compendium sync, and automatic client-side optimization for FPS, audio, video tiles, chat, and socket load.
# Performance Manager World Cleaner Compendium Sync

Foundry VTT performance toolkit focused on client-side optimization, world cleanup, and compendium syncing. It combines a background performance manager with a GM cleanup and sync panel so you can reduce clutter, stabilize sessions, and keep world data aligned with unlocked compendiums. 

## What It Does

### Background Performance Manager
The background manager is built to reduce session strain while you play. It automatically handles FPS stabilization, audio loop cleanup, off-screen video tile control, chat DOM trimming, texture garbage collection, perception refresh management, ghost ruler cleanup, and latency-aware socket throttling. :contentReference[oaicite:1]{index=1}

### World Cleaner
The GM cleanup side gives you one place to purge common world clutter, including chat log cleanup, combat tracker cleanup, scene thumbnail regeneration, fog of war clearing, ghost folder cleanup, and ghost flag cleanup. These are destructive actions and should be used carefully. :contentReference[oaicite:2]{index=2}

### Compendium Sync
The sync tools push matching world entries into unlocked compendiums by name. The UI supports syncing Actor Players, Actor NPCs, Items, Scenes, Macros, Journals, and Roll Tables. Actor Players are filtered to `character`, and Actor NPCs are filtered to `npc`. 

## Main Features

- Automatic background turbo refresh
- FPS cap stabilization
- Audio stuck-loop cleanup
- Off-screen video tile pause and resume handling
- Chat trimming and optional automatic chat pruning
- Texture garbage collection support
- Latency monitoring with socket-saving behavior
- Ghost ruler cleanup for offline or high-latency users
- World cleanup tools for common clutter sources
- Matching-name compendium sync for multiple document types
- Built-in themed UI with scale controls, color presets, custom theme colors, and saved UI preferences per user 

## GM Tools Included

### Database Purge
The cleanup panel includes these purge options:

- Wipe Chat Log
- Clear Combat Tracker
- Regenerate Scene Thumbs
- Clear Fog of War
- Purge Ghost Folders
- Clear Macro Flags

These actions cannot be undone. :contentReference[oaicite:5]{index=5}

### Compendium Sync Targets
The sync panel supports:

- Actor Players
- Actor NPCs
- Items
- Scenes
- Macros
- Journals
- Roll Tables

Sync uses matching names and targets unlocked compendiums only. It does not create new entries automatically. 

## UI Features

The module includes a custom Performance Manager interface with:

- Theme presets
- Custom accent, panel, and glow colors
- UI scaling
- Hover tips
- Saved window size and position
- Built-in Discord and Patreon links 

## Usage Notes

- The cleanup and compendium sync interface is GM-facing.
- Compendium sync overwrites matching unlocked compendium entries.
- Database purge options are destructive.
- This module is intended to help stabilize active worlds, reduce clutter, and make long-running sessions easier to maintain. 

## Module Focus

This module is built for GMs who want:

- better session stability
- less world clutter
- cleaner compendium maintenance
- easier long-term world upkeep

## Support

## Main Links
- **Main Hub:** https://ctrlaltdefeatam.github.io/
- **Patreon:** https://www.patreon.com/Ctrl_Alt_Defeat
- **Discord:** https://discord.gg/fBf7xw2bmB
- **StartPlaying:** https://startplaying.games/gm/ctrl-alt-defeat
- **YouTube:** https://www.youtube.com/@Ctrl_Alt_Defeat-GM
- **Homebrewery:** https://homebrewery.naturalcrit.com/share/LtF88dEE8z1S
- **GitHub:** https://ctrlaltdefeat.carrd.co/
