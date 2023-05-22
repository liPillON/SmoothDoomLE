# SmoothDoomMonsters
I wanted a monsters-only version of Smooth Doom, so I went ahead and made it! 

Uploaded to GitHub for posterity's sake, originally posted here:
https://forum.zdoom.org/viewtopic.php?p=1226965#p1226965


## Disclaimer
This is a trimmed/refactored version of Smooth Doom by Gifty

The bulk of the work should be credited to him and the many contributors to his project

https://forum.zdoom.org/viewtopic.php?t=45550


## Background
After trying many monsters-only variants of Smooth Doom (and being dissatisfied
with most of them) I decided to look into creating one myself.

I've started with the latest official Gifty's build (dating back to april 2020).

My job has initially been to comment-out and chopping-off anything that I was able
to identify as non-monster-related.

As time passed, I also began standardizing how the mod contents where organized.


## Changes
- removed all toggable features (leaving only the extra death animations)
- removed the MENUDEF, CVARINFO, LOADACS lumps (they were used for managing the features' toggles)
- removed most DECORATE actor definitions, keeping only those for Monsters and Projectiles
- removed all unused GFX/SFX resources (effects, gore, weapons, items, powerups, decorations...)
- removed the ANIMDEFS, DECALDEF, KEYCONF, SBARINFO, SNDINFO, TERRAIN lumps (they had no use anymore)
- converted all remaining GFX resources to Truecolor PNGs
- introduced new naming convention for actors
- reorganized the pk3 contents (lump filtering, decorate/gldefs file naming)

