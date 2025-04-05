---
tags:
  - Category/Group
Community-Size: 
Alignment: 
Government: 
Leader: 
PrimaryHome: 
NoteIcon: group
banner: [[PartyBanner.jpg]]
banner-y: 25
content-start: 175
banner-display: cover
banner-repeat: false
banner-height: 250
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 100
---

<% await tp.file.move("/5-Campaign/Guilds and Groups/" + tp.file.title) %>

<%*  
const hasTitle = !tp.file.title.startsWith("NewGroup");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Group Name");  
await tp.file.rename(title);  
} else {  
title = tp.file.title;  
}  
_%>

> [!infobox]
> # `=this.file.name`
> ![[ImagePlaceholder.png]]
> ###### Key Members
> ```dataview
table Race, Gender
FLATTEN Race
where contains( AssociatedGroup, this.file.link)
## Overview
...

## Etymology
...
## Activities
...

## Society
### Beliefs
...
### Culture
...

### Religion
...

## Possessions
...

## History
...

## Rumors & Legends
...


