---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/air
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/genie
aliases: ["Djinni"]
---
# Djinni
*Source: Monster Manual (2024) p. 99*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/djinni.webp#right)

## Djinni

*Genie of the Air*

- **Habitat.** Coastal, Planar (Elemental Plane of Air)  
- **Treasure.** Arcana  

As genies of wind and skies, djinn personify freedom and might. They can control wind and travel as swiftly as a breeze. They might be as serene as drifting clouds or as tempestuous as storms, but most djinn relish their freedom and desire to discover the wonders of the multiverse. Djinn often know many stories, and they might share such lore with those who offer their own exciting stories in trade.

While many djinn create airy palaces on stormy coasts or high in the clouds, untold numbers dwell on the Elemental Plane of Air. In floating cities, djinn collect tales and experiences from across the planes of existence, sharing them in fabulous forums, libraries, and theaters. The greatest of these cities is the Citadel of Ice and Steel, in which wind-sculpted towers contain a city-size trove of incredible knowledge and treasures that defy belief.

```ad-statblock
title: Djinni
![](2-Mechanics/CLI/bestiary/elemental/token/djinni-xmm.webp#token)
*Large elemental (genie), Chaotic Good*

- **Armor Class** 17 
- **Hit Points** 218 (`19d10 + 114`) 
- **Speed** 30 ft., fly 90 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|15 (+2)|22 (+6)|15 (+2)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +6, Wisdom +7
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Immunities** lightning, thunder
- **Languages** Primordial (Auran)
- **Challenge** 11

## Traits

***Elemental Restoration.*** If the djinni dies outside the Elemental Plane of Air, its body dissolves into mist, and it gains a new body in `1d4` days, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere on the Plane of Air.

***Magic Resistance.*** The djinni has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Wishes.*** The djinni has a 30 percent chance of knowing the [Wish](2-Mechanics/CLI/spells/wish-xphb.md) spell. If the djinni knows it, the djinni can cast it only on behalf of a non-genie creature who communicates a wish in a way the djinni can understand. If the djinni casts the spell for the creature, the djinni suffers none of the spell's stress. Once the djinni has cast it three times, the djinni can't do so again for 365 days.

***Spellcasting.*** The djinni casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [Detect Evil and Good](2-Mechanics/CLI/spells/detect-evil-and-good-xphb.md), [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md)

**1/day each**: [Creation](2-Mechanics/CLI/spells/creation-xphb.md), [Gaseous Form](2-Mechanics/CLI/spells/gaseous-form-xphb.md), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md), [Major Image](2-Mechanics/CLI/spells/major-image-xphb.md), [Plane Shift](2-Mechanics/CLI/spells/plane-shift-xphb.md)

**2/day each**: [Create Food and Water](2-Mechanics/CLI/spells/create-food-and-water-xphb.md) (can create wine instead of water), [Tongues](2-Mechanics/CLI/spells/tongues-xphb.md), [Wind Walk](2-Mechanics/CLI/spells/wind-walk-xphb.md)

## Actions

***Multiattack.*** The djinni makes three attacks, using Storm Blade or Storm Bolt in any combination.

***Storm Blade.*** *Melee Attack Roll:* `+9`, reach 5 feet. *Hit:* 12 (`2d6 + 5`) Slashing damage plus 7 (`2d6`) Lightning damage.

***Storm Bolt.*** *Ranged Attack Roll:* `+9`, range 120 feet. *Hit:* 13 (`3d8`) Thunder damage. If the target is a Large or smaller creature, it has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Create Whirlwind.*** The djinni conjures a whirlwind at a point it can see within 120 feet. The whirlwind fills a 20-foot-radius, 60-foot-high [Cylinder](2-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md) centered on that point. The whirlwind lasts until the djinni's [Concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) on it ends. The djinni can move the whirlwind up to 20 feet at the start of each of its turns.

Whenever the whirlwind enters a creature's space or a creature enters the whirlwind, that creature is subjected to the following effect. *Strength Saving Throw:* DC 17 (a creature makes this save only once per turn, and the djinni is unaffected). *Failure:* While in the whirlwind, the target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and moves with the whirlwind. At the start of each of its turns, the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target takes 21 (`6d6`) Thunder damage. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success.
```
^statblock

## Environment

coastal, planar, air