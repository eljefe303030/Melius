# **Melius**
![Melius logo](https://github.com/eljefe303030/Melius/blob/main/Melius%20banner.webp)

<p align="center">
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License</a>

<p align="center">
  <a href="https://www.nexusmods.com/starfield/mods/12658">Nexus Page</a> |
  <a href="https://discord.gg/ZyakMg7CGN">Discord</a> |
  <a href="https://loadorderlibrary.com/lists/melius-3">Full Modlist</a> |
  <a href="https://github.com/eljefe303030/Melius/blob/main/changelog.md">Changelog</a>

<p align="center">
  <a href="https://ko-fi.com/eljefe303030">Ko-fi</a>
  
 </p>

## Please read ALL of this document before installing/playing the list.

# Contents List

<details>

* [Preamble](#preamble)
* [Modlist](#modlist)
* [Requirements](#requirements)
* [Pre-installation Steps](#pre-installation-steps)
* [Using Wabbajack](#using-wabbajack)
* [Post-installation Steps](#post-installation-steps)
  * [Root Builder](#root-builder)
  * [Stock Game](#stock-game)
  * [Starting Mod Organizer 2](#starting-mod-organizer-2)
* [Important mods you should know about](#important-mods-you-should-know-about)
* [Optional Mods](#optional-mods)
  * [Manuel Installations](#manuel-installations)
  * [Modifications to the modlist](#modifications-to-the-modlist)
* [Gameplay Guide](#gameplay-guide)
* [Recommended Settings](#recommended-settings)
* [Note for Content Creators](note-for-content-creators)
* [Known Issues](#known-issues)
* [Changelog](#changelog)
* [Updating the Modlist](#updating-the-modlist)
* [Support](#support) 
* [Credits and Thanks](#credits-and-thanks)

</details>

# Preamble
Melius is a Starfield Wabbajack mod list based on [melik173's](https://next.nexusmods.com/profile/melik173?gameId=4187) excellent [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465) and includes mods to make the game more immersive, combat more challenging and enjoyable, as well as adding in a number of quality of life mods and mods to improve the aesthetics. 

Stability and balanced gameplay that is challenging but rewarding are key aims of this list. 

## Modlist

The full list of mods can be found on [Load Order Library](https://loadorderlibrary.com/lists/melius-3)

## Requirements
* I have tested this on an AMD 5700X3D/AMD 7800 XT and it works well without any noticeable drops in FPS.
* Your computer will need to meet at least the [minimum requirements specified by Bethesda](https://help.bethesda.net/#en/answer/60442)
* Language set to English.
* You need the latest Steam version (1.15.216) of the game and the Shattered Space DLC.

## Pre-installation Steps
1. Install [Microsoft .NET v8.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer) and [Microsoft Visual C++ 2019 Runtime](https://aka.ms/vs/16/release/vc_redist.x64.exe).
2. Fully disable OneDrive and any other programs that affect user file areas.
3. Reinstall Starfield into a location that is not Program Files. Somewhere like C:\Games is a good location [(detailed instructions on how to do this)](https://help.steampowered.com/en/faqs/view/4BD4-4528-6B2E-8327#:~:text=The%20default%20installation%20location%20is,Program%20Files%20(x86)%5CSteam). You MUST have the latest Steam version of Starfield, version 1.15.216 and it MUST be a clean install.
4. Set Starfield to not automatically update.
    - Right click Starfield in Steam, click Properties, disable *'Enable the Steam overlay while in-game'*.
6. Language set to English. You can check translations of the mods on NexusMods but I cannot support you with that.
7. Start Starfield via Steam once, get to the main menu and exit the game. After this step, you will be starting the game through Steam anymore.

## Using Wabbajack
1. Download the latest version of [Wabbajack](https://www.wabbajack.org/) and place it in a folder near or at the root of your drive, e.g. C:\Wabbajack
2. Create the installation folder e.g. C:\Melius
4. Create the mod download folder e.g. C:\Melius Mod Downloads. The download folder can be on a different drive. This can be deleted after the installation has completed but is not advised, as if you want to update or reinstall, you'll need to redownload all the mods again.
5. In the WABBAJACK folder, run Wabbajack.exe to install the Wabbajack program
6. After the install has completed, run Wabbajack.exe once more
7. Make sure you are logged into Nexus. Click on the gear icon in the bottom left hand corner and click login to Nexus Mods.
8. Browse the Starfield modlists to choose Melius.
9. Choose the Mod Installation Location and Downloads Location paths you set earlier for the installation and mod download folders.
10. Click the **Install** button to start the installation.
11. If you have a premium Nexus membership, it will install automatically, if you don't, you will have to click slow download for each and every mod.
12. Once completed, it's installed.

If there are any issues with the installation, start Wabbajack again and it will continue from where it left off.

## Post-installation Steps
### Root Builder
*For your information only, this step is done automatically* 

The list uses Kezyma's Root Builder to keep the game root folder clean. Any mod that needs to be installed in the game folder is instead added to MO2 with a special file structure, and is then added to the game folder whenever the game is running.

### Stock Game 
*For your information only, this step is done automatically* 

Melius uses the Stock Game method. This is essentially a copy of Starfield included with the installation folder. This means that everything is completely separate from your Steam installation of Starfield (which is still required as the game files are not redistributed). The folder in question is called Stock Game, located at Melius\Stock Game.

### Starting Mod Organizer 2
1. Launch ModOrganizer.exe in the Melius installation folder. If you get a popup asking about nxm links. Click Yes.

2. Only launch Melius through MO2 via the 'Starfield SFSE'. **Do not start through Steam or by selecting Starfield in MO2**, as this will result in mods not working.
![start SFSE](https://github.com/user-attachments/assets/101caa91-dba3-4620-95ba-1a60a22f48e9)
> [!IMPORTANT]
> 3. **Do not press the Unlock button** that MO2 displays after clicking run. The game may take a few minutes to start, this is normal.
4. Start a new game. I will not provide support if you use this list on an existing save game, as there could be issues from other mods you used.

> [!IMPORTANT]
> 4. After starting the game for the first time, the sound, elements of the user interface and other things will not work properly, save the game when you are able to, close the game down and reloading your save will correct this.

## Important mods you should know about

1. [El Jefe Combat AI](https://www.nexusmods.com/starfield/mods/13194) and [Bedlam](https://www.nexusmods.com/starfield/mods/10717) to make combat more fun and interesting
2. [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465) overhauls the gameplay in many ways.
3. [StarUI suite of mods](https://next.nexusmods.com/profile/m8r98a4f2/mods?gameId=4187) to change the UI to make it easier and nicer to use.
5. Various mods to change the transitions and animations to make them more immersive and less annoying
6. [Rabbit’s suite of mods](https://next.nexusmods.com/profile/RabbitDoesStuff?gameId=4187) to make area lighting more realistic and playable i.e. not having to walk around in the dark when there are lights around you!
7. [Revelation - Main Quest Overhaul](https://www.nexusmods.com/starfield/mods/10418) This mod overhauls Starfield's main quest, including removing most Temples.
8. [Simple Immersive Helmets](https://www.nexusmods.com/starfield/mods/4930) adds an overlay to the screen when wearing a helmet to provide reflections, as you could expect when having glass in front of you.
9. [Gorefield - A Starfield Gore Framework](https://www.nexusmods.com/starfield/mods/12833) Introduces special death effects such as bodies exploding, disintegrating and burning.
10. Multiple mods that remove the chance of coming across the same POIs all the time.
11. [Deadly Hazards](https://www.nexusmods.com/starfield/mods/5800) Overhauls and fixes Starfield's environmental gameplay systems.
12. [Vitality - Sustenance Overhaul](https://www.nexusmods.com/starfield/mods/10536) This mod replaces the Sustenance system with a more gradual one, that includes sleep mechanics.
13. [Real Fuel - Immersive Exploration](https://www.nexusmods.com/starfield/mods/13306) Introduces Fuel usage mechanics to travel in Starfield in a lightweight and immersive manner.
14. [Real O2]([https://www.nexusmods.com/starfield/mods/9827](https://www.nexusmods.com/starfield/mods/12303)) A lightweight, highly compatible revamp of the O2 system in Starfield. Oxygen is now a limited resource in zero-atmosphere environments, and must be managed carefully.
15. [Better Boarding Encounters (BBE)](https://www.nexusmods.com/starfield/mods/13964) and [Enemies Boarding My Ship](https://www.nexusmods.com/starfield/mods/13999) Spices up docking encounters with surprise boarding, occasional hazards, and cut pirate dialogue! Enemies actively try to dock onto your ship during combat in order to board it. In space combat, there is now a constant risk of being boarded yourself. The risk increases with the interests of the factions and the condition of your ship.
16. [New Atlantis Awaits](https://www.nexusmods.com/starfield/mods/13614) Explore a revitalized version of New Atlantis with New Atlantis Awaits. This mod brings a complete overhaul to the city, enhancing its layout, architecture, and overall atmosphere.
    
## Optional Mods

Within the left hand pane of MO2 there are several separator sections marked as 'OPTIONAL', you can also use the filter box to search for optional mods. Click on the empty tickbox to the left of the mod you want to enable and a tick will appear, this mod is now enabled: 

**01.1a CORE MODS - SFSE PLUGINS**
1. [Auto Unlock - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/5571) Auto unlock doors, containers and terminals (including inaccessible) if you have the required perks.
2. [Auto Transfer Mineral Deposits and Resources - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/8606) SFSE plugin that automatically transfers mined mineral deposits and harvested resources to your Homeship instead of your inventory. **note, some missions require you to gather resources on your person. For these, you will have to go back to your ship to collect the resources.**
3. [Gravity Affects Weight - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/3048) SFSE plugin that makes gravity affect inventory/carry weight.
4. [Smart Aiming - Third to First Person - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/11706) Automatically switch to first person when aiming your weapon, and back to third person upon release.

**05.1 CORE MODS - QUEST ALTERATIONS**
1. [Commitment](https://www.nexusmods.com/starfield/mods/13436) Choose only Vanguard, Ranger or Ryujin Operative. Force disguise when undercover for SysDef. Locks you out of other factions based on your decisions. Enable all 3 commitment mods. **needs to be enabled before starting your game or before NG+**
   
**06.1 USER INTERFACE**
1. [Better Button Prompts - PS4 - PS5 - Switch](https://www.nexusmods.com/starfield/mods/478) Enable button prompts for PlayStation DualShock/DualSense Controllers or Nintendo Switch-based controllers with any language.
2. [No Legendary Pickup Notification](https://www.nexusmods.com/starfield/mods/5687) Removes the additional rare/epic/legendary item card notification, which pops up when you pick up an rare/epic/legendary item.
3. [Replace Circle Cursor](https://www.nexusmods.com/starfield/mods/1297) This mod will remove the circle cursor from the game and replace it with the regular pointer cursor. **enabled by default, recommended to disable if playing with controller**
4. [Suppress Message.Show - Disable Tutorials](https://www.nexusmods.com/starfield/mods/11588) This mod patches native game functions so you can disable messages you don't like. **read the mod page description on how to configure**

**06.1a USER INTERFACE - ULTRA WIDESCREEN**

Selection of Ultra Widescreen mods

**7.1 MENU & LOADING SCREENS**

1. [Melius - Main Menu Background - MELIUS ORIGINAL](https://www.nexusmods.com/starfield/mods/12860) Original Melius main menu background of an animated starfield. **you'll need to disable the mod 'Melius Main Menu Replacer [0Bek version]**
2. [Melius - Pause Menu Background - MELIUS ORIGINAL](https://www.nexusmods.com/starfield/mods/13232) Original Melius pause menu background. **you'll need to disable the mod 'Melius Pause Menu Background Replacer [0Bek version]**

**08.1 AUDIO & MUSIC**
1. [Faded Memories - Ambient Music Overhaul](https://www.nexusmods.com/starfield/mods/6778) Replaces the combat, exploration, dungeon, and (most of) the city music with music by Nyghttones for a darker atmosphere.
2. [No Headshot and Crit Sounds](https://www.nexusmods.com/starfield/mods/4414) This mod removes Headshot and Crit sounds. No more immersion breaking UI sound effects. All crits and headshot sounds replaced with silence. *recommended to use in conjunction with the mod below - Satisfying Headshots - Sound Overhaul*
3. [Satisfying Headshots - Sound Overhaul](https://www.nexusmods.com/starfield/mods/3823) You now hear the clanging of the bullet hitting the helmets of your foes. *recommended to use in conjunction with the mod above - No Headshot and Crit Sounds*
4. [No Hit Confirmation Sound](https://www.nexusmods.com/starfield/mods/3938) no projectile hit confirmation sfx (thud).
5. [No XP Soundeffect](https://www.nexusmods.com/starfield/mods/4271) This mod disables the sound effect played when gaining XP in game.
6. [Silent Sounds - Immersive Gameplay - Selective](https://www.nexusmods.com/starfield/mods/664) Removes Level Up, Location Discover, Mission related, Skill Magazine read and similar sounds. Intended for a more immersive gameplay.
7. [Starfield Epic Theme Menu Replacer by CJMusic](https://www.nexusmods.com/starfield/mods/2810) Replaces The Main Menu Theme with the "Starfield Epic Theme" composed by CJMusic. **you'll also need to disable the mod 'Melius - Main Menu Music [MELIUS DEFAULT]' in '08 AUDIO & MUSIC'**
8. [Vanilla Plus Main Theme - Into the Starfield](https://www.nexusmods.com/starfield/mods/14312?tab=files) An epic version of the Starfield main theme, "Into the Starfield". Perfect for that vanilla+ modded playthrough! **you'll also need to disable the mod 'Melius - Main Menu Music [MELIUS DEFAULT]' in '08 AUDIO & MUSIC'**

**09.1 LUT RESOURCES**
1. [Gravity LUT - No Color Filters](https://www.nexusmods.com/starfield/mods/1871) Alternative LUT, "hand crafted to deliver true to life colors and luminance." **only enable one LUT mod at a time**
2. [Stellar LUT - High Contrast Color Filters](https://www.nexusmods.com/starfield/mods/1072) Custom LUT created using ARRI Log 3 conversion and includes AgX color management for crisp, accurate color and gamut. Hand crafted, per-location LUTs for the perfect balance. **only enable one LUT mod at a time**

**19.1 MESHES & TEXTURES - ARMOR & WEAPONS**
1. [Varuun Spacesuit Remade - Replacer - Dark Visor](https://www.nexusmods.com/starfield/mods/7254) Changes the Va'ruun Spacesuit to have a dark visor. **use this mod OR the mod below, not both**
2. [Varuun Spacesuit Remade - Replacer - Red Visor](https://www.nexusmods.com/starfield/mods/7254) Changes the Va'ruun Spacesuit to have a red visor. **use this mod OR the mod below, not both**

**22.1 MESHES & TEXTURES - FX**
1. [Vanilla Flashlight Improved - Bright](https://www.nexusmods.com/starfield/mods/701) It's the vanilla flashlight, but better! Enjoy a larger, brighter beam without the ugly banding artifacts. **enabling this mod will replace the default flashlight mod [Luxor's Realistic Flashlight - HD](https://www.nexusmods.com/starfield/mods/11036)**

**34.1 IMMERSION**
1. [Simple Immersive Helmets - 2K](https://www.nexusmods.com/starfield/mods/4930) adds an overlay to the screen when wearing a helmet to provide reflections, as you could expect when having glass in front of you. **Can cause a performance hit of around 5 FPS, disable this if you need those extra 5 FPS. The related patches will do nothing once you start the game after disabling this mod and can be safely left enabled**
2. [Simple Immersive Helmets - Shattered Space Patch](https://www.nexusmods.com/starfield/mods/13353) does the same as above but for the DLC.

**35.1 WEATHER**
1. [Royal Weathers - Fantasy Add-On](https://www.nexusmods.com/starfield/mods/7946) some beautiful, potentially not lore-friendly weather on moons and locations without atmosphere.

**49.1 GENERAL COMBAT**
1. [Doubled Enemy Numbers - No Robots](https://www.nexusmods.com/starfield/mods/6030) enemy numbers in most abandoned, deserted, forgotten places are doubled.
2. [Human Damage multiplier options](https://www.nexusmods.com/starfield/mods/12603) choose one of the lower multipler here if you want headshots to you and enemies to do less damage.
3. [Remove Auto Aim](https://www.nexusmods.com/starfield/mods/14096) Removes the auto aim from the game. When shooting, if you see the red crosshair appearing to correct your aim, that is the auto aim kicking in, this mod simply disables that. Want to get the satisfaction of knowing direct hits are down to your skill and accuracy, then this mod is for you. **enabled by default**

**64 LO SENSITIVE - ALTERNATIVE START**
1. [SKK - Fast Start New Game](https://www.nexusmods.com/starfield/mods/5971) Fast Start New Game bypasses the Argos-Atlantis tutorials starting new and NG+ games from Lodge, Cydonia, Akila, Neon, Den or random location with full character configuration and some loadout choices. **When fisrt starting a game, don't do anything whilst mods are initialising (notifications appearing in the top right of the screen). If you use this mod, read the mod page for [Immersive Landing Ramps](https://www.nexusmods.com/starfield/mods/8093) as the items you need for this mod will need to be acquired within the game for the mod to be useable. Go to you inventory, it will say it is not available, exit out of that screen, a message will say the mod setup has completed and you can then continue as normal. When you start a new game with this mod, the ship control menu will pop up, tab to close this and continue.**
  
### Manuel Installations
1. Since version 1.3.0 of this modlist, a lot of HD texture mods have been removed to help reduce the mod list download size and make the list more performance friendly. If you would like to have the best possible graphics, I highly recommend you use the [Starfield HD Overhaul mod](https://www.nexusmods.com/starfield/mods/5124). This is save safe to add or remove during a playthrough.

### Modifications to the modlist
Any modifications you make to the modlist, other than the optional mods listed above, are unsupported. I would be interested to hear if you have any recommendations for mods, let me know in my Discord server.

Do not update any mods within this mod list. Reason being is that mods have been patched, both by including a patch file and binary patching. Consequences of updating mods can include mods no longer functioning as intended, to the whole mod list not working.

## Gameplay Guide

* Auto saves are disabled by default but can be enabled in the settings menu of the game.
* [Baka Quick Full Saves](https://www.nexusmods.com/starfield/mods/1750) changes quick saves to full saves, which means you will have more saves and will need to periodically delete saves as and when needed.
* [Short Temple Puzzles](https://www.nexusmods.com/starfield/mods/1139) changes the number of puzzles to 3.
* [Build Outpost Items with Credits](https://www.nexusmods.com/starfield/mods/11890) Allows you to build all outpost/ship objects with credits instead of resources.
* [Sit To Add Ship to Fleet](https://www.nexusmods.com/starfield/mods/6493) Sit in pilot seat to add captured ship to your fleet. No need to make it your home ship.
* [Leave No Witnesses](https://www.nexusmods.com/starfield/mods/12000) Reworks player bounties so that killing all witnesses to a crime you commit in space removes the bounties incurred while committing that crime.
* [Landing Bay Cargo Access](https://www.nexusmods.com/starfield/mods/11972) Adds an interactive cargo panel to each landing bay module, allowing you to access your ship's cargo hold remotely - at your ship, but outside your ship. If the cargo panel doesn't show up on your ship, you may have to refresh your ship's landing bay cell by modifying your ship in the ship builder.
* [Polyamory - Remove single romance limit](https://www.nexusmods.com/starfield/mods/10687) Removes the restriction on multiple companion romances.
* [Human Damage (Just a Flesh Wound - Bullet in the Head)](https://www.nexusmods.com/starfield/mods/12603) Changes the damage multiple for the different areas of body parts of humans to make the game more fun and rewards better aiming. Headshot multiplier is set to x10 which means headshots are deadly for you and most enemies, some bosses might take 2 or 3 headshots to kill them. If you want to change this, right click the mod and choose reinstall, which give you a choice of headshot multiplier (x2 is vanilla). Make sure to place it in the correct position in the right hand pane, immediately below the El Jefe Combat AI mod.
* [StarUI HUD](https://www.nexusmods.com/starfield/mods/3444) has been configured to not show enemy health bars or stealth meters for immersion, see the mod page for how to configure this to your tastes. Crosshairs have also been disabled, these can be displayed by changing the game 'interface' setting.
* [Starware Search Engine - SFSE](https://www.nexusmods.com/starfield/mods/13643) Implements a search engine to the Galaxy StarMap Menu, allowing you to find any location and planet within seconds. Press 'q' in the starmap to use.
* [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465) overhauls the gameplay in many ways. Additional control keys - Sensor Array mod for helmets adds Night Vision. Default key to activate is "N". There is a new menu to swap attachments (ammo, muzzle, scope and firing mode) without the need of a workbench. Default key to bring up the menu is "B"

# Recommended Settings
**Gameplay Options**
* Damage options - if you are finding it difficult, reduce the damage for a while until you gain better equipment/gain perks
* Other settings:
![Settings1](https://github.com/user-attachments/assets/bd38f3fe-1b1c-4c7f-ae60-6f9c07a638c4)
![Settings2](https://github.com/user-attachments/assets/07c3ffe3-977b-41a6-9774-86007df8a528)
![Settings3](https://github.com/user-attachments/assets/4d3293de-f005-438f-9601-a012573e8d06)

**Display**
* Brightness set to 2.62 and contrast to 0.90
* Lower Crowd Density if you need more FPS in busy areas like New Atlantis
* Motion Blur - off
* VSync - off
* Sharpening 25% (if using frame generation, such as FSR or DLSS)
* Disable frame generation if you get crashes. Otherwise use the correct one for your hardware if needed.
* Film Grain Intensity set to zero

## Note for Content Creators

Some of the added music in the list cannot be played on YouTube/Twitch or other platforms due to DMCA rules. To circumvent this, I recommend either disabling the mod PopcornTime or disabling in-game music by lowering the volume to 0% in the audio settings.

## Known Issues

1. The mod Weapon Sound Fixes has the side effect of controller vibration for Maelstrom, Grendel and some other weapons being low to non-existent.
4. Not all the additional clothing combinations are compatible with each other and can cause visual glitches/clipping in both the preview and in game views. Choose a different combination of outfits if this occurs.
5. Using SKK Fast Start, when you start a new game, you don't have access to the landing ramp remote and the ship control menus opens, just tab out of the menu to continue **read the mod page for [Immersive Landing Ramps](https://www.nexusmods.com/starfield/mods/8093) as the item you need for this mod will need to be acquired within the game for the mod to be useable**
6. Crosshairs for some weapons are unavailable and will need a patch to bring them back.

## Changelog

Version 3.0

**This version will need a new game.**

Complete rewrite of the mod list. This is a major update and will require a new game, it will not be save safe. This will no longer have two profiles and instead one profile based on the [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465) mod. I have had to make the decision to make having Shattered Space as a requirement, as too many mods need this. On the plus side, it will make installation of the modlist easier (no more having to manually copy across files). Starvival will no longer be used and instead replaced with several other mods that cover some of the systems.

[Full Changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md)

## Updating the Modlist

Before updating the modlist, check the [changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md) and it is advisable to back up your saves first. It will state in the changelog if you need to start a new game after certain updates.

**Updating to version 3.x. It is required to install into a new folder, as there are significant changes.**

It is recommended that before updating to save the game whilst you are in space, doing nothing, sat in the cockpit, doing zero speed.

Any mods you have added to the list will be deleted and other changes you have made will be overwritten. If you want to keep additional mods you have added, add `[NoDelete]` before the mod name in the left hand pane of MO2.
![NoDelete prefix](https://github.com/user-attachments/assets/e9d88441-20be-45a2-a4dc-ad59a7a9a385)

Updating is the same process as installing the list. Make sure your paths are the same. 

If you get a message like the below, choose 'No'
![Missing content](https://github.com/user-attachments/assets/60522711-6dde-46b1-a8e6-c006d28eca17)

If the update has removed any mods, you'll get the following message, choose 'Yes'
![Content not present](https://github.com/user-attachments/assets/d66fafc1-2c54-4adf-9b72-a52b55667c1b)

## Support
Use the [Discord server](https://discord.gg/ZyakMg7CGN)

## Credits and Thanks
* [Seb263](https://www.nexusmods.com/starfield/users/825950) for the [Responsive Grabbing](https://www.nexusmods.com/starfield/mods/289) ini setting.
* The mod authors for all their hard work, skill and imagination.
* The Wabbajack team for making a tool that makes this possible.
* ElminsterAU for xEdit.
* [Bhaeron](https://next.nexusmods.com/profile/Bhaeron?gameId=4187) for a massive amount of contribution, too much to list here.
* Padi for being the Discord guru and making the Melius server what it is. DrukenReaps for moderating the server and keeping everyone in line, including myself.
* Pyke Lermon, EccentricMeat, Sithishade, [0Bek](https://next.nexusmods.com/profile/0Bek), DrukenReaps, Chris and anyone else on the Melius Discord server for mod suggestions and contributions.
* [AvatarV](https://www.youtube.com/@AvatarV/videos) for allowing us to use his amazing in game photos.
* Anyone who tries this list.

**Supporters**

Thank you so much for supporting me.
* 8Bit
* Jordan


