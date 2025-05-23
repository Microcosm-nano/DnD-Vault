---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/monstrosity
aliases: ["Stirge"]
---
# Stirge
*Source: Monster Manual (2024) p. 299. Available in the Free Rules (2024)*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/stirges.webp#right)

A single stirge is usually little more than an annoyance, but several can be deadly if they attach faster than a victim can remove them.

## Stirges

*Notorious, Clinging Bloodsuckers*

- **Habitat.** Desert, Forest, Grassland, Hill, Mountain, Swamp, Underdark, Urban  
- **Treasure.** None  

Stirges are bat-size vermin with dagger-length proboscises that attach to other creatures and drain life from them. Stirges are most active at night and hide in shadowy places during the day. If disturbed, they take flight and defend themselves. Roll on or choose a result from the Stirge Roosts table to inspire where stirges might lurk.

**Stirge Roosts**

`dice: [](stirge-xmm.md#^stirge-roosts)`

| dice: 1d4 | Between Hunts, the Stirge Lurks In... |
|-----------|---------------------------------------|
| 1 | The attic or furniture of a ruined building. |
| 2 | A cave or narrow crevice. |
| 3 | A hollow tree or thicket. |
| 4 | The remains of a gigantic, dead creature. |
^stirge-roosts

## Statblock

```ad-statblock
title: Stirge
![](2-Mechanics/CLI/bestiary/monstrosity/token/stirge-xmm.webp#token)
*Tiny monstrosity, Unaligned*

- **Armor Class** 13 
- **Hit Points** 5 (`2d4`) 
- **Speed** 10 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|16 (+3)|11 (+0)| 2 (-4)| 8 (-1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Languages** —
- **Challenge** 1/8

## Actions

***Proboscis.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 6 (`1d6 + 3`) Piercing damage, and the stirge attaches to the target. While attached, the stirge can't make Proboscis attacks, and the target takes 5 (`2d4`) Necrotic damage at the start of each of the stirge's turns.

The stirge can detach itself by spending 5 feet of its movement. The target or a creature within 5 feet of it can detach the stirge as an action.
```
^statblock

## Environment

desert, forest, grassland, hill, mountain, swamp, underdark, urban