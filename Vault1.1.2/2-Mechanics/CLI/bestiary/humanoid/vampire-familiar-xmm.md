---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Vampire Familiar"]
---
# Vampire Familiar
*Source: Monster Manual (2024) p. 314*  
![A vampire familiar provide...](2-Mechanics/CLI/bestiary/undead/img/vampires.webp#right "A vampire familiar provides a meal for a vampire spawn")

Vampire familiars are living people who serve vampires, either willingly or due to coercion by their deathless masters. They channel deathly energy through their weapons, incapacitating unsuspecting targets and leaving their victims as helpless prey for their vampire masters.

Many vampire familiars aspire to eventually become vampires, while others are magically charmed or serve as part of some terrible bargain. In each case, these vampire servants show signs of their vampiric corruption, such as corpse-like complexions, uncanny reflexes, and evidence of their masters' repeated feedings. A vampire familiar loses its supernatural abilities and returns to its original Humanoid state if its vampire master is destroyed.

## Vampires

*Blood-Sucking Lords of the Night*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Vampires disguise their accursed, immortal natures, passing as mortals to feed on the blood of the living. While the youngest vampires might be little more than bloodthirsty servants of their creators, the eldest possess incredible cunning and control over supernatural forces of the night.

Undead vampires lie dormant during the day, retreating to resting places hidden from foes and the sun's searing rays. Roll on or choose a result from the Vampire Resting Places table to inspire a vampire's grim sanctuary.

**Vampire Resting Places**

`dice: [](vampire-familiar-xmm.md#^vampire-resting-places)`

| dice: 1d6 | The Vampire's Resting Place Is... |
|-----------|-----------------------------------|
| 1 | Among the roots of a dead tree. |
| 2 | At the bottom of a stagnant pool. |
| 3 | A coffin filled with grave dirt. |
| 4 | A large pot full of blood or vinegar. |
| 5 | A space accessible only by shape-shifting. |
| 6 | Within a statue or suit of armor. |
^vampire-resting-places

### Vampire Lairs

Vampires and vampire umbral lords create sanctuaries apart from the living, whether hidden in cosmopolitan cities or sequestered in ruins where they dwelled in life.

> [!quote] A quote from Astarion, Vampire Spawn  
> 
> Darling, you are simply delicious...


## Statblock

```ad-statblock
title: Vampire Familiar
![](2-Mechanics/CLI/bestiary/humanoid/token/vampire-familiar-xmm.webp#token)
*Small or Medium humanoid, Neutral Evil*

- **Armor Class** 15 
- **Hit Points** 65 (`10d8 + 20`) 
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|16 (+3)|15 (+2)|10 (+0)|10 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5, Wisdom +2
- **Skills** Perception +4, Persuasion +4, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) (except from its vampire master)
- **Languages** Common plus one other language
- **Challenge** 3

## Traits

***Vampiric Connection.*** While the familiar and its vampire master are on the same plane of existence, the vampire can communicate with the familiar telepathically, and the vampire can perceive through the familiar's senses.

## Actions

***Multiattack.*** The familiar makes two Umbral Dagger attacks.

***Umbral Dagger.*** *Melee or Ranged Attack Roll:* `+5`, reach 5 ft. or range 20/60 ft. *Hit:* 5 (`1d4 + 3`) Piercing damage plus 7 (`3d4`) Necrotic damage. If the target is reduced to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) by this attack, the target becomes [Stable](2-Mechanics/CLI/rules/variant-rules/stable-xphb.md) but has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 hour. While it has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition, the target has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition.

## Bonus Actions

***Deathless Agility.*** The familiar takes the Dash or Disengage action.
```
^statblock

## Environment

underdark, urban