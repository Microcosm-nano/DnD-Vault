---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
aliases: ["Graveyard Revenant"]
---
# Graveyard Revenant
*Source: Monster Manual (2024) p. 260*  
![](2-Mechanics/CLI/bestiary/undead/img/revenant-and-graveyard-revenant.webp#right)

Graveyard revenants possess dozens of bodies that combine to form grotesque masses. They take revenge on those responsible for mass deaths or institutions that callously ruin lives.

## Revenants

*Vengeance from beyond the Grave*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** Any  

Wrathful spirits bent on revenge, revenants possess corpses and other materials, using them to seek justice or vent their rage on those who wronged them. Revenants refuse to rest until those they seek to punish are no more. If their bodies are destroyed, revenants claim new forms and continue their ruthless quests.

## Statblock

```ad-statblock
title: Graveyard Revenant
![](2-Mechanics/CLI/bestiary/undead/token/graveyard-revenant-xmm.webp#token)
*Huge undead, Neutral*

- **Armor Class** 14 
- **Hit Points** 161 (`14d12 + 70`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|20 (+5)|13 (+1)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +8, Constitution +8, Wisdom +6, Charisma +7
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** necrotic, psychic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common plus two other languages
- **Challenge** 7

## Traits

***Undead Restoration.*** If the revenant dies, it revives 24 hours later unless [Dispel Evil and Good](2-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md) is cast on its remains. If it revives, it animates another group of corpses elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

## Actions

***Multiattack.*** The revenant makes two Suffocate attacks.

***Suffocate.*** *Melee Attack Roll:* `+8`, reach 10 ft. *Hit:* 10 (`1d10 + 5`) Bludgeoning damage plus 10 (`3d6`) Necrotic damage. If the target is a Large or smaller creature, it has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 15). Until the grapple ends, the target is suffocating. The revenant can have up to two targets [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way at a time.

***Haunting Glare (Recharge 5-6).*** *Wisdom Saving Throw:* DC 15, each creature in a 30-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the revenant. *Failure:* The target has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
```
^statblock

## Environment

forest, swamp, urban