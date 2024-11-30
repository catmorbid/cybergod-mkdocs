---
title: Gear
---
The Commonwealth is a resource-based economy where resources are distributed by need. There's a complicated Credit system in place which is linked to an individual's DNA-based biosignature that is used to track Credit usage, but most of the time individuals do not need to worry about spending credits and can simply take what they require.

That is not the case for anyone outside of the confines of Commonwealth, and in the streets and black markets there's a lively barter economy and a number of Cryptographic currencies in circulation.

Player characters can freely choose their equipment based on their equipment's Grade. In addition the players can utilize **Team Assets** which are shared among the team. Personal Gear consists mostly of weapons, armor and perhaps some tools or Gadgets.

## Grade
Availability is measured with a **Grade**:

- **Basic** — Basic commodities available to every citizen of Commonwealth. Purchase of large quantities may be flagged and require explanation and price could be adjusted accordingly if signs of abuse are noted.
- **Common** — Available to all citizens of Commonwealth with reasonable cause. Includes many harmful substances and weapons classified for self defense.
- **Uncommon** — Not available to citizens without proper clearance and a license. E.g. professional tools and most firearms. Possession without clearance may result in minor sanctions.
- **Advanced** — Restricted availability. Requires high level clearance. Possession without clearance comes with heavy sanctions.
- **Rare** — Very restricted availability. Requires extremely high level clearance. Possession and trafficking is a major felony and may result in extreme sanctions.
- **Exotic** — Technology that is not available even with highest connections. Restricted to a specific faction or organization, includes prototype or highly restricted technology.

## Bulk

Bulk determines general bulkiness of items, incorporating both mass and size. A character's **Max Bulk** rating is equal to the their Body Die size, i.e. for D6 Body Max Bulk is 6 and for D12 Body it is 12. This limit determines how much stuff you can carry around without being penalized. The stuff includes both Armor and Weapons, plus any extra equipment carried and Reloads.

## Resources

Resources represent consumable assets such as various wealth, supplies or ammo but also more abstract resources like stress and influence.

