# Bright-Nights-Kenan-Mod-Pack
Kenan's personal modpack for **LATEST** Bright Nights versions of CDDA by Coolcthulhu: https://github.com/cataclysmbnteam/Cataclysm-BN/ 

**original modpack creator is Chromosome Kun! - without his help, this would not exist** 

**IF YOU ARE EXPERIENCING ANY BUGS OR ERRORS - EITHER THE FIXES WILL BE RELEASED SOON-ISH OR THE MOD IS WIP**

# Modpack INSTALLATION Guide

1. Download and install latest release of Cataclysm fork by **Coolcthulhu/BroadFlatNails** - [*Bright Nights*](https://github.com/cataclysmbnteam/Cataclysm-BN/releases)
2. Download current modpack by clicking Code - Download ZIP, or clicking [**here**](https://github.com/Kenan2000/Bright-Nights-Kenan-Mod-Pack/archive/master.zip)
3. Unpack contents of the downloaded .zip archive into new folder; results should be looking [**like this**](https://i.imgur.com/UfvpOyV.png)
4. Copy contents of this folder and paste into `cdda/data/mods` directory as shown in the [**picture**](https://i.imgur.com/iDJyZYh.png)
5. Overwrite and replace all the files if you get a prompt
6. Enjoy the mods!

# Modpack UPDATE Guide

1. Remove the contents of the `cdda/data/mods` folder
2. Repeat all steps from the INSTALLATION guide
3. You're all set!

# FAQ:

* Q: Why should I remove manually some specific non-mainlined mods when updating?
  * A: Because sometimes some mod files become obsolete and no longer used, so you won't need them inside your mods folder anymore, so for dealing with these problems you need to delete the mod and fully reinstall it.

* Q: After updating my save file no longer loading!
  * A: It is rare, but will happen when some mod that've been used in your save has new ID and/or name, or you're trying to load the mod that is no longer used/merged with other one. You can fix it by reading `debug.log` to view what's mod should be changed, then go to `cdda\save\world_name\mods.json` and replace target mod ID with the new one, or delete it's entry from this file if there is no replacement. Also, you can read latest commits to see what is happening, if you want

Example commit of mod ID change: [c72f700f2fe35e2e5bd32995917746b47edb428e](https://github.com/Kenan2000/Bright-Nights-Kenan-Mod-Pack/commit/c72f700f2fe35e2e5bd32995917746b47edb428e)

Example commit of mod removal: [603464b7d4ee27430b84f3625cc4644f4510fb53](https://github.com/Kenan2000/Bright-Nights-Kenan-Mod-Pack/commit/603464b7d4ee27430b84f3625cc4644f4510fb53)

* Q: I have some other issues to report!
  * A: Feel free to submit your issue into the [issues tab](https://github.com/Kenan2000/Bright-Nights-Kenan-Mod-Pack/issues).

# Links to the legendary tileset by SomeDeadGuy
Legendary **UndeadPeople** tileset by SomeDeadGuy: https://github.com/SomeDeadGuy/UndeadPeopleTileset

# Links to other cool stuff
1. My HUGE and AWESOME **BL9** mod: https://github.com/Kenan2000/BL9 (included in this modpack)
2. Updated and even more awesome Otopack soundpack maintained by me: https://github.com/Kenan2000/Otopack-Mods-Updates
3. CO.AG MusicPack Redux: https://discourse.cataclysmdda.org/t/musicpack-co-ag-musicpack-redux-11-dec-2019/18992
