---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Ghost"]
---
# Ghost
*Source: Monster Manual (2024) p. 131*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/ghost.webp#right)

## Ghost

*Lost Soul and Unquiet Spirit*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Ghosts arise when living creatures die in a state of extreme emotion or having left an important task undone. These incorporeal spirits haunt locations that are meaningful to them, lingering until their business is complete or they're put to rest.

Ghosts typically appear as semitransparent versions of the creatures they were in life, though some bear evidence of the wounds that killed them or have nightmarish distortions to their forms. Many have extreme reactions to actions, objects, or individuals that remind them of emotionally charged aspects of their lives. Particularly desperate or vengeful ghosts might possess the living to fulfill their ends.

```ad-statblock
title: Ghost
![](2-Mechanics/CLI/bestiary/undead/token/ghost-xmm.webp#token)
*Medium undead, Neutral*

- **Armor Class** 11 
- **Hit Points** 45 (`10d8`) 
- **Speed** 5 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|13 (+1)|10 (+0)|10 (+0)|12 (+1)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid, bludgeoning, cold, fire, lightning, piercing, slashing, thunder
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common plus one other language
- **Challenge** 4

## Traits

***Ethereal Sight.*** The ghost can see 60 feet into the Ethereal Plane when it is on the Material Plane.

***Incorporeal Movement.*** The ghost can move through other creatures and objects as if they were [Difficult Terrain](2-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md). It takes 5 (`1d10`) Force damage if it ends its turn inside an object.

***Etherealness.*** The ghost casts the [Etherealness](2-Mechanics/CLI/spells/etherealness-xphb.md) spell, requiring no spell components and using Charisma as the spellcasting ability. The ghost is visible on the Material Plane while on the Border Ethereal and vice versa, but it can't affect or be affected by anything on the other plane.

**At will**: [Etherealness](2-Mechanics/CLI/spells/etherealness-xphb.md)

## Actions

***Multiattack.*** The ghost makes two Withering Touch attacks.

***Withering Touch.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 19 (`3d10 + 3`) Necrotic damage.

***Horrific Visage.*** *Wisdom Saving Throw:* DC 13, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md) that can see the ghost and isn't an Undead. *Failure:* 10 (`2d6 + 3`) Psychic damage, and the target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the ghost's next turn. *Success:* The target is immune to this ghost's Horrific Visage for 24 hours.

***Possession (Recharge 6).*** *Charisma Saving Throw:* DC 13, one Humanoid the ghost can see within 5 feet. *Failure:* The target is possessed by the ghost; the ghost disappears, and the target has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition and loses control of its body. The ghost now controls the body, but the target retains awareness. The ghost can't be targeted by any attack, spell, or other effect, except ones that specifically target Undead. The ghost's game statistics are the same, except it uses the possessed target's [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), as well as the target's Strength, Dexterity, and Constitution modifiers.

The possession lasts until the body drops to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) or the ghost leaves as a [Bonus Action](2-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md). When the possession ends, the ghost appears in an unoccupied space within 5 feet of the target, and the target is immune to this ghost's [Possession](2-Mechanics/CLI/rules/variant-rules/possession-xphb.md) for 24 hours. *Success:* The target is immune to this ghost's [Possession](2-Mechanics/CLI/rules/variant-rules/possession-xphb.md) for 24 hours.
```
^statblock

## Environment

underdark, urban