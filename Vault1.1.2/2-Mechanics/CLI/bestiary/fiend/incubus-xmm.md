---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
aliases: ["Incubus"]
---
# Incubus
*Source: Monster Manual (2024) p. 178*  
![](2-Mechanics/CLI/bestiary/fiend/img/incubus.webp#right)

## Incubus

*Life-Leeching Dream Stalker*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Any  

Incubi exploit the vulnerability of mortal dreams. Slipping into the homes of sleepers, incubi feed off dreams and replace them with terrifying nightmares. Incubi visit victims nightly until their prey expires. The incubi then hunt for new victims, preferring the loved ones of past targets.

Incubi can transform into succubi and vice versa, taking the forms they need to manipulate foes in dreams or in the flesh.

Those visited by an incubus have recurring nightmares. Roll on or choose a result from the Incubus Nightmares table to inspire these night terrors.

**Incubus Nightmares**

`dice: [](incubus-xmm.md#^incubus-nightmares)`

| dice: 1d8 | The Incubus's Victim Has Dreams Of... |
|-----------|---------------------------------------|
| 1 | An angry family member or authority figure. |
| 2 | Being chased through the wilderness. |
| 3 | Being devoured by animals or monsters. |
| 4 | [Falling](2-Mechanics/CLI/traps-hazards/falling-xphb.md), drowning, or suffocating. |
| 5 | A ruinous public embarrassment. |
| 6 | A shadowy intruder or monstrous silhouette. |
| 7 | A traumatic past event. |
| 8 | A visitor with an eerie or enigmatic message. |
^incubus-nightmares

```ad-statblock
title: Incubus
![](2-Mechanics/CLI/bestiary/fiend/token/incubus-xmm.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 15 
- **Hit Points** 66 (`12d8 + 12`) 
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|17 (+3)|13 (+1)|15 (+2)|12 (+1)|20 (+5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +9, Insight +5, Perception +5, Persuasion +9, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Resistances** cold, fire, poison, psychic
- **Languages** Abyssal, Common, Infernal; telepathy 60 ft.
- **Challenge** 4

## Traits

***Succubus Form.*** When the incubus finishes a [Long Rest](2-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), it can shape-shift into a [Succubus](2-Mechanics/CLI/bestiary/fiend/succubus-xmm.md), using that stat block instead of this one. Any equipment it's wearing or carrying isn't transformed.

***Spellcasting.*** The incubus casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [Disguise Self](2-Mechanics/CLI/spells/disguise-self-xphb.md), [Etherealness](2-Mechanics/CLI/spells/etherealness-xphb.md)

**1/day each**: [Dream](2-Mechanics/CLI/spells/dream-xphb.md), [Hypnotic Pattern](2-Mechanics/CLI/spells/hypnotic-pattern-xphb.md)

## Actions

***Multiattack.*** The incubus makes two Restless Touch attacks.

***Restless Touch.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 15 (`3d6 + 5`) Psychic damage, and the target is cursed for 24 hours or until the incubus dies. Until the curse ends, the target gains no benefit from finishing Short Rests.

## Bonus Actions

***Nightmare (Recharge 6).*** *Wisdom Saving Throw:* DC 15, one creature the incubus can see within 60 feet. *Failure:* If the target has 20 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) or fewer, it has the [Unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition for 1 hour, until it takes damage, or until a creature within 5 feet of it takes an action to wake it. Otherwise, the target takes 18 (`4d8`) Psychic damage.
```
^statblock

## Environment

planar, lower, urban