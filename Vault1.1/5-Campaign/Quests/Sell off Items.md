---
questObtained: 
questStatus: Complete
questGiver: 
questLocationObtained: 
questSessionObtained: 
questNotes: 
questLootAvail: 
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
banner:
  - - TreasureBanner.jpg
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

## Synopsis

> [!infobox]+
> # `=this.file.name`
> ## Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

Go to the market and sell off some unneeded items.

### Quest Objective

- Sell eye stalks to the alchemist
- Sell [[manual-of-golems-xdmg|Manual of Golems]] to the alchemist

### Rewards

- [[gold-xdmg|Gold]]
- 40,150 GP