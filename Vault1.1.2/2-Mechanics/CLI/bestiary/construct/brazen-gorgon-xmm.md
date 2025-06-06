---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
aliases: ["Brazen Gorgon"]
---
# Brazen Gorgon
*Source: Monster Manual (2024) p. 149*  
![](2-Mechanics/CLI/bestiary/construct/img/brazen-gorgon.webp#right)

Followers of the exiled archdevil Moloch altered the process of creating gorgons to craft their own diabolical guardians called brazen gorgons. These gorgons are hollow, bull-like automatons whose metal bodies glow with intense heat. When they charge their foes, the ribs of their frames open like cages to ensnare enemies and roast them within. Brazen gorgons are often found in blasphemous sites dedicated to Moloch, other archdevils, or bloodthirsty gods.

## Gorgons

*Bull-like Guardians with Petrifying Breath*

- **Habitat.** Forest, Grassland, Hill  
- **Treasure.** Any  

Resembling mighty bulls armored in iron plates, gorgons are lifelike automatons that seek to destroy all who enter their territories. In addition to goring foes with their deadly horns and trampling them under their iron hooves, gorgons exhale gouts of noxious gas.

Gorgons are created by magic-users to serve as guardians. The process for creating a gorgon is labor intensive and dangerous, with one method requiring the skeleton of a bull, the blood of a medusa, and the brain of a basilisk fused into a frame of ensorcelled iron. If the process fails, petrifying gas emerges from the materials, creating a magical threat that can fill a structure and linger for years.

When magic-users create gorgons, they often enchant them to ignore those who confront the creature with a specific command key, usually a password or a specific signal. Once a gorgon is set to guard an area, it attacks any who enter until they flee or are destroyed. Should someone provide the command key, the monster ignores that intruder so long as the intruder remains in its sight. But if the intruder ventures out of sight and then returns without again presenting the command key, the gorgon attacks. Those in a gorgon's territory must remain vigilant and aware of the monster's exact position, or they risk being attacked by a gorgon they thought was no longer a threat.

Those who create gorgons strive to give them purposefully obscure command keys. Hints at command keys might be found among the records of a gorgon's creator or in the area the gorgon protects—perhaps scrawled as a [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) trespasser's final act. Roll on or choose a result from the Gorgon Command Keys table to inspire the word or signal that temporarily neutralizes a gorgon.

**Gorgon Command Keys**

`dice: [](brazen-gorgon-xmm.md#^gorgon-command-keys)`

| dice: 1d6 | Gorgon Won't Attack Those That... |
|-----------|-----------------------------------|
| 1 | Cast a particular spell in the gorgon's presence. |
| 2 | Keep their back to the gorgon or otherwise act like they don't see the monster. |
| 3 | Offer it a drink of blood, water, or wine. |
| 4 | Recite a specific rhyme or sing a certain song. |
| 5 | Say its creator's name backward. |
| 6 | Wear a mask, perhaps in the shape of a bull or an animal meaningful to the gorgon's creator. |
^gorgon-command-keys

> [!quote] A quote from Lum the Maestro  
> 
> Notable among my eccentric ancestor's scattered designs was a schematic of a swamp-dwelling bovine monster and an ominous note: "Do better."


![](2-Mechanics/CLI/bestiary/construct/img/gorgons.webp#center)

## Statblock

```ad-statblock
title: Brazen Gorgon
![](2-Mechanics/CLI/bestiary/construct/token/brazen-gorgon-xmm.webp#token)
*Large construct, Unaligned*

- **Armor Class** 19 
- **Hit Points** 161 (`17d10 + 68`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|19 (+4)| 2 (-4)|14 (+2)| 7 (-2)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +10
- **Senses** darkvision 60 ft., passive Perception 20
- **Damage Immunities** fire
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** —
- **Challenge** 9

## Traits

***Flame Aura.*** At the end of each of the gorgon's turns, each creature in a 5-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the gorgon takes 13 (`3d8`) Fire damage.

***Illumination.*** The gorgon sheds [Bright Light](2-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md) in a 10-foot radius and [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) for an additional 10 feet.

## Actions

***Multiattack.*** The gorgon makes two Gore attacks.

***Gore.*** *Melee Attack Roll:* `+8`, reach 5 ft. *Hit:* 11 (`2d6 + 4`) Piercing damage plus 10 (`3d6`) Fire damage.

***Smelting Charge (Recharge 5-6).*** The gorgon moves up to its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) without provoking Opportunity Attacks and can move through the spaces of Medium or smaller creatures. Each time the gorgon enters a creature's space for the first time during this move, that target is subjected to the following effect. *Dexterity Saving Throw:* DC 16. *Failure:* 13 (`2d8 + 4`) Piercing damage plus 13 (`3d8`) Fire damage, and the target is pulled into the gorgon's space and has the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14); if the gorgon already has a creature [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the target has the [Prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition instead. Until the grapple ends, the target has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. When the gorgon moves, the [Grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) target moves with it, costing no extra movement.
```
^statblock

## Environment

forest, grassland, hill