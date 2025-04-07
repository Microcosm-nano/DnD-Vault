---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fey
aliases: ["Fey Spirit"]
---
# Fey Spirit
*Source: Player's Handbook (2024) p. 326*  
![](2-Mechanics/CLI/bestiary/fey/img/fey-spirit.webp#center)

```ad-statblock
title: Fey Spirit
![](2-Mechanics/CLI/bestiary/fey/token/fey-spirit-xphb.webp#token)
*Small fey, Neutral*

- **Armor Class** (12 + the spell's level)
- **Hit Points** 30 + 10 for each spell level above 3  (30 + 10 for each spell level above 3)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|16 (+3)|14 (+2)|14 (+2)|11 (+0)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Sylvan, understands the languages you know
- **Challenge** 

## Actions

***Multiattack.*** The spirit makes a number of Fey Blade attacks equal to half this spell's level (round down).

***Fey Blade.*** *Melee Attack Roll:* `YourSpellAttack Bonus equals your spell attack modifier`, reach 5 ft. *Hit:* `2d6 + 3` + the spell's level Force damage.

## Bonus Actions

***Fey Step.*** The spirit magically teleports up to 30 feet to an unoccupied space it can see. Then one of the following effects occurs, based on the spirit's chosen mood:

- **Fuming.** The spirit has Advantage on the next attack roll it makes before the end of this turn.  
- **Mirthful.** *Wisdom Saving Throw:* DC equals your spell save DC, one creature the spirit can see within 10 feet of itself. *Failure:* The target is [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by you and the spirit for 1 minute or until the target takes any damage.  
- **Tricksy.** The spirit fills a 10-foot Cube within 5 feet of it with magical Darkness, which lasts until the end of its next turn.  
```
^statblock