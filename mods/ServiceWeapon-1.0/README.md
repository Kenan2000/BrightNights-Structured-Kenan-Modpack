# What

Service Weapon (`service_weapon`) is a [*Cataclysm: Dark Days Ahead*](http://github.com/cleverRaven/Cataclysm-DDA) mod that adds the Service Weapon morphing firearm from the game *Control*.

It depends on the base game (`dda`) and Aftershock (`aftershock`).

# Why

...it's the Service Weapon.

# Using the Service Weapon

## Finding It

For the sake of balance, it spawns exceedingly rarely in Aftershock's weapon-testing facilities. When you find it, you have to activate it for it to work. After that, you'll be able to change it into its different forms from the "Use Item" menu.

## Changing It

Changing forms is rather tedious because *Cataclysm* has no way to "multi-transform" items – i.e., allow player to choose which state they want it to transform into. Right now, you have to cycle through the forms until you arrive at the one you want.

All forms are available at the start.

Aside from the five forms from the game, I took it upon myself to add one more, called Bright: a medium-range laser weapon. It seemed appropriate for the setting.

## Loading It

Unlike in *Control*, this version of the Service Weapon runs on light batteries. This usually offers plenty of ammunition, especially with disposable batteries, because one shot from any form takes one charge off the battery. The fact that it spawns so rarely should make up for the ease of provisioning.

Before settling on using batteries, I'd considered:

* using UPS
  * something that would generally make sense
  * something that would theoretically be available by the time you start raiding laboratories
  * with that in mind, I felt like batteries offer a decent trade-off between "limited" ammunition and the need to wait (in this case – for the reload to finish)
* using `ARTC_TIME`
  * something that would be ideal for the Service Weapon, within the limitations of the game
  * except for the fact that it apparently takes a long time to reload, something that doesn't fit in with the idea

The perfect solution would be JSONized auto-recharge effect, but we're still some ways away from it: the enchantment JSOnization project is underway, but its estimates of completion are unknown.

# Potential Development

## Mods

*Control* featured a mod system for both the player and the Service Weapon. Replicating the latter would be an interesting endeavor that I have no time for. If you feel like adding this kind of functionality, feel free to submit a PR to the matter.

The thing to keep in mind about gunmods and the Service Weapon is that *Cataclysm* naturally lacks the same crafting infrastructure that made *Control*'s mod crafting interesting: namely, the conceptual resources and a place to use them. Adding such resources would be an equally-interesting undertaking, with its own set of challenges.

## Conceptual Resources

One issue I can foresee with this kind of materials is that they're only ever going to be used with this one item. While an interesting system, it feels foul to waste it by limiting its scope this much.

An alternative, less-wasteful solution would be to implement much more than the Service Weapon's mod system: it would be to use the same resources to provide a unique set of items or character improvements that could be applied as "spells" or "enchantments", but with a more sci-fi flair to them.

### Gaining Conceptual Resources

On a pragmatic level, conceptual resources could be made weightless and volumeless, and their gain could be set up through the auto-pickup system.

The resources could be added to the monsters' drops, where Source spawns from every kill (thus could be added to as generalized an item group as possible), and specific resources – significantly more rarely, and perhaps distinct by the type of the enemy.

The latter detail could lead to interesting trade-off for the player: those who dislike playing with giant insects would lose access to a particular resources, thus being unable to craft a particular type of mods. Choosing to have it all would imply choosing to face opponents the player does not like to face, forcing them to learn, adapt, and overcome their weaknesses.

In a way, the player would then get more by *becoming* more.

## Expanded System of Conceptual Crafting

This sort of a system feels very much in line with *Cataclysm*'s more high-level lore. Alternative dimensions filled with terrifying creatures and powers beyond humanity's control, unknown physics of realities alien to ours... Something like the Hiss or conceptual crafting might well find its way into the game's world.

Creating such a system would be no small task, but the result of it would be a framework for what may be the pinnacle of human enhancement: bending reality itself in order to improve one's stance against the horrors of the metacosmos. *Cataclysm* prefers to settle for a tone less optimistic than that, but I've always enjoyed my bit of transhumanism – more so if it comes from something quite so powerful.

### Approaches to Conceptual Modding

On a JSON level, gaining such mods could be handled via the trait system, perhaps by hijacking the bionics system or mutations.

This would render the mods semi-permanent, as removing them would require either specialized tools or random removals with purifier-like injections, which is not ideal. After all, the point of transhumanism is not to gamble but to have a choice of ways in which to grow – something *Control* utilized on a fundamental level.

Alternatvely, mods could be made into wearable items with either `artifact_data` or `relic_data`. This risks creating a bit of clutter, both in the inventory and the player's mind.

Ideally, handling an entirely-new level of character modding would require a dedicated part of the engine to deal with it. This is inaccessible to JSON-based mods and would require some work with C++. Still having access to Lua would've made this significantly easy to make.

## Extending the Service Weapon

The Service Weapon is a personal gun of extensive potential. It could have dozens of new forms added to it, making it the ultimate gun the character would ever need. Bright – the laser pistol form – was but one expression of that potential.

You have my blessing to create your own forms of the Service Weapon and host them as separate mods dependent on this one. Alternatively, submit a PR with the new form in a separate file, like Bright is.

The player must be given a choice to play with the forms of the Service Weapon they feel belong to the idea, and discard those that don't. It's why Bright and other new forms should remain separate from the core `service_weapon.json`: to provide players with a measure of control that they deserve.

## Content Pack

The idea of introducing *Control* or *Control*-derived concepts could be extended into its own content pack. Oldest House could added, and so can the Hiss and its enemies... or something that doesn't infringe upon Remedy's copyright.

You have my blessing to use this mod or any of the ideas expressed so far in your own creations.

# License

MIT