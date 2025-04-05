---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/shadowfell
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
aliases: ["Shadow Dragon"]
---
# Shadow Dragon
*Source: Monster Manual (2024) p. 275*  
![A shadow dragon lurks amon...](2-Mechanics/CLI/bestiary/dragon/img/shadow-dragons.webp#right "A shadow dragon lurks among haunted ruins, attended by shadows raised by its life-draining breath")

## Shadow Dragons

*Dragon Corrupted by Darkness*

- **Habitat.** Planar (Shadowfell), Underdark  
- **Treasure.** Any  

Shadow dragons haunt forgotten, lightless places. While they might have once been other types of dragons, the influence of planar forces, negative energy, or sinister magic has stripped them of their former color or luster. In place of any former breath weapon, shadow dragons exhale caliginous gouts that saps life from everything it touches. Those slain by a shadow dragon's breath rise as shades obedient to the shadow dragon's will.

Shadow dragons typically dwell in the Underdark, particularly in areas with connections to the Shadowfell or other tenebrous realms. In some cases, they might lurk in dark, corrupted reaches of the regions they preferred before transforming into shadow dragons. Overgrown swamps, sepulchral desert ruins, and ash-choked volcanoes make natural lairs for shadow dragons.

Like many other dragons, shadow dragons collect hoards. Their tastes tend to be morbid—collecting coins from ruined empires and their victims' skulls.

### Shadow Dragon Lairs

Shadow dragons lair in places of darkness and despair, such as accursed ruins, the depths of the Underdark, or the Shadowfell.

> [!quote] A quote from Challenge Tempting Victims to the Lair of the Shadow Dragon Aurgloroasa  
> 
> If ye truly be adventurers of lore, seek the great shadowy wyrm who lairs beneath the Peaks of Thunder and return in triumph bearing aloft her fabled Eye of Shadow.


```ad-statblock
title: Shadow Dragon
![](2-Mechanics/CLI/bestiary/dragon/token/shadow-dragon-xmm.webp#token)
*Huge dragon, Chaotic Evil*

- **Armor Class** 16 
- **Hit Points** 189 (`18d12 + 72`) 
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|19 (+4)|18 (+4)|14 (+2)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Wisdom +6
- **Skills** Perception +11, Stealth +14
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 21
- **Damage Resistances** See Living Shadow
- **Damage Immunities** necrotic
- **Languages** Common, Draconic
- **Challenge** 13

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Living Shadow.*** While in [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) or [Darkness](2-Mechanics/CLI/rules/variant-rules/darkness-xphb.md), the dragon has [Resistance](2-Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to damage that isn't Force, Psychic, or Radiant.

***Sunlight Sensitivity.*** While in sunlight, the dragon has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on ability checks and attack rolls.

## Actions

***Multiattack.*** The dragon makes three Rend attacks.

***Rend.*** *Melee Attack Roll:* `+10`, reach 10 ft. *Hit:* 12 (`2d6 + 5`) Slashing damage plus 3 (`1d6`) Necrotic damage.

***Shadow Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 17, each creature in a 60-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 35 (`10d6`) Necrotic damage. *Success:* Half damage. *Failure or Success:* A Humanoid reduced to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) by this damage dies, and a [Shadow](2-Mechanics/CLI/bestiary/undead/shadow-xmm.md) rises from the corpse. The shadow is under the dragon's control and shares the dragon's [Initiative](2-Mechanics/CLI/rules/variant-rules/initiative-xphb.md) count but acts immediately after the dragon.

## Bonus Actions

***Shadow Stealth.*** While in [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) or [Darkness](2-Mechanics/CLI/rules/variant-rules/darkness-xphb.md), the dragon takes the Hide action.

## Legendary Actions

***Pounce.*** The dragon moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md), and it makes one Rend attack.

***Veil of Shadow.*** The dragon uses Shadow Stealth, and one creature of its choice that it can see within 10 feet of it takes 10 (`3d6`) Necrotic damage. The dragon can't take this action again until the start of its next turn.

## Regional effects

The region around a shadow dragon's lair is twisted by its presence, creating the following effects:

- **Negative Energy Suffusion.** Whenever a creature within 1 mile of the lair regains [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) from a spell, it subtracts `1d10` from the number of [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) regained.  
- **Stifling Shadows.** Within 1 mile of the lair, effects that normally create [Bright Light](2-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md) instead create [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md), and creatures there have [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks.  

If the dragon dies or moves its lair elsewhere, these effects end immediately.
```
^statblock

## Environment

planar, shadowfell, underdark