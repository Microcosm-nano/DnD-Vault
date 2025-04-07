---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
aliases: ["Myconid Sovereign"]
---
# Myconid Sovereign
*Source: Monster Manual (2024) p. 223*  
![](2-Mechanics/CLI/bestiary/plant/img/myconids.webp#right)

Myconid sovereigns resemble towering myconid adults with elaborate fungal growths. They direct their lesser kin and see to the health and growth of vast fungal blooms.

## Myconids

*Keepers of the Spore*

- **Habitat.** Underdark  
- **Treasure.** Any  

Myconids dwell in remote Underdark reaches overgrown with molds and mushrooms. These ambulatory fungal creatures tend to their sanctuaries and avoid becoming embroiled in the conflicts of other creatures. They use specialized spores to communicate, to alert one another to danger, and to defend themselves. When myconids encounter others beings, they use mind-linking spores to allow nearby creatures to telepathically share thoughts. Nevertheless, myconids' goals remain mysterious to most non-fungal creatures.

## Statblock

```ad-statblock
title: Myconid Sovereign
![](2-Mechanics/CLI/bestiary/plant/token/myconid-sovereign-xmm.webp#token)
*Large plant, Lawful Neutral*

- **Armor Class** 13 
- **Hit Points** 45 (`6d10 + 12`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|10 (+0)|14 (+2)|13 (+1)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 12
- **Languages** telepathy 240 ft.
- **Challenge** 2

## Traits

***Sun Sickness.*** While in sunlight, the myconid has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on [D20 Tests](2-Mechanics/CLI/rules/variant-rules/d20-test-xphb.md). The myconid dies if it spends more than 1 hour in sunlight.

## Actions

***Multiattack.*** The myconid makes one Slam attack and uses Pacifying Spores.

***Slam.*** *Melee Attack Roll:* `+3`, reach 5 ft. *Hit:* 6 (`2d4 + 1`) Bludgeoning damage plus 5 (`2d4`) Poison damage.

***Animating Spores (3/Day).*** The myconid releases spores at a Medium or Small corpse within 5 feet of it that wasn't a Construct or an Undead. In 24 hours, the corpse rises as a [Myconid Spore Servant](2-Mechanics/CLI/bestiary/plant/myconid-spore-servant-xmm.md). The corpse stays animate for `1d4 + 1` weeks or until destroyed, and it can't be animated again in this way.

***Pacifying Spores.*** *Constitution Saving Throw:* DC 12, one creature the myconid can see within 10 feet. *Failure:* The target has the [Stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

***Rapport Spores.*** The myconid expels spores in a 30-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from itself. Creatures in that area with an Intelligence score of 2 or higher that aren't Constructs, Elementals, or Undead gain telepathy with a range of 30 feet for 1 hour.
```
^statblock

## Environment

underdark