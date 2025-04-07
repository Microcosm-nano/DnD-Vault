---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
aliases: ["Centaur Warden"]
---
# Centaur Warden
*Source: Monster Manual (2024) p. 67*  
![](2-Mechanics/CLI/bestiary/fey/img/centaurs.webp#right)

Centaur wardens often lead groups of centaur troopers and act as intermediaries between Fey creatures and trespassers into their territories.

## Centaurs

*Defenders of the Feywild*

- **Habitat.** Forest, Grassland, Planar (Feywild)  
- **Treasure.** Armaments, Individual  

Centaurs are defenders of forests, plains, and sites of primeval power. With upper bodies like humans' and the lower bodies of horses, centaurs charge into battle against those who would harm their allies.

## Statblock

```ad-statblock
title: Centaur Warden
![](2-Mechanics/CLI/bestiary/fey/token/centaur-warden-xmm.webp#token)
*Large fey, Neutral Good*

- **Armor Class** 16 
- **Hit Points** 105 (`14d10 + 28`) 
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|14 (+2)| 9 (-1)|18 (+4)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Wisdom +7
- **Skills** Athletics +7, Nature +5, Perception +7
- **Senses** passive Perception 17
- **Languages** Druidic, Elvish, Sylvan
- **Challenge** 7

***Spellcasting.*** The centaur casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 15):

**At will**: [Druidcraft](2-Mechanics/CLI/spells/druidcraft-xphb.md), [Speak with Animals](2-Mechanics/CLI/spells/speak-with-animals-xphb.md)

## Actions

***Multiattack.*** The centaur makes two attacks, using Forest Staff or Sun Ray in any combination.

***Forest Staff.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 13 (`2d8 + 4`) Bludgeoning damage plus 14 (`4d6`) Poison damage.

***Sun Ray.*** *Ranged Attack Roll:* `+7`, range 90 ft. *Hit:* 14 (`3d6 + 4`) Radiant damage, and the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the start of the centaur's next turn.

## Bonus Actions

***Entangling Trail (Recharge 5-6).*** The centaur moves up to its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) without provoking Opportunity Attacks. Each creature within 5 feet of the centaur as it moves is targeted once by the following effect. *Strength Saving Throw:* DC 15. *Failure:* 11 (`2d6 + 4`) Bludgeoning damage, and the target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the end of its next turn.
```
^statblock

## Environment

forest, grassland, planar, feywild