> **WHEN TO READ:** Only for **turn structure, 3-stage rolls, segment costs, and facing** questions.

# PART III — BATTLE CORE

## Chapter 5 — Turn Structure & Segments (AP)
- **Major Action (4 Segments):** Heavy swings, complex spells, First Aid.
- **Minor Action (2 Segments):** Defensive footwork, feints, Take a Breath (+1 SP). (Note: *Shield-locking* is a Perk-based specialized maneuver).
- **Quick Action (1 Segment):** Drawing a blade, shifting facing, moving 1 Hex.
- **Anticipated Defense (2 Segments / Minor Action):** You must save a Minor Action during your turn to remain eligible for **Active Defense** reactions during the round. 
- **Banking:** Unused segments convert to SP at start of next turn (2 Segments = 1 SP).

### Chapter 5.1 — Active vs. Passive Defense
- **Passive Defense:** Automatic physical protection derived from gear (Armor Soak, Shield Ballistic Protection). Requires no roll and does not consume reactions.
- **Active Defense:** A reactive move (Block, Parry, Dodge) that requires a **Defense Roll (Stage 1)**. Each use consumes one charge of the character's **Starting Capacity**.

#### Starting Defensive Capacity (Per Round)
| Skill Type | Starting Capacity | Requirement |
| :--- | :--- | :--- |
| **Active Block** | 1 / round | Shield Equipped |
| **Active Parry** | 1 / round | Weapon with *Parry* Tag |
| **Active Dodge** | 3 / round | None (Physical Mobility) |

## Chapter 6 — The Combat Resolution Pipeline
To ensure physical realism, combat follows a linear 8-stage pipeline. Interactive sheets automate calculations; players resolve the dice.

### 1. Force Generation & Defensive Eligibility
Compare the kinetic energy of the strike to determine which reactions are physically possible.
- **RF (Relative Force):** `Attacker Force - Defender Force`.
- **Eligibility & Capacity:** 
    1. Refer to *Table 1 (Defensive Eligibility)* to see if the target can physically react.
    2. Check **Starting Capacity** to see if the target has reactions remaining this round.

### 2. Hit Resolution (Stage 1 Roll)
`3d6 + Skill + DEX Bonus vs Target Defense`
- **Fail (0-8):** See *Table 3*. Catastrophic results like BP loss or becoming **Unbalanced**.
- **Partial (9-12):** Minimal hit, no bonus IS.
- **Success (13-17):** Clean Hit. Standard weapon damage.
- **Great Success (18–19) / Natural 18:** **+1 IS Die** roll. If an attacker has a **Precision Perk**, they may perform a **Precision Effect Swap**, trading the extra IS Die for a specialized **Precision Effect (Table 11)**.
- **Perfect Success (20+):** **+2 IS Dice** roll. If an attacker has a **Precision Perk**, they may perform a **Precision Effect Swap**, trading the extra IS Dice for a specialized **Precision Effect (Table 11)**.

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

### 6. Ballistic Protection & Armor Soak
Incoming force is reduced by physical barriers before hitting the armor layers.
- **Shield Ballistic Protection (if applicable):** If the attack strikes a protected facing (Front/Flank), subtract the Shield's **Ballistic Protection** from the raw totals.
- **Armor HP Soak:** `max(0, Armor HP Soak - Total AP)`.
- **Net HP/SP Damage:** Subtract the effective armor soak from the remaining totals. 
- *Armor/Shields never reduce BP or SP Soak (unless specified by Heavy AP).*

### 7. Balance Damage (BP)
`BP Damage = round(IS Pool * Weapon BP Modifier)`. 
1. **Apply Resistance**: Subtract **Steadfast (-2)** or **Grounded (-1)** from the incoming BP damage. 
2. **The Stability Rule**: If a character's current BP < 4 (Unstable/Stumbling), they **lose all BP Resistance** for the rest of the turn.
3. **Note**: Gear Armor Soak does not reduce BP damage. 

