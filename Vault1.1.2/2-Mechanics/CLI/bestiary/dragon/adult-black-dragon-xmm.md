---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon/chromatic
aliases: ["Adult Black Dragon"]
---
# Adult Black Dragon
*Source: Monster Manual (2024) p. 39*  
![An adult black dragon uses...](2-Mechanics/CLI/bestiary/dragon/img/black-dragon.webp#right "An adult black dragon uses its acid breath to melt the construct defenders of a clockwork fortress")

By the time they're adults, black dragons are among the greatest terrors in the lands they claim. Wretched swamps and monster-haunted ruins grow more dismal and spread under an adult black dragon's influence. Morbid cultists and doomsayers frequently gather in the dragon's service, bringing with them undead terrors that answer to the black dragon and aid it in spreading ruin to nearby bastions of beauty and peace.

## Black Dragons

*Dragons of Decay and Despair*

- **Habitat.** Swamp  
- **Treasure.** Relics  

Black dragons delight in suffering and ruin. While other chromatic dragons scheme for power and wealth, these dragons seek to tear down all they see and rule over what remains.

Black dragons are terrifying creatures with curved horns and withered visages suggestive of fiendish skulls. They typically inhabit stagnant swamps, crumbling ruins, or places of magical or environmental corruption. Their acid breath scars their domains, eroding the features from ancient statues and leaving nature with festering wounds.

Black dragons hoard tarnished symbols of hope and relics of fallen empires. The more sought-after the treasure, the more black dragons prize it—particularly if they were responsible for it being lost.

### Black Dragon Lairs

Black dragons lurk in dismal ruins, polluted bogs, or other sites gripped by decay.

## Statblock

```ad-statblock
title: Adult Black Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/adult-black-dragon-xmm.webp#token)
*Huge dragon (chromatic), Chaotic Evil*

- **Armor Class** 19 
- **Hit Points** 195 (`17d12 + 85`) 
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|14 (+2)|21 (+5)|14 (+2)|13 (+1)|19 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +7, Wisdom +6
- **Skills** Perception +11, Stealth +7
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 21
- **Damage Immunities** acid
- **Languages** Common, Draconic
- **Challenge** 14

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17, `+9` to hit with spell attacks):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Fear](2-Mechanics/CLI/spells/fear-xphb.md), [Melf's Acid Arrow](2-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md) (level 3 version)

**1/day each**: [Speak with Dead](2-Mechanics/CLI/spells/speak-with-dead-xphb.md), [Vitriolic Sphere](2-Mechanics/CLI/spells/vitriolic-sphere-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Melf's Acid Arrow](2-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md) (level 3 version).

***Rend.*** *Melee Attack Roll:* `+11`, reach 10 ft. *Hit:* 13 (`2d6 + 6`) Slashing damage plus 4 (`1d8`) Acid damage.

***Acid Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 18, each creature in a 60-foot-long, 5-foot-wide [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). *Failure:* 54 (`12d8`) Acid damage. *Success:* Half damage.

## Legendary Actions

***Cloud of Insects.*** *Dexterity Saving Throw:* DC 17, one creature the dragon can see within 120 feet. *Failure:* 22 (`4d10`) Poison damage, and the target has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on saving throws to maintain [Concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) until the end of its next turn. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Frightful Presence.*** The dragon uses Spellcasting to cast [Fear](2-Mechanics/CLI/spells/fear-xphb.md). The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon can move up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

## Regional effects

The region containing an adult or ancient black dragon's lair is warped by its presence, creating the following effects:

- **Acrid Haze.** Odorous and stifling fog covers the area within 1 mile of the lair, rendering that area [Lightly Obscured](2-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md). Travel for creatures other than the dragon and its allies takes twice the usual time in that area.  
- **Foul Water.** Water sources within 1 mile of the lair are supernaturally fouled. A creature that drinks such water must succeed on a DC 15 Constitution saving throw or have the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 hour.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

swamp