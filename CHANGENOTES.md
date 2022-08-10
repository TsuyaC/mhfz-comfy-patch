# 1.0.0

# What is this?

This is a patch based on PewPewDojo's client files that aims to reduce some of the more extreme grinds across the game.
This version primarily targets Raviente, but also includes reduced and reworked numbers for HR5 Exotic armours, aswell as some changed recipes for consistency.

Notice: All numbers are based on averages of materials and rewards. Numbers will still seem high, but can easily be reduced through multiple means.
The game still relies on RNG, numbers will likely not apply to you, as they are just averages from math.

# Installation:

1. Navigate to dat folder of your Frontier folder and make a backup of your current mhfdat.bin if you want (rename it to something like "mhfdat_BACKUP.bin" and keep somewhere)
2. Move "ravi_mhfdat..bin" into the dat folder and rename it to "mhfdat.bin".
3. Replace your mhfo.dll and mhfo--hd.dll with the ones provided. These are needed for some changes (advised to keep a backup of original files aswell).

# Armour Changes:

## Exotics

HR Exotics were far too grindy. Moving them to G-Rank only would be an idea, but for now adjusted upgrade material numbers will do.
- Exotic armours now require around 5-10 fights per piece depending on RNG as well as needing armour spheres.

## Raviente

Ravi armours are the sole source of Determination outside of premium, and originally needed to be refined from GX7 to get a ravi deco.
The most powerful skill in the game by far is Solid Determination, so these armours were meant to require a bit of investment to get.

- All G-Rank Ravi armous have reduced material costs across the board
- Each Ravi, with exception of Extreme, used the same upgrade materials, they no longer do
	- Normal: 	Focus on more common materials
	- Violent:	Balance of materials but need exclusive Blood too
	- Berserk:	Focus on more part breaks and rares
- Ravi gives an average of 30 carves, more with optimal carve route and carving set, numbers were adjustments with this in mind
- You can make about 2-3 decos per 100 evolution levels, less if you use methods to reduce the grind, mentioned below

# Evolution Weapons:

- Evolution Exchange Rates:
	- raised across the board
	- G-Rank Power Gems are removed from the g exchange. These have been replaced with rare materials from Normal/Violent (Violent is best farm for g)
	- Gg Power Gems all increased by ~5x value
	
- Evolution Upgrades:
	- HR2 and HR5 rates remain unchanged, just g is easier to come by from Violent
	- G-Rank scales based off of rarity, increasing by 3,000 per rarity, jumping to 20,000 at final levels
	- Z weapons follow same scaling, without the rarity increases (for consistency), 4,000 to 30,000 at final levels
		- modified some Z weapon recipes, namely Magspike and Tonfa "Glory" paths to include relevant zenith parts for poison
	- At most 100 Berserk Ravi for a G1-Z100 weapon using averages.

- Numbers still seem high, tho there are multiple ways to lessen the grind:
	- Optimal Partbreaks, Gems are based on parts broken per phase, which grant more Great Slaying Points
	- Premium Course. Premium grants flat bonus gems from the rewards after a successful Ravi
	- Extreme Ravi, gives more average gems than Berserk, the averages used were from Berserk

# Bugfixes

- Base Zinogre Switch Axe had broken sharpness pointer resulting in using Francisca's sharpness
	- now has proper sharpness levels

- Conquest Fatalis Gunlance had a broken finesse upgrade level. Attempting to level up to 46 crashed the game.
	- can now upgrade properly
	
- Reverted Upgrade Materials in LR/HR resulted in unobtainable HC material for a navi mission and Gou armour upgrades
	- Torid Greaves now require "Beast Wyvern Top Tail" in place of the HC Carve from HR2 Abiorugu ("Abiorugu Evil Bone")

	
# Additional Comments

- Reasoning behind this Patch:
	- Monster should be required to be farmed for its gear, especially when its gear is BiS
	- Road Shop including Power Gems, Ravi mats and Ravi decos, completely obsoleted the only siege in the game
	- Feedback and input from the community
	- Ease grinds on MMO-Levels that can't be kept around anymore without the large MMO playerbase behind it
	
# Credits
- Created by Meinerieve and Tsuya.
- Feedback and Input, as well as playtesting by Kyzzy.
- Numbers and Feedback by the community of Frontier Shenanigans Discord Server.
	-- Including but not limited too: Firedrack, Kanon, Charlotte, Dots, Skulltank, Sahn, Tapardy, Zakal, Zoe, Coolnez, Reky, and many more that gave numbers, feedback, input and suggestions.
- Coding Assistance from Miralis.
- Grind numbers and Averages by Fist through his Raviente PDF Guide.
