---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
aliases: ["Minotaur Skeleton"]
---
# Minotaur Skeleton
*Source: Monster Manual (2024) p. 283*  
![Adventurers face an onslau...](2-Mechanics/CLI/bestiary/undead/img/skeletons.webp#right "Adventurers face an onslaught from all manner of skeletons")

Minotaur skeletons are the reanimated remains of minotaurs or the skeletons of multiple creatures merged into a minotaur-like shape. These hulking skeletons have greater speed and might than smaller skeletons. They menace the living with their horns and mighty greataxes.

## Skeletons

*Ossified Evil*

- **Habitat.** Planar (Shadowfell), Underdark, Urban  
- **Treasure.** None  

Skeletons rise at the summons of necromancers and foul spirits. Whether they're the remains of the ancient dead or fresh bones bound to morbid ambitions, they commit deathless work for whatever forces reanimated them, often serving as guardians, soldiers, or laborers. In rare cases, skeletons are reanimated but given no particular direction. Roll on or choose a result from the Skeleton Pantomimes table to inspire how undirected skeletons behave.

**Skeleton Pantomimes**

`dice: [](minotaur-skeleton-xmm.md#^skeleton-pantomimes)`

| dice: 1d6 | Left to Its Own Devices, the Skeleton... |
|-----------|------------------------------------------|
| 1 | Delivers meal salvers or ages-old correspondence to the crypt of its dead master. |
| 2 | Endlessly trains in battle with other skeletons, despite being hacked to animate splinters. |
| 3 | Mimics ways it entertained itself in life, such as acting, dancing, or reading. |
| 4 | Performs a familiar task, such as cleaning, cooking, mining, or praying. |
| 5 | Repeats its final moments of life. |
| 6 | Stands guard at the post it protected in life. |
^skeleton-pantomimes

## Statblock

```ad-statblock
title: Minotaur Skeleton
![](2-Mechanics/CLI/bestiary/undead/token/minotaur-skeleton-xmm.webp#token)
*Large undead, Lawful Evil*

- **Armor Class** 12 
- **Hit Points** 45 (`6d10 + 12`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|15 (+2)| 6 (-2)| 8 (-1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Abyssal but can't speak
- **Challenge** 2

## Actions

***Gore.*** *Melee Attack Roll:* `+6`, reach 5 ft. *Hit:* 11 (`2d6 + 4`) Piercing damage. If the target is a Large or smaller creature and the skeleton moved 20+ feet straight toward it immediately before the hit, the target takes an extra 9 (`2d8`) Piercing damage and has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Slam.*** *Melee Attack Roll:* `+6`, reach 5 ft. *Hit:* 15 (`2d10 + 4`) Bludgeoning damage.
```
^statblock

## Environment

planar, shadowfell, underdark, urban