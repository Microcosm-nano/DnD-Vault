---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
aliases: ["Iron Golem"]
---
# Iron Golem
*Source: Monster Manual (2024) p. 181*  
![](2-Mechanics/CLI/bestiary/construct/img/iron-golem.webp#right)

## Iron Golem

*Guardian of That Which Must Endure*

- **Habitat.** Any  
- **Treasure.** Any  

Their magical cores protected by mighty armor, iron golems defend important sites and objects. These golems are forged in bipedal forms, the details of which are decided by their creators. Many resemble armored guardians or legendary heroes. Iron golems confront their foes with a combination of overwhelming physical force and eruptions from their magical core. These magical blasts take the form of fiery bolts and poisonous emissions.

Iron golems preserve and protect their charges for generations. Roll on or choose a result from the Iron Golem Orders table to inspire what commands an iron golem follows.

**Iron Golem Orders**

`dice: [](iron-golem-xmm.md#^iron-golem-orders)`

| dice: 1d4 | The Iron Golem Follows Orders To... |
|-----------|-------------------------------------|
| 1 | Block a door that has never been opened, moving only when a prophecy is fulfilled. |
| 2 | Exhale poison gas whenever it can, pausing only when someone speaks a passphrase. |
| 3 | Pose as a statue until a community's hour of greatest need. |
| 4 | Stand atop the resting place of a powerful magic item. |
^iron-golem-orders

```ad-statblock
title: Iron Golem
![](2-Mechanics/CLI/bestiary/construct/token/iron-golem-xmm.webp#token)
*Large construct, Unaligned*

- **Armor Class** 20 
- **Hit Points** 252 (`24d10 + 120`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)| 9 (-1)|20 (+5)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common plus two other languages but can't speak
- **Challenge** 16

## Traits

***Fire Absorption.*** Whenever the golem is subjected to Fire damage, it regains a number of [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to the Fire damage dealt.

***Immutable Form.*** The golem can't shape-shift.

***Magic Resistance.*** The golem has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination.

***Bladed Arm.*** *Melee Attack Roll:* `+12`, reach 10 ft. *Hit:* 20 (`3d8 + 7`) Slashing damage plus 10 (`3d6`) Fire damage.

***Fiery Bolt.*** *Ranged Attack Roll:* `+10`, range 120 ft. *Hit:* 36 (`8d8`) Fire damage.

***Poison Breath (Recharge 6).*** *Constitution Saving Throw:* DC 18, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 55 (`10d10`) Poison damage. *Success:* Half damage.
```
^statblock

## Environment

any