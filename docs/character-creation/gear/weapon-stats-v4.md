---
title: Weapon Rules
version: 4
tags:
---
This section explains various **Stats** and **Rules** used with weapons.
### Area

Area is used for explosives and such to determine how large area is affected when the weapon is used. Area of effect weapons can catch multiple enemies under the weapon's effect. Every target near the primary target will take damage, but they can spend a **Reaction** to attempt a `Mobility or Tactics + Reflex` test to quickly hit the dirt or take cover, negating 1 Hit per effect gained. The test is always **Difficult**, but the cost of the Complication depends on the area of effect.


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



See [[ranged-combat-v4|Ranged Combat]] for details how this works.

A weapon can have one or more ROF modes listed, and you must choose which mode to use before engaging your target. Each ROF mode is abbreviated with a single letter, which can be joined to short *string* of text.

!!! example
	*July* has a small concealable highly customized Gauss pistol as a sidearm. The ROF for the weapon is SEA, meaning it can be fired in Single, Semi or Auto.
#### Single
- **Code:** `S`
- **Effects:** Single Hit (max 1), Aimed Hit (max 1)
- **Evasion Cost:** 1
- **Miss Effect:** No effect
- **Recoil Modifier:** None
- **Ammo Usage:** None, Unless weapon has [[#Limited Capacity]]

Fire single shots. Hits are limited to one. Does not use any ammo, unless weapon has [[#Limited Capacity]]. If you take **Aim** action, you can add weapon **CTRL** dice as Utility Dice to the attack.

#### Semi
- **Code:** `E`
- **Effects:** Single Hit (max 4), Aimed Hit (max 2), Suppression (max 1)
- **Evasion Cost:** 1
- **Miss Effect:** 1 Collateral Hit
- **Recoil Modifier:** None
- **Ammo Usage:** 1

Fire several consecutive shots, not quite as fast as full auto weapons, but fast enough to inflict several hits. You can even land a few more Aimed Hits, but not quite as many as when simply aiming for center of mass. If you take **Aim** action before attack, you add **CTRL** dice as Utility Dice.

Weapons with [[#Limited Capacity]] can be semi-automatic, but you need to choose *before attacking* how many shots to spend, between 1 and 4, limiting the max number of Hits you can obtain.

#### Burst
- **Code:** `B`
- **Effects:** Double Hit (max 2), Suppression (max 1)
- **Evasion Cost:** 1
- **Miss Effect:** 1 Collateral Hit
- **Recoil Modifier:** +1
- **Ammo Usage:** 1

Fire a short automatic burst, improving chance of landing a second hit, but usually wasting at least one shot. A Burst is not that much different than a single shot, but usually produced significantly bigger kick. If you take **Aim** action before attack, you add **CTRL** dice as Utility Dice.

#### Auto
- **Code:** `A`
- **Effects:** Double Hit (max 3), Suppression (max 2)
- **Evasion Cost:** 2
- **Miss Effect:** 2 Collateral Hits
- **Recoil Modifier:** +2
- **Ammo Usage:** 2

Fire a long fully automatic burst. Very good at suppression and sustained fire. Consumes a lot of ammo, and misses most shots, but when properly utilized can be extremely effective. Apply **CTRL** as Utility Dice.

#### Rapid
- **Code:** `R`
- **Effects:** Triple Hit (max 3), Suppression (max 2)
- **Evasion Cost:** 3
- **Miss Effect:** 3 Collateral Hits
- **Recoil Modifier:** +3
- **Ammo Usage:** 3

High rate of fire and high ammo consumption. Rapid fire weapons can be devastating due to sheer volume of shots fired, but they are harder to control. Apply **2 CTRL Dice** as Utility Dice.
#### Extreme
- **Code:** `X`
- **Effects:** Quad Hit (max 3), Suppression (max 4)
- **Evasion Cost:** 4
- **Miss Effect:** 4 Collateral Hits
- **Recoil Modifier:** +4
- **Ammo Usage:** 4

Highest practical rate of fire, usually found in heavy weapons bolted to a support platform with multiple rotary barrels and an electric feed mechanism. They fire at incredibly high rate of fire with extremely high ammo consumption and immense recoil. Apply **3 CTRL Dice** as Utility Dice.

### Recoil

Recoil is measured with a number, generally between 0 and 5. Recoil describes how much a weapon kicks when fired. High recoil can throw the character out of balance and makes controlling the weapon more difficult, which is especially important with automatic weapons.

**System**
*Recoil* is applied as a [[skill-test#Complications|Complication]] to the [[ranged-combat-v4|Attack Test]]. Cost is modified by active [[#Rate of Fire]].

> E.g. Assault Rifle has ROF `SEA` and RCL 2. Firing on semi-auto mode is RCL 1 while Full auto is RCL 3

If you fail to overcome Recoil, you are thrown out of balance and will *lose your next Action or Reaction*, when trying to recover your balance.

*Recoil* is modified by [[attributes#Body|Body attribute]], and other modifications (such as those from [[recoil-compensator|Augments]]). If Recoil is dropped to zero or less, you can make the attack test without the added complication.

| Body D4    | Body D6    | Body D8   | Body D10  | Body D12  |
| ---------- | ---------- | --------- | --------- | --------- |
| Recoil + 1 | Recoil + 0 | Recoil -1 | Recoil -2 | Recoil -3 |
Recoil can be reduced by 1 point by having a portable support device for the weapon, such as a bipod. The support device typically adds **2 Bulk**. Properly mounted weapons always mitigate the recoil entirely.

### Reloads

Each Reload has a Bulk of 0.25, so you can carry 4 Reloads for 1 Bulk. Reloads are specific to weapons you carry, but you can abstract your personal reloads. When looting ammo from dead enemies, you might not find the correct ammo. Also when an ally is out of ammo, they need to have a matching weapon or your reloads won't be of use to them.

**Reload cost**
- Reloading a Sidearm or an Assault weapon weapon consumes 1 action.
- Heavy weapons and Precision weapons require 2 actions.

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

