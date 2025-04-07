---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
aliases: ["Chain Devil"]
---
# Chain Devil
*Source: Monster Manual (2024) p. 68*  
![](2-Mechanics/CLI/bestiary/fiend/img/chain-devil.webp#right)

## Chain Devil

*Devil of Pain and Control*

- **Habitat.** Planar (Nine Hells)  
- **Treasure.** Implements  

Also known as kytons, chain devils consider themselves morbid artisans who use deception, menace, and vicious metal to coerce prisoners into betraying themselves. Many serve powerful devils, wrenching secrets from imprisoned souls using deadly, animate chains. Left to their own devices, chain devils encourage ruthless individuals to pursue forbidden magic, leading their pupils down paths to the Nine Hells.

Along with psychological threats and physical harm, a chain devil uses its unnerving gaze to make its victims perceive their worst fear rather than the monster. Roll on or choose a result from the Chain Devil Masks table to inspire a chain devil's fearful appearance.

**Chain Devil Masks**

`dice: [](chain-devil-xmm.md#^chain-devil-masks)`

| dice: 1d4 | To a Viewer, the Chain Devil Looks Like... |
|-----------|--------------------------------------------|
| 1 | The corpse of a loved one. |
| 2 | A disapproving deity. |
| 3 | A harsh instructor or superior. |
| 4 | The viewer at their lowest point in life. |
^chain-devil-masks

```ad-statblock
title: Chain Devil
![](2-Mechanics/CLI/bestiary/fiend/token/chain-devil-xmm.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 15 
- **Hit Points** 85 (`10d8 + 40`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|18 (+4)|11 (+0)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7, Wisdom +4
- **Skills** ⏤
- **Senses** darkvision 120 ft. (unimpeded by magical darkness), passive Perception 11
- **Damage Resistances** bludgeoning, cold, piercing, slashing
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal; telepathy 120 ft.
- **Challenge** 8

## Traits

***Diabolical Restoration.*** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere in the Nine Hells.

***Magic Resistance.*** The devil has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The devil makes two Chain attacks and uses Conjure Infernal Chain.

***Chain.*** *Melee Attack Roll:* `+7`, reach 10 ft. *Hit:* 11 (`2d6 + 4`) Slashing damage. If the target is a Large or smaller creature, it has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14) from one of two chains, and it has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the grapple ends.

***Conjure Infernal Chain.*** The devil conjures a fiery chain to bind a creature. *Dexterity Saving Throw:* DC 15, one creature the devil can see within 60 feet. *Failure:* 9 (`2d4 + 4`) Fire damage, and the target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the end of the devil's next turn, at which point the chain disappears. If the target is Large or smaller, the devil moves the target up to 30 feet straight toward itself. *Success:* The chain disappears.

## Reactions

***Unnerving Gaze.*** Trigger: A creature the devil can see starts its turn within 30 feet of the devil and can see the devil. _Response—_*Wisdom Saving Throw:* DC 15, the triggering creature. *Failure:* The target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the end of its turn. *Success:* The target is immune to this devil's Unnerving Gaze for 24 hours.
```
^statblock

## Environment

planar, nine hells