---
title: Cyber Warfare Suite
version: 1
tags:
  - Cybertech
  - Nanotech
  - Augment
---
A specialized suite of embedded hardware and software for advanced offensive hacking in combat.

**Combat Hacks** are single-use deployable software designed to target a particular device. They are autonomous, smart and extremely effective, utilizing AI-optimized multiple attack vector strategy to overcome target's defenses. After detecting a combat hack, the target system adapts to it and the same hack cannot be used again against the same system. If a system is connected to other systems, it will usually automatically distribute defensive analytics data making the combat hack useless against any connected system.

This effectively makes each hack a single use tool. Characters utilizing combat hacks are presumed to be knowledgeable enough to update their combat hacks during downtime.

**System**
- **Activate:** Spend 1 Energy and a **Hack Slot** to Activate a Hack as an Instant Action. Each activated Hack affects your [[stats#Multitasking|Multitasking]] limit for that turn.
- **Upload Test:** Test `Hacking + Cyber`, against target’s [[stats#Cyber Defense|Cyber Defense]]. If you succeed, the Hack is activated in full effect. On failure, you lose the spent slot anyway.
- **Hack Slots:** Three **Grades** of Hack Slots (Basic, Advanced, Ultra) represent availability of unique hacking modules. Each Slot has one unique single-use Combat Hack stored. It can only be used once, before target and networked devices adapt to it, but you can have multiple variant versions of each hack, that work multiple times.
	- Each Slot can only activate a hack of corresponding Level.
	- Each Slot is “lost” until you can recover them
	- You don’t need to determine which apps are in which slots, all you need is a free slot of correct Grade.
	- Hacks *can* be used multiple times per round, but each activation requires another slot.
	- **Recovering Hack Slots:** You need to spend some [[structure|Downtime]] to refresh your Hack Slots. This is usually impossible mid-mission. GM may allow you to take a full scene action with accompanied skill test (situational) to attempt and refresh your slots, but full recovery might not be possible in limited time.
- **Cyber Damage:** Cyber Damage is malignant feedback loop or a sensory shock that disorients and causes extreme discomfort. Cyber Damage cannot be soaked or mitigated by armor and it is unaffected by target’s [[stats#Damage Threshold|Damage Threshold]]. But then again, it is rarely too much damage at once, and is only harmful when accumulated.

### Level 1

- **Basic Hacks:** You have access to all Basic Hacks.
- **Hack Slots**: 2 Basic
- **Enhance Cyber Defense:** In addition to [[stats#Cyber Defense|Cyber Defense]] stat, you can test `Troubleshooting + Cyber` to defend against active cyber attacks.

| Basic Hacks           | Effect                                                                                                                                                                                                                                                                               |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Targeting Malfunction | Target is [[maimed]] for a Moderate duration                                                                                                                                                                                                                                         |
| Mobility Malfunction  | Target is [[crippled]] for a Moderate duration                                                                                                                                                                                                                                       |
| Glitch                | Target device will glitch next time its activated, stopping it from working. The following activation will work normally.                                                                                                                                                            |
| Open/Close            | Can open/close any door, hatch, window or the sort remotely.                                                                                                                                                                                                                         |
| Operate               | Operate any vehicle, industrial equipment or the sort for a Short Duration.                                                                                                                                                                                                          |
| Short Circuit         | Minor feeback loop, causing some discomfort. Target takes 1 [[harm]]                                                                                                                                                                                                                 |
| Noise Feedback        | Override comms channels. Everyone in vicinity is [[dazed]] for Short duration and takes [[damage-shock\|1 shock]]. You might think you want to spam this constantly, but enemies are more likely to simply mute their channels after the first go, so it’s unlikely to work more than once. |
| Distract              | Create a simulated sensory experience that distracts the target cyborg. They take [[penalties\|Fail 1]] on alertness tests for short duration.                                                                                                                               |


### Level 2

- **Advanced Hacks:** You have access to all Advanced Hacks.
- **Hack Slots**: 4 Basic, 2 Advanced
- **Predictive Algorithm:** You gain a single free re-roll on **Upload** test
- **Effect: Minor Cascade (2 EP):** The hack spreads to another target accessible by the same network


| Advanced Hacks | Effect                                                                                                                               |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Synapse Burn   | Target takes 1 [[trauma]]. Make a [[engrams#Safety Check\|D8 Safety Check]].                                                         |
| Hallucinate    | Inject generated sensory data. Makes them see things and hear things. Target takes 2 [[stress]]                                      |
| Cripple Senses | Target is [[blinded]] for Moderate duration                                                                                          |
| Reboot         | Reboots the target device, disabling it for Short duration. A Cyborg cannot use their cyber attributes or augments for the duration. |
| Sabotage       | Target Device is sabotaged to take a serious malfunction on use. It is permanently disabled for Moderate duration                    |
| Confusion      | Target’s next attack has [[combat-fumble\|Fumble 2]] complication.                                                                   |
| Power Hack     | Any Basic Hack, except its listed effects are *doubled* in magnitude.                                                                |


### Level 3

- **Ultra Hacks:** You have access to all Ultra Hacks. Ultra Hacks cost **2 energy**.
- **Hack Slots**: 8 Basic, 4 Advanced, 2 Ultra
- **Effect: Major Cascade (4 EP):** The hack spreads to 3 additional targets accessible by the same network
- **Adaptive Evolutionary Cloning**: Once per scene, you can recover any spent Hack Slot.

| Ultra Hacks         | Effect                                                                                                                                                                                                                                         |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Safety Override     | Bypass any safety overrides on devices that should definitely have them, such as heavy hydraulic doors, loudspeakers, elevators, vehicles. You can command the device to behave in a lethally unsafe manner. Good for laying out lethal traps. |
| Madness             | Override target’s sensory feed with disturbing, maddening hallucinations. Target immediately takes [[stress\|5 stress]] and is completely detached from reality for a Moderate Duration.                                                       |
| Torture             | Inflict simulated pain. Target immediately takes [[damage-pain\|5 Pain Levels]] which disappear after a short duration. Make a [[engrams#Safety Check\|D8 Safety Check]] on use.                                                               |
| Multi-Vector Attack | Target is affected by 4 lower level Hacks.                                                                                                                                                                                                     |
| Advanced Power Hack | Any Advanced Hack, except its effects are *doubled* in magnitude.                                                                                                                                                                              |
| Kill                | Override target’s senses with neural decaying feedback loop. They are in unbearable agony and take [[fatal\|1 Fatal]] damage. This is extremely disturbing. You take [[engrams#Corruption\|1 Corruption]].                                     |
