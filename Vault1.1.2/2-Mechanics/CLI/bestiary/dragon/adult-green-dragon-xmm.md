---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon/chromatic
aliases: ["Adult Green Dragon"]
---
# Adult Green Dragon
*Source: Monster Manual (2024) p. 153*  
![An adult green dragon shadows its prey](2-Mechanics/CLI/bestiary/dragon/img/green-dragon.webp#right)

The words of adult green dragons are as deadly as their poisonous breath. They are brilliant schemers that pride themselves on influencing communities near their lairs. They obsess over information and create vast spy networks. Many of these dragons seek magical methods of surveillance or domination, and they manipulate adventurers into hunting down lost magic to aid in such control.

## Green Dragons

*Dragons of Deceit and Derision*

- **Habitat.** Forest  
- **Treasure.** Arcana  

From forbidden forest depths, green dragons whisper evils into the world and manipulate the lives of those who listen. Elusive, conniving, and egotistical, these chromatic dragons patiently prey on the fears of shorter-lived beings, corrupting and isolating them. Green dragons might lurk amid labyrinthine wildernesses for centuries without revealing themselves; even their most devoted followers might know them only as the voice of the woodlands or a whisper in their dreams.

Despite their might, most green dragons disdain physical violence, viewing combat as servants' work and preferring to trick foes into dangerous or exploitative scenarios. These dragons collect "baubles" that embody their webs of manipulation and serve as tools of extortion, such as compromising documents, family heirlooms, and sentimental treasures.

### Green Dragon Lairs

Green dragons lair in ancient forests, often shaping stands of massive trees into compounds of interwoven branches, hollow trunks, and caverns amid mighty roots. They might also dwell amid forested ruins, particularly the former homes of those they've conquered.

## Statblock

```ad-statblock
title: Adult Green Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/adult-green-dragon-xmm.webp#token)
*Huge dragon (chromatic), Lawful Evil*

- **Armor Class** 19 
- **Hit Points** 207 (`18d12 + 90`) 
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|12 (+1)|21 (+5)|18 (+4)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +6, Wisdom +7
- **Skills** Deception +9, Perception +12, Persuasion +9, Stealth +6
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 22
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 15

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Mind Spike](2-Mechanics/CLI/spells/mind-spike-xphb.md) (level 3 version)

**1/day**: [Geas](2-Mechanics/CLI/spells/geas-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Mind Spike](2-Mechanics/CLI/spells/mind-spike-xphb.md) (level 3 version).

***Rend.*** *Melee Attack Roll:* `+11`, reach 10 ft. *Hit:* 15 (`2d8 + 6`) Slashing damage plus 7 (`2d6`) Poison damage.

***Poison Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 18, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 56 (`16d6`) Poison damage. *Success:* Half damage.

## Legendary Actions

***Mind Invasion.*** The dragon uses Spellcasting to cast [Mind Spike](2-Mechanics/CLI/spells/mind-spike-xphb.md) (level 3 version).

***Noxious Miasma.*** *Constitution Saving Throw:* DC 17, each creature in a 20-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the dragon can see within 90 feet. *Failure:* 7 (`2d6`) Poison damage, and the target takes a -2 penalty to AC until the end of its next turn. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

## Regional effects

The region containing an adult or ancient green dragon's lair is warped by its presence, creating the following effects:

- **Beast Spies.** Tiny Beasts magically gain the ability to understand Draconic and can communicate telepathically with the dragon while within 1 mile of the lair.  
- **Poisonous Thicket.** Ordinary plants growing within 1 mile of the lair poison the air around them. Whenever a creature other than the dragon or its allies finishes a [Long Rest](2-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md) in that area, it must succeed on a DC 15 Constitution saving throw or have the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 hour.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

forest