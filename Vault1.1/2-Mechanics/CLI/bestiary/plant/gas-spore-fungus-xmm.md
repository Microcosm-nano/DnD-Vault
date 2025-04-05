---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
aliases: ["Gas Spore Fungus"]
---
# Gas Spore Fungus
*Source: Monster Manual (2024) p. 125*  
![](2-Mechanics/CLI/bestiary/plant/img/fungi.webp#right)

Gas spores are floating, orbicular fungi with rhizome growths and protuberances that resemble the stalks and eyes of beholders. If destroyed, a gas spore explodes in a poisonous burst that can infect creatures and slay them in hours. Infected corpses spawn more gas spores that grow to full size in a matter of days.

## Fungi

*Deadly Spores and Predatory Polyps*

- **Habitat.** Underdark  
- **Treasure.** None  

The dank, sunless Underdark is a fertile breeding ground for weird and dangerous fungi.

## Statblock

```ad-statblock
title: Gas Spore Fungus
![](2-Mechanics/CLI/bestiary/plant/token/gas-spore-fungus-xmm.webp#token)
*Large plant, Unaligned*

- **Armor Class** 8 
- **Hit Points** 13 (`9d10 - 36`) 
- **Speed** 5 ft., fly 10 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 5 (-3)| 1 (-5)| 3 (-4)| 1 (-5)| 1 (-5)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 30 ft., passive Perception 5
- **Damage Immunities** poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/2

## Traits

***Death Burst.*** The gas spore bursts when it dies. *Constitution Saving Throw:* DC 10, each creature in a 20-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the gas spore. *Failure:* The target takes 10 (`3d6`) Poison damage and has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for `1d12` hours. Unless the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition is removed, the target dies at the end of that time and sprouts `2d4` Tiny Gas Spore Fungi (each with 1 [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)). After `2d6` days, they become Large and have 13 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

## Actions

***Tendril.*** *Melee Attack Roll:* `+0`, reach 5 ft. *Hit:* 3 (`1d6`) Poison damage, and the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of its next turn.
```
^statblock

## Environment

underdark