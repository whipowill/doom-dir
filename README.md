# Doom

A directory of files for playing Doom.

This was one of the first games I played as a kid.  I was probably around 12 years old, and I used to play over modem w/ a friend from school.  I wanted to relive the memories.

This repository includes my files for playing the game, which includes all my favorite mods and map packs.

## Files

This is how you mentally organize all of the files:

- ``IWADs`` - the main game files from the official releases.
    - [Doom](https://doomwiki.org/wiki/Doom)
    - [Doom 2: Hell On Earth](https://doomwiki.org/wiki/Doom_II)
    - [Doom TNT: Plutonia](https://doomwiki.org/wiki/The_Plutonia_Experiment)
    - [Doom TNT: Evilution](https://doomwiki.org/wiki/TNT:_Evilution) :star: :heart:
- ``PWADs`` - community map packs that modify the official releases.
    - [Doom: The Way ID Did](https://doomwiki.org/wiki/Doom_the_Way_id_Did)
    - [Doom 2: The Way ID Did](https://doomwiki.org/wiki/Doom_2_the_Way_id_Did)
    - [Doom 2: UAC Ultra](https://doomwiki.org/wiki/UAC_Ultra) :star:
    - [Doom TNT: Revilution](https://doomwiki.org/wiki/TNT:_Revilution)
- ``Mods`` - change the gameplay of any official release or map pack.
    - [Brutal Doom v21.11.3](https://www.moddb.com/mods/brutal-doom) - adds new weapons, alternate firing modes, and massive amounts of gore to the game.
    - [ZMove v3.2.1](https://github.com/whipowill/doom-mod-zmove) - adds Quake style movement and physics (as well as other popular FPS games) to Doom.
    - [Motion Blur v1.041](https://forum.zdoom.org/viewtopic.php?f=103&t=62772&start=45) - adds slight motion blur to the game when turning quickly from side to side.
    - [War Trophies v1.10.2](https://forum.zdoom.org/viewtopic.php?t=67054) - adds ranks and achievement medals to the game based on weapons and kill counts (I don't use but kept in here).
    - [DAR's Covers](https://www.doomworld.com/forum/topic/89263-dars-doom-marathon-music-mod-updated-070322/) - adds amazing shredding guitar covers of all the original Doom tracks.

When you launch the game, you are layering these files on top of each other.  In total there are 8 games in my setup.

## Install

- Download [GZDoom](https://www.zdoom.org/downloads).
- Download this repo to a ``Doom`` directory.
- Find copies of the following ``WAD`` files:
    - ``DOOM.WAD``
    - ``DOOM2.WAD``
    - ``PLUTONIA.WAD``
    - ``TNT.WAD``
- Put these files in the ``IWAD`` folder.
- Download the music files (over Github size limit):
    - Download [file](https://www.doomworld.com/idgames/music/dars_dm) to ``Mods/DAR's Covers.wad``.
    - Download [file](https://www.mediafire.com/file/wxese22seoovb0d/DAR%2527s_TNT_Marathon.7z/file) to ``Mods/DAR's Covers TNT.wad``.
- Prepare your launch aliases.

I play on a Linux machine and use the following ``~/.bashrc`` aliases to launch the games from command line:

```
alias doom="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/DOOM.WAD -file Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers.wad"
alias doom2="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/DOOM2.WAD -file Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers.wad"
alias doom_pluto="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/PLUTONIA.WAD -file Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers\ TNT.wad"
alias doom_evil="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/TNT.WAD -file Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers\ TNT.wad"
alias doom_revil="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/TNT.WAD -file PWADs/Doom/TNT\ Revilution.wad Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers\ TNT.wad"
alias doom_twid="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/DOOM.WAD -file PWADs/Doom/DTWID.wad Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers.wad"
alias doom2_twid="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/DOOM2.WAD -file PWADs/Doom2/D2TWID.wad Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers.wad"
alias doom2_uac="cd ~/Games/Linux/Doom && __NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only gzdoom -iwad IWADs/DOOM2.WAD -file PWADs/Doom2/UAC\ Ultra\ v1.2.wad Mods/Brutal\ Doom\ v21.11.3.pk3 Mods/ZMovement\ v3.2.1.pk3 Mods/Motion\ Blur\ v1.041.pk3 Mods/Music/Dar\'s\ Covers.wad"
```

## Settings

If you find your ``gzdoom.ini`` file, you might want to paste in some settings from my file which I included in the ``backups`` folder:

- My video settings
- My game flags (respawn items)
- My Brutal Doom settings
- My ZMove settings
- My Motion Blur settings

Final tip, I find running on the Vulkan video renderer works better than OpenGL on Linux machines.

## Credits

- Brutal Doom - by Mark IV
- ZMovement - by Ivory
- Motion Blur - by PixelEater
- DAR's Covers - by DAR