---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
aliases: ["Dryad"]
---
# Dryad
*Source: Monster Manual (2024) p. 107*  
![](2-Mechanics/CLI/bestiary/fey/img/dryad.webp#right)

## Dryad

*Tree-Bound Guardian of Nature*

- **Habitat.** Forest  
- **Treasure.** Any  

Guardians of the woodlands, dryads magically flit from tree to tree and from root to bough, harrying trespassers with tangling vines and thorns. Most of these elusive beings have a special connection with one plant or a natural sanctuary that they protect. Some also share physical similarities with the plants they're most connected to. Dryads might sicken or die if their plant or sanctuary is destroyed, recovering only if it is healed or magically replaced. Roll on or choose an option from the Dryad Sanctuaries table to inspire a dryad's bond.

**Dryad Sanctuaries**

`dice: [](dryad-xmm.md#^dryad-sanctuaries)`

| dice: 1d6 | The Dryad Dwells in and Protects... |
|-----------|-------------------------------------|
| 1 | An acres-large clonal colony—a stand of identical, interconnected trees. |
| 2 | A fortresslike tree, like a baobab or sequoia. |
| 3 | A living lock—a plant that seals evil below or blocks the path to a dungeon. |
| 4 | A lonely tree that stands atop a windswept mountain or amid a [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) forest. |
| 5 | A plant with magic fruit or remarkable seeds. |
| 6 | A shambling mound or treant that the dryad lives in or around as a Fey symbiote. |
^dryad-sanctuaries

```ad-statblock
title: Dryad
![](2-Mechanics/CLI/bestiary/fey/token/dryad-xmm.webp#token)
*Medium fey, Neutral*

- **Armor Class** 16 
- **Hit Points** 22 (`5d8`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|12 (+1)|11 (+0)|14 (+2)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Elvish, Sylvan
- **Challenge** 1

## Traits

***Magic Resistance.*** The dryad has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Speak with Beasts and Plants.*** The dryad can communicate with Beasts and Plants as if they shared a language.

***Spellcasting.*** The dryad casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [Animal Friendship](2-Mechanics/CLI/spells/animal-friendship-xphb.md), [Charm Monster](2-Mechanics/CLI/spells/charm-monster-xphb.md) (lasts 24 hours; ends early if the dryad casts the spell again), [Druidcraft](2-Mechanics/CLI/spells/druidcraft-xphb.md)

**1/day each**: [Entangle](2-Mechanics/CLI/spells/entangle-xphb.md), [Pass without Trace](2-Mechanics/CLI/spells/pass-without-trace-xphb.md)

## Actions

***Multiattack.*** The dryad makes one Vine Lash or Thorn Burst attack, and it can use Spellcasting to cast [Charm Monster](2-Mechanics/CLI/spells/charm-monster-xphb.md).

***Vine Lash.*** *Melee Attack Roll:* `+6`, reach 10 ft. *Hit:* 8 (`1d8 + 4`) Slashing damage.

***Thorn Burst.*** *Ranged Attack Roll:* `+6`, range 60 ft. *Hit:* 7 (`1d6 + 4`) Piercing damage.

## Bonus Actions

***Tree Stride.*** If within 5 feet of a Large or bigger tree, the dryad teleports to an unoccupied space within 5 feet of a second Large or bigger tree that is within 60 feet of the previous tree.
```
^statblock

## Environment

forest