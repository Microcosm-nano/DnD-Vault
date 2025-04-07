---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
aliases: ["Warhorse Skeleton"]
---
# Warhorse Skeleton
*Source: Monster Manual (2024) p. 282*  
![Adventurers face an onslau...](2-Mechanics/CLI/bestiary/undead/img/skeletons.webp#right "Adventurers face an onslaught from all manner of skeletons")

Warhorse skeletons are obedient, supernatural steeds bearing the rotted remains of the barding they wore in life. They're often ridden by the corpses of their former riders.

## Skeletons

*Ossified Evil*

- **Habitat.** Planar (Shadowfell), Underdark, Urban  
- **Treasure.** None  

Skeletons rise at the summons of necromancers and foul spirits. Whether they're the remains of the ancient dead or fresh bones bound to morbid ambitions, they commit deathless work for whatever forces reanimated them, often serving as guardians, soldiers, or laborers. In rare cases, skeletons are reanimated but given no particular direction. Roll on or choose a result from the Skeleton Pantomimes table to inspire how undirected skeletons behave.

**Skeleton Pantomimes**

`dice: [](warhorse-skeleton-xmm.md#^skeleton-pantomimes)`

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
title: Warhorse Skeleton
![](2-Mechanics/CLI/bestiary/undead/token/warhorse-skeleton-xmm.webp#token)
*Large undead, Lawful Evil*

- **Armor Class** 13 
- **Hit Points** 22 (`3d10 + 6`) 
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|15 (+2)| 2 (-4)| 8 (-1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 1/2

## Actions

***Hooves.*** *Melee Attack Roll:* `+6`, reach 5 ft. *Hit:* 7 (`1d6 + 4`) Bludgeoning damage. If the target is a Large or smaller creature and the skeleton moved 20+ feet straight toward it immediately before the hit, the target has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.
```
^statblock

## Environment

planar, shadowfell, underdark, urban