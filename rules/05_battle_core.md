> **WHEN TO READ:** Only for **turn structure, 3-stage rolls, segment costs, and facing** questions.

# PART III — BATTLE CORE

## Chapter 5 — Turn Structure & Segments
A turn has **6 segments**.
- **Major Action (4 Segments):** Heavy swings, complex spells, First Aid.
- **Minor Action (2 Segments):** Defensive footwork, feints, Take a Breath (+1 SP). (Note: *Shield-locking* is a Perk-based specialized maneuver).
- **Quick Action (1 Segment):** Drawing a blade, shifting facing, moving 1 Hex.
- **Anticipated Defense (2 Segments / Minor Action):** You must save a Minor Action during your turn to remain eligible for **Active Defense** reactions during the round. 
- **Banking:** Unused segments convert to SP at start of next turn (2 Segments = 1 SP).

### Chapter 5.1 — Active vs. Passive Defense
- **Passive Defense:** Automatic physical protection derived from gear (Armor Soak, Shield Ballistic Protection). Requires no roll and does not consume reactions.
- **Active Defense:** A reactive move (Block, Parry, Dodge) that requires a **Defense Roll (Stage 1)**. Each use consumes one charge of the character's **Starting Capacity**.
- **Hit and defense (LOCKED 2026-11-23):** a natural 18 on 3d6 always hits. On any other roll, a successful Active Defense wins — including against a modified total of 18 or more. How the defense roll is resolved is OPEN.
- **Impact and balance (LOCKED 2026-11-23):** what reaches the defender depends on whether there is physical contact.

| Outcome | Contact | BP damage |
|---|---|---|
| **Direct hit** | Full | Full, under the Balance rule (Ch.6 §7) |
| **Block** — including a shield wall (Ch.9) | Full, on the shield | Full |
| **Redirect** — a parry usually redirects | Some: the blow is met and turned | How much carries through is OPEN |
| **Avoid** — a successful dodge | None | None from the blow's impact |

#### Starting Defensive Capacity (Per Round)
| Skill Type | Starting Capacity | Requirement |
| :--- | :--- | :--- |
| **Active Block** | 1 / round | Shield Equipped |
| **Active Parry** | 1 / round | Weapon with *Parry* Tag |
| **Active Dodge** | 3 / round | None (Physical Mobility) |

#### The Engagement Cap (Simultaneous Attackers)
**Starting Capacity** is a per-round pool, not a per-attacker pool. If two attacks land against the same character within the same segment, the defender must choose a single attack to answer with an **Active Defense** roll (spending a charge). The other attack automatically resolves against **Passive Defense** only (Armor Soak, Shield Ballistic Protection) — this is not an automatic hit, it simply forgoes the Active Defense roll and its bonus.
- **Spare Capacity:** Overcoming this cap (answering both attacks with Active Defense) requires a dedicated Progression Perk, such as **Twin Ward** (The Wall — see `02_perks_and_traits.md`). It is not available by default.

### Chapter 5.2 — Specialized Actions
- **Take a Breath (Minor Action / 2 Segments):** A quick pause to refocus. Restore **+1 SP**.
- **Recovery (Full Round / 6 Segments):** Automatic at 0 SP. The character spends their entire turn regaining composure. Restore SP = **Regeneration Rate × 2**.
- **First Aid (Major Action / 4 segments):** A character can treat themselves or an adjacent ally. This removes **Bleed 1** or restores 1 lost HP from a "Partial" success wound.

## Chapter 6 — The Combat Resolution Pipeline
To ensure physical realism, combat follows a linear 8-stage pipeline. Interactive sheets automate calculations; players resolve the dice.

### 1. Force Generation & Defensive Eligibility
Compare the kinetic energy of the strike to determine which reactions are physically possible.
- **RF (Relative Force):** `Attacker Force - Defender Force`.
- **Eligibility & Capacity:** 
    1. Refer to *Table 1 (Defensive Eligibility)* to see if the target can physically react.
    2. Check **Starting Capacity** to see if the target has reactions remaining this round.

### 2. Hit Resolution (Stage 1 Roll)
`3d6 + Skill + DEX Bonus vs Target Defense` (attack vs. defense: Ch.5.1)
- **Fail (0-8):** See *Table 3*. Catastrophic results like BP loss or becoming **Unbalanced**.
- **Partial (9-12):** Minimal hit, no bonus IS.
- **Success (13-17):** Clean Hit. Standard weapon damage.
- **Great Success (18–19) / Natural 18:** **+1 IS Die** roll. If an attacker has a **Precision Perk**, they may perform a **Precision Effect Swap**, trading the extra IS Die for a specialized **Precision Effect (Table 11)**.
- **Perfect Success (20+):** **+2 IS Dice** roll. If an attacker has a **Precision Perk**, they may perform a **Precision Effect Swap**, trading the extra IS Dice for a specialized **Precision Effect (Table 11)**.

#### The Location Die (LOCKED 2026-11-23)
One die of the Stage 1 roll is the **location die**, marked by colour. It is read twice: its value counts toward the hit total as usual, and its face gives the location. On a miss, it tells where the blow would have landed. Location is used **only for BP damage** (§7) — an abstraction.

| Face | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| **Location** | Right arm | Left arm | Torso | Right leg | Left leg | Head |

