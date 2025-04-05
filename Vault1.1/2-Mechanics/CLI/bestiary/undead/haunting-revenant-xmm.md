---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/undead
aliases: ["Haunting Revenant"]
---
# Haunting Revenant
*Source: Monster Manual (2024) p. 260*  
![](2-Mechanics/CLI/bestiary/undead/img/haunting-revenant.webp#right)

Haunting revenants possess ruins and forsaken places connected with their deaths—such as abandoned buildings, wrecked ships, or junk heaps. These revenants lurk in plain sight, waiting for their foes to near, then trap their victims within their massive bodies. Those inside a revenant might be battered by animate furnishings or more unsettling manifestations of the revenant's hatred.

The places haunting revenants lurk swiftly gain infamous reputations.

## Revenants

*Vengeance from beyond the Grave*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** Any  

Wrathful spirits bent on revenge, revenants possess corpses and other materials, using them to seek justice or vent their rage on those who wronged them. Revenants refuse to rest until those they seek to punish are no more. If their bodies are destroyed, revenants claim new forms and continue their ruthless quests.

## Statblock

```ad-statblock
title: Haunting Revenant
![](2-Mechanics/CLI/bestiary/undead/token/haunting-revenant-xmm.webp#token)
*Gargantuan undead, Neutral*

- **Armor Class** 20 
- **Hit Points** 203 (`14d20 + 56`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|18 (+4)|16 (+3)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +8
- **Skills** ⏤
- **Senses** truesight 60 ft., passive Perception 14
- **Damage Resistances** necrotic, psychic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common plus two other languages
- **Challenge** 10

## Traits

***Haunted Zone.*** *Constitution Saving Throw:* DC 17, any creature that casts a spell while inside the revenant's space. *Failure:* The spell fails and is wasted.

***Undead Restoration.*** If the revenant dies, it revives 24 hours later unless [Dispel Evil and Good](2-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md) is cast on its remains. If it revives, it animates another Gargantuan object or structure elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

## Actions

***Multiattack.*** The revenant makes two [Object](2-Mechanics/CLI/rules/variant-rules/object-xphb.md) Slam attacks and uses Invitation.

***Object Slam.*** *Melee or Ranged Attack Roll:* `+9` (with [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) if the target is inside the revenant's space), reach 10 ft. or range 30/90 ft. *Hit:* 27 (`5d8 + 5`) Bludgeoning damage.

***Invitation.*** *Charisma Saving Throw:* DC 17, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target is teleported inside the revenant's space and swallowed. A swallowed creature has [Total Cover](2-Mechanics/CLI/rules/variant-rules/cover-xphb.md) against attacks and other effects outside the revenant.

While the revenant has [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), a swallowed creature can leave the revenant's space only by using magic that enables planar travel, such as the [Plane Shift](2-Mechanics/CLI/spells/plane-shift-xphb.md) spell.
```
^statblock

## Environment

forest, swamp, urban