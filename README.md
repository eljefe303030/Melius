# Preamble

Melius is a modlist hevily based on [JaeDL's](https://next.nexusmods.com/profile/JaeDL?gameId=4187) excellent [Starborn Royalty](https://www.nexusmods.com/starfield/mods/6397) and includes graphic mods and settings by [Luxor](https://www.nexusmods.com/starfield/users/50525966). Main aim is to make the game as enjoyable as possible, whilst improving graphics, audio and adding quality of life mods.

I created this list based on my persoanl preferenes and I am sharing this so others can have a modded version of Starfield, without having to spend the time I did trying out different mods and working out the load order etc. However, please be aware that this is my first Wabbajack list I have shared, I have tested this is much as possible but there is a risk this might not work for everyone. I will endevour to provide support in fixing any teething issues but I am just one person who has a full time job and life outside of doing this.

## Requirements

I have tested this on both a AMD 3600/AMD Radeon RX 580 and AMD 5700X3D/AMD 7800 XT and on both systems it works well without any noticable drops in FPS. However, planet textures can take a second to load, this may be mitigated with a faster SSD.

Your computer will need to meet at least the [minimum requirements specificed by Bethesda](https://help.bethesda.net/#en/answer/60442) 

## Pre-installation Steps

1. Install [Visual C++ x64 Redistributables](https://aka.ms/vs/17/release/vc_redist.x64.exe).
2. Install [Microsoft .NET 5.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime) and [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0/runtime) (both console apps and desktop apps x64).
3. Fully disable OneDrive and any other programs that hook into user file areas.
4. Reinstall Starfield into a location that is not Program Files. Somewhere like C:\Games is a good location. You MUST have the latest version of Starfield, version 1.14.74.0 and it MUST be a clean install.
5. Set Starfield to not automatically update.
6. Right click Starfield in Steam, click Properties, disable Enable the Steam overlay while in-game.
4. Language set to English. You can check translations of the modes on NexusMods but I cannot support you with that.

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
2. 3. Create the installatioin folder e.g. C:\Melius
4. Create the mod download folder e.g. C:\Melius mod downloads. The download folder can be on a different drive. This can be deleted after the installation has completed but is not advised, as if you want to update or reinstall, you'll need to redownload all the mods again.
5. In the WABBAJACK folder, run Wabbajack.exe to install the Wabbajack program
6. After the install has completed, run Wabbajack.exe once more
7. Browse the Starfield modlists to choose Melius. You may need to filter by unoffical lists.
8. Choose the Mod Installation Location and Resource Download Location paths you set earlier for the installation and mod download folders.
9. If you have a premium Nexus membership, it will install automatically, if you don't, you will have to click slow download for each and every mod.
10. Once completed it's installed.

## Post-installation Steps

### Root Builder
The list also uses Kezyma's Root Builder to keep the game root folder clean. Any mod that needs to be installed in the game folder is instead added to MO2 with a special file structure, and is then added to the game folder whenever the game is running.

achiement enabler error messages
restart to enable sounds
Dont not skip to Lodge if using skip start mod
Start using SFSE only via MO2

## Important mods you should know about

## Changelog

This is the initial release.

Include:

Support, use Discord server


