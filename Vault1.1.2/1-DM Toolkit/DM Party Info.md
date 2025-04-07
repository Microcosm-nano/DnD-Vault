---
obsidianUIMode: preview
assa:
---

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", max(Player) AS Player, max(hp) AS "Hit Points", max(ac) AS "Armor Class", max(pasperc) AS "Passive Perception"
from "3-Party"
where contains(Role, "Player") 
where contains(Status, "Active")
```
## Known Languages

%% This will scan the player notes for any known languages and list the unique languages that the party know here. This is handy to determine quickly if the party can understand someone. %%
```dataviewjs
dv.list(dv.pages()
		.where(p => p.Status && p.Status.includes("Active") && p.Role && p.Role.includes("Player"))
		.PlayerKnownLanguages.distinct())
```

## Magic Items

```dataviewjs
dv.list(
  dv.pages()
    .where(p => 
      p.Status && p.Status.includes("Active") &&
      p.Role && p.Role.includes("Player") &&
      p.MagicItems
    )
    .flatMap(p => 
      p.MagicItems
        .filter(item =>
          !String(item).includes("+")
        )
        .map(item =>
          String(item).replace(/\s*\([^)]*\)$/, "")
        )
    )
    .distinct()
)
```
