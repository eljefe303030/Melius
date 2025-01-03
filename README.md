# **Melius**
![Melius wide](https://github.com/user-attachments/assets/826eab34-021d-4c22-8322-4e7ac6c02e96)

<p align="center">
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License</a>

<p align="center">
  <a href="https://www.nexusmods.com/starfield/mods/12658">Nexus Page</a> |
  <a href="https://discord.gg/ZyakMg7CGN">Discord</a> |
  <a href="https://loadorderlibrary.com/lists/melius-2">Full Modlist</a> |
  <a href="https://github.com/eljefe303030/Melius/blob/main/changelog.md">Changelog</a>
 </p>

## Please read ALL of this document before playing the list.

# Contents List

<details>

* [Preamble](#preamble)
* [Modlist](#modlist)
* [Requirements](#requirements)
* [Pre-installation Steps](#pre-installation-steps)
* [Pagefile and Crash Prevention](#pagefile-and-crash-prevention)
* [Using Wabbajack](#using-wabbajack)
* [Post-installation Steps](#post-installation-steps)
  * [Root Builder](#root-builder)
  * [Shattered Space DLC](#shattered-space-dlc)
* [Important mods you should know about](#important-mods-you-should-know-about)
* [Optional Mods](#optional-mods)
  * [Modifications to the modlist](#modifications-to-the-modlist)
* [Gameplay Guide](gameplay-guide)
* [Note for Content Creators](note-for-content-creators)
* [Known Issues](#known-issues)
* [Changelog](#changelog)
* [Updating the Modlist](#updating-the-modlist)
* [Support](#support) 
* [Credits and Thanks](#credits-and-thanks)

</details>
 
# Preamble
Melius is a Starfield Wabbajack modlist heavily based on [JaeDL's](https://next.nexusmods.com/profile/JaeDL?gameId=4187) excellent [Starborn Royalty](https://www.nexusmods.com/starfield/mods/6397) and includes graphic mods and settings by [Luxor](https://www.nexusmods.com/starfield/users/50525966). Main aim is to make the game as enjoyable as possible, whilst improving graphics, audio and adding quality of life mods.

Stability and a list that works irrespective of whether you the Shattered Space DLC, is another key aim of this list.

I created this list based on my personal preferences and I'm sharing this so others can have a modded version of Starfield, without having to spend the time I did trying out different mods and working out the load order etc. However, please be aware that this is my first Wabbajack list I have shared, I have tested this as much as possible but there is a risk this might not work for everyone. I will endeavour to provide support in fixing any teething issues but I am just one person who has a full time job and life outside of doing this.

## Modlist

The full list of mods can be found on [Load Order Library](https://loadorderlibrary.com/lists/melius-2)

## Requirements
* I have tested this on both a AMD 3600/AMD Radeon RX 580 and AMD 5700X3D/AMD 7800 XT and on both systems it works well without any noticeable drops in FPS. Planet textures can take a second to load, this may be mitigated with a faster SSD.
* Your computer will need to meet at least the [minimum requirements specified by Bethesda](https://help.bethesda.net/#en/answer/60442)
* Your graphics card should have at least:

  For full HD and 1440p = 8GB

  For UWQHD and 4k = 16GB
  
* Installation folder takes up approx 93GB and the download folder takes up another 88GB. A total of 181GB is needed, including temporary installation files, if both folders are on one drive.
* Language set to English.
* You need the latest Steam version (1.14.74.0) of the game.

## Pre-installation Steps
1. Install [Visual C++ x64 Redistributables](https://aka.ms/vs/17/release/vc_redist.x64.exe).
2. Install [Microsoft .NET 5.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime) and [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0/runtime) (both console apps and desktop apps x64).
3. Fully disable OneDrive and any other programs that affect user file areas.
4. Reinstall Starfield into a location that is not Program Files. Somewhere like C:\Games is a good location. You MUST have the latest version Steam of Starfield, version 1.14.74.0 and it MUST be a clean install.
5. Set Starfield to not automatically update.
6. Right click Starfield in Steam, click Properties, disable Enable the Steam overlay while in-game.
4. Language set to English. You can check translations of the modes on NexusMods but I cannot support you with that.
5. Start a new game. I will not provide support if you use this list on an existing save game, as there could be issues from other mods you used.

## Pagefile and Crash Prevention
To prevent crashes, you will need to set the pagefile to a minimum and maximum size of 40000
1. Press Win + R and enter sysdm.cpl
2. On the Advanced tab, select Settings under the Performance section
3. On the Advanced tab and press Change... under the Virtual Memory section
4. Disable Automatically manage paging file size for all drives
5. Select your disk drive, ideally your fastest SSD
6. Under the Custom Size: option, change Initial Size (MB) and Maximum Size (MB) to 40000
7. Click Set
8. Click OK, then Apply and OK
9. Restart your computer

## Using Wabbajack
1. Download the latest version of [Wabbajack](https://www.wabbajack.org/) and place it in a folder near or at the root of your drive, e.g. C:\Wabbajack
2. Create the installation folder e.g. C:\Melius
4. Create the mod download folder e.g. C:\Melius mod downloads. The download folder can be on a different drive. This can be deleted after the installation has completed but is not advised, as if you want to update or reinstall, you'll need to redownload all the mods again.
5. In the WABBAJACK folder, run Wabbajack.exe to install the Wabbajack program
6. After the install has completed, run Wabbajack.exe once more
7. Make sure you are logged into Nexus. Click on the gear icon in the top right hand corner and click login to Nexus Mods.
8. Browse the [Starfield modlists](https://www.wabbajack.org/gallery?selectedGame=Starfield) to choose Melius. You may need to filter by unofficial lists.
9. Choose the Mod Installation Location and Resource Download Location paths you set earlier for the installation and mod download folders.
10. If you have a premium Nexus membership, it will install automatically, if you don't, you will have to click slow download for each and every mod.
11. Once completed, it's installed.

If there are any issues with the installation, start Wabbajack again and it will continue from where it left off.

## Post-installation Steps
### Root Builder
The list also uses Kezyma's Root Builder to keep the game root folder clean. Any mod that needs to be installed in the game folder is instead added to MO2 with a special file structure, and is then added to the game folder whenever the game is running.

1. Launch ModOrganizer.exe in the Melius installation folder. If you get a popup asking about nxm links. Click Yes.

### Shattered Space DLC
* If you do not have the Shattered Space DLC, keep the 'Melius No DLC' profile selected and **do not** enable any of the following mods:
  
  ![Melius No DLC profile](https://github.com/user-attachments/assets/25cc32a3-1b07-4c3f-896f-8e9a435ba683)
  1. Aurie_StayPutShatteredSpace.esm
  2. RRLD - Rabbit's Real Lights Dazra.esm
  3. RoyalLeveledEnemiesSS.esm
  4. RoyalWeathersVaRuunkai2.esm
  5. SmarterSpacesuitAutohide_SFBGS001.esm
 
* If you do have the Shattered Space DLC, change to the 'Melius Shattered Space' profile.

  ![Melius Shattered Space profile](https://github.com/user-attachments/assets/a7c54e28-8684-4f87-8fcf-c3835d8134b8)

2. Only launch Melius through MO2 via the 'Starfield SFSE'. **Do not start through Steam or by selecting Starfield in MO2**, as this will result in mods not working.
![start SFSE](https://github.com/user-attachments/assets/101caa91-dba3-4620-95ba-1a60a22f48e9)
4. **Do not press the Unlock button** that MO2 displays after clicking run. The game may take a few minutes to start, this is normal.
5. Recommend to set brightness to 2.62 and contrast to 0.90 in the game menu.
6. Messages saying achievements will be disabled can be ignored. See [Baka Achievement Enabler (SFSE)](https://www.nexusmods.com/starfield/mods/658?tab=posts) description on why this is the case and how it works.
7. After starting the game for the first time, the sound will not work properly, save the game when you are able to, close the game down and reloading your save will correct this.
8. If using the Skip Intro mod, **do not** choose to skip to the lodge, as this will break your playthrough.

## Important mods you should know about

1. [PEAK AI](https://www.nexusmods.com/starfield/mods/7120) and [Bedlam](https://www.nexusmods.com/starfield/mods/10717) to make combat more fun and interesting
2. [Royal Galaxy](https://www.nexusmods.com/starfield/mods/8222) changes a large number of things, including bug fixes, QOL improvements, stronger Terrormorphs and Ashta, increased enemy spawns, and potent Starborn magic. Diversifies encounters, Points of Interest, Weathers, and Climates.
3. [Royal Skies Space Combat](https://www.nexusmods.com/starfield/mods/7890) Overhaul of spaceship combat. Enemies will occasionally fly into you, either because they cannot get out of the way or deliberately.
4. [Starfield HD Overhaul](https://www.nexusmods.com/starfield/mods/5124) updates a lot of the games textures without having a major impact on FPS.
5. [CINE FIDELITY LUTS](https://www.nexusmods.com/starfield/mods/3767) & [Neutral LUTs - No Color Filters](https://www.nexusmods.com/starfield/mods/323) changes the LUTs of the game to remove the colour filters and make the game look a lot better. Thanks to [Luxor for the guide](https://www.nexusmods.com/starfield/mods/11413) on how to use these to best effect.
6. [StarUI suite of mods](https://next.nexusmods.com/profile/m8r98a4f2/mods?gameId=4187) to change the UI to make it easier and nicer to use.
7. Various mods to change the transitions and animations to make them more immersive and less annoying
8. [Rabbit’s suite of mods](https://next.nexusmods.com/profile/RabbitDoesStuff?gameId=4187) to make area lighting more realistic and playable i.e. not having to walk around in the dark when there are lights around you!
9. [Simple Immersive Helmets](https://www.nexusmods.com/starfield/mods/4930) adds an overlay to the screen when wearing a helmet to provide reflections, as you could expect when having glass in front of you.

## Optional Mods

Within the left hand pane of MO2 there is a section for optional mods. Put a tick next to any of these that you want to enable:
1. [Skip Intro](https://www.nexusmods.com/starfield/mods/10494) skips past the mining intro to the character creation point. **Do not** skip to the lodge, it will break the game!
2. [Doubled Enemy Numbers](https://www.nexusmods.com/starfield/mods/6030) doubles the number of enemies. Royal Galaxy already increases enemies by 1.5 but use this if you want even more.
3. [Legendary Module Recycler](https://www.nexusmods.com/starfield/mods/6074) great mod that give you the ability to remove modules from legendary weapons and spacesuits etc. This can make you overpowered if not used responsibly.
4. [Royal Recycler Patch](https://www.nexusmods.com/starfield/mods/10581?tab=files) not essential but recommend if you use Legendary Module Recycler, as this keeps the text changes from Royal Galaxy.
5. [DualSense - PS5 Icons](https://www.nexusmods.com/starfield/mods/215) use this if you use a PS5 controller
6. [Vanilla Flashlight Improved (VFI)](https://www.nexusmods.com/starfield/mods/701) alternative and brighter flashlight. If you use this, make sure you disable the default flashlight 'Luxor's realistic Flashlight HD'.

### Modifications to the modlist
Any modifications you make to the modlist, other than the optional mods listed above, are unsupported. I would be interested to hear if you have any recommendations for mods, let me know in my Discord server.

## Gameplay Guide

* Auto saves are disabled by default but can be enabled in the settings menu of the game.
* [Baka Quick Full Saves](https://www.nexusmods.com/starfield/mods/1750) changes quick saves to full saves, which means you will have more saves and will need to periodically delete saves as and when needed.
* Multiple mods change UI elements to 60 fps.
* [Fast Travel To Unknown](https://www.nexusmods.com/starfield/mods/6663) means you can fast travel to unknown POIs when using the hand scanner.
* [Auto Unlock SFSE](https://www.nexusmods.com/starfield/mods/5571) Auto unlock doors, containers and terminals (including inaccessible) if you have the required perks.
* [Short Temple Puzzles](https://www.nexusmods.com/starfield/mods/1139) changes the number of puzzles to 3.
* [Build Outpost Items with Credits](https://www.nexusmods.com/starfield/mods/11890) Allows you to build all outpost/ship objects with credits instead of resources.
* [Sit To Add Ship to Fleet](https://www.nexusmods.com/starfield/mods/6493) Sit in pilot seat to add captured ship to your fleet. No need to make it your home ship.
* [Smarter Spacesuit Auto-Hide](https://www.nexusmods.com/starfield/mods/8423) Tweaks the conditions for when your spacesuit is automatically hidden, and better synchronizes your follower's suit behavior with your own. Make sure you have used the toggle in the spacesuit inventory to show/hide spacesuits in settlements for this work to your preference.
* [Leave No Witnesses](https://www.nexusmods.com/starfield/mods/12000) Reworks player bounties so that killing all witnesses to a crime you commit in space removes the bounties incurred while committing that crime.
* [Landing Bay Cargo Access](https://www.nexusmods.com/starfield/mods/11972) Adds an interactive cargo panel to each landing bay module, allowing you to access your ship's cargo hold remotely - at your ship, but outside your ship. If the cargo panel doesn't show up on your ship, you may have to refresh your ship's landing bay cell by modifying your ship in the ship builder.
* [Polyamory - Remove single romance limit](https://www.nexusmods.com/starfield/mods/10687) Removes the restriction on multiple companion romances.
* [Auto Transfer Mined and Harvested Resources to Your Ship - SFSE](https://www.nexusmods.com/starfield/mods/8606) SFSE plugin that automatically transfers mined mineral deposits and harvested resources to your Homeship instead of your inventory. Some quests that involve collecting resources will mean you then have to collect them from your ship instead of your inventory.
* [Human Damage (Just a Flesh Wound - Bullet in the Head)](https://www.nexusmods.com/starfield/mods/12603) Changes the damage multiple for the different areas of body parts of humans to make the game more fun and rewards better aiming.

## Note for Content Creators

Some of the added music in the list cannot be played on YouTube/Twitch or other platforms due to DMCA rules. To circumvent this, I recommend either disabling the mod PopcornTime or disabling in-game music bu lowering the volume to 0% in the audio settings.

## Known Issues

1. White Dwarf 2000 engine has different thrust values for left and right engines in the ship builder. This will be fixed in the next release. In the meantime you can install my [patch](https://www.nexusmods.com/starfield/mods/12836) and set it to load immediately after Royal Skies - Complete (aka Royal Skiles Space Combat) (right hand pane of MO2).
2. Planet textures can take a second to load, this may be mitigated with a faster SSD.
3. Controller Vibration for Maelstrom and Grendel guns is low to non-existent.
4. The larger your inventory contents, the more lag you will experience when coming in and out of menus. I do not know a fix for this except stashing excess inventory (including ammo) into a safe container.

## Changelog

1.2.0 Adds a number of mods that provide some visual improvements/changes, minor changes to UI and bug fixes. This is a save game safe update.

[Full Changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md)

## Updating the Modlist

Before updating the modlist, check the [changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md) and it is advisable to back up your saves first. It will state in the changelog if you need to start a new save after certain updates.

It is recommended that before updating to save the game whilst you are in space, standing in your spaceship, doing nothing.

Updating is the same process as installing the list. Make sure your paths are the same, and tick `Overwrite Installation`. 

If you have the Shattered Space DLC, remember to select the 'Melius Shattered Space' profile in MO2, as it will default to the 'Melius No DLC' profile.

If you get a message like the below, choose 'No'
![Missing content](https://github.com/user-attachments/assets/60522711-6dde-46b1-a8e6-c006d28eca17)

If the update has removed any mods, you'll get the following message, choose 'Yes'
![Content not present](https://github.com/user-attachments/assets/d66fafc1-2c54-4adf-9b72-a52b55667c1b)

Any mods you have added to the list will be deleted and other changes you have made will be overwritten. If you want to keep additional mods you have added, add `[NoDelete]` before the mod name in the left hand pane of MO2.
![NoDelete prefix](https://github.com/user-attachments/assets/e9d88441-20be-45a2-a4dc-ad59a7a9a385)

## Support
Use the [Discord server](https://discord.gg/ZyakMg7CGN)

## Credits and Thanks
* JaeDL for permission to use Starborn Royalty as a basis for this list.
* [Seb263](https://www.nexusmods.com/starfield/users/825950) for the [Responsive Grabbing](https://www.nexusmods.com/starfield/mods/289) ini setting.
* The mod authors for all their hard work, skill and imagination.
* The Wabbajack team for making a tool that makes this possible.
* Anyone who tries this list.
