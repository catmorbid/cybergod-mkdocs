---
title: Core Systems
---
## Structure of play

Gameplay is structurally divided into few components, each serving a specific purpose.

**Game Session** takes place when players and Game Master gather together to play the game. A game session usually lasts for several hours in real time. During a game session the Game Master and Players create a narrative. The Game Master sets the **Scene**, but the players each control a **character** and have full control on their thoughts, actions and motivations.

A **Story** is a long narrative arc that has a beginning, and an end. You decide what your stories are about. Stories consist of **Scenes** and **Downtime**, and may span one ore more *game sessions*.

**Scene** is the core structural unit. Each time players explore a location or meet people, they enter a new scene. Whatever happens in that location is what defines the contents of the scene. A scene can be **freeform** where players interact with the environment in non-specific order, or it can be played out in a more structured **turn-based** order, in which case the action is divided into **Rounds**.

**Round** is a brief period during which each participant in the scene can take one more more actions. Each party gets their turn to act.

**Downtime** is a flexible unit of time during which the players can do things that do not require elaborate description like boring paperwork to sleeping or spending some R&R with friends. Downtime is usually played out with high abstraction and players do not need to provide a detailed schedule, just point out the highlights for what their character is going to do. A single stretch of downtime can take anywhere from few hours to months, sometimes more.

**Rest** is a specific type of *downtime* where the character can recover from the stresses of their work. Humans typically require some rest period each day.

### Measurements

All measurements are treated as abstractions.

#### Time

Time is measured in abstract intervals, very often to measure the *duration* of something, e.g. how long does an ability take effect.

- **Instant** is a fraction of a second, or at most a second. Enough to affect a single Action during a *round*.
- **Short** interval is equivalent to one round of action or combat, equivalent to a few seconds.
- **Moderate** interval lasts an entire *scene*.
- **Long** interval lasts until you play some *downtime*, usually several scenes or an entire game session.

#### Distance

Distance is a measurement of distance between targets. Can be used in combat to determine how easy or hard it is to hit a target, or to measure distance during a chase.

- **Close** distance means you can touch the object or entity referenced to.
- **Short** distance can be traversed easily in one round. No action required.
- **Moderate** distance requires some effort to traverse. An action with **1 Effect** is enough to reach it. 
- **Long** distance means the target is quite a bit of distance away. You can reach Long distance with an action and at least **2 Effects**.
- **Extreme** distance needs more than one action to catch up to.

#### Velocity

Velocity is an abstraction of how fast something is. Acceleration, mass and kinetic energy are all accounted for. The examples below are described relative to a human being on foot. When you compare fighter jets or space crafts, the examples would be very different.

- **Low** Velocity means something is moving slowly enough to observe easily with human eye. Human could easily run beside the object.
- **Moderate** Velocity means something is moving at a rate roughly equivalent to a sprinting human. Vehicles tend to go fast but you really need to keep up your pace to catch them on foot.
- **High** Velocity is equivalent to a fast moving vehicle, such as a GravCar speeding away. You can see them, but attempting to reach them on foot would be desperate.
- **Ultra** Velocity is closing to super sonic speeds. You don't have any hope to reach this velocity on foot.

## Skill Tests

A Skill Test is called when you need to figure out whether a character can do something that is not within basic functions of a human (or a cybernetic) being.

Skill Tests are noted as `Skill x Attribute`:
- **Skill** is the sum of the *skill level* and its linked *Aptitude level*. Optionally, GM may allow using another *Aptitude* than the one linked to the Skill.
- **Attribute** determines the size of the die to roll ranging from D6 to D12.

This generally results in a Dice Pool of 1 to 7 dice.

### Successes and Effects

Once you have figured out the Dice Pool to roll with, roll the dice and count **successes**:

- Count 1 *Success* for a roll of 5 or higher, or
- Count 2 *Successes* for a roll of 10 or higher

You need to beat the **Difficulty** of the test to actually succeed. If you succeed, you gain **One (1) Effect Point (EP)** plus another for each additional success rolled.

Spend **Effect Points** to determine the actual outcome. Most Tests have a so called *Basic* effect which simply allows you to do what you set out to do in the first place for just 1 Effect Point, but GM may present additional Effects, or simply decide what happens based on how many EP you gained.

### Difficulty

| Difficulty | Success Threshold | % 3D6 | %3D8 | %3D10 | %3D12 |
| ---------- | ----------------- | ----- | ---- | ----- | ----- |
| Easy       | 1                 | 70%   | 88%  | 95%   | 98%   |
| Moderate   | 2                 | 26%   | 50%  | 73%   | 88%   |
| Hard       | 3                 | 4%    | 13%  | 34%   | 59%   |
| Very  Hard | 4                 | -     | -    | 11%   | 24%   |

**Difficulty** determines the **Success Threshold** for a test, which is the number of success required to actually succeed. When making Opposed tests, where there is an opponent who tests their own skills, Difficulty indicates the margin by which you need to succeed, in order to actually succeed.

