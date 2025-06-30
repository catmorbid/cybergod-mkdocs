---
title: Damage System
version: 4
status: new
---
# Taking Damage

Compare total points of Damage inflicted to your [[core-attributes#Damage Threshold|Damage Threshold]] to determine the degree of Harm inflicted. There are total of four different Thresholds derived from the [[core-attributes#Body|Body]] attribute.

Choose highest threshold that was met by the damage. If no threshold was met, you take a point of **Shock**.

## Shock
Minor damage is represented by **Shock**. When enough Shock accumulates you take a condition, which stays in play until you’ve recovered enough shock.
- **Dazed:** At 5+ Shock you are *Dazed* and take **+1 Pain Level**.
- **Stunned:** 10 Shock you are [[condition-stunned|stunned]].
- **Collapsed:** At 20 Shock, you [[condition-collapsed|collapse]].

## Harm
If a single attack inflicts more damage than your **Harm Threshold**, you take one point of **Harm**. Each point of **Harm** also adds **+1 Pain Level**.

## Trauma
If a single attack inflicts more damage than your **Trauma Threshold**, or you’re out of Harm slots, you take one point of Trauma. The character is [[condition-incapacitated|Incapacitated]] and inflicts **+2 Pain Level**, if they manage to remain functional.

## Fatal
If you’re out of Trauma Slots or a single attack inflicts equal or more damage than your **Fatal Threshold**, you will receive a fatal wound, and will die unless the damage is immediately treated. If survived the character is [[condition-collapsed|Collapsed]] and are at **+3 Pain Level** until recovered.

## Overkill
If you run out of Fatal slots or take a massive amount of damage at once, you die instantly, without any chance of survival. **You cannot recover from Overkill**.

# Pain Level
Sum the total *Pain Level* added by Conditions, such as **Dazed**, **Harm** or **Trauma**. Pain Level is added to the **Difficulty** of any *Body*, *Reflex* or *Mind* actions (but not Cyber actions). Pain can be mitigated with certain augments and medical substances.

Pain mitigation can be obtained through *Medicine*, *Drugs* and *Augments*.

> Example
> Cyber Joe has taken 2 Harm and 1 Trauma after engaging two combat mechs. His Pain Level is 3, meaning he now has **Difficulty** 3 complication added to *every* test utilizing *Body*, *Reflex* or *Mind*.

# Damage Mitigation

There are two methods for mitigating damage: **Armor Class** and **Soak**:

- **Armor Class** is determined by equipped armor and it directly reduces the **Damage Class** of an incoming attack.
- **Soak** can be added by augments or high Body attribute. It reduces the amount of damage taken by subtracting from the total damage rolled. If damage is affected by any multipliers, they are applied *after* subtracting *Soak*.

!!! Example
	 Marcus fires his heavy sniper rifle, inflicting DC 12, AP 4 Aimed Critical Hit at a guard in medium armor (AC 8) 800 meters away. Applying AC (modified by AP) the hit is left with DC 8 and Marcus rolls 2d8 for 10 damage. The target has 2 points of soak, so this reduces damage further to 8, but since Marcus landed a n Aimed Critical Hit, final damage is tripled, for total 24 damage. The Guard has Body D8, so this is enough to bypass Fatal threshold of 16, and the guard drops dead instantly.


## Natural Soak

- Body D10 → 1 soak
- Body D12 → 2 soak

# Recovering from Injury


| Condition | Recovery                                                                                                                             |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Shock     | [[combat-recovery-test\|Recovery Test]] during [[turns-upkeep\|Upkeep]] phase; full recovery at end of scene.                        |
| Harm      | Healed by Field Medic, Medical Items; **Regenerate** with augments during [[turns-upkeep\|Upkeep]] phase; Naturally 5 days per Harm. |
| Trauma    | **Regenerate** with augments during [[turns-upkeep\|Upkeep]]; 20 days to heal with standard medical treatment                        |
| Fatal     | Possible to **Regenerate** with augments during [[turns-upkeep\|Upkeep]]; 40 days to heal with standard medical treatment            |

