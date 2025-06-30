---
title: Damage Class
version: 1
status: new
subtitle: DC
---
**Damage Class** (DC) is a classification system for a weapon’s power, indicated by a numeric value in the range of -3 to 12. Any lower is insignificant and should be ignored while any higher should be represented with a **Damage Scale** variable.

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
| 30           | 6D10        | Tactical Nuke                                    |
| 35           | 7D10        | Orbital Railgun Strike                           |
| 40           | 8D10        | Orbital Plasma Barrage                           |
| 50           | 5D20        | Large-yield Nuke                                 |
*\* Only applicable when large number of hits are inflicted. Round fractions down.*

!!! Example
	A street punk pulls out a light SMG and fires on full auto at Cyber Joe, obtaining 4 Hits at DC 3. Cyber Joe is not dressed for combat and only has AC 2, reducing DC to 1, which means the Punk will now roll 4D2 damage: (1, 2, 1, 1) = 5 damage.

!!! Example
	Cyber Joe retaliates immediately, charging into close combat and delivering a powerful cybernetically augmented attack for 2 hits at DC 9. He rolls 2d10+2d8 damage for total (7, 10, 4, 2) 23 damage, completely obliterating the Punk.

## Damage Scale
The normal rules are designed for personal combat on a **human scale**. When you resolve combat between different types of entities, such as **Vehicles** or **Spacecrafts**, you’re essentially working on a different *scale*. Scale can be noted numerically, and unless otherwise stated, for human-scale is zero (0). For each point of scale difference you do the following:

Target is lower scale

- Armor Class of Lower scale target has their AC divided by 5.
- Damage to Lower scale target is multiplied by 5.

Target is higher scale
- Target AC is multiplied by 5


!!! example
	Cyber Joe and his team of 8 regulators are ambushed by a Radical X guerilla force supported by heavy artillery and 2 light combat mechs. Cyber Joe botches his tactics test and before they can make a move, they’re bombarded by artillery, followed by an intense rapid fire assault by the combat mechs. The Artillery is scale +1 attack with DC 3. AC of 5+ is required to negate any damage. Cyber Joe thankfully has AC 5, but regulators only have AC 3 so they do not get any benefits. Cyber Joe then gets D4 x 5 damage while each regulator gets D6 x 5 damage
	 	- Joe is lucky and only takes 5 damage (threshold 6/12/18), reduced by 2 soak to just 3 shock and no harm.
	 	- Regulators get (25, 10, 25, 5, 20, 15, 5, 15) damage (threshold 4 / 8 / 12)
	 5 Regulators are killed and 3 are wounded before the light mechs attack.

## Optional Rule: Simplified damage
You can choose to resolve an attack using simplified damage rule:
- Each Hit inflicts damage equal to **Damage Class**
- DC 0 or less still inflicts noted fixed damage.

This rule can be used as an alternate when otherwise you’d have to roll damage for a large number of hits, usually simplifying high rate of fire attacks.

**Example**
> Cyber Joe is handling a large caliber vehicle-mounted minigun and scores 8 hits against a light vehicle. The weapon (after armor) has **Damage Class 7** inflicting 1D8+1D6 damage per hit. You can choose to resolve the damage in two ways
> 1. **Manual roll:** Joe rolls total 16 dice: 8D8+8D6, takes a minute to sum up the dice for total of 67 damage.
> 2. **Simplified damage:** $DC*Hits = 7*8 = 56$ damage.