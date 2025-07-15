---
title: Skill Tests
status: new
version: 4
---
!!! info "Skill Test Summary"
	To resolve skill tests:
	
	1. Build Dice Pool (Attribute + Aptitude + Skill + Modifiers)
	2. Roll your dice pool
	3. Count Effect Points based on dice faces
	4. Overcome Complications
	5. Spend Effect Points on Effects to achieve desired outcome
## Syntax
Skill Tests are the most common type of test you need to do. The syntax for a Skill in the rules is usually quite simple and will tell you what dice to roll and how difficult the test should be.

> `Difficulty(Cost) Skill + Attribute`

For example: *”Test `Moderate(2) Investigation + Mind` to find clues on the crime scene.”*

This test tells you the most important components you need for the test:
- [[#Test Dice]]: Which dice should you roll (Investigation skill, linked with Analytical Aptitude, and Mind attribute)
- [[#Effects|Effect Cost]]: How many *Effect Points* you need to succeed, indicating how difficult a test is. (2 effect points required to succeed).

If Effect cost is missing, there is probably a list of possible effects to choose from.
 
## Test Dice

Dice used in tests have different number of faces. You will need 4-sided, 6-sided, 8-sided, 10-sided and 12-sided dice; or D4, D6, D8, D10 and D12.

Different statistics are measured with die size, with bigger dice always being better.

Simply roll all dice that are relevant for a skill test, and then count **Effect Points** based on each die face.

| Die Face  | Effect Points | Tips                                                                                                                     |
| --------- | ------------- | ------------------------------------------------------------------------------------------------------------------------ |
| 3 or less | 0             | Check these first and put them aside before tallying rest of successes. If you have any re-rolls, start from these dice. |
| 4+        | 1             | Each die can produce 1 EP.                                                                                               |
| 8+        | 2             | D8, D10 and D12 can produce 2 EP. Check for these after d12.                                                             |
| 12+       | 3             | Only d12 can produce 3 EP. Check for these first!                                                                        |

### Dice Face Probability

On the following table you’ll find probabilities for rolling a result exactly, as well as the expected Effect Points (mean value) generated per die. Dice Pool probabilities may be difficult to calculate, but this small table may be very helpful with this.

| Die | 0 EP  | 1 EP | 2 EP  | 3 EP | Mean EP |
| --- | ----- | ---- | ----- | ---- | ------- |
| D4  | 75%   | 25%  | -     | -    | 0.25    |
| D6  | 50%   | 50%  | -     | -    | 0.50    |
| D8  | 37,5% | 50%  | 12,5% | -    | 0.75    |
| D10 | 30%   | 40%  | 30%   | -    | 1       |
| D12 | 25%   | 33%  | 33%   | 8,3% | 1.25    |

!!! tip "Estimating Chances of Success"
	If want to estimate your chances for success, it’s easiest to use the *Mean EP* column on the probability distribution table above. Simply add together the Means from each die type on your dice pool. You should expect to get this amount of successes with good odds. If the result is way less than what you need, then your chances are bad, and if it’s way more than what you need, then your chances are very good.
	E.g. You have a dice pool of `2d8+2d6`. Mean EP for your pool is then $2*0.75+2*0.5=2.5$. So if you need 2 EP, then your chances should be pretty good, but for 3 EP there’s some risk involved.

## Dice pool

Every test uses two kinds of dice: **Human Dice**, based on your character’s stats, and **Modifier Dice**, from tools, advantages, or assisting allies.

- Up to 3 **Human Dice**
	- *Raw Power* — 1 Attribute Die (Frame)
	- *Talent* — 1 Aptitude Die (Persona)
	- *Expertise* — 0-1 Skill Dice (Persona; or Frame with suitable *Augments*)
- Up to 3 **Modifier Dice**
	- Utility Dice
	- Advantage Dice
	- Teamwork Dice

Every test is roleld with at least 2 dice; **Attribute Die** and **Aptitude Die**. The **Skill Die** is optional as a character without any training in a skill only rolls their Attribute and Aptitude dice.

**Modifier Dice** are entirely optional, but may grant up to 3 dice, split into three types: *Utility Dice*, *Augment Dice* and *Teamwork Dice*, and while different modifiers may be rolled together, you can only selected one source for each type of Modifier Die.

If more than 3 modifier dice were to be applicable on a single test, you must choose which dice to keep and drop the rest.

- **Utility Dice** can be awarded by using tools, equipment, augments, instructions and walk-throughs.
- **Advantage Dice** can be gained through use of Augments or suitable circumstantial advantages.
- **Teamwork Dice** can be gained by receiving assistance from other characters. You can benefit from up to 3 assistants, any more would just make things more complicated, and they will then “lend” one of their human dice, as appropriate to situation – usually Attribute or Skill Die. A preceding test may be required to coordinate teamwork efforts in order to allow benefiting from the teamwork dice.


!!! Example
	Mick is trying to hack the security system of a Syndicate warehouse to grant the team entry through a secure door. The security system is on an isolated subnet accessible only through an arcane maintenance terminal, preventing remote connect. GM calls for a **Moderate (2) Mind + Hacking** test with **Alarm 1** complication: Mick needs 2 Effect Points to succeed, but there’s an alarm rigged to the system which will go off unless taken care of and it costs 1 Effect Point to overcome. Hacking falls under *Adaptive* aptitude and Mick spends 1 energy to gain D10 Utility Die from his *Hacking Suite* augment, making total dice pool `2D10+2D8`:
	
	 - D10 (Mind)
	 - D8 (Adaptive)
	 - D8 (Hacking)
	 - D10 (Utility, hacking suite augment)
	 
	 Total Dice Pool is then 2D10 + 2D8. He rolls [4, 7, 4, 6] for total 4 successes, overcoming the basic cost and Alarm 1 complication, with 1 EP remaining, which he spends on **Stealth** effect, cleaning any traces he was ever there. Mick successfully hacks the arcane terminal, granting his team access and preventing any alarms from being triggered. 

## Measuring Success
Any **Effect Points (EP)** gained from dice are summed up together. You can then then spend **EP** to obtain **Effects**, but you may first wish to overcome any **Complications** linked to the task at hand.

Most other complications may be voluntary, in the sense that not overcoming them does not result in complete failure, but rather some consequence that may present immediate or future troubles. Nevertheless, it's always a good idea to try and overcome all complications.

### Effects
Effects determine the outcome of your test. GM will tell you how many *Effect Points* you need for a particular effect. If you don't have enough, you don't succeed. GM may give the option to buy a lesser, weaker effect instead.

Certain systems, such as [[systems/combat/index|Combat System]] or [[systems/cyber-warfare/index|Cyber Warfare]] already provide a list of Effects you can take, but for any other situation, consult the GM. The Effect cost essentially defines how easy or hard it is to achieve such an Effect.

| Cost | Difficulty | 3D4 | 3D6 | 3D8 | 3D10 | 3D12 |
| ---- | ---------- | --- | --- | --- | ---- | ---- |
| 1    | Easy       | 58% | 88% | 95% | 97%  | 98%  |
| 2    | Moderate   | 16% | 50% | 74% | 87%  | 92%  |
| 3    | Hard       | 2%  | 13% | 40% | 64%  | 78%  |
| 4    | Very Hard  | -   | -   | 14% | 36%  | 56%  |
| 5    | Extreme    | -   | -   | 3%  | 14%  | 32%  |

#### Multiple Effects
As a rule of thumb, you can take multiple effects, as long as they affect different aspects of the outcome. Certain rule systems may defined stricter limits on effects, so you should follow those rules.

!!! example
	Mick is trying to construct a Smart Virus to infect the enemy network and monitor their communications. He wants a Virus that is good at avoiding detection and very effective at bypassing security systems, which should help in making an autonomous viral agent. GM allows this, since the effects clearly affect different aspects of the constructed Smart Virus.

#### Stacking Effects
Certain effects can stack, meaning you purchase multiple effects of same kind. GM decides if stacking is allowed or not. Stacked effects essentially provide a better result.

!!! example
	When using the  [[systems/combat/index|Combat System]] an attack may stack **Hit** effects, resulting in multiple shots or strikes landing on target, improving overall damage.


## Dice modification
Some rules may modify the die size. This can be indicated e.g. by stating *Body +1*, meaning that your Body die in this circumstance is one step higher. If the die is always the highest (i.e. D12), then you cannot modify it any further. Dice modification *is not* the common way to modify aspects of challenge in a test, but refer to specific circumstance.

## Challenge

In addition to determining the cost of the the player’s desired Effect, there are three ways to set up the challenge for a test:

- Assign [[complications|Complications]] – optional narrative consequences to *overcome*.
- Assign [[penalties|Penalties]] – difficulty modifiers due to various [[systems/conditions/index|Conditions]] or circumstances.
- Make an [[opposed-test|Opposed Test]] – test a character’s skills against another character, such as an NPC.

## Handling Failure
A test can fail in many ways: Not scoring enough Effect Points or choosing to overcome complications, but failing the test; or ending up in a stalemate in an [[opposed-test|Opposed Test]]. GM can present players various options, depending on circumstance. Sometimes it’s good to just accept the failure and think of something else.

- **Try again:** Perhaps with some sort of [[penalties|Penalty]] for stressing you out.
- **Fail Forward:** Failure opens another route – perhaps not the optimal route, but a route forward regardless.
- **Sacrifice something:** make a personal sacrifice in order to get ahead and win with just single Effect Point. E.g. an equipment can break or maybe you burn a bridge with a (former) ally to get what you want.
