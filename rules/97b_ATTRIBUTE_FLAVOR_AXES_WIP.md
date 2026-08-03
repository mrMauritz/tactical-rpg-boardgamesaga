# Attribute Flavor Axes (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: SCAFFOLD ONLY**
> This file organizes the *flavor axis* layered onto each attribute pair. Primary numeric effects are stated per axis; secondary effects, perks, combinations, and exceptions remain open. Tempo's Readiness/Initiative interaction with the core Initiative formula is pending Deep Dive — see `90_TODO_development_tracking.md`. This is a structural placeholder for material that is still open, not a fully approved Atom.

**Background:** Grounded in the four humors and the classical Wheel of the Elements (Aristotle/Empedocles) — real historical/physiological doctrine, not invented.

**Source:** Architecture and primary effects adapted from a user-provided reference workbook (*BG Saga — Creature & Humanoid Flavor System*), reconciled against this file's prior scaffold and against `01_system_foundations.md`.

---

## 1. The Three Attribute Pairs

| Pair         | Attributes | Domain                          |
| :----------- | :--------- | :------------------------------ |
| **Physical** | STR / DEX  | Body mechanics                  |
| **System**   | END / WIL  | Metabolic / systemic regulation |
| **Mental**   | INT / CHA  | Cognition / social presence     |

*(Source: six-attribute roster, `01_system_foundations.md` Ch.2.)*

---

## 2. The Six Flavor Axes

Each attribute pair carries **two** independent flavor axes (−2 to +2, 0 = Tempered): one drawn from the **Air ↔ Earth** diagonal of the classical Wheel of the Elements, one from the **Water ↔ Fire** diagonal.

This diagonal pairing is deliberate, not arbitrary. On the classical square of qualities (Hot/Cold × Wet/Dry: Fire=Hot+Dry, Air=Hot+Wet, Water=Cold+Wet, Earth=Cold+Dry), Fire↔Water and Air↔Earth are the only two element-pairs that oppose on **both** qualities at once — the two true diameters of the wheel, not merely adjacent elements sharing one quality (e.g. Fire–Air share only Hot). Using these diameters as the axes directly, rather than deriving elements from two independent Hot/Cold and Wet/Dry sliders, is the more elemental-native of the two valid classical constructions.

One consequence: because all three pairs share the *same* two diagonals, the four elements — and the four humors they carry (§7) — are common infrastructure across Physical, System, and Mental, not a re-derived grid per pair.

| Pair         | Attributes | Air ↔ Earth Flavor | Water ↔ Fire Flavor | Status                                              |
| :----------- | :--------- | :------------------ | :-------------------- | :--------------------------------------------------- |
| **Physical** | STR / DEX  | **Frame**           | **Load**              | Frame: Established. Load: Strong direction.         |
| **System**   | END / WIL  | **Temper**          | **Fortitude**         | Temper: Established direction. Fortitude: Strong direction. |
| **Mental**   | INT / CHA  | **Attention**       | **Tempo**             | Both: Strong direction.                              |

---

## 3. Physical Flavors: Frame & Load

### 3.1 Frame (Air ↔ Earth): Light ↔ Dense

```text
-2 Light (Air) ← -1 ← 0 Tempered → +1 → +2 Dense (Earth)
```

Established (`01_system_foundations.md` Ch.4, Ch.7 §3). Governs **BP resistance** specifically (§6) — raw skeletal build.

| Pole | Primary Effects |
| :--- | :--------------- |
| **Light**  | −1 BP resistance; −1 SP cost for avoidance actions per step. |
| **Dense**  | +1 BP resistance; +1 SP cost for avoidance actions per step. |

### 3.2 Load (Water ↔ Fire): Pressure ↔ Impulse

```text
-2 Pressure (Water) ← -1 ← 0 Tempered → +1 → +2 Impulse (Fire)
```

