# GoldenSun-QOL
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

Table of Contents

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

I.) Overview

II.) Adjustments to Over-world Abilities/Quality of Life Updates

c1 Retreat

c2 Avoid

c3 Default Psynergy

c4 Psynergy Items

III.) Known Bugs/Issues

IV.) FAQ

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

I.) Overview

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

This mod implements the Quality-of-Life features used in Dawn of Djinn in a setting that better reflects the original game. For players who wish to experience the original world of Golden Sun with those features.

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

II.) Adjustments to Over-world Abilities/Quality of Life Updates

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

c1 Retreat

Retreat not only warps you to the start of a dungeon or town but now functions similarly to teleport when used on the world map. Using Retreat pulls up the map and you can select any town that you've previously visited to instantly return there. The linearity of Golden Sun doesn't make this as needed as other RPGs, but it does open up some options that would be unreasonable in the original game, such as Retreating back to Imil to restock on Hermes Water.

c2 Avoid

Avoid now behaves as a random encounter toggle rather than a wear off effect. Using it once turns off 100% of random encounters, using it again turns them back on. 

c3 Default Psynergy

Building off the built in Psynergy the Randomizer provided, many utility Psynergy like Growth, Whirlwind, and even Avoid are built right into party members so they have them, regardless of your class. In addition, Psynergy not tied to battle no longer cost Psynergy to use. Though they have different names to distinguish from their battle equivalents. For example in battle Growth still cost Psynergy to use, but outside of battle it is refer to as “Sprout” but otherwise functions the same.

c4 Psynergy Items

Psynergy items also behave differently as well. Often when you first encounter them they won't be items, but rather weapons and armor you can equip to party members to get the effect without wasting an extra item slot. When the equipment becomes out-classed, you can sell it at a shop and a more traditional Psynergy item will appear in any item shop's Artifact section. You can sell and re-buy the items as you please, freeing up inventory space if you're familiar enough with the game to know when you do and don't need them.

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

IV.) Known Bugs/Issues

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

- Occasional visual effects when using Retreat in the over-world. I believe this is a carry-over from the Golden Sun Randomizer and if so, I'm not sure if I have the ability to fix it.

- Avoid can be buggy with it's new implementation. If one saves and quits the game while Avoid is still toggled on, they may have problems turning it back off once they reopen the game. Most consistent solution I've discovered to fixed this from a player's end is to toggle it on and off, transition to a new area, toggle it on and off again. If done correctly, this will make it toggle like normal. As for correcting this problem from the creator side. I'm not sure if this is possible as the Avoid changes were carried over from the Golden Sun Randomizer and I don't have access to the original code. Best measure of avoiding this issue is to make sure it's off before saving the game.
- Toggling Avoid off spits out garbage text. This appears to be a side-effect of editing the text of a Golden Sun 1 Randomizer seed, which was how I was able to implement the QOL features from the randomizer in a vanilla playthrough. Only way I know to fix this is to change what ever text is being pulled into saying what I want it to say. This may be address if I ever come back to this project, however it will come with it's own quirks of changing whatever text is being pulled in it's orginal context as well.

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

V.) FAQ

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

How do I install and play?

1. Download the patch. 

2. Have your copy of Golden Sun for the GBA ready 

-Make sure you use a clean copy, patching something already patched is not recommended. 

3. Use Lunar IPS to patch it to your copy of Golden Sun

What is the difference between the patches?

GSTBS_QoL_P: Prologue and Djinn tutorial left in the game.

GSTBS_QoL_NP: Starts the game off right as Isaac and Garet are leaving Vale, as well as skips the Flint tutorial.

Neither of these patches remove the dialogue, like in Dawn of Djinn V1, however this patch is compatible with the cut-scene skip patch used in Golden Sun 1 speed-runs (Not included). The two can be used in combination to skip the prologue and go through cut-scenes as quickly as possible.
