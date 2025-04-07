---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity
aliases: ["Cockatrice"]
---
# Cockatrice
*Source: Monster Manual (2024) p. 75*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/cockatrices.webp#right)

Cockatrices often try to claim eye-catching structures—such as ruins and secluded farms—as roosts.

## Cockatrices

*Accursed Avians with the Power to Petrify*

- **Habitat.** Grassland  
- **Treasure.** None  

Cockatrices combine the features of irate roosters and starving reptiles. They petrify those they bite, their slightest peck turning their prey to stone.

## Statblock

```ad-statblock
title: Cockatrice
![](2-Mechanics/CLI/bestiary/monstrosity/token/cockatrice-xmm.webp#token)
*Small monstrosity, Unaligned*

- **Armor Class** 11 
- **Hit Points** 22 (`5d6 + 5`) 
- **Speed** 20 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|12 (+1)|12 (+1)| 2 (-4)|13 (+1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Condition Immunities** [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** —
- **Challenge** 1/2

## Actions

***Petrifying Bite.*** *Melee Attack Roll:* `+3`, reach 5 ft. *Hit:* 3 (`1d4 + 1`) Piercing damage. If the target is a creature, it is subjected to the following effect. *Constitution Saving Throw:* DC 11. *1st Failure:* The target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. The target repeats the save at the end of its next turn if it is still [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), ending the effect on itself on a success. *2nd Failure:* The target has the [Petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition, instead of the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, for 24 hours.
```
^statblock

## Environment

grassland