---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Aberrant Cultist"]
---
# Aberrant Cultist
*Source: Monster Manual (2024) p. 86*  
![](2-Mechanics/CLI/bestiary/humanoid/img/aberrant-cultist.webp#right)

Aberrant cultists pursue mind-bending powers from alien forces. Aberrant cultists align with monsters such as aboleths and mind flayers or forces such as Cthulhu, Hadar, Ityak-Ortheel the Elf Eater, Nyarlathotep, malicious solar bodies, or entities from the Far Realm.

## Cultists

*Doomsayers and Fanatics*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Cultists use magic and extreme measures to spread radical beliefs. Some privately pursue esoteric secrets, while others form shadowy cabals seeking to bring about terrifying ends. Cultists often follow obscure mystical traditions or obsess over interpretations of ancient prophecies. They might worship supernatural patrons—deities, otherworldly creatures, manipulative alien minds, or stranger forces. Roll on or choose a result from the Cultist Agendas table to inspire what a cultist seeks to achieve.

**Cultist Agendas**

`dice: [](aberrant-cultist-xmm.md#^cultist-agendas)`

| dice: 1d6 | The Cultist Strives To... |
|-----------|---------------------------|
| 1 | Bring about the end of a dominant order, an age, or the world. |
| 2 | Burn away the comfortable lies of reality, revealing forgotten or terrible truths. |
| 3 | Expand their faith though mind control or supernatural coercion. |
| 4 | Make global changes, like sinking the land or awakening volcanoes. |
| 5 | Remake life on a mass scale, altering other creatures' bodies or spiritual beings. |
| 6 | Summon their deity or its herald, weapon, or realm into their world. |
^cultist-agendas

### Occult Symbols

Cults often identify with symbols that exemplify their beliefs. Such symbols might mark objects important to the cult, as well as the dress and bodies of cultists themselves. These symbols might be broadly understandable, or they might have meaning only to cultists. Roll twice on or choose results from the Cult Symbols table to inspire a cult's icons.

**Cult Symbols**

`dice: [](aberrant-cultist-xmm.md#^cult-symbols)`

| dice: 1d10 | The Symbol Is... | Depicted As... |
|------------|------------------|----------------|
| 1 | An alchemical sign | A calendar or map |
| 2 | An animal | A crest or as heraldry |
| 3 | A celestial body | An elaborate diagram |
| 4 | A deity's icon | A metaphorical image |
| 5 | An element | A mystical being |
| 6 | An eye | Part of an equation |
| 7 | A geometric shape | A repeating pattern |
| 8 | A letter or number | A series of scratches |
| 9 | Part of a monster | A simple pictogram |
| 10 | A skull | A weapon or tool |
^cult-symbols

### Cult Members

Cults often form hierarchies around a charismatic or domineering leader. While cult members might work independently, they take their orders from superiors with greater supernatural powers. 

### Types of Cultists

Cults can organize around any mystical tradition, but many serve supernatural beings. Cult members often have abilities tied to the forces they worship.

> [!quote] A quote from Rites of the Cult of Elemental Evil  
> 
> Dread Tharizdun, power of the Elder Elemental Eye and master of all destructive forces, I am the Champion of Elemental Evil and am ready to carry out your wishes.


> [!gallery]
![](2-Mechanics/CLI/bestiary/humanoid/img/aberrant-cultist-and-elemental-cultist.webp)
![](2-Mechanics/CLI/bestiary/humanoid/img/cultists.webp)

## Statblock

```ad-statblock
title: Aberrant Cultist
![](2-Mechanics/CLI/bestiary/humanoid/token/aberrant-cultist-xmm.webp#token)
*Small or Medium humanoid, Neutral Evil*

- **Armor Class** 14 
- **Hit Points** 137 (`25d8 + 25`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|19 (+4)|12 (+1)|16 (+3)|18 (+4)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +7
- **Skills** Arcana +6, Perception +7, Religion +6
- **Senses** darkvision 90 ft., passive Perception 17
- **Languages** Common, Deep Speech; telepathy 30 ft.
- **Challenge** 8

***Spellcasting.*** The cultist casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 15):

**At will**: [Detect Thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion-xphb.md)

***Counterspell (2/Day).*** The cultist casts [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md) in response to that spell's trigger, using the same spellcasting ability as Spellcasting.

**2/day**: [Counterspell](2-Mechanics/CLI/spells/counterspell-xphb.md)

## Actions

***Multiattack.*** The cultist makes two Tentacle Lash attacks. It can replace any attack with a use of Mind Rot.

***Tentacle Lash.*** *Melee Attack Roll:* `+7`, reach 10 ft. *Hit:* 7 (`1d6 + 4`) Slashing damage plus 14 (`4d6`) Psychic damage. If the target is a Large or smaller creature, it has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14) from one of two tentacles, and it has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the grapple ends.

***Mind Rot.*** *Wisdom Saving Throw:* DC 15, one creature the cultist can see within 90 feet. *Failure:* 27 (`6d8`) Psychic damage, and the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of the cultist's next turn. *Success:* Half damage only.
```
^statblock

## Environment

any