---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Bandit Deceiver"]
---
# Bandit Deceiver
*Source: Monster Manual (2024) p. 28*  
![](2-Mechanics/CLI/bestiary/humanoid/img/bandits.webp#right)

Bandit deceivers use magic to disguise their activities or create flashy distractions.

## Bandits

*Criminals and Scoundrels*

- **Habitat.** Any  
- **Treasure.** Any  

Bandits use the threat of violence to take what they want. Such criminals include gang members, desperadoes, and lawless mercenaries. Yet not all bandits are motivated by greed. Some are driven to lives of crime by unjust laws, desperation, or the threats of merciless leaders.

Roll on or choose a result from the Bandit Motivations table to determine the circumstances behind a bandit's crimes.

> [!quote] A quote from Jarlaxle  
> 
> I am he who rules the world, don't you know? One little piece at a time.

**Bandit Motivations**

`dice: [](bandit-deceiver-xmm.md#^bandit-motivations)`

| dice: 1d6 | The Bandit... |
|-----------|---------------|
| 1 | Fights only oppressors. |
| 2 | Is an ex-soldier who was discarded by their nation and now takes what they were promised. |
| 3 | Is in a gang that views nonmembers as foes. |
| 4 | Hesitantly serves a villainous leader. |
| 5 | Secretly works for a government or a regional ruler to sow chaos. |
| 6 | Takes what they need to survive. |
^bandit-motivations

## Statblock

```ad-statblock
title: Bandit Deceiver
![](2-Mechanics/CLI/bestiary/humanoid/token/bandit-deceiver-xmm.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 16 
- **Hit Points** 130 (`20d8 + 40`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|16 (+3)|14 (+2)|17 (+3)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Intelligence +6
- **Skills** Acrobatics +6, Perception +4, Stealth +9
- **Senses** passive Perception 14
- **Languages** Common, Thieves' cant
- **Challenge** 7

***Spellcasting.*** The bandit casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [Disguise Self](2-Mechanics/CLI/spells/disguise-self-xphb.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion-xphb.md)

**1/day each**: [Hold Person](2-Mechanics/CLI/spells/hold-person-xphb.md) (level 4 version), [Mage Armor](2-Mechanics/CLI/spells/mage-armor-xphb.md) (included in AC), [Major Image](2-Mechanics/CLI/spells/major-image-xphb.md)

## Actions

***Multiattack.*** The bandit makes three Dagger attacks.

***Dagger.*** *Melee or Ranged Attack Roll:* `+6`, reach 5 ft. or range 20/60 ft. *Hit:* 8 (`2d4 + 3`) Piercing damage plus 10 (`3d6`) Poison damage.

***Blinding Flash (Recharge 4-6).*** *Constitution Saving Throw:* DC 14, each creature in a 10-foot-radius [Sphere](2-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the bandit can see within 120 feet. *Failure:* 13 (`3d6 + 3`) Radiant damage, and the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition until the start of the bandit's next turn. *Success:* Half damage only.
```
^statblock

## Environment

any