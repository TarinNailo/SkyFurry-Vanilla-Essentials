# SkyFurry-Vanilla-Essentials

Wabbajack Modlist Installer by Tarin Nailo

<table stlyle="border: none;">
<tr>
<td><img src="https://github.com/TarinNailo/SkyFurry-Vanilla-Essentials/blob/main/screenshots/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://github.com/TarinNailo/SkyFurry-Vanilla-Essentials/blob/main/screenshots/skyfurry.png" width="72px" /></td>
<td><a href="https://discord.gg/prwgV7mN">SkyFurry Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing AVO](#downloading-and-installing-AVO)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating AVO](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

SkyFurry Vanilla+ Essentials (SVE) is designed as a base for your own SkyFurry modlist or a quick way to jump into the world of SkyFurry. Featuring lore-focused graphical enhancements, mandatory bug fixes and widely recommended tweaks along with method patching, it is the perfect base to build upon. SVE is made for Skyrim Special Edition Version 1.6.353 (also known as Anniversary Edition) and uses the .exe of that version as well so make sure your skyrim is up to date.

SVE also utilizes a Wabbajack features called "Stock Game" to leave your default skyrim installation directory completely untouched by creating its own portable MO2 installation with a clean skyrim game "root" local SVE. This means you can have SVE installed without affecting your current Skyrim/mod list! Be warned that a dirty skyrim installation could still impact SVE if you use mod organizers like Vortex that deploy/link their mods to the steam skyrim data directory. This only make SVE compatible with other MO2 modlists or other Wabbajack modlists.

SVE uses [Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/24791) by default however can support whichever weather mod you wish to use with a guide on changing the installed weathers here (coming soon).

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/) with a detailed breakdown of important mods or any mods that stray noticeably from vanilla behavior coming soon to help you configure the default modlist to your own taste.

**NOTE**: SVE **DOES NOT** require the paid "Anniversary Upgrade" to Skyrim but is compatible if you have purchased the upgrade.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

SVE is aimed at mid-tier machines so a system similar to the following is advised:

### 1080p
- CPU: Modern Quad or Hex core processor (R5 2600/i5-8600k or better)
- RAM: 16GB DDR4
- Drive: SSD
- GPU: 4GB VRAM such as 1660TI or 5600XT (2GB may be able to run it, but 4GB **stongly recommended**)

### 1440p
- CPU: Modern Hex or Octo core processor (R7 5800x/i7-10700k or better)
- RAM: 32GB DDR4 (16GB may run it, but 32GB **strongly recommended**)
- Drive: NVME SSD
- 6GB GPU

This modlist comes with BethINI to help with optimizing if you know how to use bethINI. You can also remove the ENB to try and get better performance at the expense of a less graphically pleasing game.

Space required: Approx 115GB (Downloads included)

## Installation

Installing SVE is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you do not have Nexus Premium you may have to run wabbajack a few times if mods time out due to slow/throttled connection and the install may take upwards of 8 hours to download. For this reason Nexus Premium is highly recommended to save yourself some time!

 If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing SVE, please complete the following steps. Clean installation of Skyrim is not 100% required due to useage of Wabbajack's "Stock Game" feature but is good practice if you do not have a large mod setup you wish to preserve.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. (optional steps 3-6) Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the games to the main menu in order to download all the creations if you have purchased the AE Upgrade.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing SVE

Downloading and installing SVE can take a while depending on your internet connection and computer. To install SVE, complete the following steps.

