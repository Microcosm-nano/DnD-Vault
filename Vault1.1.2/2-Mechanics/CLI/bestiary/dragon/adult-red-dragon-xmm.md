---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon/chromatic
aliases: ["Adult Red Dragon"]
---
# Adult Red Dragon
*Source: Monster Manual (2024) p. 255*  
![An adult red dragon unleas...](2-Mechanics/CLI/bestiary/dragon/img/red-dragon.webp#right "An adult red dragon unleashes its fury, reducing a city to ruin")

Adult red dragons are tyrants that claim vast domains and might command armies of followers or significant magical resources. Red dragons rarely pay attention to the nations and claims of smaller creatures, and they might consider entire cities part of their realm. Most red dragons are inattentive rulers, though, spending decades focused on their own comforts, hoards, or magical concerns within their lairs. But when their attention returns to their territories, if they find matters not to their liking, whole lands might burn.

## Red Dragons

*Dragons of Greed and Devastation*

- **Habitat.** Hill, Mountain  
- **Treasure.** Any  

Red dragons take whatever they desire and burn to ash anything that stands in their way. These chromatic dragons endlessly desire more—more magic, territory, treasure, or whatever else inflames their cruel ambitions.

Red dragons make their lairs amid perilous cliffs and volcanoes. Within, they amass and fiercely protect hoards of treasure, and many have perfect recall of the hoards' contents and the locations of all they've collected. Should anything go missing, red dragons fly into rages. They don't rest until their treasures are returned and the thieves have burned.

Red dragons believe themselves to be the greatest of all dragons and, by extension, the greatest of all creatures. To them, pillaging and conquering are their right—treasures can find no more honored place than in their hoards, and other creatures are privileged to serve them.

### Red Dragon Lairs

Red dragons make their lairs in smoldering, unapproachable places such as volcanic mountains, burning wastelands, and ruins they've stolen from other creatures.

## Statblock

```ad-statblock
title: Adult Red Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/adult-red-dragon-xmm.webp#token)
*Huge dragon (chromatic), Chaotic Evil*

- **Armor Class** 19 
- **Hit Points** 256 (`19d12 + 133`) 
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|10 (+0)|25 (+7)|16 (+3)|13 (+1)|23 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Wisdom +7
- **Skills** Perception +13, Stealth +6
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 23
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 17

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 20, `+12` to hit with spell attacks):

**At will**: [Command](2-Mechanics/CLI/spells/command-xphb.md) (level 2 version), [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Scorching Ray](2-Mechanics/CLI/spells/scorching-ray-xphb.md)

**1/day**: [Fireball](2-Mechanics/CLI/spells/fireball-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Scorching Ray](2-Mechanics/CLI/spells/scorching-ray-xphb.md).

***Rend.*** *Melee Attack Roll:* `+14`, reach 10 ft. *Hit:* 13 (`1d10 + 8`) Slashing damage plus 5 (`2d4`) Fire damage.

***Fire Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 21, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 59 (`17d6`) Fire damage. *Success:* Half damage.

## Legendary Actions

***Commanding Presence.*** The dragon uses Spellcasting to cast [Command](2-Mechanics/CLI/spells/command-xphb.md) (level 2 version). The dragon can't take this action again until the start of its next turn.

***Fiery Rays.*** The dragon uses Spellcasting to cast [Scorching Ray](2-Mechanics/CLI/spells/scorching-ray-xphb.md). The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

## Regional effects

The region containing an adult or ancient red dragon's lair is warped by its presence, creating the following effects:

- **Burning Heat.** The area within 1 mile of the lair is an area of extreme heat. A burning creature or object takes an additional `1d4` Fire damage at the start of each of its turns.  
- **Smoldering Haze.** The area within 1 mile of the lair is [Lightly Obscured](2-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md) with clouds of ash. Whenever a creature other than the dragon or one of its allies finishes a [Long Rest](2-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md) in that area, that creature must succeed on a DC 15 Constitution saving throw or have the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 hour.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

hill, mountain