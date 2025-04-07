---
PlayerRole: Guest
---

<% await tp.file.move("/3-Party/Players/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewPlayer");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Player Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

## Characters

```dataview
TABLE max(level) AS Level, Gender, join(Race, ", ") AS Race, join(Class, ", ") AS Class, max(hp) AS "Hit Points", max(ac) AS "Armor Class", max(pasperc) AS "Passive Perception"
from "3-Party"
where contains( Player, this.file.name)
FLATTEN Class
```