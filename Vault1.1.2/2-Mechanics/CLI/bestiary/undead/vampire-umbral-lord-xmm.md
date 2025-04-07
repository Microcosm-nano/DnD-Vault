---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead
aliases: ["Vampire Umbral Lord"]
---
# Vampire Umbral Lord
*Source: Monster Manual (2024) p. 318*  
![](2-Mechanics/CLI/bestiary/undead/img/vampire-umbral-lord.webp#right)

Vampire umbral lords embrace their ties to the darkness, devoting themselves to sinister powers in exchange for access to forbidden magic.

## Vampires

*Blood-Sucking Lords of the Night*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Vampires disguise their accursed, immortal natures, passing as mortals to feed on the blood of the living. While the youngest vampires might be little more than bloodthirsty servants of their creators, the eldest possess incredible cunning and control over supernatural forces of the night.

Undead vampires lie dormant during the day, retreating to resting places hidden from foes and the sun's searing rays. Roll on or choose a result from the Vampire Resting Places table to inspire a vampire's grim sanctuary.

**Vampire Resting Places**

`dice: [](vampire-umbral-lord-xmm.md#^vampire-resting-places)`

| dice: 1d6 | The Vampire's Resting Place Is... |
|-----------|-----------------------------------|
| 1 | Among the roots of a dead tree. |
| 2 | At the bottom of a stagnant pool. |
| 3 | A coffin filled with grave dirt. |
| 4 | A large pot full of blood or vinegar. |
| 5 | A space accessible only by shape-shifting. |
| 6 | Within a statue or suit of armor. |
^vampire-resting-places

### Vampire Lairs

Vampires and vampire umbral lords create sanctuaries apart from the living, whether hidden in cosmopolitan cities or sequestered in ruins where they dwelled in life.

> [!quote] A quote from Astarion, Vampire Spawn  
> 
> Darling, you are simply delicious...


![A vampire familiar provide...](2-Mechanics/CLI/bestiary/undead/img/vampires.webp#center "A vampire familiar provides a meal for a vampire spawn")

## Statblock

```ad-statblock
title: Vampire Umbral Lord
![](2-Mechanics/CLI/bestiary/undead/token/vampire-umbral-lord-xmm.webp#token)
*Small or Medium undead, Lawful Evil*

- **Armor Class** 16 
- **Hit Points** 187 (`22d8 + 88`) 
- **Speed** 40 ft., climb 40 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|18 (+4)|18 (+4)|19 (+4)|16 (+3)|21 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +10, Dexterity +9, Wisdom +8, Charisma +10
- **Skills** Arcana +9, Perception +13, Stealth +9
- **Senses** blindsight 120 ft., passive Perception 23
- **Damage Immunities** cold, necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion)
- **Languages** Common plus three other languages
- **Challenge** 15

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the vampire fails a saving throw, it can choose to succeed instead.

***Shadow Escape.*** If the vampire drops to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) outside its resting place, it teleports into its resting place unless it is in running water or sunlight. If it can't teleport, it is destroyed. Once inside its resting place, it has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition for 1 hour, after which it regains 1 [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

***Vampire Weakness.*** The vampire has these weaknesses:

- **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.  
- **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.  
- **Stake to the Heart.** If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition in its resting place, the vampire has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the weapon is removed.  
- **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks.  

***Hunger of Hadar (Recharge 5-6).*** The vampire casts [Hunger of Hadar](2-Mechanics/CLI/spells/hunger-of-hadar-xphb.md) (level 5 version), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 18).


***Beguile.*** The vampire casts [Command](2-Mechanics/CLI/spells/command-xphb.md), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 18). The vampire can't take this action again until the start of its next turn.


## Actions

***Multiattack.*** The vampire makes two attacks, using Grave Strike or Sickening Ray in any combination.

***Grave Strike.*** *Melee Attack Roll:* `+10`, reach 5 ft. *Hit:* 9 (`1d8 + 5`) Slashing damage plus 13 (`3d8`) Necrotic damage.

***Sickening Ray.*** *Ranged Attack Roll:* `+10`, range 120 ft. *Hit:* 16 (`2d10 + 5`) Necrotic damage, and the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of the vampire's next turn.

## Bonus Actions

***Sanguine Drain.*** *Constitution Saving Throw:* DC 18, one creature the vampire can see within 30 feet that isn't a Construct or an Undead. *Failure:* 14 (`4d6`) Necrotic damage. The target's [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken, and the vampire regains [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to that amount.

## Legendary Actions

***Umbral Strike.*** The vampire moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Grave Strike or Sickening Ray attack.

## Regional effects

The region containing a vampire's lair is warped by its presence, creating the following effects:

- **Children of the Night.** The vampire exerts influence over the animals in its domain. From dusk until dawn, Medium or smaller Beasts have the [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition while within 1 mile of the lair.  
- **Looming Shadows.** Shadows within 1 mile of the lair seem to move as if alive. Any creature (excluding the vampire and its allies) that finishes a [Short Rest](2-Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) while within 1 mile of the lair must succeed on a DC 15 Wisdom saving throw or gain no benefit from that rest.  
- **Mists.** The area within 1 mile of the lair is [Lightly Obscured](2-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md) by a persistent, creeping fog. The vampire and any creatures of its choice are unaffected by the fog.  

If the vampire dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

underdark, urban