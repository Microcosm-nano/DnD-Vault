---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
aliases: ["Mud Hulk"]
---
# Mud Hulk
*Source: Bigby Presents: Glory of the Giants p. 161*  
![](2-Mechanics/CLI/bestiary/elemental/img/mud-hulk.webp#right)

The ancestors of mud hulks were hill giants who, living in isolation, ate everything within reach until they were forced to subsist on the earth itself. The giants' elemental nature asserted itself and transformed them into creatures of living mud.

A mud hulk vaguely resembles its ancestors, but its body consists of wet mud that constantly sloughs off around it, creating thick pools of the stuff everywhere the creature goes. It retains the hunger of a hill giant, enveloping anything even vaguely edible and directly absorbing it into its body. When threatened, it hurls masses of mud at its enemies to make sure they stay in place long enough for the mud hulk to consume them.

> [!quote] A quote from Bigby  
> 
> Well, while you're mourning, that thing is trying to engulf me in mud! Pardon me while I interpose a hand to keep it away from me.


```ad-statblock
title: Mud Hulk
![](2-Mechanics/CLI/bestiary/elemental/token/mud-hulk-bgg.webp#token)
*Large elemental, typically  Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 68 (`8d10 + 24`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 8 (-1)|16 (+3)| 5 (-3)| 9 (-1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 9
- **Damage Resistances** acid
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** Giant, Terran
- **Challenge** 3

## Traits

***Amorphous.*** The mud hulk can move through a space as narrow as 1 inch without squeezing.

***Sticky Mud.*** The ground within 15 feet of the mud hulk is difficult terrain for other creatures.

## Actions

***Enveloping Slam.*** *Melee Weapon Attack:* `+5` to hit, reach 10 ft., one target. *Hit:* 9 (`1d12 + 3`) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 13 Strength saving throw or be pulled into the mud hulk's space and be engulfed by the mud hulk. While engulfed, the target can't breathe, has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and takes 6 (`1d12`) acid damage at the start of each of its turns. When the mud hulk moves, the engulfed target moves with it. The mud hulk can have only one target engulfed at a time. While a creature is engulfed, the mud hulk can't use its Amorphous trait.

An engulfed target can repeat the saving throw at the end of each of its turns. On a successful save, the target escapes and enters the nearest unoccupied space.

***Mud Splash.*** The mud hulk lobs a mass of mud that splashes in a 10-foot-radius sphere centered on a point within 30 feet of the mud hulk. Each creature in that area must make a DC 13 Dexterity saving throw, taking 10 (`2d6 + 3`) bludgeoning damage on a failed save, or half as much damage on a successful one. The affected area is difficult terrain until the start of the mud hulk's next turn.
```
^statblock