---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
aliases: ["Guardian Naga"]
---
# Guardian Naga
*Source: Monster Manual (2024) p. 161*  
![](2-Mechanics/CLI/bestiary/celestial/img/guardian-naga.webp#right)

## Guardian Naga

*Enduring Serpentine Lore Keeper*

- **Habitat.** Desert, Forest, Planar (Upper Planes)  
- **Treasure.** Relics  

Guardian nagas are immortal, serpentine scholars that possess perfect memories. They collect the histories and lore of those they live among, guarding cultures' stories and passing them on to new generations with infallible accuracy. Guardian nagas that outlive their host civilizations might linger in whatever ruins remain, preserving the civilizations' stories so their lost people might live on.

Roll on or choose a result from the Guardian Naga Lore table to inspire what a naga knows.

**Guardian Naga Lore**

`dice: [](guardian-naga-xmm.md#^guardian-naga-lore)`

| dice: 1d8 | The Guardian Naga Recalls... |
|-----------|------------------------------|
| 1 | The last words of an ancient sage or leader. |
| 2 | The location of a hidden city or continent. |
| 3 | A magic word, password, or riddle's answer. |
| 4 | The names of all who have told it stories. |
| 5 | An otherwise forgotten ritual or spell. |
| 6 | Recipes using regional ingredients. |
| 7 | Stories of forgotten gods and local spirits. |
| 8 | The vulnerabilities of a legendary monster. |
^guardian-naga-lore

```ad-statblock
title: Guardian Naga
![](2-Mechanics/CLI/bestiary/celestial/token/guardian-naga-xmm.webp#token)
*Large celestial, Lawful Good*

- **Armor Class** 18 
- **Hit Points** 136 (`16d10 + 48`) 
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|18 (+4)|16 (+3)|16 (+3)|19 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Constitution +7, Intelligence +7, Wisdom +8, Charisma +8
- **Skills** Arcana +11, History +11, Religion +11
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Celestial, Common
- **Challenge** 10

## Traits

***Celestial Restoration.*** If the naga dies, it returns to life in `1d6` days and regains all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) unless [Dispel Evil and Good](2-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md) is cast on its remains.

***Spellcasting.*** The naga casts one of the following spells, requiring no Somatic or Material components and using Wisdom as the spellcasting ability (spell save DC 16):

**At will**: [Thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy-xphb.md)

**1/day each**: [Clairvoyance](2-Mechanics/CLI/spells/clairvoyance-xphb.md), [Cure Wounds](2-Mechanics/CLI/spells/cure-wounds-xphb.md) (level 6 version), [Flame Strike](2-Mechanics/CLI/spells/flame-strike-xphb.md) (level 6 version), [Geas](2-Mechanics/CLI/spells/geas-xphb.md), [True Seeing](2-Mechanics/CLI/spells/true-seeing-xphb.md)

## Actions

***Multiattack.*** The naga makes two Bite attacks. It can replace any attack with a use of Poisonous Spittle.

***Bite.*** *Melee Attack Roll:* `+8`, reach 10 ft. *Hit:* 17 (`2d12 + 4`) Piercing damage plus 22 (`4d10`) Poison damage.

***Poisonous Spittle.*** *Constitution Saving Throw:* DC 16, one creature the naga can see within 60 feet. *Failure:* 31 (`7d8`) Poison damage, and the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the start of the naga's next turn. *Success:* Half damage only.
```
^statblock

## Environment

desert, forest, planar, upper