---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
aliases: ["Assassin Vine"]
---
# Assassin Vine
*Source: Tomb of Annihilation p. 213, Ghosts of Saltmarsh*  
![](2-Mechanics/CLI/bestiary/plant/img/assassin-vine.webp#right)

An assassin vine is an ambulatory plant that collects its fertilizer by grabbing and crushing prey and depositing the carcasses near its roots. It usually stays put unless it needs to seek out prey. A mature plant consists of a main vine, about 20 feet long. Smaller vines up to 5 feet long branch from the main vine every 6 inches. In late summer, the secondary vines produce bunches of small fruits that resemble wild grapes. The fruit is tough and has a hearty but bitter flavor.

A subterranean variant grows near hot springs, volcanic vents, and other sources of heat. An assassin vine growing underground usually generates enough offal to support a thriving colony of mushrooms and other fungi, which spring up around the plant and help conceal it.

```ad-statblock
title: Assassin Vine
![](2-Mechanics/CLI/bestiary/plant/token/assassin-vine-toa.webp#token)
*Large plant, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 85 (`10d10 + 30`) 
- **Speed** 5 ft., climb 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|16 (+3)| 1 (-5)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 30 ft., passive Perception 10
- **Damage Resistances** cold, fire
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 3

## Traits

***False Appearance.*** While the assassin vine remains motionless, it is indistinguishable from a normal plant.

## Actions

***Constrict.*** *Melee Weapon Attack:* `+6` to hit, reach 20 ft., one creature. *Hit:* The target takes 11 (`2d6 + 4`) bludgeoning damage, and it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and it takes 21 (`6d6`) poison damage at the start of each of its turns. The vine can constrict only one target at a time.

***Entangling Vines.*** The assassin vine can animate normal vines and roots on the ground in a 15-foot square within 30 feet of it. These plants turn the ground in that area into difficult terrain. A creature in that area when the effect begins must succeed on a DC 13 Strength saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by entangling vines and roots. A creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the plants can use its action to make a DC 13 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check, freeing itself on a successful check. The effect ends after 1 minute or when the assassin vine dies or uses Entangling Vines again.
```
^statblock