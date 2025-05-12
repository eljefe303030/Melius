# **Melius**
![MeliusPause720](https://github.com/user-attachments/assets/db6c5804-591d-4977-8edd-6eaeceb566d2)

<p align="center">
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License</a>

<p align="center">
  <a href="https://www.nexusmods.com/starfield/mods/12658">Nexus Page</a> |
  <a href="https://discord.gg/ZyakMg7CGN">Discord</a> |
  <a href="https://loadorderlibrary.com/lists/melius-2">Full Modlist</a>
  <a href="https://github.com/eljefe303030/Melius/blob/main/changelog.md">Changelog</a>
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
  * [If you have the Shattered Space DLC](#if-you-have-the-shattered-space-dlc)
  * [Starting Mod Organizer 2](#starting-mod-organizer-2)
  * [Mod Organizer 2 Profiles](#mod-organizer-2-profiles)
* [Important mods you should know about](#important-mods-you-should-know-about)
* [Optional Mods](#optional-mods)
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
Melius is a Starfield Wabbajack modlist originally based on [JaeDL's](https://next.nexusmods.com/profile/JaeDL?gameId=4187) excellent [Starborn Royalty](https://www.nexusmods.com/starfield/mods/6397) but now also has an optional profile based on [Ascension - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/6839) and [Starvival - Immersive Survival Addon](https://www.nexusmods.com/starfield/mods/6890). Main aim is to make the game as enjoyable as possible, whilst improving graphics, audio and adding quality of life mods.

Stability, a list that works irrespective of whether you have the Shattered Space DLC and is performance friendly, are other key aims of this list. Note: Starvival will only be enabled if you have the DLC.

I created this list based on my personal preferences and I'm sharing this so others can have a modded version of Starfield, without having to spend the time I did trying out different mods and working out the load order etc. I have tested this as much as possible and I will endeavour to provide support in fixing any issues but I am just one person who has a full time job and life outside of doing this.

*Please note, the loadorder library site is currently out of date, as the website is having some issues*

## Modlist

The full list of mods can be found on [Load Order Library](https://loadorderlibrary.com/lists/melius-2)

## Requirements
* I have tested this on both a AMD 3600/AMD Radeon RX 580 and AMD 5700X3D/AMD 7800 XT and on both systems it works well without any noticeable drops in FPS.
* Your computer will need to meet at least the [minimum requirements specified by Bethesda](https://help.bethesda.net/#en/answer/60442)
* Language set to English.
* You need the latest Steam version (1.14.74.0) of the game.

## Pre-installation Steps
1. Install [Visual C++ x64 Redistributables](https://aka.ms/vs/17/release/vc_redist.x64.exe).
2. Install [Microsoft .NET v8.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer) and [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0/runtime) (both console apps and desktop apps x64).
3. Fully disable OneDrive and any other programs that affect user file areas.
4. Reinstall Starfield into a location that is not Program Files. Somewhere like C:\Games is a good location. You MUST have the latest version Steam of Starfield, version 1.14.74.0 and it MUST be a clean install.
5. Set Starfield to not automatically update.
6. Right click Starfield in Steam, click Properties, disable *'Enable the Steam overlay while in-game'*.
4. Language set to English. You can check translations of the mods on NexusMods but I cannot support you with that.
5. Start a new game. I will not provide support if you use this list on an existing save game, as there could be issues from other mods you used.

## Using Wabbajack
1. Download the latest version of [Wabbajack](https://www.wabbajack.org/) and place it in a folder near or at the root of your drive, e.g. C:\Wabbajack
2. Create the installation folder e.g. C:\Melius
4. Create the mod download folder e.g. C:\Melius mod downloads. The download folder can be on a different drive. This can be deleted after the installation has completed but is not advised, as if you want to update or reinstall, you'll need to redownload all the mods again.
5. In the WABBAJACK folder, run Wabbajack.exe to install the Wabbajack program
6. After the install has completed, run Wabbajack.exe once more
7. Make sure you are logged into Nexus. Click on the gear icon in the bottom left hand corner and click login to Nexus Mods.
8. Browse the Starfield modlists to choose Melius. You may need to filter by *non featured* lists.
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
### If you have the Shattered Space DLC
Copy the following 5 files from your Starfield Steam installation folder folder e.g. from C:\Steam\steamapps\common\Starfield\Data

1. ShatteredSpace - Main01.ba2
2. ShatteredSpace - Main02.ba2
3. ShatteredSpace - Textures.ba2
4. ShatteredSpace - Voices_en.ba2
5. ShatteredSpace.esm

To inside the Data folder of your Stock Game folder e.g. into C:\Melius\Stock Game\Data

If your version of Starfield came with the Constellation and Old Mars skins, you can copy these files over too into the stock game folder, these files if you have them are as follows:

1. Constellation - Localization.ba2
2. Constellation - Textures.ba2
3. Constellation.esm
4. OldMars - Localization.ba2
5. OldMars - Textures.ba2
6. OldMars.esm

### Starting Mod Organizer 2
1. Launch ModOrganizer.exe in the Melius installation folder. If you get a popup asking about nxm links. Click Yes.

### Mod Organizer 2 Profiles
There are three profiles:
* DO NOT USE THIS PROFILE - do as it says!
* Melius - this is the original version based around Royal Galaxy and is a vanilla plus profile.
* Melius Hardcore - this is based around Ascension and Starvival and overhauls a lot of the gameplay. (Starvival will not be enabled unless you have the Shattered Space DLC).

Choose which profile you want to use but do not change profile mid playthrough, as it will cause major issues. Keep separate saves for each profile, MO2 will do this for you.

![MO2 Profiles](https://github.com/user-attachments/assets/8e25c239-395e-44ba-a724-fc02d04309f1)

* If you do not have the Shattered Space DLC, on first starting MO2: it will display a warning that there are missing masters ![MO2 warning icon](https://github.com/user-attachments/assets/cb59bebe-af62-430f-9a4b-0f79a2bf593a). This is normal and the warning message will disappear after you have run the game the first time.
 
2. Only launch Melius through MO2 via the 'Starfield SFSE'. **Do not start through Steam or by selecting Starfield in MO2**, as this will result in mods not working.
![start SFSE](https://github.com/user-attachments/assets/101caa91-dba3-4620-95ba-1a60a22f48e9)
4. **Do not press the Unlock button** that MO2 displays after clicking run. The game may take a few minutes to start, this is normal.
6. Messages saying achievements will be disabled can be ignored, they won't be disabled. See [Baka Achievement Enabler (SFSE)](https://www.nexusmods.com/starfield/mods/658?tab=posts) description on why this is the case and how it works. Click 'yes' when the below is shown on first starting your playthrough.

![Achievements initial message](https://github.com/user-attachments/assets/04b7f127-2afb-4e5f-9701-0a0c7ff1cc95)
   
8. After starting the game for the first time, the sound will not work properly, save the game when you are able to, close the game down and reloading your save will correct this.

## Important mods you should know about

1. [El Jefe Combat AI](https://www.nexusmods.com/starfield/mods/13194) and [Bedlam](https://www.nexusmods.com/starfield/mods/10717) to make combat more fun and interesting
2. [Royal Galaxy](https://www.nexusmods.com/starfield/mods/8222) changes a large number of things, including bug fixes, QOL improvements, stronger Terrormorphs and Ashta, increased enemy spawns, and potent Starborn magic. Diversifies encounters, Points of Interest, Weathers, and Climates. **only included in Melius profile**
3. [Royal Skies Space Combat](https://www.nexusmods.com/starfield/mods/7890) Overhaul of spaceship combat. Enemies will occasionally fly into you, either because they cannot get out of the way or deliberately. **only included in Melius profile**
4. [Ascension - Gameplay Overhaul](https://www.nexusmods.com/starfield/mods/6839) overhauls the gameplay in many ways. **only included in Melius Hardcore profile**
5. [CINE FIDELITY LUTS](https://www.nexusmods.com/starfield/mods/3767) & [Neutral LUTs - No Color Filters](https://www.nexusmods.com/starfield/mods/323) changes the LUTs of the game to remove the colour filters and make the game look a lot better. Thanks to [Luxor for the guide](https://www.nexusmods.com/starfield/mods/11413) on how to use these to best effect.
6. [StarUI suite of mods](https://next.nexusmods.com/profile/m8r98a4f2/mods?gameId=4187) to change the UI to make it easier and nicer to use.
7. [Starvival - Immersive Survival Addon](https://www.nexusmods.com/starfield/mods/6890) **active in the Melius Harcore profile but is optional** provides a fully working NEEDS mechanic with stages, new addictions, Spaceship Refueling and full list of other complimentary features. **This mod requires the Shattered Space DLC.** You need to enable this mod in the games settings menu. Do this after you have started your new game and made your first save. If you enable it before starting a new game, it will not start. Read the Starvival mod's page and the in-game help menu (Esc and then select Help) to understand how this mod works and the options you can change. Options are changed using the Starvival Options book in your notes section of your inventory. My suggestions are as follows but you can change these to match your preferred playing style. You can always just enable a few features to start and introduce others later on.

| Option | Location in Starvival Options Book | Enable/Disable | Comment |
| ------ | ------- | ------ | ------ |
| Basic Needs | Systems | Disable |
| Adrenaline | Systems | Disable |
| Survival Damage | Systems | Disable | Managed by other mods in this list |
| Tougher Tin Cans | Systems | Disable | Managed by other mods in this list |
| Tougher Creatures | Systems | Disable | Managed by other mods in this list |
| ADS O2 Depletion | Tweaks - Weapon Handling - Other Functions | Disable |
| Paranoid treatment | Tweaks - Intoxication - Addiction | Disable |
| Provision/morale system | Tweaks - Crew Morale | Disable |
| Spaceship Systems | Systems | Enable |
| Cassiopeia | Tweaks - Spaceship Systems - Other | Enable | Calculates fuel usage accurately |

8. Various mods to change the transitions and animations to make them more immersive and less annoying
8. [Rabbit’s suite of mods](https://next.nexusmods.com/profile/RabbitDoesStuff?gameId=4187) to make area lighting more realistic and playable i.e. not having to walk around in the dark when there are lights around you!
10. [Revelation - Main Quest Overhaul](https://www.nexusmods.com/starfield/mods/10418) This mod overhauls Starfield's main quest, including removing most Temples. **only included in Melius Hardcore profile**
11. [Simple Immersive Helmets](https://www.nexusmods.com/starfield/mods/4930) adds an overlay to the screen when wearing a helmet to provide reflections, as you could expect when having glass in front of you.
12. [Commitment (Keep Divorce Options)](https://www.nexusmods.com/starfield/mods/13436) Choose only Vanguard, Ranger or Ryujin Operative. Force disguise when undercover for SysDef. **only included in Melius Hardcore profile**
    
## Optional Mods

Within the left hand pane of MO2 there is a section for optional mods. Click on the mod you want to enable and it will highlight it in the right hand pane. Put a tick next to it in the right hand pane to enable it: 
1. [Doubled Enemy Numbers](https://www.nexusmods.com/starfield/mods/6030) doubles the number of enemies. Royal Galaxy already increases enemies by 1.5 but use this if you want even more. **not recommended for the Melius Hardcore profile**
2. [DualSense - PS5 Icons](https://www.nexusmods.com/starfield/mods/215) use this if you use a PS5 controller. Enable this mod by putting a tick next to it in the left hand pane, in the *'Optional'* section. 
3. [Immersive Landing Ramps](https://www.nexusmods.com/starfield/mods/8093) highly recommended you enable this, changes the landing ramps for your spaceships to manual control. Read the mod page before enabling to see how it works.
4. [Legendary Module Recycler](https://www.nexusmods.com/starfield/mods/6074) great mod that give you the ability to remove modules from legendary weapons and spacesuits etc. This can make you overpowered if not used responsibly.
5. [No Rescale on Interact](https://www.nexusmods.com/starfield/mods/7945) Enable if using NPC Height Variation Mod.
6. [NPC Height Variation Mod](https://www.nexusmods.com/starfield/mods/7466) Varies NPC heights but can cause clipping of female NPCs and furniture.
7. [NPC Female Height Patch](https://www.nexusmods.com/starfield/mods/12812) Enable if using NPC Height Variation Mod.
8. [Royal Recycler Patch](https://www.nexusmods.com/starfield/mods/10581?tab=files) not essential but recommend if you use Legendary Module Recycler, as this keeps the text changes from Royal Galaxy. **do not use with the Melius Hardcore profile**
9. [ReShade](https://reshade.me/) - adds visual effects that increase the contrast between light and dark. Does have some FPS impact. Can cause some visual effects to get stuck, if this happens, reload your save. Worth the downsides in my opinion. Enabled by default, to disable untick next to it in the left hand pane, in the *'Optional'* section. 
10. [Royal - Hard Mode Patch](https://www.nexusmods.com/starfield/mods/10581?tab=files) All Starborn, Creature, and Terrormorphs have slightly harder level scaling, damage, and movement speed. Player HP gain per level reduced to 15. 0.85x leveling speed. **do not use with the Melius Hardcore profile**
11. [Gorefield - A Starfield Gore Framework](https://www.nexusmods.com/starfield/mods/12833) Introduces special death effects such as bodies exploding, disintegrating and burning. Options for this mod, including turning it on/off are in the Settings -> Gameplay Options. Will cause missing body textures around the next of NPCs if used with [Simple Immersive Looting](https://www.nexusmods.com/starfield/mods/12677) when their heads have been blown off. Turn off headshot effects in the settings to avoid this.
12. [SKK Fast Start New Game (Starfield)](https://www.nexusmods.com/starfield/mods/5971) Fast Start New Game bypasses the Argos-Atlantis tutorials starting new and NG+ games from Lodge, Cydonia, Akila, Neon, Den or random location with full character configuration and some loadout choices. If you use this mod, read the mod pages for [Immersive Landing Ramps](https://www.nexusmods.com/starfield/mods/8093) and [Hide Show Helmet And Spacesuit Switch](https://www.nexusmods.com/starfield/mods/12324) as the items you need for these mods will need to be acquired within the game for the mods to be useable. When you start a new game with this mod the Ships Controls mod screen will appear, press the 'tab' key to go out of this screen and to continue. Go to you inventory, it will say it is not available, exit out of that screen, a message will say the mod setup has completed and you can then continue as normal.
13. [Smart Aiming SFSE - Third to First Person](https://www.nexusmods.com/starfield/mods/11706) Automatically switch to first person when aiming your weapon, and back to third person upon release. Enable this mod by putting a tick next to it in the left hand pane, in the *'Optional'* section.
14. [Vanilla Flashlight Improved (VFI)](https://www.nexusmods.com/starfield/mods/701) alternative and brighter flashlight. If you use this, make sure you disable the default flashlight 'Luxor's realistic Flashlight HD'.

### Manuel Installations
1. [Vanilla Landing Animations](https://www.moddb.com/mods/vanilla-landing-animations) mod that restores the default landing animations for every landing at major cities and settlements by setting discovery of the landing zone to undiscovered, therefore it works best with new game or ng+.
2. Since version 1.3.0 of this modlist, a lot of HD texture mods have been removed to help reduce the mod list download size and make the list more performance friendly. If you would like to have the best possible graphics, I highly recommend you use the [Starfield HD Overhaul mod](https://www.nexusmods.com/starfield/mods/5124). This is save safe to add or remove during a playthrough.

### Modifications to the modlist
Any modifications you make to the modlist, other than the optional mods listed above, are unsupported. I would be interested to hear if you have any recommendations for mods, let me know in my Discord server.

Do not update any mods within this mod list. Reason being is that mods have been patched, both by including a patch file and binary patching. Consequences of updating mods can include mods no longer functioning at intended to the whole mod list not working.

## Gameplay Guide

* Auto saves are disabled by default but can be enabled in the settings menu of the game.
* [Baka Quick Full Saves](https://www.nexusmods.com/starfield/mods/1750) changes quick saves to full saves, which means you will have more saves and will need to periodically delete saves as and when needed.
* Multiple mods change UI elements to 60 fps. Reinstall the UI mods by right clicking on them in the left hand pane of MO2 to choose your own preferences and settings.
* [Fast Travel To Unknown](https://www.nexusmods.com/starfield/mods/6663) means you can fast travel to unknown POIs when using the hand scanner.
* [Auto Unlock SFSE](https://www.nexusmods.com/starfield/mods/5571) Auto unlock doors, containers and terminals (including inaccessible) if you have the required perks.
* [Short Temple Puzzles](https://www.nexusmods.com/starfield/mods/1139) changes the number of puzzles to 3.
* [Build Outpost Items with Credits](https://www.nexusmods.com/starfield/mods/11890) Allows you to build all outpost/ship objects with credits instead of resources.
* [Sit To Add Ship to Fleet](https://www.nexusmods.com/starfield/mods/6493) Sit in pilot seat to add captured ship to your fleet. No need to make it your home ship.
* [Magic Boost Disabler](https://www.nexusmods.com/starfield/mods/12776) and [Hide Show Helmet And Spacesuit Switch](https://www.nexusmods.com/starfield/mods/12324) are used to ensure boost packs do not become visible when your spacesuit is not visible and gives you control over when your spacesuit is visible. Add the spacesuit add/hide switch as a favourite item for ease and use in conjunction with the toggle to show/hide suits in settlements option within your inventory screen. The switch can be found at Argos Extractors Mining Outpost, where your character wakes up during the intro of the game.
* [Leave No Witnesses](https://www.nexusmods.com/starfield/mods/12000) Reworks player bounties so that killing all witnesses to a crime you commit in space removes the bounties incurred while committing that crime.
* [Landing Bay Cargo Access](https://www.nexusmods.com/starfield/mods/11972) Adds an interactive cargo panel to each landing bay module, allowing you to access your ship's cargo hold remotely - at your ship, but outside your ship. If the cargo panel doesn't show up on your ship, you may have to refresh your ship's landing bay cell by modifying your ship in the ship builder.
* [Polyamory - Remove single romance limit](https://www.nexusmods.com/starfield/mods/10687) Removes the restriction on multiple companion romances.
* [Auto Transfer Mined and Harvested Resources to Your Ship - SFSE](https://www.nexusmods.com/starfield/mods/8606) SFSE plugin that automatically transfers mined mineral deposits and harvested resources to your Homeship instead of your inventory. Some quests that involve collecting resources will mean you then have to collect them from your ship instead of your inventory. **Disabled by default in the Melius Hardcore profile**
* [Human Damage (Just a Flesh Wound - Bullet in the Head)](https://www.nexusmods.com/starfield/mods/12603) Changes the damage multiple for the different areas of body parts of humans to make the game more fun and rewards better aiming. Headshot multiplier is set to x20 which means headshots are deadly for you and most enemies, some bosses might take 2 or 3 headshots to kill them. If you want to change this, download the latest version of the mod, which give you a choice of headshot multiplier. Make sure to place it in the correct position in the right hand pane and disable the old version.E.g. if you select a x10 multiplier, it will look like below.
![Human Damage load order](https://github.com/user-attachments/assets/aa06ad59-fdd0-4d71-8d8d-a886d8c90a48)
* [StarUI HUD](https://www.nexusmods.com/starfield/mods/3444) has been configured to not show enemy health bars or steath meters for immersion, see the mod page for how to configure this to your tastes. Crosshairs have also been disabled, these can be displayed by changing the game 'interface' setting.
* [Starfield Performance BOOST](https://www.nexusmods.com/starfield/mods/290) has been used to update the low, medium, high and ultra graphic settings profiles. To use these, select the profile you need. If the profile you want to use is already selected, select another one and then select the one you want e.g. if you want to use the 'high' profile and that is already selected, choose a different one and then select 'high' to enable it.
* [Stew - Manual Reload](https://www.nexusmods.com/starfield/mods/4451) Stops the player automatically reloading when running out of clip ammo.
* [Toggle Quest Markers with Scanner and Ship HUD](https://www.nexusmods.com/starfield/mods/50200) Simple immersion mod that toggles the Floating Quest Marker on or off with your hand scanner or spaceship HUD.
* [Starware Search Engine - SFSE](https://www.nexusmods.com/starfield/mods/13643) Implements a search engine to the Galaxy StarMap Menu, allowing you to find any location and planet within seconds.
* [Manual Weapon Stance](https://www.nexusmods.com/starfield/mods/13627) Adds a customizable hotkey to raise or lower your weapon at will. No more automatic lowering—you’re in full control. Works in both first and third person. Lightweight, immersive, and highly compatible. *[For those of you who are using a controller, follow these steps](https://github.com/eljefe303030/Melius/blob/main/MWS%20Xbox%20Controller%20layout%20instructions.md)*

# Recommended Settings
**Gameplay Options**
* Damage options - if you are finding it difficult, reduce the damage for a while until you level up/gain perks
* Other settings:
![Screenshot 2025-04-20 200648](https://github.com/user-attachments/assets/384a1908-f63b-4782-ad32-66dbd379a3a6)
![Screenshot 2025-04-20 201058](https://github.com/user-attachments/assets/b2fd6cbb-b60b-45bb-9163-1c91d3bebdd0)
![Screenshot 2025-04-20 201124](https://github.com/user-attachments/assets/00f24c5b-29c7-4ae3-832f-271e3e9f399c)

**Display**
* Brightness set to 2.62 and contrast to 0.90
* Motion Blur - off
* VSync - off
* Sharpening 25%
* Film Grain Intensity set to zero

## Note for Content Creators

Some of the added music in the list cannot be played on YouTube/Twitch or other platforms due to DMCA rules. To circumvent this, I recommend either disabling the mod PopcornTime or disabling in-game music by lowering the volume to 0% in the audio settings.

## Known Issues

1. The mod Weapon Sound Fixes has the side effect of controller vibration for Maelstrom, Grendel and some other weapons being low to non-existent.
2. The larger your inventory contents, the more lag you will experience when coming in and out of menus, especially if you have added the HD Overhaul mod. I do not know a fix for this except stashing excess inventory (including ammo) into a safe container.
3. The Random NPC Height mod can cause clipping for female NPCs and furniture.
4. If you have an issue where crew or companions freeze, try updating the [Landing Animations Reloaded](https://www.nexusmods.com/starfield/mods/7569) mod to the latest version, using the instructions on the mod page. **(Version 2.0 only of Melius only)**
5. Not all the additional clothing combinations are compatible with each other and can cause visual glitches/clipping in both the preview and in game views. Choose a different combination of outfits if this occurs.
6. [DualSense - PS5 Icons](https://www.nexusmods.com/starfield/mods/215) mod is enabled by default, if you use an Xbox controller, untick this mod in the *optional* section in the left hand pane of MO2. This will be disabled by default in the next release.
7. If you get false contraband notifications, turn off Starfarer in Starvival's settings (Configuration Book >>> Tweaks >>> Spaceship Systems >>> Other >>> Starfarer Mode [Off]). If you still have this issue, update to the latest version of Starvival and make sure Starfarer is disabled.
8. After going through Unity, Starvival will turn itself off and reset all of its settings. Turn Starvival back on and make your changes to settings. NPCs might have missing body parts. Save game, exit and reload will fix this.
9. Starvival boostpacks needs fuel will enable you to use boostpack when out of fuel, as needs patch to work with Ascension.

## Changelog

2.1 Adds a number of mods that provide some visual, audio and gameplay improvements/changes. Added Starvival to the Melius Hardcore profile, Starvival requires the Shattered Space DLC but both profiles can be played without the DLC.
**This version will need a new game.**

[Full Changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md)

## Updating the Modlist

Before updating the modlist, check the [changelog](https://github.com/eljefe303030/Melius/blob/main/changelog.md) and it is advisable to back up your saves first. It will state in the changelog if you need to start a new game after certain updates.

**Updating to version 2.x. It is recommended to install into a new folder, as there are significant changes. If you upgrade instead, do not use the old profiles, instead use one of the two new profiles. Remember to copy across the Shattered Space files (as described below) if you have them.**

**If you are struggling for drive space, delete your installation folder but not your downloads folder and treat it as a new installation. Backup your save games first, so you can revert to the previous version later if you so desire.**

It is recommended that before updating to save the game whilst you are in space, doing nothing, sat in the cockpit, doing zero speed.

Any mods you have added to the list will be deleted and other changes you have made will be overwritten. If you want to keep additional mods you have added, add `[NoDelete]` before the mod name in the left hand pane of MO2.
![NoDelete prefix](https://github.com/user-attachments/assets/e9d88441-20be-45a2-a4dc-ad59a7a9a385)

Updating is the same process as installing the list. Make sure your paths are the same. 

### Shattered Space DLC
If you have the Shattered Space DLC, copy the following 5 files from your Starfield Steam installation folder folder e.g. from C:\Steam\steamapps\common\Starfield\Data

1. ShatteredSpace - Main01.ba2
2. ShatteredSpace - Main02.ba2
3. ShatteredSpace - Textures.ba2
4. ShatteredSpace - Voices_en.ba2
5. ShatteredSpace.esm

To inside the Data folder of your Stock Game folder e.g. into C:\Melius\Stock Game\Data

If your version of Starfield came with the Constellation and Old Mars skins, you can copy these files over too into the stock game folder, these files if you have them are as follows:

1. Constellation - Localization.ba2
2. Constellation - Textures.ba2
3. Constellation.esm
4. OldMars - Localization.ba2
5. OldMars - Textures.ba2
6. OldMars.esm

If you get a message like the below, choose 'No'
![Missing content](https://github.com/user-attachments/assets/60522711-6dde-46b1-a8e6-c006d28eca17)

If the update has removed any mods, you'll get the following message, choose 'Yes'
![Content not present](https://github.com/user-attachments/assets/d66fafc1-2c54-4adf-9b72-a52b55667c1b)

## Support
Use the [Discord server](https://discord.gg/ZyakMg7CGN)

## Credits and Thanks
* JaeDL for permission to use Starborn Royalty as a basis for this list.
* [Seb263](https://www.nexusmods.com/starfield/users/825950) for the [Responsive Grabbing](https://www.nexusmods.com/starfield/mods/289) ini setting.
* The mod authors for all their hard work, skill and imagination.
* The Wabbajack team for making a tool that makes this possible.
* [Bhaeron](https://next.nexusmods.com/profile/Bhaeron?gameId=4187) for writing the Manual Weapon Stance controller settings guide, mod suggestions and beta testing.
* Padi for being the Discord guru and making the Melius server what it is.
* Rainman for beta testing and mod suggestions.
* Pyke Lermon, EccentricMeat, Sithishade and anyone else on my Discord server for mod suggestions
* Anyone who tries this list.




