---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Mage"]
---
# Mage
*Source: Monster Manual (2024) p. 199. Available in the Free Rules (2024)*  
![](2-Mechanics/CLI/bestiary/humanoid/img/mages.webp#right)

Mages are accomplished spellcasters whose lives have been shaped by magic. They can use their powers to defend or dominate other creatures, or they could focus on magical research and unlocking mystical secrets.

## Mages

*Magical Scholars and Spellcasters*

- **Habitat.** Any  
- **Treasure.** Arcana, Individual  

Mages are magical wonder-workers, ranging from spellcasting overlords to reclusive witches. They study mystical secrets and possess insight into monsters, legends, omens, and other lore. Mages often gather allies or hire assistants to aid them in their research or to attain magical might.

Roll on or choose a result from the Mage Roles table to inspire different sorts of mages.

**Mage Roles**

`dice: [](mage-xmm.md#^mage-roles)`

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
title: Mage
![](2-Mechanics/CLI/bestiary/humanoid/token/mage-xmm.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 15 
- **Hit Points** 81 (`18d8`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|11 (+0)|17 (+3)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +4
- **Skills** Arcana +6, History +6, Perception +4
- **Senses** passive Perception 14
- **Languages** Common and any three languages
- **Challenge** 6

***Spellcasting.*** The mage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Light](2-Mechanics/CLI/spells/light-xphb.md), [Mage Armor](2-Mechanics/CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation-xphb.md)

**1/day each**: [Cone of Cold](2-Mechanics/CLI/spells/cone-of-cold-xphb.md), [Fly](2-Mechanics/CLI/spells/fly-xphb.md)

**2/day each**: [Fireball](2-Mechanics/CLI/spells/fireball-xphb.md) (level 4 version), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md)

***Misty Step (3/Day).*** The mage casts [Misty Step](2-Mechanics/CLI/spells/misty-step-xphb.md), using the same spellcasting ability as Spellcasting.

**3/day**: [Misty Step](2-Mechanics/CLI/spells/misty-step-xphb.md)

***Protective Magic (3/Day).*** The mage casts [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md) or [Shield](2-Mechanics/CLI/spells/shield-xphb.md) in response to the spell's trigger, using the same spellcasting ability as Spellcasting.

**3/day**: [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md), [Shield](2-Mechanics/CLI/spells/shield-xphb.md)

## Actions

***Multiattack.*** The mage makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee or Ranged Attack Roll:* `+6`, reach 5 ft. or range 120 ft. *Hit:* 16 (`3d8 + 3`) Force damage.
```
^statblock

## Environment

any