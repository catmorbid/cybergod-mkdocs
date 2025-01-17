---
title: Damage System
version: 2
---
When a character is hit in combat they can receive [[#Conditions]] that reflect various degrees of physical trauma and wounds to their Frame. Conditions are determined by the [[#Damage Class]] of an attack, which can be reduced by [[#Mitigation and Penetration|Mitigation]] or [[#Damage Reduction]].

When you receive a condition, there is always a possibility for a bad situation becoming even worse; most non-fatal conditions have some sort of [[#Triggers|Trigger]] that can cascade into worse conditions – and eventually death.

!!! warning
	Combat can be extremely lethal as the damage system makes it possible for even small wounds to escalate into fatal wounds. To improve chances of survival, you can put skill points to Toughness, upgrade your Body attribute, wear good armor or augments that provide mitigation. As a final resort, you can use Resolve to give you a fighting chance when the odds are not in your favor.

### Damage Class

**Damage Class (DC)** of an attack is determined by the Weapon used. For unarmed attacks DC is 1 (non-lethal) and most firearms have a DC between 2 and 5, but there isn’t an upper limit.

DC determines the inflicted [[#Conditions|Wound Condition]], not accounting for [[#Mitigation|Mitigation]]. An attack can generate multiple Hits, and each Hit is handled separately.

### Mitigation

Damage can be **Mitigated** by spending **Mitigation Points**, which represent some type of protection such as personal armor or cover provided by surroundings. All mitigation points are single use only, and when provided by armor or equipment, loss of mitigation points represents wear and tear of said equipment. Some mitigation points may be temporary, provided by certain conditions, such as being under [[#Taking Cover|Cover]].

Spend Mitigation Points to reduce damage of incoming hits. A **Mitigated Hit** will reduce DC to **half** (rounded down) of normal *unmitigated* hit.

The cost of mitigating a hit is equal to the **Armor Piercing (AP)** stat of the attack. Minimum AP rating is 1/2 indicating that you can spend 1 point to mitigate 2 hits.

| Armor Piercing | Description | Examples                                            |
| -------------- | ----------- | --------------------------------------------------- |
| 1/2            | Low         | Shotguns, hollow-point rounds, low-power lasers.    |
| 1              | Standard    | Common Military-grade firearms and lasers.          |
| 2              | High        | Light armor piercing rounds, high-power lasers      |
| 3              | Superior    | High-velocity armor piercing rounds, plasma rounds  |
| 4              | Ultra       | Hypersonic projectiles                              |
| 5+             | Extreme     | Large caliber hypersonic armor-piercing projectiles |

Mitigation Points are exhausted until they can be replenished. If provided by armor, the armor takes permanent damage for each point spent and must be replaced or repaired before the points are replenished. Mitigation Points from cover and other non-permanent sources of protection, such as energy barriers should be used first and tracked separately.

!!! example
	Boris takes a blast from an automatic shotgun and takes 6 hits of DC 3 and AP 1/2. Boris spends 3 mitigation points to mitigate all hits, reducing each hit to DC 1.

!!! example 2
	Kitah has been ambushed by a sniper and is trying to move from cover to cover to avoid a hit. Kitah found some cover worth 2 points but takes a well-aimed shot dealing DC 7 AP 2 Hit. The cover is barely enough and Kitah spends both mitigation points to reduce the hit to DC 3.

### Damage Reduction
Damage Reduction (DR) reduces the Damage Class directly, *before* applying any mitigation. High DR can make a character entirely immune to lower tier DC. DR is very scarce and is only provided by heaviest armor or massive targets, representing a major difference in scale.

!!! example
	Boris is fighting against a heavily armored R-LER Mk 3 drone and fires off a burst from his CHAOS Mk.2 sidearm, landing 4 hits with DC 3 and AP 1. The Drone is very tough and has DR 2 plus 10 points of mitigation. After applying DR, Boris inflicts 4x DC 1 hits. The Drone then spends 4 Mitigation to reduce all hits to DC 0, taking no damage at all and still has 6 mitigation to spare.

### Applying Damage
When a character takes damage in combat, they receive physical [[#Conditions|Conditions]] based on the [[#Mitigation|mitigated]] [[#Damage Class]] of each hit. If you take multiple Hits, you also take multiple conditions. [[#Conditions]] are tracked separately and as you receive them, you must resolve their [[#Triggers]]. You only need to resolve each type of Trigger once, after marking down all conditions resulting from an attack.

Resolve all triggers starting from *lowest* severity first, since those may increase the worst conditions.

| Damage Class | Condition      | Wound Penalty | Trigger                 | Stabilize?                 |
| ------------ | -------------- | ------------- | ----------------------- | -------------------------- |
| 1            | [[#Bruised]]   |               | [[#Shock Trigger]]      | No                         |
| 2            | [[#Wounded]]   | -1D           | [[#Escalation Trigger]] | No                         |
| 3            | [[#Injured]]   | -2D           | [[#Critical Trigger]]   | No                         |
| 4            | [[#Dying]]     | -4D           | [[#Death Trigger]]      | Yes → [[#Maimed]]          |
| 5            | [[#Dead]]      |               | nothing                 | Yes → [[#Dying]] (1 round) |
| 6+           | [[#Destroyed]] |               | nothing                 | No                         |

!!! example
	Boris received 6 hits at DC 1 each inflicting 5 levels of [[#Bruised]] condition – the final level is ignored as Boris is already maxed on Bruised condition – and has to resolve [[#Shock Trigger]].

!!! example cascading conditions
	Kitah takes DC 3 damage from the sniper’s attack and is now [[#Injured]], marking down one level of injured condition, and now must resolve [[#Critical Trigger]]. Kitah has Body D6 and Toughness 3 for a dicepool of 3D6. Kitah rolls 2, 3, 3 – that’s a failure. Kitah receives *Dying* condition, and now has to resolve [[#Death Trigger]]. Kitah Rolls 3D6 again: 4, 3, 1 – another failure, this time resulting in death. Luckily the player still has one point of resolve left so they re-roll all dice: 6, 6, 3 – a success! Kitah collapses and is dying – but manages to hang on for a while.

!!! example multiple conditions
	Zin Long is fighting a bunch of thugs in a crowded bar and lands 2 hits with his Ultra-Blade to one of the thugs inflicting DC 4 AP 2 per hit. The Thug can only mitigate one hit, so the other goes through unmitigated causing **Wounded** and **Dying** conditions. The Thug resolves [[#Escalation Trigger]] rolling 4D6: 1, 4, 3, 2 → that’s a failure. Thug receives an **Injured** condition and now has to resolve [[#Critical Trigger]] rolling 2, 4, 4, 1 – another failure, this time adding second level of **Dying** condition. The Thug now finally resolves the [[#Death Trigger]] from **Dying** condition at threshold 2 and rolls 1, 1, 4, 5 → only 1 success is not enough to beat the threshold of 2 and the Thug succumbs to their wounds and dies.

### Condition Test
A Condition Test is required when the character needs to *resist* a certain physical or mental condition. Condition Tests are called  Condition Test is always a `Toughness x Body` test.

**Success Threshold** of a Condition Test is usually equal to the Level of Condition. Condition Tests do not suffer from usual circumstantial penalties such as *Wound Penalties*, but they cannot be **assisted** either. Certain external aids such as painkillers or stims may award Bonus Dice to Condition tests.

### Conditions

Condition is inflicted according to the **mitigated Damage Class** of a hit. Conditions stack and are tracked separately. Each condition has an immediate effect, and most conditions also have a [[#Triggers|Trigger]] requiring a [[#Condition Test]] to avoid additional consequences.

Some conditions need **stabilization** to prevent character death, requiring a **MedTech** test.

Conditions have 1-5 levels, and whenever you receive a condition, you increase its level by one. Condition Level affects the success threshold of linked [[#Triggers]]. Once condition level is maxed, you do not need to add new conditions, but still need resolve any [[#Triggers]] associated with the condition.
#### Bleeding
*Bleeding* condition does not have any immediate effects, but it inflicts additional damage at the start of each round. Make a [[#Condition Test]] against condition Level. Bleeding inflicts damage *ignoring DR and Mitigation* at DC equal to condition level, but each **success** reduces damage taken by one. First Aid or meds can be used to reduce the level of *Bleeding*.

#### Bruised
`Wound Condition`

*Bruised* condition indicates minor damage such as bruises or small cuts. When inflicted, you need to resolve [[#Shock Trigger]].

#### Burning
The character is engulfed in flames and will take continuous *damage* and *stress* at the start of each round until the fire is extinguished. Make a *Condition Test* against condition level at start of each round. *Burning* inflicts damage at DC equal to condition level, but each **success** reduces damage taken by one. If you take any damage from *burning*, you also take a point of **Stress**. Burning can be extinguished with appropriate measures, usually requiring an action and opportunity.

#### Dead
The character has taken lethal wounds and will be [[#Destroyed]] very soon.  You cannot take any actions are effectively [[#Incapacitated]].

There is however a relatively small timeframe when the body can be *stabilized* with a `Hard MedTech x Mind` test, turning death into a [[#Dying]] condition instead. Failing the test or taking too long means the character dies. You only have one chance to survive this and you also need to act fast. It is GM’s call how long you have.

#### Dying
`Wound Condition`

You take a -4D [[#Wound Penalty]] on all actions due to crippling pain. Painkillers can only mitigate half of the penalty. When inflicted, and *at the start of every round* thereafter, you must resolve [[#Death Trigger]].

The condition can be **stabilized** with first aid, meds or treatment. Without meds you need a `Moderate MedTech x Mind` test. Once stabilized you are no longer **Dying** and instead receive the **Maimed** condition.

#### Fatigued
Fatigued can be inflicted as consequence of over-strenuous physical activity, sleep deprivation or excessively burning through energy reserves. E.g. GM could assign fatigued as a complication on a very demanding physical test.

You are unable to function at peak performance due to over-exertion and are closer to collapsing. You take a -1D penalty per condition level to any skill tests.

#### Incapacitated
Your are unable to take any actions or reactions. Most humans would lose consciousness but you may sometimes retain consciousness, but are unable to act in any way regardless. Incapacitation lasts for a **Moderate** duration.

#### Injured
`Wound Condition`

Take a -2D [[#Wound Penalty]] on all actions due to serious pain and physical trauma. When inflicted, resolve [[#Critical Trigger]].

#### Maimed
`Wound Condition`

A [[#Dying]] condition that is treated becomes a *Maimed* condition. You take -3D [[#Wound Penalties]] but do not need to resolve [[#Death Trigger]] any longer.

#### Destroyed
This condition is final. You are dead and there’s no way to resuscitate or recover. Overkill is often extremely brutal and gory and will inflict Stress on any allies.

#### Stunned
You are unable to take any actions, and your next **Reaction** is at -2D penalty, stacking with wound penalties. Stunned is recovered automatically after you have taken your next Reaction. If you take multiple levels of *stunned*, you erase one mark after each Reaction taken, but remain afflicted until the condition is completely removed.

#### Wounded
`Wound Condition`

Take a -1D [[#Wound Penalty]] on all actions due to painful wounds. When inflicted, resolve [[#Escalation Trigger]]


### Triggers
When you receive a new condition, or increase the level of an existing condition, a *Trigger* is usually activated, possibly leading to further consequences. Triggers require a [[#Condition Test]] to pass, failure results in a cascade of consequences.

!!! info
	Resolve can be spent on Condition Tests, and doing so may be a very good idea in order to avoid death or crippling conditions.

#### Death Trigger
You must make a [[#Condition Test]] against a threshold of condition level. On failure, the character receives the [[#Dead]] condition.

#### Shock Trigger
Make a [[#Condition Test]]. The threshold to ignore all shock is equal to [[#Shock Level]], but you can obtain a partial success at half the threshold but still receive [[#Stunned]] condition. On **failure** you receive [[#Incapacitated]] condition.

**Success Thresholds:**

- **Success([[#Shock Level]])**: You are unaffected by the shock.
- **Stunned([[#Shock Level]] / 2 (round down))**: You receive [[#Stunned]] condition.
- **Failure**: You receive [[#Incapacitated]].

!!! example
	Boris is pretty badly beat-up and has received Bruised-6 and Wounded-2, and now must resolve a Shock Trigger. His total [[#Shock Level]] is 8 so the thresholds are 4 and 8. He rolls 5D10: 7, 7, 5, 4, 3. That’s only 3 successes, resulting in failure and Boris is now [[#Incapacitated]] due to shock. This might be a good spot to spend some Resolve to reroll the two failed dice as Boris only needs 1 more success to become [[#Stunned]] instead.

#### Escalation Trigger
Make a [[#Condition Test]] at threshold equal to [[#Wounded]] condition level. On failure, your wounds escalate to more severe injuries and you receive an [[#Injured]] condition, triggering any linked consequences as well.

#### Critical Trigger
Make a [[#Condition Test]] at threshold equal to [[#Injured]] condition level. On failure, your condition becomes critical and you receive [[#Dying]] condition, triggering any linked consequences as well.

### Shock Level
Shock Level is equal to the total of all **Wound Conditions**, which are:
- Bruised
- Wounded
- Injured
- Maimed
- Dying

!!! example
	Zin Long is in a bad shape after fighting a bar full of thugs. He has Bruised-5, Wounded-3, Injured-1. His total Shock Level is 9. He is barely standing, but remains victorious.

### Wound Penalty
Only highest level of Wound penalty is applied. E.g. if you have both [[#Wounded]] and [[#Injured]] condition, you apply the -2D penalty from [[#Injured]] only. Wound penalties are applied to all **Skill Tests** but they do not apply on **Condition Tests**.

### Non-Lethal damage
When taking Non-lethal damage, you replace any normal [[#Triggers]] with [[#Shock Trigger]] instead. Even non-lethal damage can cause death when Damage Class is high enough, but they won’t escalate to more severe conditions. When inflicting multiple Hits, you only resolve [[#Shock Trigger]] once, after marking everything down.

!!! example
	Kitah finds themselves facing an enemy in close quarters, forcing them into hand-to-hand combat. Kitah strikes the enemy with their modified Fast Shock Stick landing 3 hits with non-lethal DC 4, AP 1. The soldier has 2 mitigation which is enough to drop 2 hits to DC 2, but the third one goes through at DC 4. The enemy is now [[#Wounded]]-2 and [[#Dying]]. The enemy must resolve [[#Shock Trigger]] and rolls 3D6: 5, 1, 3 for 1 success. Their Shock Level is now 3, so with 1 success they achieve a partial success and are now [[#Stunned]] and have -4D wound penalty. The enemy is effectively taken out.

### Recovery and survival
If you do not die from your wounds, then you’ll survive. There are a few ways to recover from wounds:

- **Emergency Treatment**: In field conditions, you can test `MedTech x Mind` to administer first aid or even field surgery. provided you have the tools. Critical wounds require **stabilization** before they can be treated.
- **Nano Stims**: Fast-acting advanced high-grade medical nano-bots can be injected to accelerate healing. Excessive use is not recommended. Nano Stims can be administered and programmed for various purposes, but you need to decide how you wish to apply it:
	- Fully heal [[#Bruised]] condition in Short Duration
	- Fully heal [[#Bleeding]] condition in Short Duration
	- Heal 1 level of Wounded condition in Moderate Duration
	- Heal 1 level of Injured condition in Long Duration
- **Augments**: Certain augments enable rapid regeneration at high energy cost.
- **Natural Recovery:** Wounds heal at different rates naturally. Proper medical care will significantly reduce this time.
	- **Bruised**: One condition level is removed at end of scene.
	- **Wounded**: One condition level is healed per day
	- **Injured**: One condition level is healed in 10 days
	- **Maimed**: One condition level is healed in 30 days

While recovering from wounds completely almost always takes a long time, it may be easier to obtain some pharmaceutical aid to help alleviate the pains. Only the highest bonus of any drugs apply at any one time.

- **Painkillers**: Safe and effective aid for alleviating pain. Reduce Wound Penalties by 1D for Moderate duration and gain +1D bonus on Wound Condition Tests. Safety D12. Common Grade. Safety D12.
- **Combat Stimulants**: A powerful smart drug that increases adrenaline and dopamine by moderate amounts and blocks pain receptors. Reduce Wound Penalties by 2D and gain +2D bonus on all Condition Tests for a Moderate duration. Become [[#Fatigued]] for moderate duration after use. Advanced Grade. Safety D8.
- **Adrenaline Boosters**: Low-grade street drugs that boosts adrenaline and dopamine levels through the roof, making the user feel invincible. Reduce [[#Wound Penalty]] by 3D and gain +2D bonus on all Condition Tests for Moderate duration, but after the effect cools down, gain [[#Fatigued]] condition for a Long duration – that is unless you take another hit. Safety D6. Highly addictive.

### Simplified Damage Rules
`Optional rule`

GM may opt to simplify damage rules to speed up gameplay. This may be especially useful when resolving combat against a large number of minor NPC’s. Significant characters should always use the full rules to emphasize their level of threat and even the playing field with player characters.

**Condition Tests** are resolved automatically based on Condition Level and the character’s Body Attribute. Toughness skill is ignored for this purpose.

| Body | Failure Threshold |
| ---- | ----------------- |
| D6   | Condition Level 1 |
| D8   | Condition Level 2 |
| D10  | Condition Level 3 |
| D12  | Condition Level 4 |

**Shock Triggers** are resolved by comparing [[#Shock Level]] to a pre-calculated **Shock Threshold**.

**Shock Threshold**: Body Level + Toughness + Physical aptitude.

If Shock Level meets or exceeds the Shock Threshold, the Shock Trigger Condition Test results in [[#Incapacitated]] condition.

If Shock Level is equal or more than half Shock Threshold (rounded up), then the character becomes [[#Stunned]] instead.

!!! example
	A Syndicate Ronin has Body D8 (level 2) and Toughness+Physical 5. Their Shock Threshold is 7. They have taken 1 injury and 2 bruises and receive 2 hits bringing them to Bruised-3 and Injured-2. They first resolve Shock Trigger with Shock Level 5 resulting in Stunned condition, since Shock Level 5 is equal or more than Stun Threshold 4. Next they resolve the Critical Trigger from injured, which also fails inflicted Dying condition.