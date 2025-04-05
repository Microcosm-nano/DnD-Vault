---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
aliases: ["Troll"]
---
# Troll
*Source: Monster Manual (2024) p. 310*  
![](2-Mechanics/CLI/bestiary/giant/img/troll.webp#right)

## Troll

*Loathsome, Regenerating Lurker*

- **Habitat.** Arctic, Forest, Hill, Mountain, Swamp, Underdark  
- **Treasure.** None  

Trolls creep forth to prey on smaller creatures and drag captives back to festering lairs. These misshapen brutes can regenerate from wounds and regrow severed body parts—including their heads. A troll's severed limbs continue to move and attack. Unless they're burned by flames or acid, trolls can recover from egregious wounds and seek revenge on those who felled them.

Trolls typically hunt alone, but small groups occasionally cooperate to ambush prey or raid villages. Creatures such as hags and hill giants might convince trolls to work for them in exchange for disgusting meals.

```ad-statblock
title: Troll
![](2-Mechanics/CLI/bestiary/giant/token/troll-xmm.webp#token)
*Large giant, Chaotic Evil*

- **Armor Class** 15 
- **Hit Points** 94 (`9d10 + 45`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|13 (+1)|20 (+5)| 7 (-2)| 9 (-1)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Languages** Giant
- **Challenge** 5

## Traits

***Loathsome Limbs (4/Day).*** If the troll ends any turn [Bloodied](2-Mechanics/CLI/rules/variant-rules/bloodied-xphb.md) and took 15+ Slashing damage during that turn, one of the troll's limbs is severed, falls into the troll's space, and becomes a [Troll Limb](2-Mechanics/CLI/bestiary/giant/troll-limb-xmm.md). The limb acts immediately after the troll's turn. The troll has 1 [Exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) level for each missing limb, and it grows replacement limbs the next time it regains [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

***Regeneration.*** The troll regains 15 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) at the start of each of its turns. If the troll takes Acid or Fire damage, this trait doesn't function on the troll's next turn. The troll dies only if it starts its turn with 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) and doesn't regenerate.

## Actions

***Multiattack.*** The troll makes three Rend attacks.

***Rend.*** *Melee Attack Roll:* `+7`, reach 10 ft. *Hit:* 11 (`2d6 + 4`) Slashing damage.

## Bonus Actions

***Charge.*** The troll moves up to half its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) straight toward an enemy it can see.
```
^statblock

## Environment

arctic, forest, hill, mountain, swamp, underdark