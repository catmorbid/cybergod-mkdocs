---
title: Skill Tests
status: new
version: 1
---
!!! info "Skill Test Summary"
	To resolve skill tests:
	
	1. Build Dice Pool (Attribute + Aptitude + Skill + Modifiers)
	2. Roll your dice pool
	3. Count Effect Points based on dice faces
	4. Overcome Complications
	5. Spend Effect Points on Effects to achieve desired outcome
## Syntax
Skill Tests are the most common type of test you need to do. The syntax for a Skill in the rules is usually:

> Test `Skill + Attribute`.

For example: *”Test `Analyze+Mind` to find clues on the crime scene.”*

This test tells you the most important components you need for the test. All you do is add up all relevant dice together, then roll them as one [[#Dice pool]].
 
## Test Dice

Dice used in tests have different number of faces. You will need 4-sided, 6-sided, 8-sided, 10-sided and 12-sided dice; or D4, D6, D8, D10 and D12.

Different statistics are measured with die size, with bigger dice always being better.

Simply roll all dice that are relevant for a skill test, and then count successes based on each die face.

| Die Face  | Outcome        | Tips                                                                                                                     |
| --------- | -------------- | ------------------------------------------------------------------------------------------------------------------------ |
| 3 or less | Failure        | Check these first and put them aside before tallying rest of successes. If you have any re-rolls, start from these dice. |
| 4+        | Single success | Each die can produce a single success.                                                                                   |
| 8+        | Double success | D8, D10 and D12 can produce double success. Check for these after d12.                                                   |
| 12+       | Triple success | Only d12 can produce triple success. Check for these first!                                                              |


### Dice Face Probability

On the following table you’ll find probabilities for rolling a result exactly, as well as the expected successes per dice. Dice Pool probabilities may be difficult to calculate, but this small table may be very helpful with this.

| Die | Failure (1-3) | Success (4-7) | Double (8-11) | Triple (12) | Expected Successes |
| --- | ------------- | ------------- | ------------- | ----------- | ------------------ |
| D4  | 75%           | 25%           | -             | -           | 0.25               |
| D6  | 50%           | 50%           | -             | -           | 0.50               |
| D8  | 37,5%         | 50%           | 12,5%         | -           | 0.75               |
| D10 | 30%           | 40%           | 30%           | -           | 1                  |
| D12 | 25%           | 33%           | 33%           | 8,3%        | 1.25               |

!!! tip "Estimating Chances of Success"
	If want to estimate your chances for success, it’s easiest to use the Expected Success column on the probability distribution table above. Simply add together the Expected Successes from each die type on your dice pool. You should expect to get this amount of successes with good odds. If the result is way less than what you need, then your chances are bad, and if it’s way more than what you need, then your chances are very good.
	E.g. You have a dice pool of `2d8+2d6`. Expected value for your pool is then $2*0.75+2*0.5=2.5$. So if you need 2 successes, then your chances should be pretty good, but for 3 successes there’s some risk involved.

## Dice pool

Every test uses two kinds of dice: **Human Dice**, based on your character’s stats, and **Modifier Dice**, from tools, augments, or allies.

- Up to 3 **Human Dice**
	- *Raw Power* — 1 Attribute Die (Frame)
	- *Talent* — 1 Aptitude Die (Persona)
	- *Expertise* — 0-1 Skill Dice (Persona; or Frame with suitable *Augments*)
- Up to 3 **Modifier Dice**
	- Utility Dice
	- Augment Dice
	- Teamwork Dice

Every test rolls at least 2 dice; **Attribute Die** and **Aptitude Die**. The **Skill Die** is optional as a character without any training in a skill only rolls their Attribute and Aptitude dice.

**Modifier Dice** are entirely optional, but may grant up to 3 dice, split into three types: *Utility Dice*, *Augment Dice* and *Teamwork Dice*, and while different modifiers may be rolled together, you can only selected one source for each type of Modifier Die.

If more than 3 modifier dice were to be applicable on a single test, you must choose which dice to keep and drop the rest.

- **Utility Dice** can be awarded by using tools, equipment, augments, instructions and walk-throughs.
- **Augment Dice** can be gained through use of Augments or unique circumstantial advantages.
- **Teamwork Dice** can be gained by receiving assistance from other characters. You can benefit from up to 3 assistants, any more would just make things more complicated, and they will then “lend” one of their human dice, as appropriate to situation – usually Attribute or Skill Die. A preceding test may be required to coordinate teamwork efforts in order to allow benefiting from the teamwork dice.


!!! Example
	Mick is trying to hack the security system of a Syndicate warehouse to grant the team entry through a secure door. The security system is on an isolated subnet accessible only through an arcane maintenance terminal, preventing remote connect. GM calls for a **Mind + Hacking** test and the GM announces the test has the following *Complications:* **Difficult 2** and **Alarm 1**, meaning Mick has to first assign 2 Effect Points to overcome the Difficulty, or the test fails, and finally there’s an alarm rigged to the system which will go off unless taken care of. Hacking falls under *Technical* aptitude and Mick spends 1 energy to gain D10 Utility Die from his *Hacking Suite* augment, making total dice pool `2D10+2D8`:
	
	 - D10 (Mind)
	 - D8 (Technical)
	 - D8 (Hacking).
	 - D10 (Utility, hacking suite augment)
	 
	 Total Dice Pool is then 2D10 + 2D8. He rolls [4, 7, 4, 6] for total 4 successes, overcoming both the Difficult 2 and Alarm 1 complications with 1 Effect Point to spare, which he spends on **Stealth** effect, cleaning any traces he was ever there. Mick successfully hacks the arcane terminal, granting his team access and preventing any alarms from being triggered. 

## Measuring Success
Any successes gained from dice are summed up together, collectively called **Effect Points**. You can then then spend **EP** to obtain **Effects**, but before being able to do so, you must overcome **complications** linked to the task at hand. Most common type of complication is a generic **Difficult** complication, which must be overcome or the test fails. Some complications may be voluntary, in the sense that not overcoming them does not result in complete failure, but rather some consequence that may present future troubles.

## Dice modification
Some rules may modify the die size. This can be indicated e.g. by stating *Body +1*, meaning that your Body die in this circumstance is one step higher. If the die is always the highest (i.e. D12), then you cannot modify it any further. Dice modification *is not* the common way to modify aspects of challenge in a test, but refer to specific circumstance.

## Challenge

There’s two ways to set up the challenge for a test:

- Assign Complications
- Make an Opposed Test

### Complications

- GM sets complications when they apply
- Complication has a **cost** and **consequence**:
	- *Cost* determines how many Effect Points are required
	- *Consequence* determines what happens when complication is *not* overcome

#### Complication: Difficult
*Difficult* is a complication with varying cost, where the consequence is *failure*, unless overcome. Difficulty is often abbreviated as `DIF [X]` where `[X]` is a number indicating the cost of the complication.

- DIF 0 or No difficulty = Easy
- DIF 1 = Moderate
- DIF 2 = Hard
- DIF 3 = Very hard
- DIF 4 = Extreme

### Opposed Test
Opposed Tests mean that two characters, e.g. PC and NPC both roll their dice competing against one another. They may test the same skill or different skills (opposing skills), depending on circumstance. Whoever rolls most successes wins, but their opponent’s successes are subtracted, acting much like *Difficult Complication*.

!!! Example
	Kris is leading the team making entry into the Syndicate warehouse. The team is going for a stealth approach, following a plan Kris formulated earlier. GM allows a *Callback* and calls Kris to test `Stealth + Mind` – but this is an opposed test against the Syndicate warehouse security chief in charge of handling the security. Kris rolls `D10+2d8` → 8, 7, 5 → 4 successes. The Syndicate security chief rolls `4d8` → 7, 4, 5, 2 → 3 successes. Kris beats the opponent and the team enters the facility following Kris’ meticulously formulated infiltration plan. GM awards the team a D6 augment die to any future tests related to Kris’ plan.

### Stalemates
If you overcome difficulty, but do not generate any Effect Points thereafter, or match your opponent’s successes, then the test is effectively a *stalemate*. You neither succeed, nor you lose. What happens next, is up to the GM to decide, but here are a few options:

- Try again. Perhaps with some sort of penalty for stressing you out.
- Settle on a status quo – maybe it’s time to compromise?
- Sacrifice something – make a personal sacrifice in order to get ahead and win with just single Effect Point. E.g. an equipment can break or maybe you burn a bridge with a (former) ally to get what you want.

## Rerolls
Spend **Rerolls** to 

Sometimes you have the option to spend a **Reroll** on a test vastly improving your chances of success or improving the outcome. Each *Reroll* allows you to pick any number of rolled dice and roll them again. You must keep the new results, even if they’re worse. When rerolling a skill test, it makes most sense to only re-roll dice that did not generate any successes, otherwise you will risk those dice producing zero successes.

!!! example
	Kris is facing a high-risk negotiation and needs to convince an enemy mercenary to stand down before the situation escalates. GM states it's a `Persuasion + Mind` test with `DIF 2`. Kris rolls 2D10+D8 → 6, 4, 3 generating only 2 successes, which is not enough to succeed. Facing a failure, He decides to spend a point of **Resolve** to reroll d10 and d8 (4 and 3) → 8, 1. That’s one double success, which results in total 3 successes. The reroll paid of and Kris succeeds.
