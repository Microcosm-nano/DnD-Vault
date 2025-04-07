---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/chromatic
aliases: ["Ancient Red Dragon"]
---
# Ancient Red Dragon
*Source: Monster Manual (2024) p. 256*  
![Even the bravest souls fle...](2-Mechanics/CLI/bestiary/dragon/img/ancient-red-dragon.webp#right "Even the bravest souls flee the onslaught of an ancient red dragon")

Ancient red dragons number among the most feared and destructive beings in the multiverse. Few can withstand the wrath of an ancient red dragon that turns its mind toward devastation. These dragons' greed matches their ruinous potential, and they collect vast hoards studded with storied treasures and magic items. Their lairs frequently tap into volcanic depths and might pierce other planes of existence, bringing servants from the Elemental Plane of Fire or the Lower Planes into their service.

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
title: Ancient Red Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/ancient-red-dragon-xmm.webp#token)
*Gargantuan dragon (chromatic), Chaotic Evil*

- **Armor Class** 22 
- **Hit Points** 507 (`26d20 + 234`) 
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|10 (+0)|29 (+9)|18 (+4)|15 (+2)|27 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Wisdom +9
- **Skills** Perception +16, Stealth +7
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 24

## Traits

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 23, `+15` to hit with spell attacks):

**At will**: [Command](2-Mechanics/CLI/spells/command-xphb.md) (level 2 version), [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Scorching Ray](2-Mechanics/CLI/spells/scorching-ray-xphb.md) (level 3 version)

**1/day each**: [Fireball](2-Mechanics/CLI/spells/fireball-xphb.md) (level 6 version), [Scrying](2-Mechanics/CLI/spells/scrying-xphb.md)

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Scorching Ray](2-Mechanics/CLI/spells/scorching-ray-xphb.md) (level 3 version).

***Rend.*** *Melee Attack Roll:* `+17`, reach 15 ft. *Hit:* 19 (`2d8 + 10`) Slashing damage plus 10 (`3d6`) Fire damage.

***Fire Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 24, each creature in a 90-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 91 (`26d6`) Fire damage. *Success:* Half damage.

## Legendary Actions

***Commanding Presence.*** The dragon uses Spellcasting to cast [Command](2-Mechanics/CLI/spells/command-xphb.md) (level 2 version). The dragon can't take this action again until the start of its next turn.

***Fiery Rays.*** The dragon uses Spellcasting to cast [Scorching Ray](2-Mechanics/CLI/spells/scorching-ray-xphb.md) (level 3 version). The dragon can't take this action again until the start of its next turn.

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