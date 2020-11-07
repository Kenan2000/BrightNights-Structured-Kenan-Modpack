# MST_Extra_Mod

A mod for Cataclysm: Dark Days Ahead, the official followup to the now-obsolete More Survival Tools mod formerly present in the repo. Adds assorted additional content and changes that improve quality of life when playing innawoods, adding various interesting ideas variously thought up or suggested to me.

The following list of content is not only incomplete and unlikely to be out of date, it's also specifically only what MST Extra adds that was not originally present in More Survival Tools. All content that was part of the original MST at the time of its obsolescence is also now a part of this mod.

Recipe Additions/Overrides for Existing Items:
* Added the option of making waterskins using sealed stomachs. The idea is it isn't that complicated to add a strap to an already usable water container.
* Added overrides for some of the most basic leather and fur recipes, allowing the use of cured pelts/hides. The idea is that rawhide is still usable for some limited applications.
* Added both an override and an alternative recipe for boat oars, changing the material demand and making it non-reversible. The alternative version allows use of cordage instead of nails, and cutting instead of hammering.
* The `adhesive` crafting requirement has been overridden to allow pitch (see below) as an option. This does not yet make it an option for all recipes as not all have been converted to use the requirements system, but this should improve over time.
* Added a recipe for carving a spile out of bone. Hand drill will still be required, and I might plan to add a flint drill in the future.
* Use of pitch in the waterproofing crafting requirement.
* A recipe for leaching saltpeter out of bird droppings.
* Certain recipes have been made `BLIND_EASY`.
* Overrides allowing bologna, dog food, and cat food to use meat scraps as an option.
* Re-added a recipe for the stone spear. There, it's book-learn only and only works with sharp rocks or ceramic shards. It wasn't that difficult compared to removing the recipe entirely.

Item Edits:
* Set charcoal water purifier to count as a substitute for electronic water purifiers. The `use_action` works the same consistently, so why shouldn't they be used the same in recipes?

New Clothing:
* Pack baskets, allowing a basic storage item to be crafted without access to cloth or leather.
* Birchbark sheathes, something that might be useful for players innawoods, similar to how birchbark quivers are an option.
* Birchbark canteens, sealed with pitch or similar materials.
* Leather and fur arm and leg wraps, as a supplement to other basic wrap recipes. As with the overrides, cured hides/pelts can be used as well.

Medical/Chemistry Items:
* Willowbark tea. Way back when I PR'd willow bark and a recipe to make aspirin from them, I had the idea of using them directly as they've historically been used. My initial proposed implementation had some flaws in it, and at the time I simply axed it rather than trying to fix the idea. Being less efficient than processing into aspirin, yet still being useful when taken individually, this should fit the intended purpose.
* Tar oil, made from birchbark or pine boughs. Represents both birch and pine oil, which have antiseptic properties. Less effective than thyme oil or disinfectant for gameplay reasons, as I do not have any data on whether birch or pine oil are any less effective compared to other essential oils with antiseptic properties. Note that "oil" does not require the addition of cooking oil. I haven't been able to find whether thyme oil and mugwort oil is actually made in a realistic manner, but birch/pine oil don't involve cooking oil. :v
* Pitch, made by reducing tar oil to a more solid state. Usable as an adhesive for some recipes as stated above.
* Garlic oil, using the `WEAK_ANTIBIOTIC` use action. As with standard weak antibiotic, it's best used to to prevent a bite from turning infected if you lack any other antiseptic, but is better than nothing if you have a full-blown infection.
* Makeshift poultices, with two separate methods of crafting based on historical methods (crushed dry herbs, versus wet materials with absorbent binder). Main purpose is a way to make a healing item using some of the antibacterial items in the game that aren't otherwise usable for this, but it also has a secondary niche as a "can treat bleeding and bites, but not as well as a specialized item" function.

New Food Items:
* Ability to make basic roasted garlic and chili peppers, due to my experience finding these to be two of the most underused crops in the game.
* Garlic bread, for similar reasons as above.

New Tools/Related Items:
* A makeshift hoe with a stone blade. Recipe is comparable to that of the stone adze.
* Clay jars that can be used for some of the most basic canning recipes, in reference to the Appert process.

Vehicles and Parts:
* A makeshift sled with associated parts, that can be either assembled or constructed as a folding-vehicle item. The idea is one I had a long time ago, before I even released More Survival Tools. It was a bit of an annoyance to make and balance the parts, so I ended up scrapping it back in the day.
* The frame is notable mainly for being much less of a drain on rope than light wooden frames, which is by far the biggest problem with simply making a vanilla travois. The result is more fragile, however.
* The basket does not store as much as a wooden box, travois, etc. But it uses different resources, straw or birchbark primarily.
* Finally, the sled runners serve a niche that is effectively unique. It functions as a source of a stable single-tile wheelbase that does not require access to welding, and is also the only stable "wheel" to lack steering ability. To avoid illogical events like slapping foot pedals on a sled, its stats make it inadequate to accelerate a vehicle. Instead its primary purpose is for dragging a pulk or other storage vehicle.
* Log frames that can be made with fire, cutting, and an adze. Usable for outrigging, rafts, etc. The frame itself can float, rather than requiring separate boat boards.
* A log canoe that can be made from several logs, representing the dugout style. Made as a single item, the resulting vehicle can be packed up to carry if it you have the strength to.

Construction:
* Beehives. This was an idea that came up during the Utterly Mad succession game, and works in a somewhat hacky way. No use of the bees field for you, because holy crap bees are awful about homing in on players and never dissipating. Producing honeycombs still takes time and some established initial resources to begin with, but the result should be worth it.
* An option to convert window frames into door frames, as that has been my number one most common cause of roof collapses that shouldn't be happening anyway.
* Constructable version of charcoal water purifiers.
* Leather version of door curtains.
* Makeshift stills, based off a technique looked up that uses sand or earth to insulate glass containers for distillation.
* Pulley lifters that can be constructed indoors, to provide a source of lifting quality for more advanced bases in isolated areas.
* Wooden windbreaks, simple barricades mainly to block wind for basic shelters.
* Version of the tarp lean-to using the leather tarp.

Other:
* Escaped livestock now start to filter into the standard forest monstertgroup as time goes on, remaining relatively rare but allowing the player some shot at finding livestock to tame.

