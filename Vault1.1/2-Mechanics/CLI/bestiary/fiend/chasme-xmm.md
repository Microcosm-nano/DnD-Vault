---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/abyss
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
aliases: ["Chasme"]
---
# Chasme
*Source: Monster Manual (2024) p. 69*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/chasme.webp#right)

## Chasme

*Demon of Betrayal and Sycophancy*

- **Habitat.** Planar (Abyss)  
- **Treasure.** Relics  

Flying forth from the Abyss, chasmes resemble horse-size flies. They incapacitate foes by producing a mind-numbing droning, then use their proboscises to drain victims of life. In the Abyss, most chasmes obsequiously serve more powerful demons and search for captives to press into demonic hordes.

```ad-statblock
title: Chasme
![](2-Mechanics/CLI/bestiary/fiend/token/chasme-xmm.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 15 
- **Hit Points** 78 (`12d10 + 12`) 
- **Speed** 20 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|15 (+2)|12 (+1)|11 (+0)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Wisdom +5
- **Skills** Perception +5
- **Senses** blindsight 10 ft., darkvision 120 ft., passive Perception 15
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal; telepathy 120 ft.
- **Challenge** 6

## Traits

***Demonic Restoration.*** If the chasme dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere in the Abyss.

***Magic Resistance.*** The chasme has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spider Climb.*** The chasme can climb difficult surfaces, including along ceilings, without needing to make an ability check.

## Actions

***Proboscis.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 16 (`4d6 + 2`) Piercing damage plus 21 (`6d6`) Necrotic damage. If the target is a creature, its [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the Necrotic damage taken.

## Bonus Actions

***Drone.*** *Constitution Saving Throw:* DC 12, each creature in a 30-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the chasme (demons automatically succeed on this save). *Failure:* The target has the [Unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition and repeats the save at the end of each of its turns. The target succeeds automatically after 10 minutes or if it takes damage or a creature within 5 feet of it takes an action to empty a flask of Holy Water on it. *Success:* The target is immune to this chasme's Drone for 24 hours.
```
^statblock

## Environment

planar, abyss