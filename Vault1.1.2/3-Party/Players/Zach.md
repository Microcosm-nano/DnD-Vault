---
PlayerRole: Permanent
---

## Characters

```dataview
TABLE max(level) AS Level, Gender, join(Race, ", ") AS Race, join(Class, ", ") AS Class, max(hp) AS "Hit Points", max(ac) AS "Armor Class", max(pasperc) AS "Passive Perception"
from "3-Party"
where contains( Player, this.file.link)
FLATTEN Class
```