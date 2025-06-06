---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
aliases: ["Storm Giant"]
---
# Storm Giant
*Source: Monster Manual (2024) p. 302*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/storm-giant.webp#right)

## Storm Giant

*Giant of Seas and Skies*

- **Habitat.** Coastal, Underwater  
- **Treasure.** Armaments  

Among the tallest giants, storm giants live amid extreme forces of nature. In palaces at the bottom of the sea and castles floating amid the clouds, they revel in the power of mighty storms. When angered, they can shape the weather and call down devastating lightning. More often, though, these giants watch the rise and fall of nations and interpret supernatural omens, interfering in the world only when they're needed most.

```ad-statblock
title: Storm Giant
![](2-Mechanics/CLI/bestiary/giant/token/storm-giant-xmm.webp#token)
*Huge giant, Chaotic Good*

- **Armor Class** 16 
- **Hit Points** 230 (`20d12 + 100`) 
- **Speed** 50 ft., fly 25 ft. (hover), swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|14 (+2)|20 (+5)|16 (+3)|20 (+5)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +14, Constitution +10, Wisdom +10, Charisma +9
- **Skills** Arcana +8, Athletics +14, History +8, Perception +10
- **Senses** darkvision 120 ft., truesight 30 ft., passive Perception 20
- **Damage Resistances** cold
- **Damage Immunities** lightning, thunder
- **Languages** Common, Giant
- **Challenge** 13

## Traits

***Amphibious.*** The giant can breathe air and water.

***Spellcasting.*** The giant casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 18):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Light](2-Mechanics/CLI/spells/light-xphb.md)

**1/day**: [Control Weather](2-Mechanics/CLI/spells/control-weather-xphb.md)

## Actions

***Multiattack.*** The giant makes two attacks, using Storm Sword or Thunderbolt in any combination.

***Storm Sword.*** *Melee Attack Roll:* `+14`, reach 10 ft. *Hit:* 23 (`4d6 + 9`) Slashing damage plus 13 (`3d8`) Lightning damage.

***Thunderbolt.*** *Ranged Attack Roll:* `+14`, range 500 ft. *Hit:* 22 (`2d12 + 9`) Lightning damage, and the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [Deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) conditions until the start of the giant's next turn.

***Lightning Storm (Recharge 5-6).*** *Dexterity Saving Throw:* DC 18, each creature in a 10-foot-radius, 40-foot-high [Cylinder](2-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md) originating from a point the giant can see within 500 feet. *Failure:* 55 (`10d10`) Lightning damage. *Success:* Half damage.
```
^statblock

## Environment

coastal, underwater