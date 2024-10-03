# DOOM

A directory of files for playing Doom.

This was one of the first games I played as a kid.  I was probably around 12 years old, and I used to play over modem w/ a friend from school.  I wanted to relive the memories.

On my computer this repo is full of WAD files, but they are so large I can't upload them to Github.

So, I will give you the links instead.  These are the mods I consider "the best".

## Files

The file structure here is to put the original game WAD files in the ``IWAD/`` folder, and to put all the mods and custom campaigns in the ``PWAD/`` folder, with nested subfolders for the IWAD they are built for.

- IWAD
    - ``DOOM.WAD``
    - ``DOOM2.WAD``
    - ``TNT.WAD``
- PWAD
    - DOOM
        - [Brutal DOOM v22](https://www.moddb.com/mods/brutal-doom/downloads) (weapons)
        - [DOOM The Way Id Did](https://www.doomworld.com/idgames/levels/doom/megawads/dtwid) (maps)
        - [No End In Sight](https://www.doomworld.com/idgames/levels/doom/Ports/megawads/neis) (maps)
        - [DAR's DOOM Marathon](https://mega.nz/file/hP0ihCxa#CdeWARW75SN7PVCtYzlhgq4d0aF__OiqmSSQVSan04k) (music)
    - DOOM2
        - [Brutal DOOM v22](https://www.moddb.com/mods/brutal-doom/downloads) (weapons)
        - [DOOM2 The Way Id Did](https://www.doomworld.com/idgames/levels/doom2/megawads/d2twid) (maps)
        - [DOOM64 for DOOM2](https://www.doomworld.com/idgames/levels/doom2/megawads/d64d2) (maps)
        - [UAC Ultra v1.2](https://www.doomworld.com/idgames/levels/doom2/Ports/s-u/uacultra) (maps)
        - [DAR's DOOM2 Marathon](https://mega.nz/file/wTliiDBR#Jj22XnTQatDODttRoFalQKOE-Y5y_ljg5AxXJMq0g6A) (music)
        - [DAR's D64D2 Marathon](https://mega.nz/file/ZWc1EarB#c1ZqghDVe_ZgsfyLGLVhlXC0PZD2fuVonnrPqpoPtYM) (music, use w/ D64 for D2 mod)
        - [Brutal DOOM64 v2.666](https://www.moddb.com/news/brutal-doom-64-v2666-unofficial) (overhaul, use by itself)
        - [Brutal Wolfenstein v7](https://www.moddb.com/mods/brutal-wolfenstein-3d/downloads) (overhaul, use by itself)
    - TNT
        - [Brutal DOOM v22](https://www.moddb.com/mods/brutal-doom/downloads) (weapons)
        - [TNT Revilution](https://www.doomworld.com/idgames/levels/doom2/megawads/tntr) (maps)
        - [DAR's TNT Marathon](https://mega.nz/file/sLETlJhI#D8XBqy2UlPic37EGgvpAklGJX3QctmC5pcwCnMEC3aE) (music)

The trick here is knowing which mods you can stack w/ other mods.  Basically, if I didn't put a note, you can stack that mod with others. Map mods should not be stacked w/ other map mods.  Note that map mods are optional, w/out them the game will play the original maps.

## Launcher

Be sure to checkout my shell script [DOOM Launcher](https://github.com/whipowill/sh-doom-launcher) which uses this directory structure to manage your mods and launch your games.

## Notes

- D64D2 was buggy w/ Brutal DOOM v21, but v22 seems to have no problem.  I was getting some weird CPU leak on the second map that would bring the game to a crawl.