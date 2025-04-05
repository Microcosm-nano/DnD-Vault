---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
aliases: ["Remorhaz"]
---
# Remorhaz
*Source: Monster Manual (2024) p. 258*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/remorhazes.webp#right)

Full-grown remorhazes are single-minded ambush predators. They attempt to bite prey and trap it against their searing bodies, then swallow their meal whole. Remorhazes eat as much as they can, since they might go months without feeding.

## Remorhazes

*Super-Heated Arctic Arthropods*

- **Habitat.** Arctic  
- **Treasure.** None  

Remorhazes are centipede-like terrors that burrow through snow and ice to ambush smaller creatures that trespass in their frozen territories.

## Statblock

```ad-statblock
title: Remorhaz
![](2-Mechanics/CLI/bestiary/monstrosity/token/remorhaz-xmm.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 17 
- **Hit Points** 195 (`17d12 + 85`) 
- **Speed** 40 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|13 (+1)|21 (+5)| 4 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., tremorsense 60 ft., passive Perception 10
- **Damage Immunities** cold, fire
- **Languages** —
- **Challenge** 11

## Traits

***Heat Aura.*** At the end of each of the remorhaz's turns, each creature in a 5-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the remorhaz takes 16 (`3d10`) Fire damage.

## Actions

***Bite.*** *Melee Attack Roll:* `+11`, reach 10 ft. *Hit:* 18 (`2d10 + 7`) Piercing damage plus 14 (`4d6`) Fire damage. If the target is a Large or smaller creature, it has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 17), and it has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the grapple ends.

## Bonus Actions

***Swallow.*** *Strength Saving Throw:* DC 19, one Large or smaller creature [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the remorhaz (it can have up to two creatures swallowed at a time). *Failure:* The target is swallowed by the remorhaz, and the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition ends. A swallowed creature has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, it has [Total Cover](2-Mechanics/CLI/rules/variant-rules/cover-xphb.md) against attacks and other effects outside the remorhaz, and it takes 10 (`3d6`) Acid damage plus 10 (`3d6`) Fire damage at the start of each of the remorhaz's turns.

If the remorhaz takes 30 damage or more on a single turn from a creature inside it, the remorhaz must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 5 feet of the remorhaz and has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. If the remorhaz dies, any swallowed creature no longer has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and can escape from the corpse by using 15 feet of movement, exiting [Prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

arctic