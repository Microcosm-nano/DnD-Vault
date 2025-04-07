---
NoteIcon: location
tags:
  - Category/Settlement
Community-Size: Outpost
Government: Autocracy
type: Settlement
politics: Lordship
leader: 
guildsgroups: 
region: 
size: Small city
population: 0
commonraces:
  - Humans
  - Elves
  - Dwarves
religion:
  - Lathander
defenses:
banner: [[CityBanner.jpg]]
banner-y: 70
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
const hasTitle = !tp.file.title.startsWith("NewLocation");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Location Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


> [!infobox]
> # `=this.file.name`
> ![[MapPlaceholder.png|cover hsmall]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defenses | `=this.defenses` |
> 
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Organizations
> Type |  Stat |
> ---|---|
> Factions| `=this.guildsgroups`|

## Overview

Placeholder

### Scenery
![[ImagePlaceholder.png|Placeholder Picture]]

Placeholder

## Notable People
- Placeholder

## History

Placeholder

## Points of Interest
- Placeholder

