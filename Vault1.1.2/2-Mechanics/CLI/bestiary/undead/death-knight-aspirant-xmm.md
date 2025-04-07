---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
aliases: ["Death Knight Aspirant"]
---
# Death Knight Aspirant
*Source: Monster Manual (2024) p. 93*  
![](2-Mechanics/CLI/bestiary/undead/img/death-knights.webp#right)

When the leader of a villainous order rises as a death knight, their wicked devotees might join them in their cursed existence as death knight aspirants. These followers bear a measure of their leader's power and serve as they did in life, obediently following the death knight's decrees and heralding its terrible will.

## Death Knights

*Haunted Commanders of Unliving Legions*

- **Habitat.** Any  
- **Treasure.** Armaments  

Champions of evil, death knights are armor-clad, skeletal warlords. Combining devastating martial prowess and blasphemous magic, these undying tyrants lead unholy legions against the living or brood in cursed citadels. Every death knight is haunted by a legacy of tragedy and dishonor that drives it to commit greater evils.

## Statblock

```ad-statblock
title: Death Knight Aspirant
![](2-Mechanics/CLI/bestiary/undead/token/death-knight-aspirant-xmm.webp#token)
*Small or Medium undead, Chaotic Evil*

- **Armor Class** 20 
- **Hit Points** 178 (`21d8 + 84`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|18 (+4)|10 (+0)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +4, Wisdom +5
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 11

## Traits

***Magic Resistance.*** The aspirant has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Marshal Undead.*** Undead creatures of the aspirant's choice (excluding itself) in a 60-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from it have [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls and saving throws. It can't use this trait if it has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

***Spellcasting.*** The aspirant casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [Phantom Steed](2-Mechanics/CLI/spells/phantom-steed-xphb.md)

**1/day each**: [Destructive Wave](2-Mechanics/CLI/spells/destructive-wave-xphb.md) (Necrotic), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic-xphb.md)

## Actions

***Multiattack.*** The aspirant makes three Dread Blade attacks.

***Dread Blade.*** *Melee Attack Roll:* `+9`, reach 5 ft. *Hit:* 14 (`2d8 + 5`) Slashing damage plus 10 (`3d6`) Necrotic damage.

***Hellfire Orb (Recharge 5-6).*** *Dexterity Saving Throw:* DC 15, each creature in a 20-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the aspirant can see within 120 feet of itself. *Failure:* 21 (`6d6`) Fire damage plus 21 (`6d6`) Necrotic damage. *Success:* Half damage.

## Reactions

***Parry.*** Trigger: The aspirant is hit by a melee attack roll while holding a weapon. _Response:_ The aspirant adds 4 to its AC against that attack, possibly causing it to miss.
```
^statblock

## Environment

any