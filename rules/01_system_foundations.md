> **WHEN TO READ:** Only for **attributes, vitality pools (HP/SP/BP), and 3d6 ladder** questions.

# PART I — SYSTEM FOUNDATIONS

## Chapter 1 — The 3d6 Resolution Ladder
All tactical and skill checks use a **3d6 roll** (summed) against a target difficulty. The bell curve provides a predictable outcome range (3-18), ideally suited for the **Modifier Barrier**.

### The Standard Ladder (1–20)
| Result | Tier | Outcome Description |
| :--- | :--- | :--- |
| **0–8** | **Fail** | Complete failure; exposure or resource loss. |
| **9–12** | **Partial Success** | Success at a cost (SP loss, minor injury, or positioning error). |
| **13–17** | **Success** | Clean, intended result achieved. Standard hit. |
| **18–19** | **Great Success** | Exceptional hit. Provides **+1 IS Die** or **Precision Effect Swap**. |
| **20+** | **Perfect Success** | Pinnacle hit. Provides **+2 IS Dice** or **Precision Effect Swap**. |

*Note: Results above 18 are only achievable through Attribute/Skill modifiers.*

## Chapter 2 — Attributes
Characters are defined by six core attributes, usually ranging from 1 to 12. Reaching 12 represents a peak historical achievement. 

> [!NOTE]
> Attributes do **not** represent physical size or mass. They define the **Internal Architecture** of the character—physiological efficiency, neuromuscular recruitment, and the density of the spirit/will within the physical frame.


1. **STR (Strength):** Raw physical power. Generates **Force** and determines **IS Bonus Dice**.
2. **DEX (Dexterity):** Precision and reflex. Infuences **Hit Quality**, **BP**, and **Defensive Tiers**.
3. **END (Endurance):** Resilience and stamina recovery.
4. **INT (Intelligence):** Analytical logic and Arcane conduit.
5. **WIL (Willpower):** Mental grit and Divine conduit.
6. **CHA (Charisma):** Leadership and Nature conduit.

### The Progression Ladder (Bonus vs. Pillars)
Every point of attribute growth contributes to either the character's **Passive Bonus** (efficiency) or their **Internal Architecture** (Pillars).

- **Every Odd Value (1, 3, 5...):** Increases the **Attribute Bonus**.
- **Every Even Value (2, 4, 6...):** Unlocks a **Pillar Slot** (Threshold begins at level 4).

| Attribute Value | Attribute Bonus | Pillar Slots | Milestone Description |
| :--- | :--- | :--- | :--- |
| **1** | -1 | — | Raw Potential |
| **2** | -1 | — | Physiological Awakening |
| **3** | **0** | — | Systemic Refinement |
| **4** | 0 | **1 Slot** | **Pillar Ignition (Baseline)** |
| **5** | **+1** | 1 Slot | Capacity Expansion |
| **6** | +1 | **2 Slots** | Structural Integration |
| **7** | **+2** | 2 Slots | Force Unification |
| **8** | +2 | **3 Slots** | Synaptic Clarity |
| **9** | **+3** | 3 Slots | Systemic Mastery |
| **10** | +3 | **4 Slots** | Peak Physicality |
| **11** | **+4** | 4 Slots | Transcendent Form |
| **12** | +4 | **5 Slots** | **Historical Legend (Mastery)** |

## Chapter 3 — Vitality Pools (Bookkeeping)
Calculated once during character setup. Interactive sheets handle dynamic tracking.

- **HP (Hit Points / Flesh):** `(Body × 3) + Size`. 
  - *Represents deep physical injury, bleeding, and structural failure.*
- **SP (Systemic Integrity / Shock):** `(Body × 2) + Endurance + Frame`. 
  - *Represents neurological stability. Uses the **Attribute Value** for granularity.*
    - **Stable (> 1/2 SP)**: No penalty.
    - **Rattled (≤ 1/2 SP)**: **Disable 6s** (The Glance Rule: 6s become 1s).
    - **Staggered (≤ 1/4 SP)**: **Disable 5s & 6s** (5s and 6s become 1s).
    - **Disabled (0 SP)**: **Physiological Shutdown.** The character cannot act until they recover.
- **BP (Balance Points):** `Body + Size + DEX Bonus + 2`.
  - *Represents postural integrity and footing. Penalties apply as BP drops:*
    - **Stable (BP > 4)**: No penalty. BP Resistance applies.
    - **Unstable (BP 2–3)**: -1 to all Defense rolls. BP Resistance lost.
    - **Stumbling (BP 1)**: -2 to all Defense rolls. BP Resistance lost.
    - **Knock Down (BP 0)**: Prone. Must stand up.

### The Regeneration Rate
At the start of every turn, characters automatically recover SP AND BP:
- **SP Recovery**: `Endurance Bonus + 2`.
- **BP Recovery**: BP resets fully to its maximum value at the start of the character's turn.

