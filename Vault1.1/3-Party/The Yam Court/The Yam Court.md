---
NoteIcon: 
aat-render-enabled: true
players: 5
Status: 
tags: 
banner: "[[PartyBanner.jpg]]"
banner-y: 25
content-start: 175
banner-display: cover
banner-repeat: false
banner-height: 250
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 67
---

## Adventurers
```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", max(Player) AS Player, max(level) AS Level, join(Race, ", ") AS Race, join(Class, ", ") AS Class, max(hp) AS "Hit Points", max(ac) AS "Armor Class", max(pasperc) AS "Passive Perception"
from "3-Party"
WHERE contains(Role, "Player") AND contains(Status, "Active")
```

## Featuring
```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", max(Player) AS Player, max(level) AS Level, join(Race, ", ") AS Race, join(Class, ", ") AS Class, max(hp) AS "Hit Points", max(ac) AS "Armor Class", max(pasperc) AS "Passive Perception"
from "3-Party"
WHERE contains(Role, "Guest") AND contains(Status, "Active")
```
