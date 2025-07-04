---
title: Weapons
version: 1
---

### Stats

#### Damage Class
How effective the weapon is. Determines base Damage Class on a Hit.

#### Range

Noted as `Optimal Range - Effective Range`. Or just Optimal Range if only one range is noted.

**Optimal Range** where weapon is best utilized. Take -1D penalty for each range increment more or less than indicated range.

**Effective Range** is the maximum suggested range for the weapon. Damage Class is reduced by 1 for each range increment further than Effective Range.

#### Recoil

How much the weapon kicks when fired. Recoil is measured with a Die from D6 to D12. You need to match recoil with your **Body** attribute to mitigate recoil, otherwise you take a -1D penalty on Attack Test for each step of difference. Having 2+ steps higher recoil also means you take a Wound each time you use the weapon.

Recoil can be reduced by one degree by having a support device for the weapon, such as a bipod. The support device typically adds **2 Bulk**. Properly mounted weapons always mitigate the recoil entirely.

#### Area

Area is used for explosives and such to determine how large area is affected when the weapon is used. Area of effect weapons can catch multiple enemies under the weapon's effect. Every target near the primary target will take damage, but they can take a **Reaction** to attempt a `Mobility or Tactics x Reflex` test to quickly hit the dirt or take cover. The difficulty for the test depends on the scale of the Area stat. On success you can mitigate a single Hit per Effect Point.


| Area     | Description                                                                                                  | Reaction Difficulty |
| -------- | ------------------------------------------------------------------------------------------------------------ | ------------------- |
| Small    | Radius is few meters at most and can impact up to three targets in close vicinity.                           | 1                   |
| Moderate | Easily a dozen meters or more. Usually up to 6 targets.                                                      | 2                   |
| Large    | Large areas covering several dozen meters from point of impact. Affects easily up to 20 targets in vicinity. | 3                   |
| Huge     | Covers a massive area of hundred meters or more. Affects every target in the area, as many as needed.        | 4                   |

!!! example
	Morales' team of insurgents is ambushed by an ARC-backed regulator force. They are under heavy fire and take cover behind nearby concrete pillars, but the ARC Bulwark giving fire support has an automatic grenade launcher and lands a burst of Frag grenades (Moderate Area) in their general direction. The Bulwark scores 3 hits, firing randomly in the area, so no one takes a direct hit, but everyone takes 3 Hits. Morales takes a Reaction to avoid the hits, choosing to roll with his Mobility skill of 4 against difficulty 2 (Moderate Area). Morales rolls 4D10, scoring 3, 5, 10, 4 → 3 success – Morales mitigates 2 hits, but takes a third one unmitigated.

#### Capacity
Capacity (CAP) determines the Resource Die used when making Ammo Checks. Higher Capacity means you will run out of ammo less likely and have to reload less frequently.

### Weapon Tags

Tags are used for additional rules regarding weapons.