### 8. Consequences & Fatigue
Apply final HP, SP, and BP losses. Check for failure states (Unconscious, Stunned, Knocked Down) and Gear Fatigue (Armor/Shield damage).

#### Systemic Integrity (Shock Status)
As systemic Integrity (SP) is lost, the character faces a physiological "shutdown." This is modeled by disabling high d6 results (**The Glance Rule**: Disabled dice are treated as a **1**).
- **Stable (> 1/2 SP)**: Normal operation.
- **Rattled (≤ 1/2 SP)**: **Disable 6s.** (A 6 becomes a 1). Affects all 3d6 checks and IS rolls.
- **Staggered (≤ 1/4 SP)**: **Disable 5s & 6s.** (5s and 6s become a 1). Affects all 3d6 checks and IS rolls.
- **Disabled (0 SP)**: **Physiological Shutdown.** The character is removed from the tactical exchange until they recover at least 1 SP.

#### Balance State Penalties
- **Unstable (BP 2–3)**: The character is fighting to maintain their footing. They suffer a **-1 penalty to all Defense rolls**.
- **Stumbling (BP 1)**: The character is on the verge of falling. They suffer a **-2 penalty to all Defense rolls**.
- **Knocked Down (BP 0)**: The character has lost their footing. They must spend a **Minor Action (2 segments)** to stand up. While down, incoming attacks gain **+1 IS Die** (Advantage).
- **Unconscious (HP=0):** The character is removed from the tactical exchange.

### Chapter 5.1 — Specialized Actions
- **Take a Breath (Minor Action / 2 Segments):** A quick pause to refocus. Restore **+1 SP**.
- **Recovery (Full Round / 6 Segments):** Automatic at 0 SP. The character spends their entire turn regaining composure. Restore SP = **Regeneration Rate × 2**.
- **First Aid (Major Action / 4 segments):** A character can treat themselves or an adjacent ally. This removes **Bleed 1** or restores 1 lost HP from a "Partial" success wound.

## Chapter 7 — Facing and Positional Exposure
Positional exposure grants pure kinetic advantages (more dice) rather than accuracy bonuses.
- **Front (3 Hexes):** Full defense; all reactions and shields apply. Provides **Ballistic Protection** (Soak).
- **Flank (2 Side Hexes):** Partial exposure; Attacker gains **+1 IS Die**. Shield Ballistic Protection only applies here if **Shield Skill ≥ 3** (Heater/Tower).
- **Rear (1 Hex):** Major exposure; No shield use, No reactions, Attacker gains **+2 IS Dice**.

---

## Chapter 9 — Tactical Formations (Player-Driven)
Formations are physical arrangements of unit hexes that provide group-level advantages. They are not automatic; they rely on the **Player's understanding** of geometry and the **Command Skill** of a leader.

### 1. Requirements
- **The Leader**: At least one character in the formation must possess **Command Tier 3+**.
- **The Anchor**: Units must be in **Adjacent Hexes** and facing the same general direction.
- **Breaking the Line**: A formation is immediately broken if any member is **Pushed**, **Moves** out of the hex-chain, or is forced to **Change Facing**.

### 2. Valid Formations
- **Shield-Wall (The Skjaldborg):** A line of 2+ adjacent units with shields facing the same way.
    - *Effect*: Members **Share Ballistic Protection**. Use the highest BP (Soak) value among the wall members for all front-facing hits.
- **The Swine-Array (The Wedge):** A triangle of 3 units (One "Point," two "Shoulders" behind).
    - *Effect*: When the Point unit charges, they gain **+1 IS Die** from the combined weight and momentum of the shoulders pushing them from behind.
- **Rear-Guard (Shared Cover):** A unit positioned directly in the hex behind a Tower Shield wielder.
    - *Effect*: The rear unit inherits the Tower Shield’s **Ballistic Protection** against ranged or reach attacks coming from the front, even if they are not using a shield themselves.
