# Cyber Warfare

## Combat Hacks

A Combat Hack is a single-use deployable software designed to target a particular device. They are autonomous, smart and extremely effective, utilizing AI-optimized multiple attack vector strategy to overcome target's defenses. After detecting a combat hack, the target system adapts to it and the same hack cannot be used again against the same system. If a system is connected to other systems, it will usually automatically distribute defensive analytics data making the combat hack useless against any connected system. This effectively makes each hack a single use tool. Characters utilizing combat hacks are presumed to be knowledgeable enough to update their combat hacks during downtime, so you can always refresh your Apps between scenes.

### Upload

`Hacking x Cyber`

Upload a Combat Hack to target device or system. Make a opposing test against the target's **Combat Hack Defense**, or use a flat defense rating. You must have visual on target or some other way of pinpointing their location.

**Effects:**
- **Basic(1)**: Apply app effects to target device or system.
- **Pincer Attack (2)**: You can upload another (different) combat hack of your choice.
- **Man-in-the-middle (2)**: You can intercept any network alerts and defensive analytics transmissions before they're received: The hack can be used again against any other targets, but not against this target.

### Combat Hack Defense

`Troubleshooting x Cyber`

If you can detect a combat hack in time, you can attempt to defend against it by slowing down the progress before it is too late.
**Effects:**
- **Basic(1, repeatable)**: Increase attacker's hack difficulty by 1.
- **Copy (2)**: You can make a copy of the used cyber weapon usable in your own arsenal. The attacker is unfortunately immune to it, but others may not be.
- **Trace(1, repeatable)**: Attempt a trace of the attacker's location. If you succeed you can pinpoint their realspace location.
- **Feedback (2, repeatable)**: You cause feedback damage on the attacker, inflicting a Bruise.

### Apps

