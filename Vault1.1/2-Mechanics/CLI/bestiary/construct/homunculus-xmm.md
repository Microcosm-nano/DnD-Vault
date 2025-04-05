---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
aliases: ["Homunculus"]
---
# Homunculus
*Source: Monster Manual (2024) p. 172*  
![Homunculi are as varied as...](2-Mechanics/CLI/bestiary/construct/img/homunculus.webp#right "Homunculi are as varied as the magic-users who create them")

## Homunculus

*Winged Servant Given Magical Life*

- **Habitat.** Any  
- **Treasure.** None  

A mage can create a cat-sized, obedient assistant called a homunculus through a ritual that uses the mage's blood. Each homunculus shares a telepathic bond with the mage who created it and loyally serves its creator. A homunculus is reduced to inert material if its creator dies.

A homunculus's appearance reflects its creator's tastes. Roll on or choose a result from the Homunculus Features table to inspire a homunculus's form.

**Homunculus Features**

`dice: [](homunculus-xmm.md#^homunculus-features)`

| dice: 1d8 | The Homunculus Has Features That Are... |
|-----------|-----------------------------------------|
| 1 | Bat-like with tattered wings. |
| 2 | Made of soft metal and delicate gears. |
| 3 | Marked with its creator's symbol. |
| 4 | Similar to those of a winged humanoid. |
| 5 | Sprouting flowers and leaves. |
| 6 | Suggestive of its creator's appearance. |
| 7 | Underdeveloped and fleshy with beady eyes. |
| 8 | Woven and patchwork, like a well-loved toy. |
^homunculus-features

```ad-statblock
title: Homunculus
![](2-Mechanics/CLI/bestiary/construct/token/homunculus-xmm.webp#token)
*Tiny construct, Neutral*

- **Armor Class** 13 
- **Hit Points** 4 (`1d4 + 2`) 
- **Speed** 20 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|15 (+2)|14 (+2)|10 (+0)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2, Charisma +0
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common plus one other language but can't speak
- **Challenge** 0

## Traits

***Telepathic Bond.*** While the homunculus is on the same plane of existence as its master, the two of them can communicate telepathically with each other.

## Actions

***Bite.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 1 Piercing damage, and the target is subjected to the following effect. *Constitution Saving Throw:* DC 12. *Failure:* The target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of the homunculus's next turn. Failure by 5 or More: The target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. While [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the target has the [Unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition, which ends early if the target takes any damage.
```
^statblock

## Environment

any