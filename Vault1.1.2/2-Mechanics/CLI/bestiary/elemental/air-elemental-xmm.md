---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/air
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
aliases: ["Air Elemental"]
---
# Air Elemental
*Source: Monster Manual (2024) p. 13*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/air-elemental.webp#right)

## Air Elemental

*Primal Spirit of Wind and Storm*

- **Habitat.** Desert, Mountain, Planar (Elemental Plane of Air)  
- **Treasure.** None  

Energetic spirits from the Elemental Plane of Air, air elementals gather clouds and winds into ever-changing bodies with indistinct limbs and vague features. Beyond their home plane, these elementals might serve magic-users who conjure them, or they might congregate around nexuses of unbridled planar energy, such as wind-scoured mountain peaks or endless storms. In battle, air elementals batter enemies with powerful gusts or transform into whirlwinds to fling away foes.

Air elementals often have distinctive compositions. Roll on or choose a result from the Air Elemental Compositions table to inspire the elemental's appearance.

> [!quote] A quote from Husam, Son of the Breezes, Ruler of Djinn  
> 
> What can withstand the storm's scream? The lightning's spear? The want of sweet breath? Air is the mightiest of elements—respect its power.

**Air Elemental Compositions**

`dice: [](air-elemental-xmm.md#^air-elemental-compositions)`

| dice: 1d6 | The Air Elemental's Body Features... |
|-----------|--------------------------------------|
| 1 | Cumulus or cirrus clouds. |
| 2 | A mixture of vibrantly colored gases. |
| 3 | A pungent, sour-looking miasma |
| 4 | Shifting cloud clusters that resemble animals and simple shapes. |
| 5 | Sinister features obscured in a misty mass. |
| 6 | Swirling storm clouds. |
^air-elemental-compositions

```ad-statblock
title: Air Elemental
![](2-Mechanics/CLI/bestiary/elemental/token/air-elemental-xmm.webp#token)
*Large elemental, Neutral*

- **Armor Class** 15 
- **Hit Points** 90 (`12d10 + 24`) 
- **Speed** 10 ft., fly 90 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|20 (+5)|14 (+2)| 6 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, lightning, piercing, slashing
- **Damage Immunities** poison, thunder
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Primordial (Auran)
- **Challenge** 5

## Traits

***Air Form.*** The elemental can enter a creature's space and stop there. It can move through a space as narrow as 1 inch without expending extra movement to do so.

## Actions

***Multiattack.*** The elemental makes two Thunderous Slam attacks.

***Thunderous Slam.*** *Melee Attack Roll:* `+8`, reach 10 ft. *Hit:* 14 (`2d8 + 5`) Thunder damage.

***Whirlwind (Recharge 4-6).*** *Strength Saving Throw:* DC 13, one Medium or smaller creature in the elemental's space. *Failure:* 24 (`4d10 + 2`) Thunder damage, and the target is pushed up to 20 feet straight away from the elemental and has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. *Success:* Half damage only.
```
^statblock

## Environment

desert, mountain, planar, air