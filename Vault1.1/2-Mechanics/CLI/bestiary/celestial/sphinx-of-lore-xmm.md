---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
aliases: ["Sphinx of Lore"]
---
# Sphinx of Lore
*Source: Monster Manual (2024) p. 293*  
![](2-Mechanics/CLI/bestiary/celestial/img/sphinx-of-lore.webp#right)

Sphinxes of lore each know a great secret and protect it all costs. This truth might take the form of an ancient text, a magical puzzle, or a path to another world. These sphinxes might gain reputations as sages or oracles, but they typically dwell far from civilization.

## Sphinxes

*Collectors and Keepers of Secrets*

- **Habitat.** Desert, Planar (Upper Planes)  
- **Treasure.** Arcana  

Sphinxes protect the secrets of the multiverse. Formed from the spirits of sages and explorers, sphinxes know the power of truth and the importance of preserving it. They share their wisdom only with those who prove themselves wise or overcome tests of worthiness, such as riddles or battles with dangerous beasts. Through their existences, sphinxes might change form as they gain more nuanced understanding of cosmic enigmas.

### Sphinx Lairs

Sphinxes typically dwell in places that hold great knowledge or prophetic magic.

> [!quote]  
> 
> Round she is, yet flat as a board
> 
> Altar of the Lupine Lords
> 
> Jewel on black velvet, pearl in the sea
> 
> Unchanged but e'erchanging eternally

> [!note]
> Answer to the riddle of White Plume Mountain: The Moon.

![](2-Mechanics/CLI/bestiary/celestial/img/sphinxes.webp#center)

## Statblock

```ad-statblock
title: Sphinx of Lore
![](2-Mechanics/CLI/bestiary/celestial/token/sphinx-of-lore-xmm.webp#token)
*Large celestial, Lawful Neutral*

- **Armor Class** 17 
- **Hit Points** 170 (`20d10 + 60`) 
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|16 (+3)|18 (+4)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Arcana +12, History +12, Perception +8, Religion +12
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** necrotic, radiant
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Celestial, Common
- **Challenge** 11

## Traits

***Inscrutable.*** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) checks made to ascertain its intentions or sincerity are made with [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md).

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the sphinx fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The sphinx casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 16):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Identify](2-Mechanics/CLI/spells/identify-xphb.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion-xphb.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation-xphb.md)

**1/day each**: [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic-xphb.md), [Legend Lore](2-Mechanics/CLI/spells/legend-lore-xphb.md), [Locate Object](2-Mechanics/CLI/spells/locate-object-xphb.md), [Plane Shift](2-Mechanics/CLI/spells/plane-shift-xphb.md), [Remove Curse](2-Mechanics/CLI/spells/remove-curse-xphb.md), [Tongues](2-Mechanics/CLI/spells/tongues-xphb.md)

## Actions

***Multiattack.*** The sphinx makes three Claw attacks.

***Claw.*** *Melee Attack Roll:* `+8`, reach 5 ft. *Hit:* 14 (`3d6 + 4`) Slashing damage.

***Mind-Rending Roar (Recharge 5-6).*** *Wisdom Saving Throw:* DC 16, each enemy in a 300-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the sphinx. *Failure:* 35 (`10d6`) Psychic damage, and the target has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the start of the sphinx's next turn.

## Legendary Actions

***Arcane Prowl.*** The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.

***Weight of Years.*** *Constitution Saving Throw:* DC 16, one creature the sphinx can see within 120 feet. *Failure:* The target gains 1 [Exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) level. While the target has any [Exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) levels, it appears `3d10` years older. *Failure or Success:* The sphinx can't take this action again until the start of its next turn.

## Regional effects

The region containing a sphinx of lore's or sphinx of valor's lair is altered by its presence, creating the following effects:

- **Distant Sight.** While in its lair, the sphinx can cast [Clairvoyance](2-Mechanics/CLI/spells/clairvoyance-xphb.md), requiring no spell components and using the same spellcasting ability as its Spellcasting action. When cast this way, the spell's range is 1 mile.  
- **Infusion of Knowledge.** Whenever the sphinx or one of its allies takes a [Study](2-Mechanics/CLI/rules/actions.md#Study) action while within 1 mile of the lair, it adds `1d6` to any ability check it makes for that action.  

If the sphinx dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

desert, planar, upper