---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Banshee"]
---
# Banshee
*Source: Monster Manual (2024) p. 29*  
![](2-Mechanics/CLI/bestiary/undead/img/banshee.webp#right)

## Banshee

*Wailing Harbinger of Death*

- **Habitat.** Any  
- **Treasure.** Relics  

Heralds of doom and plagues on the living, banshees are spirits obsessed by unresolved bitterness or sorrow. These storied phantoms slay any who glimpse them or hear their baleful wails. Although any tormented soul can arise as a banshee, some elven communities particularly fear them and believe that those who hoard or destroy beauty—natural or otherwise—risk returning as a banshee.

All manner of torments might give rise to a banshee. Roll on or choose a result from the Banshee Sorrows table to inspire how a banshee's torment influences its behavior.

**Banshee Sorrows**

`dice: [](banshee-xmm.md#^banshee-sorrows)`

| dice: 1d6 | Torment Compels the Banshee To... |
|-----------|-----------------------------------|
| 1 | Appear prior to a family member's death. |
| 2 | Haunt the site where it was executed. |
| 3 | Lament a lost love and haunt their grave. |
| 4 | Presage a disaster or tragedy. |
| 5 | Seek the return of a stolen treasure. |
| 6 | Slay those more beautiful than it was in life. |
^banshee-sorrows

```ad-statblock
title: Banshee
![](2-Mechanics/CLI/bestiary/undead/token/banshee-xmm.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12 
- **Hit Points** 54 (`12d8`) 
- **Speed** 5 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|14 (+2)|10 (+0)|12 (+1)|11 (+0)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** acid, bludgeoning, fire, lightning, piercing, slashing, thunder
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Elvish
- **Challenge** 4

## Traits

***Detect Life.*** The banshee magically senses the direction of creatures up to 1 mile away that aren't Constructs or Undead.

***Incorporeal Movement.*** The banshee can move through other creatures and objects as if they were [Difficult Terrain](2-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md). It takes 5 (`1d10`) Force damage if it ends its turn inside an object.

## Actions

***Multiattack.*** The banshee makes two Corrupting Touch attacks and uses Horrify.

***Corrupting Touch.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 7 (`1d8 + 3`) Necrotic damage.

***Horrify.*** *Wisdom Saving Throw:* DC 13, one creature the banshee can see within 60 feet that can see the banshee. *Failure:* The target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the banshee's next turn. *Success:* The target is immune to this banshee's Horrify for 24 hours.

***Deathly Wail (1/Day).*** The banshee releases a mournful wail if it isn't in sunlight. *Constitution Saving Throw:* DC 13, each creature within 30 feet that can hear the wail and isn't a Construct or an Undead. *Failure:* If the target has 25 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) or fewer, it drops to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). Otherwise, the target takes 10 (`3d6`) Psychic damage.
```
^statblock

## Environment

any