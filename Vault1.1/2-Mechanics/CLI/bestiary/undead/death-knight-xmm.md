---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
aliases: ["Death Knight"]
---
# Death Knight
*Source: Monster Manual (2024) p. 92*  
![](2-Mechanics/CLI/bestiary/undead/img/death-knights.webp#right)

Death knights are deadly combatants and domineering commanders with grim histories. Some strive to end the curses that doom them to undeath, though their selfish souls eternally shackle them to their fates. Others, like the infamous death knight Lord Soth, brood in dismal ruins for centuries, rousing themselves to action only when something reignites their deathless evil.

## Death Knights

*Haunted Commanders of Unliving Legions*

- **Habitat.** Any  
- **Treasure.** Armaments  

Champions of evil, death knights are armor-clad, skeletal warlords. Combining devastating martial prowess and blasphemous magic, these undying tyrants lead unholy legions against the living or brood in cursed citadels. Every death knight is haunted by a legacy of tragedy and dishonor that drives it to commit greater evils.

## Statblock

```ad-statblock
title: Death Knight
![](2-Mechanics/CLI/bestiary/undead/token/death-knight-xmm.webp#token)
*Small or Medium undead, Chaotic Evil*

- **Armor Class** 20 
- **Hit Points** 199 (`21d8 + 105`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|11 (+0)|20 (+5)|12 (+1)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Wisdom +9
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 17

## Traits

***Legendary Resistance (3/Day).*** If the death knight fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The death knight has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Marshal Undead.*** Undead creatures of the death knight's choice (excluding itself) in a 60-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from it have [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls and saving throws. It can't use this trait if it has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

***Undead Restoration.*** If the death knight is destroyed before it atones for its evil, it gains a new body in `1d10` days, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). The new body appears in a location significant to the death knight.

***Spellcasting.*** The death knight casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 18):

**At will**: [Command](2-Mechanics/CLI/spells/command-xphb.md), [Phantom Steed](2-Mechanics/CLI/spells/phantom-steed-xphb.md)

**2/day each**: [Destructive Wave](2-Mechanics/CLI/spells/destructive-wave-xphb.md) (Necrotic), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic-xphb.md)

## Actions

***Multiattack.*** The death knight makes three Dread Blade attacks.

***Dread Blade.*** *Melee Attack Roll:* `+11`, reach 5 ft. *Hit:* 12 (`2d6 + 5`) Slashing damage plus 13 (`3d8`) Necrotic damage.

***Hellfire Orb (Recharge 5-6).*** *Dexterity Saving Throw:* DC 18, each creature in a 20-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the death knight can see within 120 feet. *Failure:* 35 (`10d6`) Fire damage plus 35 (`10d6`) Necrotic damage. *Success:* Half damage.

## Reactions

***Parry.*** Trigger: The death knight is hit by a melee attack roll while holding a weapon. _Response:_ The death knight adds 6 to its AC against that attack, possibly causing it to miss.

## Legendary Actions

***Dread Authority.*** The death knight uses Spellcasting to cast [Command](2-Mechanics/CLI/spells/command-xphb.md). The death knight can't take this action again until the start of its next turn.

***Fell Word.*** *Constitution Saving Throw:* DC 18, one creature the death knight can see within 120 feet. *Failure:* 17 (`5d6`) Necrotic damage, and the target's [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken. *Failure or Success:* The death knight can't take this action again until the start of its next turn.

***Lunge.*** The death knight moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Dread Blade attack.
```
^statblock

## Environment

any