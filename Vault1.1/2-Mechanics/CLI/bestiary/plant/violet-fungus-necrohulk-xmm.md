---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
aliases: ["Violet Fungus Necrohulk"]
---
# Violet Fungus Necrohulk
*Source: Monster Manual (2024) p. 126*  
![](2-Mechanics/CLI/bestiary/plant/img/violet-fungus-necrohulk.webp#right)

A violet fungus necrohulk forms when a violet fungus colony infests and animates an ample heap of decay. This necrohulk attacks prey and spreads fungal spores for the colony.

## Fungi

*Deadly Spores and Predatory Polyps*

- **Habitat.** Underdark  
- **Treasure.** None  

The dank, sunless Underdark is a fertile breeding ground for weird and dangerous fungi.

![](2-Mechanics/CLI/bestiary/plant/img/fungi.webp#center)

## Statblock

```ad-statblock
title: Violet Fungus Necrohulk
![](2-Mechanics/CLI/bestiary/plant/token/violet-fungus-necrohulk-xmm.webp#token)
*Large plant, Neutral Evil*

- **Armor Class** 17 
- **Hit Points** 123 (`13d10 + 52`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|12 (+1)|18 (+4)| 7 (-2)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft., passive Perception 12
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 7

## Actions

***Multiattack.*** The necrohulk makes two Rotting Slam attacks.

***Rotting Slam.*** *Melee Attack Roll:* `+7`, reach 10 ft. *Hit:* 9 (`1d10 + 4`) Bludgeoning damage plus 7 (`2d6`) Necrotic damage.

***Spore Bomb (Recharge 5-6).*** *Constitution Saving Throw:* DC 15, each creature in a 20-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the necrohulk can see within 60 feet. *Failure:* 28 (`8d6`) Necrotic damage, and the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of the necrohulk's next turn. While [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the target can't regain [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). *Success:* Half damage only.

## Bonus Actions

***Absorb Body.*** *Strength Saving Throw:* DC 15, one Medium or Small creature the necrohulk can see within 5 feet. *Failure:* The target is pulled into the necrohulk's space and becomes grafted to its body. The necrohulk can have only one target grafted at a time.

While grafted, the target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on Constitution saving throws. When the necrohulk moves, the grafted target moves with it. If the target dies while grafted, its body is destroyed, and the necrohulk regains 10 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

The grafted target or a creature within 5 feet of the necrohulk can take an action to make a DC 15 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check. On a successful check, the target is no longer grafted and moves to an unoccupied space within 5 feet of the necrohulk.
```
^statblock

## Environment

underdark