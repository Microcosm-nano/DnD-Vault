---
NoteIcon: character
aliases: 
tags:
  - character
Player: 
Role:
  - Player
Class: 
Race: 
level: 
hp: 
ac: 
modifier: 
pasperc: 
Status:
  - Active
PlayerKnownLanguages:
  - Common
Gender: 
AssociatedGroup: 
Vitality: Alive
Age: 
MagicItems:
---

<% await tp.file.move("/3-Party/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewCharacter");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Character Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[PartyLogo.jpg]]
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
`INPUT[listSuggester(optionQuery("2-Mechanics/CLI/races")):Race]`
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