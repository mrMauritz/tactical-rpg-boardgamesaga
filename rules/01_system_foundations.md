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
| **18–19** | **Great Success** | Exceptional hit. Provides **+1 IS Die** or **Perk Swap**. |
| **20+** | **Perfect Success** | Pinnacle hit. Provides **+2 IS Dice** or **Perk Swap**. |

*Note: Results above 18 are only achievable through Attribute/Skill modifiers.*

## Chapter 2 — Attributes
Characters are defined by six core attributes, usually ranging from 1 to 12. Reaching 12 represents a peak historical achievement.

1. **STR (Strength):** Raw physical power. Generates **Force** and determines **IS Bonus Dice**.
2. **DEX (Dexterity):** Precision and reflex. Infuences **Hit Quality** and **Defensive Tiers**.
3. **END (Endurance):** Resilience and stamina recovery.
4. **INT (Intelligence):** Analytical logic and Arcane conduit.
5. **WIL (Willpower):** Mental grit and Divine conduit.
6. **CHA (Charisma):** Leadership and Nature conduit.

## Chapter 3 — Vitality Pools (Bookkeeping)
Calculated once during character setup. Interactive sheets handle dynamic tracking.

- **HP (Hit Points / Flesh):** `(Body × 3) + Size`. 
  - *Represents deep physical injury, bleeding, and structural failure.*
- **SP (Shock Points / Stamina):** `(Body × 2) + Endurance + Frame`.
  - *Represents tactical integrity and posture.*
- **BP (Balance Points):** `Body + Size + floor(DEX / 2)`.
  - *Represents postural integrity. BP resets fully when "Standing Up" or at the end of an exchange.*

### The Regeneration Rate
At the start of every turn, characters automatically recover SP equal to their **Regeneration Rate**:
`Regeneration Rate = floor(Endurance / 2)`.

## Chapter 4 — Physical Structure (Mass)
- **Body (Scale 1–10):** The primary mass baseline. Body directly sets the **Base IS Dice Pool**.
- **Size (−2 to +2):** Variations within a body scale (e.g., a "Large" human).
- **Frame (−2 to +2):** Skeletal density.
- **RB (Relative Body):** `Attacker Body - Defender Body`. Used for specialized mass comparison.

## Chapter 5 — Force and Momentum
Physical interaction is governed by the comparison of kinetic energy, handled via **Force** and **RF**.

### 1. The Force Calculation
`Base Force = (STR × Body) / 8`

### 2. Relative Force (RF)
`RF = Attacker Force - Defender Force`.
RF is used exclusively to determine **Defensive Eligibility** (which reactions are physically possible against the incoming blow).

### 3. Strength IS Bonus (Dice Pool)
STR modifies the number of d6s rolled in **Stage 2 (Impact Severity)**.

| STR Value | IS Dice Bonus |
| :--- | :--- |
| **2** | -1 Die |
| **4** | +0 (Baseline) |
| **6** | +1 Die |
| **8** | +2 Dice |
| **10** | +3 Dice |
| **12** | +4 Dice |

---

## Chapter 6 — Tactical Initiative (Speed)
Initiative determines the order of action within each segment. It is a live value affected by physical burden.

`Initiative = DEX - floor(Armor HP Soak / 2)`

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
