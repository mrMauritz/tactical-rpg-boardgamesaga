> **WHEN TO READ:** Only for **weapon tags, armor degradation, and environmental stability**.

# PART IV — WEAPON & ARMOR PROPERTIES

## Chapter 9 — Weapon Tags & Specializations
Tags add personality to weapons. They modify the core impact tables but never replace them.

### 1. Tag Definitions
- **Heavy**: The weapon possesses significant mass. **Effect**: Reroll IS dice results of `1` once. **Penalty**: -1 Initiative, -1 Stage 1 Accuracy.
- **Impact Head**: The weapon's weight is concentrated at the strike point (Axes, Maces). **Effect**: +1 RF (Relative Force), +0.5 Balance Damage (BP) per IS Die. **Penalty**: -1 Initiative, -1 Stage 1 Accuracy.
- **Flail**: A flexible weapon with a weighted head. **Effect**: Bypasses **Active Parry** (Target must Dodge or Block). **Backfire**: On a **Major Fail (0-1)**, the wielder becomes **Unstable** (BP reduced to 3).
- **Two-Handed (2H)**: Designed for deep leverage. **Effect**: Grants **+1 IS Die** to the pool. **Requirement**: Requires both hands; prevents the use of a shield or free off-hand.
- **Versatile**: Weight-balanced for dual use. **Effect**: May be wielded 1H or 2H. If used with two hands, it gains the **Two-Handed (+1 IS Die)** bonus but loses the off-hand.
- **Sharp**: On any die that deals HP, if that die is a 6+, add **Bleed 1**.
- **Armor-Piercing (AP)**: Use the AP Tag rules (4+ threshold for AP).
- **Fast**: If any IS die shows 5+, the attacker gains **+1 Initiative** for the next segment.
- **Reach**: Allows a weapon to target a hex up to **2 hexes away**. 
- **Parry**: This weapon is designed for defensive play. Allows the use of the **Active Parry** reaction.

### 1.1 Momentum & Acceleration
Movement generates kinetic force.
- **Acceleration Tax:** Moving from a standstill (0 velocity) costs an extra **1 Segment**.
- **The Momentum Bonus:** For every **3 hexes** moved in a straight line immediately before an attack, the striker gains **+1 IS Die** (Impact Severity).

### 2. STR Scaling (Weight Requirements)
High-impact tags require physical leverage. If a character does not meet the **STR Baseline**, they suffer penalties.

| Tag | STR Req | Penalty for Failure |
| :--- | :--- | :--- |
| **Heavy Head** | 8 | +1 Segment of Recovery (1 SP) after attack. |
| **Heavy AP (AP+)** | 10 | Target receives **+1 Advantage** to Stage 1 defense. |
| **Hooking (Polearm)** | 6 | Weapon becomes **Unwieldy** (-1 Accuracy next turn). Can be used to **Push** a unit, triggering a **Formation Break**. |

### 2.1 Dual-Wielding Defense
If a character has a weapon equipped in each hand and both weapons possess the **Parry** tag, they gain a bonus to their reactive capacity.
- **Effect:** Increase **Starting Active Parry Capacity** by **+1** (Total 2 / round).

---

## Chapter 10 — The Grounding Rule (Dynamic BP Resilience)
While armor protects the flesh, the environment protects the footing. 
- **Environmental Stability:** If a unit is in a **Stable Position** (e.g., leaning against a wall, in a fortified hex, or prone), they gain a **BP Soak** equal to their **Size + 1**.
- **Effect:** Subtract this value from the incoming BP damage before applying it to the BP pool.

---

## Chapter 11 — Gear Fatigue (Automatic Damage)
Items fail under extreme kinetic stress. This is not a choice, but a consequence of physics.

### 1. Shield Damage & Condition
Shields fail under extreme kinetic stress. This is modeled by **Condition** (item health).
- **The Rule**: If an attack is **Blocked** (Active) or strikes the **Passive Coverage**, compare the **IS (Impact Severity) Pool** to the shield's **Durability**.
- **Damage**: Every point of **IS > Durability** reduces the shield's **Condition** by 1.
- **The Shield Sacrifice**: If an attack is overwhelming (RF Tier exceeds eligibility), the defender may choose to sacrifice the shield. The remaining IS points are absorbed by the shield's condition until it is **Destroyed (Condition 0)**. The absorbed IS does not affect the defender.
- **Repair**: Condition can be restored during Camping/Prep phases using appropriate materials.

### 2. Armor Damage
If a strike results in a **Perfect Success (Stage 1)** and the total **IS Dice Sum** ≥ 15, the armor's structural integrity is compromised.
- **Effect:** The Armor HP Soak is permanently reduced by **1 point** until repaired.

---

## Chapter 12 — Armor Material Tags
Material tags define how armor reacts to specific elemental or tactical "Saga" conditions.

| Material Tag | Armor Types | Effect |
| :--- | :--- | :--- |
| **Flammable** | Cloth, Leather | If hit by a fire-tagged attack, the target suffers **Bleed 1**. |
| **Conductive** | Chain, Plate | If hit by a lightning-tagged attack, the **SP Soak** is ignored entirely. |

---

- **Outcome**: Only "Success" or "Perfect" rolls can leverage high-tech or specialized armor-piercing features.

---

## Chapter 14 — Shield Maneuvers & Geometric Coverage
Shields are physical barriers that provide protection based on orientation and user skill.

### 1. Ballistic Protection (Soak)
Shields provide a static **HP/SP Soak** (Reference Table 7.1) against attacks coming from the **protected facing**. 
- This soak is applied **before** armor soak.

### 2. Geometric Coverage (Passive Scaling)
As a character's **Shield Skill** increases, they learn to maneuver the barrier to cover more of their physical silhouette.
- **Skill 0–2**: Protects the **Front (3 Hexes)**.
- **Skill 3–4**: Protects the **Front + Left Flank (4 Hexes)**.
- **Skill 5+**: Protects the **Front + Both Flanks (5 Hexes)**.

### 3. Tower Shield "Shadow" (Line of Sight)
Tower shields are massive enough to create a physical "safe zone" on the tactical grid.
- **Effect**: If an ally is positioned **directly behind** a Tower Shield wielder relative to the attacker, they gain the shield's **Ballistic Protection** as if they were the primary target.
- **Note**: This only applies to ranged or reaching attacks that must pass through the wielder's hex.
