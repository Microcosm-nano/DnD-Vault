---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
aliases: ["Cockatrice Regent"]
---
# Cockatrice Regent
*Source: Monster Manual (2024) p. 75*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/cockatrices.webp#right)

Bolder than their smaller cousins, cockatrice regents brim with unstable magical energy they use to restrain distant foes.

## Cockatrices

*Accursed Avians with the Power to Petrify*

- **Habitat.** Grassland  
- **Treasure.** None  

Cockatrices combine the features of irate roosters and starving reptiles. They petrify those they bite, their slightest peck turning their prey to stone.

## Statblock

```ad-statblock
title: Cockatrice Regent
![](2-Mechanics/CLI/bestiary/monstrosity/token/cockatrice-regent-xmm.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 15 
- **Hit Points** 136 (`16d10 + 48`) 
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|14 (+2)|16 (+3)| 3 (-4)|16 (+3)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +6
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Condition Immunities** [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** —
- **Challenge** 8

## Traits

***Flyby.*** The cockatrice doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.

## Actions

***Multiattack.*** The cockatrice makes one Petrifying Bite attack and two Talons attacks.

***Petrifying Bite.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 13 (`2d8 + 4`) Piercing damage. If the target is a creature, it is subjected to the following effect. *Constitution Saving Throw:* DC 14. *1st Failure:* The target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and repeats the save at the end of its next turn if it is still [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), ending the effect on itself on a success. *2nd Failure:* The target has the [Petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition instead of the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition.

***Talons.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 18 (`4d6 + 4`) Slashing damage.

## Reactions

***Magical Backlash.*** Trigger: A creature within 120 feet of the cockatrice deals damage to it. _Response—_*Dexterity Saving Throw:* DC 14, the triggering creature. *Failure:* 13 (`3d6 + 3`) Force damage.
```
^statblock

## Environment

grassland