---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/environment/beastlands
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
aliases: ["Animal Lord"]
---
# Animal Lord
*Source: Monster Manual (2024) p. 15*  
![](2-Mechanics/CLI/bestiary/celestial/img/animal-lord.webp#right)

## Animal Lord

*Immortal Regent of the Wild*

- **Habitat.** Planar (Beastlands)  
- **Treasure.** Relics  

Animal lords are the immortal spirits of legendary animals. They serve as the divine protectors of animals of their kind, and they appear as hybrids of humanoids and the animals they defend. They frequently change into giant, idealized versions of the animals they're associated with—albeit with glowing eyes. When contending with people, they sometimes appear as humanlike beings with subtle, animal-like features. No matter their appearance, animal lords exhibit the instincts and predilections of the animals they represent, tempered by their intellect and experience.

Most animal lords make their homes in the Beastlands, but they occasionally journey to the Feywild or other idyllic realms. They rarely travel to the Material Plane, making exceptions only when a world faces environmental disaster or droves of animals are otherwise in jeopardy.

Among the best-known animal lords are those that represent cats, hawks, lizards, and wolves, but animal lords exist for beasts of all types. Some animal lords even embody creatures that are rare or extinct on Material Plane worlds, like megafauna or dinosaurs. Using their divine might, animal lords can summon spectral animals, channel spiritual energy, and exhibit powers associated with one of three broad groups: foragers, hunters, or sages. These powers are tied to an animal lord's personality and traits associated with the creature it resembles. Roll on or choose results from the relevant Animal Lord Appearances table to inspire what creature an animal lord resembles.

> [!quote] A quote from Brother of Shadows, Cat Lord  
> 
> While I don't deny the compliment, I assure you, I'm more akin to a god than a "pretty kitty."

> [!quote] A quote from Wind and Moon, Wolf Lord  
> 
> You call yourself hunter, but your fear makes you smell like prey.

**Forager Animal Lord Appearances**

`dice: [](animal-lord-xmm.md#^forager-animal-lord-appearances)`

| dice: 1d10 | Bestial Shape |
|------------|---------------|
| 1 | Bear |
| 2 | Bee |
| 3 | Bison |
| 4 | Capybara |
| 5 | Carp |
| 6 | Rabbit |
| 7 | Rooster |
| 8 | Sloth |
| 9 | Stag |
| 10 | Vulture |
^forager-animal-lord-appearances

**Hunter Animal Lord Appearances**

`dice: [](animal-lord-xmm.md#^hunter-animal-lord-appearances)`

| dice: 1d10 | Bestial Shape |
|------------|---------------|
| 1 | Alligator |
| 2 | Badger |
| 3 | Bat |
| 4 | Cat |
| 5 | Hawk |
| 6 | Mongoose |
| 7 | Praying mantis |
| 8 | Shark |
| 9 | Snake |
| 10 | Wolf |
^hunter-animal-lord-appearances

**Sage Animal Lord Appearances**

`dice: [](animal-lord-xmm.md#^sage-animal-lord-appearances)`

| dice: 1d10 | Bestial Shape |
|------------|---------------|
| 1 | Coyote |
| 2 | Crow |
| 3 | Elephant |
| 4 | Lizard |
| 5 | Mouse |
| 6 | Owl |
| 7 | Salmon |
| 8 | Spider |
| 9 | Turtle |
| 10 | Whale |
^sage-animal-lord-appearances

```ad-statblock
title: Animal Lord
![](2-Mechanics/CLI/bestiary/celestial/token/animal-lord-xmm.webp#token)
*Medium celestial, Neutral*

- **Armor Class** 19 
- **Hit Points** 323 (`34d8 + 170`) 
- **Speed** 60 ft., fly 60 ft. (hover), swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|25 (+7)|20 (+5)|19 (+4)|23 (+6)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +11, Wisdom +12
- **Skills** Acrobatics +13, Athletics +13, Perception +18, Stealth +13
- **Senses** truesight 120 ft., passive Perception 28
- **Damage Resistances** cold, fire, necrotic, psychic, radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** all
- **Challenge** 20

## Traits

***Animal Lordship.*** An animal lord represents a Forager, Hunter, or Sage (DM's choice), which determines certain traits in this stat block.

***Legendary Resistance (4/Day).*** If the animal lord fails a saving throw, it can choose to succeed instead.

***Lordly Presence.*** *Wisdom Saving Throw:* DC 20, any enemy that starts its turn in a 30-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the animal lord. *Failure:* The target suffers one of the following effects:

- **Captivated (Forager Only).** The target has the [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition until the end of its next turn. While [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), the target has the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.  
- **Fearful (Hunter Only).** The target has the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the end of its next turn.  
- **Mired (Sage Only).** The target takes 10 (`3d6`) Psychic damage, and the target is magically bewildered until the end of its next turn. While bewildered, the target subtracts `1d4` from its saving throws.  

***Magic Resistance.*** The animal lord has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Spellcasting.*** The animal lord casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 20):

**At will**: [Animal Friendship](2-Mechanics/CLI/spells/animal-friendship-xphb.md), [Animal Messenger](2-Mechanics/CLI/spells/animal-messenger-xphb.md), [Speak with Animals](2-Mechanics/CLI/spells/speak-with-animals-xphb.md)

**1/day each**: [Animal Shapes](2-Mechanics/CLI/spells/animal-shapes-xphb.md), [Sunburst](2-Mechanics/CLI/spells/sunburst-xphb.md)

**2/day each**: [Awaken](2-Mechanics/CLI/spells/awaken-xphb.md), [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration-xphb.md)

## Actions

***Multiattack.*** The animal lord makes two attacks, using Rend or Radiant Ray in any combination, and uses Animal Spirit.

***Rend.*** *Melee Attack Roll:* `+13`, reach 5 ft. *Hit:* 14 (`2d6 + 7`) Slashing damage plus 7 (`2d6`) Force damage.

***Radiant Ray.*** *Ranged Attack Roll:* `+12`, range 120 ft. *Hit:* 20 (`4d6 + 6`) Radiant damage.

***Animal Spirit.*** The animal lord conjures an animal spirit that strikes at a creature and then disappears. *Dexterity Saving Throw:* DC 20, one creature the animal lord can see within 120 feet. *Failure:* 28 (`4d10 + 6`) Radiant damage. *Success:* Half damage. *Failure or Success:* One of the following effects occurs:

- **Fortify (Forager Only).** The animal lord gains 20 [Temporary Hit Points](2-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md).  
- **Marked as Prey (Hunter Only).** The animal lord has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls against the target until the start of the animal lord's next turn.  
- **Pesky Swarm (Sage Only).** The target has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks until the end of its next turn.  

## Bonus Actions

***Shape-Shift.*** The animal lord shape-shifts into a Huge or smaller version of the animal it represents or a Medium or Small Humanoid, or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.

## Legendary Actions

***Feral Strike.*** The animal lord moves up to its [Speed](2-Mechanics/CLI/rules/variant-rules/speed-xphb.md) without provoking Opportunity Attacks, and it makes one Rend attack.

***Radiant Strike.*** The animal lord makes one Radiant Ray attack.
```
^statblock

## Environment

planar, beastlands