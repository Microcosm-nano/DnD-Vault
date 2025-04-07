---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/aberration
aliases: ["Storm Herald"]
---
# Storm Herald
*Source: Bigby Presents: Glory of the Giants p. 183*  
![](2-Mechanics/CLI/bestiary/aberration/img/storm-herald.webp#right)

Ancient and alien beings dwell or slumber in ocean depths, awaiting some cosmic circumstance that signals their time to rise. In their retreat from the world, storm giants sometimes stray into the orbit of such creatures, perhaps while seeking insight into some omen, vision, or prophecy. Krakens, aboleths, and Great Old Ones delight in corrupting storm giants to their service, transforming them into storm heralds.

A storm herald grows fins and tentacles, giving it a monstrous appearance. Its mind is wholly under its master's sway, and the herald gains fearsome psychic powers to use in advancing its master's plans. When the herald dies, it reverts to its previous appearance.

A storm herald might try to sway other storm giants to its master's service, while others gather devoted cults of lesser creatures to serve the monsters of the deep.

```ad-statblock
title: Storm Herald
![](2-Mechanics/CLI/bestiary/aberration/token/storm-herald-bgg.webp#token)
*Huge aberration, typically  Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 287 (`23d12 + 138`) 
- **Speed** 50 ft., swim 100 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|22 (+6)|24 (+7)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Wisdom +10, Charisma +10
- **Skills** Arcana +13, Deception +10, Perception +10
- **Senses** darkvision 120 ft., passive Perception 20
- **Damage Resistances** cold, psychic
- **Damage Immunities** lightning, thunder
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Giant, telepathy 120 ft.
- **Challenge** 17

## Traits

***Amphibious.*** The herald can breathe air and water.

***Magic Resistance.*** The herald has advantage on saving throws against spells and other magical effects.

***Spellcasting (Psionics).*** The herald casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 21):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [mage hand](2-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is invisible)

**1/day each**: [control water](2-Mechanics/CLI/spells/control-water-xphb.md), [control weather](2-Mechanics/CLI/spells/control-weather-xphb.md) (as an action), [sending](2-Mechanics/CLI/spells/sending-xphb.md)

## Actions

***Multiattack.*** The herald makes one Claw attack, one Tentacles attack, and one Trident attack.

***Claw.*** *Melee Weapon Attack:* `+14` to hit, reach 10 ft., one target. *Hit:* 18 (`3d6 + 8`) slashing damage.

***Tentacles.*** *Melee Weapon Attack:* `+14` to hit, reach 10 ft., one target. *Hit:* 21 (`3d8 + 8`) bludgeoning damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18). It also has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and takes 16 (`3d10`) psychic damage at the start of each of its turns until this grapple ends. The herald can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) this way at a time.

***Trident.*** *Melee Weapon Attack:* `+14` to hit, reach 10 ft., one target. *Hit:* 18 (`3d6 + 8`) piercing damage or 21 (`3d8 + 8`) piercing damage if used with two hands, plus 13 (`3d8`) lightning damage.

***Psychic Wave (Recharge 6).*** The herald unleashes a blast of psionic energy into the minds of up to three creatures it can see within 90 feet of itself. Each target must make a DC 21 Intelligence saving throw. On a failed save, a target takes 23 (`3d10 + 7`) psychic damage and has the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. On a successful save, a target takes half as much damage only. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

If a creature is reduced to 0 hit points by this psychic damage, it dies and its head explodes if it has one.
```
^statblock