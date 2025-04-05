---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Undead Spirit"]
---
# Undead Spirit
*Source: Player's Handbook (2024) p. 328*  
![](2-Mechanics/CLI/bestiary/undead/img/undead-spirit.webp#center)

```ad-statblock
title: Undead Spirit
![](2-Mechanics/CLI/bestiary/undead/token/undead-spirit-xphb.webp#token)
*Medium undead, Neutral*

- **Armor Class** (11 + the spell's level)
- **Hit Points** 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3  (30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3)
- **Speed** 30 ft., fly 40 ft. (hover; Ghostly only)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|15 (+2)| 4 (-3)|10 (+0)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages you know
- **Challenge** 

## Traits

***Festering Aura (Putrid Only).*** *Constitution Saving Throw:* DC equals your spell save DC, any creature (other than you) that starts its turn within a 5-foot Emanation originating from the spirit. *Failure:* The creature has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of its next turn.

***Incorporeal Passage (Ghostly Only).*** The spirit can move through other creatures and objects as if they were Difficult Terrain. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes `1d10` Force damage for every 5 feet traveled.

## Actions

***Multiattack.*** The spirit makes a number of attacks equal to half this spell's level (round down).

***Deathly Touch (Ghostly Only).*** *Melee Attack Roll:* `YourSpellAttack Bonus equals your spell attack modifier`, reach 5 ft. *Hit:* `1d8 + 3` + the spell's level Necrotic damage, and the target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the end of its next turn.

***Grave Bolt (Skeletal Only).*** *Ranged Attack Roll:* `YourSpellAttack Bonus equals your spell attack modifier`, range 150 ft. *Hit:* `2d4 + 3` + the spell's level Necrotic damage.

***Rotting Claw (Putrid Only).*** *Melee Attack Roll:* `YourSpellAttack Bonus equals your spell attack modifier`, reach 5 ft. *Hit:* `1d6 + 3` + the spell's level Slashing damage. If the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition, it has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the end of its next turn.
```
^statblock