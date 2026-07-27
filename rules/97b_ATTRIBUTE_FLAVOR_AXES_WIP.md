# Attribute Flavor Axes (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: SCAFFOLD ONLY**
> This file organizes the *flavor axis* layered onto each attribute pair. Mechanical effects and modifications are **NOT fixed**. This is a structural placeholder for material that is still open — not an approved Atom.

---

## 1. The Three Attribute Pairs

| Pair         | Attributes | Domain                          |
| :----------- | :--------- | :------------------------------ |
| **Physical** | STR / DEX  | Body mechanics                  |
| **System**   | END / WIL  | Metabolic / systemic regulation |
| **Mental**   | INT / CHA  | Cognition / social presence     |

*(Source: six-attribute roster, `01_system_foundations.md` Ch.2.)*

---

## 2. The Flavor Axis (Third Layer per Pair)

Each pair carries a "flavor" addition — a trait beyond the raw attribute values that colors how the pair expresses itself. This is distinct from the Lá/Óðr saga-lens (§3), which applies per-attribute rather than per-pair.

| Pair                    | Flavor Addition                    | Status                                                      | Existing Source                                                          |
| :---------------------- | :---------------------------------- | :----------------------------------------------------------- | :------------------------------------------------------------------------ |
| **Physical (STR/DEX)** | **Fiber & Frame**                  | ✅ Defined (Frame mechanically grounded; Fiber flavor only) | Two dials (Hot/Cold = Fiber, Wet/Dry = Frame). See §3 below.             |
| **System (END/WIL)**   | **Temper & Consistency**           | ✅ Defined (flavor only)                                    | Two dials (Hot/Cold, Wet/Dry) grounded in the four humors. See §4 below. |
| **Mental (INT/CHA)**   | **Disposition (Instinct & Focus)** | ✅ Defined (flavor only)                                    | Two dials (Hot/Cold = Instinct, Wet/Dry = Focus). See §5 below.          |

