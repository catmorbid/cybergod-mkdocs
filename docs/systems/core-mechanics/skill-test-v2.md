---
title: Skill Tests
version: 2
---
Skill Tests are the most common type of test you need to do. The syntax for a Skill in the rules is usually:

> Test $Skill + Attribute$.

For example:

!!! Example
 	Test `Analyze+Mind` to find clues on the crime scene.

This test tells you the most important components you need for the test. All you do is add up all relevant dice together, then roll them as one [[#Dice pool]].
 
## Dice

In typical **Skill Test** you roll one or more dice of different sizes. You need quite a bit of dice to play the game, suggested amount is at least three of each standard die from 4 to 12 faces, i.e. d4, d6, d8, d10 and d12. 

Simply roll all dice that are relevant for a skill test, and then count successes based on each die face.

| Die Face  | Outcome        | Tips                                                                                                                     |
| --------- | -------------- | ------------------------------------------------------------------------------------------------------------------------ |
| 3 or less | Failure        | Check these first and put them aside before tallying rest of successes. If you have any re-rolls, start from these dice. |
| 4+        | Single success | Each die can produce a single success.                                                                                   |
| 8+        | Double success | D8, D10 and D12 can produce double success. Check for these after d12.                                                   |
| 12+       | Triple success | Only d12 can produce triple success. Check for these first!                                                              |


Probability distribution per die type:

| Die | Failure (1-3) | Success (4-7) | Double (8-11) | Triple (12) | Expected Successes |
| --- | ------------- | ------------- | ------------- | ----------- | ------------------ |
| D4  | 75%           | 25%           | -             | -           | 0.25               |
| D6  | 50%           | 50%           | -             | -           | 0.50               |
| D8  | 37,5%         | 50%           | 12,5%         | -           | 0.75               |
| D10 | 30%           | 40%           | 30%           | -           | 1                  |
| D12 | 25%           | 33%           | 33%           | 8,3%        | 1.25               |

!!! Note
	If want to estimate your chances for success, it’s easiest to use the Expected Success column on the probability distribution table above. Simply add together the Expected Successes from each die type on your dice pool. You should expect to get this amount of successes with good odds. If the result is way less than what you need, then your chances are bad, and if it’s way more than what you need, then your chances are very good.
	E.g. You have a dice pool of 2d8+2d6. Expected value for your pool is then $2*0.75+2*0.5=2.5$. So if you need 2 successes, then your chances should be pretty good.

## Dice pool

When a skill test is called for, you need first form your **Dice Pool** by picking dice matching various characteristics on your character sheet.

**Dice Pool Structure**
- Up to 3 **Human Dice**
	- *Raw Power* — 1 Attribute Die (Frame)
	- *Talent* — 1 Aptitude Die (Persona)
	- *Expertise* — 0-1 Skill Dice (Persona; or Frame with suitable *Augments*)
- Up to 3 **Modifier Dice**
	- Utility Dice
	- Augment Dice
	- Teamwork Dice

Every test rolls at least 2 dice. 2-3 Dice come from base characteristics, and up to 3 dice can be granted by Modifiers, split into three types: *Utility Dice*, *Augment Dice* and *Teamwork Dice*. If more than 3 modifier dice were to be applicable on a single test, you must choose which dice to keep and drop the rest.

- **Utility Dice** can be awarded by using tools, equipment, augments, instructions and walk-throughs.
- **Augment Dice** can be gained through use of Augments or unique circumstantial advantages.
- **Teamwork Dice** can be gained by receiving assistance from other characters. You can benefit from up to 3 assistants, any more would just make things more complicated, and they will then “lend” one of their human dice, as appropriate to situation – usually Attribute or Skill Die. A preceding test may be required to coordinate teamwork efforts in order to allow benefiting from the teamwork dice.


!!! Example
	Mick is trying to hack the security system of a Syndicate warehouse to grant the team entry through a secure door. He must test **Mind x Hacking** and the GM announces the test has the following *Complications:* **Difficulty 2** and **Alarm 1**, meaning Mick has to first assign 2 Effect Points to overcome the Difficulty, or the test fails, and finally there’s an alarm rigged to the system which will go off unless taken care of. Hacking falls under *Technical* aptitude and Mick spends 1 energy to gain D10 Utility Die from his *Hacking Suite* augment, making total dice pool 2D10+2D8:
	
	 - D10 (Mind)
	 - D8 (Technical)
	 - D8 (Hacking).
	 - D10 (Utility, hacking suite)
	 
	 Total Dice Pool is then 2D10 + 2D8. He rolls [4, 7, 4, 6] for total 4 successes, overcoming the Difficulty complication with 2 Effect Points remaining. That’s barely enough, but Mick gets the door open and manages to avoid tripping alarms.

## Dice modification
Some rules may modify the die size. This can be indicated e.g. by stating *Body +1*, meaning that your Body die in this circumstance is one step higher. If the die is always the highest (i.e. D12), then you cannot modify it any further. Dice modification *is not* the common way to modify aspects of challenge in a test, but refer to specific circumstance.

## Successes
Any successes gained from dice are summed up together, collectively called **Effect Points**. You can then then spend **EP** to obtain **Effects** or execute **Stunts**, but before being able to do so, you must overcome **complications** linked to the task at hand. Most common type of complication is a generic **Difficulty** complication, which must be overcome or the test fails. Some complications may be voluntary, in the sense that not overcoming them does not result in complete failure, but rather some consequence that may present future troubles.

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
*Difficult* is a [[#Complications|complication]] with varying cost, where the consequence is *failure*, unless overcome. Difficulty is often abbreviated as `DIF [X]` where `[X]` is a number indicating the cost of the complication.

- DIF 0 or No difficulty = Easy
- DIF 1 = Moderate
- DIF 2 = Hard
- DIF 3 = Very hard
- DIF 4 = Extreme

### Opposed Test
Opposed Tests mean that two characters, e.g. PC and NPC both roll their dice competing against one another. They may test the same skill or different skills (opposing skills), depending on circumstance. Whoever rolls most successes wins, but their opponent’s successes are subtracted, acting much like *Difficulty Complication*.

### Stalemates
If you overcome difficulty, but do not generate any Effect Points thereafter, or match your opponent’s successes, then the test is effectively a *stalemate*. You neither succeed, nor you lose. What happens next, is up to the GM to decide, but here are a few options:

- Try again. Perhaps with some sort of penalty for stressing you out.
- Settle on a status quo – maybe it’s time to compromise?
- Sacrifice something – make a personal sacrifice in order to get ahead and win with just single Effect Point. E.g. an equipment can break or maybe you burn a bridge with a (former) ally to get what you want.

## Rerolls

Sometimes you have the option to spend a **Reroll** on a test vastly improving your chances of success or improving the outcome. Each *Reroll* allows you to pick any number of rolled dice and roll them again. You must keep the new results, even if they’re worse. When rerolling a skill test, it makes most sense to only re-roll dice that did not generate any successes, otherwise you will risk those dice producing zero successes.

!!! example
	Kris is facing a high-risk negotiation and needs to convince an enemy mercenary to stand down before the situation escalates. GM states it's a `Persuasion + Mind` test with `DIF 2`. Kris rolls 2D10+D8 → 6, 4, 3 generating only 2 successes, which is not enough to succeed. Facing a failure, He decides to spend a point of **Resolve** to reroll d10 and d8 (4 and 3) → 8, 1. That’s one double success, which results in total 3 successes. The reroll paid of and Kris succeeds.
