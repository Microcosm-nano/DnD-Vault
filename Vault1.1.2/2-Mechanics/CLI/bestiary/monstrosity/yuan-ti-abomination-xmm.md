---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
aliases: ["Yuan-ti Abomination"]
---
# Yuan-ti Abomination
*Source: Monster Manual (2024) p. 345*  
![](2-Mechanics/CLI/bestiary/monstrosity/img/yuan-ti-abomination.webp#right)

Yuan-ti abominations have traded away nearly all evidence of their humanity, coming to resemble giant, upright serpents with scaly arms and hands. In battle, they relish opportunities to crush foes in their powerful coils or strike with their venomous fangs. These abominations can also shape-shift into snakes. In these forms, abominations are indistinguishable from normal serpents.

The true threat of yuan-ti abominations stems not from their physical might but from their cunning. These masterminds often lead cultlike cells of other yuan-ti and direct them in enacting elaborate conspiracies. Abominations avoid jeopardizing themselves, typically scheming from hidden bastions where they're protected by yuan-ti and serpent guardians. These coldhearted leaders have a unique understanding of the supernatural forces that grant yuan-ti their powers, and they usually have insidious magical traps and contingencies at their disposal.

## Yuan-ti

*Power-Hungry Serpentine Conspirators*

- **Habitat.** Desert, Forest, Swamp, Urban  
- **Treasure.** Relics  

Exploiting pacts with sinister supernatural forces, yuan-ti bargain away their humanity for the lethality and predatory deviousness of serpents. From hidden bastions, they manipulate rulers and the wealthy, seeking to control the world. Many yuan-ti possess venomous magic, which often manifests as fangs or striking serpents.

Yuan-ti have humanlike forms with a variety of horrifying serpentine transformations. Some have a scattering of reptilian scales, while others are giants that are more snake than human. Typically, the more snakelike yuan-ti are, the greater esteem they hold among their kind.

Yuan-ti might gain their reptilian features through dangerous supernatural rites. Roll on or choose a result from the Yuan-ti Transformations table to inspire how yuan-ti obtain their serpentine aspects.

**Yuan-ti Transformations**

`dice: [](yuan-ti-abomination-xmm.md#^yuan-ti-transformations)`

| dice: 1d6 | A Yuan-ti Gained Its Snake Features From... |
|-----------|---------------------------------------------|
| 1 | Bargaining parts of its soul to a pantheon of serpentine demigods. |
| 2 | A curse laid on its people in the distant past. |
| 3 | The dream-venom of Merrshaulk, a slumbering snake god. |
| 4 | Experiments by spirit nagas or other yuan-ti. |
| 5 | A ritual involving the skin of a fiendish snake. |
| 6 | Trials to excise its "weak" human parts. |
^yuan-ti-transformations

> [!quote] A quote from Last Message of Sorril Venil, Explorer of the Labyrinth of Madness  
> 
> Great magic, twisted and corrupted... Malice beyond reckoning... Flesh reshaped, becoming serpentine horrors...


![](2-Mechanics/CLI/bestiary/monstrosity/img/yuan-ti.webp#center)

## Statblock

```ad-statblock
title: Yuan-ti Abomination
![](2-Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-abomination-xmm.webp#token)
*Large monstrosity, Neutral Evil*

- **Armor Class** 15 
- **Hit Points** 127 (`15d10 + 45`) 
- **Speed** 40 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|16 (+3)|17 (+3)|17 (+3)|18 (+4)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +7, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 17
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 7

## Traits

***Magic Resistance.*** The yuan-ti has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting (Yuan-ti Form Only).*** The yuan-ti casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 15):

**At will**: [Animal Friendship](2-Mechanics/CLI/spells/animal-friendship-xphb.md) (snakes only)

**3/day**: [Suggestion](2-Mechanics/CLI/spells/suggestion-xphb.md)

## Actions

***Multiattack.*** The yuan-ti makes two Bite attacks, and it can use Spellcasting to cast [Suggestion](2-Mechanics/CLI/spells/suggestion-xphb.md) if available.

***Bite.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 11 (`2d6 + 4`) Piercing damage plus 10 (`3d6`) Poison damage.

***Constrict.*** *Strength Saving Throw:* DC 15, one Large or smaller creature within 5 feet. *Failure:* 28 (`7d6 + 4`) Bludgeoning damage. The target has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14), and it has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the grapple ends. *Success:* Half damage only.

***Poison Spray (Recharge 5-6).*** *Constitution Saving Throw:* DC 14, each creature in a 30-foot [Cone](2-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 21 (`6d6`) Poison damage, and the target has the [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of the yuan-ti's next turn. While [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the target has the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition. *Success:* Half damage only.

## Bonus Actions

***Shape-Shift.*** The yuan-ti shape-shifts into a Large snake or returns to its true form. If it dies, it stays in its current form. The yuan-ti's game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.
```
^statblock

## Environment

desert, forest, swamp, urban