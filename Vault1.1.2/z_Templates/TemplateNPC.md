---
AssociatedGroup: 
Gender: Male
Race: 
Age: "1"
Class: 
Alignment: 
Character-Role: NPC
Location: 
NoteIcon: npc
Vitality: Deceased
exampleProperty: z_Assets/Decks/Business Card Dungeon/Dungeon16.png
banner: "[[NpcBanner.jpg]]"
banner-y: 45
content-start: 250
banner-display: cover
banner-repeat: false
banner-height: 325
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 100
---

<% await tp.file.move("/5-Campaign/NPCs/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[ImagePlaceholder.png|cover hsmall]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.Location` |
> Group | `=this.AssociatedGroup` |
> Sex | `=this.gender` |
> Race | `=this.race` |
> Age | `=this.age` |
> Vitality | `=this.vitality` |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

## Biography

...

## Relationships

...

## Personality

...

## Abilities

...

## Statblock

> [!info] Statblock
> ```statblock
> name: Individual
> monster: Commoner
> columns: 1
> ```
