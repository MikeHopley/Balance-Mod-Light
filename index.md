# Balance Mod Light -- IN PROGRESS, DOWNLOAD NOT YET AVAILABLE

[Twinge’s Balance Mod](http://www.it-is-law.com/ftl-balance/index.php?title=Main_Page) is a great mod for FTL. In the words of the author, its goal is “to improve the overall game experience by fixing balance issues throughout the game and by adding more interesting decisions”.

Balance Mod *Light* is my custom version of Twinge’s Balance Mod. It reverts a number of changes, giving an experience that is closer to vanilla.


## Installation and versions

This is not a standalone mod. In Slipstream Mod Manager, you need both mods enabled, and Balance Mod Light must be loaded **after** Twinge’s Balance Mod.

As the audience for this mod is small (just me?), I’ll keep versioning simple, and I won’t maintain a changelog. The documentation here will always refer to the latest version, but old versions will remain available for download:

| Balance Mod Light version | Recommended version of Twinge’s Balance Mod |
|:-------------------------:|:-------------------------------------------:|
| 1.0                      :|: 3.6                                       :|


## Motivation

### Why Balance Mod?

What I want from Balance Mod is a more enjoyable, varied, and nuanced version of FTL, which feels like the same game and has the same difficulty or slightly harder.

Balance Mod does a great job of making trash items more usable, often just by reducing their cost; importantly, this also reduces sale value.

Increased Flak 1 and Halberd rarity means they carry fewer runs. Increased hacking costs, and removal of [the bypass](https://www.youtube.com/watch?v=vKZXUAaZSCQ&t=37s), make hacking a less complete “I win” button; hacking shields is too expensive sometimes, so saving scrap by hacking evasion is a real choice.

Balance Mod also applies polish, care, and craftsmanship. I appreciate the small details.


### Why Balance Mod *Light*?

What I **don’t** want from Balance Mod are changes designed to make the game less harsh or reduce the effect of <abbr title="Random Number Generation">RNG</abbr>.

It’s easy to overstate the influence of these changes. Nevertheless, reverting them makes me feel better. When I’m doing a win streak, I want to feel sure I’ve earned it.

This mod was prompted by some changes in Balance Mod 3.6, notably reducing the missile count of several enemies from 10 to 6. When an endgame Auto-scout runs out of ammo after firing twin Letos three times, I feel there has been too much meddling.


## Original changes

Hardly any. Three of my graphical changes are already incorporated into Balance Mod (Hull Beam and Beam Drone 2 fixes, and the Heavy Ion Stunner graphic).

I fixed a graphical glitch with the reactor bar, when using Zoltan C.

I fixed the Rebel Defector event, so you can never tell whether it’s a trap.


## Changes from Balance Mod

Unless otherwise noted, every change is a reversion to vanilla behaviour.


### Sector 1

Auto-assaults can appear in sector 1.
<p class="rationale">Excluding an entire class of ships, just to help Stealth B and C, seems overkill.</p>

The Rebel Shield hack event can appear in sector 1, cannot appear in Rebel sectors, and halves the shield level (rounds down unfavourably).
<p class="rationale">Yes, the event is utter RNG trash. But that’s part of variety and I like having a scare from time to time. Rebel Sectors on the other hand don’t need a nerf.*


### Player ships

Federation C has Emergency Respirators, instead of Zoltan Shield Bypass.
<p class="rationale">ZSB is a rather large change to early matchups for this ship. It’s also the only ship where Respirators are actually useful.

Stealth B cloaking room is below sensors.
<p class="rationale">Moving the cloaking room above sensors was a pure anti-RNG change, specifically for Mini Beam and Beam Drone 2. It made the combination of repairs, <50% venting, sensor dashes, and power-stealing awkward; and also made it harder to judge whether enemy drones were targeting a critical room.*


### Enemy ships

[TO DO] Enemy ship missile stocks are returned to vanilla amounts.
<p class="rationale">Reducing the stock of missiles on several ships from 10 to 6 is a significant anti-RNG change.*

[TO DO] Lanius Scout and Federation Bomber names are restored. [CHECK OTHERS]
<p class="rationale">the name changes were a consequence of the missile stock changes.*

[TO DO] Lanius Bombers have their system strength returned to vanilla values.
*Lanius Bombers are scary. I like that.*

[TO DO, and check BM change] Rock ships’ maximum cloaking is returned to level 3.
<p class="rationale">Long cloaks and missiles are rough, but that’s part of the game.*

[TO DO] Zoltan Fighters (and similar?) hull is returned to 7 (from 6)
<p class="rationale">This change seemed unnecessary. It could cause Stealth B rather silly problems, as this enemy can run at 4 hull (avoidable by hitting two systems, but still...).*


### Augments

Advanced FTL Navigation is reinstated. Its cost is reduced from 50 (vanilla) to 20.
<p class="rationale">It has occasional use for diving and a fun blue option. Make it cheap so at least you might keep a free one.*

Hacking Stun is reinstated. Its cost is reduced from 60 (vanilla) to 20.
<p class="rationale">Although rarely useful, it’s fun sometimes. Make it cheap so at least you might keep a free one.*

Long-Ranged Scanners cost is reduced from 50 to 40 (vanilla cost is 30).
<p class="rationale">This item is slightly overrated. At 30 scrap it’s great value, although not quite the auto-buy people think. At 50 scrap I’m almost never buying it. 40 scrap means I will buy it sometimes. Note that LRS blue options are slightly weaker in Balance Mod.*


### Weapons

Flak 1 radius is returned to 42 (from 49).
<p class="rationale">Inaccurate flak mostly harms enemies more than the player; flak and Swarm are the only enemy weapons that can land multiple shots in the same room. Reduced Flak 1 accuracy makes Flak 2 (55 radius) less distinct.*

Adv. Flak radius is returned to 40 (from 45), and charge time to 8 (from 9).
<p class="rationale">The changes are ineffective at nerfing Lanius B, and it’s fun to have the weapon be more distinct.*

Halberd Beam charge time is returned to 17 seconds (from 18).
<p class="rationale">Slower Halberds mostly harm enemy salvo timings, not the player. I can’t imagine declining a Halberd purchase due to a +1 second charge time. The 3-power usage is enough to separate Halberd from Pike and Hull Beams.*

Burst Laser 3 charge time is returned to 19 seconds (from 18).
<p class="rationale">Honestly, I just think it’s cool that you can cloak two unmanned volleys in a row. I’m only using this weapon when desperate anyway (or with a pre-igniter), so -1 second charge is not going to change decisions.*

Hull Laser 2 speed is returned to 90 (from 75)
<p class="rationale">I can time my weapons, it’s not that hard. The faster speed gives this weapon just a touch more personality.*