| Tag                | Effect                                                                                                                                                                 |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Accurate           | Gain +1D on attack tests                                                                                                                                               |
| AOE                | Areaf of Effect; affects everything in an area (Small, Moderate, Large, Huge). Larger area means it's more difficult to avoid hits                                     |
| Bleeding           | When receiving any wounds, the target is also Bleeding.                                                                                                                |
| Burn               | When receiving any wounds, the target is also Burning.                                                                                                                 |
| Double Hits        | For each hit you inflict an additional Hit of the same type. Hit Limit is also doubled.                                                                                |
| EMP                | Electro-Magnetic Pulse. Disables electronics and machinery. Cybertech or Nanotech frames take **Double Damage**.                                                       |
| Explosive Ordnance | Uses explosives as ammunition. Pick suitable explosive from Explosives list and use its damage and tags.                                                               |
| Fast               | Hit Limit is increased to 3.                                                                                                                                           |
| Forceful           | High impact force causes target to be knocked back when hit. Test Toughness x Body against unmitigated Hit DC to avoid being knocked down.                             |
| Full Auto          | Upgrades Fast. Hit Limit 5, you can lay Suppressive Fire. Use 2 Ammo per attack. Gain +1D on attack if your Body rating exceeds Recoil.                                |
| Gas                | Deployed as a Gas. Ignores any armor that is not completely sealed or user is not wearing a gas mask, but is ineffective if deployed against gas mask or sealed armor. |
| Inaccurate         | Take -1D penalty on attack tests                                                                                                                                       |
| Irradiate          | Target suffers from radiation poisoning. -2D penalty.                                                                                                                  |
| Non-Lethal         | Inflict non-lethal damage: Half of mitigated damage is automatically soaked before making Soak Test.                                                                   |
| Non-Physical       | (Melee only) Cannot take Power effect to increase damage class.                                                                                                        |
| Slow               | Maximum Hit Limit is decreased to 1                                                                                                                                    |
| Stealthy           | Weapon is silenced and can be used in stealth operations without alarming more enemies                                                                                 |
| Stun               | Double the inflicted Shock                                                                                                                                             |
| Wasteful           | Spend additional Ammo on attack                                                                                                                                        |


### Reloads

Each Reload has a Bulk of 0.25, so you can carry 4 Reloads for 1 Bulk. Reloads are specific to weapons you carry, but you can abstract your personal reloads. When looting ammo from dead enemies, you might not find the correct ammo. Also when an ally is out of ammo, they need to have a matching weapon or your reloads won't be of use to them.

### Sidearms

`Range Combat x Reflex`

