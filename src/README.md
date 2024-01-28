# SR_Slow_Burners {{ ver }}

The Slow Burners is a [SupplyRaid](https://h3vr.thunderstore.io/package/Packer/SupplyRaid/) faction that works well with slow-starting characters who focus on scavenging and improvisational play. Over 4 rounds, they progress from pistol-wielding civilians to a well-equipped and armoured force.

If you have feedback about this faction, I'm `@desi4175` in the modding Discord.



# Managing difficulty

I designed the Slow Burners to be a little pressing on small maps like SR Downtown, when [HardcoreSosigAI](https://h3vr.thunderstore.io/package/NGA/HardcoreSosigAI/) is installed and all of the SupplyRaid settings are kept at default. You can adjust the enemy numbers up or down using the "Max Defender Enemies" and "Max Squad Enemies" settings.



# Play tips

- All enemies respawn infinitely, and you can get overwhelmed by respawning enemies if you can't clear them consistently. The most important factor in this is armour penetration. If you don't have appropriate weapons, try picking up and using the sosiggun versions of full-power rifles (Mk14 EBR, PSG1, Dragunov).

- Despite the infinite respawns, it is possible to capture a point if all the defenders are dead at the same time. Free-roaming enemy squads don't count towards this.

- Carry and use smoke grenades to obscure dangerous sightlines and force sosigs to get closer.

- Shield-carrying sosigs are fatal in cramped indoor spaces.
  


# Known issues

- I don't have sniper sosigs enabled because it seems to make SupplyRaid end the levels early (like I kill 3 squad sosigs somewhere and the level is completed) or just bug out.



# Recommended mods

- [HardcoreSosigAI](https://h3vr.thunderstore.io/package/NGA/HardcoreSosigAI/) speeds up sosigs' reaction times. Th e Slow Burners were balanced with this mod in mind.
- [PlayerFootsteps](https://h3vr.thunderstore.io/package/Kodeman/PlayerFootsteps/) lets sosigs hear you when you're running nearby (or not hear you when you're walking slowly).



# Future wishlist

- I'll make the appearance of the Slow Burners more consistent when SupplyRaid supports custom sosigs. Currently, I have had to use different kinds of built-in sosigs to balance their armour and weaponry across levels.



# Changelog

## v3.1.0 (2024-01-26)

- Enemy spawn probability is now weighted based on their weapons and armour. Enemies with better armour and weapons spawn less often. This change should generally make the Slow Burners easier.
	- Previously, only the sosigs in the final level were weighted.


## v3.0.0 (2024-01-23)

- Changes to progression:
	- Removed Level 2 entirely.
		- It didn't differentiate itself well because it used the same enemies as Level 1, just with rifles and SMGs.
		- I also wanted all of the levels to fit within the default 5-round setting of SupplyRaid, so that players would be able to extract at the start of the 5th Level.

- Changes to sosigs:
	- Changed supply point guards to be drawn from the pool of sosigs that will show up as regular enemies in the next Level. Gives you a glimpse at what's coming.

- Rebalanced enemy numbers using default SR settings (12 defender sosigs alive at one time, 8 squad sosigs alive at one time).


## v2.0.0 (2024-01-16)

- Removed the melee sosig from the random squads at Level 1. It was too annoying getting a melee sosigweapon instead of a useful sosiggun.
- Improved Level 5 enemies from Light and Medium armour to Medium and Heavy armour. Light armour was still too easy because you just do what you've been doing all this time: headshots.
- Set the supply point guards to respawn infinitely. It was previously only the patrols that did so.
	- In general, this makes a Slow Burners session more interesting because supply point guards respawn to attack you while you're trying to cap the point.
	- This also means you encounter more enemies overall which helps with drop rates and applies pressure on Limited Ammo runs.
	- For [Sosiggun Soren](https://h3vr.thunderstore.io/package/Desi/SR_Sosiggun_Soren/), this further incentivises the use of the plentiful sosigguns to conserve ammo. 
- Respawn timers adjusted a lot, from [180, 120, 90, 60, 45] to [16, 15, 14, 13, 12].
	


## v1.1.0 (2024-01-11)

- Removed or reduced the spawning of LMG-wielding sosigs across all levels. LMGs, especially the M60, were just too good to the point where it became more viable to use the LMG than to use your own guns, especially to defeat the stronger body armour of sosigs from Level 4 onwards. It was even worse when the LMGs could be reloaded in Spawnlocked mode.
	- Levels 1 & 2: There are not (and never were) any sosiggun LMGs at these levels.
	- Level 3: Jungle Riflewieners no longer spawn; no LMGs at this level now.
	- Level 4: There are not (and never were) any sosiggun LMGs at this level.
	- Level 5/Endless: You only start enountering LMGs here. A Tier 5 Heavy Operator armed with an LMG can spawn as a supply point guard. There's about a 4% chance of spawning at least one in every level. You'll have to earn the LMG by taking down a very well-armoured enemy.


## v1.0.1 (2024-01-10)

- Forgot to update the package description.


## v1.0.0 (2024-01-10)

- Initial release.
