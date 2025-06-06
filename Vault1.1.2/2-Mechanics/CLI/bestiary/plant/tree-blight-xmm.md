---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant
aliases: ["Tree Blight"]
---
# Tree Blight
*Source: Monster Manual (2024) p. 44*  
![](2-Mechanics/CLI/bestiary/plant/img/vine-needle-and-tree-blights.webp#right)

Tree blights look like ancient, dead trees with gnarled limbs and splintered hollows. Imbued with bloodlust, these blights feed on the living. Evidence of their past meals is often tangled amid their branches and roots. Tree blights cooperate with other blights, but they attack other tree-shaped beings they encounter, such as awakened trees and treants.

## Blights

*Plants Sprouted from Evil*

- **Habitat.** Forest  
- **Treasure.** None  

Blights are malicious plants that sprout from deep-rooted evil. Their gnarled forms twist with fearsome features suggestive of human limbs and vicious maws. Blights lurk in ambush amid mundane vegetation and lash out at non-Plant creatures. While blights can act independently, they're usually motivated by whatever sinister forces spawned them or by wicked creatures with control over nature. The magic that creates blights often affects other vegetation as well, causing brambles, vines, and gnarled trees to overwhelm roads and fields, choke wells and streams, and force animals from their natural habitat. This might make blights the first sign of an oncoming wave of corruption.

> [!quote] A quote from Belak the Outcast, Druid of the Twilight Grove  
> 
> It lives, though it looks dead. In an age long past, someone staked a vampire to the earth on this very spot. The wooden stake was yet green and took root. And so grew the Gulthias Tree, reverberating with primal power.


## Statblock

```ad-statblock
title: Tree Blight
![](2-Mechanics/CLI/bestiary/plant/token/tree-blight-xmm.webp#token)
*Huge plant, Neutral Evil*

- **Armor Class** 15 
- **Hit Points** 115 (`10d12 + 50`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|20 (+5)| 6 (-2)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft., passive Perception 10
- **Condition Immunities** [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened)
- **Languages** understands Common and Druidic but can't speak
- **Challenge** 7

## Actions

***Multiattack.*** The blight makes two Branch attacks and uses Grasping Root.

***Branch.*** *Melee Attack Roll:* `+9`, reach 15 ft. *Hit:* 16 (`3d6 + 6`) Bludgeoning damage.

***Grasping Root.*** *Strength Saving Throw:* DC 17, one Large or smaller creature the blight can see within 15 feet. *Failure:* The target is pulled up to 10 feet straight toward the blight and has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16) from one of six roots. Until the grapple ends, the target takes 13 (`2d6 + 6`) Bludgeoning damage at the start of each of its turns.

## Bonus Actions

***Gnash.*** *Dexterity Saving Throw:* DC 17, one creature [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the blight. *Failure:* 19 (`3d8 + 6`) Piercing damage. *Success:* Half damage.
```
^statblock

## Environment

forest