---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/limbo
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
aliases: ["Death Slaad"]
---
# Death Slaad
*Source: Monster Manual (2024) p. 287*  
![](2-Mechanics/CLI/bestiary/aberration/img/death-slaad.webp#right)

Slaad lords create death slaadi by infusing gray slaadi with a portion of their chaotic energy. When groups of slaadi act deliberately, death slaadi are often behind their designs.

## Slaadi

*Chaos-Spawned Hordes of Limbo*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Any  

Unpredictable slaadi devour and multiply across the Ever-Changing Chaos of Limbo. These toad-like, extraplanar beings embody the endless potentiality of their home plane of existence. While slaadi aren't inherently evil, their impulses are wild and often destructive. Many are driven to propagate through supernatural processes. Unfortunately, these processes typically are fatal for other creatures.

Slaadi have no formal society. Rather, strong slaadi dominate weaker ones. Blue and red slaadi rampage across Limbo and spill into other worlds at the direction of green slaadi. More powerful slaadi have connections to the Spawning Stone, a source of chaotic magic from which the first slaadi originated. The Spawning Stone is hidden deep within Limbo, and legends tie its origins to the modron overlord Primus or the ruinous slaad lords, such as Ssendam, the golden amoeboid terror, and Ygorl, the winged skeleton. These slaad lords and others plot to spread slaadi across the multiverse.

> [!note] Slaad Control Gems
> 
> A slaad born from the Spawning Stone has a magical control gem embedded in its head. If a creature claims the gem, the slaad has the [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition and obeys the gem's bearer. The slaad ceases to be [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) if it is harmed by the gem's bearer or the bearer's allies or if the gem is returned to the slaad. A [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration-xphb.md) spell cast on a slaad destroys the gem, and the slaad ceases to be [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed).
> 
> One can obtain a slaad's control gem using a [Wish](2-Mechanics/CLI/spells/wish-xphb.md) or [Imprisonment](2-Mechanics/CLI/spells/imprisonment-xphb.md) spell. If the slaad fails its saving throw against [Imprisonment](2-Mechanics/CLI/spells/imprisonment-xphb.md), the caster gains the gem, and the slaad isn't imprisoned. An [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) slaad's control gem can be removed by spending 1 minute and succeeding on a DC 20 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. Failing this check deals 22 (`4d10`) Piercing damage to the slaad.
^slaad-control-gems

> [!quote] A quote from Jebeel Sloom  
> 
> Fight a slaad and lose, the story's over. Fight a slaad and win, there's a thousand more standing in line just to prove they're tougher.


## Statblock

```ad-statblock
title: Death Slaad
![](2-Mechanics/CLI/bestiary/aberration/token/death-slaad-xmm.webp#token)
*Medium aberration, Chaotic Evil*

- **Armor Class** 18 
- **Hit Points** 178 (`21d8 + 84`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|19 (+4)|15 (+2)|10 (+0)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Arcana +6, Perception +8
- **Senses** blindsight 60 ft., darkvision 60 ft., passive Perception 18
- **Damage Resistances** acid, cold, fire, lightning, thunder
- **Languages** Common, Slaad; telepathy 60 ft.
- **Challenge** 10

## Traits

***Magic Resistance.*** The slaad has [Advantage](2-Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Regeneration.*** The slaad regains 10 [Hit Points](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) at the start of each of its turns if it has at least 1 [Hit Point](2-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

***Spellcasting.*** The slaad casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](2-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Invisibility](2-Mechanics/CLI/spells/invisibility-xphb.md) (self only), [Mage Hand](2-Mechanics/CLI/spells/mage-hand-xphb.md), [Major Image](2-Mechanics/CLI/spells/major-image-xphb.md)

**1/day each**: [Blight](2-Mechanics/CLI/spells/blight-xphb.md) (level 8 version), [Cloudkill](2-Mechanics/CLI/spells/cloudkill-xphb.md) (level 6 version), [Fly](2-Mechanics/CLI/spells/fly-xphb.md), [Plane Shift](2-Mechanics/CLI/spells/plane-shift-xphb.md), [Tongues](2-Mechanics/CLI/spells/tongues-xphb.md)

## Actions

***Multiattack.*** The slaad makes two Chaos Blade attacks.

***Chaos Blade.*** *Melee Attack Roll:* `+9`, reach 10 ft. *Hit:* 11 (`1d12 + 5`) Slashing damage plus 10 (`3d6`) Necrotic damage. Until the start of the slaad's next turn, the target has a condition determined by rolling `1d4`: on a 1, [Charmed](2-Mechanics/CLI/rules/conditions.md#Charmed); on a 2, [Frightened](2-Mechanics/CLI/rules/conditions.md#Frightened); on a 3, [Poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned); or on a 4, [Incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Bonus Actions

***Shape-Shift.*** The slaad shape-shifts into a Small or Medium Humanoid, or it returns to its true form. Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```
^statblock

## Environment

planar, limbo