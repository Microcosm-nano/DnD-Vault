---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
aliases: ["Purple Worm"]
---
# Purple Worm
*Source: Monster Manual (2024) p. 250*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/purple-worm.webp#right)

## Purple Worm

*What Gnaws the Roots of the World*

- **Habitat.** Desert, Underdark  
- **Treasure.** None  

Titanic purple worms burrow through the earth and sand. Ever ravenous, they devour smaller creatures and ravage entire communities in their aimless burrowing.

> [!quote] A quote from Morrikan d'Kundarak  
> 
> Purple worms alone are bad enough, but the blasted monsters have a knack for unearthing things that are even worse!


```ad-statblock
title: Purple Worm
![](2-Mechanics/CLI/bestiary/monstrosity/token/purple-worm-xmm.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 18 
- **Hit Points** 247 (`15d20 + 90`) 
- **Speed** 50 ft., burrow 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)| 7 (-2)|22 (+6)| 1 (-5)| 8 (-1)| 4 (-3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Wisdom +4
- **Skills** ⏤
- **Senses** blindsight 30 ft., tremorsense 60 ft., passive Perception 9
- **Languages** —
- **Challenge** 15

## Traits

***Tunneler.*** The worm can burrow through solid rock at half its [Burrow Speed](2-Mechanics/CLI/rules/variant-rules/burrow-speed-xphb.md) and leaves a 10-foot-diameter tunnel in its wake.

## Actions

***Multiattack.*** The worm makes one Bite attack and one Tail Stinger attack.

***Bite.*** *Melee Attack Roll:* `+14`, reach 10 ft. *Hit:* 22 (`3d8 + 9`) Piercing damage. If the target is a Large or smaller creature, it has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 19), and it has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the grapple ends.

***Tail Stinger.*** *Melee Attack Roll:* `+14`, reach 10 ft. *Hit:* 16 (`2d6 + 9`) Piercing damage plus 35 (`10d6`) Poison damage.

## Bonus Actions

***Swallow.*** *Strength Saving Throw:* DC 19, one Large or smaller creature [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the worm (it can have up to three creatures swallowed at a time). *Failure:* The target is swallowed by the worm, and the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition ends. A swallowed creature has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, has [Total Cover](2-Mechanics/CLI/rules/variant-rules/cover-xphb.md) against attacks and other effects outside the worm, and takes 17 (`5d6`) Acid damage at the start of each of the worm's turns.

If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 5 feet of the worm and has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. If the worm dies, any swallowed creature no longer has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and can escape from the corpse using 20 feet of movement, exiting [Prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

desert, underdark