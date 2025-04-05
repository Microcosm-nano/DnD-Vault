---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/elemental
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/elemental
aliases: ["Steam Mephit"]
---
# Steam Mephit
*Source: Monster Manual (2024) p. 208. Available in the Free Rules (2024)*  
![](2-Mechanics/CLI/bestiary/elemental/img/smoke-and-steam-mephits.webp#right)

These arrogant mephits are made of heat and vaporous water. They often trick creatures into doing them favors, then renege on promised rewards.

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
title: Steam Mephit
![](2-Mechanics/CLI/bestiary/elemental/token/steam-mephit-xmm.webp#token)
*Small elemental, Neutral Evil*

- **Armor Class** 10 
- **Hit Points** 17 (`5d6`) 
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 5 (-3)|11 (+0)|10 (+0)|11 (+0)|10 (+0)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +2
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Primordial (Aquan, Ignan)
- **Challenge** 1/4

## Traits

***Blurred Form.*** Attack rolls against the mephit are made with [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) unless the mephit has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

***Death Burst.*** The mephit explodes when it dies. *Dexterity Saving Throw:* DC 10, each creature in a 5-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the mephit. *Failure:* 5 (`2d4`) Fire damage. *Success:* Half damage.

## Actions

***Claw.*** *Melee Attack Roll:* `+2`, reach 5 ft. *Hit:* 2 (`1d4`) Slashing damage plus 2 (`1d4`) Fire damage.

***Steam Breath (Recharge 6).*** *Constitution Saving Throw:* DC 10, each creature in a 15-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 5 (`2d4`) Fire damage, and the target's [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) decreases by 10 feet until the end of the mephit's next turn. *Success:* Half damage only. *Failure or Success:* Being underwater doesn't grant [Resistance](2-Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to this Fire damage.
```
^statblock

## Environment

planar, elemental