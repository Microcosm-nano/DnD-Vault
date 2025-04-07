---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Flaming Skeleton"]
---
# Flaming Skeleton
*Source: Monster Manual (2024) p. 283*  
![Adventurers face an onslau...](2-Mechanics/CLI/bestiary/undead/img/skeletons.webp#right "Adventurers face an onslaught from all manner of skeletons")

Flaming skeletons burn with unbridled necromantic energy. This magic grants them blazing attacks and greater awareness, which they use to command lesser Undead.

## Skeletons

*Ossified Evil*

- **Habitat.** Planar (Shadowfell), Underdark, Urban  
- **Treasure.** None  

Skeletons rise at the summons of necromancers and foul spirits. Whether they're the remains of the ancient dead or fresh bones bound to morbid ambitions, they commit deathless work for whatever forces reanimated them, often serving as guardians, soldiers, or laborers. In rare cases, skeletons are reanimated but given no particular direction. Roll on or choose a result from the Skeleton Pantomimes table to inspire how undirected skeletons behave.

**Skeleton Pantomimes**

`dice: [](flaming-skeleton-xmm.md#^skeleton-pantomimes)`

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
title: Flaming Skeleton
![](2-Mechanics/CLI/bestiary/undead/token/flaming-skeleton-xmm.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 15 
- **Hit Points** 65 (`10d8 + 20`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|15 (+2)|10 (+0)|15 (+2)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common plus one other language but can't speak
- **Challenge** 3

## Traits

***Death Burst.*** The skeleton explodes when it dies. *Dexterity Saving Throw:* DC 12, each creature in a 10-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the skeleton. *Failure:* 14 (`4d6`) Fire damage. *Success:* Half damage.

***Illumination.*** The skeleton sheds [Bright Light](2-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md) in a 15-foot radius and [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) for an additional 15 feet.

## Actions

***Multiattack.*** The skeleton makes two attacks, using Flame Scepter or Hurl Flame in any combination.

***Flame Scepter.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 5 (`1d6 + 2`) Bludgeoning damage plus 3 (`1d6`) Fire damage.

***Hurl Flame.*** *Ranged Attack Roll:* `+4`, range 60 ft. *Hit:* 7 (`1d10 + 2`) Fire damage.
```
^statblock

## Environment

planar, shadowfell, underdark, urban