When you consume resources, you mark down the consumption and then proceed to make a [[#Resource Checks|Resource Check]] to see if you can manage the consumption. Different resources work in slightly different ways, but the amount of resources is always indicated by a **Resource Die**, which is either D6, D8, D10 or D12.

### Resource Check

A Resource Check is used to measure consumption of various resources such as **Ammo** or personal **Assets**.

Resource Check is rolled with Resource Dice which are D6, D8, D10 or D12. When you consume resources, you must make a Resource Check. The number of dice is 1 + previous level of consumption. E.g. If you you currently have 4 points of ammo tracked, spending another ammo means you now roll 5 dice for Resource Check.

If any dice show 1-2 then the check fails. Consequences of failure depend on the measured resource:

- **Ammo**: You run out of ammo and must spend a Reload. but usage is cleared.
- **Stress**: you suffer from a mental breakdown, but stress track remains unchanged.
- **Assets** (RP, QC or Influence): You must reduce the usage dice by one step or forfeit the transaction.

If you fail the check, then clear the tracked usage track and start tracking again from zero, if any resources remain.

### General Resources
General Resources are various commodities you can spend to obtain other commodities, favors or privileges. They include Resource Points, Quantum Crypto Currency and Influence. You can write down other resources as needed.

**Resource Points (RP)** is a measure of Commonwealth standard currency, a fully digitalized, personal unit of consumption. Commonwealth is a resource based economy so consumption is rather based on resource availability and cost of production than arbitrary monetary value. Overconsumption may also increase the cost as Resource Points are tracked personally.

**Quantum Crypto Currency (QC)** is widely used throughout freeports and in black markets within commonwealth. It is often distributed in anonymized encrypted polyhedral storage devices small enough to fit in a pouch or pocket, and in that form can be used as the equivalent to “cash” or physical money. The shape of the QC storage devices has given it the nickname “qubes” and “dice”.

**Influence** is a measure of social wealth, respect and renown. It can be used to call in favors and influence outcomes of certain situations.

### Ammo

When you use a weapon in combat, you need to track its ammo usage. Mark down how much ammo you used (typically just one) and make a [[#Resource Check]] after attack using the weapon’s [[#Capacity]] as the Resource Die. On failure, you are out of ammo and must spend a Reload.
## Weapons

### Stats

#### Damage Class
How effective the weapon is. Determines base Damage Class on a Hit.

#### Range

Noted as `Optimal Range - Effective Range`. Or just Optimal Range if only one range is noted.

**Optimal Range** where weapon is best utilized. Take -1D penalty for each range increment more or less than indicated range.

**Effective Range** is the maximum suggested range for the weapon. Damage Class is reduced by 1 for each range increment further than Effective Range.

#### Recoil

How much the weapon kicks when fired. You need to match recoil with high enough **Body** attribute to mitigate recoil, otherwise you take a -1D penalty to attack for each step of difference. Having 2+ steps higher recoil also means you take Bruise or greater wound each time you use the weapon.

- **Low**: Body D6 to mitigate recoil
- **Moderate**: Body D8 to mitigate recoil
- **High**: Body D10 to mitigate recoil
- **Extreme**: Body D12 to mitigate recoil

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
### Tags

Tags are used for additional rules regarding weapons.


| Tag                | Effect                                                                                                                                                                 |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Accurate           | Gain +1D on attack tests                                                                                                                                               |
| Area               | Affects everything in an area (Small, Moderate, Large, Huge). Larger area means it's more difficult to avoid hits (Reflex Save, see Gear/Weapons/Stats/Area)           |
| Burn               | Target takes 2 Stress and will Burn next round for DC - 1 damage. Damage will persist until fire can be exintinguished.                                                |
| Double Hits        | For each hit you gain two hits.                                                                                                                                        |
| EMP                | Electro-Magnetic Pulse. Disables electronics and machinery. +1 DC vs. Cybertech frames, +2 DC vs. drones, no effect on organics.                                       |
| Explosive Ordnance | Uses explosives as ammunition. Pick suitable explosive from Explosives list and use its damage and tags.                                                               |
| Fast               | Maximum Hit Limit is increased to 3.                                                                                                                                   |
| Forceful           | High impact force causes target to be knocked back when hit. They must make a Force x Body test against weapon DC or be knocked down.                                  |
| Full Auto          | Upgrades Fast. No limit on how many Hits you can take and you can lay Suppressive Fire. Consumes 3 Ammo. Gain +1D on attack if your Body rating exceeds Recoil.        |
| Gas                | Deployed as a Gas. Ignores any armor that is not completely sealed or user is not wearing a gas mask, but is ineffective if deployed against gas mask or sealed armor. |
| Hard Piercing      | Upgrades Soft Piercing. Ignores Soft and Hard mitigation, but Ultra mitigation is unaffected.                                                                          |
| High Capacity      | Upgrades Moderate Capacity (default: D8 Usage Die). Ammo Usage die is D10                                                                                              |
| Inaccurate         | Take -1D penalty on attack tests                                                                                                                                       |
| Irradiate          | Target suffers from radiation poisoning. -2D penalty.                                                                                                                  |
| Low Capacity       | Downgrades Low Capcity. Ammo Usage Die is D6                                                                                                                           |
| Non-Lethal         | Lethal Wounds become non-lethal: target will be incapacitated, but not dying. Overkill counts as Lethal wound, but does not outright kill.                             |
| Stealthy           | Weapon is silenced and can be used in stealth operations without alarming more enemies                                                                                 |
| Slow               | Maximum Hit Limit is decreased to 1                                                                                                                                    |
| Soft Piercing      | Ignores Soft mitigation, but Hard and Ultra mitigation are unaffected                                                                                                  |
| Stun               | Affected target is disoriented and will lose their next action.                                                                                                        |
| Ultra Capacity     | Upgrades High Capacity. Ammo Usage Die is D12.                                                                                                                         |
| Non-Physical       | Melee weapon cannot take Power effect to increase damage class.                                                                                                        |

### Reloads

Each Reload has a Bulk of 0.25, so you can carry 4 Reloads for 1 Bulk. Reloads are specific to weapons you carry, but you can abstract your personal reloads. When looting ammo from dead enemies, you might not find the correct ammo. Also when an ally is out of ammo, they need to have a matching weapon or your reloads won't be of use to them.

### Sidearms

`Range Combat x Reflex`

Sidearms are small **(Bulk 1)** and easily concealed under clothing. They are not suitable for main weapons in serious combat duty, but serve as easily concealable backup weapons. Sidearms can be used effectively one-handed, but a two-handed grip is more common, reducing their effective [[#Recoil]] by one degree.


| Weapon                  | DC  | Range          | Recoil   | Grade    | Tags                   |
| ----------------------- | --- | -------------- | -------- | -------- | ---------------------- |
| Light Pistol            | 2   | Short-Moderate | Low      | Common   | Fast                   |
| Shock Gun               | 4   | Short          | Low      | Uncommon | Slow, Stun, Non-Lethal |
| Heavy Pistol            | 3   | Short-Moderate | Moderate | Uncommon |                        |
| Micro SMG               | 2   | Short-Moderate | Low      | Uncommon | Full Auto              |
| Hand Cannon             | 4   | Short-Moderate | High     | Advanced | Slow, Low Capacity     |
| Laser Pistol            | 2   | Moderate       | Low      | Advanced | Accurate, Full Auto    |
| Sonic Blaster           | 3   | Short          | Low      | Advanced | Stun, Soft Piercing    |
| Plasma Pistol           | 5   | Short-Moderate | Low      | Rare     | Inaccurate             |
| Gauss Pistol            | 3   | Moderate-Long  | High     | Rare     | Hard Piercing          |
| CHAOS Mk.2 (base model) | 3   | Short-Moderate | Low      | Exotic   | Full Auto              |


### Assault Weapons

`Ranged Combat x Reflex`

Assault Weapons are usually Medium sized weapons **(Bulk 2)** that require a *two-handed grip* for effective use. They are designed for moderate to long-ranged encounters. You can wield an assault Weapon in one hand, but this will increase [[#Recoil]] by one step.


| Weapon              | DC  | Range          | Recoil   | Grade    | Tags                                  |
| ------------------- | --- | -------------- | -------- | -------- | ------------------------------------- |
| Assault Rifle       | 3   | Moderate-Long  | Low      | Uncommon | Full Auto                             |
| Heavy SMG           | 3   | Short-Moderate | Low      | Uncommon | Full Auto                             |
| Riot Shotgun        | 2   | Short-Moderate | Low      | Uncommon | Double Hits, Forceful                 |
| Tactical SMG        | 2   | Short-Moderate | Low      | Uncommon | Stealthy, Full Auto                   |
| Assault Shotgun     | 3   | Short-Moderate | Moderate | Advanced | Fast, Double Hits, Forceful           |
| Battle Rifle        | 4   | Long-Extreme   | Moderate | Advanced | Fast                                  |
| Heavy Assault Rifle | 5   | Moderate-Long  | High     | Advanced | Fast, Low Capacity                    |
| Assault Laser       | 3   | Long           | Low      | Rare     | Accurate, Full Auto                   |
| Gauss Needler       | 2   | Moderate-Long  | Moderate | Rare     | Full Auto, Double Hits, Hard Piercing |
| Gauss Rifle         | 4   | Long-Extreme   | Extreme  | Rare     | Full Auto, Hard Piercing              |
| Plasma Rifle        | 6   | Moderate-Long  | Low      | Rare     | Inaccurate, Burn                      |


### Heavy Weapons

**Machineguns**: `Ranged Combat x Body`

**Launchers and Cannons**: `Ranged Combat x Reflex`

Heavy weapons fit the support role. They are big and clumsy **(Bulk 4)** and most of them are designed to be set up on a fixed position before firing, but can be used while detached. Heavy Weapons have reduced (-1) recoil when using from a fixed position. You need to spend an action to set up a heavy weapon properly.

| Weapon                | DC     | Range          | Recoil   | Grade    | Tags                                            |
| --------------------- | ------ | -------------- | -------- | -------- | ----------------------------------------------- |
| Light Machinegun      | 3      | Long-Extreme   | High     | Uncommon | Full Auto, High Capacity                        |
| Chaingun              | 3      | Moderate-Long  | High     | Advanced | Full Auto, Double Hits, Ultra Capacity          |
| Flamethrower          | 4      | Short-Moderate | Moderate | Advanced | Full Auto, Double Hit, Burn                     |
| Grenade Launcher      | Varies | Long-Extreme   | Moderate | Advanced | Explosive Ordnance                              |
| Heavy Machinegun      | 5      | Long-Extreme   | Extreme  | Advanced | Full Auto, High Capacity                        |
| Missile Launcher      | 8      | Long-Extreme   | Low      | Advanced | Accurate, Area (Moderate), Low Capacity, Slow   |
| Sonic Disruptor       | 3      | Long           | Low      | Advanced | Area (Moderate), Stun, Soft Piercing            |
| Auto Shotgun          | 3      | Short-Moderate | High     | Advanced | Full Auto, Double Hits, High Capacity, Forceful |
| Auto Grenade Launcher | Varies | Moderate-Long  | High     | Rare     | Inaccurate, Full Auto, Explosive Ordnance       |
| Auto Plasma           | 6      | Moderate-Long  | Moderate | Rare     | Inaccurate, Full Auto                           |
| Gauss Machinegun      | 4      | Long-Extreme   | Extreme  | Rare     | Full Auto, High Capacity, Hard Piercing         |
| Laser Gatling         | 3      | Long           | Low      | Rare     | Accurate, Full Auto, Double Hits, High Capacity |
| Plasma Cannon         | 8      | Long-Extreme   | High     | Rare     | Inaccurate, Area (Small), Burn, Slow            |
| Pulse Cannon          | 5      | Long-Extreme   | Low      | Rare     | Area (Moderate), EMP, Hard Piercing, Slow       |


### Precision Weapons

`Ranged Combat x Mind`

Precision weapons are ideal for extreme range support and assassinations. They are somewhat big and clumsy **(Bulk 3)** and tend to have low rate of fire, but can be used at extreme range. Precision Weapons are more effective when when deployed as a dedicated two-person team where one operates the weapon while the other acts as a spotter. A remote-operated drone can also be used as extra pair of eyes for an effective lone sniper. Precision Weapons require good focus to utilize effectively.

| Weapon              | DC | Range   | Recoil   | Grade    | Tags                               |
|---------------------|----|---------|----------|----------|------------------------------------|
| Hunting Rifle       | 4  | Extreme | Moderate | Common   | Slow, Low Capacity                 |
| Marksman Rifle      | 4  | Extreme | Moderate | Uncommon |                                    |
| Anti-Material Rifle | 6  | Extreme | High     | Advanced | Slow, Low Capacity                 |
| Light Railgun       | 5  | Extreme | Extreme  | Rare     | Slow, Hard Piercing                |
| Laser Sniper        | 4  | Extreme | Low      | Rare     | Accurate, Full Auto, Soft Piercing |



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

| Explosive      | DC           | Area     | Grade    | Tags                |
| :------------- | :----------- | :------- | :------- | :------------------ |
| Frag           | 4            | Moderate | Uncommon |                     |
| High-Explosive | 5            | Small    | Uncommon | Forceful            |
| Incendiary     | 3            | Small    | Common   | Burn                |
| Anti-Armor     | 4            | Small    | Advanced | Hard Piercing       |
| Concussion     | 4            | Small    | Uncommon | Forceful            |
| Stun           | 2            | Moderate | Uncommon | Stun                |
| Plasma         | 8            | Small    | Rare     | Burn                |
| EM Pulse       | 6 (machines) | Moderate | Rare     | EMP                 |
| Nuclear        | 10           | Large    | N/A      | Burn, EMP, Forceful |
| Dirty Bomb     | 5            | Moderate | Rare     | Irradiate           |

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

| Melee Weapon       | DC | Range | Size   | Grade    | Tags                       |
|--------------------|----|-------|--------|----------|----------------------------|
| Knife              | 2  | Close | Small  | Common   | Accurate, Fast             |
| Club/Baton         | 3  | Close | Medium | Common   |                            |
| Sledgehammer       | 4  | Close | Large  | Common   | Forceful, Slow             |
| Fighting Stick     | 3  | Close | Small  | Uncommon | Accurate                   |
| Chainsaw           | 4  | Close | Large  | Uncommon | Double Hits, Inaccurate    |
| Shock Stick        | 3  | Close | Small  | Advanced | Non-Lethal, Stun           |
| Nanoblade Katana   | 3  | Close | Medium | Rare     | Hard Piercing              |
| Nanoblade Knife    | 2  | Close | Small  | Rare     | Hard Piercing, Fast        |
| Mono Whip          | 2  | Short | Small  | Rare     | Inaccurate, Hard Piercing  |
| Improvised, small  | 2  | Close | Small  | Common   | Fast                       |
| Improvised, medium | 3  | Close | Medium | Common   |                            |
| Improvised, large  | 4  | Close | Large  | Common   | Inaccurate, Forceful       |
| Improvised, huge   | 5  | Close | Huge   | Common   | Inaccurate, Forceful, Slow |


### Custom Spec Weapons
Custom Spec weapons allow you to modify standard weapons with attachments or high quality components.

The rules of obtaining Custom Spec weapons are relatively simple: For each modification you increase the Rarity of the weapon by one, and can now apply one of the following modifications:

- Remove a negative Tag (e.g. Inaccurate)
- Add any custom-spec compliant Tag (e.g. Soft Piercing)
- Upgrade a basic tag to a more advanced variant (e.g. Soft Piercing -> Hard Piercing)

Custom Spec weapons are difficult to replace and you cannot expect your Faction to simply have them lying around, so losing your weapon or dying horribly explosive death means you will also lose your custom spec weapon. In addition your weapon might use unique ammunition and it might be difficult for you to find extra reloads on the field.

GM can veto any custom spec weapons if they do not make any sense, so try to make up a good explanation on how the modifications be made possible.

### Vehicle Weapons
Vehicle weapons are too big for personal use and usually need to be fitted to a vehicle and must be fitted to a **Hardpoint** of suitable size, reflected by the Size stat of a vehicle weapon.

**Large** weapons have Bulk 4 and they are equivalent to personal heavy weapons.

**Very Large** weapons have Bulk 8. It is possible to pick up and carry one with a high Body, but Recoil is increased by 2 steps.

**Massive** weapons have Bulk 12. They can be removed and carried around with high Body, but are practically impossible to use as personal weapons.

| Weapon                      | DC | Range    | Size     | Recoil   | Grade    | Tags                                                  |
|-----------------------------|----|----------|----------|----------|----------|-------------------------------------------------------|
| Auto Cannon                 | 6  | Long     | V. Large | High     | Advanced | Full Auto, High Capacity                              |
| Minigun                     | 4  | Moderate | V. Large | High     | Advanced | Full Auto, Double Hits, Ultra Capacity                |
| Standard Missile (x1)       | 8  | Extreme  | Large    | Low      | Advanced | Accurate, Area (Moderate), Forceful                   |
| Auto Plasma Cannon          | 6  | Moderate | V. Large | Moderate | Rare     | Full Auto, Inaccurate                                 |
| Beam Laser Cannon           | 6  | Long     | V. Large | Low      | Rare     | Accurate, Full Auto, Soft Piercing                    |
| Gauss Vulcan                | 6  | Moderate | V. Large | Extreme  | Rare     | Full Auto, Double Hits, Hard Piercing, Ultra Capacity |
| Heavy Plasma Cannon         | 12 | Long     | Massive  | High     | Rare     | Slow, Inaccurate, Burn, Area (Moderate)               |
| Heavy Railgun               | 10 | Long     | Massive  | Extreme  | Rare     | Slow, Hard Piercing                                   |
| Medium Railgun              | 7  | Long     | V. Large | High     | Rare     | Hard Piercing                                         |
| Plasma Cannon               | 10 | Moderate | V. Large | Moderate | Rare     | Inaccurate, Burn, Area (Small)                        |
| Plasma Missile (x1)         | 10 | Extreme  | Large    | Low      | Rare     | Accurate, Area (Large), Burn                          |
| Pulse Laser Cannon          | 8  | Long     | V. Large | Low      | Rare     | Accurate, Soft Piercing                               |
| Standard Missile Array (x6) | 8  | Extreme  | V. Large | Low      | Rare     | Accurate, Area (Moderate), Forceful                   |
| Fusion Missile (x1)         | 12 | Extreme  | Large    | Low      | Exotic   | Accurate, Area (Large), Burn, EMP, Forceful           |
| Fusion Missile Array (x6)   | 12 | Extreme  | V. Large | Low      | Exotic   | Accurate, Area (Large), Burn, EMP, Forceful           |
| Plasma Missile Array (x6)   | 10 | Extreme  | V. Large | Low      | Exotic   | Accurate, Area (Large), Burn                          |


## Personal Armor

| Armor                   | Soft | Hard | Ultra | Bulk | Grade    | Powered             |
| ----------------------- | ---- | ---- | ----- | ---- | -------- | ------------------- |
| Ballistic Weave         | 4    |      |       | 0    | Common   |                     |
| Ballistic Plates        | 0    | 2    |       | 1    | Common   |                     |
| Nano Weave              | 2    | 2    |       | 0    | Uncommon |                     |
| Security Armor          | 4    | 2    |       | 1    | Uncommon |                     |
| Combat Armor            | 4    | 4    |       | 2    | Advanced |                     |
| Hard Shell              | 1    | 3    | 3     | 4    | Advanced |                     |
| Industrial Exosuit      | 3    | 3    |       | 2    | Advanced | Body D12, Reflex D6 |
| Combat Exosuit          | 5    | 5    | 1     | 1    | Rare     | Body D10, Reflex D8 |
| Reflex Armor            | 2    | 4    | 1     | 0    | Rare     | Body D8, Reflex D10 |
| Power Suit              | 6    | 4    | 4     | 2    | Exotic   | Body D12, Reflex D6 |
| Cybernetic armor 1      | 4    | 2    | 1     | 0    | -        |                     |
| Cybernetic armor 2      | 4    | 4    | 2     | 2    | -        |                     |
| Cybernetic armor 3      | 5    | 5    | 3     | 4    | -        |                     |
| Vehicle Plating, Light  | 2    | 2    |       | 1    | Common   |                     |
| Vehicle Plating, Medium | 4    | 4    |       | 2    | Uncommon |                     |
| Vehicle Plating, Heavy  | 6    | 4    | 2     | 4    | Advanced |                     |
| Vehicle Plating, Ultra  | 6    | 6    | 4     | 8    | Rare     |                     |

### Ballistic Weave
Ballistic Weave can be manufactured into common clothing. It protects the user from small arms and knives, but not much more.
### Nano Weave
Nano Weave uses advanced nanotech materials to create a lightweight protective mesh in clothing and can be fabricated into almost anything. Nano Weave is stain-proof and self-repairing. Restore all Soft Mitigation and 1 point of Hard mitigation in Moderate duration when not subjected to more damage.
### Ballistic Plates
A thin layer of poly-ceramic armor that can be inserted to clothing and combat vests. It won't withstand sustained fire, but may be a lifesaver when nothing better is available.
### Security Armor
A lightweight suit of body armor with layers of ballistic weave and poly-ceramic plating. The body armor is often complemented with arm and leg guards and a lightweight helmet with an info-visor covering the eyes. Standard issue for regulator units and corporate security throughout the world.
### Combat Armor
Combat armor is a bulky suit of polymer-ceramic armor intended for military operations. Standard issue comes with a body armor and separate pieces for arms and legs, as well as a heavy-duty helmet with full face protection and a Smart visor.
### Hard Shell
A seamless full-body suit built for heavy encounters. Toughest available in un-powered suits. It adds a lot of bulk, but offers excellent protective capabilities and can withstand a few shots from even heaviest weapons.
### Powered Armor
Powered armor are wearable exosuits designed for human soldiers to improve the wearer's strength, stamina and coordination with assisted robotic limbs. The technology was refined in the the pre-collapse era and has seen only minor improvements since then. The technology is expensive, hard to maintain and has limited time of operation due necessity of compact well-protected power cells: with full charge the suit will last roughly 16 hours of active use, with the exception of the **Industrial Exosuit**, which is much bulkier, but also has bigger power cells, upgrading active use to 48 hours.

!!! info Power Armor attributes
	Always use the powered armor's attributes over the Frame's normal attribute, even if the armor has worse attributes.

!!! info Power Source Weak Spot
	Power Armor’s most significant weakness is its power source. If you have a chance, you can aim at the power source by taking the **Weak Spot** effect, but instead of inflicting extra damage, the target must make a D6 save with difficulty equal to damage inflicted. If they fail the save, the power source will shutdown. It won’t cause a fancy explosion or anything, but the sorry individual inside is stuck inside a heavy, immobile metal husk.

### Vehicle Plating
Vehicles and Drones can fitted with armor plating. This kind of plating is not suitable for humanoid Frames though.

 
## Equipment
 
You can also carry various tools and other useful equipment. Your faction can probably provide you with facilities for anything you need, but sometimes it's handy to have some things with you on the field.

| Equipment                | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Bulk | Grade    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | -------- |
| Disposable Hack Tool     | A single use tool with Cyber rating of D8 for hacking devices as long as it can interact with physically.                                                                                                                                                                                                                                                                                                                                                                      | 0,25 | Advanced |
| Cyberweb Link            | A portable Cyberweb Link that extends the Reach of Cyberweb to areas that are not normally covered.                                                                                                                                                                                                                                                                                                                                                                            | 1    | Common   |
| Nutri-Pack               | A military grade food ration with high nutrition value. Restores 1 Energy when consumed.                                                                                                                                                                                                                                                                                                                                                                                       | 0,25 | Uncommon |
| Dermal Communicator      | A super thin dermal implant that acts as a communications device.                                                                                                                                                                                                                                                                                                                                                                                                              | 0    | Common   |
| Q-Com Stick              | A tiny but powerful computer that fits on a small stick. Holographic interface. Provides D6 Cyber rating.                                                                                                                                                                                                                                                                                                                                                                      | 0,25 | Common   |
| Holorecorder             | A small device that can create a 360 degree holographic recording.                                                                                                                                                                                                                                                                                                                                                                                                             | 1    | Common   |
| Holomesh Unit            | A tiny device for projecting holographic recordings. Several devices can be combined together to create a holographic mesh, a large area that can project holograms.                                                                                                                                                                                                                                                                                                           | 0,25 | Common   |
| Molecular Mesh Projector | Molecular Projector is an advanced version of a Holographics projector that can rearrange molecules, creating a realistic scene. It is significantly larger than a typical holomesh unit and requires much more energy to operate.                                                                                                                                                                                                                                             | 1    | Advanced |
| Rebreather               | Sophisticated system for detecting accurately all molecules in surrounding medium and filtering them conditionally. Different options extend usability to beyond just breathing air.                                                                                                                                                                                                                                                                                           | 1    | Uncommon |
| Portable Cyberweb Hub    | A Cyberweb Hub creates a stable Quantum Communications Connection to the Cyberweb, a mass of interconnected devices, and automatically acts as an Access Point to nearby devices for remotely accessing Cyberweb. Provides a direct neural interface for fast access to Cyberweb. Cyberweb Hubs are not normally portable and they require significant energy to operate, thus this portable Hub can only function for 24 hours, unless connected to an external power source. | 4    | Advanced |
| Field CSI Kit            | Portable equipment for proper handling of evidence and tools for quick analysis on the field.                                                                                                                                                                                                                                                                                                                                                                                  | 2    | Uncommon |
| Field Medical Kit        | Can be used to administer first aid to organics. Includes anti-bleeding spray, antiseptic bandages, general disinfectant, basic surgery tools and an array of basic meds.                                                                                                                                                                                                                                                                                                      | 2    | Uncommon |
| Field Surveillance Kit   | Kit with various advanced surveillance equipment for remote surveillance, signal manipulation etc.                                                                                                                                                                                                                                                                                                                                                                             | 2    | Uncommon |
| Field Repair Kit         | Set of sophisticated devices and tools for troubleshooting mechanical or electrical issues and performing crude field repairs.                                                                                                                                                                                                                                                                                                                                                 | 2    | Uncommon |
| Portable Replicator      | A suitcase model of a Universal Replicator with enough matter blocks to get you started. Can be used to craft almost anything provided you have the designs for it and enough matter blocks.                                                                                                                                                                                                                                                                                   | 4    | Uncommon |
| Ninja Tools              | A set of professional ninja tools help you access places that are otherwise inaccessible. Tools may include wall scaling equipment, grappling hook launcher, paraglider, rappelling equipment etc. As a rule of thumb, each set of Ninja Tools is usable for only one type of Action, although you do not need to decide which action. Commonly the equipment is also discarded immediately after being used. Receive +1D to +2D advantage on related tests, if applicable.    | 2    | Uncommon |

## Drugs

Many kinds of drugs exists. Some are legal and approved for official use, while others are strictly illegal. The black market however has lots of drugs in circulation.

### Safety Check
You must make a [[persona#Safety Check|Safety Check]] whenever you use any drugs using the indicated Safety Die. Over-use may lead to [[persona#Corruption|Corruption]] and loss of humanity. Safety Checks can be re-rolled by spending a point of [[persona#Resolve|Resolve]], which might be a good idea to avoid taking corruption.

### Legal drugs

| Name                | Description                                                                                                                                                                                                                                                 | Grade    | Safety |
| :------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :----- |
| Nano Stim           | An injection of fast acting nano agents programmed to repair physical damage. Heals all Minor Wounds in Short Duration.                                                                                                                                     | Advanced | D10    |
| Cognitive Enhancers | Gain a free re-roll on any Mind Test                                                                                                                                                                                                                        | Advanced | D10    |
| Reflex Enhancers    | Gain a free re-roll on any Reflex Test                                                                                                                                                                                                                      | Advanced | D10    |
| Painkillers         | Negate 1D worth wound penalties                                                                                                                                                                                                                             | Common   | D12    |
| Pscyhers            | Gain temporary telepathic ability. Can read the thoughts and emotions of nearby people. Experience is enhanced with physical contact and with proximity to other Psycher users. Very popular recreational drug, and also useful for interrogation purposes. | Rare     | D8     |
| Purge               | Force body to flush any toxins and foreign chemical and biological agents from within their system, effectively neutralizing their effects. Cancel ANY and ALL drug and poison effects. Causes painful vomiting for 1 round per effect flushed.             | Uncommon | D12    |
| Sedatives           | Powerful sedatives with rapid rate of effect. Reduce accumulated Stress by one.                                                                                                                                                                             | Common   | D12    |
| Somatic Enhancers   | Gain a free re-roll in any Body Test                                                                                                                                                                                                                        | Advanced | D10    |

### Black Market Drugs

| Equipment      | Description                                                                                                                                                                                                                                                                                                                                          | Grade    | Safety |
| :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | :----- |
| Black Psychers | A Black Market version of Psychers that allow individuals to share memories and experiences, even diving to the other's subconscious. Can cause neural overload and permanent brain damage. Highly addictive.                                                                                                                                        | Rare     | D6     |
| Easy [Skill]   | Easies are retro-virus based neural duplicators that inject the skill of another person to the drug's user. Easies often give a combined Aptitude + Skill rating between 2 and 5, depending on the quality of the drug. Double the cost for each quality level. While under influence, the character's natural skill rating is subsided by the drug. | Uncommon | D6     |
| Flashback      | Injects vivid memories stored in nano-chemical agent. Highly addictive. Can be a significant stress reliever if applied properly.                                                                                                                                                                                                                    | Common   | D6     |
| Rush           | A massive surge of adrenaline. Gain an extra Action.                                                                                                                                                                                                                                                                                                 | Advanced | D6     |
| Slow Mo        | Slows down the perception of time. Gain a free re-roll on any Reaction test and gain +2 to Initiative.                                                                                                                                                                                                                                               | Advanced | D6     |
| Spark          | Modamphetamine derivative that removes all natural fatigue and replenishes energy. Refresh 1D6 Energy. Each dose also causes one point of Stress.                                                                                                                                                                                                    | Common   | D8     |
| Ultra Steroids | Fast-acting nano-agent steroids that cause uncontrollable rage and violent bursts of strength. +2D in tests of Brute Force and +2 Attack Power in close combat. If you exceed your body's Max Attack Power, your body will take a Bruise for each attack you make.                                                                                   | Uncommon | D6     |


## Utility Apps
In addition to [[cyber-warfare#Combat Hacks|Combat Hacks]], you can install various apps for different utility. The cybernetic brain, and many common communication devices or handheld computing devices already have applications for various mundane tasks, such as communications, 2D photography, audio and video recording and editing etc. But for any non-mundane task you can likely find and install an App. These do take an App Slot in your cybernetic Brain. You can also install them in any external devices.

### Aptitude Suite
`Advanced`, `2 slots`,`Safety D6`

Install for one Aptitude. When activated, make a **Decay Save** but gain +1D in all tests using the Aptitude for Moderate duration. You need Moderate cooldown between uses, otherwise you will automatically take a point of **Corruption**.

### Skill Suite
`Advanced`,`Safety D10`

Install for one Skill. When activated, make a **Decay Save** but gain +1D in all tests using the Skill for Moderate duration. You need Moderate cooldown between uses, otherwise you take a point of **Corruption**.

### Personal Assistant
`Advanced`, `2 slots`

An advanced General Intelligence that can help you with anything you need. It can lookup information for you, control a drone or vehicle and many other things. The AI is controlled by the GM and it has a skill of 3D8 in every test, but using it costs 2 Energy for Moderate Duration.

## Commodities

Commodities are general everyday household items and services. Note that players are not expected to keep track of these things. You can use the Grade to estimate cost or availability of such service or produce if necessary.

| **Name**                             | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                              | Grade    |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- |
| Accomodation,  hotel room, luxurious | One night at a luxurious hotel  room with a king-size bed, fully-equipped bathroom, kitchen, a livingroom,  jacuzzi, etc. Room service charged separately.                                                                                                                                                                                                                                                                                                   | Advanced |
| Accomodation, hotel room, simple     | One night at a one-bed hotel room with  access to basic necessities                                                                                                                                                                                                                                                                                                                                                                                          | Uncommon |
| Accomodation,  Pod hotel             | A simple bed for one night at a  capsule hotel. Access to Shower, bathroom and food is charged separately.  Clean sheets included and the Pod is cleansed daily.                                                                                                                                                                                                                                                                                             | Common   |
| Cyberweb Hub                         | Free Cyberweb access is guaranteed by the Commonwealth. The Cyberweb Hub is a common household item built into every apartment, usually fitted to a wall for easy but concealable access. It functions as a personal computer, communicator that also provides physical, AR, VR or neural interface for accessing entertainment, social media and information. While Cyberweb Hubs are common, they are very valuable and each unit is meticulously tracked. | Advanced |
| Meal, luxurious                      | A luxurious meal with synthetic  animal-based protein and a mix of fresh vedgetables and carbohydrates  prepared by a professional chef.                                                                                                                                                                                                                                                                                                                     | Uncommon |
| Meal,  simple                        | A simple homemade meal with a  mix of plant-based fiber, protein and carbohydrates, often mixed together  from pre-packaged recyclable containers.                                                                                                                                                                                                                                                                                                           | Basic    |
| Beverage, Synthehol                  | A drink made with synthetic alcohol. Tastes almost like the real thing, but without overloading the environment                                                                                                                                                                                                                                                                                                                                              | Basic    |
| Beverage, Brewed Alcohol             | Real alcohol brewed with real malts. Expensive compared to synthehol.                                                                                                                                                                                                                                                                                                                                                                                        | Uncommon |
| Beverage, Single Malt Whiskey        | A bottle of real single malt whiskey, painstakingly crafted with time and patience. A rare luxury produce.                                                                                                                                                                                                                                                                                                                                                   | Advanced |
| Transportation, shared               | A vehicle you can reserve for use when needed, which is shared between several people. You only pay for the time you use the vehicle, making it an affordable option for transportation.                                                                                                                                                                                                                                                                     | Common   |
| Transportation, public               | Access to public transportation.  Approximated cost for a one-way ticket via any available public  transportations.                                                                                                                                                                                                                                                                                                                                          | Basic    |

## Vehicles and Drones

Individual ownership of vehicles is extremely rare, and most civilians used some form of public transportation or shared vehicles. Drones are extremely common and all vehicles can also be remote-controlled. If the players’ team requires use of a vehicle, you can use their basic Grade as point of reference and then simply allow or deny use of such vehicle. Characters may wish to spend their [[gamemastering/index|index]]

**Vehicle Scale** determines the scale of the vehicle relative to humans. A Scale of 0 indicates equal to scale to humans, while bigger scale means larger and smaller scale means smaller. Scale affects [[combat#Damage Scale|Damage Scale]] when the vehicle or drone is used in combat.

**Hardpoints** determine what kind of equipment or weaponry can be fitted on vehicles or drones.

- **Small** hardpoint fits equipment and weapons with up to 1 Bulk, such as any [[#Sidearms]].
- **Medium** hardpoint fits equipment and weapons with 2 Bulk, such as any [[#Assault Weapons]].
- **Large** hardpoint fits equipment and weapons with 3-4 Bulk, such as [[#Heavy Weapons]] and [[#Precision Weapons]]
- **Very Large** hardpoint fits equipment with 5-8 Bulk and most vehicular weapons
- **Massive** hardpoint fits the biggest vehicle weapons.

| Name                       | Type    | Description                                                                                                                                                                                                                                                                                                                                                                                                                   | Grade    |
|----------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| EV-58 Street Strider       | Car     | A common electric vehicle that can carry a pilot + four passengers with a sizable trunk for cargo. Used mainly in the Ground Zone and highways. Operating range is 500km on full charge. High Velocity, Scale +1.                                                                                                                                                                                                             | Common   |
| EV-77 Roadrunner           | Bike    | A fast electric bike ideal for fast transport in the Ground Zone and highways. 1 Pilot + 1 passenger. Operating range is 400km on full charge. High Velocity, Scale +0.                                                                                                                                                                                                                                                       | Common   |
| Recreational Drone         | Flyer   | A Small recreational drone with wide-lense optics and neural link for immersive FPV flying experience. Scale -3, Moderate Velocity.                                                                                                                                                                                                                                                                                           | Common   |
| Mk. 4 General Transport    | APT     | A widely used Antigravity Personal Transport for hauling equipment or people. Fits a pilot and 9 passengers or a hefty load of cargo. High Velocity. Scale +2.                                                                                                                                                                                                                                                                | Uncommon |
| Mk. 8 Personal Transport   | APT     | The most common civilian Antigravity Personal Transport designed for pilot and 4 passengers. It is used by vehicle sharing companies, taxi companies, and even Regulator Patrol units, although the Regulator models are slightly modified. High Velocity. Scale +1.                                                                                                                                                          | Uncommon |
| Security Drone             | Flyer   | A tiny unarmed drone built for speed. It has integrated loudspeaker and high lumen lights. Produces a loud alarm with bright flashing lights to alert anyone in vicinity of potential intruders. Moderate Velocity. Scale -2.                                                                                                                                                                                                 | Uncommon |
| Utility Drone              | Floater | A slowly moving floating platform with two Small Hardpoints for fitting industrial tools and equipment. Scale -1, Low Velocity.                                                                                                                                                                                                                                                                                               | Uncommon |
| Assault Drone              | Floater | A sturdy floating weapons platform with a single Medium Hardpoint. Low Velocity.                                                                                                                                                                                                                                                                                                                                              | Advanced |
| DK-27 Donkey               | Walker  | A two-legged infantry support platform, the size of pony, or a donkey, with one Small Hardpoint. It can carry heavy loads and is used by infantry to carry their heavy equipment and wounded soldiers. Moderate Velocity. Scale 0.                                                                                                                                                                                            | Advanced |
| Mk. 14 Armored Transport   | APT     | An armored Antigravity Personal Transport that fits a pilot, a gunner and up to 8 passengers or cargo. Standard for Regulator Strike teams or ARC teams. The Gunner seat is a single Large Hardpoint. High Velocity. Scale +3.                                                                                                                                                                                                | Advanced |
| Scout Drone                | Flyer   | A fast and small quadcopter ideal for scouting with one Small Hardpoint. Moderate Velocity. Scale -1.                                                                                                                                                                                                                                                                                                                         | Advanced |
| M-44 Kabuto                | Walker  | The Kabuto is a heavy combat mech, a two-legged weapons platform with four Large Hardpoints. Used as heavy fire support in demanding military operations. It is relatively compact in size and is suitable for urban use. Kabuto can fit a single human pilot inside, but it is often used as unmanned drone. Low Velocity. Scale +1.                                                                                         | Rare     |
| R-LER Mk. 3                | Roller  | 3rd generation urban pacification drone. Six-wheeled fully automated drone with two Large Hardpoints. Moderate Velocity. Scale 0.                                                                                                                                                                                                                                                                                             | Rare     |
| Swallow Combat Hyperjet    | Jet     | A relatively small unmanned hypersonic jet with 2 Large hardpoints, usually fitted with air-to-ground or air-to-air missiles. Ultra Velocity. Scale +1.                                                                                                                                                                                                                                                                       | Rare     |
| T-27 Beetle                | Crawler | The Beetle is a highly mobile assault tank with six robotic legs with built-in wheels enabling high velocity in roads, but retaining mobility in difficult terrain. It is a completely sealed construct suitable for every terrain, including amphibious use. It can be operated by a single pilot and can fit two additional passenger. Two Large Hardpoints and One Very Large Hardpoint. Moderate/High Velocity, Scale +2. | Rare     |
| Whisper Stealth Drone      | Floater | An advanced high-tech drone with built-in thermoptic camouflage, advanced optics, anti-gravity engine and silent propulsion system. It is designed to not be seen, to provide high quality intel at long distances. Low Velocity. Scale -2.                                                                                                                                                                                   | Rare     |
| Overlord Floating Fortress | Floater | A massive aerial vehicle fitted with anti-gravity engine and 8 rotating Plasma Thrusters designed for mobile ultra-heavy weapons platform and secure assault transport. It has 4 Large Hardpoints and 2 Massive Hardpoints and can safely transport 24 passengers plus a pilot. High Velocity. Scale +5.                                                                                                                      | Exotic   |



