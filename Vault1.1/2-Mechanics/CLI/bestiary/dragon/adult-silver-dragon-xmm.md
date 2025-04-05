---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon/metallic
aliases: ["Adult Silver Dragon"]
---
# Adult Silver Dragon
*Source: Monster Manual (2024) p. 279*  
![An adult silver dragon rel...](2-Mechanics/CLI/bestiary/dragon/img/silver-dragon.webp#right "An adult silver dragon relaxes in camp alongside its fellow adventurers")

Adult silver dragons love to spend time among various peoples. Rather than manipulating politics directly, they support individuals who have ambitious goals or who popularize the return of great universities, inspiring athletics events or festivals, and other salutary civic institutions of the past. Silver dragons often surround themselves with like-minded allies and are watchful for hidden threats.

## Silver Dragons

*Dragons of Courage and Fairness*

- **Habitat.** Mountain, Urban  
- **Treasure.** Arcana  

Silver dragons work to preserve peace and encourage greatness. They try to live as examples of decency while remaining watchful against evil.

Silver dragons typically dwell amid snow-capped mountains, though aspirations and congeniality drive some to instead live among cosmopolitan societies. Disguised as humanoids, they ally with artists, historians, knights, and humble leaders who learn from the past to create better futures.

Silver dragons take inspiration from legendary heroes and have grand ambitions. Many collect treasures that reflect these interests, such as histories, ancient art, and the gear of famous champions.

### Silver Dragon Lairs

Silver dragons typically lair in picturesque mountain retreats or on sculpted cloud "islands."

## Statblock

```ad-statblock
title: Adult Silver Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/adult-silver-dragon-xmm.webp#token)
*Huge dragon (metallic), Lawful Good*

- **Armor Class** 19 
- **Hit Points** 216 (`16d12 + 112`) 
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|10 (+0)|25 (+7)|16 (+3)|13 (+1)|22 (+6)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +5, Wisdom +6
- **Skills** History +8, Perception +11, Stealth +5
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 21
- **Damage Immunities** cold
- **Languages** Common, Draconic
- **Challenge** 16

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 19, `+11` to hit with spell attacks):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Hold Monster](2-Mechanics/CLI/spells/hold-monster-xphb.md), [Ice Knife](2-Mechanics/CLI/spells/ice-knife-xphb.md), [Shapechange](2-Mechanics/CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only, no [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each**: [Ice Storm](2-Mechanics/CLI/spells/ice-storm-xphb.md) (level 5 version), [Zone of Truth](2-Mechanics/CLI/spells/zone-of-truth-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast [Ice Knife](2-Mechanics/CLI/spells/ice-knife-xphb.md).

***Rend.*** *Melee Attack Roll:* `+13`, reach 10 ft. *Hit:* 17 (`2d8 + 8`) Slashing damage plus 4 (`1d8`) Cold damage.

***Cold Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 20, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 54 (`12d8`) Cold damage. *Success:* Half damage.

***Paralyzing Breath.*** *Constitution Saving Throw:* DC 20, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *1st Failure:* The target has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the end of its next turn, when it repeats the save. *2nd Failure:* The target has the [Paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

## Legendary Actions

***Chill.*** The dragon uses Spellcasting to cast [Hold Monster](2-Mechanics/CLI/spells/hold-monster-xphb.md). The dragon can't take this action again until the start of its next turn.

***Cold Gale.*** *Dexterity Saving Throw:* DC 19, each creature in a 60-foot-long, 10-foot-wide [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). *Failure:* 14 (`4d6`) Cold damage, and the target is pushed up to 30 feet straight away from the dragon. *Success:* Half damage only. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

## Regional effects

The region containing an adult or ancient silver dragon's lair is changed by its magic, creating the following effects:

- **Gentle Gusts.** Winds buoy creatures that fall within 1 mile of the lair. Such creatures descend at a rate of 60 feet per round and take no damage from falling.  
- **Sun and Storms.** While in its lair, the dragon can cast [Control Weather](2-Mechanics/CLI/spells/control-weather-xphb.md), requiring no Material components and using the same spellcasting ability as its Spellcasting action.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

mountain, urban