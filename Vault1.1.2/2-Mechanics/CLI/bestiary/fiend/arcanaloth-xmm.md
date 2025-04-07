---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
aliases: ["Arcanaloth"]
---
# Arcanaloth
*Source: Monster Manual (2024) p. 19*  
![](2-Mechanics/CLI/bestiary/fiend/img/arcanaloth.webp#right)

## Arcanaloth

*Yugoloth of Magical Manipulation*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Arcana  

While all yugoloths are fiendish manifestations of wickedness and greed, arcanaloths bend their considerable intellects toward hoarding and exploiting secrets. They then deploy these secrets to ensnare countless victims and lesser villains, beguiling foes with false promises and powerful magic.

Arcanaloths possess considerable spellcasting prowess and frequently disguise themselves with magic. While they prefer to let magical servants or other yugoloths do their fighting for them, arcanaloths can defend themselves with arcane might, banishing opponents into the pages of their magic tomes.

```ad-statblock
title: Arcanaloth
![](2-Mechanics/CLI/bestiary/fiend/token/arcanaloth-xmm.webp#token)
*Medium fiend (yugoloth), Neutral Evil*

- **Armor Class** 18 
- **Hit Points** 175 (`27d8 + 54`) 
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|12 (+1)|14 (+2)|20 (+5)|16 (+3)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +5, Constitution +6, Intelligence +9, Wisdom +7
- **Skills** Arcana +9, Deception +7, Insight +7, Perception +7
- **Senses** truesight 120 ft., passive Perception 17
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all; telepathy 120 ft.
- **Challenge** 12

## Traits

***Fiendish Restoration.*** If the arcanaloth dies outside Gehenna, its body dissolves into ichor, and it gains a new body instantly and revives with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) in Gehenna.

***Magic Resistance.*** The arcanaloth has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Soul Tome.*** The arcanaloth has a magic tome. While holding or carrying the tome, the arcanaloth can use its Banishing Claw action.

The tome has AC 17; HP 35; and [Immunity](2-Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to Necrotic, Poison, and Psychic damage. The tome regains all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) at the end of every turn, but it turns to dust if reduced to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) or when the arcanaloth dies. If the tome is destroyed, the arcanaloth can create a new one when it finishes a [Short](2-Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](2-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

***Spellcasting.*** The arcanaloth casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [Alter Self](2-Mechanics/CLI/spells/alter-self-xphb.md), [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Identify](2-Mechanics/CLI/spells/identify-xphb.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation-xphb.md)

**1/day each**: [Contact Other Plane](2-Mechanics/CLI/spells/contact-other-plane-xphb.md), [Detect Thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Dimension Door](2-Mechanics/CLI/spells/dimension-door-xphb.md), [Mind Blank](2-Mechanics/CLI/spells/mind-blank-xphb.md)

***Counterspell.*** The arcanaloth casts [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md) in response to that spell's trigger, using the same spellcasting ability as Spellcasting.

**At will**: [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md)

## Actions

***Multiattack.*** The arcanaloth makes three Fiendish Burst attacks. It can replace one attack with a Banishing Claw attack.

***Fiendish Burst.*** *Melee or Ranged Attack Roll:* `+9`, reach 5 ft. or range 120 ft. *Hit:* 31 (`4d12 + 5`) Necrotic damage.

***Banishing Claw (Requires Soul Tome).*** *Melee Attack Roll:* `+9`, reach 5 ft. *Hit:* 10 (`2d4 + 5`) Slashing damage plus 19 (`3d12`) Psychic damage. If the target is a creature, it is subjected to the following effect. *Charisma Saving Throw:* DC 17. *Failure:* The target is trapped in a demiplane inside the Soul Tome. While trapped there, the target has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition. At the end of each of its turns, the target repeats the save, escaping the tome on a success. When the target escapes, it appears in the space it left or, if that space is occupied, the nearest unoccupied space.

If the target fails three of these saves while in the demiplane, it becomes bound to the tome and can escape only if the tome is reduced to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

## Bonus Actions

***Teleport.*** The arcanaloth teleports up to 30 feet to an unoccupied space it can see.
```
^statblock

## Environment

planar, lower