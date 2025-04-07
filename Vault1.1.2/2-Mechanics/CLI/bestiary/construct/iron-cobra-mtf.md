---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mtf
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
aliases: ["Iron Cobra"]
---
# Iron Cobra
*Source: Mordenkainen's Tome of Foes p. 125, Ghosts of Saltmarsh*  
![](2-Mechanics/CLI/bestiary/construct/img/iron-cobra.webp#right)

> [!quote] A quote from Mordenkainen  
> 
> Never depend on something built by a gnome. You can always rely on a gnome to take a good idea and make it impractical.

## Iron Cobra

An iron cobra is exactly what its name implies: a metal snake with a poisonous bite. In addition to standard poisons, gnomes load this clockwork with alchemical concoctions that can paralyze creatures and cloud their minds with paranoia.

The gnomes' efforts to invent and tinker with magic and mechanical devices produce many failed constructs, but also result in genuine advances, such as clockworks. Since their discovery, the methods used to craft clockworks have passed from one community of gnomes to another and down the generations.

## Constructed Nature

A clockwork doesn't require air, food, drink, or sleep.

## Individual Designs

A gnome artisan values an individualized clockwork more highly than a perfectly functioning one that copies too much from another creation. For that reason, even clockworks that fit established designs, such as those described here, are seldom identical.

A clockwork can be customized by adding one of the following enhancements and one potential malfunction to its stat block. You can select randomly or choose a pair of modifications that fit the temperament of the clockwork's builder.

**Clockwork Enhancements**

`dice: [](iron-cobra-mtf.md#^clockwork-enhancements)`

| dice: d10 | Enhancement |
|-----------|-------------|
| 1 | **Camouflaged.** The clockwork gains proficiency in [Stealth](2-Mechanics/CLI/rules/skills.md#Stealth) if it doesn't already have it. While motionless, it is indistinguishable from a stopped machine. |
| 2 | **Sensors.** The range of the clockwork's [darkvision](2-Mechanics/CLI/rules/senses.md#Darkvision) becomes 120 feet, unless it is higher, and it gains proficiency in [Perception](2-Mechanics/CLI/rules/skills.md#Perception) if it doesn't already have it. |
| 3 | **Improved Armor.** The clockwork's AC increases by 2. |
| 4 | **Increased Speed.** The clockwork's speed increases by 10 feet. |
| 5 | **Reinforced Construction.** The clockwork has resistance to force, lightning, and thunder damage. |
| 6 | **Self-Repairing.** If the clockwork starts its turn with at least 1 hit point, it regains 5 hit points. If it takes lightning damage, this ability doesn't function at the start of its next turn. |
| 7 | **Sturdy Frame.** The clockwork's hit point maximum increases by an amount equal to its number of Hit Dice. |
| 8 | **Suction.** The clockwork gains a climbing speed of 30 feet. |
| 9 | **Vocal Resonator.** The clockwork gains the ability to speak rudimentary Common or Gnomish (creator's choice). |
| 10 | **Water Propulsion.** The clockwork gains a swimming speed of 30 feet. |
^clockwork-enhancements

**Clockwork Malfunctions**

`dice: [](iron-cobra-mtf.md#^clockwork-malfunctions)`

| dice: d10 | Malfunction |
|-----------|-------------|
| 1 | **Faulty Sensors.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its turn. |
| 2 | **Flawed Targeting.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork makes attack rolls with disadvantage until the end of its turn. |
| 3 | **Ground Fault.** The clockwork has vulnerability to lightning damage. |
| 4 | **Imprinting Loop.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork mistakes one creature it can see within 30 feet for its creator. The clockwork won't willingly harm that creature for 1 minute or until that creature attacks it or deals damage to it. |
| 5 | **Leaking Lubricant.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork gains 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) that it isn't immune to. |
| 6 | **Limited Steering.** The clockwork must move in a straight line. It can turn up to 90 degrees before moving and again at the midpoint of its movement. It can rotate freely if it doesn't use any of its speeds on its turn. |
| 7 | **Overactive Sense of Self-Preservation.** If the clockwork has half its hit points or fewer at the start of its turn in combat, roll a `d6`. If you roll a 1, it retreats from combat. If retreat isn't possible, it continues fighting. |
| 8 | **Overheats.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its turn. |
| 9 | **Rusty Gears.** The clockwork has disadvantage on initiative rolls, and its speed decreases by 10 feet. |
| 10 | **Weak Armor.** The clockwork isn't immune to bludgeoning, piercing, and slashing damage from nonmagical attacks that aren't adamantine. |
^clockwork-malfunctions

## Statblock

```ad-statblock
title: Iron Cobra
![](2-Mechanics/CLI/bestiary/construct/token/iron-cobra-mtf.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 13 
- **Hit Points** 45 (`7d8 + 14`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|14 (+2)| 3 (-4)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +7
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands one language of its creator but can't speak
- **Challenge** 4

## Traits

***Magic Resistance.*** The iron cobra has advantage on saving throws against spells and other magical effects.

## Actions

***Bite.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) piercing damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw or suffer one random poison effect:

1. Poison Damage: The target takes 13 (`3d8`) poison damage.

2. Confusion: On its next turn, the target must use its action to make one weapon attack against a random creature it can see within 30 feet of it, using whatever weapon it has in hand and moving beforehand if necessary to get in range. If it's holding no weapon, it makes an unarmed strike. If no creature is visible within 30 feet, it takes the Dash action, moving toward the nearest creature.

3. Paralysis: The target is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the end of its next turn.
```
^statblock

## Environment

forest, grassland, hill, mountain