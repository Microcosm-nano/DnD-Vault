---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Revenant"]
---
# Revenant
*Source: Monster Manual (2024) p. 259*  
![Revenant Followed by a Graveyard Revenant](2-Mechanics/CLI/bestiary/undead/img/revenant-and-graveyard-revenant.webp#right)

Revenants possess the bodies they had in life, using them to hunt down their killers. If their bodies are destroyed, they take control of new bodies that gradually change to resemble the revenants' original forms.

## Revenants

*Vengeance from beyond the Grave*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** Any  

Wrathful spirits bent on revenge, revenants possess corpses and other materials, using them to seek justice or vent their rage on those who wronged them. Revenants refuse to rest until those they seek to punish are no more. If their bodies are destroyed, revenants claim new forms and continue their ruthless quests.

## Statblock

```ad-statblock
title: Revenant
![](2-Mechanics/CLI/bestiary/undead/token/revenant-xmm.webp#token)
*Medium undead, Neutral*

- **Armor Class** 13 
- **Hit Points** 127 (`15d8 + 60`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|18 (+4)|13 (+1)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Constitution +7, Wisdom +6, Charisma +7
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic, psychic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Common plus one other language
- **Challenge** 5

## Traits

***Regeneration.*** The revenant regains 10 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) at the start of each of its turns. If the revenant takes Fire or Radiant damage, this trait doesn't function at the start of its next turn. Its body is destroyed only if it starts its turn with 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) and doesn't regenerate.

***Undead Restoration.*** If the revenant dies, it revives 24 hours later in a different body unless [Dispel Evil and Good](2-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md) is cast on its corpse. If it revives, it animates a Humanoid corpse elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

## Actions

***Multiattack.*** The revenant uses Vengeful Glare and makes two Slam attacks.

***Slam.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 11 (`2d6 + 4`) Necrotic damage.

***Vengeful Glare.*** *Wisdom Saving Throw:* DC 15, one creature the revenant can see within 30 feet. *Failure:* The target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. If the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target is cursed by the revenant (see Vow of Revenge), the target also has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition for the duration.

## Bonus Actions

***Vow of Revenge (1/Day).*** The revenant curses one creature it can see within 30 feet of itself. The revenant knows the distance to and direction of the cursed target, even if it is on a different plane of existence. The curse ends on the target if the revenant uses this [Bonus Action](2-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) on a different creature.
```
^statblock

## Environment

forest, swamp, urban