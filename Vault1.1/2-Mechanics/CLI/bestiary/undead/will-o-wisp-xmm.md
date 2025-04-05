---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead
aliases: ["Will-o'-Wisp"]
---
# Will-o'-Wisp
*Source: Monster Manual (2024) p. 333*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/will-o-wisp.webp#right)

## Will-o'-Wisp

*Guide on the Path to Doom*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** None  

From a distance, will-o'-wisps look like lanterns bobbing in the dark. Through the windows of abandoned structures or around the bends of treacherous paths, these spirits tempt the curious into peril. Once their prey is vulnerable, will-o'-wisps feed on the life force of those they lay low.

Roll on or choose a result from the Will-o'-Wisp Ambushes table to inspire how a will-o'-wisp imperils its victims.

**Will-o'-Wisp Ambushes**

`dice: [](will-o-wisp-xmm.md#^will-o-wisp-ambushes)`

| dice: 1d6 | The Will-o'-Wisp Tempts Victims Into... |
|-----------|-----------------------------------------|
| 1 | An abandoned structure ready to collapse. |
| 2 | An ambush by hungry ghouls or vampires. |
| 3 | A dreaded ruin that curses those who enter. |
| 4 | The lair of a predator, like a bear or wyvern. |
| 5 | Patches of brown mold or green slime. |
| 6 | Quicksand or pools covered in thin ice. |
^will-o-wisp-ambushes

```ad-statblock
title: Will-o'-Wisp
![](2-Mechanics/CLI/bestiary/undead/token/will-o-wisp-xmm.webp#token)
*Tiny undead, Chaotic Evil*

- **Armor Class** 19 
- **Hit Points** 27 (`11d4`) 
- **Speed** 5 ft., fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|28 (+9)|10 (+0)|13 (+1)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** acid, bludgeoning, cold, fire, necrotic, piercing, slashing
- **Damage Immunities** lightning, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common plus one other language
- **Challenge** 2

## Traits

***Ephemeral.*** The wisp can't wear or carry anything.

***Illumination.*** The wisp sheds [Bright Light](2-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md) in a 20-foot radius and [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) for an additional 20 feet.

***Incorporeal Movement.*** The wisp can move through other creatures and objects as if they were [Difficult Terrain](2-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md). It takes 5 (`1d10`) Force damage if it ends its turn inside an object.

## Actions

***Shock.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 11 (`2d8 + 2`) Lightning damage.

## Bonus Actions

***Consume Life.*** *Constitution Saving Throw:* DC 10, one living creature the wisp can see within 5 feet that has 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). *Failure:* The target dies, and the wisp regains 10 (`3d6`) [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

***Vanish.*** The wisp and its light have the [Invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) condition until the wisp's [Concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends on this effect, which ends early immediately after the wisp makes an attack roll or uses Consume Life.
```
^statblock

## Environment

forest, swamp, urban