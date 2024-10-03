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
        - [Brutal DOOM v21](https://www.moddb.com/mods/brutal-doom/downloads) (weapons)
        - [DOOM The Way Id Did](https://www.doomworld.com/idgames/levels/doom/megawads/dtwid) (maps)
        - [No End In Sight (AE)](https://forum.zdoom.org/viewtopic.php?t=66837&sid=ca2ce47d125b5654a3346ba9ab9e29b0) (maps)
        - [DAR's DOOM Marathon.wad](https://mega.nz/file/hP0ihCxa#CdeWARW75SN7PVCtYzlhgq4d0aF__OiqmSSQVSan04k) (music)
    - DOOM2
        - [Brutal DOOM v21](https://www.moddb.com/mods/brutal-doom/downloads) (weapons)
        - [Brutal DOOM64 v2.666](https://www.moddb.com/news/brutal-doom-64-v2666-unofficial) (overhaul, use by itself)
        - [Brutal Wolfenstein v7](https://www.moddb.com/mods/brutal-wolfenstein-3d/downloads) (overhaul, use by itself)
        - [DOOM2 The Way Id Did](https://www.doomworld.com/idgames/levels/doom2/megawads/d2twid) (maps)
        - [DOOM64 for DOOM2 (AE)](https://forum.zdoom.org/viewtopic.php?t=66837&sid=ca2ce47d125b5654a3346ba9ab9e29b0) (maps)
        - [UAC Ultra v1.2](https://www.doomworld.com/idgames/levels/doom2/Ports/s-u/uacultra) (maps)
        - [DAR's DOOM2 Marathon.wad](https://mega.nz/file/wTliiDBR#Jj22XnTQatDODttRoFalQKOE-Y5y_ljg5AxXJMq0g6A) (music)
        - [DAR's D64D2 Marathon.wad](https://mega.nz/file/ZWc1EarB#c1ZqghDVe_ZgsfyLGLVhlXC0PZD2fuVonnrPqpoPtYM) (music, use w/ D64 for D2 mod)
    - TNT
        - [Brutal DOOM v21](https://www.moddb.com/mods/brutal-doom/downloads) (weapons)
        - [TNT Revilution (AE)](https://forum.zdoom.org/viewtopic.php?t=66837&sid=ca2ce47d125b5654a3346ba9ab9e29b0) (maps)
        - [DAR's TNT Marathon.wad](https://mega.nz/file/sLETlJhI#D8XBqy2UlPic37EGgvpAklGJX3QctmC5pcwCnMEC3aE) (music)

The trick here is knowing which mods you can stack w/ other mods.  Basically, if I didn't put a note, you can stack that mod with others. Map mods should not be stacked w/ other map mods.  Note that map mods are optional, w/out them the game will play the original maps.

Some of these map wads I have in here are so-called "Autoload Edition".  I'm not totally clear on what this means but I was having compatibility issues w/ Brutal DOOM on D64D2 maps and the AE version seemed to fix it.

## Launcher

Be sure to checkout my shell script [DOOM Launcher](https://github.com/whipowill/sh-doom-launcher) which uses this directory structure to manage your mods and launch your games.