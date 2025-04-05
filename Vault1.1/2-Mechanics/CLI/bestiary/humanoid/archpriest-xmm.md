---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
aliases: ["Archpriest"]
---
# Archpriest
*Source: Monster Manual (2024) p. 248*  
![](2-Mechanics/CLI/bestiary/humanoid/img/priests.webp#right)

By forging connections with divine beings and mastering mystical truths, archpriests become conduits for godly intentions and other supernatural forces. Their magic allows them to work wonders, whether to share the benevolence of their faiths or to vent divine wrath. Some archpriests attract vast followings as they claim to speak for divine forces, while others undertake personal spiritual journeys and seek to transcend mortal concerns.

## Priests

*Arbiters of the Mortal and the Divine*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Priests harness the power of faith to work miracles. These religious adherents are as diverse as the faiths they follow. Some obey gods and their servants, while others live by age-old creeds. Belief guides priests' actions and their magic, which they use to shape the world in line with their ideologies.

Roll on or choose a result from the Priest Roles table to inspire different sorts of priests.

**Priest Roles**

`dice: [](archpriest-xmm.md#^priest-roles)`

| dice: 1d10 | The Priest Is... |
|------------|------------------|
| 1 | An ascetic who keeps wicked spirits at bay. |
| 2 | An elder who speaks for the dead. |
| 3 | An exorcist who hunts wicked spirits. |
| 4 | A follower of a god no one has heard of. |
| 5 | A mediator and teacher of traditional ways. |
| 6 | A philosopher devoted to a concept, multiversal view, or plane of existence. |
| 7 | The reincarnation of an ancient faith leader. |
| 8 | A ritualist who uses tinctures and performances to access the divine. |
| 9 | A shaman whose medicines ease many ills. |
| 10 | A zealot who wages war for a divine cause. |
^priest-roles

> [!quote]  
> 
> Shining One, light my hours. Enkindle my soul, and inspire my deeds. Chase the shadows from my path, and let me walk in your brilliance.


## Statblock

```ad-statblock
title: Archpriest
![](2-Mechanics/CLI/bestiary/humanoid/token/archpriest-xmm.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 16 
- **Hit Points** 240 (`32d8 + 96`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|17 (+3)|14 (+2)|21 (+5)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +7, Constitution +7, Intelligence +6, Wisdom +9
- **Skills** Insight +9, Medicine +9, Perception +9, Religion +10
- **Senses** passive Perception 19
- **Languages** Common plus two other languages
- **Challenge** 12

***Spellcasting.*** The archpriest casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 17):

**At will**: [Light](2-Mechanics/CLI/spells/light-xphb.md), [Thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy-xphb.md)

**1/day each**: [Flame Strike](2-Mechanics/CLI/spells/flame-strike-xphb.md) (level 6 version), [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration-xphb.md), [Raise Dead](2-Mechanics/CLI/spells/raise-dead-xphb.md), [Zone of Truth](2-Mechanics/CLI/spells/zone-of-truth-xphb.md)

***Divine Aid (3/Day).*** The priest casts [Bless](2-Mechanics/CLI/spells/bless-xphb.md), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic-xphb.md), [Healing Word](2-Mechanics/CLI/spells/healing-word-xphb.md), or [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration-xphb.md), using the same spellcasting ability as Spellcasting.

**3/day**: [Bless](2-Mechanics/CLI/spells/bless-xphb.md), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic-xphb.md), [Healing Word](2-Mechanics/CLI/spells/healing-word-xphb.md), [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration-xphb.md)

## Actions

***Multiattack.*** The archpriest makes three Radiant Burst attacks.

***Radiant Burst.*** *Melee or Ranged Attack Roll:* `+9`, reach 5 ft. or range 60 ft. *Hit:* 27 (`4d10 + 5`) Radiant damage.

***Holy Word (Recharge 4-6).*** *Wisdom Saving Throw:* DC 17, each enemy in a 20-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the archpriest. *Failure:* 21 (`6d6`) Radiant damage, and the target has the [Stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the end of the archpriest's next turn. *Success:* Half damage only.
```
^statblock

## Environment

any