---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
aliases: ["Cairnwight"]
---
# Cairnwight
*Source: Bigby Presents: Glory of the Giants p. 122*  
![](2-Mechanics/CLI/bestiary/undead/img/cairnwight.webp#right)

Stone giants believe the god Skoraeus Stonebones inspires artists to create their finest stone carvings. Sometimes a giant pursues this divine inspiration to the exclusion of all other tasks, retreating into a spacious cavern and blocking out all distractions. Creating a masterwork can become such a driving obsession that death can't stop it: a giant who dies while creating art might rise as a cairnwight and continue the work. Once the artwork is completed, the cairnwight remains as its undying guardian.

A cairnwight looks much like an emaciated stone giant. Its form is caked with lichens and mineral deposits, which help it blend with its cavern tomb. Should a creature attempt to interfere with the completion of the cairnwight's project, damage the art, or steal from the cairnwight, the giant petrifies the creature, places the resulting statue outside as a warning, then reseals its cavern vault.

```ad-statblock
title: Cairnwight
![](2-Mechanics/CLI/bestiary/undead/token/cairnwight-bgg.webp#token)
*Huge undead, typically  Neutral*

- **Armor Class** 19 (natural armor)
- **Hit Points** 138 (`12d12 + 60`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|21 (+5)|10 (+0)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +9, Wisdom +5
- **Skills** Athletics +10, Perception +5, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 15
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** Giant
- **Challenge** 9

## Actions

***Multiattack.*** The cairnwight makes two Slam attacks or two Rock attacks, and it uses its Petrifying Touch if available.

***Slam.*** *Melee Weapon Attack:* `+10` to hit, reach 10 ft., one target. *Hit:* 22 (`3d10 + 6`) bludgeoning damage.

***Rock.*** *Ranged Weapon Attack:* `+10` to hit, range 60/240 ft., one target. *Hit:* 19 (`3d8 + 6`) bludgeoning damage, and the target must succeed on a DC 17 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Petrifying Touch (Recharge 5-6).*** The cairnwight touches one creature it can see within 10 feet of itself. The target must succeed on a DC 17 Constitution saving throw or take 26 (`4d12`) force damage and have the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition as it begins to turn to stone. The affected target must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the target. On a failed save, the target has the [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition instead of the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition.
```
^statblock