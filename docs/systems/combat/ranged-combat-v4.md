---
title: Ranged Combat
status: new
tags:
  - Action
  - Combat
  - Offense
version: 4
---
Test `Aim + Combat` plus Attribute depending on type of weapon
- `Body:` Automatic weapons with high recoil and rate of fire
- `Reflex:` Sidearms, SMG’s, shotguns and assault rifles
- `Mind:` Single shot powerful rifles and support weapons like rocket launchers.
- `Cyber:` Attacks utilizing augments, such as **Targeting System** or remote-operating neural-controlled attack drones

Consider the following conditions that could add to Difficulty of the attack test. Only consider circumstances that make a test more difficult; if something were to make a test impossible, then a test should not be allowed.
- **Target Range:** Add `DIF 1` for each step less or more than Optimal Range
- **Target Velocity:** `DIF 1+`. Objects moving at high [[structure#Velocity|Velocity]] make for more difficult targets. Add the difference in attacker’s and target’s relative velocity, if they are moving faster. Cyborgs may have [[hermes-mobility-suite|augments]] that increase their *Velocity* scale.
- **Target Evasion:** `DIF 1+`. [[mobility-evasion|Evasive maneuvers]] or naturally high [[attributes#Reflex|Reflex attribute]] may make the target hard to hit.
- **Low visibility:** `DIF 1`– `DIF 3`.Darkness, fog, rain, clutter and generally anything that can obscure vision. Poor visibility makes it hard to spot and track target. Such hindrances can be ignored by suitable augments.

In addition, a weapon with high [[weapon-stats-v4#Recoil|Recoil]] may add a complication to the test.

!!! example "Ranged Combat Example"
	 Cyber Joe is tracking a slippery Syndicate assassin on the maze-like streets of ground-level slums. He catches the criminal below an overpass, just as they’re about the disappear into the side alleys of a busy market street. Joe has a brief opportunity and attempts to take a shot.
	 
	 Joe declares he wants to **Aim** and then **Shoot**, using his full turn. GM allows the aim action. There’s not much time, but it only takes a few seconds for a decent aim. This will however be Joe’s only attempt. Not taking the Aim Action Joe could possibly try twice, but Joe decides he wants to go all-in on this.
	 
	 GM considers for a moment and assigns the test two complications: **Difficult 6** and **Collateral 1**, which totals 7 complication points. He needs more successes than that to actually pull off this feat.
	  
	 **Complication: Difficult (6)**: Joe needs to overcome this complication or he will fail the test.
	   - **Target Range (1):** Target is at long range while Joe’s weapon is optimal at Moderate range
	   - **Target Velocity (0):** Target is moving fast, but they’re on foot, so that doesn’t give additional difficulty cost.
	   - **Target Evasion (3):** Target is moving erratically and very skillfully; they definitely don’t want to get hit.
	   - **Low Visibility (2):** It is dark, and there is fog and rain obscuring vision.
	 
	 **Complication: Collateral (1)**: If Complication is not bought off, Joe will hit a bystander
	   - **Bystanders (1):** It’s a busy street, there is a high chance to miss the target and hit an innocent bystander instead. If Joe fails this complication, he hits an innocent bystander, which will result in repercussions. He doesn’t want this to happen.
     
	 The **Collateral 1** complication is optional, while **Difficult 6** is mandatory. It’s not looking good, but luckily Joe has some aces up his sleave.
	
	Joe activates **Sensor Augment** and **Targeting System** to help with the difficulty. He marks 2 energy usage and rolls 2d8 usage check → 4, 7 and passes (any 1-2 would have resulted in failure, resulting in risk of overload).
	- **Sensor Augment**: At Level 1 the augment provides Low-Light Vision, which negates the 1 point penalty due to darkness, but does not negate vision obscurement due to rain and fog and visual clutter.
	- **Targeting System**: At Level 2 he can reduce the target’s Evasion by 2 points, and gets a free re-roll on attack test and reduces cost of **Aimed Hit** effects by one. He can also make Trick Shots, but that is not of any use in this situation.
	  
	  In total with augments Joe reduces the complications to **Difficult 3** and **Collateral 1**, for total 4 complication points. Joe needs to overcome the difficult complication to succeed, while Collateral is optional, although it may have severe repercussions.
	     
	 Joe’s semi-automatic weapon normally uses **Reflex**, but his active **Targeting System** requires using **Cyber** instead. Due to the **Aim Action**, he adds the weapon’s **CTRL** die.
	 
	 **Dice Pool:** 2d10 (Combat+Aim) + 2d8 (Cyber+CTRL) 
	 - Joe rolls **2d10 + 2d8**: 9, 5, 5, 3 → **4 successes** (1 double success (8+), 2 successes (4+), 1 failure). 
	- Using the Targeting System’s Reroll, he rolls the three lower dice again (5, 5, 3): new results are 8, 6, 4
	 - **Final successes:** 9, 8, 6, 4 → **6 total successes** (2 double successes, 2 successes).
	 
	 Joe clears all complications, leaving **2 Effect Points** available.
	  
	 He chooses two **Aimed Hit, Cripple** effects, each reduced by Targeting System from 2 EP to 1 EP, totaling 2 EP – Joe wants the assassin alive.
	    
	 Joe’s sidearm (**DC 6**, **AP 1**) vs. target’s armor (**AC 4**) results in modified **DC 3** hits. The target’s damage thresholds (Body D8): Harm 4, Trauma 8, Fatal 16.
	    
	 **Final Result:** Joe inflicts **2 hits** (total **2d6 damage = 9**), causing a **Trauma** and applying the **Crippled** condition (impaired mobility). The assassin collapses, disabled but alive.


### Effects
All attacks can score a **Single Hit** (1 stack), but the availability of other effects depend on [[weapon_rules#Rate of Fire|Rate Of Fire]].

#### Basic Hits
Available basic hits and their maximum stacks depends on the weapon’s [[weapon_rules#Rate of Fire|ROF]].

| Effect      | Cost | Description                                                                                                                                                                                                      |
| ----------- | ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Single Hit  | 1    | Inflict 1 hit aimed at the general center of mass of the target.                                                                                                                                                 |
| Double Hit  | 1    | 2 hits at Optimal Range; or 1 Hit and 1 Collateral Hit at up to Maximum range. **Multiple targets**.                                                                                                             |
| Triple Hit  | 1    | 3 hits at Optimal Range; or 1 hit and 2 Collateral Hits at up to Maximum range. **Multiple targets**.                                                                                                            |
| Suppression | 2    | Designate a [[threat-zone\|Threat Zone]] where everyone within is at risk of taking a Hit, if they take any other actions than stick to cover. If Suppression is stacked, the number of Hits taken is increased. |

#### Aimed Hits

Available with [[weapon_rules#Rate of Fire|ROF]] **Single** or **Semi**.

Inflict 1 hit carefully aimed at a specific hit location. Actual location varies according to context, but the cost depends on the effect associated with the location. GM can determine custom hit locations and effects as necessary.

| Effect       | Cost | Description                                                                                                                                    |
| ------------ | ---- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Disarm Hit   | 3    | Disarm a target without inflicting any damage to them, unless you want to cause damage as well (you can).                                      |
| Maim Hit     | 2    | A hit to an arm or another limb or support structure operating a weapon. Inflict Maimed condition.                                             |
| Cripple Hit  | 2    | A hit to a leg, or another limb or structural component used for mobility, such as wheels or tracks. Inflict Crippled condition.               |
| Blinding Hit | 3    | A hit to or near eyes/ears or a sensor component affecting detection capabilities and ranged combat, to name a few. Inflict Blinded condition. |
| Critical Hit | 3    | A hit to the skull, or another vulnerable location. Inflict **Triple Damage** after applying Soak.                                             |
