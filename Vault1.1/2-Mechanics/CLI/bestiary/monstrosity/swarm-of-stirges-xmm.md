---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
aliases: ["Swarm of Stirges"]
---
# Swarm of Stirges
*Source: Monster Manual (2024) p. 299*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/stirges.webp#right)

Swarms of stirges sometimes form in swamps and Underdark caverns, draining livestock and any other creatures that can't escape them.

## Stirges

*Notorious, Clinging Bloodsuckers*

- **Habitat.** Desert, Forest, Grassland, Hill, Mountain, Swamp, Underdark, Urban  
- **Treasure.** None  

Stirges are bat-size vermin with dagger-length proboscises that attach to other creatures and drain life from them. Stirges are most active at night and hide in shadowy places during the day. If disturbed, they take flight and defend themselves. Roll on or choose a result from the Stirge Roosts table to inspire where stirges might lurk.

**Stirge Roosts**

`dice: [](swarm-of-stirges-xmm.md#^stirge-roosts)`

| dice: 1d4 | Between Hunts, the Stirge Lurks In... |
|-----------|---------------------------------------|
| 1 | The attic or furniture of a ruined building. |
| 2 | A cave or narrow crevice. |
| 3 | A hollow tree or thicket. |
| 4 | The remains of a gigantic, dead creature. |
^stirge-roosts

## Statblock

```ad-statblock
title: Swarm of Stirges
![](2-Mechanics/CLI/bestiary/monstrosity/token/swarm-of-stirges-xmm.webp#token)
*Medium monstrosity, Unaligned*

- **Armor Class** 14 
- **Hit Points** 36 (`8d8`) 
- **Speed** 10 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|16 (+3)|11 (+0)| 2 (-4)| 8 (-1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Resistances** bludgeoning, piercing, slashing
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 2

## Traits

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny creature. The swarm can't regain [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) or gain [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md).

## Actions

***Swarm of Proboscises.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 14 (`2d10 + 3`) Piercing damage, or 8 (`1d10 + 3`) Piercing damage if the swarm is [Bloodied](2-Mechanics/CLI/rules/variant-rules/bloodied-xphb.md). If the target is a Medium or smaller creature in the swarm's space, the target has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 13). Until the grapple ends, the target takes 7 (`2d6`) Necrotic damage at the end of each of its turns.
```
^statblock

## Environment

desert, forest, grassland, hill, mountain, swamp, underdark, urban