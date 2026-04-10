> **WHEN TO READ:** Only for **turn structure, 3-stage rolls, segment costs, and facing** questions.

# PART III — BATTLE CORE

## Chapter 5 — Turn Structure & Segments (AP)
Combat is measured in **6-segment rounds**. Time and Stamina (SP) are fungible; every 1-segment of action costs 1 SP.
- **Major Action (4 Segments / 4 SP):** Heavy swings, complex spells, First Aid.
- **Minor Action (2 Segments / 2 SP):** Defensive footwork, feints, shield-locking, standing up.
- **Quick Action (1 Segment / 1 SP):** Drawing a blade, shifting facing, moving 1 Hex.
- **Reactions (Variable Segments / 2 SP Base):** Parries, dodges, or diving. Reactions consume segments from your banked turn.

## Chapter 6 — The Combat Resolution Pipeline
To ensure physical realism, combat follows a linear 8-stage pipeline. Interactive sheets automate calculations; players resolve the dice.

### 1. Force Generation & Defensive Eligibility
Compare the kinetic energy of the strike to determine which reactions are physically possible.
- **RF (Relative Force):** `Attacker Force - Defender Force`.
- **Eligibility:** Refer to *Table 1 (Defensive Eligibility)* to see if the target can Block, Parry, or must Dodge.

### 2. Hit Resolution (Stage 1 Roll)
`3d6 + Skill + DEX vs Target Defense`
- **Result:** Determines the "Hit Quality" (Fail, Partial, Success, Great, Perfect). 
- **Fail:** If the roll is ≤ 8, the attack misses or is completely negated.

### 3. Impact Severity (IS Dice Pool)
Calculate the number of d6 dice to be rolled.
- `Base IS Pool = Attacker Body + STR Bonus`
- **Success Modifier:** Apply Dice ± from the Hit Resolution (Stage 1).
- **Positional Advantage:** 
    - **Flank:** +1 IS Die.
    - **Rear:** +2 IS Dice.

### 4. Impact Dice (Stage 2 Roll)
Roll the final **IS d6** pool. Each die is read individually against the weapon's specific impact table.

### 5. Weapon Interpretation (Raw Damage)
Convert each die into raw **HP**, **SP**, or **AP** using the *Weapon Family Impact Tables*. 
- *Note: Weapon Tags (Sharp, Crushing) are applied to the raw totals here.*

### 6. Armor Soak & AP Resolution
Armor reduces incoming damage but is vulnerable to **Armor Piercing (AP)**.
- **Effective HP Soak:** `max(0, Armor HP Soak - Total AP)`.
- **Net HP/SP Damage:** Subtract the effective soak from raw totals. 
- *Armor never reduces BP or SP Soak (unless specified by Heavy AP).*

### 7. Balance Damage (BP)
`BP Damage = round(IS Pool * Weapon BP Modifier)`. 
- **Note:** Armor does not reduce BP damage. See *The Grounding Rule* for environmental stability.

### 8. Consequences & Fatigue
Apply final HP, SP, and BP losses. Check for failure states (Unconscious, Stunned, Knocked Down) and Gear Fatigue (Armor/Shield damage).

#### Failure State Definitions
- **Stunned (SP=0):** The character is overwhelmed by shock. They lose their next **Quick Action** and cannot perform **Major Actions** until they recover at least 1 SP.
- **Knocked Down (BP=0):** The character loses their footing. They must spend a **Minor Action (2 SP)** to stand up. While down, all incoming attacks gain **+1 IS Die** (Advantage).
- **Unconscious (HP=0):** The character is removed from the tactical exchange.

### Chapter 5.1 — Specialized Actions
- **First Aid (Major Action / 4 SP):** A character can treat themselves or an adjacent ally. This removes **Bleed 1** or restores 1 lost HP from a "Partial" success wound.
- **Recover (Minor Action / 2 SP):** Used specifically to stand up from a **Knocked Down** state.

## Chapter 7 — Facing and Positional Exposure
Positional exposure grants pure kinetic advantages (more dice) rather than accuracy bonuses.
- **Front (3 Hexes):** Full defense; all reactions and shields apply.
- **Flank (2 Side Hexes):** Partial exposure; Attacker gains **+1 IS Die**.
- **Rear (1 Hex):** Major exposure; No shield use, No reactions, Attacker gains **+2 IS Dice**.

## Chapter 8 — Momentum & Acceleration
- **Acceleration Tax:** Moving from a standstill requires a 1nd-segment Quick Action tax.
- **Momentum:** Moving in a straight line for 4+ hexes adds +1 to +3 IS (Stage 2).
