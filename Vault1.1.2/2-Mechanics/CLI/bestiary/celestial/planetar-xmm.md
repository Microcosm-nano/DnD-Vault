---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial/angel
aliases: ["Planetar"]
---
# Planetar
*Source: Monster Manual (2024) p. 245*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/planetar.webp#right)

## Planetar

*Righteously Wrathful Angelic Warrior*

- **Habitat.** Planar (Upper Planes)  
- **Treasure.** Relics  

Planetars deliver the punishment of righteous gods. These angels innately know truth from lies, and they use magic and blessed weapons to protect the just and root out wickedness across the Multiverse.

These angels act where they can against overwhelming evil, but to avoid the attention of the Lower Planes, they prefer to let mortals attend to affairs on the Material Plane. Planetars often choose mortal champions to oppose threats they're loath to face directly, involving themselves only if necessary. Roll on or choose a result from the Planetar Quests table to inspire what evil a planetar might recruit heroes to thwart.

**Planetar Quests**

`dice: [](planetar-xmm.md#^planetar-quests)`

| dice: 1d6 | The Planetar Entreats a Mortal Hero To... |
|-----------|-------------------------------------------|
| 1 | Convince a villain to meet with the angel. |
| 2 | Find a loved one a villain believes is dead. |
| 3 | Heal the loved one of an evil ruler. |
| 4 | Inspire the defenders of a besieged holy site. |
| 5 | Recover and destroy an evil Artifact. |
| 6 | Reveal the true name of a devil to banish it. |
^planetar-quests

```ad-statblock
title: Planetar
![](2-Mechanics/CLI/bestiary/celestial/token/planetar-xmm.webp#token)
*Large celestial (angel), Lawful Good*

- **Armor Class** 19 
- **Hit Points** 262 (`21d10 + 147`) 
- **Speed** 40 ft., fly 120 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|20 (+5)|24 (+7)|19 (+4)|22 (+6)|25 (+7)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Constitution +12, Wisdom +11, Charisma +12
- **Skills** Perception +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all; telepathy 120 ft.
- **Challenge** 16

## Traits

***Divine Awareness.*** The planetar knows if it hears a lie.

***Exalted Restoration.*** If the planetar dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere in Mount Celestia.

***Magic Resistance.*** The planetar has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting.*** The planetar casts one of the following spells, requiring no Material components and using Charisma as spellcasting ability (spell save DC 20):

**At will**: [Detect Evil and Good](2-Mechanics/CLI/spells/detect-evil-and-good-xphb.md)

**1/day each**: [Commune](2-Mechanics/CLI/spells/commune-xphb.md), [Control Weather](2-Mechanics/CLI/spells/control-weather-xphb.md), [Dispel Evil and Good](2-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md), [Raise Dead](2-Mechanics/CLI/spells/raise-dead-xphb.md)

***Divine Aid (2/Day).*** The planetar casts [Cure Wounds](2-Mechanics/CLI/spells/cure-wounds-xphb.md), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md), [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration-xphb.md), or [Remove Curse](2-Mechanics/CLI/spells/remove-curse-xphb.md), using the same spellcasting ability as Spellcasting.

**2/day**: [Cure Wounds](2-Mechanics/CLI/spells/cure-wounds-xphb.md), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md), [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration-xphb.md), [Remove Curse](2-Mechanics/CLI/spells/remove-curse-xphb.md)

## Actions

***Multiattack.*** The planetar makes three Radiant Sword attacks or uses Holy Burst twice.

***Radiant Sword.*** *Melee Attack Roll:* `+12`, reach 10 ft. *Hit:* 14 (`2d6 + 7`) Slashing damage plus 18 (`4d8`) Radiant damage.

***Holy Burst.*** *Dexterity Saving Throw:* DC 20, each enemy in a 20-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the planetar can see within 120 feet. *Failure:* 24 (`7d6`) Radiant damage. *Success:* Half damage.
```
^statblock

## Environment

planar, upper