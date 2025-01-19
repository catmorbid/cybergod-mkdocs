---
title: Damage System
version: 3
---
## Glossary

- **Damage Class (DC)**: The raw damage value of each hit before applying mitigation or armor effects.    
- **Damage Reduction (DR)**: A defensive stat that reduces the DC of each hit by a fixed amount. DR cannot reduce DC below the minimum damage value (0.5). DR can be sacrificed to mitigate all hits from an attack.
- **Death Test:** Test Toughness x Body against Difficulty equal to number of Critical Wounds. On failure, the character will die.
- **Hit:** Hits represent a strikes and projectiles that cause an effective impact on the target, inflicting significant damage. A single slow strike can inflict a single hit, while an array of automatic fire can inflict multiple Hits.
- **Mitigated Hits:** A hit that was mitigated by a Mitigation Points. Halves Damage (minimum 0.5) for the Hit.
- **Mitigation Points (MP)**: A temporary resource that reduces the remaining DC of hits after DR is applied. Consumed at a rate of 1 MP per mitigated hit.    
- **Shock**: Represents non-lethal damage, such as bruises or stamina loss. Shock can accumulate and impose penalties (e.g., Dazed or Stunned).    
- **Wounds**: Represents direct injuries inflicted when damage exceeds mitigation. Wounds can incapacitate or kill a character if they exceed certain thresholds.
- **Wounds, Critical:** If you have more than 5 wounds, each additional wound becomes a Critical Wound, causing a **Death Test**.
- **Soak Test**: A dice roll based on Toughness x Body that reduces Wounds and Shock. Soak successes are spent first to convert Wounds to Shock and then to reduce Shock.    
- **Unmitigated Hits**: Hits that remain after all DR and MP have been applied.
- **Conditions**: The character's status after resolving Shock and Wounds. Conditions include Unharmed, Wounded, Critically Wounded, Dazed, Stunned, and Instant Death.

## Damage Resolution Steps

### 1. Apply Damage Reduction
    
- Each hit's Damage Class (DC) is reduced by the target's DR.
- Resulting DC after applying DR cannot be negative.
- A minimum damage of 0.5 is always inflicted after applying DR, ensuring that high-hit-count, low-damage weapons remain effective against heavily armored targets.
### 2. Apply Mitigation
    
- Spend 1 MP to Mitigate a Hit, reducing the remaining DC by half, rounding down, to a minimum of 0.5.
- A Hit that already does minimum damage 0.5 cannot be further mitigated and does not consume MP either.
- If you do not have enough MP, you have two options:
	- **Take unmitigated Hit:** Take the hits as unmitigated, risking getting wounded
	- **Sacrifice Armor DR:** By sacrificing 1 point of Damage Reduction, you can mitigate all remaining Hits and immediately Refresh MP. This will permanently reduce the DR of the armor.
### 3. Accumulate Wounds
    
- Both mitigated and unmitigated hits contribute to wounds.
- The total wounds are calculated by summing the damage from all hits after mitigation and applying DR.
- The final wound total is rounded to the nearest whole number.
### 4. Perform Soak Test
    
The defender rolls a soak test using their **Toughness x Body** to reduce any incoming Wounds or Shock.

**Effects**
- **Soak (1)**: Converts 1 Wound from the attack to 1 Shock
- **Negate Shock (1):** Negates 1 point of Shock from the attack, including any Shock caused by Soaking wounds.
- **Negate Wound (2):** Completely negates 1 point of Wound from the attack. This is the same as if first Soaking a wound and then Negating the Shock.

### 5. Determine Conditions
    
Based on the total shock and wounds, the defender's condition is determined:
- **Unharmed:** No shock or wounds.
- **Wounded:** Up to 5 Wounds. Take a Penalty Die to actions for each Wound up to 5 wounds.
- **Critically Wounded:** 6 or more Wounds. Character is incapacitated and unable to take any actions. Make a **Death Test** with Difficulty equal to number of Critical Wounds
- **Dazed**: 6+ Shock. Temporary disorientation. Suffer -1D penalty until Shock is reduced to 6 or less.
- **Stunned:** 10 Shock; Unable to take any Actions. Character is vulnerable to further attacks. Any Shock taken beyond 10 Shock is converted to Wounds.
- **Instant Death:** 11 or more Wounds. Excessive wounds beyond survivable limits.

### 6. Death Test

If the Defender received any Critical Wounds, they must make a Death Test. Test **Toughness x Body** at difficulty equal to number of **Critical Wounds** (Wounds above 5). On failure, the character will die.

## Damage Reduction and Mitigation
Armor provides two stats used to reduce damage: **Damage Reduction (DR)** and **Mitigation Points (MP)**. The stats are linked together in that at start of each round of combat MP will refresh to a value equal to `DR x 2`. Once MP are spent, you can choose to sacrifice 1 point of DR to negate all hits in an attack and immediately refresh MP. But this will reduce the amount of available MP on a round and once the last DR is depleted, the armor is useless.

**Armor Tags:**
- **Durable:** MP are refreshed to `DR x 3`, giving much more longevity.
- **Fragile:** MP are refreshed to `DR x 1`, making armor much more fragile and easy to break.

## Non-Lethal Damage

Non-lethal damage represents attacks intended to incapacitate rather than kill. This damage primarily results in shock but may still cause minor wounds in certain cases.

- Apply DR and Mitigation normally
- When accumulating wounds, you automatically Soak half of the damage, converting them into Shock instead.
- Soak Test then may then reduce the Wounds and Shock as usual.

## Recovering Wounds and Shock
- Shock 
	- **Automatic Recovery:** Everyone recovers 1 Shock at the start of each round
	- **Recover action:** Spend an action to catch your breath and make an easy `Toughness x Body` test: Each success removes 1 point of Shock
	- **Medical Aid:** Spend Action to take medical aid or activate appropriate augments
- Wounds
	- **First Aid:** Administer or receive first aid. Requires appropriate medical kit.
		- Difficulty is Moderate when **Wounded**
		- Difficulty is Hard when **Critically Wounded**.
		- **Effects**
			- 2 EP to recover a Wound
			- 1 EP to recover Shock
	- **Medical Items**: Spend Action to apply instant medical items
	- **Augments:** Activate relevant Augments such as [[regeneration]].