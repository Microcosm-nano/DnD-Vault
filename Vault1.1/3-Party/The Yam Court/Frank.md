---
NoteIcon: character
aliases:
  - The Prince of Yams
tags:
  - character
Player: "[[3-Party/Players/Zach.md|Zach]]"
Role:
  - Player
Class:
  - "[[Fighter|Fighter]]"
Race:
  - Human
level: 8
hp: 82
ac: 18
modifier: "3"
pasperc: "10"
Status:
  - Active
PlayerKnownLanguages:
  - Common
  - Celestial
  - Sign Language
Gender: Male
AssociatedGroup:
  - "[[Clan Wilthang]]"
Vitality: Alive
Age: "29"
MagicItems:
  - "[[dread-helm-xdmg|Dread Helm]]"
  - "[[Blade of Benevolence]]"
  - "[[Handcannon]] (Blue Crystal)"
  - "[[cloak-of-protection-xdmg|Cloak of Protection]]"
  - "[[1-weapon-xdmg#+1 Longsword|+1 Weapon]]"
  - "[[1-armor-xdmg#+1 Half Plate Armor|+1 Armor]]"
  - "[[dimensional-shackles-xdmg|Dimensional Shackles]]"
---

> [!infobox]
> # `=this.file.name`
> ![[Frank.jpg]]
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
>>> Languages | `=this.PlayerKnownLanguages` |
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
`INPUT[number:age]`
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

...

## Relationships

...

## Abilities

...

## Deeds & Misdeeds

...

## Quirks and Tendencies

...