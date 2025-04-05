---
banner: "[[StrahdBanner.jpg]]"
banner-y: 30
content-start: 225
banner-display: cover
banner-repeat: false
banner-height: 300
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 47
---

## Dead Adventurers

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", max(Player) AS Player, max(level) AS Level, join(Race, ", ") AS Race, join(Class, ", ") AS Class
from "3-Party"
WHERE contains(Role, "Player") AND contains(Vitality, "Deceased")
FLATTEN Class
```