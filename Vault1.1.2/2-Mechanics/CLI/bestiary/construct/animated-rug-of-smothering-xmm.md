---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
aliases: ["Animated Rug of Smothering"]
---
# Animated Rug of Smothering
*Source: Monster Manual (2024) p. 17*  
![](2-Mechanics/CLI/bestiary/construct/img/animated-objects.webp#right)

Animated rugs of smothering might attack any creature that steps on them, or they might be passed off as superficially similar magic items, such as Carpets of Flying, and attack those who speak a supposed command word. Deadly tapestries, furs, and similar items also use this stat block.

## Animated Objects

*Mundane Objects Come to Life*

- **Habitat.** Urban  
- **Treasure.** None  

Magic can manipulate mundane items, compelling them to perform simple tasks. Such animate objects might be unassuming tools or decorations that can defend their creator. These objects follow simple instructions from whatever force or magic-user created them. If left unattended, they might defend an area for ages or repeat a task until they wear out.

Roll on or choose a result from the Animated Object Catalysts table to inspire what sort of magic motivates an ambulatory item.

> [!quote] A quote from Levity Quickstitch, Rogue  
> 
> Lyin' next to the chest were the bones of Cap'n Scornblade himself, still clutchin' his rusty sword. Imagine my surprise when the blade flew from his bony grasp! Still got the scar.

**Animated Object Catalysts**

`dice: [](animated-rug-of-smothering-xmm.md#^animated-object-catalysts)`

| dice: 1d10 | The Object Was Animated By... |
|------------|-------------------------------|
| 1 | A Celestial or Fiend using the object to protect or torment a mortal. |
| 2 | A combination of magic and technology, such as alchemy or alien science. |
| 3 | The essence of someone transformed by a supernatural trickster. |
| 4 | Fey as part of their games or wiles. |
| 5 | Happenstance, with the item gaining a semblance of life after a hundred years of use. |
| 6 | A magic-user in need of a guardian or servant. |
| 7 | The song of a magical instrument. |
| 8 | A spirit possessing the object. |
| 9 | Wild magic, a spell that went awry, or a chaotic Artifact. |
| 10 | The will of a powerful psychic being. |
^animated-object-catalysts

## Statblock

```ad-statblock
title: Animated Rug of Smothering
![](2-Mechanics/CLI/bestiary/construct/token/animated-rug-of-smothering-xmm.webp#token)
*Large construct, Unaligned*

- **Armor Class** 12 
- **Hit Points** 27 (`5d10`) 
- **Speed** 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|14 (+2)|10 (+0)| 1 (-5)| 3 (-4)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft., passive Perception 6
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 2

## Actions

***Smother.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 10 (`2d6 + 3`) Bludgeoning damage. If the target is a Medium or smaller creature, the rug can give it the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 13) instead of dealing damage. Until the grapple ends, the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, is suffocating, and takes 10 (`2d6 + 3`) Bludgeoning damage at the start of each of its turns. The rug can smother only one creature at a time.

While grappling the target, the rug can't take this action, the rug halves the damage it takes (round down), and the target takes the same amount of damage.
```
^statblock

## Environment

urban