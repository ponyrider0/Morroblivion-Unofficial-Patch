Faction Fixes: Removes the +100 to factMorrowind and noLore faction relation hack to allow for NPC follower companions to attack other NPCs in Morrowind.  However, this will cause many NPCs to fight each other, requiring properly fixing the thousands+ NPC records so that their aggression/disposition/faction values are appropriate to prevent in-fighting.

2018-may-factionfixes.esp (incomplete) - 8 NPC records repaired, bandits from the Zainsipilu dungeon.

2018-june-factionfixes.esp (incomplete)- 16 NPC records repaired, mainly Ashlander Outcasts (assigned to mwOutcastsFaction which was defined in the morroblivion unofficial patch).

2018-july-finalfactionfixes.esp (incomplete)- A little over 170 NPC records repaired.  I was in the process of exhaustively reviewing and repairing every Morrowind NPC record (starting with 01001AB6 and going down to 01F8E9A5).  I got to 0126009A (and for some reason a random one-off fix for 012603A1).  That is about 5%, leaving another 95% of NPC records to review and modify for completion of this mod.

-----

2018-aug-meadhall-hotfix.esp (completed) - fixes dialog bug for "one more task" topic, so that speaking to Svenja Snow-Song will advance the Mead Hall Massacre quest.

2018-july-bloodmoon-fixes.esp (completed) - many fixes to quests, items, enchantments, factions, NPC AI related to Bloodmoon expansion, including Bloodmoon main quest, East Empire quest line, and NPC and PC Werewolf transformation, death animation, and attack sounds.

2018-june-morroblivion-unofficial-patch-update.esp (completed) - fixes multiple bugs including (1) Ama Nin is found dead in Berandas, Underground. (2) Tanisie Verethi in Addamasartus is autoscaled instead of using fixed stats. (3) the weaker of the two Ash Ghoul mini-boss types was scaled to +5 PC level instead of just +1 PC level.  the stronger Ash Ghoul mini-boss type is left scaled to +15 PC level. (4) Meet Sul-Matuul quest did not complete properly after speaking to Caius Cosades.  (5) Summon Ancestral Ghost spell rebalanced to better match original Morrowind gameplay balancing. (6) Incorporates the Multi-Skill Trainer Hotfix patches from 2018-July-9 and 2018-July-11.

2018-july-morroblivion-unofficial-patch-updates.esp (completed) - fixes Centurion Spiders records (6 types) so they move closer to original Morrowind speed and not in slow-motion.

DagothSpeedFix.esp (completed) - modifies the 7 named Dagoth mini-bosses so they move at Morrrowind speeds and less like a "Benny Hill Show" chase scene. 

blight_fix.esp (completed) - fixes all Morroblivion Blighted creatures to use the correct Morroblivion Blight disease record rather than the not-a-true-blight-disease "Black Heart Blight" disease from Oblivion.

blizzardfix.esp (completed) - fixes random Blizzard weather effect bug with Morroblivion Overhaul S.T.E.P. guide (must be placed at the end of load order).

mediumrebalance.esp (completed) - re-assigns all the original Morrowind Medium Armors to Oblivion's Light Armor skill rather than splitting them between Light and Heavy Armor.  This helps smooth out the huge gap between Chitin Armor and Glass Armor, giving the players who specialize in Light Armor more easily accessible armor types during the mid-game.

mournhold_gate_patch.esp (?completed?) - allows accessing Mournhold/Tribunal inner city from the Tamriel Rebuilt mainland map.

mwDynamicMapSwitcher.esp (incomplete, will not work until script is finished) - WIP mod to use the "GetFormFromMod" and "GetWorldMapData" OBSE script functions to dynamically modify the WorldMap based on where you are in Vvardenfell/Solstheim/Mainland Morrowind.  This is mainly a pseudocode framework.  I don't know where my proof of concept mod is that I used to verify that this technique works.

mwWeatherRemover.esp (usable but only really intended for testing/debugging) - experimental / debugging mod that does 2 things: (1) replaces all Morroblivion Regions with custom Morroblivion weather effects with vanilla Oblivion equivalent weather effects. (2) Resets all HDR/Fog values in the custom Morroblivion weather effects with values from the equivalent Oblivion weather effect records.  The purpose of this mod was to try to isolate all the weather variables in order to track down and fix the cause of the Morroblivion night-time fog "wall of blackness" effect.

opentouch.esp (completed, but needs changes in spells/enchantments to actually have an effect in game) - changes Oblivion's "Open" magic effect spell record to allow for touch-based "Open" spells as seen in Morrowind.

-----------------------

Mods requiring OBME and unofficial-patch-magic-addon:

2018-may-morroblivion-unofficial-patch-magic-addon-update.esp (completed) - (1) bug-fixes and rebalances several slowfall and levitate enchantments, spells and potions; some had 0 duration.  (2) restores missing enchantments to Crying Ring, Ring of Tears and Wooden Staff of War.  (3) Recreates the "Blind" magic effect and restores the original Morrowind Blind-based spells to use this magic effect.

conjurationrebalance.esp (?completed?) - rebalances Bound Weapon/Armor spells: (1) creates a separate branch of spells for Morroblivion that is independent (does not change) vanilla Oblivion bound-weapon/armor spells. (2) rebalances the Morroblivion-specific spells so they work closer to the original Morrowind gameplay mechanics, i.e. all bound weapon/armor spell-types are available to low level characters but just have high magicka costs. (3) bound spells now use the Morrowind-type weapon/armor models rather than the generic-looking Oblivion equivalent.

summonrebalance.esp (incomplete, but usable) - WIP, fix all Morroblivion summon creature spells to behave more closely to how they did in Morrowind.  Only the Ancestral Ghost is completed.  It now functions like it did in Morrowind: a tank creature that is immune to normal weapons, disease, poison and frost attacks but vulnerable to fire, lightning and enchanted weapons.