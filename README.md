# SmoothDoomLE
A no-frills variant of SmoothDoom.
Created starting from the original mod by Gifty, limiting it to Monsters.
Updated with weapons animations by ScubaSteve.
Compatible with ZDOOM (tested in 2.81), Zandronum (tested in 3.1) and GZDOOM (tested in 4.7.x)

## Disclaimer
Credit to Gifty for everything concerning Monsters:
https://forum.zdoom.org/viewtopic.php?t=45550

Credit to ScubaSteve for fine-tuning the Weapons:
https://www.doomworld.com/forum/post/2517286


## Background
After trying many monsters-only variants of Smooth Doom (and being dissatisfied with most of them) I decided to look into creating one myself.

I've started with the latest official Gifty's build (dating back to april 2020). My job has initially been to comment-out and chopping-off anything that I was able to identify as non-monster-related.

As time passed, I also began standardizing how the mod contents where organized.


## Changes
- removed all toggable features (leaving only the extra death animations)
- removed the MENUDEF, CVARINFO, LOADACS lumps (they were used for managing the features' toggles)
- removed most DECORATE actor definitions, keeping only those for Monsters and Projectiles
- removed all unused GFX/SFX resources (effects, gore, weapons, items, powerups, decorations...)
- removed the ANIMDEFS, DECALDEF, GLDEFS, SBARINFO, SNDINFO, TERRAIN lumps (they had no use anymore)
- converted all remaining GFX resources to optimized PNGs
- introduced new naming convention for actors
- reorganized the pk3 folders structure
- merged the Smooth Weapons mod by ScubaSteve

## Downloads:
- [this](https://github.com/liPillON/SmoothDoomLE/releases/latest) is the latest release.
- [this](https://github.com/liPillON/SmoothDoomLE/archive/refs/heads/main.zip) is the current repository snapshot.

