> **WHEN TO READ:** Only when **calculating 3-stage rolls, force tiers, or weapon damage**.

# PART VI — REFERENCE TABLES

## Table 1: Defensive Eligibility (RF Comparison)
Determines which defensive reactions are physically possible based on the **Relative Force (RF)** of the strike.
`Base Force = (STR × Body) / 8` | `RF = A_Force - D_Force`

| RF Tier | Comparison | Defensive Options | Starting Capacity |
| :--- | :--- | :--- | :--- |
| **≤ -3** | Defender Dominates | Block, Parry (Easy) | 1 / 1 / 3 |
| **-2 to +2** | Evenly Matched | Block, Parry, Dodge | 1 / 1 / 3 |
| **+3** | Shield Advantage | Block (Shield Only), Dodge | 1 / - / 3 |
| **+4 to +5** | Attacker Overpowers | Dodge, Redirect only | - / - / 3 |
| **≥ +6** | Overwhelming | Dodge only (Guard Crushed) | - / - / 3 |

---

## Table 2: IS Dice Pool (Stage 2)
The number of d6 dice rolled depends on the **Attacker's Body** and their **Strength Modifier**.

### STR Dice Bonus Table
| Attribute Value | IS Dice Bonus |
| :--- | :--- |
| **2** | -1 Die |
| **4** | +0 (Baseline) |
| **6** | +1 Die |
| **8** | +2 Dice |
| **10** | +3 Dice |
| **12** | +4 Dice |

---

## Table 3: Hit Success Ladder (Stage 1 to Stage 3)
Modifiers applied to the IS Dice Pool based on the quality of the Stage 1 Skill Roll.

| Roll Result | Tier | IS Dice Modifier | Failure Effect |
| :--- | :--- | :--- | :--- |
| **0–1** | **Major Fail** | Attack Ends | **-2 BP** & **Unbalanced** |
| **2–3** | **Fail** | Attack Ends | **-2 BP** |
| **4–8** | **Miss** | Attack Ends | — |
| **9–12** | **Partial** | -2 Dice | — |
| **13–17** | **Success** | +0 Dice | — |
| **18–19** | **Great** | +1 Die | **Precision Effect Swap** (Table 11) |
| **20+** | **Perfect** | +2 Dice (+1 AP) | **Precision Effect Swap** (Table 11) |

---

## Table 4: Weapon Balance Damage (BD) Rates
Balance Damage (BD) is calculated per die rolled in Stage 2. **Armor DOES NOT reduce Balance Damage.**

| Weapon Type | BD / Die | Example (8 Dice IS) |
| :--- | :--- | :--- |
| **Swords / Spears** | 0.5 BD | 4 BD |
| **Axes / Maces** | 1.0 BD | 8 BD |
| **Impact Head Tag** | **+1.0 BD** | +8 BD (Additive) |
| **Heavy Hammers** | 1.5 BD | 12 BD |

---

## Table 6: Weapon Family Impact (Per IS Die)
Each die in the IS pool is read individually against the weapon's table.

| D6 | Blade (Cut/Thrust) | Spear (Pierce) | Axe (Cleave) | Blunt (Crush) |
| :--- | :--- | :--- | :--- | :--- |
| **1** | 1 SP | — | 1 SP | 1 SP |
| **2** | 1 HP | 1 HP | 1 HP | 1 SP |
| **3** | 1 HP | 1 HP | 1 HP + 1 SP | 1 HP + 1 SP |
| **4** | 1 HP + 1 SP | 2 HP | 2 HP | 2 SP |
| **5** | 2 HP | 2 HP | 2 HP + 1 SP | 1 HP + 2 SP |
| **6** | 2 HP + 1 SP | 2 HP + 1 AP | 3 HP | 2 HP + 2 SP |

*Note: Spears and Greatswords have **Reach 2**.*

---

