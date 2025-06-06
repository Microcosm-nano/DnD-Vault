---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Ghoul"]
---
# Ghoul
*Source: Monster Manual (2024) p. 132*  
![](2-Mechanics/CLI/bestiary/undead/img/ghouls.webp#right)

Ghouls rise from the bodies of cannibals and villains with depraved hungers. They form packs out of shared voracity.

## Ghouls

*Eaters of the Dead*

- **Habitat.** Swamp, Underdark, Urban  
- **Treasure.** Any  

Packs of ghouls haunt the rotten corners of the world, ravenously hunting for corpses and those soon to be corpses. These gaunt, animate cadavers with unnaturally long tongues dwell in catacombs and ruins where they devour the contents of graves and paralyze foes with vicious claws.

> [!quote]  
> 
> On a plain of teeth, in a temple of filth, the starving king wastes no morsel. Every coffin a banquet. Every slab a platter. Now is the time of feasting!


## Statblock

```ad-statblock
title: Ghoul
![](2-Mechanics/CLI/bestiary/undead/token/ghoul-xmm.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12 
- **Hit Points** 22 (`5d8`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|15 (+2)|10 (+0)| 7 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 1

## Actions

***Multiattack.*** The ghoul makes two Bite attacks.

***Bite.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 5 (`1d6 + 2`) Piercing damage plus 3 (`1d6`) Necrotic damage.

***Claw.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 4 (`1d4 + 2`) Slashing damage. If the target is a creature that isn't an Undead or elf, it is subjected to the following effect. *Constitution Saving Throw:* DC 10. *Failure:* The target has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the end of its next turn.
```
^statblock

## Environment

swamp, underdark, urban