!!! example
	Janey must beat a Hard test of `Investigation x Mind`. She rolls 3D12 gaining 10, 6 and 9. That's total 4 successes, which earns her 2 Effect Points.

### Opposed Test

When two characters roll dice against each other, they are making an Opposed Test. The outcome of one test will be highly dependent on the outcome of the other test. Whoever has more successes is the victor, with a margin equal to the difference between the results. So if you beat your opponent by one success, you succeed with a one success.


!!! example
	a Moderately difficult test means that on an opposed test you need 2 successes more than your opponent to actually succeed.

### Complications

Complications are optional challenges that may be present when attempting a Test. GM can introduce complications on any tests, presenting them as a potential harm that can happen unless dealt with. Players are free to choose whether they want to deal with the complication, or face the consequences.

Each complication comes with a rating of 1-5 depicting how difficult the complication is to overcome. In practice this means that to overcome the complication, you need to spend that many additional successes, which can't then be used to beat the difficulty, and won't count for *Effect Points*. But as long as you overcome the complication, then it won’t come into play.

It is also possible that multiple complications apply to a single test, but having more than three complications makes tracking them really difficulty, so having more than three complications on a single test is not recommended.

!!! Example Complications example
	Marko is trying to hack into a Syndicate server to obtain some cargo manifest data he needs for a client. He's testing `Hacking x Cyber` and can roll 4D10. But GM tells him that the while the server itself only has Moderate security, there is a local Sys Op monitoring the situation, which presents a 1-point complication. If Marko fails to overcome the complication, the Sys Op will detect him and will begin countermeasures and a trace, which might eventually see Marko's location compromised...

### Effects

You gain a number of **Effect Points (EP)** upon beating the difficulty of a test equal to 1 + any successes in excess of the *Success Threshold* determined by difficulty. EP can be spent on various *Effects* to determine the outcome of the test. Each Test will have some sort of **Basic Effect**, that will always cost just 1 EP, allowing the character to simply do what they set out to do. Additional Effects allow the character to somehow improve the outcome, and could be as as simple as *doing it faster*, or *doing it with style*. You can suggest your own effects, which can cost any number of Effect Points. Many actions listed in the rulebook have some kind of list of Effects that can be used without further debate, but players and GM should feel free to improvise and discuss.

### Modifiers

Different modifiers may apply to a test, either granting or removing dice. Generally the total number of modifiers should not exceed +/- 3 Dice. Regardless, maximum number of dice to roll is 10, and minimum is zero. If you don't have dice, you fail automatically.

A positive modifier may be referred to as **Advantage** or **Bonus**, while a negative modifier may be called **Disadvantage** or **Penalty**.

### Rerolls

Sometimes you have the option to spend a **Reroll** on a test vastly improving your chances of success or improving the outcome. Each Reroll allows you to pick any number of rolled dice and roll them again. You must keep the new results. When rerolling a skill test, it makes most sense to only re-roll dice that did not generate any successes, otherwise you will risk those dice producing zero successes.

!!! example
	Kris is facing a high-risk negotiation and needs to convince an enemy mercenary to stand down before the situation escalates. GM states it's a Hard `Persuasion x Mind` test, so Kris rolls 6D10 and gains 3, 4, 6, 2, 1, 1, generating only 1 success out of the 3 required. Facing a failure, He decides to spend a point of Resolve to reroll the five failed dice, rolling 7,10,5,2,1 adding 4 successes for a total of 5 successes. That's more than enough to succeed with flying colors.

### Assistance

Another character may provide assistance in a test. The assistant does not roll any dice on their own, but rather awards half (round down) of their **Dice Pool** to the acting character performing the test. The minimum Dice Pool is then 2 for assistant to be of any use to the acting character.

The assistant may also utilize a different skill than the acting character, if it fits the situation. You can suggest GM how your character would be able to assist another character, suggesting a skill to use, but the GM has the final call if such assistance works in the situation at hand.

## Resource Check

A Resource Check is used to measure consumption of various resources such as **Ammo** or personal **Assets**. It's a quicker and simplified form of test where degrees of success do not matter. A resource Check can be noted simply as `Check (resource)`, e.g. `Check Ammo` to make Resource Check to see if your weapon is running out of ammo.

Resource Check is rolled with **Resource Dice** which are D6, D8, D10 or D12. The number of dice is Total Level of consumption. E.g. If you you currently have 4 points of ammo tracked, spending another ammo means you now roll 5 dice for Resource Check.

If any dice show 1-2 then the check fails. Consequences of failure depend on the measured resource:

Examples:
- **Ammo**: You run out of ammo and must spend a Reload. but usage is cleared.
- **Stress**: you suffer from a mental breakdown, but stress track remains unchanged.
- **Assets** (RP, QC or Influence): You must reduce the usage dice by one step or forfeit the transaction.
- **Energy:** receive a point of *Burn*

If you fail the check, then clear the tracked usage track and start tracking again from zero, if any resources remain.