## Chapter 4 — Physical Structure (Mass)
The physical structure of a character provides the baseline for all kinetic interactions.

### 1. The Physical Constants (Scale)
Physical scale is determined at character creation and **does not scale** with progression. A character may grow in power and skill, but their physical frame remains a constant reference point throughout the Saga.

- **Body (Scale 1–10):** The primary mass baseline. Body directly sets the **Base IS Dice Pool**.
- **Size (−2 to +2):** Variations within a body scale (e.g., a "Large" human).
- **Frame (−2 to +2):** skeletal density and bone thickness.
- **RB (Relative Body):** `Attacker Body - Defender Body`. Used for specialized mass comparison.

### 2. Scale vs. Architecture
Character development represents the optimization of the **Internal Architecture** rather than the expansion of Scale.

- **Scale (Static):** The "Container." Fixed mass, size, and skeletal density.
- **Architecture (Progressive):** The "Engine." Attributes, Skills, and Perks that improve efficiency, force output, and stamina within the fixed Scale.


## Chapter 5 — Force and Momentum
Physical interaction is governed by the comparison of kinetic energy, handled via **Force** and **RF**.

### 1. The Force Calculation
`Base Force = (STR × Body) / 8`

### 2. Relative Force (RF)
`RF = Attacker Force - Defender Force`.
RF is used exclusively to determine **Defensive Eligibility** (which reactions are physically possible against the incoming blow).

STR modifies the number of d6s rolled in **Stage 2 (Impact Severity)**. This bonus is identical to the **STR Bonus**.

| STR Value | STR Bonus | IS Dice Bonus | Pillar Slots (The Center) |
| :--- | :--- | :--- | :--- |
| **2** | -1 | **-1 Die** | — |
| **4** | 0 | **+0 (Baseline)**| **1 Slot** (Ignited) |
| **6** | +1 | **+1 Die** | **2 Slots** |
| **8** | +2 | **+2 Dice** | **3 Slots** |
| **10** | +3 | **+3 Dice** | **4 Slots** |
| **12** | +4 | **+4 Dice** | **5 Slots** |

*Note: Odd numbers (e.g., 3, 5, 7) increase the IS Dice Bonus but do not unlock further Pillar Slots.*

---

## Chapter 6 — Tactical Initiative (Speed)
Initiative determines the order of action within each segment. It is a live value affected by physical burden.

`Initiative = DEX - floor(Armor HP Soak / 2)`
- *Initiative uses the **Attribute Value** to define the segment timeline (1–12).*

- **Heavy Armor Penalty**: Characters in Plate or Chain act significantly later than those in Light Armor or Cloth.
- **Dynamic Shifts**: Weapon tags (like *Fast*) or status effects (like *Staggered*) can modify Initiative during a round.

---

## Chapter 6 — The Spirit Layer (Wyrd & Oaths)
*The Saga* defines a separation between physical world-interaction and the fated current:

- **Perception (Reality Layer):** Using the senses to navigate and survive. Governed by DEX/INT.
- **Vision (Wyrd Layer):** The mystery of seeing the fated current beneath the world. Vision is not a skill; it is a state of being influenced by the **Wyrd**.

### The Mystery of the Wyrd
The Wyrd is a universal current that affects all beings. It is indifferent and unquantified (no points). Modifying it is forbidden and risky.

### Oaths & The Tension of Time
Oaths exert **Moral Gravity**. Breaking them has real, non-physical consequences that can "blind" a character's Vision. Players must balance **Short-term Survival** against the **Long-term Saga** (mythic legacy and honor).

### Generational Remnants
When a character falls, their presence is "seeded" into the world as a persistent marker. A character's **Alignment and Wyrd** influence the nature of the remnant (e.g., *Hallowed* vs. *Cursed*).

### Faction Breathing
Factions operate on a **Pulse** of **Active Push** (proactive gain) and **Reactive Pull** (responding to players). This creates a "breathing" campaign state.

---

## Chapter 7 — Natural Protection
Characters and monsters possess inherent resilience that exists independently of gear or equipment.

### 1. Natural Armor (Resilience)
Natural armor acts as a passive reduction to incoming kinetic and shock energy.
- **Effect**: Subtract the Natural Armor value from all raw **HP** and **SP** damage totals before applying Gear Soak.
- **Consistency**: Unlike gear, Natural Armor cannot be "compromised" by critical hits unless specified by a unique monster trait.

### 2. Physical Weight (BP Soak)
A character's physical build provides resistance to being moved or unbalanced.
- **Steadfast (Trait)**: Subtract **2 BP** from all incoming Balance Damage.
- **Grounded (Position/Trait)**: Subtract **1 BP** from all incoming Balance Damage.
- **The Stability Rule**: This resistance is temporarily **lost** if the character is currently **Unstable** or **Stumbling** (BP < 4).