### Observations
- All three pairs now share the same Hot/Cold × Wet/Dry shape. Only Frame has mechanical grounding (`01_system_foundations.md` Ch.7 §3) — Fiber, Temper/Consistency, and Instinct/Focus are flavor-only so far.
- Focus (Mental's Wet/Dry axis) reuses the existing Master/Emissary attention lore (`01_INTERNAL_ARCHITECTURE_WIP.md`) rather than inventing new material.

---

## 3. Physical Flavor (STR/DEX): Fiber & Frame

Two dials describing physical build and output, in the same Hot/Cold × Wet/Dry shape as the System pair. **Frame** (the Wet/Dry-equivalent) already exists (`01_system_foundations.md` Ch.4 & Ch.7 §3); **Fiber** (the Hot/Cold-equivalent) is proposed here to complete the pair.

### 3.1 Fiber (Hot ↔ Cold): Sustained ↔ Explosive

```text
-2 Sustained ← -1 ← 0 Tempered → +1 → +2 Explosive
```

- **Sustained (slow-twitch/oxidative):** steady power output, resists fatigue, slower to reach peak force.
- **Explosive (fast-twitch/glycolytic):** burst power output, fast to reach peak force, fatigues quickly.

### 3.2 Frame (Wet ↔ Dry): Light ↔ Dense

```text
-2 Light (Fluid) ← -1 ← 0 Tempered → +1 → +2 Dense (Fixed)
```

Already established: raises structural resistance and avoidance cost as it increases (`01_system_foundations.md` Ch.4, Ch.7 §3). Structurally the same "fixed vs. adaptable" shape as Consistency (§4.2), applied to skeletal build rather than reaction pattern.

### 3.3 The Four Elements (Physical)

| Element   | Fiber     | Frame          | Archetype                                                             |
| :-------- | :-------- | :------------- | :--------------------------------------------------------------------- |
| **Fire**  | Explosive | Dense (Fixed)  | heavy, devastating single bursts — slow to wind up, brutal on contact |
| **Air**   | Explosive | Light (Fluid)  | fast, springy bursts — agile striker                                  |
| **Earth** | Sustained | Dense (Fixed)  | grinder/tank — heavy and enduring                                     |
| **Water** | Sustained | Light (Fluid)  | nimble endurance — built for the long fight                           |

*Fiber and this grid are proposed, not mechanically defined — Frame's own mechanics (§3.2) are the only locked-in piece.*

---

## 4. System Flavor (END/WIL): Temper & Consistency

Two independent dials (-2 to +2 each) describing *how* systemic strain is processed — orthogonal to raw capacity (END) and persistence (WIL) themselves. Traditional grounding: the classical Hot/Cold and Wet/Dry qualities underlying the four humors.

### 4.1 Temper (Hot ↔ Cold): Containment ↔ Mobilization

```text
-2 Contained ← -1 ← 0 Tempered → +1 → +2 Kindled
```

- **Contained:** strain is absorbed, suppressed, kept internally ordered — fear produces caution, pain is contained, composure is preserved, arousal rises slowly, action stays deliberate. Danger: rigidity, delayed response, failure to mobilize in time.
- **Kindled:** strain converts into activation and outward force — fear becomes immediate action, pain becomes aggression/urgency, composure gives way to intensity, arousal rises quickly. Danger: fury, recklessness, loss of restraint, rapid expenditure.

| Phenomenon    | Contained pole                | Kindled pole                  |
| :------------ | :----------------------------- | :----------------------------- |
| Fear response | restraint, caution             | mobilization, attack           |
| Composure     | preserved through containment  | replaced by focused intensity  |
| Arousal       | slow and controlled            | rapid and forceful             |
| Pain response | absorbed or suppressed         | converted into action          |

### 4.2 Consistency (Wet ↔ Dry): Fluid ↔ Fixed

```text
-2 Fluid ← -1 ← 0 Tempered → +1 → +2 Fixed
```

- **Fluid:** the reaction pattern is impressionable — it shifts with recent experience, mood, and context. Habituates, adapts, recalibrates. Danger: unpredictability, no reliable baseline.
- **Fixed:** the reaction pattern is retentive — the same reaction fires the same way regardless of history or context. Consistent, but unyielding. Danger: can't adapt when the old pattern stops working.

| Phenomenon        | Fluid pole                              | Fixed pole                    |
| :----------------- | :---------------------------------------- | :------------------------------ |
| Fear response     | wariness rises/falls with recent events | same threshold every time     |
| Composure         | mood-dependent, context-shifted         | stable regardless of context  |
| Arousal threshold | recalibrates encounter to encounter     | fixed baseline                 |
| Pain response     | varies with circumstance                | invariant                      |

### 4.3 The Four Elements (System)

The two axes recombine into the traditional four humors — which in turn carry their own traditional element names:

| Element      | Temper        | Consistency  | Archetype                                                                                                                                              |
| :----------- | :------------ | :----------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Fire**     | Kindled (+)   | Fixed (Dry)  | *(Choleric)* converts strain into force immediately, the same forceful way every time — an instant, identical counter-strike to any hit               |
| **Air**      | Kindled (+)   | Fluid (Wet)  | *(Sanguine)* converts strain into force immediately, but its shape shifts with mood — a lunge, a taunt, or a reckless charge, depending on the moment |
| **Earth**    | Contained (-) | Fixed (Dry)  | *(Melancholic)* absorbs/suppresses strain the same withheld way regardless of circumstance — stoic under a scratch or a mortal wound alike            |
| **Water**    | Contained (-) | Fluid (Wet)  | *(Phlegmatic)* absorbs/suppresses strain, but the manner of restraint adapts to context — calm under any strain, recalibrating each time              |
| **Balanced** | Tempered (0)  | Tempered (0) | *(Eukrasia)* neither pole dominant — response scales with the situation, not a fixed lean                                                             |

Both axes are independent dials — a character can sit anywhere in the grid, not just at the four named corners; the humors mark the corners for reference.

*Mechanical effects (what these dials modify numerically) are not yet defined — this section fixes the flavor/identity layer only.*

---

## 5. Mental Flavor (INT/CHA): Disposition (Instinct & Focus)

Two dials describing cognitive/social response, in the same Hot/Cold × Wet/Dry shape as the other pairs — framed in INT/CHA's own terms (speed of processing, breadth of attention) rather than reusing System's strain-response phrasing.

### 5.1 Instinct (Hot ↔ Cold): Deliberate ↔ Instinctive

```text
-2 Deliberate ← -1 ← 0 Tempered → +1 → +2 Instinctive
```

- **Deliberate:** slow, reflective processing.
- **Instinctive:** fast, reflexive processing — INT's "Spark" domain.

### 5.2 Focus (Wet ↔ Dry): Broad ↔ Narrow

```text
-2 Broad (Fluid) ← -1 ← 0 Tempered → +1 → +2 Narrow (Fixed)
```

- **Broad:** diffuse, context-shifting attention — the Master (`01_INTERNAL_ARCHITECTURE_WIP.md`).
- **Narrow:** locked, fixed attention — the Emissary.

### 5.3 The Four Elements (Mental)

| Element   | Instinct    | Focus          | Archetype                                                             |
| :-------- | :---------- | :------------- | --------------------------------------------------------------------- |
| **Fire**  | Instinctive | Narrow (Fixed) | snap-reactor locked on one cue — an assassin's single-target reflex   |
| **Air**   | Instinctive | Broad (Fluid)  | scattershot reactor — reacts fast, attention jumping between concerns |
| **Earth** | Deliberate  | Narrow (Fixed) | methodical specialist — unshaken, singularly fixated                  |
| **Water** | Deliberate  | Broad (Fluid)  | calm strategist — reads the whole field, adapts thinking to context   |

*Instinct, Focus, and this grid are proposed, not mechanically defined.*

---

## 6. Saga Lens: Lá & Óðr (Cross-Cutting, Not a Flavor Addition)

Independent of §2, every attribute already carries a dual manifestation:
- **Lá (Physical Form)** — the physical/embodied expression.
- **Óðr (Mystic Spirit)** — the mystic/spiritual expression.

This is fully detailed elsewhere and not duplicated here:
- `97_ATTRIBUTE_IMPACT_WIP.md` — per-attribute Lá/Óðr breakdown, Pillar Matrices, Alignment Filters.
- `01_INTERNAL_ARCHITECTURE_WIP.md` — philosophical grounding, the Ignition Logic (2x3 Matrix), the Six Saga Archetypes.

---

## 7. Four Elements — Resolved for All Three Pairs

No longer a future option: §3.3 gives the Fire/Air/Earth/Water correspondence for Physical (Fiber × Frame), §4.3 for System (Temper × Consistency), and §5.3 for Mental (Instinct × Focus).

---
*Status: Scaffold. Frame established (mechanically grounded). Fiber, Temper/Consistency, and Instinct/Focus defined at the flavor layer only — no mechanical effects yet.*
