# SmoothDoomMonsters

I wanted a monsters-only version of Smooth Doom, so I went ahead and make it! 

Uploaded to GitHub for posterity's sake, originally posted here:
https://forum.zdoom.org/viewtopic.php?p=1226965#p1226965


## Changes
- removed all toggable features (leaving only the extra death animations)
- removed the MENUDEF, CVARINFO, LOADACS lumps (they were used for managing the features' toggles)
- removed most DECORATE actor definitions, keeping only those for Monsters and Projectiles
- removed all unused GFX/SFX resources (effects, gore, weapons, items, powerups, decorations...)
- removed the ANIMDEFS, DECALDEF, KEYCONF, SBARINFO, SNDINFO, TERRAIN lumps (they had no use anymore)
- converted all remaining GFX resources to Truecolor PNGs
- introduced new naming convention for actors
- reorganized the pk3 contents (lump filtering, decorate/gldefs file naming)


## Credits
Thank you Gifty for doing all of the dirty work:
https://www.doomworld.com/profile/14161-gifty/
https://forum.zdoom.org/memberlist.php?mode=viewprofile&u=8604


