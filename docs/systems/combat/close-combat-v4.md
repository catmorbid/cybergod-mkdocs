---
title: Close Combat
tags:
  - Action
  - Combat
  - Offense
  - Defense
version: 4
status: new
---
Test `Combat + Fighting + Body or Reflex`. You can use either attribute, and the difference is in narrative style of fighting. Body-based close combat tends to be more reliant on brute force, while Reflex-based close combat can be described as more acrobatic and agile.

The target may choose to **Fight Back** but they must spend an **Action/Reaction** to do so. If they do not *fight back*, their [[stats#Evasion|Evasion]] is still used as Difficulty for the attack.

If a Target Fights Back, then the test is resolved as an **Opposed Test**, and both attacker and defender test their close combat skills. Whoever wins the test, may spend their remaining **Effect Points**.

### Melee Damage
If a melee weapon has `Tag: physical` you may add **Melee DC** from [[core-attributes#Body|Body]] attribute to Weapon DC. Unarmed attacks default to **Melee DC** 

### Effects
Maximum hits is limited by [[weapon_rules#Melee speed|Melee Speed]], but there is otherwise no limitation on combining effects.

#### Basic Strikes

| Effect       | Cost | Description                                                                   |
| ------------ | ---- | ----------------------------------------------------------------------------- |
| Strike Hit   | 1    | Inflict 1 Hit at Target. Max Limit [[weapon_rules#Melee speed\|Melee Speed]]. |
| Strike Power | 1    | *Requires* `Tag: Physical`. Improve DC of all Hits by +1. Max Stack 5.        |

#### Aimed Strikes
Make a carefully aimed strike at a specific location. GM may introduce alternate locations and alternate effects if needed. If the attack inflicts [[damage-harm|Serious Harm]] or worse, the attack also inflicts the indicated [[systems/conditions/index|Condition]].

| Effect       | Cost | Description                                                                                                                                         |
| ------------ | ---- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Disarm Hit   | 2    | Disarm a target without inflicting any damage to them, unless you want to cause damage as well (you can).                                           |
| Maim Hit     | 2    | A hit to an arm or another limb or support structure operating a weapon. Inflicts [[maimed]] condition.                                             |
| Cripple Hit  | 2    | A hit to a leg, or another limb or structural component used for mobility, such as wheels or tracks. Inflicts [[crippled]] condition.               |
| Blinding Hit | 3    | A hit to or near eyes/ears or a sensor component affecting detection capabilities and ranged combat, to name a few. Inflicts [[blinded]] condition. |
| Critical Hit | 3    | A hit to the skull, or another vulnerable location. Inflict **Triple Damage** after applying Soak.                                                  |

#### Grappling

| Effect     | Cost | Description                                                                                                      |
| ---------- | ---- | ---------------------------------------------------------------------------------------------------------------- |
| Immobilize | 2    | Target is [[immobilized]] and held, until their next action.                                                     |
| Pin        | 4    | Target must be [[immobilized]]. Target is [[pinned]] until you free them or they succeed in a [[#Forced Escape]] |

### Forced Escape

When [[pinned]], you can either submit your defeat or attempt a *Forced Escape*, risking damage to your *frame*.

- *Both* participants must make an **Opposed Test**: `Hard(3) Toughness + Body`
- You take 1 level of [[harm]]
- You take **Forced Trauma 3** complication; upon failing to overcome the complication, you will take [[harm|3 harm]].
