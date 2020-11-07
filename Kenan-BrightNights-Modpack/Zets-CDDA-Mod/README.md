# Zetsukaze's CDDA Tweaks!
Minor tweaks to make the game more to my liking, some of the changes are OP, but this is a play your way game!

# Usage Guide
1. Unzip the downloaded file and copy the mod folder into `<CDDAInstallationFolder>\data\mods`
2. For mods that you do not play with, remove the dependency from [modinfo.json](modinfo.json)
3. Remove the related files of the disabled mods
4. Enable in CDDA `Zetsukaze's CDDA Tweaks` and enjoy the variety of hairs, eyes and skins!

For example, if you do not play with [Cataclysm++](https://github.com/Noctifer-de-Mortem/nocts_cata_mod), then remove `Cata++` from [modinfo.json](modinfo.json) and the `cata++` JSON files.

# List of Changes
* [Base Game](#base-game)
  * [Tool Armor](#tool-armor)
  * [Vehicle Parts](#vehicle-parts)
  * [Comestibles](#comestibles)
* [Blazemod aka Vehicle Additions Pack](#blazemod)
  * [Vehicle Parts](#vehicle-parts-1)
* [Cataclysm++](#cataclysm)
  * [Armor](#armor)
  * [Vehicle Parts](#vehicle-parts-2)
* [Advanced Gear](#advanced-gear)
  * [Equipment](#equipment)
  * [Vehicle Parts](#vehicle-parts-3)

## Base Game
### Armor
##### Ankle Sheathe
Annoyed that really small items can't be kept in this sheathe? Now it can!
* Minimum volume 0

### Tool Armor
##### Survivor Utility Belt
This is a survivor's utility belt, why wouldn't a survivor add belt loops to keep tools, as well as larger knives?
* Added the ability to holster tools
* Added the ability to keep up to 3 items
* Changed the storage volume `Min: 0L - Max: 3L`

### Vehicle Parts
##### Minifreezer
Yeah yeah, mini I know, but come on, I have stacks of meat I need to freeze!
* Increased the storage volume to `350L` (Same as DC Fridge from Cata++)
* Added the `LOCKABLE_CARGO` flag

##### Minifridge
* Added the `LOCKABLE_CARGO` flag

##### Internal Boom Crane
* Added the `FOLDABLE` flag

### Comestibles
##### Prepper pemmican
* No more rot!

## Blazemod
### Vehicle Parts
##### Cargo dimensions!!!
I added the ability to install cargo lock sets, because who wants those grubby NPC paws on your sweet loot? Also, fold it up and carry around your own pocket dimension!
* Added the `LOCKABLE_CARGO` flag
* Added the `FOLDABLE` flag

##### Boreal dimension
Hoho, a fridge cargo dimension.

##### Gelidus dimension
Aaaaand a freezer one! :snowman:

## Cataclysm++
### Armor
##### Survivor's Archer Backpack
A backpack and a quiver all rolled into one! Of course I want to carry more loot :smirk:
* Increased the storage volume to `25L`
* Decreased the warmth to 0. Who wants a sweaty back?

##### Survivor's Scout Suit & Survivor's Armored Scout Suit
* Decreased the warmth to 25. Way too much warmth on these things.

### Vehicle Parts
##### DC Fridge
* Added the `LOCKABLE_CARGO` flag

##### Survivor's Station
* Added the `LOCKABLE_CARGO` flag

## Advanced Gear
### Equipment
##### Nanotech 'mini-shoggoth' storage
* Added a holster action because it has pseudopods to help you hold things! :octopus:
* Changed the layering to `SKINTIGHT` as I imagine it supporting your body like an exoskeleton, explaining why it allows you to carry more weight

##### Nanotech liquid compressor
* Removed unnecessary flags `RIGID` and `WATERTIGHT` (Removes it from `a`ctivate menu)

##### Small nanotech liquid compressor
* Big isn't always better!

##### Nanosuit
* Changed the layering to `OUTER`, kind of like an Iron Man suit!

### Vehicle Parts
##### Nanotech 'shoggoth' storage node
* Added the `LOCKABLE_CARGO` flag

##### Nanotech crafting node
* Added the `LOCKABLE_CARGO` flag
* Changed the look to match the survivor's station added by Cata++ as there isn't a tile yet :anguished:

# My CDDA Mods
[Zetsukaze's Hair Extensions](https://github.com/Zetsukaze/Zets-Hair-Extensions)

[Zetsukaze's CDDA Tweaks](https://github.com/Zetsukaze/Zets-CDDA-Tweaks)