Sidearms are small **(Bulk 1)** and easily concealed under clothing. They are not suitable for main weapons in serious combat duty, but serve as easily concealable backup weapons. Sidearms can be used effectively one-handed, but a two-handed grip is more common, reducing their effective [[#Recoil]] by one degree.


| Weapon                  | DC  | AP  | RNG            | RCL      | CAP | Grade    | Tags                   |
| ----------------------- | --- | --- | -------------- | -------- | --- | -------- | ---------------------- |
| CHAOS Mk.2 (base model) | 3   | 1   | Short-Moderate | Low      | D8  | Exotic   | Full Auto              |
| Gauss Pistol            | 3   | 3   | Moderate-Long  | High     | D8  | Rare     |                        |
| Hand Cannon             | 4   | 1   | Short-Moderate | High     | D6  | Advanced | Slow                   |
| Heavy Pistol            | 3   | 1/2 | Short-Moderate | Moderate | D8  | Uncommon |                        |
| Laser Pistol            | 2   | 1   | Moderate       | Low      | D8  | Advanced | Accurate, Full Auto    |
| Light Pistol            | 2   | 1/2 | Short-Moderate | Low      | D8  | Common   | Fast                   |
| Micro SMG               | 2   | 1/2 | Short-Moderate | Low      | D6  | Uncommon | Full Auto, Wasteful    |
| Plasma Pistol           | 5   | 2   | Short-Moderate | Low      | D6  | Rare     | Inaccurate, Burn       |
| Shock Gun               | 4   | 1   | Short          | Low      | D8  | Uncommon | Slow, Stun, Non-Lethal |
| Sonic Blaster           | 3   | 2   | Short          | Low      | D8  | Advanced | Stun                   |



### Assault Weapons

`Ranged Combat x Reflex`

Assault Weapons are usually Medium sized weapons **(Bulk 2)** that require a *two-handed grip* for effective use. They are designed for moderate to long-ranged encounters. You can wield an assault Weapon in one hand, but this will increase [[#Recoil]] by one step.

| Weapon              | DC  | AP  | RNG            | RCL      | CAP | Grade    | Tags                        |
| ------------------- | --- | --- | -------------- | -------- | --- | -------- | --------------------------- |
| Assault Laser       | 3   | 1   | Long           | Low      | D8  | Rare     | Accurate, Full Auto         |
| Assault Rifle       | 3   | 1   | Moderate-Long  | Low      | D8  | Uncommon | Full Auto                   |
| Assault Shotgun     | 3   | 1/2 | Short-Moderate | Moderate | D8  | Advanced | Fast, Double Hits, Forceful |
| Battle Rifle        | 4   | 1   | Long-Extreme   | Moderate | D8  | Advanced | Fast                        |
| Gauss Needler       | 2   | 3   | Moderate-Long  | Moderate | D8  | Rare     | Full Auto, Double Hits      |
| Gauss Rifle         | 4   | 4   | Long-Extreme   | Extreme  | D8  | Rare     | Full Auto                   |
| Heavy Assault Rifle | 5   | 1   | Moderate-Long  | High     | D6  | Advanced | Fast                        |
| Heavy SMG           | 3   | 1   | Short-Moderate | Low      | D8  | Uncommon | Full Auto                   |
| Plasma Rifle        | 6   | 4   | Moderate-Long  | Low      | D8  | Rare     | Inaccurate, Burn, Fast      |
| Riot Shotgun        | 2   | 1/2 | Short-Moderate | Low      | D8  | Uncommon | Double Hits, Forceful       |
| Tactical SMG        | 2   | 1   | Short-Moderate | Low      | D8  | Uncommon | Stealthy, Full Auto         |



### Heavy Weapons

**Machineguns**: `Ranged Combat x Body`

**Launchers and Cannons**: `Ranged Combat x Reflex`

Heavy weapons fit the support role. They are big and clumsy **(Bulk 4)** and most of them are designed to be set up on a fixed position before firing, but can be used while detached. Heavy Weapons have reduced (-1) recoil when using from a fixed position. You need to spend an action to set up a heavy weapon properly.

| Weapon                | DC     | AP     | RNG            | RCL      | CAP | Grade    | Tags                                      |
| --------------------- | ------ | ------ | -------------- | -------- | --- | -------- | ----------------------------------------- |
| Auto Grenade Launcher | Varies | Varies | Moderate-Long  | High     | D8  | Rare     | Inaccurate, Full Auto, Explosive Ordnance |
| Auto Plasma           | 6      | 4      | Moderate-Long  | Moderate | D8  | Rare     | Inaccurate, Full Auto, Burn               |
| Auto Shotgun          | 3      | 1/2    | Short-Moderate | High     | D10 | Advanced | Full Auto, Double Hits, Forceful          |
| Chaingun              | 3      | 1      | Moderate-Long  | High     | D12 | Advanced | Full Auto, Double Hits, Wasteful          |
| Flamethrower          | 4      | 1/2    | Short-Moderate | Moderate | D8  | Advanced | Full Auto, Double Hits, Burn              |
| Gauss Machinegun      | 4      | 3      | Long-Extreme   | Extreme  | D10 | Rare     | Full Auto                                 |
| Grenade Launcher      | Varies | Varies | Long-Extreme   | Moderate | D6  | Advanced | Explosive Ordnance                        |
| Heavy Machinegun      | 5      | 1      | Long-Extreme   | Extreme  | D10 | Advanced | Full Auto                                 |
| Laser Gatling         | 3      | 1      | Long           | Low      | D10 | Rare     | Accurate, Full Auto, Double Hits          |
| Light Machinegun      | 3      | 1      | Long-Extreme   | High     | D10 | Uncommon | Full Auto                                 |
| Missile Launcher      | 8      | 2      | Long-Extreme   | Low      | 1   | Advanced | Accurate, AOE-M, Slow                     |
| Plasma Cannon         | 8      | 5      | Long-Extreme   | High     | D8  | Rare     | Inaccurate, AOE-S, Burn, Slow             |
| Pulse Cannon          | 5      | 5      | Long-Extreme   | Low      | D8  | Rare     | AOE-M, EMP, Slow                          |
| Sonic Disruptor       | 3      | 2      | Long           | Low      | D8  | Advanced | AOE-M, Stun                               |



### Precision Weapons

`Ranged Combat x Mind`

Precision weapons are ideal for extreme range support and assassinations. They are somewhat big and clumsy **(Bulk 3)** and tend to have low rate of fire, but can be used at extreme range. Precision Weapons are more effective when when deployed as a dedicated two-person team where one operates the weapon while the other acts as a spotter. A remote-operated drone can also be used as extra pair of eyes for an effective lone sniper. Precision Weapons require good focus to utilize effectively.

| Weapon              | DC  | AP  | RNG     | RCL      | CAP | Grade    | Tags                |
| ------------------- | --- | --- | ------- | -------- | --- | -------- | ------------------- |
| Anti-Material Rifle | 6   | 2   | Extreme | High     | D6  | Advanced | Slow                |
| Hunting Rifle       | 4   | 1   | Extreme | Moderate | D6  | Common   | Slow                |
| Laser Sniper        | 4   | 2   | Extreme | Low      | D8  | Rare     | Accurate, Full Auto |
| Light Railgun       | 5   | 5   | Extreme | Extreme  | D8  | Rare     | Slow                |
| Marksman Rifle      | 4   | 2   | Extreme | Moderate | D8  | Uncommon |                     |

### Explosives

**Throwing**: `Ranged Combat x Body`, Distance thrown requires spending Effect cost for throwing distance. If you fail to meet desired range effect cost, the throw will fall short.

| Range Thrown | Effect Cost |
| ------------ | ----------- |
| Close        | 0           |
| Short        | 1           |
| Moderate     | 2           |
| Long         | 4           |
| Extreme      | 8           |

**Demolitions**: `Tactics x Mind`

**Bomb disposal**: `Combat+Troubleshooting x Mind`

Explosive ordnance can be deployed as stand-alone explosive or launched using the appropriate platform.

#### URDO
`Bulk 1/4, Advanced Grade`

**Universal Remote-Detonated Ordnance** (URDO) is an advanced compact explosive delivery system that can be utilized like a grenade, but it is highly configurable and can be programmed to detonate by impact, timed fuse, remote detonation or by proximity or pressure trigger. As such it can serve as a landmine, demolitions charge or a hand grenade.

URDO use sophisticated nanites to enable different warhead configurations and they are completely safe until you **format** them to utilize a specific configuration. Formatting takes a **Short** duration, but once formatted the device is more sensitive and could be triggered to explode externally. A formatted URDO is also susceptible to remote hacking (Very Hard), so consider carefully before carrying around formatted URDO.
### Warheads
Warheads are used with various weapon delivery systems from missile launchers to grenades or improvised explosive devices.

| Name           | DC  | AP  | Grade    | Tags                       |
| -------------- | --- | --- | -------- | -------------------------- |
| Anti-Armor     | 4   | 3   | Advanced | AOE-S                      |
| Concussion     | 4   | 1   | Uncommon | Forceful, AOE-S            |
| Dirty Bomb     | 5   | 3   | Rare     | Irradiate, AOE-L           |
| EM Pulse       | 6   | 3   | Rare     | EMP, AOE-M                 |
| Frag           | 3   | 2   | Uncommon | AOE-M                      |
| High-Explosive | 5   | 1   | Uncommon | Forceful, AOE-S            |
| Incendiary     | 4   | 1   | Common   | Burn, AOE-S                |
| Nuclear        | 10  | 5   | N/A      | Burn, EMP, Forceful, AOE-H |
| Plasma         | 7   | 2   | Rare     | Burn, AOE-S                |
| Tear Gas       | 3   | 0   | Uncommon | AOE-M, Gas, Non-Lethal     |
| Lethal Gas     | 4   | 0   | Advanced | AOE-M, Gas                 |
| Smoke          | 1   | 0   | Common   | AOE-M, Gas, Non-Lethal     |
| Stun           | 3   | 1   | Uncommon | Stun, AOE-M                |


### Melee Weapons

`Close Combat x Body or Reflex`

Melee weapon can be anything from a blunt object to a master-crafted nano-edge katana blade. While ranged weapons are usually the preferred way to fight, a melee weapon can have the edge in close quarters. They are also common among lowlife street thugs, due to restrictions place in the ownership of personal firearms.

**Size** of a Melee weapon determines how heavy and bulky the weapon is. If you have less Body than the indicated minimum, you get -1D when handling the weapon for each step less. A melee weapon can be wielded two-handed to reduce the Body requirement by one degree.
 
| Size   | Min. Body | Bulk |
| :----- | :-------- | :--- |
| Small  | D6        | 1    |
| Medium | D8        | 2    |
| Large  | D10       | 3    |
| Huge   | D12       | 4    |

| Weapon                 | DC  | AP  | RNG   | SIZ    | Grade    | Tags                              |
| ---------------------- | --- | --- | ----- | ------ | -------- | --------------------------------- |
| Chainsaw               | 4   | 1   | Close | Large  | Uncommon | Double Hits, Inaccurate, Bleeding |
| Club/Baton             | 3   | 1/2 | Close | Medium | Common   | Forceful                          |
| Combat Knife           | 2   | 1   | Close | Small  | Uncommon | Accurate, Fast, Bleeding          |
| Fighting Stick         | 3   | 1/2 | Close | Small  | Uncommon | Accurate                          |
| Improvised, huge       | 5   | 1/2 | Close | Huge   | Common   | Inaccurate, Forceful, Slow        |
| Improvised, large      | 4   | 1/2 | Close | Large  | Common   | Inaccurate, Forceful              |
| Improvised, medium     | 3   | 1/2 | Close | Medium | Common   |                                   |
| Improvised, small      | 2   | 1/2 | Close | Small  | Common   | Fast                              |
| Mono Lash              | 4   | 5   | Short | Small  | Exotic   | Inaccurate, Reach                 |
| Nanoblade Katana       | 3   | 5   | Close | Medium | Rare     | Bleeding                          |
| Nanoblade Knife        | 2   | 5   | Close | Small  | Rare     | Fast                              |
| Shock Stick            | 3   | 1   | Close | Small  | Advanced | Non-Lethal, Stun                  |
| Sledgehammer           | 4   | 1/2 | Close | Large  | Common   | Forceful, Slow                    |
| Ultra-Blade Battle Axe | 5   | 2   | Close | Large  | Advanced | Inaccurate, Slow, Bleeding        |
| Ultra-Blade Katana     | 4   | 2   | Close | Medium | Advanced | Bleeding                          |
| Ultra-Blade Knife      | 3   | 2   | Close | Small  | Advanced | Accurate, Fast, Bleeding          |

### Custom Spec Weapons
Custom Spec weapons allow you to modify standard weapons with attachments or high quality components.

The rules of obtaining Custom Spec weapons are relatively simple: For each modification you increase the Rarity of the weapon by one, and can now apply one of the following modifications:

- Remove a negative Tag (e.g. Inaccurate)
- Add a suitable Weapon Tag (e.g. Fast)
- Add a custom spec Tag (table below)
- Upgrade a basic tag to a more advanced variant (e.g. Fast → Full Auto)

Custom Spec weapons are difficult to replace and you cannot expect your Faction to simply have them lying around, so losing your weapon or dying horribly explosive death means you will also lose your custom spec weapon until another can be provided. In addition your weapon might use unique ammunition and it might be difficult for you to find extra reloads on the field.

GM can veto any custom spec weapons if they do not make any sense, so try to make up a good explanation on how the modifications be made possible.

| Custom Spec Tag    | Effect                                                                                                                  |
|--------------------|-------------------------------------------------------------------------------------------------------------------------|
| AP Rounds          | Armor Piercing rounds. DC -1, AP +1.                                                                                    |
| HP Rounds          | Hollow-Point or anti-personnel rounds. DC +1, AP -1                                                                     |
| Large Caliber      | Increased caliber for more damage. DC +1, Recoil +1. Only if Recoil is High or lower.                                   |
| Huge Caliber       | Massively increased caliber. Upgrades Large Caliber. DC +2, Recoil +2, Capacity -1. Only if Recoil is Moderate or Lower |
| Increased Capacity | Increased Capacity. Capacity +1, Bulk +1.                                                                               |

### Super-Heavy Weapons
Super-Heavy weapons are too big for personal use and usually need to be fitted to a vehicle and fitted to a **Hardpoint** of suitable size, reflected by the Size stat of a vehicle weapon.

It is possible to utilize Super-Heavy weapons as personal weapons, but it is highly impractical – ath least without the correct [[recoil-compensator|Augment]] to mitigate this.

+ **Increased Bulk and Recoil:** Super-Heavy weapons are very heavy and have increased Recoil. The listed rating presumes the weapon is fitted on a suitable vehicle, drone or mech – not to be carried around by a humanoid sized creature.
	+ **Large** weapons have Bulk 6 and while similar in size to typical Heavy Weapons they tend to be more cumbersome and pack a bit more punch, resulting in +1 Recoil.
	- **Very Large** weapons have Bulk 8. Recoil +2.
	- **Massive** weapons have Bulk 12. Recoil +4.

| Weapon                      | DC  | Range    | Size     | Recoil   | Grade    | Tags                                                  |
| --------------------------- | --- | -------- | -------- | -------- | -------- | ----------------------------------------------------- |
| Auto Cannon                 | 6   | Long     | V. Large | High     | Advanced | Full Auto, High Capacity                              |
| Minigun                     | 4   | Moderate | Large    | High     | Advanced | Full Auto, Double Hits, Ultra Capacity                |
| Standard Missile (x1)       | 8   | Extreme  | Large    | Low      | Advanced | Accurate, Area (Moderate), Forceful                   |
| Auto Plasma Cannon          | 6   | Moderate | V. Large | Moderate | Rare     | Full Auto, Inaccurate                                 |
| Beam Laser Cannon           | 6   | Long     | V. Large | Low      | Rare     | Accurate, Full Auto, Soft Piercing                    |
| Gauss Vulcan                | 6   | Moderate | V. Large | Extreme  | Rare     | Full Auto, Double Hits, Hard Piercing, Ultra Capacity |
| Heavy Plasma Cannon         | 12  | Long     | Massive  | High     | Rare     | Slow, Inaccurate, Burn, Area (Moderate)               |
| Heavy Railgun               | 10  | Long     | V. Large | Extreme  | Rare     | Slow, Hard Piercing                                   |
| Medium Railgun              | 7   | Long     | Large    | High     | Rare     | Hard Piercing                                         |
| Plasma Cannon               | 10  | Moderate | V. Large | Moderate | Rare     | Inaccurate, Burn, Area (Small)                        |
| Plasma Missile (x1)         | 10  | Extreme  | Large    | Low      | Rare     | Accurate, Area (Large), Burn                          |
| Pulse Laser Cannon          | 8   | Long     | V. Large | Low      | Rare     | Accurate, Soft Piercing                               |
| Standard Missile Array (x6) | 8   | Extreme  | V. Large | Low      | Rare     | Accurate, Area (Moderate), Forceful                   |
| Fusion Missile (x1)         | 12  | Extreme  | Large    | Low      | Exotic   | Accurate, Area (Large), Burn, EMP, Forceful           |
| Fusion Missile Array (x6)   | 12  | Extreme  | V. Large | Low      | Exotic   | Accurate, Area (Large), Burn, EMP, Forceful           |
| Plasma Missile Array (x6)   | 10  | Extreme  | V. Large | Low      | Exotic   | Accurate, Area (Large), Burn                          |