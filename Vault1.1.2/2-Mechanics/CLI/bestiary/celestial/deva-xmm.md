---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial/angel
aliases: ["Deva"]
---
# Deva
*Source: Monster Manual (2024) p. 97*  
![](2-Mechanics/CLI/bestiary/celestial/img/deva.webp#right)

## Deva

*World-Changing Angelic Messenger*

- **Habitat.** Planar (Upper Planes)  
- **Treasure.** Relics  

Devas are emissaries of divine will. These immortal messengers adopt the shapes of mystical beasts or idealized, winged mortals. As with all angels, their true forms are known only to the gods they serve.

Rather than literal correspondence from a god, a deva conveys an allegory or quest to mortals, tasking them with delivering something to its rightful place. While the angel might be called on in times of need, it encourages mortal heroism. Should a deva's chosen champions carry out their charge, they experience a revelation or the world is changed in line with divine purpose. Roll on or choose a result from the Deva Messages table to inspire a deva's charge.

**Deva Messages**

`dice: [](deva-xmm.md#^deva-messages)`

| dice: 1d6 | The Deva Tasks a Mortal with Delivering... |
|-----------|--------------------------------------------|
| 1 | The corpse of a hero in need of redemption. |
| 2 | The cure for a plague in a distant land. |
| 3 | A holy coffer that must not be opened. |
| 4 | A magic weapon usable only by a true hero. |
| 5 | A seedling that wilts if exposed to anger. |
| 6 | Someone from another world with a prophesied purpose but no memory. |
^deva-messages

```ad-statblock
title: Deva
![](2-Mechanics/CLI/bestiary/celestial/token/deva-xmm.webp#token)
*Medium celestial (angel), Lawful Good*

- **Armor Class** 17 
- **Hit Points** 229 (`27d8 + 108`) 
- **Speed** 30 ft., fly 90 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|20 (+5)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +9, Charisma +9
- **Skills** Insight +9, Perception +9
- **Senses** darkvision 120 ft., passive Perception 19
- **Damage Resistances** radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all; telepathy 120 ft.
- **Challenge** 10

## Traits

***Exalted Restoration.*** If the deva dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere in Mount Celestia.

***Magic Resistance.*** The deva has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting.*** The deva casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [Detect Evil and Good](2-Mechanics/CLI/spells/detect-evil-and-good-xphb.md), [Shapechange](2-Mechanics/CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only, no [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each**: [Commune](2-Mechanics/CLI/spells/commune-xphb.md), [Raise Dead](2-Mechanics/CLI/spells/raise-dead-xphb.md)

***Divine Aid (2/Day).*** The deva casts [Cure Wounds](2-Mechanics/CLI/spells/cure-wounds-xphb.md), [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration-xphb.md), or [Remove Curse](2-Mechanics/CLI/spells/remove-curse-xphb.md), using the same spellcasting ability as Spellcasting.

**2/day**: [Cure Wounds](2-Mechanics/CLI/spells/cure-wounds-xphb.md), [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration-xphb.md), [Remove Curse](2-Mechanics/CLI/spells/remove-curse-xphb.md)

## Actions

***Multiattack.*** The deva makes two Holy Mace attacks.

***Holy Mace.*** *Melee Attack Roll:* `+8`, reach 5 ft. *Hit:* 7 (`1d6 + 4`) Bludgeoning damage plus 18 (`4d8`) Radiant damage.
```
^statblock

## Environment

planar, upper