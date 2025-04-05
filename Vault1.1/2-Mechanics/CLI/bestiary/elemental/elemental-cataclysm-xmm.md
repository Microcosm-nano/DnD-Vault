---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/environment/elemental-chaos
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental/titan
aliases: ["Elemental Cataclysm"]
---
# Elemental Cataclysm
*Source: Monster Manual (2024) p. 111*  
![](2-Mechanics/CLI/books/monster-manual-2025/img/elemental-cataclysm.webp#right)

## Elemental Cataclysm

*The End and Beginning of Ages*

- **Habitat.** Planar (Elemental Chaos)  
- **Treasure.** None  

Beyond the fringes of the Elemental Planes, primordial forces endlessly clash amid the Elemental Chaos. Within the vastness and violence of this realm rage elemental cataclysms, entities spawned from the raw forces of the multiverse and awash in dissonant elemental powers. These beings of primal conflict annihilate nearly all they encounter and seed the ruins left in their wake with the potential for new creations.

Elemental cataclysms rarely escape the Elemental Chaos. When they do, it is typically due to some planar disruption or the summons of nihilistic cultists. When they emerge on Material Plane worlds, elemental cataclysms create realm-altering trails of destruction, carelessly destroying cities and throwing whole nations into chaos. The rampages aren't random. Elemental cataclysms abhor anything that visibly mars nature, be it mines or monuments, fortresses or cities, but they vent their most intense rage on works of metal and clockwork. As they sow destruction, they howl condemnation and chant words of unmaking in the languages of the Inner Planes.

Little can stop an elemental cataclysm. Those that oppose one of these calamities often attempt to reverse the ritual that summoned it, coax it through a planar rift, or conjure another titan in hopes that the two destroy one another. These terrors leave a wake of ashes, floods, storms, and broken earth. But after these disasters recede, the land is imbued with new life or environmental changes. Roll on or choose a result from the Elemental Alterations table to inspire what changes emerge after an elemental cataclysm's destruction.

**Elemental Alterations**

`dice: [](elemental-cataclysm-xmm.md#^elemental-alterations)`

| dice: 1d8 | The Elemental Cataclysm Leaves Behind A... |
|-----------|--------------------------------------------|
| 1 | Dramatic increase or decrease in temperature. |
| 2 | Gigantic coral reef or fungal forest. |
| 3 | Never-ending storm or whirlpool. |
| 4 | Passage to the Underdark or portal to an Elemental Plane. |
| 5 | Primeval or previously extinct animal population. |
| 6 | Rapidly growing rainforest. |
| 7 | River where previously there was none. |
| 8 | Series of dramatic rock formations. |
^elemental-alterations

```ad-statblock
title: Elemental Cataclysm
![](2-Mechanics/CLI/bestiary/elemental/token/elemental-cataclysm-xmm.webp#token)
*Gargantuan elemental (titan), Chaotic Neutral*

- **Armor Class** 20 
- **Hit Points** 370 (`20d20 + 160`) 
- **Speed** 60 ft., burrow 60 ft., fly 80 ft. (hover), swim 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|19 (+4)|27 (+8)| 9 (-1)|14 (+2)| 9 (-1)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +11, Constitution +15, Wisdom +9, Charisma +6
- **Skills** ⏤
- **Senses** truesight 150 ft., passive Perception 12
- **Damage Immunities** acid, cold, fire, lightning, poison, thunder
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Primordial
- **Challenge** 22

## Traits

***Earth Glide.*** The cataclysm can burrow through nonmagical, unworked earth and stone. While doing so, the cataclysm doesn't disturb the material it moves through.

***Legendary Resistance (4/Day).*** If the cataclysm fails a saving throw, it can choose to succeed instead.

***Siege Monster.*** The cataclysm deals double damage to objects and structures.

***Control Weather.*** The cataclysm casts the [Control Weather](2-Mechanics/CLI/spells/control-weather-xphb.md) spell, requiring no spell components and using Constitution as the spellcasting ability.

**At will**: [Control Weather](2-Mechanics/CLI/spells/control-weather-xphb.md)

## Actions

***Multiattack.*** The cataclysm makes two Elemental Burst attacks.

***Elemental Burst.*** *Melee or Ranged Attack Roll:* `+15`, reach 30 ft. or range 150 ft. *Hit:* 25 (`5d6 + 8`) damage of a type chosen by the cataclysm: Acid, Cold, Fire, Lightning, or Thunder.

***Cataclysmic Event (Recharge 4-6).*** The cataclysm creates one of the following effects at random (roll `1d4`):

- **1 Clinging Flames.** *Dexterity Saving Throw:* DC 23, each creature in a 60-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the cataclysm can see within 150 feet. *Failure:* 45 (`13d6`) Fire damage. *Success:* Half damage. *Failure or Success:* The target starts burning.  
- **2 Freezing Waves.** *Strength Saving Throw:* DC 23, each creature in a 90-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 22 (`5d8`) Bludgeoning damage plus 22 (`5d8`) Cold damage, and the target has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. *Success:* Half damage only. *Failure or Success:* The target's [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) is reduced to 0 until the end of its next turn.  
- **3 Raging Storm.** A storm cloud fills a 60-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the cataclysm can see within 150 feet. The cloud lasts for 1 minute or until the cataclysm uses Cataclysmic Event again. Creatures entirely in the cloud have the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [Deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) conditions and can't cast spells with a Verbal component. *Dexterity Saving Throw:* DC 23, each creature that enters the cloud for the first time on a turn or starts its turn there. *Failure:* 18 (`4d8`) Lightning damage plus 18 (`4d8`) Thunder damage. *Success:* Half damage.  
- **4 Swallowing Earth.** *Strength Saving Throw:* DC 23, each creature in a 90-foot [Cube](2-Mechanics/CLI/rules/variant-rules/cube-area-of-effect-xphb.md) originating from a point on the ground within 150 feet. *Failure:* 18 (`4d8`) Bludgeoning damage plus 18 (`4d8`) Acid damage, and the target has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition and is buried under rubble. A buried target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, has [Total Cover](2-Mechanics/CLI/rules/variant-rules/cover-xphb.md), and is suffocating. As an action, a buried creature or another creature within 5 feet of it can make a DC 18 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check. On a successful check, the creature is no longer buried. *Success:* Half damage only.  

## Legendary Actions

***Eruption.*** The cataclysm makes one Elemental Burst attack.

***Rumbling Movement.*** The cataclysm moves up to its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), [Fly Speed](2-Mechanics/CLI/rules/variant-rules/fly-speed-xphb.md), or [Swim Speed](2-Mechanics/CLI/rules/variant-rules/swim-speed-xphb.md) without provoking Opportunity Attacks. Each creature within 5 feet of the cataclysm as it moves is targeted once by the following effect. *Constitution Saving Throw:* DC 23. *Failure:* The target has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. *Failure or Success:* The cataclysm can't take this action again until the start of its next turn.
```
^statblock

## Environment

planar, elemental chaos