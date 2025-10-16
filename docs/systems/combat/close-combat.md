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
## Close Combat Actions
When engaging in close combat your options are few: The aggressor will **Fight** their opponent, but the defender may choose to **Fight Back** or attempt **Evading** the attack. If they do not *fight back*, their current [[stats#Evasion|Evasion]], if any is applied to the attack, but Evasion is ignored when taking the *Fight Back* action.

| Close Combat Action | Test                                     |
| ------------------- | ---------------------------------------- |
| Fight               | Fighting(Body \| Reflex)                 |
| Fight Back          | Fighting(Body \| Reflex)                 |
| Evade               | Use Evasion Pool; test Mobility (Reflex) |

### Fight
Test `Fighting (Body | Reflex)`. You can use either Body or Reflex, and the difference is in narrative style of fighting. Body-based close combat tends to be more reliant on brute force, while Reflex-based close combat can be described as more acrobatic and agile.

### Fight Back
The target may choose to **Fight Back** but they must spend an **Action/Reaction** to do so.

If a target *fights back*, then the test is resolved as an **Opposed Test**, and both attacker and defender test their close combat skills. Whoever wins the test, may spend their remaining **Effect Points**. The opposition may well strike back and defeat the attacker.

### Evade
[[stats#Evasion|Evasion]] is the base defense against close combat attacks, unless the defender is *fighting back*. If you do not have enough Evasion, you can also take a *Reaction* to perform the [[action-move-evade|Move and Evade]] action, but unlike *Fight Back* action, this will not allow you to deal damage to your opponent, but can be useful to avoid the attack and escape.

## Melee Damage
If a melee weapon has `Tag: physical` you may add **Physical DC** from [[attributes#Body|Body]] attribute to Weapon DC. Unarmed attacks default to **Physical DC** 

## Effects
Maximum hits is limited by [[weapon-stats-v4#Melee speed|Melee Speed]], but there is otherwise no limitation on combining effects.

#### Basic Strikes

| Effect       | Cost | Description                                                                                  |
| ------------ | ---- | -------------------------------------------------------------------------------------------- |
| Strike Hit   | 1    | Inflict 1 Hit at an eligible Target. Max Limit [[weapon-stats-v4#Melee speed\|Melee Speed]]. |
| Strike Power | 1    | *Requires* `Tag: Physical`. Improve DC of all Hits by +1. Max Stack 5.                       |

#### Aimed Strikes
Make a carefully aimed strike at a specific location. GM may introduce alternate locations and alternate effects if needed. If the attack inflicts [[damage-harm|Serious Harm]] or worse, the attack also inflicts the indicated [[conditions/index|Condition]].

| Effect       | Cost | Description                                                                                                                                         |
| ------------ | ---- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Disarm Hit   | 2    | Disarm a target without inflicting any damage to them, unless you want to cause damage as well (you can).                                           |
| Maim Hit     | 2    | A hit to an arm or another limb or support structure operating a weapon. Inflicts [[maimed]] condition.                                             |
| Cripple Hit  | 2    | A hit to a leg, or another limb or structural component used for mobility, such as wheels or tracks. Inflicts [[crippled]] condition.               |
| Blinding Hit | 3    | A hit to or near eyes/ears or a sensor component affecting detection capabilities and ranged combat, to name a few. Inflicts [[blinded]] condition. |
| Critical Hit | 3    | A hit to the skull, or another vulnerable location. Inflict **Triple Damage** *after* armor DR, but *before* Soak roll.k.                           |

#### Grappling
Unarmed or grappling weapons enable taking grappling effects.

| Effect     | Cost | Description                                                                                                      |
| ---------- | ---- | ---------------------------------------------------------------------------------------------------------------- |
| Immobilize | 2    | Target is [[immobilized]] and held, until their next action.                                                     |
| Pin        | 4    | Target must be [[immobilized]]. Target is [[pinned]] until you free them or they succeed in a [[#Forced Escape]] |

### Forced Escape

When [[pinned]], you can either submit your defeat or attempt a *Forced Escape*, risking damage to your *frame*. Each attempt takes a full round from both participants.

- *Both* participants must make an **Opposed Test**: `Hard(3) Toughness + Body`
- You take [[damage-class|1 Damage]] ignoring [[damage-armor|Armor]] when attempting the test, regardless of outcome.
- You take **Forced Trauma 3** complication; upon failing to overcome the complication, you will take additional [[damage-class|3 Damage]] ignoring [[damage-armor|Armor]].
- If you win, you escape, if they win you remain pinned.
	- Opponent can inflict additional [[damage-class|1 Damage]] for effect they have remaining.
- Total the Harm taken and then roll [[damage-soak|Soak]].
