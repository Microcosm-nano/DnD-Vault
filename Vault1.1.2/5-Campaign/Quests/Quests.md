---
banner: [[TreasureBanner.jpg]]
banner-y: 90
content-start: 250
banner-display: cover
banner-repeat: false
banner-height: 325
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 100
---

```meta-bind-button
label: New Quest
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateQuest.md"
    fileName: NewQuest
```

## Active Quests

```dataview
TABLE WITHOUT ID link(file.name) AS " Quests", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Available Rewards"
from "5-Campaign" AND #quest
where questStatus = "In Progress"
```

## Completed Quests

```dataview
TABLE WITHOUT ID link(file.name) AS "Quests", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Rewards"
from "5-Campaign" AND #quest
where questStatus = "Complete"
```