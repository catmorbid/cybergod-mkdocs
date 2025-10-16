---
title: Ranged Combat
status: new
tags:
  - Action
  - Combat
  - Offense
version: 4
---
Test `Aim` plus **Attribute** depending on type of weapon
- `Body:` Automatic weapons with high recoil and rate of fire
- `Reflex:` Sidearms, SMG’s, shotguns and assault rifles
- `Mind:` Single shot powerful rifles and support weapons like rocket launchers.
- `Cyber:` Attacks utilizing augments, such as **Targeting System** or remote-operating neural-controlled attack drones

Consider the following circumstantial [[penalties]]:

- **Target Range:** Add **-1 penalty** for each step less or more than [[weapon-stats-v4#Range|Optimal Range]].
- **Target Velocity:** Apply **-1 penalty** or worse. Objects moving at high [[structure#Velocity|Velocity]] make for more difficult targets. Add the difference in attacker’s and target’s relative velocity, if they are moving faster. Cyborgs may have [[hermes-mobility-suite|augments]] that increase their *Velocity* scale.
- **Target Evasion:** Apply target’s current [[stats#Evasion|Evasion]] as **penalty**. [[action-move-evade|Evasive maneuvers]] or naturally high [[attributes#Reflex|Reflex attribute]] may make the target hard to hit. Evasion may include *Mobility* or *Cover* based bonuses.
- **Low visibility:** Apply **-1 to -3 penalty**. Darkness, fog, rain, clutter and generally anything that can obscure vision, makes it more difficult to spot the *correct* target or track them. Such hindrances can be ignored by suitable augments or gadgets.

In addition, a weapon with high [[weapon-stats-v4#Recoil|Recoil]] may add a complication to the test.

!!! example "Ranged Combat Example"
	 Cyber Joe is tracking a slippery Syndicate assassin on the maze-like streets of ground-level slums. He catches the criminal below an overpass, just as they’re about the disappear into the side alleys of a busy market street. Joe has a brief opportunity and attempts to take a shot.
	 
	 Joe declares he wants to **Aim** and then **Shoot**, using his full turn. GM allows the aim action. There’s not much time, but it only takes a few seconds for a decent aim. This will however be Joe’s only attempt. Not taking the Aim Action Joe could possibly try twice, but Joe decides he wants to go all-in on this.
	 
	 GM considers for a moment and assigns the test the following modifiers:
	
	   - **Target Range (-1):** Target is at long range while Joe’s weapon is optimal at Moderate range
	   - **Target Evasion (-3):** Target is moving erratically and very skillfully; they definitely don’t want to get hit.
	   - **Low Visibility (-2):** It is dark, and there is fog and rain obscuring vision.
	   - **Complication 'Bystanders 1':** It’s a busy street, there is a high chance to miss the target and hit an innocent bystander instead.
     
		 The **Bystanders 1* complication is optional, while the rest accumulate a total of -6 penalty to the test. It’s not looking good, but luckily Joe has some aces up his sleave.
	
	Joe activates **Sensor Augment** and **Targeting System** to help with the difficulty. He marks 2 energy usage and rolls 2d8 usage check → 4, 7 and passes (any 1-2 would have resulted in failure, resulting in risk of overload).
	- **Sensor Augment**: At Level 1 the augment provides Low-Light Vision, which negates the 1 point penalty due to darkness, but does not negate vision obscurement due to rain and fog and visual clutter.
	- **Targeting System**: At Level 2 he can reduce the target’s Evasion by 2 points, and gets a free re-roll on attack test and reduces cost of **Aimed Hit** effects by one. He can also make Trick Shots, but that is not of any use in this situation.
	  
	  In total with augments Joe reduces the penalties to -3, but also has the 'Bystanders 1' complication to overcome.
	     
	 Joe’s semi-automatic weapon normally uses **Reflex**, but his active **Targeting System** requires using **Cyber** instead. Due to the **Aim Action**, he adds the weapon’s **CTRL** die.
	 
	 **Dice Pool:** 2d10 (Combat+Aim) + 2d8 (Cyber+CTRL) 
	 - Joe rolls **2d10 + 2d8**: 9, 5, 5, 3 → **4 successes** (1 double success (8+), 2 successes (4+), 1 failure). 
	- Using the Targeting System’s Reroll, he rolls the three lower dice again (5, 5, 3): new results are 8, 6, 4
	 - **Final successes:** 9, 8, 6, 4 → **6 total successes** (2 double successes, 2 successes).
	 
	 After penalties, Joe has 3 **Effect Points**, enough to overcome the 'Bystanders 1' complication, leaving **2 Effect Points** available.
	  
	 He chooses one **Aimed Hit, Cripple** effect, reduced by Targeting System from 3 EP to 2 EP – Joe wants the assassin alive.
	    
	 Joe’s sidearm (**DC 6**, **AP 1**) vs. target’s armor (**AC 4**) results in modified **DC 3** hits. The target’s damage thresholds (Body D8): Harm 4, Trauma 8, Fatal 16.
	    
	 **Final Result:** Joe inflicts **1 hit** (total **1d6 damage = 6**), causing a **Harm** and applying the **Crippled** condition (impaired mobility). The assassin collapses, unable to move quickly, but alive enough for interrogation...

### Ranged Weapons in Close Combat
If end up having to use a ranged weapon in [[weapon-stats-v4#Range|Close Range]], resolve the attack as [[close-combat|Close Combat]] action instead. Target can fight back and you do not get the weapon’s CTRL die applied. If you fight better than opponent, you can score either close combat or ranged combat hits, but ranged combat Hits cost additional 1 EP.

### Rate of Fire

*Rate of Fire* (ROF) determines how rapidly you can fire a weapon, described on a scale of 1-6. You can choose your **Effective ROF**, between 1 and weapon ROF rating.

Each point of *Effective ROF* has following effects:
- Gain 1 CTRL Die per 2 ROF as utility modifier.
- Increase Recoil by 1 per ROF
- Roll one die per ROF for ammo [[resource-check|Resource Check]].
- Maximum number of **Hits** is equal to **ROF**.

### Recoil

Effective Recoil is equal to [[weapon-stats-v4#Recoil|Weapon Recoil]] + [[#Rate of Fire|Effective Rate of Fire]]. It is applied as a [[skill-test#Complications|Complication]] to the [[ranged-combat-v4|Attack Test]].

> E.g. Assault Rifle has ROF 3 and RCL +0. Firing the weapon with effective ROF 2 has Recoil of 2.

If you fail to overcome Recoil, you are thrown out of balance and will *lose your next Action or Reaction*, when trying to recover your balance.

*Recoil* is modified by [[attributes#Body|Body attribute]], and other modifications (such as those from [[recoil-compensator|Augments]]). If Recoil is dropped to zero or less, you can make the attack test without the added complication.


Recoil can be reduced by 1 point by having a portable support device for the weapon, such as a bipod. The support device typically adds **2 Bulk**. Properly mounted weapons always mitigate the recoil entirely.
### Effects
You can choose from available Hit Effects determined by the weapon’s [[#Rate of Fire|Rate Of Fire]].

#### Basic Hits
Available basic hits and their maximum stacks depends on the weapon’s [[#Rate of Fire|ROF]]. *You assign any Hits freely between any eligible targets.*

| Effect      | Cost | Description                                                                                          |
| ----------- | ---- | ---------------------------------------------------------------------------------------------------- |
| Ranged Hit  | 2    | 1 Hit at any eligible targets. Stacks up *Effective ROF*.                                            |
| Suppression | 1    | *Requires ROF 2 or greater.* One target is [[suppressed]] for 1 round. Suppression. Stack up to ROF. |

#### Aimed Hits

Aimed Hits *Require [[#Rate of Fire|Effective Rate of Fire]] of 2 or less*.

Inflict 1 hit carefully aimed at a specific hit location. Actual location varies according to context, but the cost depends on the effect associated with the location. GM can determine custom hit locations and effects as necessary. Any **Conditions** are inflicted only if target takes [[damage-harm|Serious Harm]] or worse.

| Effect       | Cost | Description                                                                                                                                        |
| ------------ | ---- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Disarm Hit   | 3    | Disarm a target without inflicting any damage to them, unless you want to cause damage as well (you can).                                          |
| Maim Hit     | 3    | A hit to an arm or another limb or support structure operating a weapon. Inflict [[maimed]] condition.                                             |
| Cripple Hit  | 3    | A hit to a leg, or another limb or structural component used for mobility, such as wheels or tracks. Inflict [[crippled]] condition.               |
| Blinding Hit | 4    | A hit to or near eyes/ears or a sensor component affecting detection capabilities and ranged combat, to name a few. Inflict [[blinded]] condition. |
| Critical Hit | 4    | A hit to the skull, or another vulnerable location. Inflict **Triple Damage** *after* armor DR, but *before* Soak roll.                            |
