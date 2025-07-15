---
title: Resolving Damage
version: 1
status: new
subtitle: DC
---
## Damage Class
**Damage Class** (DC) is a classification system for a weapon’s power, indicated by a numeric value. Typically Damage class can range between -3 and 20, but the **Damage Class Table** will list DC ratings up to 50, for reference.

Subtract **Armor Class** (AC) from **Damage Class** (DC) to obtain **Damage**. *Damage* is either dice or a fixed value. You roll damage dice once per **Hit** obtained. DC of 7 or higher rolls always two dice, so both dice are rolled once per hit. DC of 0 or less on the other hand always inflicts fixed damage. For DC < 0 the damage is actually a fraction and you always round it down. But when taking multiple hits, sum the fractions to determine total damage dealt. This means that a large volume of low powered hits may still accumulate some damage.

| Damage Class | Damage Roll | Attack Example                                   |
| ------------ | ----------- | ------------------------------------------------ |
| -3*          | 1/8         | Scratch, minor animal bite                       |
| -2*          | 1/4         | Punch from a child                               |
| -1*          | 1/2         | Minor bruise, slap                               |
| 0            | 1           | Average punch, small animal bite                 |
| 1            | D2          | Heavy punch, small knife graze                   |
| 2            | D4          | Knife stab, improvised blunt hit                 |
| **3**        | **D6**      | **Small Caliber Pistol (e.g., .22 LR)**          |
| 4            | D8          | Small melee weapon, thrown blade, shotgun pellet |
| **5**        | **D10**     | **Large Caliber Pistol (e.g., 9mm, .45 ACP)**    |
| 6            | D12         | Heavy revolver (.44 Magnum)                      |
| 7            | D8+D6       | Heavy melee weapon strike                        |
| **8**        | **2D8**     | **Small Caliber Rifle (5.56 NATO)**              |
| 9            | D10+D8      | Close-range shotgun blast                        |
| 10           | 2D10        | Powerful hunting rifle, slug shotgun             |
| 11           | D12+D10     | High-powered combat rifle                        |
| 12           | 2D12        | Sniper rifle, very powerful hunting rifle        |
| 13           | D10+2D8     | Explosive shrapnel, frag grenade                 |
| 14           | 2D10+D8     | Anti-material rifle (lighter calibers)           |
| **15**       | **3D10**    | **Large Caliber Rifle (.50 BMG)**                |
| 16           | D12+2D10    | Light anti-vehicle weapons                       |
| 17           | 2D12+D10    | Heavy machine gun burst                          |
| 18           | 3D12        | Direct explosive shell impact                    |
| 19           | 3D10+D8     | Small rocket launcher hit                        |
| 20           | 4D10        | Heavy missile, artillery hit                     |
| 25           | 5D10        | Plasma Artillery                                 |
| 30           | 6D10        | High-yield explosives                            |
| 35           | 7D10        | Orbital Railgun Strike                           |
| 40           | 8D10        | Orbital Plasma Barrage                           |
| 50           | 5D20        | Tactical Nuke                                    |
*\* Only applicable when large number of hits are inflicted. Round fractions down.*

!!! Example
	A street punk pulls out a light SMG and fires on full auto at Cyber Joe, obtaining 4 Hits at DC 3. Cyber Joe is not dressed for combat and only has AC 2, reducing DC to 1, which means the Punk will now roll 4D2 damage: (1, 2, 1, 1) = 5 damage.

!!! Example
	Cyber Joe retaliates immediately, charging into close combat and delivering a powerful cybernetically augmented attack for 2 hits at DC 9. He rolls 2d10+2d8 damage for total (7, 10, 4, 2) 23 damage, completely obliterating the Punk.

## Optional Rule: Simplified damage
You can choose to resolve an attack using simplified damage rule:
- Each Hit inflicts damage equal to **Damage Class**
- DC 0 or less still inflicts noted fixed damage.

This rule can be used as an alternate when otherwise you’d have to roll damage for a large number of hits, usually simplifying high rate of fire attacks.

**Example**
> Cyber Joe is handling a large caliber vehicle-mounted minigun and scores **8 hits** against a light vehicle, inflicting (after armor) **DC 7** or `1D8+1D6` damage per hit. GM calculates **Simplified damage:** $DC*Hits = 7*8 = 56$ damage.