## Table 7: Armor Soak (HP & SP)
Armor reduces incoming force into manageable shock (SP) or absorbs it entirely.

| Armor Type | HP Soak | SP Soak |
| :--- | :--- | :--- |
| **Cloth / Padded** | 1 | 1 |
| **Leather / Hide** | 2 | 1 |
| **Chain / Scale** | 4 | 1 |
| **Plate** | 5 | 2 |

*Note: Armor never reduces BP damage.*

---

## Table 7.1: Shields (Ballistic Protection & Durability)
Shields provide physical **Ballistic Protection** (HP/SP Soak) for specific facings.

| Shield Type | Ballistic Prot (Soak) | Durability (per hit) | Max Condition |
| :--- | :--- | :--- | :--- |
| **Buckler** | 1 | 6 | 2 |
| **Heater** | 2 | 8 | 3 |
| **Tower** | 3 | 10 | 4 |

*Note: If an incoming IS (Impact Severity) pool exceeds Durability, Condition is reduced by 1. At 0 Condition, the shield is destroyed.*

---

## Table 8: Armor Piercing (AP) Mechanics
For each Impact Die ($5, 6$), check for AP generation.

| Weapon Tag | AP Threshold | Effect |
| :--- | :--- | :--- |
| **Standard** | 6 | +1 AP |
| **AP Tag** | 4+ | +1 AP |
| **Heavy AP (AP+)** | 3+ | +1 AP |

*AP only reduces HP Soak. Unused AP does not carry over.*

---

## Table 5: 3d6 Probability Reference
For players to assess risk during Stage 1.

| Result | Probability | Frequency |
| :--- | :--- | :--- |
| **9+** | 74.07% | High |
| **13+** | 25.93% | Moderate |
| **18+** | 0.46% | Rare |

---

## Table 11: Precision Effect Swaps (Anatomical)
Requires a specific **Precision Perk** (Chapter 4.1) and a **Natural 18** OR a **Great/Perfect Success (18+)**.

| Effect | Target | Mechanical Consequence |
| :--- | :--- | :--- |
| **Concussion** | Head | **Automatic Stun.** Target loses 3 segments of action budget. |
| **Hit the Gap** | Vitals | **Armor Bypass.** Subtract entire Armor Soak (HP) from strike. |
| **Sever Tendon** | Legs | **Movement Disable.** Target Move speed = 0 for 1 round. |
| **Blinded** | Eyes | **Major Blindness.** Target suffers -2 to all Accuracy/Defense. |
| **Hand Strike** | Arms | **Disarm.** Weapon dropped or +2 segment cost to next swing. |

---

## Table 12: Balance States & Penalties
As a character's **BP Pool** is depleted during a round, they suffer increasing penalties to their defensive capability. Balance fully resets at the start of the character's turn.

| BP Value | State | Penalty | Resistance Status |
| :--- | :--- | :--- | :--- |
| **> 4** | **Stable** | None | **Resistance Active** (Steadfast/Grounded) |
| **2–3** | **Unstable** | **-1 to Defense Rolls** | Resistance **LOST** |
| **1** | **Stumbling** | **-2 to Defense Rolls** | Resistance **LOST** |
| **0** | **Fallen** | **Knock Down** (Prone) | Cannot React |

---

## Table 13: Systemic Shock (The Glance Rule)
Physiological trauma limits the character's ability to exert force and maintain precision. Disabled dice results are treated as a **1**.

| SP Value | State | Disabled Results | Consequence |
| :--- | :--- | :--- | :--- |
| **> 1/2 SP** | **Stable** | None | Normal performance. |
| **≤ 1/2 SP** | **Rattled** | **6** | All 6s become 1s. Accuracy and Impact drop. |
| **≤ 1/4 SP** | **Staggered** | **5, 6** | All 5s and 6s become 1s. Catastrophic failure. |
| **0 SP** | **Disabled** | ALL | **Physiological Shutdown.** No actions possible. |
