---
obsidianUIMode: preview
---


> [!cards|4]
> **Revachol**
> [![[Landscape.jpg\|sban htiny ctr]]](Revachol.md)
> 
> **Emory Mountain Range**
> [![[Emory.jpg\|sban htiny ctr]]](Emory%20Mountain%20Range.md)
>
> **Players**
> [![[PlayerBanner.jpg\|sban htiny ctr]]](Players.md)
> 
> **Current Party**
> [![[PartyBanner.jpg\|sban htiny ctr p+tcc]]](The%20Yam%20Court.md)


> [!infobox]
> # Session Journals
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Sessions", players
from "4-Session Journals"
where (type = "Session Journal")
SORT file.name ASC


```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, hp, ac, pasperc As "Pass Perc (WIS)"
from "3-Party"
where contains(Role, "Player") 
where contains(Status, "Active")
```
# Recently Modified NPCs

```dataview  
TABLE WITHOUT ID link(file.name) AS "NPC Name", Gender, Race, Age, Location, AssociatedGroup  
FROM "5-Campaign/NPCs"
WHERE (NoteIcon = "npc") 
FLATTEN Race
FLATTEN Location
FLATTEN AssociatedGroup
SORT file.mtime DESC
LIMIT 10
```

# Recently Modified Locations

```dataview  
TABLE WITHOUT ID link(file.name) AS "Location Name", type, Government, Community-Size, size, population  
FROM "6-World"
WHERE (NoteIcon = "location")  
SORT file.mtime DESC
LIMIT 10
```


# Recently Modified Notes
```dataview
TABLE WITHOUT ID
    link(file.path, file.folder + " / " + file.name) AS "Note",
    file.mtime AS "Last modified"
FROM "/"
WHERE file.mtime >= date(today) - dur(30 days)
AND file.name != this.file.name
    AND !contains(file.path, "z_Assets")
    AND !contains(file.path, "Inline Scripts")
    AND !contains(file.path, "z_Templates")
    AND !contains(file.path, "daily notes")
    AND !contains(file.path, "BRAT")
SORT file.mtime DESC
LIMIT 10
```

![[Vault Report]]


