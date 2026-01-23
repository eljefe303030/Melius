# **Melius**
![Melius logo](https://github.com/eljefe303030/Melius/blob/80ef279772736b740a9aca09a0ea66ef2bc23e0b/assets/images/Melius%20banner.webp)

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
  * [Manual Installations](#manual-installations)
  * [Modifications to the modlist](#modifications-to-the-modlist)
* [Gameplay Guide](#gameplay-guide)
* [Recommended Settings](#recommended-settings)
* [Note for Content Creators](note-for-content-creators)
* [Known Issues](#known-issues)
* [Troubleshooting](#troubleshooting)
* [Changelog](#changelog)
* [Updating the Modlist](#updating-the-modlist)
* [FAQ (Frequently Asked Questions)](#faq-frequently-asked-questions)
* [Support](#support) 
* [Credits and Thanks](#credits-and-thanks)

</details>

# Preamble
Melius is a Starfield Wabbajack mod list based on [melik173's](https://next.nexusmods.com/profile/melik173?gameId=4187) excellent [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465), which imitates Requiem and Requiem - 3BFTweaks for Skyrim and applies this to Starfield. Melius includes mods to make the game more immersive, combat more challenging and enjoyable, as well as adding in a number of quality of life mods and mods to improve the aesthetics. 

Stability and balanced gameplay that is challenging but rewarding are key aims of this list. 

Combat is much more challenging than vanilla Starfield. Headshots are more deadly for the player and enemies. When first starting the game you may wish to choose to concentrate on non-combat missions to build experience, acquire better equipment and perks before taking on groups of better trained factions. For example, fighting Va’ruun will be more challenging than Spacers, use of cover and the need to retreat will be more important than before. The Gameplay Guide section of this ReadMe details how you can change the difficulty significantly by adjusting the Human Damage mod's multiplier and/or you may wish to change the main difficulty settings to your preferred level of challenge. 

## Modlist

The full list of mods can be found on [Load Order Library](https://loadorderlibrary.com/lists/melius-3)

## Requirements
* I have tested this on an AMD 5700X3D/AMD 7800 XT and it works well. Personally I find playing without frame generation provides the best experience for me.
* Your computer will need to meet at least the [minimum requirements specified by Bethesda](https://help.bethesda.net/#en/answer/60442)
* Language set to English.
* You need the latest Steam version (1.15.222) of the game and the Shattered Space DLC.

## Pre-installation Steps
1. Install [Microsoft .NET v8.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer) and [Microsoft Visual C++ 2019 Runtime](https://aka.ms/vs/16/release/vc_redist.x64.exe).
2. Fully disable OneDrive and any other programs that affect user file areas.
3. Reinstall Starfield into a location that is not Program Files. Somewhere like C:\Games is a good location [(detailed instructions on how to do this)](https://help.steampowered.com/en/faqs/view/4BD4-4528-6B2E-8327#:~:text=The%20default%20installation%20location%20is,Program%20Files%20(x86)%5CSteam). You **MUST** have the latest Steam version of Starfield, version 1.15.222 and it **MUST** be a clean install.
4. Set Starfield to not automatically update.
    - Right click Starfield in Steam, click Properties, disable *'Enable the Steam overlay while in-game'*.
6. Language set to English. You can check translations of the mods on NexusMods but I cannot support you with that.
7. Start Starfield via Steam once, get to the main menu and exit the game. After this step, you will not be starting the game through Steam anymore.
8. *Optional but recommended*: adjust your pagefile to at least 20GB but recommended to 40GB, up to 80GB if you have the space to be sure. Some people have reported this can prevent crashes to desktop (CTDs), if you are getting them, set your pagefile. To do this:

      a) Right click the Start Button

      b) Click System

      c) Click Advanced Systems Settings

      d) On the Advanced tab, click Settings in the Performance section

      e) On the Advanced tab, click the Change button

      f) Set the Initial Size and Maximum Size to 40000 or if you are struggling for drive space, to at least 20000.

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

If there are any issues with the installation, start Wabbajack again and it will continue from where it left off. **Do not press the retry button, as it can delete the whole installation. Instead, close and restart Wabbajack if there are any installation issues.**

## Post-installation Steps
### Root Builder
*For your information only, this step is done automatically* 

The list uses Kezyma's Root Builder to keep the game root folder clean. Any mod that needs to be installed in the game folder is instead added to MO2 with a special file structure, and is then added to the game folder whenever the game is running.

### Stock Game 
*For your information only, this step is done automatically* 

Melius uses the Stock Game method. This is essentially a copy of Starfield included with the installation folder. This means that everything is completely separate from your Steam installation of Starfield (which is still required as the game files are not redistributed). The folder in question is called Stock Game, located at Melius\Stock Game.

### Starting Mod Organizer 2
1. Launch ModOrganizer.exe in the Melius installation folder. If you get a popup asking about nxm links. Click Yes.
2. You can safely ignore any missing masters error messages. Any mods than depend on the Constellation or Old Mars skins that you get with the Premium Edition of Starfield will be automatically disabled the first time you run the list. If you have the Constellation and Old Mars skins, copy the files over to the Stock Game/Data folder before starting the list for the first time.

   ![Premium Edition files1](https://github.com/user-attachments/assets/8f32cb9c-7b39-4df2-9f65-0f3a92d333a0)
   ![Premium Edition files2](https://github.com/user-attachments/assets/d0829801-533a-4e1e-8111-26b78fa91300)

3. There are two profiles to choose from, the standard 'Melius' and the 'Performance Friendly' profiles. Both profiles share the same game saves, which are located in `\Users\hallm\Documents\My Games\Starfield\Saves` which enables you to swicth between profiles to find the best for your hardware.

4. Only launch Melius through MO2 via the 'Starfield SFSE'. **Do not start through Steam or by selecting Starfield in MO2**, as this will result in mods not working.
![start SFSE](https://github.com/user-attachments/assets/101caa91-dba3-4620-95ba-1a60a22f48e9)
> [!IMPORTANT]
> 3. **Do not press the Unlock button** that MO2 displays after clicking run. The game may take a couple of minutes to start, this is normal.
5. Start a new game. I will not provide support if you use this list on an existing save game, as there could be issues from other mods you used.

> [!IMPORTANT]
> 6. When you first start a game the following message will be displayed saying achievements have been disabled, this is not true and achievements will still work, press the 'YES' button to continue:
> <img width="999" height="285" alt="image" src="https://github.com/user-attachments/assets/3deae6bd-2806-4313-864c-46a1d7a1fa63" />

> 7. After starting the game for the first time, the sound, elements of the user interface and other things will not work properly, save the game when you are able to, close the game down and reloading your save will correct this.

## Important mods you should know about

1. [El Jefe Combat AI](https://www.nexusmods.com/starfield/mods/13194) and [Bedlam](https://www.nexusmods.com/starfield/mods/10717) to make combat more fun and interesting
2. [El Jefe Space Combat AI](https://www.nexusmods.com/starfield/mods/15386) Changes how enemies act, space combat will be more varied and more difficult. All enemies now have increased detection range. You will need to power down ship systems before grav jumping if you don't want to be detected on arrival. Missile seeking strength has been decreased slightly to enable to you to take evasive maneuvers to avoid being hit.
> [!IMPORTANT]
> if you are playing the game for the first time, before you travel to Venus in the Old Neighbourhood quest, you will need to reduce all ship power systems to zero, except 1 bar in engines. Otherwise you will be attacked on sight, as the enemy will detect you on arrival.
3. [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465) Overhauls the gameplay in many ways. Read the mod page to understand what is changed and new controls.
4. [StarUI suite of mods](https://next.nexusmods.com/profile/m8r98a4f2/mods?gameId=4187) to change the UI to make it easier and nicer to use.
5. [Revelation - Main Quest Overhaul](https://www.nexusmods.com/starfield/mods/10418) This mod overhauls Starfield's main quest, including removing most Temples.
6. Multiple mods that remove the chance of coming across the same POIs all the time.
7. [Deadly Hazards](https://www.nexusmods.com/starfield/mods/5800) Overhauls and fixes Starfield's environmental gameplay systems. If you have a yellow part of your health bar, it's environmental damage and needs to be healed by doctors or a Nanobots Injector. **You will start with a random but small amount of environmental damage**
8. [Vitality - Sustenance Overhaul](https://www.nexusmods.com/starfield/mods/10536) This mod replaces the Sustenance system with a more gradual one, that includes sleep mechanics.
9. [Real Fuel - Immersive Exploration](https://www.nexusmods.com/starfield/mods/13306) Introduces Fuel usage mechanics to travel in Starfield in a lightweight and immersive manner.
10. [Real O2](https://www.nexusmods.com/starfield/mods/12303) A lightweight, highly compatible revamp of the O2 system in Starfield. Oxygen is now a limited resource in zero-atmosphere environments, and must be managed carefully.
11. [Better Boarding Encounters (BBE)](https://www.nexusmods.com/starfield/mods/13964) and [Enemies Boarding My Ship](https://www.nexusmods.com/starfield/mods/13999) Spices up docking encounters with surprise boarding, occasional hazards, and cut pirate dialogue! Enemies actively try to dock onto your ship during combat in order to board it. In space combat, there is now a constant risk of being boarded yourself. The risk increases with the interests of the factions and the condition of your ship.
12. Selection of economy mods to add balance to the game and make money more valuable; [Cost Of Living - Simple Taxes](https://www.nexusmods.com/starfield/mods/12136), [Cost Of Spacing](https://www.nexusmods.com/starfield/mods/11726), [Spacefaring Economy](https://www.nexusmods.com/starfield/mods/12022) and [Variable Contraband Prices - Redux](https://www.nexusmods.com/starfield/mods/12205).
13. Selection of mods that improves the shipbuilding aspect of the game and add new parts and habs. You can now make and use Class M ships.
14. [TN's Space Mining and Salvage](https://www.nexusmods.com/starfield/mods/6331) Mining out in space is more challenging and more rewarding now. The asteroids will take special mining lasers you unlock with the geology perk, which deals good damage to asteroids, but not to anything else. They can also be used for salvaging. Many junk items can be taken to the Industrial Workbench and Salvaged into usable items. They will show up on the recipe list when they are in your inventory (Not your ship's).
15. [Starfield Engine Fixes - SFSE](https://www.nexusmods.com/starfield/mods/10457) Fixes bugs and adds new features to the game engine. The following settings have been changed from the default, most are self explanatory, see mod page for more detailed descriptions:

<details>
  
bEngineLoadOptimizer=1
bEngineLoadOptimizerActorBackgroundProcessPatchesCompatibilityMode=1

bGameplayOptionDisableXPModifiersBonus=1
bGameplayOptionDisableXPModifiersPenalty=1

bCanUseAnyFurnitureInZeroG=1
bDataMenuShowGameDateAndPlanetTimescale=1

bShowPlanetTemperatureInGalaxyStarMapMenu=1

bUseAnyWeaponInHandscanner=1

bPapyrusArrayNoLimit=1

bLoadingScreenOptions=1

bPhotoModeActorsAllowNonCompanions=1

bDisableWeaponSheatheInDialogues=1

bEyeContactNPCHelloDisallowWhileSprinting=1
bEyeContactNPCHelloDisallowWhileRunning=1

bFixNPCMakeupMod=1

bBA2Counter=1
bBA2CountLog=0 (change to 1 if need to see the log)

bDynamicFlightCameraDistance=1
iDynamicFlightCameraDistanceMinLength=20
iDynamicFlightCameraDistanceMinWidth=20
fDynamicFlightCameraDistanceExtraOffsetPerMeterLength=1.25

bDisableForcedHomeshipChangeOnPurchase=1

bActorCollisionMovementSync=1
bNoPlayerHeadCameraDirection=1

</details>

16. [Ultra Minus - Tuned Ultra Quality INI](https://www.nexusmods.com/starfield/mods/15126) This list uses a the majority of the ini settings from this mod to increase the quality of visuals as much as possible.
    
## Optional Mods

Within the left hand pane of MO2 there are several separator sections marked as 'OPTIONAL', you can also use the filter box to search for optional mods. Click on the empty tickbox to the left of the mod you want to enable and a tick will appear, this mod is now enabled: 

<details>

**01.1a CORE MODS - SFSE PLUGINS**
1. [Auto Spacesuit Hider - Custom Conditionalizer - Vanilla Bug Fixes - SFSE](https://www.nexusmods.com/starfield/mods/7432) Lets you determine under what conditions your Spacesuit is hidden. Also aims to fix some of the relevant vanilla bugs. **enabling this mod will pretty much make 'Fast Spacesuit Deployment Kit' mod redundant, as it takes away the manual control of when your spacesuit is displayed.**
2. [Auto Transfer Mineral Deposits and Resources - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/8606) SFSE plugin that automatically transfers mined mineral deposits and harvested resources to your Homeship instead of your inventory. **note, some missions require you to gather resources on your person. For these, you will have to go back to your ship to collect the resources.**
3. [Auto Unlock - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/5571) Auto unlock doors, containers and terminals (including inaccessible) if you have the required perks.
4. [Gravity Affects Weight - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/3048) SFSE plugin that makes gravity affect inventory/carry weight.
5. [Smart Aiming - Third to First Person - SFSE - Plugin](https://www.nexusmods.com/starfield/mods/11706) Automatically switch to first person when aiming your weapon, and back to third person upon release. Ini provided to change settings, see mod page for more details.

**05.1 CORE MODS - QUEST ALTERATIONS**
1. [Commitment](https://www.nexusmods.com/starfield/mods/13436) Choose only Vanguard, Ranger or Ryujin Operative. Force disguise when undercover for SysDef. Locks you out of other factions based on your decisions. Enable all 3 commitment mods. **needs to be enabled before starting your game or before NG+**
   
**06.1 USER INTERFACE**
1. [Better Button Prompts - PS4 - PS5 - Switch](https://www.nexusmods.com/starfield/mods/478) Enable button prompts for PlayStation DualShock/DualSense Controllers or Nintendo Switch-based controllers with any language.
2. [Bigger Systems - Expanded Star Maps](https://www.nexusmods.com/starfield/mods/14256) This mod expands the scale of planetary systems on the starmap, creating the illusion of much larger and more realistic distances between celestial bodies. **enabled by default**
3. [Replace Circle Cursor](https://www.nexusmods.com/starfield/mods/1297) This mod will remove the circle cursor from the game and replace it with the regular pointer cursor. **enabled by default, recommended to disable if playing with controller**
4. [Starfield String Sharpener - A Font Overhaul](https://www.nexusmods.com/starfield/mods/622) Replace the rounded default fonts with sharper, more intelligent, and readable fonts. **enabling this mod will disable the ALIEN Inspired fonts mod**
5. [Suppress Message.Show - Disable Tutorials](https://www.nexusmods.com/starfield/mods/11588) This mod patches native game functions so you can disable messages you don't like. **read the mod page description on how to configure**

**06.1a USER INTERFACE - ULTRA WIDESCREEN**

Selection of Ultra Widescreen mods

**7.1 MENU & LOADING SCREENS**

1. [Melius - Main Menu Background - MELIUS ORIGINAL](https://www.nexusmods.com/starfield/mods/12860) Original Melius main menu background of an animated starfield.
2. [Melius - Pause Menu Background - MELIUS ORIGINAL](https://www.nexusmods.com/starfield/mods/13232) Original Melius pause menu background.

**07.1a MENU & LOADING SCREENS - ULTRA WIDESCREEN**

Selection of Ultra Widescreen mods for menu and loading screens 

**08.1 AUDIO & MUSIC**
1. [No Headshot and Crit Sounds](https://www.nexusmods.com/starfield/mods/4414) This mod removes Headshot and Crit sounds. No more immersion breaking UI sound effects. All crits and headshot sounds replaced with silence. *recommended to use in conjunction with the mod below - Satisfying Headshots - Sound Overhaul*
2. [Satisfying Headshots - Sound Overhaul](https://www.nexusmods.com/starfield/mods/3823) You now hear the clanging of the bullet hitting the helmets of your foes. *recommended to use in conjunction with the mod above - No Headshot and Crit Sounds*
3. [No Hit Confirmation Sound](https://www.nexusmods.com/starfield/mods/3938) no projectile hit confirmation sfx (thud).
4. [No XP Soundeffect](https://www.nexusmods.com/starfield/mods/4271) This mod disables the sound effect played when gaining XP in game.
5. [Silent Sounds - Immersive Gameplay - Selective](https://www.nexusmods.com/starfield/mods/664) Removes Level Up, Location Discover, Mission related, Skill Magazine read and similar sounds. Intended for a more immersive gameplay.

**19.1 MESHES & TEXTURES - ARMOR & WEAPONS**
1. [Varuun Spacesuit Remade - Replacer - Dark Visor](https://www.nexusmods.com/starfield/mods/7254) Changes the Va'ruun Spacesuit to have a dark visor. **use this mod OR the mod below, not both**
2. [Varuun Spacesuit Remade - Replacer - Red Visor](https://www.nexusmods.com/starfield/mods/7254) Changes the Va'ruun Spacesuit to have a red visor. **use this mod OR the mod above, not both**

**22.1 MESHES & TEXTURES - FX**
1. [Vanilla Flashlight Improved (VFI)](https://www.nexusmods.com/starfield/mods/701) Alternative flashlight that has a larger, brighter beam. 
2. [3rd Person Flashlight Fix](https://www.nexusmods.com/starfield/mods/15740) Fixes the flashlight in 3rd person, so it doesn't point at the floor when aiming down sights (ADS) **enabled by default, disable if you only play in 1st person view.**

**34.1 IMMERSION**
1. [Simple Immersive Helmets - 2K](https://www.nexusmods.com/starfield/mods/4930) adds an overlay to the screen when wearing a helmet to provide reflections, as you could expect when having glass in front of you. **Enabled by default. Can cause a performance hit of around 5 FPS, disable this if you need those extra 5 FPS. The related patches will do nothing once you start the game after disabling this mod and can be safely left enabled**
2. [Simple Immersive Helmets - Shattered Space Patch](https://www.nexusmods.com/starfield/mods/13353) does the same as above but for the DLC.

**40.1 FIXED AREA EDITS - CITIES & TOWNS & SETTLEMENTS**
1. a selection of mods that add a significant amount of visual improvements to New Atlantis, includes New Atlantis Awaits, Positivity New Atlantis and related patches. *some users have reported drops in frame rates and infinite loading screens in New Atlantis when using these mods, I myself haven't and highly recommend these mods*

**43.1 OUTPOST BUILDING**
1. [Aurie's Build with Credits - BWC](https://www.nexusmods.com/starfield/mods/11890) Allows you to build most outpost/ship objects with credits instead of resources.

**44.1 SPACECRAFT & VEHICLES - OVERHAULS & MECHANICS**
1. [Astrogate](https://www.nexusmods.com/starfield/mods/9363) Immersive way to fly ships between systems and planets. Choice of FTL and Autopilot. Enable the two related files for best experience. *Read the descriptions of the settings in the main game menu, as some settings have the potential to prevent some quests from starting.* Recommended that you disable the following mods if using this; More Immersive Landings And Takeoffs & More Visualized Docking - Vanilla Enhanced & Default Speed
2. a selection of mods that remove the limits for engine power, shield and weapons. Using these mods makes building more unique and bigger spaceships easier but could be considered cheating and can result in overpowered spaceships.
3. [Seizure Of Ships - Take Over Restricted Ships](https://www.nexusmods.com/starfield/mods/5212) This mod removes the restriction on ships' pilot seats, so that you are no longer blocked from commandeering certain ships. **Warning, taking over some restricted ships can break quests or the game as a whole.** 

**49.1 GENERAL COMBAT**
1. [Doubled Enemy Numbers - No Robots](https://www.nexusmods.com/starfield/mods/6030) enemy numbers in most abandoned, deserted, forgotten places are doubled.
3. [Gorefield - A Starfield Gore Framework](https://www.nexusmods.com/starfield/mods/12833) Gorefield gives you a set of gameplay options that allow you to turn on special gory death effects for NPCs.
4. [Human Damage multiplier options](https://www.nexusmods.com/starfield/mods/12603) choose a higher/lower multipler here if you want headshots to you and enemies to do more/less damage.
5. [Remove Auto Aim](https://www.nexusmods.com/starfield/mods/14096) Removes the auto aim from the game. When shooting, if you see the red crosshair appearing to correct your aim, that is the auto aim kicking in, this mod simply disables that. Want to get the satisfaction of knowing direct hits are down to your skill and accuracy, then this mod is for you. **enabled by default**

**58.1 BEAUTY & APPEARANCE**
1. [NPC Height Variation Toolkit](https://www.nexusmods.com/starfield/mods/7466) A mod that realistically resizes all human NPCs in the game. NPCs are no longer all the same height. Included patch that fix an issue if playing with a female character, in third person and when aiming down sights, as well as [No Rescale on Interact](https://www.nexusmods.com/starfield/mods/7945) that disables automatic rescaling of characters on interaction with furniture and terminals so they don't visibly shrink/grow when sitting, standing, operating computers/workstations, etc. **characters can clip furniture when using this mod e.g. when sitting or leaning at desks.**

**64 LO SENSITIVE - ALTERNATIVE START**
> [!IMPORTANT]
> Select only one alternative start mod.
>1. [Roleplayers' Alternate Start](https://www.nexusmods.com/starfield/mods/15094) An alternate start mod designed for roleplayers, fully dynamic, with main quest replacement and dialog edits. **Be careful with options you choose e.g. if you choose a Class C spaceship, you won't be able to fly it at the beginning, as you won't have the required licence or perk.**
>2. [SKK - Fast Start New Game](https://www.nexusmods.com/starfield/mods/5971) Fast Start New Game bypasses the Argos-Atlantis tutorials starting new and NG+ games from Lodge, Cydonia, Akila, Neon, Den or random location with full character configuration and some loadout choices. **When first starting a game, don't do anything whilst mods are initialising (notifications appearing in the top right of the screen). If you use this mod, read the mod page for [Immersive Landing Ramps](https://www.nexusmods.com/starfield/mods/8093) as the items you need for this mod will need to be acquired within the game for the mod to be useable. Go to you inventory, it will say it is not available, exit out of that screen, a message will say the mod setup has completed and you can then continue as normal. When you start a new game with this mod, if the ship control menu will pops up, tab to close this and continue.**

**66.1 ANIMATION - GENERAL**
1. [Manual Weapon Stance](https://www.nexusmods.com/starfield/mods/13627) Adds a customizable hotkey to raise or lower your weapon at will. No more automatic lowering—you’re in full control. Works in both first and third person. Lightweight, immersive, and highly compatible.
[Instructions for Xbox Controller layout](https://github.com/eljefe303030/Melius/blob/main/assets/docs/MWS%20Xbox%20Controller%20layout%20instructions.md) *Some users have reported lags related to using this mod, I have not but your experience may vary*

</details>
  
### Manual Installations
1. Since version 1.3.0 of this modlist, a lot of HD texture mods have been removed to help reduce the mod list download size and make the list more performance friendly. If you would like to have the best possible graphics, I highly recommend you use the [Starfield HD Overhaul mod](https://www.nexusmods.com/starfield/mods/5124). This is save safe to add or remove during a playthrough. Place the plugin for this mod at the top of the load order in the right hand window.

### Modifications to the modlist
Any modifications you make to the modlist, other than the optional mods listed above, are unsupported. I would be interested to hear if you have any recommendations for mods, let me know in my Discord server.

Do not update any mods within this mod list. Reason being is that mods have been patched, both by including a patch file and binary patching. Consequences of updating mods can include mods no longer functioning as intended, to the whole mod list not working.

## Gameplay Guide

* Auto saves are disabled by default but can be enabled in the settings menu of the game.
* [Baka Quick Full Saves](https://www.nexusmods.com/starfield/mods/1750) changes quick saves to full saves, which means you will have more saves and will need to periodically delete saves as and when needed.
* [Auto Hide HUD and Widgets - SFSE](https://www.nexusmods.com/starfield/mods/8946) The Hud and Widgets are automatically hidden when not needed. See the mod's page for details on how you can change the behaviour of this mod.
* [Short Temple Puzzles](https://www.nexusmods.com/starfield/mods/1139) changes the number of puzzles to 3.
* [Immersive Driving - SFSE](https://www.nexusmods.com/starfield/mods/11253) Collection of a few immersive land vehicle features; Visible Body, Smart Aim, Panorama View, Rear View, Exit Anywhere, Companion Chatter. Key bindings are: Rear View 'Q', Companion Chatter 'V'.
* [Sit To Add Ship to Fleet](https://www.nexusmods.com/starfield/mods/6493) Sit in pilot seat to add captured ship to your fleet. No need to make it your home ship.
* [Leave No Witnesses](https://www.nexusmods.com/starfield/mods/12000) Reworks player bounties so that killing all witnesses to a crime you commit in space removes the bounties incurred while committing that crime.
* [Landing Bay Cargo Access](https://www.nexusmods.com/starfield/mods/11972) Adds an interactive cargo panel to each landing bay module, allowing you to access your ship's cargo hold remotely - at your ship, but outside your ship. If the cargo panel doesn't show up on your ship, you may have to refresh your ship's landing bay cell by modifying your ship in the ship builder.
* [Polyamory - Remove single romance limit](https://www.nexusmods.com/starfield/mods/10687) Removes the restriction on multiple companion romances.
* [Human Damage (Just a Flesh Wound - Bullet in the Head)](https://www.nexusmods.com/starfield/mods/12603) Changes the damage multiple for the different areas of body parts of humans to make the game more fun and rewards better aiming. Headshot multiplier is set to x10 which means headshots are deadly for you and most enemies, some bosses might take 2 or 3 headshots to kill them. If you want to change this, choose a different multiplier from the 49.1 GENERAL COMBAT - OPTIONAL section.
* [StarUI HUD](https://www.nexusmods.com/starfield/mods/3444) has been configured to not show stealth meters for immersion, see the mod page for how to configure this to your tastes. Crosshairs have also been disabled, these can be displayed by changing the game 'interface' setting.
* [Starware Search Engine - SFSE](https://www.nexusmods.com/starfield/mods/13643) Implements a search engine to the Galaxy StarMap Menu, allowing you to find any location and planet within seconds. Press 'q' in the starmap to use.
* [Serenity of Stars - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/13465) overhauls the gameplay in many ways. Additional control keys - Sensor Array mod for helmets adds Night Vision. The default key to activate is "N". There is a new menu to swap attachments (ammo, muzzle, scope and firing mode) without the need of a workbench. The default key to bring up the menu is "B". This mod does not show enemy health bars unless you are in the handscanner mode.
* [Fast Spacesuit Deployment Kit](https://www.nexusmods.com/starfield/mods/8229) This mod gives you a toolkit that can be called from the Favorite menu, and automatically equip/unequip your current spacesuit. Whether to wear a spacesuit and helmet, now is your call. To use, go straight to Laredo Firearms located at the Akila City, on the front counter, you can see the Fast Spacesuit Deployment Kit. Pick it up (the vendor also sells it), in your inventory, go to the Aid category, and add it to one of your Favorite slots. Whenever you press that hotkey, it will equip/unequip your current spacesuit. If you are wearing a spacesuit, it will remember them when unequipping, so the next time you use the item, it will equip back exactly the last spacesuits you had in your inventory. Nothing will happen if you are not wearing spacesuits or you take the spacesuit out of your inventory after the last unequipping.
* [Change Your Outfit](https://www.nexusmods.com/starfield/mods/14484) This mod transforms mannequins into fully interactive outfit stations. Instead of just displaying what you’ve stored, you can swap outfits with mannequins on the fly—perfect for players who roleplay different moods, story arcs, or faction allegiances and want to change their look instantly, immersively.
* [Leave No Witnesses](https://www.nexusmods.com/starfield/mods/12000) This mod removes the 30-second time limit and tracks all crimes you commit against ships, so that it is now possible to commit piracy or outright murder against ships in space and suffer no bounty - as long as you leave no witnesses.
* Both the Shattered Space and Trackers Alliance quests have been delayed to start at more appropriate times. Settings for these are in the main game options.
* [More NPCs Have Routines and Stores Have Schedules](https://www.nexusmods.com/starfield/mods/12140) Adds daily routines to 75 named NPCs, and 12 unnamed NPCs across major cities and settlements, who didn't already have schedules in vanilla. Many stores now have business hours, and employ robots to work the night shift.
* [The Gang's All Here - Multiple Companions and Crew](https://www.nexusmods.com/starfield/mods/7469) Allows you to have multiple companions and crew follow you and a control terminal to rule them all.
* [Ship Power Control Tweaks](https://www.nexusmods.com/starfield/mods/4820) Swap between multiple preconfigured power presets, or customize your own. Set a default power preset for your ship. Quickly select your ship's power systems. You will need to either enable the Stealth preset (`]}` key) before grav jumping or as soon as you arrive to avoid detection by enemies. Keys '1 to 6' select the different ship systems, `9` selects a combat preset, `0` balanced preset, `[{` escape preset, see the mod page for full details and how you can customise the presets and keys.
* [New Workbenches Essential Framework NWEF](https://www.nexusmods.com/starfield/mods/8024) Seperate workbenches called Fabrication (for ammo), Textiles (for outfits/clothes) and Armorer (for armour). Reduces lag and clutter in the Industrial Workbench.
* [Not Yet Shattered Space](https://www.nexusmods.com/starfield/mods/14112) Delays Shattered space starting until a configurable point in the main quest.
* [Working Water Coolers](https://www.nexusmods.com/starfield/mods/13503) Replaces nearly all water coolers and sinks in the world with working versions.

# Recommended Settings
**Gameplay Options**
* Damage options - if you are finding it difficult, reduce the damage for a while until you gain better equipment/gain perks
* Other settings:
![Settings4](https://github.com/user-attachments/assets/379013e3-e7b1-45b3-9b97-7378f2545912)
![Settings5](https://github.com/user-attachments/assets/1b4d85e2-b241-4c83-b638-4e2665179168)
![Settings6](https://github.com/user-attachments/assets/7769bf04-a223-4e15-ac08-f0b7f8e4103c)

* Other recommended settings but be aware these will make the game much more challenging and rewarding:
![Settings1](https://github.com/user-attachments/assets/c91a2c9f-99a5-46ee-aba2-bdf30dfa07dc)
![Settings2](https://github.com/user-attachments/assets/998889e4-5cb0-4e72-a47e-9007c9c662e0)
![Settings3](https://github.com/user-attachments/assets/a2539e0d-ff88-41c5-944b-ed4bcd6f5b34)

**Display**
* Contrast set to 90 then adjust brightness to whatever value you prefer, I have mine set to 2.62.
* Lower Crowd Density if you need more FPS in busy areas like New Atlantis
* Motion Blur - off
* VSync - off
* Sharpening 0%
* Disable frame generation if you get crashes. Otherwise use the correct one for your hardware if needed. Do not use sharpening in both gpu driver and ReShade. 
* Film Grain Intensity set to zero

**Enabling Enemy Healthbars**

[This guide by AldmerExile takes you step by step through the process](https://github.com/eljefe303030/Melius/blob/2ea64e7bb2c0a5a58bcf5ef94bcf7e18112571d3/assets/docs/Enabling%20Enemy%20Healthbars%20(Melius)v2.pdf).

## Note for Content Creators

Some of the added music in the list cannot be played on YouTube/Twitch or other platforms due to DMCA rules. To circumvent this, I recommend either disabling the mod PopcornTime or disabling in-game music by lowering the volume to 0% in the audio settings.

## Known Issues

1. Not all the additional clothing combinations are compatible with each other and can cause visual glitches/clipping in both the preview and in game views. Choose a different combination of outfits if this occurs.
2. Using SKK Fast Start, when you start a new game, you don't have access to the landing ramp remote and the ship control menus opens, just tab out of the menu to continue **read the mod page for [Immersive Landing Ramps](https://www.nexusmods.com/starfield/mods/8093) as the item you need for this mod will need to be acquired within the game for the mod to be useable**
3. The quest "legacy's end" if you chose the UC side and at the stage to destroy the crimson defenders, if during the dialogue it appears one of the ships runs into the key and explodes and prevents you from progressing, disable the mod 'Deadly Ramming and Debris Fields - Medium' and load and earlier save.
4. Starting the game without fast start will produce this error message, this can safely be ignored: ![Enemies Boarding My Ship error message](https://github.com/user-attachments/assets/7d1030ee-4158-4588-ae96-632d5441d75c)
5. The UI cannot display a 7th digit for cost, with the updated economy, some ships now cost more than 999,999 credits and therefore the last digit is not displayed. If you cannot buy a ship but seem to have enough credits, this will be why.
6. The list alters the weight and other attributes of ships parts. When you try to alter any vanilla ships in ship builder, it might say the ship is too heavy and you need to reduce mass or increase grav jump thrust. You can continue to use the ship but if you want to make alterations, you will need to address the mass/thrust issue.
7. If you select to sleep/wait for 1 hour, it will only actually sleep/wait for a few minutes. Choose to sleep/wait for a longer period. Values of 2 or more hours will work as intended. The only way to resolve this is to revert back to the incredibly slow vanilla sleep/wait speeds, which I don't want to do!

## Troubleshooting

### Strange Visual Effects
1. If you have strange visual effects, such as lights flickering when moving around or artifacting, reset your shader cache:

<details>
   
**AMD**
* Open AMD Software: Right-click on your desktop and select "AMD Software: Adrenalin Edition" or open it from the Start menu. 
* Navigate to Graphics Settings: Click the Gaming tab at the top, then select the Graphics subtab. 
* Find the Reset Option: Scroll all the way to the bottom of the graphics settings page. 
* Perform the Reset: Locate the Reset Shader Cache option and click the Perform Reset button next to it. 
* Confirm: Click OK when prompted to confirm the action.

**Nvidia**
Disable the cache: 
* Open the NVIDIA Control Panel, go to Manage 3D Settings > Global Settings. 
* Scroll down and find Shader Cache Size, then change the setting from the dropdown menu to Disabled. 
* Click Apply and close the NVIDIA Control Panel.
  
Delete the cache files: 
* Press Windows Key + R to open the Run dialog. 
* Type %USERPROFILE%\\AppData\\Local\\ and press Enter. 
* Open the NVIDIA folder, then open the GLCache folder and delete all the files and folders inside. 
* Go back to the %USERPROFILE%\\AppData\\Local\\ folder. 
* Find and open the NVIDIA Corporation folder. 
* Open the NV_Cache folder and delete all its contents. 
* Next, open the Run dialog again (Windows Key + R) and type %LOCALAPPDATA% (or just %APPDATA%) and press Enter. 
* Go to Local > NVIDIA > DXCache. 
* Delete all files inside the DXCache folder.
  
Re-enable and restart: 
* Open the NVIDIA Control Panel again. 
* Go to Manage 3D Settings > Global Settings. 
* Set Shader Cache Size back to its desired setting (or you can re-enable it). 
* Click Apply and then restart your PC. 

</details>

### Things generally not working and error messages

1. Check your antivirus program's log to make sure it's not affecting the list and exclude the list's folder if needed.
2. Reinstall the list, keeping the same folder locations to reset the list and fix any installation errors. You won't need to download the mods again.

## Changelog

**3.1.0**

**Save game safe if updating from 3.0.2 or above**

Game play and visual improvements. More challenging and rewarding spaceship combat. Balanced value of class C/M Stroud reactors, gyros and TNs supplemental reactors. New weapons and outfits.

[Full Changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md)

## Updating the Modlist

Before updating the modlist, check the [changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md) and it is advisable to back up your saves first. It will state in the changelog if you need to start a new game after certain updates.

**Updating to version 3.x from 2.x. It is required to install into a new folder, as there are significant changes.**

It is recommended that before updating to save the game whilst you are in space, doing nothing, sat in the cockpit, doing zero speed.

Any mods you have added to the list will be deleted and other changes you have made will be overwritten. If you want to keep additional mods you have added, add `[NoDelete]` before the mod name in the left hand pane of MO2.
![NoDelete prefix](https://github.com/user-attachments/assets/e9d88441-20be-45a2-a4dc-ad59a7a9a385)

Updating is the same process as installing the list. Make sure your paths are the same. 

If you get a message like the below, choose 'No'
![Missing content](https://github.com/user-attachments/assets/60522711-6dde-46b1-a8e6-c006d28eca17)

If the update has removed any mods, you'll get the following message, choose 'Yes'
![Content not present](https://github.com/user-attachments/assets/d66fafc1-2c54-4adf-9b72-a52b55667c1b)

## FAQ (Frequently Asked Questions)
**Q. I have a yellow bit in my health bar and am unable to get full health.**

A. This is environmental Damage, you will need to see a doctor or use nanobot injectors to heal this. You will get a random amount of environmental damage when starting the game without using SKK fast start.

**Q. Is this modlist compatible with Watchtower.**

A. Not out of the box, as weapons and armours will be vastly underpowered and need balancing. However, if you reinstall the mod Serenity of Stars and choose the Watchtower patch, the balancing should be done. The UI needs patching too (this will be built into Melius in the next version but for now [you can follow this guide by umat to patch the UI](https://github.com/eljefe303030/Melius/blob/4acc99ecf152ccd73daa3479f778d5a6f175fe66/assets/docs/Watchtower%20UI%20patching).

**Q. All my launches and landings (along with grav jumps) are switching to cockpit (first person)? Any way to change that to 3rd person?**

A. Right click the More Immersive Landings And Takeoffs mod in the left hand window, choose reinstall and change the options in the installer to what you want. For grav jumps, download the 3rd person version of [Grav Jump Reanimated](https://www.nexusmods.com/starfield/mods/14528?tab=files) mod and replace the current version. Finally, delete the 'shiproot.agx' file from the More Visualized Docking mod which is in the following path: `\mods\More Visualized Docking - Vanilla Enhanced & Default Speed\meshes\animtextdata\tables\graphs`.

**Q. How do I enable enemy health bars?**

A. [Follow these instructions](https://github.com/eljefe303030/Melius/blob/2ea64e7bb2c0a5a58bcf5ef94bcf7e18112571d3/assets/docs/Enabling%20Enemy%20Healthbars%20(Melius)v2.pdf).

**Q. I'm dying too easily, how do I change the difficulty?**

A. Change the difficulty settings in the main game menu and/or choose a lower headshop multiplier for the Human Damage mod (currently set to x5, so choose x2).

**Q. MO2 says there are missing masters and "the game will crash unless you install and enable the following plugins."**

A. You can safely ignore this error message. There are some patches for optional mods, if you don't have these the game will automatically disable the patches when you first run the modlist and the error message will go away.

**Q. My vehicle is not spawning when I land and remains where i took off.**

A. The Roverhaul mod requires enough space in your cargo hold. Make space or change the option in the Gameplay settings menu.

**Q. I get an "invalid file attributes found" error message when launching.**

A. This is because you have used Vortex and it has created a symlink to your Documents folder. You can still run the list without any issue but the message will appear every time you launch it. Either remove the symlink by changing the setting below in Vortex 

![symlink](https://github.com/eljefe303030/Melius/blob/4442e1be733c52220817d3f8d47c0ca5f561facf/assets/images/Symlink.webp)

OR change the following setting within Mod Organizer 2 *Settings>Plugins>BasicDiagnosePlugin>rightpanel:check_fileattributes=false* this won't fix the issue but will stop the error message from appearing.

**Q. How do I disable the conversation camera changes so that it uses the original system?**

A. Open the StarfieldCustom.ini file, which is located in the 'profiles' folder, locate the following 2 lines and add a '#' symbol at the beginning of both lines `fDialogueCameraFailsafeFPFOV=100` `fDialogueCameraCollisionRadius=2` Save the ini file.

**Q. Can I use a controller?

A. Yes, see [these instructions](https://github.com/eljefe303030/Melius/blob/96dc3f04f50b2083981c5843a8321bb02447f8fd/assets/docs/MWS%20Xbox%20Controller%20layout%20instructions.md) on how to bind any additional key commands.

## Support
Use the [Discord server](https://discord.gg/ZyakMg7CGN)

## Credits and Thanks
* The mod authors for all their hard work, skill and imagination.
* The Wabbajack team for making a tool that makes this possible.
* ElminsterAU for xEdit.
* [Bhaeron](https://next.nexusmods.com/profile/Bhaeron?gameId=4187) for a massive amount of contribution, too much to list here.
* Padi for being the Discord guru and making the Melius server what it is. DrukenReaps and Arkangel for moderating the server and keeping everyone in line, including myself.
* Pyke Lermon, EccentricMeat, Sithishade, [0Bek](https://next.nexusmods.com/profile/0Bek), DrukenReaps, Chris and anyone else on the Melius Discord server for mod suggestions and contributions.
* [AvatarV](https://www.youtube.com/@AvatarV/videos) for allowing us to use his amazing in game photos.
* NeuroticNinjah for creating the Melius MO2 splash screen and the top Nexus banner image.
* [ultramatt](https://www.nexusmods.com/starfield/mods/15126) for their ini settings and visual suggestions.
* Anyone who tries this list.

**Supporters**

Thank you so much for supporting me.
* 8Bit
* mustardwhisper
* whiskyjvck
* povel
* HawkDigital
* Hieronymos
* Yun
* Bonelord
* Chikdutabac
* daresert
* chaoticmartian
* Tempus
