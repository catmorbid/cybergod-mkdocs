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

Consider the following circumstantial [[penalties]]:

- **Target Range:** Add **-1 penalty** for each step less or more than [[weapon-stats-v4#Range|Optimal Range]].
- **Target Velocity:** Apply **-1 penalty** or worse. Objects moving at high [[structure#Velocity|Velocity]] make for more difficult targets. Add the difference in attacker’s and target’s relative velocity, if they are moving faster. Cyborgs may have [[hermes-mobility-suite|augments]] that increase their *Velocity* scale.
- **Target Evasion:** Apply target’s current [[stats#Evasion|Evasion]] as **penalty**. [[mobility-evasion|Evasive maneuvers]] or naturally high [[attributes#Reflex|Reflex attribute]] may make the target hard to hit. Evasion may include *Mobility* or *Cover* based bonuses.
- **Low visibility:** Apply **-1 to -3 penalty**. Darkness, fog, rain, clutter and generally anything that can obscure vision, makes it more difficult to spot the *correct* target or track them. Such hindrances can be ignored by suitable augments or gadgets.

In addition, a weapon with high [[weapon-stats-v4#Recoil|Recoil]] may add another complication to the test.

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
If end up having to use a ranged weapon in [[weapon-stats-v4#Range|Close Range]]

### Effects
All attacks can score a **Single Hit** (1 stack), but the availability of other effects depend on [[weapon_rules#Rate of Fire|Rate Of Fire]].

#### Basic Hits
Available basic hits and their maximum stacks depends on the weapon’s [[weapon_rules#Rate of Fire|ROF]]. Default attacks apply all hits against a Single target, but you can spend EP to purchase additional targets.

| Effect       | Cost | Description                                                                                                                                                                                                      |
| ------------ | ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Single Hit   | 2    | 1 Hit                                                                                                                                                                                                            |
| Double Hit   | 2    | 2 Hits at *Optimal Range*; 1 Hit at other ranges                                                                                                                                                                 |
| Triple Hit   | 2    | 3 Hits at *Optimal Range*; 1 Hit at other ranges                                                                                                                                                                 |
| Quad Hit     | 2    | 4 Hits at *Optimal Range*; 2 Hits at other ranges                                                                                                                                                                |
| Extra Target | 1    | Add an extra target. You can distribute any Hits freely between targets.                                                                                                                                         |
| Suppression  | 2    | Designate a [[threat-zone\|Threat Zone]] where everyone within is at risk of taking a Hit, if they take any other actions than stick to cover. If Suppression is stacked, the number of Hits taken is increased. |

#### Aimed Hits

Available with [[weapon-stats-v4#Rate of Fire|ROF]] **Single** or **Semi**.

Inflict 1 hit carefully aimed at a specific hit location. Actual location varies according to context, but the cost depends on the effect associated with the location. GM can determine custom hit locations and effects as necessary. Any **Conditions** are inflicted only if target is **Harmed** or worse.

| Effect       | Cost | Description                                                                                                                                                                                  |
| ------------ | ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Disarm Hit   | 3    | Disarm a target without inflicting any damage to them, unless you want to cause damage as well (you can).                                                                                    |
| Maim Hit     | 3    | A hit to an arm or another limb or support structure operating a weapon. If target is [[harm\|Harmed]] or worse, they take [[maimed]] condition.                                             |
| Cripple Hit  | 3    | A hit to a leg, or another limb or structural component used for mobility, such as wheels or tracks. If target is [[harm\|Harmed]] or worse, they take [[crippled]] condition.               |
| Blinding Hit | 4    | A hit to or near eyes/ears or a sensor component affecting detection capabilities and ranged combat, to name a few. if target is [[harm\|Harmed]] or worse, they take [[blinded]] condition. |
| Critical Hit | 4    | A hit to the skull, or another vulnerable location. Inflict **Triple Damage** after applying Soak.                                                                                           |
