---
NoteIcon: character
aliases: 
tags:
  - character
Player: "[[3-Party/Players/Dean.md|Dean]]"
Role:
  - Player
Class:
  - "[[Wizard|Wizard]]"
Race:
  - Gnome
level: 8
hp: 61
ac: 13
modifier: "3"
pasperc: "11"
Status:
  - Inactive
PlayerKnownLanguages:
  - Common
  - Sylvan
  - Deep Speech
Gender: Male
AssociatedGroup:
  - "[[Herzloch College of the Arcane]]"
Vitality: Deceased
Age: "116"
MagicItems:
  - "[[hat-of-wizardry-xdmg|Hat of Wizardry]]"
---

> [!infobox]
> # `=this.file.name`
> ![[Aldwerden.webp]]
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
>#### Class(es)
`INPUT[suggester(optionQuery("2-Mechanics/CLI/classes")):Class]`
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