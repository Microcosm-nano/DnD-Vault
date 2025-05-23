---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
aliases: ["Fomorian Warlock of the Dark"]
---
# Fomorian Warlock of the Dark
*Source: Bigby Presents: Glory of the Giants p. 144*  
![](2-Mechanics/CLI/bestiary/giant/img/fomorian-warlock-of-the-dark.webp#right)

Some fomorians search for the arcane glory their kind possessed before their banishment into the Underdark. They forge magical pacts with entities of the dark—perhaps powerful Fey of the Gloaming Court or eldritch entities buried deep in the Underdark. Their pacts give these fomorians power over shadows, allowing them to mold and shape darkness like clay.

## Fomorians

Descended from Annam's son Karontor, fomorians once occupied a place in the giants' ordning between hill and stone giants. In ancient times, they were scholars of magic known for their keen intellect—but also for their inflated egos and sense of entitlement. Karontor exploited these qualities, tempting them with promises of higher standing in the ordning, and incited his descendants to launch an assault on the Feywild. When the assault failed, the fomorians were banished to the Underdark and their god was consigned to a subterranean prison. Subjected to the strange magic of the Underdark, the fomorians' bodies and souls twisted until they became the fomorians of today.

## Statblock

```ad-statblock
title: Fomorian Warlock of the Dark
![](2-Mechanics/CLI/bestiary/giant/token/fomorian-warlock-of-the-dark-bgg.webp#token)
*Huge giant, Any alignment*

- **Armor Class** 15 (natural armor)
- **Hit Points** 207 (`18d12 + 90`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|13 (+1)|20 (+5)| 9 (-1)|14 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +6, Charisma +8
- **Skills** Arcana +3, Perception +6, Stealth +5
- **Senses** darkvision 120 ft., passive Perception 16
- **Languages** Giant, Undercommon
- **Challenge** 12

## Traits

***Blood Rune.*** The fomorian has a blood rune inscribed on an effigy or some other object in its possession. While holding or wearing the object bearing the rune, the giant can use its Corrupting Hex action and Poisoning Rebuke reaction.

The object bearing the blood rune has AC 15; 30 hit points; and immunity to necrotic, poison, and psychic damage. The object regains all its hit points at the end of every turn, but it turns to dust if reduced to 0 hit points or when the fomorian dies. If the rune is destroyed, the fomorian can inscribe a blood rune on an object in its possession when it finishes a short or long rest.

***Devil's Sight.*** Magical darkness doesn't impede the fomorian's darkvision.

***Legendary Resistance (3/Day).*** If the fomorian fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The fomorian casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [levitate](2-Mechanics/CLI/spells/levitate-xphb.md), [mage hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation-xphb.md)

**1/day each**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [suggestion](2-Mechanics/CLI/spells/suggestion-xphb.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis-xphb.md)

## Actions

***Multiattack.*** The fomorian makes three Greatclub attacks. If the fomorian has its blood rune, it can replace one of these attacks with a use of Corrupting Hex.

***Greatclub.*** *Melee Weapon Attack:* `+10` to hit, reach 15 ft., one target. *Hit:* 19 (`3d8 + 6`) bludgeoning damage plus 7 (`2d6`) necrotic damage.

***Corrupting Hex (Requires Blood Rune).*** The fomorian targets one creature it can see within 60 feet of itself. The target must succeed on a DC 16 Charisma saving throw or take 27 (`6d8`) necrotic damage and become cursed for 24 hours. While cursed this way, the target's speed is reduced by half, and if it tries to cast a spell, it must first succeed on a DC 16 Intelligence check or the spell fails and is wasted.

***Eldritch Burst.*** Magical energy explodes in a 20-foot-radius sphere centered on a point the fomorian can see within 120 feet of itself. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 32 (`5d12`) force damage and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. On a successful save, a creature takes half as much damage only.

## Bonus Actions

***Creeping Gloom (Recharge 6).*** The fomorian momentarily conjures grasping darkness in a 30-foot-radius sphere centered on a point it can see within 120 feet of itself. Each creature in that area must succeed on a DC 16 Constitution saving throw or take 11 (`2d10`) necrotic damage and have the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the end of its next turn.

## Reactions

***Poisoning Rebuke (Requires Blood Rune).*** In response to being damaged by a creature the fomorian can see within 60 feet of itself, the fomorian forces that creature to make a DC 16 Constitution saving throw; on a failed save, the creature has the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of its next turn.
```
^statblock