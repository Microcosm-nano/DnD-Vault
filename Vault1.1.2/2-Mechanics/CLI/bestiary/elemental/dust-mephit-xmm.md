---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/elemental
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/elemental
aliases: ["Dust Mephit"]
---
# Dust Mephit
*Source: Monster Manual (2024) p. 206*  
![](2-Mechanics/CLI/bestiary/elemental/img/mephits.webp#right)

Dust mephits are composed of air and fine earth. They are drawn to forsaken places, and they think everything associated with death is hilarious.

## Mephits

*Malicious Elemental Hooligans*

- **Habitat.** Planar (Elemental Planes)  
- **Treasure.** None  

Mephits are mean-spirited tricksters that dwell on the Elemental Planes. The six most prominent types of mephits resemble halfling-size gargoyles with wings, exaggerated features, and bodies composed of two elements. Most live self-interested existences, indulging their warped senses of humor or overblown egos on their home planes of existence. Some serve as messengers or spies for genies or magic-users.

Mephits resent leaving the elemental extremes where they make their homes. If loosed on the Material Plane or other realms, they lash out with nasty pranks or by tormenting weaker creatures. When destroyed, mephits explode in a burst of elemental magic.

> [!quote] A quote from Seamusxanthuszenus, smoke mephit with a typically inflated impression of itself  
> 
> I am Seamusxanthuszenus, Slayer of Fiends, Merchant Most Excellent, Purveyor of Death!


## Statblock

```ad-statblock
title: Dust Mephit
![](2-Mechanics/CLI/bestiary/elemental/token/dust-mephit-xmm.webp#token)
*Small elemental, Neutral Evil*

- **Armor Class** 12 
- **Hit Points** 17 (`5d6`) 
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 5 (-3)|14 (+2)|10 (+0)| 9 (-1)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +2, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Vulnerabilities** fire
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Primordial (Auran, Terran)
- **Challenge** 1/2

## Traits

***Death Burst.*** The mephit explodes when it dies. *Dexterity Saving Throw:* DC 10, each creature in a 5-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the mephit. *Failure:* 5 (`2d4`) Bludgeoning damage. *Success:* Half damage.

***Sleep (1/Day).*** The mephit casts the [Sleep](2-Mechanics/CLI/spells/sleep-xphb.md) spell, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 10).

**1/day**: [Sleep](2-Mechanics/CLI/spells/sleep-xphb.md)

## Actions

***Claw.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 4 (`1d4 + 2`) Slashing damage.

***Blinding Breath (Recharge 6).*** *Dexterity Saving Throw:* DC 10, each creature in a 15-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the end of the mephit's next turn.
```
^statblock

## Environment

planar, elemental