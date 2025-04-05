---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
aliases: ["Spirit Naga"]
---
# Spirit Naga
*Source: Monster Manual (2024) p. 297*  
![](2-Mechanics/CLI/bestiary/fiend/img/spirit-naga.webp#right)

## Spirit Naga

*Spiteful Serpentine Grudge Keeper*

- **Habitat.** Planar (Lower Planes), Underdark  
- **Treasure.** Arcana  

Spirit nagas loathe the world and all creatures. Possessing perfect memories, these venomous, cobra-like creatures recall every slight committed against them during their immortal existences. In their dank, joyless lairs, they create vicious plots to avenge themselves against even petty offenses.

Spirit nagas seek to claim what they believe they deserve. Their schemes often involve poisons, vile spells, cursed objects, or magical compulsions, eventually making them wellsprings of diabolical knowledge and evil inspiration. Other villains often seek out spirit nagas as advisers and allies. Roll on or choose a result from the Spirit Naga Grievances table to inspire what motivates a spirit naga's schemes.

**Spirit Naga Grievances**

`dice: [](spirit-naga-xmm.md#^spirit-naga-grievances)`

| dice: 1d6 | The Spirit Naga Believes... |
|-----------|-----------------------------|
| 1 | A character is to blame for its recent failures. |
| 2 | It has been evicted from its rightful home. |
| 3 | Locals have reneged on an age-old bargain. |
| 4 | Other creatures are mocking it. |
| 5 | A rival is spying on it. |
| 6 | Someone's treasure rightfully belongs to it. |
^spirit-naga-grievances

```ad-statblock
title: Spirit Naga
![](2-Mechanics/CLI/bestiary/fiend/token/spirit-naga-xmm.webp#token)
*Large fiend, Chaotic Evil*

- **Armor Class** 17 
- **Hit Points** 135 (`18d10 + 36`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|17 (+3)|14 (+2)|16 (+3)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Constitution +5, Wisdom +5, Charisma +6
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 8

## Traits

***Fiendish Restoration.*** If it dies, the naga returns to life in `1d6` days and regains all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). Only a [Wish](2-Mechanics/CLI/spells/wish-xphb.md) spell can prevent this trait from functioning.

***Spellcasting.*** The naga casts one of the following spells, requiring no Somatic or Material components and using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion-xphb.md), [Water Breathing](2-Mechanics/CLI/spells/water-breathing-xphb.md)

**2/day each**: [Detect Thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Dimension Door](2-Mechanics/CLI/spells/dimension-door-xphb.md), [Hold Person](2-Mechanics/CLI/spells/hold-person-xphb.md) (level 3 version), [Lightning Bolt](2-Mechanics/CLI/spells/lightning-bolt-xphb.md) (level 4 version)

## Actions

***Multiattack.*** The naga makes three attacks, using Bite or Necrotic Ray in any combination.

***Bite.*** *Melee Attack Roll:* `+7`, reach 10 ft. *Hit:* 7 (`1d6 + 4`) Piercing damage plus 14 (`4d6`) Poison damage.

***Necrotic Ray.*** *Ranged Attack Roll:* `+6`, range 60 ft. *Hit:* 21 (`6d6`) Necrotic damage.
```
^statblock

## Environment

planar, lower, underdark