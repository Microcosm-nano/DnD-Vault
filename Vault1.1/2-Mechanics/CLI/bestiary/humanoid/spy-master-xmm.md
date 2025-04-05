---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Spy Master"]
---
# Spy Master
*Source: Monster Manual (2024) p. 295*  
![](2-Mechanics/CLI/bestiary/humanoid/img/spies.webp#right)

Spy masters have extensive experience in gathering secrets while leaving no evidence of their presence.

## Spies

*Infiltrators and Informants*

- **Habitat.** Any  
- **Treasure.** Implements, Individual  

Spies gather information and disseminate lies, manipulating people to gain the results the spies' patrons desire. They're trained to manipulate, infiltrate, and—when necessary—escape in a hurry. Many adopt disguises, aliases, or code names to maintain anonymity. Roll on or choose a result from the Spy Personas table to inspire a spy's disguise.

**Spy Personas**

`dice: [](spy-master-xmm.md#^spy-personas)`

| dice: 1d4 | The Spy Disguises Themself As... |
|-----------|----------------------------------|
| 1 | A bard or traveling performer. |
| 2 | A captive or servant of a monster or villain. |
| 3 | A dignitary or traveler from a distant land. |
| 4 | A visitor from a different time or world. |
^spy-personas

## Statblock

```ad-statblock
title: Spy Master
![](2-Mechanics/CLI/bestiary/humanoid/token/spy-master-xmm.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 19 
- **Hit Points** 137 (`25d8 + 25`) 
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|20 (+5)|12 (+1)|18 (+4)|16 (+3)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Constitution +5, Intelligence +8, Wisdom +7
- **Skills** Deception +7, Insight +7, Investigation +8, Perception +11, Sleight of Hand +9, Stealth +13
- **Senses** passive Perception 21
- **Languages** Common plus two other languages
- **Challenge** 10

## Actions

***Multiattack.*** The spy makes three attacks, using Rapier or Hand Crossbow in any combination.

***Rapier.*** *Melee Attack Roll:* `+9`, reach 5 ft. *Hit:* 14 (`2d8 + 5`) Piercing damage plus 7 (`2d6`) Poison damage.

***Hand Crossbow.*** *Ranged Attack Roll:* `+9`, range 30/120 ft. *Hit:* 12 (`2d6 + 5`) Piercing damage plus 9 (`2d8`) Poison damage.

***Smoke Bomb (1/Day).*** The spy throws a bomb to a point it can see within 30 feet of itself. *Constitution Saving Throw:* DC 16, each creature in a 20-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on that point. *Failure:* 28 (`8d6`) Poison damage, and the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the end of the spy's next turn. *Success:* Half damage only.

## Bonus Actions

***Cunning Action.*** The spy takes the Dash, Disengage, or Hide action.
```
^statblock

## Environment

any