---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/metallic
aliases: ["Ancient Gold Dragon"]
---
# Ancient Gold Dragon
*Source: Monster Manual (2024) p. 146*  
![The pure of heart have not...](2-Mechanics/CLI/bestiary/dragon/img/ancient-gold-dragon.webp#right "The pure of heart have nothing to fear in the presence of an ancient gold dragon")

Ancient gold dragons are wise and mysterious. Many aid virtuous groups, guiding them in secret or patronizing them from afar. Only when stakes are at their highest do ancient gold dragons reveal themselves in all their majesty.

## Gold Dragons

*Dragons of Hope and Majesty*

- **Habitat.** Forest, Grassland  
- **Treasure.** Arcana  

Gold dragons work to make the world a better place. The most powerful of the metallic dragons, these awe-inspiring dragons strive to protect that which is good and bend fate toward a brighter future. Their kind dispositions don't prevent gold dragons from engaging in combat when necessary, though, and they exhale brilliant flames and weakening magic to rout their foes.

Gold dragons favor grasslands and pristine forests, frequently dwelling near awe-inspiring natural wonders or guarding monuments from ancient civilizations. In their lairs, gold dragons hoard coins and gems, but they frequently put their treasure to use in pursuit of greater goals. They often use their riches to buy rare lore books, pay informants, or patronize idealistic adventurers.

### Gold Dragon Lairs

Gold dragons make their homes in places of natural and magical wonder.

## Statblock

```ad-statblock
title: Ancient Gold Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/ancient-gold-dragon-xmm.webp#token)
*Gargantuan dragon (metallic), Lawful Good*

- **Armor Class** 22 
- **Hit Points** 546 (`28d20 + 252`) 
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|14 (+2)|29 (+9)|18 (+4)|17 (+3)|28 (+9)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Wisdom +10
- **Skills** Insight +10, Perception +17, Persuasion +16, Stealth +9
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 27
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 24

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 24, `+16` to hit with spell attacks):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Guiding Bolt](2-Mechanics/CLI/spells/guiding-bolt-xphb.md) (level 4 version), [Shapechange](2-Mechanics/CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only, no [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each**: [Flame Strike](2-Mechanics/CLI/spells/flame-strike-xphb.md) (level 6 version), [Word of Recall](2-Mechanics/CLI/spells/word-of-recall-xphb.md), [Zone of Truth](2-Mechanics/CLI/spells/zone-of-truth-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast [Guiding Bolt](2-Mechanics/CLI/spells/guiding-bolt-xphb.md) (level 4 version) or (B) Weakening Breath.

***Rend.*** *Melee Attack Roll:* `+17` to hit, reach 15 ft. *Hit:* 19 (`2d8 + 10`) Slashing damage plus 9 (`2d8`) Fire damage.

***Fire Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 24, each creature in a 90-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 71 (`13d10`) Fire damage. *Success:* Half damage.

***Weakening Breath.*** *Strength Saving Throw:* DC 24, each creature that isn't currently affected by this breath in a 90-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on Strength-based [D20 Tests](2-Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) and subtracts 5 (`1d10`) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

## Legendary Actions

***Banish.*** *Charisma Saving Throw:* DC 24, one creature the dragon can see within 120 feet. *Failure:* 24 (`7d6`) Force damage, and the target has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Guiding Light.*** The dragon uses Spellcasting to cast [Guiding Bolt](2-Mechanics/CLI/spells/guiding-bolt-xphb.md) (level 4 version).

***Pounce.*** The dragon moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

## Regional effects

The region containing an adult or ancient gold dragon's lair is altered by its presence, creating the following effects:

- **Dream Messenger.** While in its lair, the dragon can cast [Dream](2-Mechanics/CLI/spells/dream-xphb.md), requiring no Material components and using Charisma as the spellcasting ability. When casting the spell this way, the dragon can target any creature within 6 miles.  
- **Foretelling Fog.** The area within 1 mile of the lair is [Lightly Obscured](2-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md) by opalescent fog. While in that area, creatures can't be [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised), as the fog swirls into shapes that warn of danger.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

forest, grassland