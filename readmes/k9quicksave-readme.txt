*********************************************
*                                           *
*          Quick Save Slots Tweaks          *
*                   v 1.6                   *
*                                           *
*********************************************

A Spellhold Studios mod for BG:EE (with or without SoD), BG2:EE, IWD:EE and PsT:EE

WARNING: This mod is not compatible with EET
-------


I. Overview
===========

This mod lets you choose between having 1 to 4 different quick save slots in BGEE, SoD, BG2EE, IWDEE and PSTEE.



II. Compatibility
=================

This mod is designed to work on the series of Enhanced Editions published by Beamdog, which at present includes:

- Baldur's Gate: Enhanced Edition (BGEE).
- Baldur's Gate II: Enhanced Edition (BG2EE).
- Icewind Dale: Enhanced Edition (IWDEE).
- Planescape Torment: Enhanced Edition (PSTEE).

The BGEE Siege of Dragonspear expansion (SoD) is supported as well. All of the Enhanced Edition games include the original expansion packs, e.g. IWDEE includes Heart of Winter (HoW) and Trials of the Luremaster (TotLM).



III. Installation
=================

# Notes
 ------
If you've previously installed the mod, remove it before extracting the new version. To do this, run `setup-k9quicksave.exe`, un-install all previously installed main component and delete the k9quicksave folder.

When installing or un-installing, do not close the DOS window by clicking on the "X" button! Instead, press the "Enter" key whenever instructed to do so.

Disable any antivirus or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.


# Special Note for Siege of Dragonspear from Steam/GOG
  ----------------------------------------------------
Good Old Games (GOG) and Steam both package the additional content for Siege of Dragonspear in a method that WeiDU, the tool used to install this mod, cannot access. You must run a program called "DLC Merger" on your SoD installation before you can install this or any other WeiDU-based mod: https://github.com/Argent77/A7-DlcMerger/releases/latest


# Enhanced Editions Note
  ----------------------
The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.


# Windows
  -------
The Quick Save Slots Tweaks mod for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (the folder which contains the "CHITIN.KEY" file). On successful extraction, there should be a k9quicksave folder and a setup-k9quicksave.exe file in your game folder. To install, simply double-click `setup-k9quicksave.exe` and follow the instructions on screen.

Run `setup-k9quicksave.exe` in your game folder to reinstall, un-install or otherwise change components.


# Mac OS X
  --------
The Quick Save Slots Tweaks mod for Mac OS X is distributed in the same compressed archive and includes a WeiDU installer.

First, extract the files from the archive into your game directory. On successful extraction, there should be a k9quicksave folder, setup-k9quicksave and setup-k9quicksave.command files in your game folder. To install, double-click `setup-k9quicksave.command` and follow the instructions on screen.

You can run `setup-k9quicksave.command` in your game folder to reinstall, un-install or otherwise the components settings.


# Linux
  -----
The Quick Save Slots Tweaks mod for Linux is distributed in the same compressed archive and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from WeiDU ( https://github.com/WeiDUorg/weidu/releases ) and copy weidu and weinstall to `/usr/bin`. Following that, open a terminal, `cd` to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run `weinstall setup-k9quicksave` in your game folder. Then run `wine bgmain.exe` (or `wine baldur.exe` for EE games), and start playing.


# Note for Complete Un-installation
  ---------------------------------
In addition to the methods above for removing individual components, you can completely un-install the mod using `setup-k9quicksave --uninstall` at the command line to remove all components without wading through prompts.



IV. Components
==============

The installer groups numbers of Quick Save slots to be installed by games, letting the player decide how many slots he/she wants to install.  
Be sure you are installing the right component of the mod for your version of the game. If you do not have Siege of Dragonspear installed then do not install the "SoD" component. Similarly, if you have Siege of Dragonspear installed then be sure to not install anything in this mod that has to do with the non-SoD components.
The installer includes the following components. The number of each is the component `DESIGNATED` number which gives it a fixed install position, lets other components detect it and allows automated installers to specify component choices.

# [11-14] Quick Slots for BGEE**  
  - [11] Install 1 Quick Save Slot
  - [12] Install 2 Quick Save Slots
  - [13] Install 3 Quick Save Slots
  - [14] Restore 4 Quick Save Slots


# [21-24] Quick Slots for SoD**  
  - [21] Install 1 Quick Save Slot
  - [22] Install 2 Quick Save Slots
  - [23] Install 3 Quick Save Slots
  - [24] Restore 4 Quick Save Slots


# [31-34] Quick Slots for BG2EE**  
  - [31] Install 1 Quick Save Slot
  - [32] Install 2 Quick Save Slots
  - [33] Install 3 Quick Save Slots
  - [34] Restore 4 Quick Save Slots


# [41-44] Quick Slots for PSTEE**  
  - [41] Install 1 Quick Save Slot
  - [42] Install 2 Quick Save Slots
  - [43] Install 3 Quick Save Slots
  - [44] Restore 4 Quick Save Slots


# [51-54] Quick Slots for IWDEE**  
  - [51] Install 1 Quick Save Slot
  - [52] Install 2 Quick Save Slots
  - [53] Install 3 Quick Save Slots
  - [54] Restore 4 Quick Save Slots



V. Credits and Acknowledgements
===============================

# Author: yellow hat elminster  

# Copyrights Information

The Quick Save Slots Tweaks mod is not developed, supported, or endorsed by BioWare™ or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by yellow hat elminster, based on material from the game Baldur's Gate and its expansion.
All mod content is © yellow hat elminster.
Baldur's Gate, Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal © TSR, Inc. The BioWare Infinity Engine is © BioWare Corp. All other trademarks and copyrights are property of their respective owners.

This mod was created to be freely enjoyed by all Baldur's Gate players, and its content is free of rights. Please note that any and all redistribution and/or hosting of this mod is prohibited without permission from the authors.

The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
Be kind to your fellow players and modders. Don't do either.



VI. Version History
===================

# Version 1.6 (December 7, 2020)
  ------------------------------
- Added "k9quicksave.ini" metadata file to support AL|EN's "Project Infinity".
- Renamed "setup-k9Quicksave.tp2" -> "k9quicksave.tp2" to support AL|EN's "Project Infinity".
- Added Modmerge check for SoD games.
- Added components `DESIGNATED` numbers and `LABELS`.
- Fine tuned `REQUIRE_PREDICATE` conditions to avoid installing the mod in inaccurate games.
- Grouped games components into `SUBCOMPONENTS` to support AL|EN's "Project Infinity".
- Added French translation (thanks Gwendolyne).
- Added "k9quicksave-readme.txt" file.
- Lower cased files.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Updated WeiDU installer to v247.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

# Version 1.5 (September 10, 2018)
- Updated to work with IWDEE.

# Version 1.4 (November 28, 2017)
- Updated the TP2 file to make installation easier.

# Version 1.3 (April 12, 2017)
- Made it compatible with PSTEE.

# Version 1.2 (December 25, 2016)
- Added support for having different numbers of quick slots.
- Made the mod a WeiDU mod.

# Version 1.1 (April 1, 2016)
- Added non SoD BGEE support.

# Version 1.0 (March 31, 2016)
- Initial release.
