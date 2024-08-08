# 0x06 >> Frame

Frame is the physical body that character uses as host for their consciousness. Consciousness is digital and if you die you can be *reborn* in another frame. You pick one frame from those available to your [[#Faction]], but you can spend **Upgrade Points** to improve it further. Factions provide the resources to you and are also responsible for your Upgrades.

## Attributes

Frame determines the character's attributes. Attributes are measured with a **Level** from 1 to 4 and each Level indicates a Die Size from D6 to D12. The average human has Level 1 attributes, i.e. a D6 in everything. If a frame is lacking any attribute, it cannot perform any related tasks.

> [!info]
> You can spend **Upgrade Points** to improve Attributes. Attributes cost **2 Upgrade Points**.

### Body

Body represents constitution, strength, fitness and athletic ability. Use Body to fight in close combat and perform tasks that require endurance, strength or athletic ability. Body affects many aspects of the character passively, although it might not be used in tests that much.

**Max Power** determines how much damage you can deal in close combat, indicating how many **Attack Power** effects you can take without harming yourself.

**Max Bulk** determines how much gear and armor you can carry without penalties. More info on [[gear]]

**Wounds Slots** determine how much damage your Frame can take before going down. Higher level Body helps sustain more damage and still remain functional. See [[combat#Damage and Mitigation]] on how wound slots work.

| Body | Description | Max Power | Max Bulk | Wounds Slots                         |
|------|-------------|-----------|----------|--------------------------------------|
| D6   | Average     | 1         | 6        | 2 Bruise, 2 Minor, 1 Major, 1 Lethal |
| D8   | Strong      | 2         | 8        | 3 Bruise, 3 Minor, 2 Major, 1 Lethal |
| D10  | Powerful    | 3         | 10       | 4 Bruise, 4 Minor, 2 Major, 2 Lethal |
| D12  | Superhuman  | 4         | 12       | 5 Bruise, 5 Minor, 3 Major, 2 Lethal |

### Reflex

Reflex determines hand-eye coordination and reaction time. Reflex is used to react to sudden situations, evade attacks and make ranged attacks.

Reflex affects **Initiative** which determines how fast you can act when making a Conflicting test in combat. Read more on this in [[combat]]. At D10 or higher Reflex you also become **Ambidextrous** and can handle actions with either hand effectively. Without ambidexterity, you take a -1D penalty to using your off-hand, when relevant.

| Reflex | Description | Initiative | Ambidextrous |
| ------ | ----------- | ---------- | ------------ |
| D6     | Average     | 1          | No           |
| D8     | Quick       | 2          | No           |
| D10    | Graceful    | 3          | Yes          |
| D12    | Superhuman  | 4          | Yes          |

### Mind

Mind determines intellect, cunning, awareness and focus. Mind is is probably one of the most utilized attributes, but it does not have any passive effects.

| Mind | Description |
|------|-------------|
| D6   | Average     |
| D8   | Smart       |
| D10  | Genius      |
| D12  | Visionary  |

### Cyber

Cyber determines the character's ability to interface with computers, hack devices, engage in electronic and cyber warfare and defend against cyber intrusions.

Cyber determines how many **Apps** you can have installed. Apps are your weapons when using Combat Hacks. Read more about this on [[cyber-warfare]].

| Cyber | Description     | Apps |
| ----- | --------------- | ---- |
| D6    | Common hardware | 2    |
| D8    | Hacker gear     | 4    |
| D10   | Military Grade  | 6    |
| D12   | Supercomputer   | 8    |

## Energy

Energy is used to fuel Augments. Each Attribute adds some Energy to the total based on its rating. You automatically recover 1 point of Energy after each scene, and additional 1D6 energy if you spend time recovering or consuming nutrients after.

| Attribute | Energy |
| :-------- | :----- |
| D8        | 1      |
| D10       | 2      |
| D12       | 4      |


## Augments

Your initial Augments are determined by your **Frame**. Choose a frame from the ones listed in your chosen Faction.

> [!info]
> You can spend **Upgrade Points** to improve Augments. Augment Level costs 1 Upgrade Point.

**Activating** Augments is an **Instant Action** and costs 1 Energy per Level. You can choose to activate lower level abilities to conserve energy. Some Augments are tagged as #Passive  and those do not require energy expenditure.

Many augments can be **Boosted** by spending additional energy. When some property can be boosted, it's marked with an arrow symbol ->, indicating the new boosted property.

**Safety**: High level augments or those tagged as #Unsafe will trigger a *Decay Save* whenever they're used. The die size depends on the augment level and whether the augment has the unsafe tag. Only augments that require activation trigger *Decay Saves*.

[Augment Safety table]

| Augment Level | Safe | Unsafe |
| ------------- | ---- | ------ |
| [1] Basic     | -    | D10    |
| [2] Advanced  | D12  | D8     |
| [3] Ultra     | D10  | D6     |

### Adrenaline Rush

#Biotech #Cybertech #Nanotech 

Enter a state of constant adrenaline frenzy improving overall combat capabilities. Once activated, the effect will be maintained for a **Moderate** duration, or until hostilities are ceased. Even then you might require some time to calm down.

| Level | Effect                                                                                                                                              |     |
| :---- | :-------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| 1     | Gain +1D in Close Combat. Ignore Minor Wound penalties. You must attack nearest perceived threat and you can't reliably recognize friend from foe.  |     |
| 2     | Gain +2D in Combat actions. Ignore Major wound penalties. You can recognize friends and foes while frenzied.                                        |     |
| 3     | Gain +3D in Combat actions. When receiving Lethal Wounds you are no longer incapacitated and can take actions normally. You can end effect at will. |     |


### Aegis

#Cybertech 

Create energy field to protect yourself and those nearby. The shield lasts for a **Short** duration, but it can be maintained by spending another point of Energy.

| Level | Effect                                                                                                                                                                                                   |
| :---- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Activate for 1 Energy. Generate a force field that affects anything within **Close** -> **Short** -> **Moderate** radius and adds **2 points** of **Ultra Mitigation**. Melee weapons bypass the shield. |
| 2     | Activate for 2 Energy. Shield adds **4 points** of **Ultra Mitigation**.                                                                                                                                 |
| 3     | Activate for 3 Energy. Shield adds **6 points** of **Ultra Mitigation**.                                                                                                                                 |

### Avatar

#Cybertech #Unsafe 

Avatar enables physical remote presence at very distant locations through holographic interface. You can use holoprojection drones and and a location's built-in projection systems by accessing the location through remote connection. Once connected you can project Holographic Avatars to interact on your behalf. The area can be extended by connecting to new Access Points. If you lose access to the location, or all of your holoprojector drones are destroyed, your Avatars will immediately perish.

| Level | Effect                                                                                                                                                                                                                                                                                                                                                                |
|:----- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Create a single Holographic Avatar within Moderate range for a Moderate duration for 1 Energy. Avatars are capable of normal physical interaction and they have Body D6 and Reflex D6. You can spend additional Energy to augment Avatar's Body or Reflex by one die step per Energy, up to D12. Avatars can pick up weapons and wear armor like any physical entity. |
| 2     | Long range. You can create multiple avatars, but each avatar costs separate energy.                                                                                                                                                                                                                                                                                   |
| 3     | Extreme range. The total cost of each Avatar is halved.                                                                                                                                                                                                                                                                                                               |

### Biomorph Armor

#Biotech #Unsafe 

Biomorphs can be used to mutate the frame in a rapid rate to grow extra layers of protection from muscle, bones, tendons. The process is generally called creating a Biomorph armor, but it will also alter the character' physical traits in such significant way that calling it just "armor" seems like an understatement. Mutation is always permanent unless recalled. Mutating the frame and then recalling it takes just a short duration. The sight itself is so gruesome most characters witnessing it will take **Stress**. Biomorph Armor can be reactivated to regenerated spent mitigation points.


| Level | Effect                  |
|:----- |:----------------------- |
| 1     | Gain 5 Soft Mitigation. |
| 2     | Gain 5 Hard Mitigation. |
| 3     | Gain 5 Ultra Mitigation |

### Biomorph Healing

#Biotech #Unsafe 

You can use Biomorphs from close proximity to another target, or heal yourself to by spending an Action. Total **Healing Power** is `2x Energy Spent`, but each level requires a minimum energy to be spent to activate. You can spend additional energy to improve the effect, but the maximum wound level is limited by the ability.

Healing Power is a pool of points you can use to heal wounds. A wound requires Healing Power equal to their Damage Class equivalence.

>[!example]
>a Major Wound occurs at Damage Class 3, so you need 3 Healing Power to heal a Major Wound.

| Level | Effect              |
|:----- |:------------------- |
| 1     | Heal Minor Wounds.  |
| 2     | Heal Major Wounds.  |
| 3     | Heal Lethal Wounds. |

### Biomorph Invasion

#Biotech #Unsafe 

Invade a target with parasitic Biomorphs that latch onto the target's biological components. Gain access to their motor functions and even cognitive state. Synthetic frames cannot be invaded, but even Cybernetic frames are susceptible to invasion. Target must be within close range and unable or unwilling to resist physically. It is practical to first physically incapacitate the target before attempting invasion.

| Level | Effect                                                                                                                                                                                     |
| :---- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | **Zombification**: Render the target into a mindless husk that can follow simple orders. Long Duration. Resist with a Body Save vs. Mind -> +1 -> +2                                       |
| 2     | **Mind Spy**: Gain telepathic link between target and yourself. You can share thoughts to them and pry on their thoughts. Long Duration. Resist with Mind Save vs Mind -> +1 -> +2         |
| 3     | **Indoctrinate**: Alter the subject's cognitive state. They perceive you as an ally and will fight for you to the death. Long Duration. Resist with Body or Mind Save vs. Mind -> +1 -> +2 |

### Biomorph Weapons

#Biotech #Unsafe 

You can use Biomorphs to transform your flesh into deadly weapons, increasing your mass and density, forming new growth and matter. The process is almost instantaneous and by the time you see the transformation, it's likely too late. 

| Level | Effect                                                                                                                                                             |
|:----- |:------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1     | **Bone Talon**: Grow a long, pointy talon in one of your arms. DC 3 Close Range, Armor Piercing.                                                                   |
| 1     | **Razor Blades**: Transform your fingers into sharp razor blades made of unnaturally dense bone. DC 3, Close Range, Double Hits.                                   |
| 2     | **Meat Club**: Undergo incredible growth on one of your limbs, creating a huge awkward club made of hardened flesh and bone. DC 5, Close Range, Inaccurate         |
| 2     | **Bone Whip**: Grow a long, fleshy whip with razor-like bone claws protruding out. Slow attack that is easy to avoid. DC 4 Short Range, Inaccurate.                |
| 3     | **Flesh Crusher**: Transform half of your body and a ton of additional mass into a massive deformed bludgeoning device. DC 8 Short Range, Inaccurate, Area (small) |
| 3     | **Tentacle Madness**: A mass of fleshy tentacles explode from your body ripping into any living things nearby. DC 5 Moderate Range, attack up to 10 targets.       |

### Camouflage

#Biotech #Cybertech #Nanotech 

A stealth augment that can blend the character with their surroundings. Advanced tiers also help mitigate noise from movement and provide additional masking options. Unless an observers has a way to see through the camouflage, they cannot see the cyborg and have a -4D penalty to any actions against them, if even allowed. Camouflage is maintained even after the cyborg attacks a target, but taking any wounds will interfere with the camouflage.

A downside to camouflage is that you cannot use most **armor**, and only *Nano Weave* or integrated *Cybernetic Armor* work with Camouflage.

Likewise only **Small** melee weapons and Integrated weapon systems are viable when using Camouflage.

| Level | Effect                                                                             |
|:----- |:---------------------------------------------------------------------------------- |
| 1     | Optical Camouflage. Short Duration when moving. Moderate Duration when stationary. |
| 2     | Thermoptic camouflage. Hide sounds of movement.                                    |
| 3     | Electromagnetic Camouflage. Does not cost any energy when staying still.           |


### Chronoflux

#Cybertech #Syndicate #Unsafe 

A dangerous modification to the frame's Energy Core that can create a temporal distortion centered on the frame, which alters the flow of time. It allows the individual to momentarily act faster and take more actions at a significant cost to themselves. Any damage taken by using the augment takes effect next round.

| Level | Effect                                                                                             |
|:----- |:-------------------------------------------------------------------------------------------------- |
| 1     | Take an additional action for **Short** Duration at cost of 1 energy and 1 Minor Wound to yourself. |
| 2     | Take 2 additional actions for total 2 Energy and a Major Wound                                     |
| 3     | Take 3 additional actions for 3 Energy and 2 Major wounds                                          |

### Coil interface

#Cybertech #Cyberweavers #Unsafe 
A system for remotely interfacing with any device that has any sort of circuitry, even without a software interface. Can also be used to inflict Feedback damage without hacking on cyborgs or synthetics and drain energy from electrical systems and cyborgs who lack the critical protection.

| Level | Effect                                                                                                 |
| :---- | :----------------------------------------------------------------------------------------------------- |
| 1     | **Interface**: Interact with devices within Moderate distance. Maintain connection for Short duration. |
| 1     | **Drain**: Drain 1 Energy from all eligible targets within a Short radius.                             |
| 2     | **Interface**: Interact with devices within Long distance. Maintain connection for Moderate duration.  |
| 2     | **Minor Feedback**: Inflict a minor wound for 1 Energy.                                                |
| 3     | **Interface**: Interact with devices within Extreme distance. Maintain connection for a Long duration. |
| 3     | **Major Feedback**: Inflict a Major wound for 3 Energy.                                                |
| 3     | **Heavy Drain**: Drain up to 5 Energy from a single target.                                            |

### Cybernetic Armor

#Cybertech #Passive

Integrated exoskeletal armor that cannot be removed without heavy tools. Cannot equip additional armor. Cybernetic Armor must be repaired once broken down.

| Level | Effect                                      |
|:----- |:------------------------------------------- |
| 1     | 4 Soft, 2 Hard, 1 Ultra Mitigation. No bulk.         |
| 2     | 4 Soft, 4 Hard, 2 Ultra Mitigation. 2 Bulk. |
| 3     | 5 Soft, 5 hard, 3 Ultra Mitigation. 4 Bulk. |

### Drone Eyes

#Cybertech 

A modified ocular system which has an array of multiple *Ocular Drones* that can be launched independently to provide visual coverage of a large area. The image of all the drones is combined in real-time to a visual matrix combined from the image of all the drones.

| Level | Effect                                                                                                                                                                                                          |
|:----- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | **Quad Array**: Four ocular drones which either add a combined +1D to Alertness tests, when mounted in the Ocular Array, or can be launched independently to provide large area coverage. Long Range.           |
| 2     | **Hexagonal Array**: Six ocular drones which either add a combined +2D Alertness when mounted in the Ocular Array, or can be launched independently to provide large area coverage. Extreme Range.              |
| 3     | **Octagonal Array**: 8 ocular drones which either add a combined +3D Alertness when all drones are mounted in the Ocular Array, or can be launched independently to provide large area coverage. Extreme Range. |

### FACE

#Cybertech #Nanotech #Biotech #Unsafe 

FACE is an active feromone agent manipulation system that acts as a powerful social enhancer.

| Level | Effect                                                   |
|:----- |:-------------------------------------------------------- |
| 1     | Gain +1D in Social Tests for Moderate Duration           |
| 2     | Gain +2D in Social Tests. You can re-roll a single test. |
| 3     | Gain +3D in Social Tests. You can re-roll twice.         |


### Flight

#Cybertech 

Built-in thrusters to arms and legs and other modifications that enable flight. Operate with a `(Mobility or Pilot)+Reflex Test`. 

| Level | Effect                                                                             |
|:----- |:---------------------------------------------------------------------------------- |
| 1     | Take up flight for Moderate Duration. Moderate Velocity. Maneuvering Difficulty 1. |
| 2     | High Velocity. Maneuvering Difficulty 2.                                           |
| 3     | Ultra Velocity. Maneuvering Difficulty 3.                                          |

### Gravitron

#Cybertech #Unsafe 

The Gravitron is a powerful augment that can be used for manipulating and altering gravity.

| Level  | Effect                                                                                                                                                                                                                                                                   |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1      | **Nullify Gravity**: Close -> Short -> Moderate radius. Counteracts gravitic forces within the specified area. Everything floats as if in micro gravity. Short->Moderate duration.                                                                                       |
| 1      | **Gravity Punch**: Pinpoint gravity to a small area, magnifying striking power when fighting unarmed. Improves unarmed DC by +1 -> +2 -> +3 for an Instant -> Short -> Moderate duration.                                                                                |
| 2      | **Lift**: You can slowly repulse gravity to lift everything within Close -> Short -> Moderate radius centered on you, enabling a slow levitation effect. Affects everything within the radius for Moderate duration.                                                     |
| 2      | **Impulse**: Generate a momentary impulse of force to move yourself, or to push targets back. When pushing a target they must make a Body Save 4 -> 5 -> 6.                                                                                                              |
| 3      | **Immobilize**: Pin targets at Short -> Moderate range to the ground by amplifying local gravity, making them extremely heavy. Targets may attempt to resist by making Body Save 4 -> 5 -> 6.                                                                            |
| 3      | **Barrier**: Generate a brief but powerful force field in one direction at approximately 90->180->270 degree arc that nullifies all kinetic forces that collide with it. Stops anything with a kinetic force, including bullets. Lasts for an Instant -> Short Duration. |



### Immortal

#Cybertech #Nanotech #Passive 

Takes a backup of consciousness in realtime. Provided you have the means to deploy a new frame, you could be back in action within minutes of a Frame Death incident. 

>[!info]
>Immortal is always active and it **permanently** reduces available Energy by an amount equal to Augment Level. You can choose to disable it, but do you really want to?

| Level | Effect                                             |
|:----- |:-------------------------------------------------- |
| 1     | Backup can be restored once every 2 game sessions. |
| 2     | Backup can be restored once every game session.    |
| 3     | Backup can be restored twice per game session.     |

### Inhibitor

#Cybertech #Nanotech #Biotech #Unsafe 

A system for controlling hormonal activity and emotional state. Helps mitigate Stress and maintain combat readiness. The effects on each level stack and can be applied at the same time. Once activated, Inhibitor will remain active for a **Long** duration.

| Level | Effect                                                                     |
| :---- | :------------------------------------------------------------------------- |
| 1     | Mitigate 1 point of Mental damage.                                         |
| 2     | You can re-roll the result of a Mental Breakdown and choose either result. |
| 3     | Mitigate 1 point of Stress. Initiative +1.                                 |

### Interference

#Cybertech

An asymmetric warfare system that allows disruption of communications, electronics and augmentations. Designed for anti-cyborg warfare, Interference can be a powerful tool against powerful cyborgs.

| Level | Effect                                                                                                                                                                     |
| :---- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | **Electronic Camouflage**: Test `Stealth x Cyber` to conceal up to 2 targets from electronic surveillance without penalties. Add -1D penalty for every 2 targets beyond 2. |
| 1     | **Interference Detection**:Test `Alertness x Cyber` to detect use of Interference.                                                                                         |
| 2     | **Augment Interference**: Disrupt a random augment -&gt; choose 1 augment on target. The augment is disabled for **Short** -&gt; **Moderate** duration.                    |
| 2     | **Electronic Disruption**: Block communications within **Long** -&gt; **Extreme** distance radius.                                                                         |
| 3     | **Electronic Hijack**: You can hijack any wireless communications within **Long** -&gt; **Extreme** radius.                                                                |
| 3     | **Short Circuit**: If target activates any augments for **Moderate** duration, they take a Major Wound.                                                                    |

### Pinpoint

#Cybertech #Nanotech`

Specialized marksmanship enhancement. Automatically tracks targets and helps aiming at critical locations.

| Level | Effect                                                                                                                                                                                                                                                                                                                    |
|:----- |:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | You can Mark one target. Target remains marked for as long as they are visible to you or any of your allies. If you lose track of target at end of round, the Mark is lost. You and allies receive +1D modifier on any tests to observe the target or attack them or any other related Tests that benefits from the Mark. |
| 2     | You can Mark 2 Targets. Damage Class against Marked Targets is increased by +1.                                                                                                                                                                                                                                           |
| 3     | You can Mark up to 4 Targets. Damage Class against marked targets is increased by +2.                                                                                                                                                                                                                                     |

### Psionics

#Nanotech #Section12 #Unsafe 

Unlock psionic abilities in the human brain. To use Psionics you need to spend Energy to activate an ability. In addition you must make a **Psionics test** using `Current Resolve + Psychology x Mind`.

**Psionics Boosting**: You can spend energy as usual to Boost various properties of abilities, but you can also spend any bonus Effects from the Psionics test in similar manner.


| Level | Effect                                                                                                                                                                                                                                                                                                                                                              |
|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | **Telepathy**: Target must make a **Mind Save** at Difficulty of your **Mind Level** -> +1 per boost. If they fail, you can read their thought and project mental images to their mind. This can be used to inflict Stress on target. Make subsequent tests as necessary.                                                                                           |
| 1     | **Telekinesis**: Telekinetically manipulate 1-> 2-> 4-> 8 objects at **Moderate** ->  **Long** -> **Extreme** range. Object can be manipulated normally as if you had a Body attribute equal to your Mind or more if you boost.                                                                                                                                     |
| 1     | **Kinetic Force Impulse**: Launch a powerful impulse of kinetic force inflicting DC 2-> 3-> 4-> 5 Forceful Impact at **Short** -> **Moderate**-> **Long**-> **Extreme** range, with a shape of: **cone (90)** ->  **cone(180)** ->  **circle**.&nbsp                                                                                                                |
| 2     | **Force Sling**: Launch small objects as projectiles: test `Ranged Combat x Mind` to attack with them. Projectiles inflict 3-> 4-> 5-> 6 damage at Short-Moderate range. You can boost to add tags: Soft Piercing, Full Auto, Double Hit                                                                                                                            |
| 2     | **Scan**: Invade the mind of any target within your line of sight. Target may resist as with _Telepathy_. You can access their memories and subconcsious thoughts. The target takes Stress and you can cause them serious harm: Inflict a Minor Wound per Boost.                                                                                                    |
| 2     | **Suggestion**: Target may resist with a test of `Psychology x Mind` at Difficulty of your **Mind Level** -> +1 up to +3. If they fail, they will succumb to your suggestion and perform non-threatening actions equal to 1 ->.                                                                                                                                     |
| 2     | **Thermokinesis**: Rapidly change temperature in an area, which can cause fires or snuff them out. You can also boost **Impulse** to **Burn** or **Stun** targets.                                                                                                                                                                                                  |
| 2     | **Shield**: Counteract _Impulse_ by making a contested test. The victor of the test can inflict Impulse damage. You can also use the shield to block melee or projectile attacks, even stop vehicles. Add 1 Ultra Mitigation +1 per Boost for Short Duration.                                                                                                       |
| 3     | **Hallucinate**: Create vivid, lifelike hallucinations that can affect several subjects. Targets must initially test `Psychology x Mind` at Difficulty equal to your **Mind Level** +1 per Boost to attempt resist the effects. Affects targets in an area of **Short** -> **Moderate** -> **Long** -> **Extreme** radius for a **Moderate** -> **Long*** duration. |
| 3     | **Mind Control**: Difficulty 4. Make an opposed test against target's `Psychology x Mind`. If you succeed, the target is under your control for a Moderate duration and must obey all your orders. They may attempt to resist again if you force them to act in a way that is severely against their nature or risks their life.                                    |
| 3     | **Kinetic Detonation**: Detonate a psionic explosion centered around you. The area of effect is **Moderate** ->  **Long** ->  **Extreme** and you inflict damage at Forceful Impact at DC of Mind Level + Resolve + Boost that will Stun the targets.                                                                                                               |
| 3     | **Psionic Scream**: Detonate a psionic explosion centered around you. The area of effect is **Moderate** ->  **Long** ->  **Extreme**. Each target in the area is Stunned and take 1 Stress. For each Boost you inflict additional stress.                                                                                                                          |



### Mimic

#Cybertech #Nanotech #Biotech #Unsafe 

You can reconstruct your facial features and mimic voice and behavioral patterns of a person, or create entirely new personalities and faces by combining known patterns and features. Depending on the used technology, the implementation of the augment is somewhat different, but the principle remains the same.


| Level | Effect                                                                                                                  |
|:----- |:----------------------------------------------------------------------------------------------------------------------- |
| 1     | Reconstruct your face from sufficient sample footage to copy someone's likeness, or to alter your identity.             |
| 2     | Speech pattern mimicry allows you to perfectly match someone's voice and accent, or to alter your own voice pattern too |
| 3     | Behavioral pattern mimicry alters your personality to perfectly mimic a subject. You can fully become someone else.     |

### Mobility System

#Cybertech #Nanotech 

Advanced Mobility enhancement system enhances the cyborg's movement capabilities. Requires activation. Once activated, effects last for **Moderate** duration.

| Level | Effect                                                                                                                         |
|:----- |:------------------------------------------------------------------------------------------------------------------------------ |
| 1     | +1D in Mobility Tests.                                                                                                         |
| 2     | +2D in Mobility Tests. Jump height is doubled                                                                                  |
| 2     | Roller blades: Activate integrated roller blades for 1 Energy. Velocity scale is increased.                                    |
| 3     | +3D in Mobility Tests.                                                                                                         |
| 3     | Jumpjets: Activate for 1 Energy to safely land from any distance to momentarily hover in place or further improve jump height. |

### Regeneration

#Cybertech #Nanotech #Biotech

A system for manufacturing and coordinating an army of nanites programmed to repair physical damage. Regeneration can be activated via subconscious functions to automatically initiate when the you're wounded. The effects will take a Short duration to complete.

| Level | Effect               |
|:----- |:-------------------- |
| 1     | Heal a Minor Wound   |
| 2     | Heal a Major Wound   |
| 3     | Heal a Lethal Wound. |

### Smart Weapons

#Cybertech #Nanotech 

You can interface with Smart Weapons and ordnance and use guided projectiles and access their combat data. Any Personal Weapons are automatically modified to be compatible, but random weapons picked from dead enemies are probably not compatible. Even if they were, Smart Weapons have high security and need to be hacked before they can be used.

>[!warning]
>Smart Weapons are only compatible with conventional firearms and slow projectile launches, such as missile launchers or grenade launchers and cannot be used with Gauss weapons, Laser weapons or Plasma weapons.

| Level | Effect                                                                                                                                                                                                            |
| :---- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Gain +1D on Ranged Combat tests for **Moderate Duration** when using Smart Weapons, but you can only designate one target at a time. Ordnance provide you telemetry data for up to 300 meters.                    |
| 2     | Gain +2D on Ranged Combat tests when using Smart Link and you can handle up to 3 targets. Maximum effective distance is 1km. You can use the Bullet Cam feature to gain visual feedback as the ordnance travels.. |
| 3     | Gain +3D on Range Combat tests when using Smart Link and you can handle up to 6 targets. Smart Link maximum effective distance is 3km.                                                                            |


### Swarm

#Cybertech #Nanotech 

Utilize a swarm of special micro drones to spread out and monitor large areas, or to harass, disrupt or attack enemies. Swarm persists for a Moderate duration or until destroyed.

| Level | Effect                                                                                                                                                               |
| :---- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Swarm Size 1. Long Range. Swarm has body of D6 and it can affect the environment. Swarm take -2 Damage from conventional attacks and normal damage from AOE attacks. |
| 2     | Swarm Size 2 Body D8. Swarm can attack individual targets, ignoring all armor and cover that is not Sealed or Vacuum proof to automatically inflict a Major Wound.   |
| 3     | Swarm Size 3. Swarm can self-destruct inflicting Explosive or EMP damage with DC of Size+1 within Medium radius.                                                     |

### Targeting System

#Cybertech #Nanotech 

Enables extremely high damage and precision in combat by extreme calculation power, which is displayed as slowed down time and trajectory tracking. Effective in both close combat and ranged combat.

Using Targeting System costs 1 Energy, but you can keep spending Energy after the first re-roll to gain further re-rolls, up to the limit indicated by Augment Level.

| Level | Effect                              |
|:----- |:----------------------------------- |
| 1     | Re-roll an attack test.             |
| 2     | Re-roll an attack test twice.       |
| 3     | Re-roll an attack test three times. |

### The Crucible

#Cybertech #RadicalX

The poetically named Crucible is little more than a Suicide Bomb, a dangerously modified Reactor Core built to overload. It comes with a dead man's switch and the ability to trigger the device remotely by high-ranking operator. It is weapon whose delivery system is the unfortunate person picked for Crucible duty that day in the daily Radical X lottery where everyone loses.

A Black Box has 50% chance of surviving the Crucible detonation.

| Level | Effect                                                                                                                                                                                                                                              |
|:----- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Gain 4 Energy Points. When you die or Crucible is remotely triggered, it Detonates exploding your body to several small pieces and causing 1 DC damage per remaining Energy Point. Area of Effect depends on DC: 1-4 Small, 5-7 Moderate, 8+ Large. |
| 2     | Gain 6 Energy Points. Detonation inflicts EMP damage.                                                                                                                                                                                               |
| 3     | Gain 8 Energy Points. You can choose when to detonate the Crucible.                                                                                                                                                                                 |


### Weapon Systems

#Cybertech

You can integrate a variety of concealable weaponry to the frame. Larger, more complicated systems may require transformation (Short duration) before the weapon can be utilized. Each Weapon System is usually custom built to the user's specifications, and even though many pick from one of the available common blueprints, in truth there are countless variations and modifications of each and plenty of unique systems as well. Each Weapon System is its own augment and you can take multiple Weapon Systems. Weapon Systems can also be switched whenever you are upgrading your Frame.


| Level | Effect                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | **Finger Guns**: Not a joke. But rather 10 single-shot small caliber guns built into your fingers. A favorite for assassins, and also when you need that cool finishing move. The basic Finger Guns are Breech Loaders, so you need some time to reload them all. **Ranged Weapon DC 2, Close to Short Range, Low Recoil, 10 Shots. Full Auto if 5 or more guns are fired simultaneously. Max Hits = Shots Fired, 1 Bulk**.                                                                                                             |
| 1     | **Fingertip Lasers**: Another assassin favorite, 10 laser pointers in fingertips that can slice and dice whatever you point at. **Melee Weapon, DC 2, Accurate, Fast**,.                                                                                                                                                                                                                                                                                                                                                                |
| 1     | **Sidearm Holster**: Holster your sidearm and some backup ammo, most commonly fit in inside a prosthetic leg. It takes less than a second to open the holster and some individuals are known to have customized their holster with variety of functions, like a launcher spring that shoots the gun straight up to your hand - if you can catch it.                                                                                                                                                                                     |
| 1     | **Power Knuckles**: Small gravity generators integrated to arms that focus their force to your knuckles whenever you punch someone. **Melee Weapon, DC 3, Forceful**                                                                                                                                                                                                                                                                                                                                                                    |
| 1     | **Razor Claws**: A pair of retractable hardened steel claws for a surprise slice and dice that can easily penetrate soft body armor. **Melee Weapon, DC 2, Fast, Soft Piercing**                                                                                                                                                                                                                                                                                                                                                        |
| 2     | **Laser Eyes**: A pair of low-powered laser beamers inside your skull for that extra serious look that can kill. **Ranged Weapon, DC 2, Short-Moderate Range, Low Recoil, Accurate, Full Auto**                                                                                                                                                                                                                                                                                                                                         |
| 2     | **Nano Blades**: A set of monomolecular blades commonly attached to your forearms (can be dual wielded). The blades can extend either forward or backward enabling flexible slicing and dicing and they are very good at cutting through soft armor. **Melee Weapon, DC 3, Hard Piercing**                                                                                                                                                                                                                                              |
| 2     | **Gun Machine Arm**: Despite the stupid name, Gun Machine Arm is an effective small caliber machinegun integrated into your arm. **Ranged Weapon, DC 3, Moderate-Long Range, Moderate Recoil, Full Auto, 2 Bulk**                                                                                                                                                                                                                                                                                                                       |
| 2     | **Leg Sniper**: A large caliber sniper rifle built right into your leg. Don't forget to do your stretches. **Ranged Weapon, DC 6, Extreme Range, High Recoil, Single Shot, 3 Bulk**.                                                                                                                                                                                                                                                                                                                                                    |
| 2     | **Knee Shot**: A short-barrel shotgun integrated to your knee. The weapon system's original creator was an expert Muay Thai fighter who wanted to incorporate some "extra kick" to her knee strikes. **Ranged Weapon, DC 4, Close-Short, Moderate Recoil, Double Hits,  2 Bulk**                                                                                                                                                                                                                                                        |
| 2     | **Shock Fist**: A powerful tazer built into your fists, activated the moment you hit something hard. **Melee Weapon, DC 5, Stun, Forceful**                                                                                                                                                                                                                                                                                                                                                                                             |
| 3     | **Plasma Arm**: A built-in supercharged plasma cannon right in your arm. **Ranged Weapon, DC 7, Short-Moderate Range, Moderate Recoil, Single Shot, Soft Piercing 3 Bulk**                                                                                                                                                                                                                                                                                                                                                              |
| 3     | **NEMESIS Missile Array**: A Multi-Missile launcher integrated to your back. Holds 6 missiles that can be launched individually or simultaneusly. Comes with a custom targeting system that enables you to assign target for each missile separately. Missiles need to be reloaded from your backside after opening a backplate protecting the ordnance and operation will take a Moderate amount of time, so better make each shot count. **Ranged Weapon, DC 5 Explosion, Moderate-Long Range, Short Radius, Multi-Shot (6), 3 Bulk** |
| 3     | **Railgun arms**: Your both arms transform into a single massively powerful railgun capable of piercing through the hardest armor. You can't do much else than shoot while transformed, but boy does it shoot. **Ranged Weapon, DC 8, Extreme Range, Extreme Recoil, Single Shot, Accurate, Hard Piercing, 3 Bulk**                                                                                                                                                                                                                     |
| 3     | **Arm Minigun**: A bulky arm that can transform into a powerful minigun that can spread lead like there's no tomorrow. **Ranged Weapon, DC 4, Moderate-Long Range, Extreme Recoil, Full Auto, Double Hits, High Capacity, 3 Bulk**                                                                                                                                                                                                                                                                                                      |
