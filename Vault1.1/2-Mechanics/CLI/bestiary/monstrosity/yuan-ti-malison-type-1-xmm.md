---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
aliases: ["Yuan-ti Malison (Type 1)"]
---
# Yuan-ti Malison (Type 1)
*Source: Monster Manual (2024) p. 343*  
![Yuan-Ti Malison type 1 (left) and type 2 (right)](2-Mechanics/CLI/bestiary/monstrosity/img/yuan-ti-malison-type-1-and-yuan-ti-malison-type-2.webp#right)

Malisons exhibit snakelike features that make them deadly in combat.

- **Type 1.** These malisons have human bodies and the heads of giant, venomous snakes.  

Malisons possesses deadly venom, which some manipulate into magical strikes. They can also shape-shift into snakes, helping them to position themselves for surprise attacks or to slither away with nary a trace.

## Yuan-ti

*Power-Hungry Serpentine Conspirators*

- **Habitat.** Desert, Forest, Swamp, Urban  
- **Treasure.** Relics  

Exploiting pacts with sinister supernatural forces, yuan-ti bargain away their humanity for the lethality and predatory deviousness of serpents. From hidden bastions, they manipulate rulers and the wealthy, seeking to control the world. Many yuan-ti possess venomous magic, which often manifests as fangs or striking serpents.

Yuan-ti have humanlike forms with a variety of horrifying serpentine transformations. Some have a scattering of reptilian scales, while others are giants that are more snake than human. Typically, the more snakelike yuan-ti are, the greater esteem they hold among their kind.

Yuan-ti might gain their reptilian features through dangerous supernatural rites. Roll on or choose a result from the Yuan-ti Transformations table to inspire how yuan-ti obtain their serpentine aspects.

**Yuan-ti Transformations**

`dice: [](yuan-ti-malison-type-1-xmm.md#^yuan-ti-transformations)`

| dice: 1d6 | A Yuan-ti Gained Its Snake Features From... |
|-----------|---------------------------------------------|
| 1 | Bargaining parts of its soul to a pantheon of serpentine demigods. |
| 2 | A curse laid on its people in the distant past. |
| 3 | The dream-venom of Merrshaulk, a slumbering snake god. |
| 4 | Experiments by spirit nagas or other yuan-ti. |
| 5 | A ritual involving the skin of a fiendish snake. |
| 6 | Trials to excise its "weak" human parts. |
^yuan-ti-transformations

> [!quote] A quote from Last Message of Sorril Venil, Explorer of the Labyrinth of Madness  
> 
> Great magic, twisted and corrupted... Malice beyond reckoning... Flesh reshaped, becoming serpentine horrors...


![](2-Mechanics/CLI/bestiary/monstrosity/img/yuan-ti.webp#center)

## Statblock

```ad-statblock
title: Yuan-ti Malison (Type 1)
![](2-Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-malison-type-1-xmm.webp#token)
*Medium monstrosity, Neutral Evil*

- **Armor Class** 12 
- **Hit Points** 66 (`12d8 + 12`) 
- **Speed** 30 ft., climb 30 ft. (snake form only)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|13 (+1)|14 (+2)|16 (+3)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4 (+6 while in snake form)
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 3

## Traits

***Magic Resistance.*** The yuan-ti has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting (Yuan-ti Form Only).*** The yuan-ti casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 13):

**At will**: [Animal Friendship](2-Mechanics/CLI/spells/animal-friendship-xphb.md) (snakes only)

**2/day**: [Suggestion](2-Mechanics/CLI/spells/suggestion-xphb.md)

## Actions

***Multiattack.*** The yuan-ti makes two attacks, using Bite or Poison Ray in any combination, and it can use Spellcasting to cast [Suggestion](2-Mechanics/CLI/spells/suggestion-xphb.md) if available.

***Bite.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 5 (`1d4 + 3`) Piercing damage plus 7 (`2d6`) Poison damage.

***Poison Ray (Yuan-ti Form Only).*** *Ranged Attack Roll:* `+5`, range 120 ft. *Hit:* 12 (`2d8 + 3`) Poison damage.

## Bonus Actions

***Shape-Shift.*** The yuan-ti shape-shifts into a Medium snake or returns to its true form. If it dies, it stays in its current form. The yuan-ti's game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.
```
^statblock

## Environment

desert, forest, swamp, urban