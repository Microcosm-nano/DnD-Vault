---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Gladiator"]
---
# Gladiator
*Source: Monster Manual (2024) p. 139*  
![In an undersea arena, the ...](2-Mechanics/CLI/bestiary/humanoid/img/gladiator.webp#right "In an undersea arena, the crowd goes wild as a gladiator triumphs over a giant squid")

## Gladiator

*Competitor and Prizefighter*

- **Habitat.** Any  
- **Treasure.** Armaments, Individual  

Gladiators are professional fighters who pit themselves against one another, monsters, and other challenges to entertain audiences. While some compete merely to survive, others love the thrill of performing—and all gladiators know the importance of theatrics in keeping audiences excited. Roll on or choose an option from the Gladiator Theatrics table to inspire the unique flourishes a gladiator uses when competing.

**Gladiator Theatrics**

`dice: [](gladiator-xmm.md#^gladiator-theatrics)`

| dice: 1d6 | During a Competition, the Gladiator... |
|-----------|----------------------------------------|
| 1 | Dedicates their impending victory to a deity, ruler, beloved noble, or member of the crowd. |
| 2 | Dresses in a monster-themed mask and cape. |
| 3 | Judges whether their foe fights honorably. |
| 4 | Leads the crowd in a rousing theme song. |
| 5 | Seeks to claim a trophy from a foe. |
| 6 | Takes advice from the crowd, omens, or a pet. |
^gladiator-theatrics

```ad-statblock
title: Gladiator
![](2-Mechanics/CLI/bestiary/humanoid/token/gladiator-xmm.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 16 
- **Hit Points** 112 (`15d8 + 45`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|16 (+3)|10 (+0)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Dexterity +5, Constitution +6, Wisdom +4
- **Skills** Athletics +10, Performance +5
- **Senses** passive Perception 11
- **Languages** Common
- **Challenge** 5

## Actions

***Multiattack.*** The gladiator makes three Spear attacks. It can replace one attack with a use of Shield Bash.

***Spear.*** *Melee or Ranged Attack Roll:* `+7`, reach 5 ft. or range 20/60 ft. *Hit:* 11 (`2d6 + 4`) Piercing damage.

***Shield Bash.*** *Strength Saving Throw:* DC 15, one creature within 5 feet that the gladiator can see. *Failure:* 9 (`2d4 + 4`) Bludgeoning damage. If the target is a Medium or smaller creature, it has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

## Reactions

***Parry.*** Trigger: The gladiator is hit by a melee attack roll while holding a weapon. _Response:_ The gladiator adds 3 to its AC against that attack, possibly causing it to miss.
```
^statblock

## Environment

any