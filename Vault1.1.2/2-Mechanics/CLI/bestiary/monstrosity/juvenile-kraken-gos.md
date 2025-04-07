---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity/titan
aliases: ["Juvenile Kraken"]
---
# Juvenile Kraken
*Source: Ghosts of Saltmarsh p. 238*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/juvenile-kraken.webp#right)

Hidden in a deep, dark underwater pit near the Styes, this creature bears the mark of the dark god Tharizdun's madness. Becoming more independent every day, it dreams of freeing itself from its aboleth tenders and wreaking its own foul will upon the seas.

```ad-statblock
title: Juvenile Kraken
![](2-Mechanics/CLI/bestiary/monstrosity/token/juvenile-kraken-gos.webp#token)
*Huge monstrosity (titan), Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 207 (`18d12 + 90`) 
- **Speed** 20 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|20 (+5)|19 (+4)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Dexterity +5, Constitution +10, Intelligence +9, Wisdom +7
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** Abyssal, Celestial, Infernal, Primordial, telepathy 60 ft. but can't speak
- **Challenge** 14

## Traits

***Amphibious.*** The kraken can breathe air and water.

***Freedom of Movement.*** The kraken ignores difficult terrain, and magical effects can't reduce its speed or cause it to be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It can spend 5 feet of movement to escape from nonmagical restraints or being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

## Actions

***Multiattack.*** The kraken makes two tentacle attacks, each of which it can replace with a use of Fling.

***Bite.*** *Melee Weapon Attack:* `+12` to hit, reach 5 ft., one target. *Hit:* 20 (`3d8 + 7`) piercing damage. If the target is a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken, that creature is swallowed and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the kraken, and it takes 21 (`6d6`) acid damage at the start of each of the kraken's turns. One Medium or two smaller creatures can be swallowed at the same time.

If the kraken takes 35 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in spaces within 10 feet of the kraken. If the kraken dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tentacle.*** *Melee Weapon Attack:* `+12` to hit, reach 20 ft., one target. *Hit:* 17 (`3d6 + 7`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 20). Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The kraken has ten tentacles, each of which can grapple one target.

***Fling.*** One Medium or smaller object held or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken is thrown up to 40 feet in a random direction and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes 3 (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 13 Dexterity saving throw or take the same damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Lightning Strike.*** The kraken magically create a bolt of lightning, which can strike a target the kraken can see within 90 feet of it. The target must make a DC 18 Dexterity saving throw, taking 22 (`4d10`) lightning damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Tentacle Attack (Costs 2 Actions).*** The kraken makes one tentacle attack.

***Fling.*** The kraken uses Fling.

***Ink Cloud (Costs 3 Actions).*** While underwater, the kraken expels an ink cloud in a 40-foot radius. The cloud spreads around corners, and that area is heavily obscured to creatures other than the kraken. Each creature other than the kraken that ends its turn there must succeed on a DC 18 Constitution saving throw, taking 11 (`2d10`) poison damage on a failed save or half as much damage on a successful one. A strong current disperses the cloud, which otherwise disappears at the end of the kraken's next turn.
```
^statblock