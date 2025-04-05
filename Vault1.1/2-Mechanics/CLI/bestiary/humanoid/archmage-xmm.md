---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Archmage"]
---
# Archmage
*Source: Monster Manual (2024) p. 199*  
![](2-Mechanics/CLI/bestiary/humanoid/img/mages.webp#right)

Archmages have mastered incredible magical power. While some use their magic to protect the world, others become tyrants or pursue forbidden secrets. Many archmages retain magical servants and collect magic items and occult lore.

## Mages

*Magical Scholars and Spellcasters*

- **Habitat.** Any  
- **Treasure.** Arcana, Individual  

Mages are magical wonder-workers, ranging from spellcasting overlords to reclusive witches. They study mystical secrets and possess insight into monsters, legends, omens, and other lore. Mages often gather allies or hire assistants to aid them in their research or to attain magical might.

Roll on or choose a result from the Mage Roles table to inspire different sorts of mages.

**Mage Roles**

`dice: [](archmage-xmm.md#^mage-roles)`

| dice: 1d10 | The Mage Is... |
|------------|----------------|
| 1 | An astronomer who draws magic from stars. |
| 2 | An author who writes about the occult. |
| 3 | A magical engineer who creates wonders. |
| 4 | An oracle who interprets omens. |
| 5 | A prodigy with a remarkable magical heritage. |
| 6 | A psion whose powers manifest as spells. |
| 7 | A scholar investigating ancient lore. |
| 8 | A soothsayer who advises rulers. |
| 9 | A war mage who aids soldiers in battle. |
| 10 | A witch who shares secret wisdom. |
^mage-roles

> [!quote] A quote from Nathor, Thayan Refugee  
> 
> Have you gazed on the Runes of Chaos, held the Death Moon Orb in your trembling hands, entered the Devouring Portal and walked the Paths of the Doomed, or sat at the left hand of Szass Tam during the Ritual of Twin Burnings? No? Then speak not to me of wizards. Speak not to me of Thay.


## Statblock

```ad-statblock
title: Archmage
![](2-Mechanics/CLI/bestiary/humanoid/token/archmage-xmm.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 17 
- **Hit Points** 170 (`31d8 + 31`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|12 (+1)|20 (+5)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +9, Wisdom +6
- **Skills** Arcana +13, History +9, Perception +6
- **Senses** passive Perception 16
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) (with Mind Blank)
- **Languages** Common plus five other languages
- **Challenge** 12

## Traits

***Magic Resistance.*** The archmage has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting.*** The archmage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Disguise Self](2-Mechanics/CLI/spells/disguise-self-xphb.md), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md), [Light](2-Mechanics/CLI/spells/light-xphb.md), [Mage Armor](2-Mechanics/CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation-xphb.md)

**1/day each**: [Cone of Cold](2-Mechanics/CLI/spells/cone-of-cold-xphb.md) (level 9 version), [Mind Blank](2-Mechanics/CLI/spells/mind-blank-xphb.md) (cast before combat), [Scrying](2-Mechanics/CLI/spells/scrying-xphb.md), [Teleport](2-Mechanics/CLI/spells/teleport-xphb.md)

**2/day each**: [Fly](2-Mechanics/CLI/spells/fly-xphb.md), [Lightning Bolt](2-Mechanics/CLI/spells/lightning-bolt-xphb.md) (level 7 version)

***Misty Step (3/Day).*** The mage casts [Misty Step](2-Mechanics/CLI/spells/misty-step-xphb.md), using the same spellcasting ability as Spellcasting.

**3/day**: [Misty Step](2-Mechanics/CLI/spells/misty-step-xphb.md)

***Protective Magic (3/Day).*** The archmage casts [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md) or [Shield](2-Mechanics/CLI/spells/shield-xphb.md) in response to the spell's trigger, using the same spellcasting ability as Spellcasting.

**3/day**: [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md), [Shield](2-Mechanics/CLI/spells/shield-xphb.md)

## Actions

***Multiattack.*** The archmage makes four Arcane Burst attacks.

***Arcane Burst.*** *Melee or Ranged Attack Roll:* `+9`, reach 5 ft. or range 150 ft. *Hit:* 27 (`4d10 + 5`) Force damage.
```
^statblock

## Environment

any