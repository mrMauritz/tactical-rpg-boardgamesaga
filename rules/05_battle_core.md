> **WHEN TO READ:** Only for **turn structure, 3-stage rolls, segment costs, and facing** questions.

# PART III — BATTLE CORE

## Chapter 5 — Turn Structure & Segments (AP)
- **Major Action (4 Segments):** Heavy swings, complex spells, First Aid.
- **Minor Action (2 Segments):** Defensive footwork, feints, shield-locking, Take a Breath (+1 SP).
- **Quick Action (1 Segment):** Drawing a blade, shifting facing, moving 1 Hex.
- **Anticipated Defense (2 Segments / Minor Action):** You must save a Minor Action during your turn to remain eligible for Active Defense (Block, Parry, Dodge) during the round. 
- **Banking:** Unused segments convert to SP at start of next turn (2 Segments = 1 SP).

## Chapter 6 — The Combat Resolution Pipeline
To ensure physical realism, combat follows a linear 8-stage pipeline. Interactive sheets automate calculations; players resolve the dice.

### 1. Force Generation & Defensive Eligibility
Compare the kinetic energy of the strike to determine which reactions are physically possible.
- **RF (Relative Force):** `Attacker Force - Defender Force`.
- **Eligibility:** Refer to *Table 1 (Defensive Eligibility)* to see if the target can Block, Parry, or must Dodge.

### 2. Hit Resolution (Stage 1 Roll)
`3d6 + Skill + DEX vs Target Defense`
- **Fail (0-3):** A physical error occurs. See *Table 3 (Reference Tables)* for catastrophic results like BP loss or becoming **Unbalanced**.
- **Miss (4-8):** The attack is completely negated with no penalty.

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

#### SP Status & Fatigue
- **Minor Disadvantage (SP ≤ 1/2 Max SP):** Character is winded. **-1 Defense**.
- **Major Disadvantage (SP ≤ 1/4 Max SP):** Character is gassed. **-2 Defense**.
- **Gassed (SP=0):** Emergency state. Character automatically enters **Recovery** (described below). No actions/reactions possible until turn recovery.

#### Failure State Definitions
- **Unbalanced (Tag):** The character has lost their posture or overextended. They suffer a **-2 penalty to Defense** until the start of their next turn.
- **Stunned:** Triggered by SP loss ≥ 1/2 Max SP in one blow. The character loses **3 segments** of their next action budget.
- **Knocked Down (BP=0):** The character loses their footing. They must spend a **Minor Action (2 SP)** to stand up. While down, all incoming attacks gain **+1 IS Die** (Advantage).
- **Unconscious (HP=0):** The character is removed from the tactical exchange.

### Chapter 5.1 — Specialized Actions
- **Take a Breath (Minor Action / 2 Segments):** A quick pause to refocus. Restore **+1 SP**.
- **Recovery (Full Round / 6 Segments):** Automatic at 0 SP. The character spends their entire turn regaining composure. Restore SP = **Regeneration Rate × 2**.
- **First Aid (Major Action / 4 segments):** A character can treat themselves or an adjacent ally. This removes **Bleed 1** or restores 1 lost HP from a "Partial" success wound.

## Chapter 7 — Facing and Positional Exposure
Positional exposure grants pure kinetic advantages (more dice) rather than accuracy bonuses.
- **Front (3 Hexes):** Full defense; all reactions and shields apply.
- **Flank (2 Side Hexes):** Partial exposure; Attacker gains **+1 IS Die**.
- **Rear (1 Hex):** Major exposure; No shield use, No reactions, Attacker gains **+2 IS Dice**.

## Chapter 8 — Momentum & Acceleration
- **Acceleration Tax:** Moving from a standstill requires a 1nd-segment Quick Action tax.
- **Momentum:** Moving in a straight line for 4+ hexes adds +1 to +3 IS (Stage 2).