- **Read first:** the location is read before the Glance Rule (§8) disables any dice, and before the Triples Rule removes one (`01c_CHARACTER_BUILD_PIPELINE_WIP.md` §2).
- **Odds:** the better the hit, the more often it lands high on the table — a natural 18 is always the head. BP is greatest at the head, then the legs.
- **Armor by location:** location makes armor by location possible (e.g. a helmet on the head) — not used yet.

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
- *Armor and shields never reduce BP damage. AP reduces HP Soak only, never SP Soak (`10_reference_tables.md` Table 8).*

### 7. Balance Damage (BP)
`BP Damage = round(IS Pool * Weapon BP Modifier)`, adjusted by the hit's location (§2, The Location Die); how each location acts on this formula is OPEN. 
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
- **Beaten (Surrender/Route):** The character's spirit or tactical will is broken. They are removed from the exchange (see Chapter 8).

---

## Chapter 7 — Facing and Positional Exposure
Positional exposure grants pure kinetic advantages (more dice) rather than accuracy bonuses.
- **Front (3 Hexes):** Full defense; all reactions and shields apply. Provides **Ballistic Protection** (Soak).
- **Flank (2 Side Hexes):** Partial exposure; Attacker gains **+1 IS Die**. Shield Ballistic Protection only applies here if **Shield Skill ≥ 3** (Heater/Tower).
- **Rear (1 Hex):** Major exposure; No shield use, No reactions, Attacker gains **+2 IS Dice**.

### Chapter 7.1 — Sensory Conditions (Obscured & Deafened)
Facing describes what the body can physically cover. Sensory conditions describe what the mind can physically perceive — a Front-facing attacker can still land a blow with the impact of a Rear attack if the defender never saw or heard them coming (see `95_HISTORICAL_COMBAT_WIP.md`, Senses entries).

- **Obscured:** Applied by fog, smoke, darkness, sun-glare, or a full-face helm. A defender cannot use **Active Defense** against an attack originating from a hex they have not observed this round, regardless of Facing arc. Passive Defense still applies.
- **Deafened:** Applied by a full-face helm or an attack originating beyond shout/command range. A Deafened character cannot declare **Anticipated Defense** against an Ambush or Surprise Round attack — there was no warning to react to.

---

## Chapter 8 — Tactical Routing & Surrender ("Beating" the Enemy)
In *BoardGameSaga*, an opponent can be **Beaten** long before they are dead. Whether that is victory depends on the mission (§4). This adheres to the **Reality Core**—historical battles often end in routing or surrender once the internal architecture of a formation or individual collapses.

### 1. The Breaking Point (Warlust)
A combatant is **Beaten** (Routing or Surrendering) when their **Warlust** reaches 0 and they fail the Rout Check (§2). These **Reality Conditions** drain Warlust (LOCKED 2026-11-23):
- **Systemic Collapse (SP = 0):** The target is **Disabled** (Physiological Shutdown).
- **Positional Collapse (BP 0 after Stumbling):** The target is **Knocked Down** after more than 2 rounds in a **Stumbling/Unstable** state.
- **Leader Lost:** The leader is defeated or flees — every subordinate's Warlust drains.

Amounts are OPEN.

### 2. The Rout Check (Will vs. Pressure)
When Warlust reaches **0**, the character rolls a **3d6 Rout Check** against a difficulty determined by the opponent's **Moral Pressure** (`01_system_foundations.md` Ch.3).
- **Moral Pressure:** Set by the attacker's **WIL** or **CHA**.
- **Cohesion (Campaign Layer):** Cohesion (`26_CAMPAIGN_ECONOMY_WIP.md` §3.2) gives a party member a **buffer** — it lowers the effective Moral Pressure DC, and at a high enough threshold auto-negates the check entirely (automatic success), the same scaling-then-threshold shape as Devotion (`24_BONDS_AND_DEVOTION_WIP.md` §4.1) — and a **lifeline**: the option *I must stay with my friends*. Exact curve, threshold, and lifeline mechanics are OPEN, see `90_TODO_development_tracking.md` §5.
- **Enemy morale:** set by the enemy's leader and group, and can be modified by the mission (§4).
- **Result:**
    - **Success:** The character holds their nerve and stands at 0 Warlust.
    - **Fail:** The character is **Beaten** — they stop fighting, and flee, surrender, or drop their weapons. For a party member, what happens is determined by their disposition in the party.

### 3. "Clever Ways" to Beat Enemies
Characters focused on non-lethal paths (WIL, CHA) use these mechanics to resolve encounters:
- **Intimidation (The Terror-Gaze):** A character with **CHA 7+** can spend a **Major Action** to drain the **Warlust** of an Unstable or Rattled enemy (§1).
- **Negotiation (WIL):** A character with **WIL 7+** can "Order" a Staggered or Stumbling enemy to surrender, bypassing the need for further HP damage.
- **Environment Exploitation:** Collapsing a structure (Material Tag) or isolating an enemy can trigger automatic **Routing** due to tactical hopelessness.

### 4. Victory and Defeat (LOCKED 2026-11-23)
The mission defines what ends the fight and what counts as success or failure for each side (`27_EVENTS.md` §0, §10). The battle rules supply the outcomes — collapse, surrender, rout; their significance depends on the mission.

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
