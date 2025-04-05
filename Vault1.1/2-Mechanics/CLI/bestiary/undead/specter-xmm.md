---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Specter"]
---
# Specter
*Source: Monster Manual (2024) p. 290*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/specter.webp#right)

## Specter

*Spirit of Wrath and Servant of Death*

- **Habitat.** Underdark, Urban  
- **Treasure.** None  

Specters are bodiless, life-devouring spirits drawn to darkness and negative emotions. Having lost all connection to the beings they once were, these hateful spirits drain mortal essence to steal fleeting tastes of life and warmth.

Specters seek creatures and locations that exude evil and feed on the suffering they inspire. Roll on or choose a result from the Specter Haunts table to inspire where a specter lurks.

**Specter Haunts**

`dice: [](specter-xmm.md#^specter-haunts)`

| dice: 1d8 | The Specter Lurks Near... |
|-----------|---------------------------|
| 1 | A community afflicted by curses, grudges, plagues, or tragedies. |
| 2 | An evil Artifact or a deadly magical device. |
| 3 | The lair of a Fiend or an Undead. |
| 4 | The place where a villain died or is buried. |
| 5 | A portal to the Lower Planes, Negative Plane, or Shadowfell. |
| 6 | The sanctuary of a necromancer or death cult. |
| 7 | A secluded monument binding wicked souls. |
| 8 | The site of a disaster or mass death. |
^specter-haunts

```ad-statblock
title: Specter
![](2-Mechanics/CLI/bestiary/undead/token/specter-xmm.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12 
- **Hit Points** 22 (`5d8`) 
- **Speed** 30 ft., fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|14 (+2)|11 (+0)|10 (+0)|10 (+0)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** acid, bludgeoning, cold, fire, lightning, piercing, slashing, thunder
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands Common plus one other language but can't speak
- **Challenge** 1

## Traits

***Incorporeal Movement.*** The specter can move through other creatures and objects as if they were [Difficult Terrain](2-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md). It takes 5 (`1d10`) Force damage if it ends its turn inside an object.

***Sunlight Sensitivity.*** While in sunlight, the specter has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on ability checks and attack rolls.

## Actions

***Life Drain.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 7 (`2d6`) Necrotic damage. If the target is a creature, its [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken.
```
^statblock

## Environment

underdark, urban