---
title: Weapon Rules
version: 4
tags:
---
This section explains various **Stats** and **Rules** used with weapons.

### Ammo and Reloads

When you use a weapon in combat, you need to track its ammo usage. Each weapon has its own Ammo Tracker on the Frame Sheet. Mark down how much ammo you used and make a [[resource-check|Resource Check]] after the attack using the weapon’s [[#Capacity]] as the **Resource Die**. On failure, you are out of ammo and must spend an action and a use up a [[character-creation/gear/index#Reloads|Reload]].

Each Reload has a Bulk of 0.25, so you can carry 4 Reloads for 1 Bulk. Reloads are specific to weapons you carry, but you can abstract your personal reloads. When looting ammo from dead enemies, you might not find the correct ammo. Also when an ally is out of ammo, they need to have a matching weapon or your reloads won't be of use to them.

**Reload cost**
- Reloading a Sidearm or an Assault weapon weapon consumes 1 action.
- Heavy weapons and Precision weapons require 2 actions.

### Area

**Area stat** is used for explosives and such to determine how large area is affected when the weapon is used. Area of effect weapons can catch multiple enemies under the weapon's effect. Every target near the primary target will take damage, but they can spend a **Reaction** to attempt a `Mobility or Tactics + Reflex` test to quickly hit the dirt or take cover, negating 1 Hit per effect gained. The test is always **Difficult**, but the cost of the Complication depends on the area of effect.


| Area     | Description                                                                                                               | Difficulty |
| -------- | ------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Small    | Radius is few meters at most and can impact up to three targets in close vicinity.                                        | 1          |
| Moderate | 8-15 meter radius. Easily affects up to 10 targets.                                                                       | 2          |
| Large    | 20-40 meter radius. Easily affects dozens of targets.                                                                     | 3          |
| Huge     | Covers a massive area of hundred meters or more. Affects every target in the area, as many as needed, could be thousands. | 4          |

!!! example
	Morales' team of insurgents is ambushed by an ARC-backed regulator force. They are under heavy fire and take cover behind nearby concrete pillars, but the ARC Bulwark giving fire support has an automatic grenade launcher and lands a burst of Frag grenades (Moderate Area) in their general direction. The Bulwark scores 3 hits, firing randomly in the area, so no one takes a direct hit, but everyone takes 3 Hits. Morales takes a Reaction to avoid the hits, choosing to roll with his Mobility skill of 4 with *Difficult 2* complication.. Morales rolls 3D10, scoring 5, 10, 4 → 4 successes – Morales mitigates 2 hits, but the third one lands close enough to inflict damage.

### Capacity
**Capacity `(CAP)`** determines the [[resource-check|Resource Die]] used when making **Ammo Checks**. Higher Capacity means you will run out of ammo less likely and have to reload less frequently. Active [[#Rate of Fire]] determines how much ammo is consumed per attack.

#### Limited Capacity
Noted with the syntax `L[X]` – e.g. `L4` = *4 shots*.

Capacity can be *limited* to a small fixed amount of shots, between 1 and 6. Limited Capacity weapons cannot have any other [[#Rate of Fire]] than [[#Single]], and each attack consumes 1 ammo. Ammo Checks are not made, since number of shots is easy to track.

### Control
Control `(CTRL)` determines how accurate and easy to handle the weapon is. **CTRL** is rated between D4 and D12 and every weapon has a **CTRL** rating. **CTRL** may be applied as [[skill-test#Dice pool|Utility Dice]] on an attack.
- **Ranged Weapons:** the active [[#Rate of Fire]] determines if **CTRL** can be applied or not.
- [[#Melee Weapons]]: always use **CTRL** die. 
### Damage Class
Damage Class `(DC)` determines how effective the weapon is. Damage Class is an abstraction, and actual damage is rolled with dice, but before that you apply modifiers, such as **Armor Class** and **Penetration**. Read more about how to [[damage/index|handle damage]] in the [[systems/combat/index|Combat System.]]

### Melee speed
Melee speed depends the character’s **Body** relative to weapon **Size**. Stronger characters can attack faster. Speed determines how many Hit effects you can purchase when making melee attacks. The exception to this rule is **unarmed** attacks which is always limited to **4 hits** at DC equal to **Body Level**. If an object is too big and heavy, you cannot use it in combat at all.

| Body | Small | Medium | Large | Huge | Massive | Colossal |
| ---- | ----- | ------ | ----- | ---- | ------- | -------- |
| D4   | 2     | 1      | N/A   | N/A  | N/A     | N/A      |
| D6   | 2     | 2      | 1     | N/A  | N/A     | N/A      |
| D8   | 3     | 2      | 2     | 1    | N/A     | N/A      |
| D10  | 3     | 3      | 2     | 2    | 1       | N/A      |
| D12  | 4     | 3      | 3     | 2    | 2       | 1        |

### Penetration
Armor Penetration `(AP)` is subtracted from **Armor Class** to a minimum of 0, before applying armor to `DC`.

### Range

Noted as `Optimal Range - Effective Range`. Or just Optimal Range if only one range is noted.

**Optimal Range** is the [[structure#Distance|Distance]] where weapon is best utilized. Add [[penalties|-1 Penalty]] for *each* range increment more or less than indicated range.

**Effective Range** is the maximum suggested [[structure#Distance|Distance]] the weapon should be used at. [[damage/damage-class|Damage Class]] is reduced by 1 for each range increment further than Effective Range.

### Rate of Fire
Rate of Fire (ROF) determines how rapidly a weapon can fire.See [[ranged-combat-v4#Rate of Fire|Ranged Combat]] for details how ROF is applied in combat.

### Recoil Modifier
Recoil Modifier (RCL) determines how much the weapon contributes to the [[ranged-combat-v4#Recoil|Recoil]] of an attack.
### Size
**Size** `(SIZ)` determines a weapon’s overall mass and length. Ranged Weapons do not list separate Size stat, instead the size of the weapon mostly depends on the weapon’s type. But for Melee weapons, size is used to determined [[#Melee speed]] and [[bulk-v1|Bulk]]. Large weapons also require a certain level of **Body** to be utilized at all, otherwise the weapon is simply too heavy and cumbersome to use. Size and Body together determined [[#Melee speed]] – or many hits you can land in per attack.

| Size     | Bulk | Min. Body |
| :------- | :--- | --------- |
| Small    | 1    | -         |
| Medium   | 2    | D4        |
| Large    | 3    | D6        |
| Huge     | 4    | D8        |
| Massive  | 5    | D10       |
| Colossal | 6    | D12       |
### Weapon Tags

Tags are used for additional rules regarding weapons.

[todo list tags]

