---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/chromatic
aliases: ["Ancient Black Dragon"]
---
# Ancient Black Dragon
*Source: Monster Manual (2024) p. 40*  
![As terrifying as it is tit...](2-Mechanics/CLI/bestiary/dragon/img/ancient-black-dragon.webp#right "As terrifying as it is titanic, an ancient black dragon eradicates unwanted life in its despoiled territory")

Ancient black dragons plot the ruin of whole realms. They seek magic to corrupt the land, raise undead hordes, bind fiends, and replicate magical disasters. Ancient black dragons strive to create vast, dead domains where they are the greatest things that remain.

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
title: Ancient Black Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/ancient-black-dragon-xmm.webp#token)
*Gargantuan dragon (chromatic), Chaotic Evil*

- **Armor Class** 22 
- **Hit Points** 367 (`21d20 + 147`) 
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|25 (+7)|16 (+3)|15 (+2)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Wisdom +9
- **Skills** Perception +16, Stealth +9
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Immunities** acid
- **Languages** Common, Draconic
- **Challenge** 21

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21, `+13` to hit with spell attacks):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Fear](2-Mechanics/CLI/spells/fear-xphb.md), [Melf's Acid Arrow](2-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md) (level 4 version)

**1/day each**: [Create Undead](2-Mechanics/CLI/spells/create-undead-xphb.md), [Speak with Dead](2-Mechanics/CLI/spells/speak-with-dead-xphb.md), [Vitriolic Sphere](2-Mechanics/CLI/spells/vitriolic-sphere-xphb.md) (level 5 version)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Melf's Acid Arrow](2-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md) (level 4 version).

***Rend.*** *Melee Attack Roll:* `+15`, reach 15 ft. *Hit:* 17 (`2d8 + 8`) Slashing damage plus 9 (`2d8`) Acid damage.

***Acid Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 22, each creature in a 90-foot-long, 10-foot-wide [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). *Failure:* 67 (`15d8`) Acid damage. *Success:* Half damage.

## Legendary Actions

***Cloud of Insects.*** *Dexterity Saving Throw:* DC 21, one creature the dragon can see within 120 feet. *Failure:* 33 (`6d10`) Poison damage, and the target has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on saving throws to maintain [Concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) until the end of its next turn. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Frightful Presence.*** The dragon uses Spellcasting to cast [Fear](2-Mechanics/CLI/spells/fear-xphb.md). The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

## Regional effects

The region containing an adult or ancient black dragon's lair is warped by its presence, creating the following effects:

- **Acrid Haze.** Odorous and stifling fog covers the area within 1 mile of the lair, rendering that area [Lightly Obscured](2-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md). Travel for creatures other than the dragon and its allies takes twice the usual time in that area.  
- **Foul Water.** Water sources within 1 mile of the lair are supernaturally fouled. A creature that drinks such water must succeed on a DC 15 Constitution saving throw or have the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 hour.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

swamp