Each App is a separate weapon used in Combat Hacking. You can get Apps as part of your Gear, and all Apps are of **Advanced** grade. You maximum App capacity depends on your [[frame#Cyber|Cyber]] attribute level

There are also a few [[gear#Utility Apps|Utility Apps]], which use the same App slots, so you might want to consider those as well.

| App              | Grade    | Effect                                                                                                                               |
| ---------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Open/Close       | Advanced | Can open/close any door, hatch, window or the sort.                                                                                  |
| Operate          | Advanced | Operate any vehicle, industrial equipment or the sort.                                                                               |
| Reboot           | Advanced | Reboots the target device, disabling it for Short duration. A Cyborg cannot use their cyber attributes or augments for the duration. |
| Short Circuit    | Advanced | Target takes a Bruise and is Stunned.                                                                                                |
| Synapse Burn     | Advanced | Target takes a Minor wound                                                                                                           |
| Hallucinate      | Advanced | Inject generated sensory data. Makes them see things and hear things. Target takes 2 Mental Damage.                                  |
| Cripple Movement | Advanced | Target takes 1D penalty on Mobility and Close Combat tests per Success.                                                              |
| Cripple Aim      | Advanced | Target takes 1D penalty on Aim tests per Success.                                                                                    |
| Cripple Senses   | Advanced | Target loses use of one sense for Short duration and takes a -1D penalty on Alertness tests.                                         |


## Cyberjacking

*Cyberjacking* refers to the act of invading an entity’s **Cybernetic Brain**. This essentially allows the attacker to take over the physical functions of the subject, upload devastating neural viruses and inflict all kinds of harm. Cyberjacking is serious breach of a person’s privacy and as such a severely punishable offense.

### Resolution Steps
To engage in cyberjacking, you must first reach the target at close range, then use their neural ports to plug-in to their brain and commence the attack.

Anyone with a cybernetic brain has a neural port and is susceptible to attack. The port may be protected by armor, so you might have to make sure they've taken enough damage to make the port accessible.

**Resolve** cyberjacking as an [[core-mechanics#Opposed Test]]. Attacker tests `Hacking x Cyber` while defender tests `Troubleshooting x Cyber`.

**Compare successes:**
- If *defender* wins, they can counter-attack and become the *attacker* next turn
- If *attacker* wins, they may also attack one of the target's **Cores**, inflicting *1 Core Damage* per Effect

When cyberjacking both attacker and defender are unable to move. The attacker has the upper hand and only if they choose to disengage, the connection can be severed.
#### Core Damage
Core Damage is added to each Core after the attacker succeeds in a Cyberjacking test.
Based on how much damage has been inflicted, you have some options:
- **Crash(3)**: You can crash the node, ceasing the functions it provides.
- **Control(5):** You can control the node and thus affect the functions it provides. E.g. controlling the Sensory Core allows you to access sensory data they provide.

#### Remote Cyberjacking
It is possible to attempt cyberjacking remotely, provided the subject is connected to Cyberweb and you have a trace on their physical location, or via proxy such as with a hard-to-detect drone designed to provide remote cyberjacking access. Attacker however has **Difficulty 2** and complication **Detect Intrusion (2)** on their tests. If the hacker passes the complication, then the subject is unaware of the hacking attempt, although they still roll their defenses normally.

### The Cybernetic Brain

To get started with cyberjacking, we must first understand the Cybernetic Brain. Cybernetic Brain is comprised of 7 Nodes, each controlling certain aspects of the character. 


- **Primary Nexus:** *Primary Access point*, and gateway to external data. Creates Filtered Reality Display for the individual. Primary Nexus is built as a foolproof security layer. Attacking Primary Nexus has added **+2 difficulty**, and it cannot be *crashed*, but controlling Primary Nexus effectively allows tapping into *any* incoming or outgoing data, allowing you to manipulate the data as you see fit.
- **Sensory Core:** Handles raw sensory data from all five senses. Each sense has a separate function. Crashing Sensory Core will block any sensory data, making them completely blind and deaf and unable to use their senses, effectively disabling most subjects.
- **Motor Core:** Handles motor functions. Crashing Motor core effectively paralyzes the subject, while controlling it allows you to control the actions of the target.
- **Logic Core:** Handles cognitive functions and speech. Crashing Logic Core disables the ability to speak and drops **Mind** attribute to D6.
- **Memory Core:** Enhanced memory handling and data storage. Can access memories and any stored data. Crashing Memory Core wipes their short-term memory until that point and disables their access to long-term memories for a **Moderate duration**.
- **Empathy Core:** Controls and monitors emotional status. Disabling Empathy Core removes any emotional response from the character. Personal interests, empathy and ethical consideration are gone, and their primary focus becomes whatever prime objectives are hard coded to their Primary Nexus. E.g. personal survival. Crashing Empathy Core disables use of **Resolve**.
- **Auxiliary Nexus:** Gateway to augmentations. Crashing Auxiliary Nexus will disable all augments.

## System Breach

System Breach covers all kinds of cyber intrusion scenarios from hacking remote servers to breaching security measures in a VR simulation. System Breach is possible as long as you possess any suitable hardware, and does not require special augmentations to do it.

System Breach is often a simple test of `Hacking x Cyber` for as long as the target system is a simple network of devices. Attacking a cybernetic brain on the other hand is covered by [[#Cyberjacking]].

### Resolution Steps

**Goal:** Determine your objective. Each breach should have a purpose. Examples:
- Look for way to activate a locked vault door
- Disable defensive turrets
- Look for critical data
- Install spyware to monitor activity in system

**Difficulty**: More secure systems have higher difficulty and objective may affect this as well. You can roll or pick from the following table, or make your own.

|    1d10    |    System Security                |    Breach Difficulty    |    Complications Roll         |    Data Node Roll    |
|:-----------|:----------------------------------|:------------------------|:------------------------------|:---------------------|
|       1    |    Outdated, vulnerable           |                    1    |    1D6                        | D6                   |
|        2   |    Low, out-of-date               |                    1    |                         2D6   |   D6                 |
|        3   |    Standard, up-to-date           |                    2    |         3D6                   |    D8                |
|       4    |    High-security, top-grade       |                    3    |                         3D8   |    D8                |
|       5    |    Military-grade                 |                    4    |                        3d10   |    D10               |
|       6    |    Top Secret                     |                    5    |     4d10                      |    D10               |  

#### Complications

Complications may include **IC**, hostile defensive software that attack any invaders, or a Sys Op or Overseer program may be active and can start a trace at your position, unless you're fast enough.

You can roll on the table below for random complication. Use D6 or D8 for milder effects. By default each complication is worth 1 point, but if you roll any twice or more, you can increase the cost of the complication.

| 1D10 | Breach Complication | Effect          |
|:---- |:------------------- |:--------------- |
| 1    | IC Class 1          | Minor Wound     |
| 2    | Junior Sys Op       | 2d8 Trace test  |
| 3    | IC Class 2          | 2 Minor Wounds  |
| 4    | Midior Sys Op       | 4d8 Trace test  |
| 5    | IC Class 3          | 3 Minor Wounds  |
| 6    | Senior Sys Op       | 4d10 Trace test |
| 7    | Black IC Class 1    | Major Wound     |
| 8    | IC Class 4          | 4 Minor Wounds  |
| 9    | Elite Sys Op        | 5d12 Trace      |
| 10   | Black IC Class 2    | 2 Major Wounds  | 

#### Trace Test

**Trace** test is System Overseer's `Investigation x Cyber` test vs. the hacker's `Stealth x Cyber`. If the Sys Op wins, they have just pinpointed the hacker's physical location and may proceed to send some security forces to deal with them.

#### Bonus Effects

If you succeed well enough, you could aim for one or more bonus objectives. They vary but may include e.g. valuable data or any other suitable benefits. GM will tell you what is available. Sometimes there's nothing extra to gain, while at other times there's plenty.

**Bonus Data:** You can roll valuable data on the following table, *if available*. Use D6, D8 or D10 for a milder potential value.

| 1D12 | Data                   | Effect           |
|:---- |:---------------------- |:---------------- |
| 1    | Useless employee logs  | None             |
| 2    | Useless executive logs | None             |
| 3    | Financial data         | 1 Merit          |
| 4    | Crypto Bits            | 2 Merits         |
| 5    | Fraud Evidence         | 3 Merits         |
| 6    | Humiliating Evidence   | 4 Merits         |
| 7    | Conspiracy Evidence    | 1d12 Merits      |
| 8    | Convicting Evidence    | 10 Merits        |
| 9    | Stolen Crypto Art      | 2d10 Merits      |
| 10   | Military Research      | 1 Upgrade Point  |
| 11   | Cybernetics Research   | 2 Upgrade Points |
| 12   | Faction Secrets        | Unknown          |