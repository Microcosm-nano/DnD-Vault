---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
aliases: ["Hydra"]
---
# Hydra
*Source: Monster Manual (2024) p. 175*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/hydra.webp#right)

## Hydra

*Multiheaded Serpent of Legend*

- **Habitat.** Coastal, Swamp  
- **Treasure.** Any  

Hydras are storied hero slayers with vicious, serpentine heads and infamous regenerative powers. Endlessly hungry, they devour any creatures they catch. Hydras that deplete an area of prey often go into a lengthy torpor until new prey arrives.

Most hydras have five heads, but some mature or battle-tested hydras have more. Such elder hydras might become local legends, known for their battles with heroes or for the riches lost in their domains.

While many hydras claim their own territories, wicked deities might use them to guard treasures or magical sites. Roll on or choose a result from the Hydra Lairs table to inspire why a hydra lurks where it does.

**Hydra Lairs**

`dice: [](hydra-xmm.md#^hydra-lairs)`

| dice: 1d4 | The Hydra Lurks Where It Does To... |
|-----------|-------------------------------------|
| 1 | Ensure none claim the weapon of a fallen hero. |
| 2 | Defend the home of a wise but sinister oracle. |
| 3 | Guard a magical herb that blooms once a year. |
| 4 | Protect a font of poison that pollutes a river. |
^hydra-lairs

```ad-statblock
title: Hydra
![](2-Mechanics/CLI/bestiary/monstrosity/token/hydra-xmm.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 
- **Hit Points** 184 (`16d12 + 80`) 
- **Speed** 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)| 2 (-4)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** darkvision 60 ft., passive Perception 16
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 8

## Traits

***Hold Breath.*** The hydra can hold its breath for 1 hour.

***Multiple Heads.*** The hydra has five heads. Whenever the hydra takes 25 damage or more on a single turn, one of its heads dies. The hydra dies if all its heads are dead. At the end of each of its turns when it has at least one living head, the hydra grows two heads for each of its heads that died since its last turn, unless it has taken Fire damage since its last turn. The hydra regains 20 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) when it grows new heads.

***Reactive Heads.*** For each head the hydra has beyond one, it gets an extra [Reaction](2-Mechanics/CLI/rules/variant-rules/reaction-xphb.md) that can be used only for Opportunity Attacks.

## Actions

***Multiattack.*** The hydra makes as many Bite attacks as it has heads.

***Bite.*** *Melee Attack Roll:* `+8`, reach 10 ft. *Hit:* 10 (`1d10 + 5`) Piercing damage.
```
^statblock

## Environment

coastal, swamp