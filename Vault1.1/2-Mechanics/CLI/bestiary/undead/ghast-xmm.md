---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Ghast"]
---
# Ghast
*Source: Monster Manual (2024) p. 130*  
![](2-Mechanics/CLI/bestiary/undead/img/ghasts.webp#right)

Ghasts frequently organize ghouls into packs to despoil crypts and steal the wealth within.

## Ghasts

*Tyrants among Corpses*

- **Habitat.** Swamp, Underdark, Urban  
- **Treasure.** Any  

Ghasts are reeking, undying corpses closely related to ghouls. They hunger for the vices they enjoyed in life as much as they do for rotting flesh.

## Statblock

```ad-statblock
title: Ghast
![](2-Mechanics/CLI/bestiary/undead/token/ghast-xmm.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 13 
- **Hit Points** 36 (`8d8`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|17 (+3)|10 (+0)|11 (+0)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 2

## Traits

***Stench.*** *Constitution Saving Throw:* DC 10, any creature that starts its turn in a 5-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the ghast. *Failure:* The target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of its next turn. *Success:* The target is immune to this ghast's Stench for 24 hours.

## Actions

***Bite.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 7 (`1d8 + 3`) Piercing damage plus 9 (`2d8`) Necrotic damage.

***Claw.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 10 (`2d6 + 3`) Slashing damage. If the target is a non-Undead creature, it is subjected to the following effect. *Constitution Saving Throw:* DC 10. *Failure:* The target has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the end of its next turn.
```
^statblock

## Environment

swamp, underdark, urban