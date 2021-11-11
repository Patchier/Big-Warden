# Big Warden

January 15th, 2021 - Full Install: ~37GB.

## OVERVIEW

This ReadMe is designed to help you with the last few finishing steps necessary to enjoy Big Warden as I personally enjoy it. 

## GOALS


-  Put the finishing touches on your Big Warden installation

-  Get you playing the game as quickly as possible

## SPECIFICATIONS

- Due to the way .DAZIPs work, you will need to follow a few instructions before you're completely ready. Don't worry, this won't hurt a bit, so long as you're capable of following instructions.

## First off, you will need:

-   A clean, fresh, and LEGAL installation of Dragon Age Origins: Ultimate Edition It DOES require all of the DLC, so Ultimate Edition is likely required.

## Install Dragon Age: Origins Ultimate Edition

- This part is self-explanatory. You'll want to go to the installation of the game, and remove all files present in the install folder (For example, steamapps/common/Dragon Age Origins). 

- Once done, go ahead and re-install it. This ensures that any installs you have will be totally clean, which is important for the next steps. 

- While you're here, run the game once, and choose "Configure". Then, in the Video Settings, choose whichever options you desire. (I maxxed mine out with a 16:9 display, and to skip the intro movies)

- Go to the main menu, check the "Other Campaigns" option, and exit

### If using Steam and, upon loading the game, the "other campaigns" button is darkened, exit the game, navigate to steamapps\common\Dragon Age Ultimate Edition\redist, and run DAOU_UpdateAddinsXML_Steam.exe. This should pull all of your addins into the game. 

Install Big Warden via Wabbajack
-----------------------------------------

1.  Simply open the Wabbajack UI, which can be acquired from here if you don't already have it: <https://www.wabbajack.org/#/>. 

2.  Once you've installed Wabbajack, or if you already have it, open it up and choose "Browse Modlists". 

3.  From there, you will download "Big Warden" by clicking the little down arrow. 

4.  After that, you will choose an installation folder (I recommend something like "D:/Big Warden", substituting D: for any drive available.) This CANNOT be where Wabbajack.exe is located, nor your Dragon Age Origins folder.

5.  Downloads will auto-populate for you, but you can change that location if you so choose. 

6.  From there, just click the "play" button and let it do the rest.

Copy over the LAA Patched EXE AND upscaled cutscenes (all users)
-----------------------------------------------------------------------------------

1. After the installation has completed, navigate to your Big Warden installation folder

2. Open the folder labeled "Game Folder Files"

3. Inside of this folder will be a copy of the Dragon Age: Origins EXE that has been patched to use 4GB of memory. Copy this exe to your Dragon Age Ultimate Edition/bin_ship folder. Overwrite when prompted. 

4. While you're here, also copy over the three folders present here (Addins, Modules, Packages) to your Dragon Age Ultimate Edition installation folder, overwriting when asked. 

5. In your Big Warden installation folder, you will see a folder named "COPY THIS FILE TO DOCUMENTS-BIOWARE-DRAGON AGE-SETTINGS". You will copy the file inside this folder to...well...Documents\BioWare\Dragon Age\Settings. Overwrite when asked.

6. Ditto for the folder named "COPY THIS FILE TO YOUR DRAGON AGE INSTALLATION FOLDER - DATA", except it goes in your DA install location's data folder. Overwrite when asked.

Install the remaining DAZIPs
---------------------------------

1. Upon finishing the Big Warden installation, navigate to steamapps/common/Dragon Age Ultimate Edition/bin_ship

2. Click on the program titled DAUpdater.exe

3. Choose "Select DAZIPs", and navigate to your Big Warden installation folder. 

4. There, inside of Other Necessary DAZips, will be several DAZIPs that you will need to install using the DAUpdater. Simply select them, and they should appear in DAUpdater. Note: You may not be able to do them all at once due to some additions recently. There are also several promotional DAZIPs located in the "Promotional Items" folder which may be installed if you so choose.

5. Select all of the DAZIPs within DAUpdater, and choose "Install Selected".

6. Wait for all of them to read "installed". Afterwards, you may close the program. 

7. See the bottom of this ReadMe for instructions to make Awakening in the OC work for you. Believe me, it's worth it.

# Finishing up Awakening in the OC (Note: GOG users will use GOG Galaxy paths (GOG Galaxy\Games\Dragin Age Origins) and Steam users (steam\steamapps\common\Dragon Age Ultimate Edition) instead of (Game_Install_Location))
--------------------------------------------------------------------------------

1. Find the equivalent of your "(Game_Install_Location)\packages\core_ep1\data" directory.

2. Copy all of the .erf files found there.

3. Find the "Documents\BioWare\Dragon Age\AddIns\gxa_res_to_core\core\data" directory.

4. Paste the copied .erfs into that folder.

5. Find the equivalent of your "(Game_Install_Location)\packages\core_ep1" directory.

6. Copy the texture folder.

7. Paste the copied folder into the "Documents\BioWare\Dragon Age\AddIns\gxa_res_to_core\core" directory.

8. Find the equivalent of your "(Game_Install_Location)\packages\core_ep1\audio\sound" directory.

9. Copy the three vfx_spells files.

1. Paste them into the "Documents\BioWare\Dragon Age\AddIns\gxa_res_to_core\core\audio\sound" directory (create it if it doesn't exist).

12. Find the equivalent of your "(Game_Install_Location)\packages\core_ep1\patch" folder

13. Copy the .erf file found there to the "Documents\BioWare\Dragon Age\AddIns\gxa_res_to_core\core\override" directory.

14. In the "Game Folder Files" folder, you will find three .bat files which fix issues importing DLC items into Awakening. Choose the one associated with which platform you own the game on and run it.

15. Activate the 'Awakening in the OC' Addon via the Downloadable Contents menu in-game once you've launched it later on.

## Starting the game

Once you've finished installing the DAZIPs, Awakening in the OC, and Dragon Age Redesigned, and assuming you followed the order present in this readme, you should have Mod Organizer opened already. If so, simply choose Dragon Age Origins from the dropdown menu in the top right, and click "Play" to begin your adventure. If you DIDN'T follow the order in the readme, then simply open Mod Organizer and do the exact same thing. 

## Mods to be aware of

- Skip the Fade/ Skip Ostagar - These mods do as written, and warrant no further explination. If you would rather not skip these, disable them at the bottom of Mod Organizer.
(NOTE: Some people have had issues when skipping Ostagar where the tutorial attempts to force them to select Alistair when he is not in the party. If you plan to skip Ostagar, be sure to disable tutorials, just in case)

- Awakening in the OC - This is THE big one. This mod pulls in skills, talents, and abilities from Awakening into the base game. It also raises the level cap to 35. An amazing mod that's bound to be fun for everyone.
