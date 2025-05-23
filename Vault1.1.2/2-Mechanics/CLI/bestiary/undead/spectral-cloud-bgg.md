---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
aliases: ["Spectral Cloud"]
---
# Spectral Cloud
*Source: Bigby Presents: Glory of the Giants p. 176*  
![](2-Mechanics/CLI/bestiary/undead/img/spectral-cloud.webp#right)

A cloud giant that dies through an act of betrayal or an ill-fated wager sometimes returns as a spectral cloud. While this Undead seems to be merely a thick cloud or fog bank, observers can sometimes spot a shadowy bipedal figure lurking within. At the heart of the cloud, the figure's appearance becomes clear: a skeletal cloud giant corpse.

Tales suggest cloud giants sometimes seek this fate rather than accept the end of their naturally long lives. In such stories, a cloud giant undergoes a ritual in which its heart is transplanted into a cloud, causing the giant's body to dissolve and its spirit to animate the cloud.

```ad-statblock
title: Spectral Cloud
![](2-Mechanics/CLI/bestiary/undead/token/spectral-cloud-bgg.webp#token)
*Huge undead, typically  Neutral*

- **Armor Class** 11 
- **Hit Points** 189 (`18d12 + 72`) 
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|12 (+1)|18 (+4)|12 (+1)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +6, Charisma +8
- **Skills** Perception +8
- **Senses** passive Perception 18
- **Damage Resistances** cold; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, thunder
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Giant
- **Challenge** 13

## Traits

***Blurred Form.*** Attack rolls against the spectral cloud are made with disadvantage unless the attacker is within 15 feet of the spectral cloud or the spectral cloud is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Incorporeal Movement.*** The spectral cloud can move through other creatures and objects as if they were difficult terrain. It takes 5 (`1d10`) force damage if it ends its turn inside an object.

## Actions

***Multiattack.*** The spectral cloud makes two Spectral Touch attacks.

***Spectral Touch.*** *Melee Weapon Attack:* `+12` to hit, reach 10 ft., one target. *Hit:* 20 (`3d8 + 7`) force damage plus 10 (`3d6`) necrotic damage. If the target is a creature, it must succeed on a DC 20 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

A Humanoid slain by this attack immediately rises as a miniature spectral cloud (use the [specter](2-Mechanics/CLI/bestiary/undead/specter-xmm.md) stat block in the Monster Manual). The miniature spectral cloud acts as an ally of its creator but isn't under its control.

***Chilling Winds (Recharge 5-6).*** The spectral cloud emits intensely cold wind in a 60-foot line that is 10 feet wide. Each creature in that area must make a DC 20 Constitution saving throw. On a failed save, a creature takes 38 (`7d10`) cold damage and has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only.

If a creature's saving throw is successful or the effect ends for it, that creature is immune to this spectral cloud's Chilling Winds for the next 24 hours.
```
^statblock