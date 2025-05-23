---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/fire
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
aliases: ["Fire Elemental"]
---
# Fire Elemental
*Source: Monster Manual (2024) p. 118*  
![](2-Mechanics/CLI/bestiary/elemental/img/fire-elemental.webp#right)

## Fire Elemental

*Primal Spirit of Heat and Flame*

- **Habitat.** Desert, Planar (Elemental Plane of Fire)  
- **Treasure.** None  

Fire elementals arise when spirits of the Elemental Plane of Fire inhabit flames, burning cinders, and heated smoke. These beings are tangible despite largely being made of flames and particles, and they can uses their vague limbs to ignite foes and flammable materials. Fire elementals typically burn in shades of orange and red, but other colors are possible. Most on the Material Plane are summoned by magical means, or they might appear near rifts amid desert depths, volcanoes, wildfires, or magma flows that connect to their home plane.

Fire elementals might burn in distinctive ways. Roll on or choose a result from the Fire Elemental Compositions table to inspire a fire elemental's features.

**Fire Elemental Compositions**

`dice: [](fire-elemental-xmm.md#^fire-elemental-compositions)`

| dice: 1d8 | The Fire Elemental's Body Features... |
|-----------|---------------------------------------|
| 1 | Colorful, superheated gases. |
| 2 | A column of diabolical or divine flame. |
| 3 | Crackling shapes that look like animals, fiends, skeletons, sprites, or other beings. |
| 4 | Flames that are predominantly white, blue, or a more unusual color. |
| 5 | The form of a calm or tormented humanoid. |
| 6 | Smoke that forms eerie shapes or symbols. |
| 7 | Soot that smells like cedar, cloves, incense, or burning meat. |
| 8 | Swirls of cinders and burning debris. |
^fire-elemental-compositions

> [!quote] A quote from Marrake the Incandescent, Ruler of Efreet  
> 
> All the elements bow to fire. The strongest earth melts. Water boils. Even air ignites. We are all souls of flame, and we know what it is to burn.


```ad-statblock
title: Fire Elemental
![](2-Mechanics/CLI/bestiary/elemental/token/fire-elemental-xmm.webp#token)
*Large elemental, Neutral*

- **Armor Class** 13 
- **Hit Points** 93 (`11d10 + 33`) 
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|17 (+3)|16 (+3)| 6 (-2)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Primordial (Ignan)
- **Challenge** 5

## Traits

***Fire Aura.*** At the end of each of the elemental's turns, each creature in a 10-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the elemental takes 5 (`1d10`) Fire damage. Creatures and flammable objects in the [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) start [burning](2-Mechanics/CLI/traps-hazards/burning-xphb.md).

***Fire Form.*** The elemental can move through a space as narrow as 1 inch without expending extra movement to do so, and it can enter a creature's space and stop there. The first time it enters a creature's space on a turn, that creature takes 5 (`1d10`) Fire damage.

***Illumination.*** The elemental sheds [Bright Light](2-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md) in a 30-foot radius and [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) for an additional 30 feet.

***Water Susceptibility.*** The elemental takes 3 (`1d6`) Cold damage for every 5 feet the elemental moves in water or for every gallon of water splashed on it.

## Actions

***Multiattack.*** The elemental makes two Burn attacks.

***Burn.*** *Melee Attack Roll:* `+6`, reach 5 ft. *Hit:* 10 (`2d6 + 3`) Fire damage. If the target is a creature or a flammable object, it starts burning.
```
^statblock

## Environment

desert, planar, fire