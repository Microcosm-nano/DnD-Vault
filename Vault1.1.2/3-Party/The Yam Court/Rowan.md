---
NoteIcon: character
aliases:
  - The Duke of Yams
  - Corvid
  - Isaac Cunningham
tags:
  - character
Player: "[[3-Party/Players/Mitch.md|Mitch]]"
Role:
  - Player
Class:
  - "[[Fighter|Fighter]]"
Race:
  - Human
Age: 51
level: 8
hp: 82
ac: 17
modifier: "3"
pasperc: "13"
Status:
  - Active
PlayerKnownLanguages:
  - Common
  - Draconic
  - Dwarvish
Gender: Male
AssociatedGroup:
  - "[[The Murder]]"
Vitality: Alive
MagicItems:
  - "[[shield-of-missile-attraction-xdmg|Shield of Missile Attraction]]"
  - "[[ring-of-free-action-xdmg|Ring of Free Action]]"
  - "[[1-weapon-xdmg#+1 War Pick|+1 Weapon]]"
  - "[[dimensional-shackles-xdmg|Dimensional Shackles]]"
  - "[[Eye of Aazimor]] (Normal)"
  - "[[Eye of Aazimor]] (Hourglass)"
KeyItems:
  - Abyssal Dictionary
  - Celestial Dictionary
  - Deep Speech Dictionary
  - Infernal Dictionary
---


> [!infobox]
> # `=this.file.name`
> ![[Rowan.jpg]]
>~~~meta-bind
>INPUT[select(
>option(1, Stats),
>option(2, Inventory),
>class(tabbed)
>)]
>~~~
>> [!tabbed-box]
>>> [!div|no-t no-i clean]
>>>|||
>>>|---|---|
>>> ###### Info
>>> Type |  Stat |
>>> ---|---|
>>> Player | `=this.Player` |
>>> Level | `=this.level` |
>>> Gender | `=this.gender` |
>>> Race | `=this.race` |
>>> Class | `=this.Class` |
>>> Age | `=this.age` |
>>> Faction(s) | `=this.AssociatedGroup` |
>>> Vitality | `=this.vitality` |
>>> ###### Stats
>>> Type |  Stat |
>>> ---|---|
>>> Total HP | `=this.hp` |
>>> AC | `=this.ac` |
>>> Passive Perception | `=this.pasperc` |
>>> Languages | `=this.PlayerKnownLanguages`
>>
>>> [!div|no-t no-i clean]
>>>|||
>>>|---|---|
>>> # Inventory
>>> ```dataview
>>> TABLE WITHOUT ID MagicItems AS "Magic Items"
>>> where (file.name = this.file.name)
>>> FLATTEN MagicItems
>>> LIMIT 20
>>> ```
>>> ```dataview
>>> TABLE WITHOUT ID KeyItems AS "Key Items"
>>> where (file.name = this.file.name)
>>> FLATTEN KeyItems
>>> LIMIT 20
>>> ```


> [!recite| no-i background-black]- # Character Editor
> 
> ## Basic Info
> ### Player Name
`INPUT[suggester(optionQuery("3-Party/Players")):Player]`
>#### Character Aliases
**Do not enter your character's name. This is for nicknames, aliases, codenames, etc.**
>
`INPUT[list:aliases]`
>
>#### Sex
`INPUT[inlineSelect(option(Select), option(Male), option(Female), option(Nonbinary), option(Genderless)):Gender]`
>
>#### Race
`INPUT[list:Race]`
[[races]]
>
>#### Class
`INPUT[listSuggester(optionQuery("2-Mechanics/CLI/classes")):Class]`
[[classes]]
>
>## Stats
>
>### Level
`INPUT[number:level]`
>
>#### Maximum Hit Points
`INPUT[number:hp]`
[[level-1-hit-points-by-class-xphb]]
[[hit-points-xphb|Hit Points]]
[[hit-point-dice-xphb|Hit Point Dice]]
>
>#### Armor Class
`INPUT[number:ac]`
[[armor-class-xphb|Armor Class]]
>
>#### Proficiency Bonus
`INPUT[number:modifier]`
[[proficiency-bonus-xphb|Proficiency Bonus]]
>
>#### Passive Perception
`INPUT[number:pasperc]`
[[passive-perception-xphb|Passive Perception]]
>
>## Inventory, Lore, & Misc
>
>#### Age
`INPUT[number:Age]`
>
>#### Known Languages
[[03-chapter-2-creating-a-character#Choose Languages| Languages]]
`INPUT[list:PlayerKnownLanguages]`
>#### Factions
`INPUT[listSuggester(optionQuery("5-Campaign/Guilds and Groups")):AssociatedGroup]`
>
>#### Magic Items
`INPUT[listSuggester(optionQuery("5-Campaign/Items" OR "2-Mechanics/CLI/items")):MagicItems]`


## Biography

Isaac Cunningham became orphaned at a very young age in [[Herzloch]]. He has memories of his parents but most are blurry and unreliable after the passage of time. As a child he learned how to sneak and steal in order to survive between odd jobs across the [[Emory Mountain Range]]. He found himself in a gang by the time he reached adolescence where he honed his skills in thievery, intimidation and combat.  By the time he had reached adulthood he had established himself as a formidable foe. He was capable of dispatching powerful combatants and outmaneuvering shrewd enemies to gain power and influence in his gang. The gang was attempting to commit a series of stagecoach robberies along the main highway between [[Lierburg]] and [[Herzloch]], but could not do so with the Vetterlund  presence along the highway in the form of a manned outpost. There were 22 soldiers stationed at the outpost. Isaac, by some horrid means, managed to eliminate the entire Vetterlund outpost alone. He quickly became well known across the region in whispers and rumors as a Boogeyman. It was around this time that [[Sien Severim]] learned about Isaac.

A few years later, after a job gone wrong, Isaac's gang was in shambles. His leader had died and many of his colleagues had scattered. It was around this time he was recruited into [[The Murder]]. There, Isaac became the enforcer of The Murder, answering directly to Sien Severim. Here, he became an even more fearsome foe, adding torture and assassination to his repertoire, and gaining the nickname Corvid.  Despite all the legends now surrounding him, his identity was mostly shrouded in myth, with very few still alive knowing the man himself. After some years in the gang, (((Redacted))). Isaac, now going by the name of  Rowan, sets off from [[Lierburg]], ready to enact revenge and destroy The Murder, and eliminate Sien Severim.

## Relationships

- [[Sien Severim]] - Main Antagonist (formerly a business partner in [[The Murder]])
- (((Redacted)))

## Abilities

- Affinity for thievery and sneaking
- Competent combatant
- Wide array of tools
- (((Redatcted)))
- Skilled with intimidation and torture, though now unlikely to use it.

## Deeds & Misdeeds

Rowan:
- Destroyed [[The Murder]], though Severim lives
- A member of [[The Yam Court]]
- Liberated [[Maier]] from the False hydra
- Helped destroy a Darkling caravan
- Liberated [[Geldfelder]] from a Lupine

Isaac:
- Famed Criminal
- Former Member of multiple gangs
- Torturer
- Now thought to be dead by most

## Quirks and Tendencies

- Raspy voice
- Often smoking a pipe during leisure time
- Penchant for gambling at taverns and inns
- Falsely claims any lock he cannot pick is an "Unpickable lock"
