---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/chromatic
aliases: ["Ancient Green Dragon"]
---
# Ancient Green Dragon
*Source: Monster Manual (2024) p. 154*  
![An ancient green dragon ma...](2-Mechanics/CLI/bestiary/dragon/img/ancient-green-dragon.webp#right "An ancient green dragon manipulates the fates of its pawns from deep within its forest lair")

Ancient green dragons are creatures of legend, rarely seen by their servants or foes. Via magic and well-hidden agents, these dragons stoke suspicion between allies and undermine noble works. As bonds fray, the dragons reap rewards of greater wealth and control. Eventually the ambitions of ancient green dragons stretch beyond their territories as they seek control over empires, planar realms, or death itself.

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
title: Ancient Green Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/ancient-green-dragon-xmm.webp#token)
*Gargantuan dragon (chromatic), Lawful Evil*

- **Armor Class** 21 
- **Hit Points** 402 (`23d20 + 161`) 
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|12 (+1)|25 (+7)|20 (+5)|17 (+3)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +8, Wisdom +10
- **Skills** Deception +13, Perception +17, Persuasion +13, Stealth +8
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 27
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 22

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Mind Spike](2-Mechanics/CLI/spells/mind-spike-xphb.md) (level 5 version)

**1/day each**: [Geas](2-Mechanics/CLI/spells/geas-xphb.md), [Modify Memory](2-Mechanics/CLI/spells/modify-memory-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Mind Spike](2-Mechanics/CLI/spells/mind-spike-xphb.md) (level 5 version).

***Rend.*** *Melee Attack Roll:* `+15`, reach 15 ft. *Hit:* 17 (`2d8 + 8`) Slashing damage plus 10 (`3d6`) Poison damage.

***Poison Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 22, each creature in a 90-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 77 (`22d6`) Poison damage. *Success:* Half damage.

## Legendary Actions

***Mind Invasion.*** The dragon uses Spellcasting to cast [Mind Spike](2-Mechanics/CLI/spells/mind-spike-xphb.md) (level 5 version).

***Noxious Miasma.*** *Constitution Saving Throw:* DC 21, each creature in a 30-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the dragon can see within 90 feet. *Failure:* 17 (`5d6`) Poison damage, and the target takes a -2 penalty to AC until the end of its next turn. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

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