**Grounding:** *Impulse* (J = FΔt, mechanics) is momentum delivered in a short, high-force burst; *pressure* (force sustained over time/area) is its direct physical opposite — not invented vocabulary. Matches the two primary families of close combat: **percussion** (strikes — brief, concentrated force; fracture, concussion, laceration) vs. **grappling/constriction** (holds, chokes, crushing — sustained force; ischemia, asphyxiation, crush injury). Historical wrestling treatises (e.g. Fiore dei Liberi's *Abrazare*) already separate strikes from binds/pressure on this exact line.

| Pole | Primary Effects |
| :--- | :--------------- |
| **Pressure** | +1 maintained impact; −1 initial impact per step. |
| **Impulse**  | +1 initial impact; −1 maintained impact per step. |

---

## 4. System Flavors: Temper & Fortitude

### 4.1 Temper (Air ↔ Earth): Mobilization ↔ Containment

```text
-2 Mobilization (Air) ← -1 ← 0 Tempered → +1 → +2 Containment (Earth)
```

Established direction. Governs **SP resistance** specifically (§6) — how strain converts into action versus staying absorbed.

| Pole | Primary Effects |
| :--- | :--------------- |
| **Mobilization** | +1 SP generation; −1 SP resistance per step. |
| **Containment**  | +1 SP resistance; −1 SP generation per step. |

### 4.2 Fortitude (Water ↔ Fire): Mental ↔ Physical

```text
-2 Mental (Water) ← -1 ← 0 Tempered → +1 → +2 Physical (Fire)
```

**Grounding:** *Fortitudo* is one of the four Cardinal Virtues (Plato; later Aquinas) — defined specifically as the capacity to endure fear and pain **psychologically**, distinguished in antiquity from raw bodily toughness (Aristotle's *karteria*, bodily endurance, vs. *andreia*, courage under fear). Physiologically, psychological resilience runs through the HPA axis (fear/cortisol regulation) — a distinct system from tissue/structural resilience (nociception threshold, wound tolerance). Military history draws the same line: troops routing from fear while physically unharmed, versus fighting on through physical wounds.

| Pole | Primary Effects |
| :--- | :--------------- |
| **Mental**   | +1 mental resistance; −1 HP resistance per step. |
| **Physical** | +1 HP resistance; −1 mental resistance per step. |

---

## 5. Mental Flavors: Attention & Tempo

### 5.1 Attention (Air ↔ Earth): Diffuse ↔ Selective

```text
-2 Diffuse (Air) ← -1 ← 0 Tempered → +1 → +2 Selective (Earth)
```

Reuses the existing Master/Emissary attention lore directly — `01_INTERNAL_ARCHITECTURE_WIP.md` Ch. "The Attention (CHA — The Master & The Emissary)" already names this exact CHA concept "Attention."

| Pole | Primary Effects |
| :--- | :--------------- |
| **Diffuse**   | +1 field awareness; −1 accuracy/precision per step. |
| **Selective** | +1 accuracy/precision; −1 field awareness per step. |

### 5.2 Tempo (Water ↔ Fire): Control ↔ Execution

```text
-2 Control (Water) ← -1 ← 0 Tempered → +1 → +2 Execution (Fire)
```

**Grounding:** Japanese swordsmanship's *Sen* doctrine draws exactly this distinction — *Sen* (先, seizing initiative, striking first) vs. *Go no Sen* (後の先, yielding tempo to react/counter from readiness). Military doctrine mirrors it: "initiative" (offense-postured, seizes tempo) vs. "reserve" (defense-postured, held back to react). Neuroscience offers the physiological analogue — feedforward (anticipatory/planned) vs. feedback (reactive) motor control.

| Pole | Primary Effects |
| :--- | :--------------- |
| **Control**   | +1 Readiness; −1 Initiative. Each +1 Readiness allows defense against one additional attacker. |
| **Execution** | +1 Initiative; −1 Readiness. Each −1 Readiness removes defense capacity against one attacker. |

*Integration with the core Initiative formula (`01_system_foundations.md` Ch.6) and the exact opponent-count thresholds are pending Deep Dive — see `90_TODO_development_tracking.md`.*

---

## 6. Resistance Channels

Each of the four damage/effect pools has exactly one governing flavor:

| Incoming effect                      | Governing flavor              |
| :------------------------------------ | :------------------------------ |
| **HP** damage or HP-affecting effect | Fortitude (Physical pole)     |
| **SP** damage                        | Temper                        |
| **BP** damage                        | Frame                         |
| **Mental** effect                    | Fortitude (Mental pole)       |

A single attack can trigger several channels at once:

```text
Fireball:
HP damage → Fortitude (Physical)
SP damage → Temper
BP damage → Frame
```

The same attack therefore resolves differently depending on the target's flavor profile. *(Formulas pending — see `90_TODO_development_tracking.md`.)*

---

## 7. Element Matrix

The four classical elements are shared infrastructure across all three pairs — each pair's Air↔Earth flavor and Water↔Fire flavor read onto the same four poles. The classical humors attach here, at the element level, since they name the same four points under a parallel doctrine (four qualities → four humors), not at any pair's two-axis corners (a corner combining, say, full Air-lean with full Fire-lean lands on a blend between adjacent elements, not on a single humor — the humors only resolve at the pure poles).

| Element   | Humor           | Physical      | System              | Mental               |
| :-------- | :--------------- | :------------- | :-------------------- | :---------------------- |
| **Air**   | Sanguine        | Light Frame   | Mobilization         | Diffuse Attention     |
| **Earth** | Melancholic     | Dense Frame   | Containment           | Selective Attention   |
| **Water** | Phlegmatic      | Pressure (Load) | Mental Fortitude    | Control (Tempo)       |
| **Fire**  | Choleric        | Impulse (Load)  | Physical Fortitude  | Execution (Tempo)     |

Both axes within a pair remain independent dials — a character can sit anywhere in that pair's 2D space, not just at the four pure-pole points; the elements/humors mark those pure points for reference.

---

## 8. Saga Lens: Lá & Óðr (Cross-Cutting, Not a Flavor Addition)

Independent of §2, every attribute already carries a dual manifestation:
- **Lá (Physical Form)** — the physical/embodied expression.
- **Óðr (Mystic Spirit)** — the mystic/spiritual expression.

This is fully detailed elsewhere and not duplicated here:
- `97_ATTRIBUTE_IMPACT_WIP.md` — per-attribute Lá/Óðr breakdown, Pillar Matrices, Alignment Filters.
- `01_INTERNAL_ARCHITECTURE_WIP.md` — philosophical grounding, the Ignition Logic (2x3 Matrix), the Six Saga Archetypes.

---

## 9. Design Principles

*(Source: user-provided reference workbook, Design Notes sheet.)*

| Principle | Current meaning |
| :--- | :--- |
| **Flavor scale** | Each flavor uses a five-grade scale from −2 to +2, with 0 as Tempered/balanced. |
| **Primary effects** | Each step gives one clear gain and one corresponding cost. |
| **Secondary effects** | Left open for later; should emerge from combinations with attributes, equipment, senses, perks, and situations — not stated in advance. |
| **Creature profiles** | Animals and monsters are usually defined by 2–3 strong flavors, often at ±2. |
| **Humanoid profiles** | Humanoids are usually defined by one dominant flavor or several weaker ±1 expressions. |
| **Perks** | Perks should emerge by selectively modifying or breaking existing rules, not by adding generic bonuses. |
| **Resistance division** | Frame governs BP resistance; Temper governs SP resistance; Fortitude divides mental versus physical (HP) resistance — see §6. |

---
*Status: Scaffold. Frame established (mechanically grounded, `01_system_foundations.md`). Temper established direction. Load, Fortitude, Attention, Tempo defined with primary effects and historical/physiological grounding — full mechanical formulas and Tempo's Initiative integration pending, see `90_TODO_development_tracking.md`.*