1. Download the .wabbajack file for this modlist from this page's files section.
2. Open Wabbajack (The .exe you installed above) and click "Install From Disk".
3. Set the installation folder to be somewhere like C:\Games\SVE. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing much faster.
5. Press the play button to begin.
6. Go and get a cup of coffee, pet your nearest furbaby if you have one, or take a nap whilst Wabbajack does its thing. Alternatively read through this readme completely or at least the description of the important mods provided! Depending on your internet connection, if you have Nexus Premium, and your computer this could up to a few hours.
7. If the installation is successful, you are almost ready to play so move onto [post installation](#post-installation). If the installation is unsuccessful, move on below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step to make sure your game is installed correctly.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

SVE uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all. If you have the AE Upgrade version and downloaded the Creation Club Contents from the main menu make sure all mods labeled AE CC are activated in Mod Organizer 2.

### ENB
SVE comes out of the box with support for an ENB with [The Perfect PredCaliber Approved ENB Cocktail](https://www.nexusmods.com/skyrimspecialedition/mods/55526?tab=files) availiable for use alongside ENB Organizer to manage ENBs. If you want to install your own ENB put them into a seperate folder in 'SVE\Tools\ENB Organizer\Games\SkyrimSE\Presets'.

#### Using ENB Organizer

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big run button next to it. Run the program named `Pick Your ENB` from Mod Organizer 2.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%201.png?raw=true)

If the image below comes up, simply press OK. It is nothing to be concerned about.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/Ignore%20Warning.png?raw=true)

Navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%203.png?raw=true)

Activate the ENB you wish to use by pressing the slider. To deactivate it, simply press the slider.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%205.png)

For adding your own presets and more details, take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the run button.

### In-Game MCM options
`SVE has no MCM options required, however you can load the SmoothCam preset if you wish.`

- This serves as a placeholder in case you want to use the Readme as some sort of template.

## Adding mods to SVE

To safely add mods to SVE, please read [the guide](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Adding%20mods%20to%20AVO.md) which covers some of the details you need to know. Even if you are an experienced modder it is worth reading. This modlist is [Method Patched](https://gist.github.com/CovenantTurtle/9992289653e91455a06753ef6275590a) to make customization easier.

### Using LOOT with SVE

Before you can use LOOT while adding mods to SVE, you must setup LOOT with the custom userlist.yaml downloaded with SVE. You can find a guide on how to do so [here](https://github.com/TarinNailo/SkyFurry-Vanilla-Essentials/blob/main/LOOT.md).

### Anniversary Edition

SVE supports the latest verison of Skyrim, but **does not require** the paid update. 

If you have the paid update, you will need to enable a few extra mods so that SVE will work with it. I have not fully tested the list against all the AE content, however I have downloaded any compatibility mods for them I could find and have done custom conflict resolution for the modlist based on conflicts I saw in xEdit. I expect all the CC content will likely work but there may be some bugs as not all the mods in this list expect the AE CC content to be in the game. Please let me know if you find any bugs with the AE content and the [b]DEFAULT[/b] SVE modlist.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You will have to update your save after every major version of this modlist (E.g. 1.x.x -> 2.x.x).

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating. You can always install this as a new modlist to preserve your old installation. Saves that used mods outside this list however will NOT be compatible.

## FAQ

Coming soon as I get and answer questions after the release of this modlist.

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must then you can.

## Removing the Modlist
Simply delete the folder and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The SkyFurry Team for their wonderful mods.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team for building this tool to make Bethesday modding so accesible.

## Modlist References
- [Bugs Fixes and Patches Masterlist V2 - AE Update](https://www.reddit.com/r/skyrimmods/comments/vm9ltd/bug_fixes_and_patches_masterlist_v2_ae_update/)

## Contact

For help and support I hope to have a channel for this within the [SkyFurry Discord](https://discord.gg/DffHKcszfg), but please check the [issues](https://github.com/TarinNailo/SkyFurry-Vanilla-Essentials/issues) tab on this github first if you have any issues before posting there as well as the FAQ in this readme. PLEASE DO NOT DM ME OR ANYONE ON THE SKYFURRY TEAM.

You are welcome to [contribute](https://github.com/TarinNailo/SkyFurry-Vanilla-Essentials/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/TarinNailo/SkyFurry-Vanilla-Essentials/blob/main/Changelog.md) before you do.

## The SVE Team (Looking for Testers, Support, and maintainers!)
- Tarin Nailo - Original Creator and SkyFurry supporter/tester