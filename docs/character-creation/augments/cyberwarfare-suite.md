---
title: Cyber Warfare Suite
version: 1
tags:
  - Cybertech
  - Nanotech
  - Augment
---
A specialized suite of embedded hardware and software for advanced offensive hacking in combat.

**Combat Hacks** are single-use deployable software designed to target a particular device. They are autonomous, smart and extremely effective, utilizing AI-optimized multiple attack vector strategy to overcome target's defenses. After detecting a combat hack, the target system adapts to it and the same hack cannot be used again against the same system. If a system is connected to other systems, it will usually automatically distribute defensive analytics data making the combat hack useless against any connected system. This effectively makes each hack a single use tool. Characters utilizing combat hacks are presumed to be knowledgeable enough to update their combat hacks during downtime, so you can always refresh your Apps between scenes.

**System**
- **Activate:** Spend 1 Energy and a **Hack Slot** to Activate a Hack as an Instant Action. Each activated Hack affects your [[stats#Multitasking|Multitasking]] limit for that turn.
- **Upload Test:** Test `Hacking + Cyber`, against target’s [[stats#Cyber Defense|Cyber Defense]]. If you succeed, the Hack is activated in full effect. On failure, you lose the spent slot anyway.
- **Hack Slots:** Three **Grades** of Hack Slots (Basic, Advanced, Ultra) represent availability of unique hacking modules.
	- Each Slot can only activate a hack of corresponding Level or lower.
	- Each Slot can only be used once per scene
	- You don’t need to determine which apps are in which slots, all you need is a free slot
	- You can use another slot to activate a Hack multiple times. Each Slot represents a different variant
- **Cyber Damage:** Cyber Damage is malignant feedback loop or a sensory shock that disorients and causes extreme discomfort. Cyber Damage cannot be soaked or mitigated by armor and it is unaffected by target’s [[stats#Damage Threshold|Damage Threshold]]. But then again, it is rarely too much damage at once, and is only harmful when accumulated.

### Level 1

- **Basic Hacks:** You have access to all Basic Hacks.
- **Hack Slots**: 2 Basic
- **Enhance Cyber Defense:** In addition to [[stats#Cyber Defense|Cyber Defense]] stat, you can test `Troubleshooting + Cyber` to defend against active cyber attacks.

| Basic Hacks           | Effect                                                                                                                                                 |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Targeting Malfunction | Target is [[maimed]] for a Moderate duration                                                                                                           |
| Mobility Malfunction  | Target is [[crippled]] for a Moderate duration                                                                                                         |
| Glitch                | Target device will glitch next time its activated, stopping it from working. The following activation will work normally.                              |
| Open/Close            | Can open/close any door, hatch, window or the sort.                                                                                                    |
| Operate               | Operate any vehicle, industrial equipment or the sort.                                                                                                 |
| Short Circuit         | Minor feeback loop, causing some discomfort. Target takes 1 [[harm]]                                                                                   |
| Noise Feedback        | Override comms channels. Everyone in vicinity is [[dazed]] for Short duration and takes [[shock\|1 shock]].                                            |
| Distract              | Create a simulated sensory experience that distracts the target cyborg. They take [[complication-fail\|Fail 1]] on alertness tests for short duration. |


### Level 2

- **Advanced Hacks:** You have access to all Advanced Hacks.
- **Hack Slots**: 4 Basic, 2 Advanced
- **Predictive Algorithm:** You gain a single free re-roll on **Upload** test
- **Effect: Minor Cascade (2 EP):** The hack spreads to another target accessible by the same network


| Advanced Hacks | Effect                                                                                                                               |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Synapse Burn   | Target takes 1 [[trauma]]                                                                                                            |
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

| Ultra Hacks         | Effect                                                                                                                                                                                                             |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Safety Override     | Bypass any safety overrides on devices such as doors, loudspeakers, elevators. You can command the device to behave in a lethally unsafe manner. Good for laying out lethal traps made of doors or garbage chutes. |
| Madness             | Override target’s sensory feed with disturbing, maddening hallucinations. Target immediately takes [[stress\|5 stress]] and is completely detached from reality for a Moderate Duration.                           |
| Torture             | Inflict simulated pain. Target immediately takes [[damage-pain\|4 Pain Levels]] which disappear after a short duration.                                                                                            |
| Multi-Vector Attack | Target is affected by 4 lower level Hacks.                                                                                                                                                                         |
| Advanced Power Hack | Any Advanced Hack, except its effects are *doubled* in magnitude.                                                                                                                                                  |
| Kill                | Override target’s senses with neural decaying feedback loop. They are in unbearable agony and take [[fatal\|1 Fatal]] damage. This is extremely disturbing. You take [[engrams#Corruption\|1 Corruption]].         |