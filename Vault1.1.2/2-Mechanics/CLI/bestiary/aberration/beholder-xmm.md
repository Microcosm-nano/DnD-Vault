---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
aliases: ["Beholder"]
---
# Beholder
*Source: Monster Manual (2024) p. 36*  
![](2-Mechanics/CLI/bestiary/aberration/img/beholder.webp#right)

## Beholder

*Infamous Many-Eyed Tyrant*

- **Habitat.** Underdark  
- **Treasure.** Arcana  

Beholders—also known as eye tyrants—number among the most notorious inhabitants of the Underdark. Few creatures in the multiverse are as loathed and feared as these maniacal horrors.

A beholder's distinctive, globular body is dominated by an oversize maw and a gigantic central eye. Ten stalks ending in smaller eyes crown its form. From each of these eleven eyes, a beholder can unleash a different magic power. The central eye can deactivate magic, while the smaller eyes emit rays that inflict various dooms—such as petrifying creatures, disintegrating them, slaying them outright, or other effects.

Beholders possess utterly alien minds. Most exhibit paranoid, narcissistic, and megalomaniacal tendencies, and they act on agendas beyond human reasoning. While some keep to themselves, others force weaker creatures into their service. Still others cultivate grand ambitions, creating networks of minions to manipulate groups, settlements, and whole nations in the Underdark and sometimes the surface world.

Few creatures loathe beholders more than other beholders. Every beholder views itself as the physical and intellectual pinnacle of its species. To them, all other beholders are aberrant rivals to be dominated or destroyed. Conflicts between beholders can last for decades and lay waste to vast subterranean realms.

Beholders are a particular threat to adventurers because both gravitate toward mysterious ruins and sites of great magic. Many beholders collect the magic items and [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) bodies of heroes they've defeated, displaying them as trophies.

### Beholder Lairs

Beholders lurk in cavern complexes they've carved using their eye rays deep in the Underdark or in lairs created for them by their servants.

```ad-statblock
title: Beholder
![](2-Mechanics/CLI/bestiary/aberration/token/beholder-xmm.webp#token)
*Large aberration, Lawful Evil*

- **Armor Class** 18 
- **Hit Points** 190 (`20d10 + 80`) 
- **Speed** 5 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|18 (+4)|17 (+3)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +9, Wisdom +7
- **Skills** Perception +12
- **Senses** darkvision 120 ft., passive Perception 22
- **Condition Immunities** [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Deep Speech, Undercommon
- **Challenge** 13

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the beholder fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The beholder uses Eye Rays three times.

***Bite.*** *Melee Attack Roll:* `+8`, reach 5 ft. *Hit:* 13 (`3d6 + 3`) Piercing damage.

***Eye Rays.*** The beholder randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll `1d10`; reroll if the beholder has already used that ray during this turn):

- **1 Charm Ray.** *Wisdom Saving Throw:* DC 16. *Failure:* 13 (`3d8`) Psychic damage, and the target has the [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition for 1 hour or until it takes damage. *Success:* Half damage only.  
- **2 Paralyzing Ray.** *Constitution Saving Throw:* DC 16. *Failure:* The target has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  
- **3 Fear Ray.** *Wisdom Saving Throw:* DC 16. *Failure:* 14 (`4d6`) Psychic damage, and the target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the end of its next turn. *Success:* Half damage only.  
- **4 Slowing Ray.** *Constitution Saving Throw:* DC 16. *Failure:* 18 (`4d8`) Necrotic damage. Until the end of the target's next turn, the target's [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) is halved; the target can't take Reactions; and it can take either an action or a [Bonus Action](2-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) on its turn, not both. *Success:* Half damage only.  
- **5 Enervation Ray.** *Constitution Saving Throw:* DC 16. *Failure:* 13 (`3d8`) Poison damage, and the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of its next turn. While [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the target can't regain [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). *Success:* Half damage only.  
- **6 Telekinetic Ray.** *Strength Saving Throw:* DC 16 (the target succeeds automatically if it is Gargantuan). *Failure:* The beholder moves the target up to 30 feet in any direction. The target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the start of the beholder's next turn or until the beholder has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition. The beholder can also exert fine control on objects with this ray, such as manipulating a tool or opening a door or container.  
- **7 Sleep Ray.** *Wisdom Saving Throw:* DC 16 (the target succeeds automatically if it is a Construct or an Undead). *Failure:* The target has the [Unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition for 1 minute. The condition ends if the target takes damage or a creature within 5 feet of it takes an action to wake it.  
- **8 Petrification Ray.** *Constitution Saving Throw:* DC 16. *1st Failure:* The target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and repeats the save at the end of its next turn if it is still [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), ending the effect on itself on a success. *2nd Failure:* The target has the [Petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition instead of the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition.  
- **9 Disintegration Ray.** *Dexterity Saving Throw:* DC 16. *Failure:* 36 (`8d8`) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot [Cube](2-Mechanics/CLI/rules/variant-rules/cube-area-of-effect-xphb.md) of it disintegrates into dust. *Success:* Half damage. *Failure or Success:* If the target is a creature and this damage reduces it to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), it disintegrates into dust.  
- **10 Death Ray.** *Dexterity Saving Throw:* DC 16. *Failure:* 55 (`10d10`) Necrotic damage. *Success:* Half damage. *Failure or Success:* The target dies if the ray reduces it to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).  

## Bonus Actions

***Antimagic Cone.*** The beholder's central eye emits an antimagic wave in a 150-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Until the start of the beholder's next turn, that area acts as an [Antimagic Field](2-Mechanics/CLI/spells/antimagic-field-xphb.md) spell, and that area works against the beholder's own Eye Rays.

## Legendary Actions

***Chomp.*** The beholder makes two Bite attacks.

***Glare.*** The beholder uses Eye Rays.

## Regional effects

The region containing a beholder's lair is twisted by its presence, creating the following effects:

- **Scopophobia.** Creatures within 1 mile of the lair feel as if they're being watched. Any creature (excluding the beholder and its allies) that finishes a [Short Rest](2-Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) while within 1 mile of the lair must succeed on a DC 13 Wisdom saving throw or gain no benefit from that rest.  
- **Warping Terrain.** Minor warps in reality occur near the lair; any creature (excluding the beholder) within 1 mile of the lair that makes a [D20 Test](2-Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) and rolls a 1 has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.  

If the beholder dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

underdark