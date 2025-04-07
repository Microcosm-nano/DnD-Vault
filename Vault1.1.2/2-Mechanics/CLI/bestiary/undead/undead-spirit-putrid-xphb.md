---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Undead Spirit (Putrid)"]
---
# Undead Spirit (Putrid)
*Source: Player's Handbook (2024) p. 328*  

```ad-statblock
title: Undead Spirit (Putrid)
*Medium undead, Neutral*

- **Armor Class** (11 + the spell's level)
- **Hit Points** 30 + 10 for each spell level above 3  (30 + 10 for each spell level above 3)
- **Speed** 30 ft.

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

***Festering Aura.*** *Constitution Saving Throw:* DC equals your spell save DC, any creature (other than you) that starts its turn within a 5-foot Emanation originating from the spirit. *Failure:* The creature has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of its next turn.

## Actions

***Multiattack.*** The spirit makes a number of attacks equal to half this spell's level (round down).

***Rotting Claw.*** *Melee Attack Roll:* `YourSpellAttack Bonus equals your spell attack modifier`, reach 5 ft. *Hit:* `1d6 + 3` + the spell's level Slashing damage. If the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition, it has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the end of its next turn.
```
^statblock