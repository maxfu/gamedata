STALKER Complete 2009 by artistpavel
----------------------------------------
Version 1.4.4

========================================
::::::::::: INSTALLATION :::::::::::::::
========================================


Designed and tested for STALKER version 1.0005 (also works with v1.0006, the multiplayer patch). Please update your game, otherwise you will see black screen upon startup.

To check if your game is updated, check the lower left corner of the main menu screen, it should say 'ver. 1.0005' (or 1.0006). If nothing is there the game is not updated.

If you bought this game on direct2drive.com, you need a 'digital distribution' patch called stk-dd-10005.exe, available here: http://www.filefront.com/9029406/S.T.A.L.K.E.R.---v1.0005-Patch-Download/
Starting a new game is required! The game engine can only read mod changes when you create a new game!

Steam version is updated to 1.0005 automatically.

Starting a new game is required! The game engine can only read all mod changes when you create a new game!



========================================
.exe installer:
========================================

Launch .exe and follow instructions.

Compatibility:

 - Retail DVD versions of  S.T.A.L.K.E.R.: Shadow of Chernobyl game with 1.0005 (or 1.0006) patch
 - Direct2Drive digital copy with Digital Distribution 1.0005 patch
 - Steam (if using installer, launch & exit the game at least once, check for version 1.0005 and install the mod)  


Important: start a new game again after mod is installed!



========================================
Manual:
========================================

1. In the main STALKER directory (by default it's "C:\Program Files\THQ\S.T.A.L.K.E.R. - Shadow of Chernobyl", and for Steam users "Steam\SteamApps\Common\Stalker shadow of Chernobyl"), locate file "fsgame.ltx", open with Notepad and change both variables in this line to "true":


$game_data$ = true | true | $fs_root$ | gamedata\


2. Copy "gamedata" folder from the SC2009 archive to main STALKER directory (the whole folder, not just its content).


3. In the "user.ltx" file make changes to these lines:


cam_inert 0.1

r2_sun_near 20 
r2_sun_near_border 1

r2_gloss_factor 2.5


- XP users:
"C:\Documents and Settings\All Users\Shared Documents\stalker-shoc\user.ltx"

- Vista/Win7 users:
"C:\Users\Public\Documents\stalker-shoc\user.ltx"

- Steam users, follow the XP/ Vista/Win7 instructions, you have a dummy "user.ltx" in “_appdata_” that does absolutely nothing, make sure you find the correct "user.ltx" in folders specified above.


4. Install Weapon Scopes for your monitor (default 16:10):

Copy the files from the following directories according to your monitors aspect ratio:

\gamedata\textures\wpn\16x10 scopes
\gamedata\textures\wpn\16x9 scopes
\gamedata\textures\wpn\4x3 scopes

and paste to this directory overwriting all files:

\gamedata\textures\wpn



Uninstall:
----------------------------------------
1. Delete or rename "gamedata"
2. Delete "user.ltx" file to reset everything back to default, the game will create a new one.



----------------------------------------
STALKER Complete 2009 designed and compiled by artistpavel

02 November 2010
artistpavel.com

For latest version visit:
http://artistpavel.blogspot.com/2009/04/stalker-complete-2009.html

or stalkercomplete.com