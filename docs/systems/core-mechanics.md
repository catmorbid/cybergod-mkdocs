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

**Instant** is a fraction of a second, or at most a second. Enough to affect a single Action during a *round*.
**Short** interval is equivalent to one round of action or combat, equivalent to a few seconds.
**Moderate** interval lasts an entire *scene*.
**Long** interval lasts until you play some *downtime*, usually several scenes or an entire game session.

#### Distance

Distance is a measurement of distance between targets. Can be used in combat to determine how easy or hard it is to hit a target, or to measure distance during a chase.

**Close** distance means you can touch the object or entity referenced to.
**Short** distance can be traversed easily in one round. No action required.
**Moderate** distance requires some effort to traverse. An action with **1 Effect** is enough to reach it. 
**Long** distance means the target is quite a bit of distance away. You can reach Long distance with an action and at least **2 Effects**.
**Extreme** distance needs more than one action to catch up to.

#### Velocity

Velocity is an abstraction of how fast something is. Acceleration, mass and kinetic energy are all accounted for. The examples below are described relative to a human being on foot. When you compare fighter jets or space crafts, the examples would be very different.

**Low** Velocity means something is moving slowly enough to observe easily with human eye. Human could easily run beside the object.
**Moderate** Velocity means something is moving at a rate roughly equivalent to a sprinting human. Vehicles tend to go fast but you really need to keep up your pace to catch them on foot.
**High** Velocity is equivalent to a fast moving vehicle, such as a GravCar speeding away. You can see them, but attempting to reach them on foot would be desperate.
**Ultra** Velocity is closing to super sonic speeds. You don't have any hope to reach this velocity on foot.
## Tests

A Test is sometimes called upon when you need to figure out whether a character can do something that is not within basic functions of a human (or a cybernetic) being. Complicated tasks that require years of learning are represented by the characters' **Skills** and **Attributes**, which are the core elements of a Test.

Each skill is also linked to an **Aptitude**, which is like a skill category, and the skill level is always the sum of the actual skill and the linked Aptitude. If the character doesn't have any points in the actual tested skill, they can always use the linked Aptitude.

Tests are noted as `Skill x Attribute`, where Skill determines the number of dice to roll, and Attribute the type of Die used. This generally results in a Dice Pool of 1 to 7 dice. The type of Die is determined by the Attribute used in the test, and can be D6, D8, D10 or D12.

### Simple Test

Roll the dice and count **successes**:

- Count 1 *Success* for a roll of 5 or higher, or
- Count 2 *Successes* for a roll of 10 or higher

You need to beat the **Difficulty** of the test to actually succeed. If you succeed, you gain **One (1) Effect Point (EP)** plus another for each additional success rolled. Spend Effect Points to determine the actual outcome. Most Tests have a so called *Basic* effect which simply allows you to do what you set out to do in the first place for just 1 Effect Point, but GM may present additional Effects, or simply decide what happens based on how many EP you gained.

> Janey must beat a Hard test of `Investigation x Mind`. She rolls 3D12 gaining 10, 6 and 9. That's total 4 successes, which earns her 2 Effect Points.

### Opposed Test

When two characters roll dice against each other, they are making an Opposed Test. The outcome of one test will be highly dependent on the outcome of the other test. Whoever has more successes is the victor, with a margin equal to the difference between the results. So if you beat your opponent by one success, you succeed with a one success.

### Difficulty

| Difficulty | Success Threshold | % 3D6 | %3D8 | %3D10 | %3D12 |
| ---------- | ----------------- | ----- | ---- | ----- | ----- |
| Easy       | 1                 | 70%   | 88%  | 95%   | 98%   |
| Moderate   | 2                 | 26%   | 50%  | 73%   | 88%   |
| Hard       | 3                 | 4%    | 13%  | 34%   | 59%   |
| Very  Hard | 4                 | -     | -    | 11%   | 24%   |

**Difficulty** determines the **Success Threshold** for a test, which is the number of success required to actually succeed. When making Opposed tests, where there is an opponent who tests their own skills, Difficulty indicates the margin by which you need to succeed, in order to actually succeed.

> E.g. a Moderately difficult test means that on an opposed test you need 2 successes more than your opponent to actually succeed.

### Complications

Complications are optional challenges that may be present when attempting a Test. GM can introduce complications on any tests, presenting them as a potential harm that can happen unless dealt with. Players are free to choose whether they want to deal with the complication, or face the consequences.

Each complication comes with a rating of 1-5 depicting how difficult the complication is to overcome. In practice this means that to overcome the complication, you need to spend that many additional successes, which can't then be used to beat the difficulty, and won't count for *Effect Points*.

It is also possible that multiple complications apply to a single test, but having more than three complications makes tracking them really difficulty, so having more than three complications on a single test is not recommended.

> [!Example] Complications example
>
> Marko is trying to hack into a Syndicate server to obtain some cargo manifest data he needs for a client. He's testing `Hacking x Cyber` and can roll 4D10. But GM tells him that the while the server itself only has Moderate security, there is a local Sys Op monitoring the situation, which presents a 1-point complication. If Marko fails to overcome the complication, the Sys Op will detect him and will begin countermeasures and a trace, which might eventually see Marko's location compromised...

### Effects

You gain a number of **Effect Points (EP)** upon beating the difficulty of a test equal to 1 + any successes in excess of the *Success Threshold* determined by difficulty. EP can be spent on various *Effects* to determine the outcome of the test. Each Test will have some sort of **Basic Effect**, that will always cost just 1 EP, allowing the character to simply do what they set out to do. Additional Effects allow the character to somehow improve the outcome, and could be as as simple as *doing it faster*, or *doing it with style*. You can suggest your own effects, which can cost any number of Effect Points. Many actions listed in the rulebook have some kind of list of Effects that can be used without further debate, but players and GM should feel free to improvise and discuss.

### Modifiers

Different modifiers may apply to a test, either granting or removing dice. Generally the total number of modifiers should not exceed +/- 3 Dice. Regardless, maximum number of dice to roll is 10, and minimum is zero. If you don't have dice, you fail automatically.

## Saves
A Save is a simplified test where you typically roll one or more dice to *avoid* certain effects. If you roll the *highest* face on the die, the save will fail, otherwise it will succeed. E.g. a 10 on a D10. Saves can be rolled using any *attribute*, but there are also special saves where a fixed die type is used.

When a Save is noted a difficulty rating is usually included, meaning how many dice you need to roll on the save. The more dice, the more difficult it is.

Some types of common saves:

- **Ammo Save**: Roll a D6 to see if you're out of ammo and need to reload.
- **Knockdown Save**: Roll one or more Body dice to resist being knocked down or knocked back, e.g. thrown out of a window.
- **Death Save**: Roll **Body** for each Lethal wound at start of combat round to see if you die from your wounds.
- **Evasion Save**: Roll **Reflex** to avoid the worst when a trap is triggered or take cover when caught under fire.
- **Mental Save**: Roll **Mind** to maintain your cool when succumbed to stressful situations, horrors or mind manipulation.
- **Stress Save**: Roll one or more **Stress Dice** to resist mental breakdown.