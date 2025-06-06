---
obsidianUIMode: preview
cssclasses: json5e-item
tags:
- ttrpg-cli/compendium/src/5e/xdmg
- ttrpg-cli/item/attunement/required
- ttrpg-cli/item/rarity/rare
aliases: 
- "Wand of Wonder"
---
# Wand of Wonder
*Rare (requires attunement)*  
![](2-Mechanics/CLI/items/img/wand-of-wonder.webp#right)

- **Weight**: 1.0 lbs.

This wand has 7 charges. While holding it, you can take a [Magic](2-Mechanics/CLI/rules/actions.md#Magic) action to expend 1 charge while choosing a point within 120 feet of yourself. That location becomes the point of origin of a spell or other magical effect determined by rolling on the Wand of Wonder Effects table. Spells cast from the wand have a save DC of 15. If a spell's maximum range is normally less than 120 feet, it becomes 120 feet when cast from the wand. If an effect has multiple possible subjects, the DM determines randomly which among them are affected.

## Regaining Charges

The wand regains `1d6 + 1` expended charges daily at dawn. If you expend the wand's last charge, roll `d20`. On a 1, the wand crumbles into dust and is destroyed.

**Wand of Wonder Effects**

`dice: [](wand-of-wonder-xdmg.md#^wand-of-wonder-effects)`

| dice: 1d100 | Effect |
|-------------|--------|
| 01-20 | You cast a spell originating from the chosen point. Roll `1d10` to determine the spell: on a **1-2**, [Darkness](2-Mechanics/CLI/spells/darkness-xphb.md); on a **3-4**, [Faerie Fire](2-Mechanics/CLI/spells/faerie-fire-xphb.md); on a **5-6**, [Fireball](2-Mechanics/CLI/spells/fireball-xphb.md); on a **7-8**, [Slow](2-Mechanics/CLI/spells/slow-xphb.md); on a **9-10**, [Stinking Cloud](2-Mechanics/CLI/spells/stinking-cloud-xphb.md). |
| 21-25 | Nothing happens at the chosen point of origin. Instead, you have the [Stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of your next turn, believing something awesome just happened. |
| 26-30 | You cast [Gust of Wind](2-Mechanics/CLI/spells/gust-of-wind-xphb.md). The [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md) created by the spell extends from you to the chosen point of origin. |
| 31-35 | Nothing happens at the chosen point of origin. Instead, you take `1d6` Psychic damage. |
| 36-40 | Heavy rain falls for 1 minute in a 120-foot-high, 60-foot-radius [Cylinder](2-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md) centered on the chosen point of origin. During that time, the area of effect is [Lightly Obscured](2-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md). |
| 41-45 | A cloud of 600 oversized butterflies fills a 60-foot-high, 30-foot-radius [Cylinder](2-Mechanics/CLI/rules/variant-rules/cylinder-area-of-effect-xphb.md) centered on the chosen point of origin. The butterflies remain for 10 minutes, during which time the area of effect is [Heavily Obscured](2-Mechanics/CLI/rules/variant-rules/heavily-obscured-xphb.md). |
| 46-50 | You cast [Lightning Bolt](2-Mechanics/CLI/spells/lightning-bolt-xphb.md). The [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md) created by the spell extends from you to the chosen point of origin. |
| 51-55 | The creature closest to the chosen point of origin is enlarged as if you had cast [Enlarge/Reduce](2-Mechanics/CLI/spells/enlarge-reduce-xphb.md) on it. If the target isn't you and can't be affected by that spell, you become the target instead. |
| 56-60 | A magically formed creature appears in an unoccupied space as close to the chosen point of origin as possible. The creature isn't under your control, acts as it normally would, and disappears after 1 hour or when it drops to 0 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). Roll `1d4` to determine which creature appears. On a **1**, a [Rhinoceros](2-Mechanics/CLI/bestiary/beast/rhinoceros-xmm.md) appears; on a **2**, an [Elephant](2-Mechanics/CLI/bestiary/beast/elephant-xmm.md) appears; and on a **3-4**, a [Rat](2-Mechanics/CLI/bestiary/beast/rat-xmm.md) appears. |
| 61-64 | Grass covers a 60-foot-radius circle of ground, with the center of that circle as close to the chosen point of origin as possible. Grass that's already there grows to ten times its normal size and remains overgrown for 1 minute. |
| 65-68 | An object of the DM's choice disappears into the Ethereal Plane. The object must be neither worn nor carried, within 120 feet of the chosen point of origin, and no larger than 10 feet in any dimension. If there are no such objects in range, nothing happens. |
| 69-72 | Nothing happens at the chosen point of origin. Instead, you shrink as if you had cast [Enlarge/Reduce](2-Mechanics/CLI/spells/enlarge-reduce-xphb.md) on yourself and remain in that state for 1 minute. |
| 73-77 | Leaves grow from the creature nearest to the chosen point of origin. Unless they are picked off, the leaves turn brown and fall off after 24 hours. |
| 78-82 | Nothing happens at the chosen point of origin. Instead, a burst of colorful, shimmering light extends from you in a 30-foot [Emanation](2-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md). Each creature in the area must succeed on a DC 15 Constitution saving throw or have the [Blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) condition for 1 minute. A creature repeats the save at the end of each of its turns, ending the effect on itself on a success. |
| 83-87 | Nothing happens at the chosen point of origin. Instead, you cast [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md) on yourself. |
| 88-92 | Nothing happens at the chosen point of origin. Instead, a stream of `1d4 × 10` gems, each worth 1 GP, shoots from the wand's tip in a [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md) 30 feet long and 5 feet wide toward the chosen point of origin. Each gem deals 1 Bludgeoning damage, and the total damage of the gems is divided equally among all creatures in the [Line](2-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). |
| 93-97 | You cast [Polymorph](2-Mechanics/CLI/spells/polymorph-xphb.md), targeting the creature closest to the chosen point of origin. Roll `1d4` to determine the target's new form. On a **1**, the new form is a [Black Bear](2-Mechanics/CLI/bestiary/beast/black-bear-xmm.md); on a **2**, the new form is a [Giant Wasp](2-Mechanics/CLI/bestiary/beast/giant-wasp-xmm.md); on a **3-4**, the new form is a [Frog](2-Mechanics/CLI/bestiary/beast/frog-xmm.md). |
| 98-00 | The creature closest to the chosen point of origin makes a DC 15 Constitution saving throw. On a failed save, the creature has the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and begins to turn to stone. While [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in this way, the creature repeats the save at the end of its next turn. On a successful save, the effect ends. On a failed save, the creature has the [Petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition instead of the [Restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. The petrification lasts until the creature is freed by the [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration-xphb.md) spell or similar magic. |
^wand-of-wonder-effects

*Source: Dungeon Master's Guide (2024) p. 322*