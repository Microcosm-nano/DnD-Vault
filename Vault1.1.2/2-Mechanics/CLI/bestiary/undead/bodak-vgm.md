---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/vgm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
aliases: ["Bodak"]
---
# Bodak
*Source: Volo's Guide to Monsters p. 127, Ghosts of Saltmarsh*  
![](2-Mechanics/CLI/bestiary/undead/img/bodak.webp#right)

A bodak is the undead remains of someone who revered Orcus. Devoid of life and soul, it exists only to cause death.

## Marked by Orcus

A worshiper of Orcus can take ritual vows while carving the demon lord's symbol on its chest over the heart. Orcus's power flays body, mind, and soul, leaving behind a sentient husk that sucks in all life energy near it. Most bodaks come into being in this way, then unleashed to spread death in Orcus's name.

Orcus created the first bodaks in the Abyss from seven devotees, called the Hierophants of Annihilation. These figures, as mighty as balors, have free will but serve the Prince of Undeath directly. Any one of these bodaks can turn a slain mortal into a bodak with its gaze. Like each Hierophant of Annihilation, every bodak bears the mark of Orcus as a chest wound, an opening where a mortal humanoid's heart would be.

Orcus can recall anything a bodak sees or hears. If he so chooses, he can speak through a bodak to address his enemies and followers directly. Bodaks are extensions of Orcus's will outside the Abyss, serving the demon prince's aims and other minions.

Even nature despises bodaks. The sun burns away a bodak's tainted flesh. The creature's gaze lays waste to the living. Anyone a bodak slays with its gaze withers, its face frozen in a mask of terror. The monster's mere presence is so unnatural that it chills the soul. Animals untrained for war instinctively flee just before a bodak arrives.

## Unhallowed Fragments

A bodak retains vague impressions of its past life. It seeks out both its former allies and its former enemies to destroy them, as its warped soul seeks to erase anything connected to its former life. Minions of Orcus are the one exception to this compulsion; a bodak recognizes them as kindred souls and spares them from its wrath. Anyone who knew the individual before its transformation into a bodak can recognize mannerisms or other subtle clues to its original identity.

## Ravaged Soul

The soul of a creature that becomes a bodak is so damaged that it is unfit for most forms of magical resurrection. Only a [wish](2-Mechanics/CLI/spells/wish-xphb.md) spell or similar magic can return a bodak to its former life.

## Undead Nature

A bodak doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Bodak
![](2-Mechanics/CLI/bestiary/undead/token/bodak-vgm.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 58 (`9d8 + 18`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|16 (+3)|15 (+2)| 7 (-2)|12 (+1)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +6
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** cold; fire; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, the languages it knew in life
- **Challenge** 6

## Traits

***Aura of Annihilation.*** The bodak can activate or deactivate this feature as a bonus action. While active, the aura deals 5 necrotic damage to any creature that ends its turn within 30 feet of the bodak. Undead and fiends ignore this effect.

***Death Gaze.*** When a creature that can see the bodak's eyes starts its turn within 30 feet of the bodak, the bodak can force it to make a DC 13 Constitution saving throw if the bodak isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and can see the creature. If the saving throw fails by 5 or more, the creature is reduced to 0 hit points, unless it is immune to the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition. Otherwise, a creature takes 16 (`3d10`) psychic damage on a failed save.

Unless [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised), a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it has disadvantage on attack rolls against the bodak until the start of its next turn. If the creature looks at the bodak in the meantime, it must immediately make the saving throw.

***Sunlight Hypersensitivity.*** The bodak takes 5 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

## Actions

***Fist.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 4 (`1d4 + 2`) bludgeoning damage plus 9 (`2d8`) necrotic damage.

***Withering Gaze.*** One creature that the bodak can see within 60 feet of it must make a DC 13 Constitution saving throw, taking 22 (`4d10`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

underdark, swamp, urban