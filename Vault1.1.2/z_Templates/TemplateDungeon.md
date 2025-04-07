---
NoteIcon: dungeon
tags:
  - Category/Settlement
leader: Billy Joel
guildsgroups:
  - The Guys
region:
  - Place
creaturetypes:
  - Undead
floors: 4
banner: [[DungeonBanner.jpg]]
banner-y: 20
content-start: 250
banner-display: cover
banner-repeat: false
banner-height: 325
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 100
---

<% await tp.file.move("/6-World/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewDungeon");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Dungeon Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
![[Pasted image 20250128214925.png]]
> ###### INFO
> Type |  Stat |
> ---|---|
> Region | `=this.region` |
>  Floors | `=this.floors` |
> Boss | `=this.leader` |
> Factions| `=this.guildsgroups`|
> Creatures| `=this.creaturetypes`|

## Overview

Placeholder

### Scenery
![[Pasted image 20250128214931.png]]

*Placeholder*

## Map

![[cavemap.png]]

## Notable People & Creatures
- Placeholder

## History

Placeholder

## Points of Interest
- Placeholder