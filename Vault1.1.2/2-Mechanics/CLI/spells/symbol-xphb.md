---
obsidianUIMode: preview
cssclasses: json5e-spell
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/spell/class/bard
- ttrpg-cli/spell/class/cleric
- ttrpg-cli/spell/class/druid
- ttrpg-cli/spell/class/wizard
- ttrpg-cli/spell/level/7th-level
- ttrpg-cli/spell/school/abjuration
- ttrpg-cli/spell/subclass/abjurer
- ttrpg-cli/spell/subclass/divine-soul
classes:
- Bard
- Cleric
- Druid
- Sorcerer (Divine Soul)
- Wizard
- Wizard (Abjurer)
aliases: ["Symbol"]
---
# Symbol
*7th-level, Abjuration*  


- **Casting time:** 1 minute
- **Range:** Touch
- **Components:** V, S, M (powdered diamond worth 1,000+ GP, which the spell consumes)
- **Duration:** Until dispelled or triggered

You inscribe a harmful glyph either on a surface (such as a section of floor or wall) or within an object that can be closed (such as a book or chest). The glyph can cover an area no larger than 10 feet in diameter. If you choose an object, it must remain in place; if it is moved more than 10 feet from where you cast this spell, the glyph is broken, and the spell ends without being triggered.

The glyph is nearly imperceptible and requires a successful Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check against your spell save DC to notice.

When you inscribe the glyph, you set its trigger and choose which effect the symbol bears: Death, Discord, Fear, Pain, Sleep, or Stunning. Each one is explained below.

## Set the Trigger

You decide what triggers the glyph when you cast the spell. For glyphs inscribed on a surface, common triggers include touching or stepping on the glyph, removing another object covering it, or approaching within a certain distance of it. For glyphs inscribed within an object, common triggers include opening that object or seeing the glyph.

You can refine the trigger so that only creatures of certain types activate it (for example, the glyph could be set to affect Aberrations). You can also set conditions for creatures that don't trigger the glyph, such as those who say a certain password.

Once triggered, the glyph glows, filling a 60-foot-radius Sphere with [Dim Light](2-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md) for 10 minutes, after which time the spell ends. Each creature in the Sphere when the glyph activates is targeted by its effect, as is a creature that enters the Sphere for the first time on a turn or ends its turn there. A creature is targeted only once per turn.

## Death

Each target makes a Constitution saving throw, taking `10d10` Necrotic damage on a failed save or half as much damage on a successful save.

## Discord

Each target makes a Wisdom saving throw. On a failed save, a target argues with other creatures for 1 minute. During this time, it is incapable of meaningful communication and has [Disadvantage](2-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks.

## Fear

Each target must succeed on a Wisdom saving throw or have the [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute. While [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), the target must move at least 30 feet away from the glyph on each of its turns, if able.

## Pain

Each target must succeed on a Constitution saving throw or have the [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition for 1 minute.

## Sleep

Each target must succeed on a Wisdom saving throw or have the [Unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition for 10 minutes. A creature awakens if it takes damage or if someone takes an action to shake it awake.

## Stunning

Each target must succeed on a Wisdom saving throw or have the [Stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute.

## Summary

**Classes**: [Sorcerer (Divine Soul)](2-Mechanics/CLI/lists/list-spells-classes-sorcerer-xphb-divine-soul-xge.md "subclass=XGE;class=XPHB"); [Druid](2-Mechanics/CLI/lists/list-spells-classes-druid.md); [Cleric](2-Mechanics/CLI/lists/list-spells-classes-cleric.md); [Wizard](2-Mechanics/CLI/lists/list-spells-classes-wizard.md); [Bard](2-Mechanics/CLI/lists/list-spells-classes-bard.md); [Wizard (Abjurer)](2-Mechanics/CLI/lists/list-spells-classes-wizard-xphb-abjurer-xphb.md "subclass=XPHB;class=XPHB")

*Source: Player's Handbook (2024) p. 329. Available in the Free Rules (2024)*