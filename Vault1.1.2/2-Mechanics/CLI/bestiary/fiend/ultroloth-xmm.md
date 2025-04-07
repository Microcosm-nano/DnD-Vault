---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
aliases: ["Ultroloth"]
---
# Ultroloth
*Source: Monster Manual (2024) p. 311*  
![](2-Mechanics/CLI/bestiary/fiend/img/ultroloth.webp#right)

## Ultroloth

*Yugoloth of Conspiracy and Control*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Armaments  

With uncanny patience and fiendish cunning, ultroloths manipulate mortals and their fellow yugoloths alike, seeking to hoard power and spread suffering. These sinister masterminds often work with other yugoloths, but they might compel nearly any creature into their service. If coercion doesn't work, ultroloths use their eerie eyes and innate magic to hypnotize or charm targets.

Ultroloths strive to achieve planes-spanning plots. Roll on or choose a result from the Ultroloth Conspiracies table to inspire such villainy.

**Ultroloth Conspiracies**

`dice: [](ultroloth-xmm.md#^ultroloth-conspiracies)`

| dice: 1d6 | The Ultroloth Schemes To... |
|-----------|-----------------------------|
| 1 | Convince cultists their god has forsaken them. |
| 2 | Destabilize a nation and rule the chaos. |
| 3 | Incite a calamity and hold a world hostage. |
| 4 | Provoke hostilities between immortal armies and sell magic weapons to both sides. |
| 5 | Steal an invention and slay all who know of it. |
| 6 | Unleash fiendish hordes on a foe's homeland. |
^ultroloth-conspiracies

```ad-statblock
title: Ultroloth
![](2-Mechanics/CLI/bestiary/fiend/token/ultroloth-xmm.webp#token)
*Medium fiend (yugoloth), Neutral Evil*

- **Armor Class** 19 
- **Hit Points** 221 (`26d8 + 104`) 
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|16 (+3)|18 (+4)|19 (+4)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** Deception +9, Perception +7, Stealth +8
- **Senses** truesight 120 ft., passive Perception 17
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal; telepathy 120 ft.
- **Challenge** 13

## Traits

***Fiendish Restoration.*** If the ultroloth dies outside Gehenna, its body dissolves into ichor, and it gains a new body instantly, reviving with all its [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere in Gehenna.

***Magic Resistance.*** The ultroloth has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting.*** The ultroloth casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [Alter Self](2-Mechanics/CLI/spells/alter-self-xphb.md), [Clairvoyance](2-Mechanics/CLI/spells/clairvoyance-xphb.md), [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md)

**1/day each**: [Dimension Door](2-Mechanics/CLI/spells/dimension-door-xphb.md), [Fireball](2-Mechanics/CLI/spells/fireball-xphb.md) (level 5 version), [Wall of Fire](2-Mechanics/CLI/spells/wall-of-fire-xphb.md)

***Fiendish Guile (Recharge 4-6).*** The ultroloth casts [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic-xphb.md), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md) (self only), [Misty Step](2-Mechanics/CLI/spells/misty-step-xphb.md), or [Suggestion](2-Mechanics/CLI/spells/suggestion-xphb.md), requiring no Material components and using the same spellcasting ability as Spellcasting.


## Actions

***Multiattack.*** The ultroloth uses Hypnotic Gaze and makes two Mercurial Whip attacks.

***Mercurial Whip.*** *Melee Attack Roll:* `+9`, reach 15 ft. *Hit:* 25 (`6d6 + 4`) Force damage, and the ultroloth can teleport the target up to 10 feet to an unoccupied space the ultroloth can see that isn't in the air.

***Hypnotic Gaze.*** *Wisdom Saving Throw:* DC 17, each creature in a 30-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 10 (`3d6`) Psychic damage, and the target has the [Stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of the ultroloth's next turn. *Success:* The target is immune to this ultroloth's Hypnotic Gaze for 24 hours.
```
^statblock

## Environment

planar, lower