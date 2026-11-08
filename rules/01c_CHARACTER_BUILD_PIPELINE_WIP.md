# Character Build Pipeline (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** This file maps how Attributes, Pillars, Flavor Axes, Skills, Class Trees, Devotion, and Magic actually compose at character creation and progression — the single picture that was previously scattered across seven files with no map tying them together. Several pieces are ESTABLISHED (cited to their source); several remain explicitly OPEN. Do not read an OPEN item as decided.

**Source:** Reconstructed across this session and the prior one, resolving one real contradiction and consolidating several design decisions that existed only in conversation until now (2026-11-09).

---

## 1. The Pipeline, Staged

| Stage | What happens | Source |
|---|---|---|
| **0. Race Tendencies** | Sets starting nudges on the six Flavor Axes (Frame/Load/Temper/Fortitude/Attention/Tempo). Never touches Attribute values. | `97b_ATTRIBUTE_FLAVOR_AXES_WIP.md` §10 |
| **1. Scale** (static, set once) | Body (1–10), Size (−2/+2), Frame (−2/+2) — the "Container." | `01_system_foundations.md` Ch.4 |
| **2. Attributes** (progressive, "the Engine") | STR/DEX/END/WIL/INT/CHA, 1–12 baseline (Chaos alignment can break the cap past 12). Bonus = `floor((Value−3)/2)` — **kept as-is**, confirmed negative at Value 1–2 (Bonus −1). Odd values raise Bonus; even values unlock a Pillar Slot. | `01_system_foundations.md` Ch.2 |
| **3. Pillar Ignition** (per attribute, independently) | The Pillar **Slot** opens at the even value (Gray). **Ignition** itself fires at the *following odd value* — see §2 below for the full resolution. At Ignition, choose Lá (Physical) or Óðr (Mystic) architecture, then the Alignment Filter (Order/Wild/Chaos), which sets the mechanical reward/cost. Choice is independent per attribute — same filter every time = Streamlined; mixed = Diverse (`20b` Build Synergy dial). | `01_INTERNAL_ARCHITECTURE_WIP.md` "Ignition Logic" |
| **4. Flavor Axes refine** | Frame/Load/Temper/Fortitude/Attention/Tempo settle per attribute pair. No stated interaction with Ignition — explicitly left open (§4 below). | `97b` |
| **5. Skills unlock** | A Skill under a given Attribute is trainable only once that Attribute's Bonus is ≥ 0 (Value ≥ 3). A Master Trainer can bypass this gate for a fee (`26_CAMPAIGN_ECONOMY_WIP.md` Levers). Skills then grow through **use**, not through spent points — see §3 below. | `03_skill_system.md` |
| **6. Class Trees & Perks** | 8 universal trees per attribute pair; perks gated by [Social] / [Racial] / [Alignment] / [Skill] — the [Alignment] gate consumes Stage 3's choice, the [Skill] gate consumes Stage 5's tier, and [Social] can also be satisfied by Devotion Tree standing (`24b_BOND_AND_DEVOTION_PROGRESSION_TREE_WIP.md`). | `99_CLASS_TREES_WIP.md`, `02_perks_and_traits.md` |
| **7. Magic Casting** (drafted, not active) | `3d6 + Conduit Tier + Galdr Tier + Attribute Bonus vs Difficulty`, three tiers (Binding/Bending/Breaching). Whole system flagged "not currently part of the active rule system"; Conduit/Galdr Tier have no numeric formula anywhere. | `01_INTERNAL_ARCHITECTURE_WIP.md` |

---

## 2. Pillar Ignition Timing — Resolved

**ESTABLISHED (2026-11-09):** `01_INTERNAL_ARCHITECTURE_WIP.md`'s own Block System already describes ignition as two sequential stages — Gray Slot (threshold met) → Glowing/Active Block (trigger completed). Checked against `97_ATTRIBUTE_IMPACT_WIP.md`'s Master Matrix table: its value-4 row carries no Ignition label at all; "[Ignition]" first appears at value 5. That is exactly the Gray-at-4 → Ignited-at-5 pattern, just never stated as a rule before now.

**The rule:** Pillar Slot unlocks at the even Attribute value (Gray). Ignition fires at the following odd value — the same moment the Attribute Bonus ticks up. This is not a contradiction between files; it is the missing sentence that makes `01_system_foundations.md`, `01_INTERNAL_ARCHITECTURE_WIP.md`, and `97_ATTRIBUTE_IMPACT_WIP.md` consistent with each other.

---

## 3. The Three-Currency Progression Model

**ESTABLISHED (2026-11-09):** Skill, Attribute, and Tree/Faction progression are not one pool wearing three hats — they are three different currencies with three different earning logics, each matching a different kind of real growth:

| Currency | Represents | Earned by | Cost shape |
|---|---|---|---|
| **Skill** | How much you've *done* something | Usage/repetition over time — **no spendable currency at all** | N/A — a counter, not a purchase |
| **Attribute** | Effort and aim — deliberate investment | Spent points, granted at a Level (§4 below) | Rising: N→N+1 costs N points (PROVISIONAL — see §5) |
| **Tree / Faction (Devotion)** | Deeds and achievements | Earned via specific accomplishments — the same mechanism `24_BONDS_AND_DEVOTION_WIP.md` §4 already uses for Bond Devotion ("one earned achievement = one point") | Flat: Class Tree perks are 1 point = 1 gain (PROVISIONAL) |

Class Tree achievement-points and Bond Devotion-points are **parallel, separate economies** (confirmed `24b` §1) — not the same pool, even though they're earned the same way.

**Why three, not one:** a system where progression depends only on repetition (Skill alone) isn't fun; a system where it depends only on deliberate spend ignores how much a character has actually *done*; a system where it depends only on achievement ignores practiced competency. Together, the three tracks interact to form distinct paths rather than one undifferentiated grind.

---

## 4. Level — A Reflection Event, Not a Counter

**ESTABLISHED (2026-11-09):** A "Level" is not a flat XP-threshold tick. It is a narrative moment where the character stops to reflect on recent events — mechanically, this reuses the existing Camping/Prep-Phase tool (`06_adventure_and_prep.md`) rather than inventing a new trigger. A Level grants two things simultaneously:
- An opportunity to **learn something new** → Tree points.
- An opportunity to **reflect on how things were done** → Attribute points.

**OPEN:** the exact trigger condition is left open, except that it is gated by accumulated experience points crossing some threshold — what grants XP, and the threshold value, are undecided.

---

## 5. Open Questions (Do Not Treat as Decided)

1. **Race-modifies-attribute-cost conflict.** `01_system_foundations.md` Ch.2's Character Origins principle currently reads "Race does not modify attribute values... Race shapes expression, not progression" (locked earlier this session). The proposal that Race also modify the attribute-cost formula contradicts that tagline as written. Two reconciliation paths were raised, neither chosen:
   - **A.** Narrow the tagline — Race nudges flavor *and* which specific attributes are cheap/expensive for that race (a biological affinity), while Individual still governs the baseline curve and ceiling.
   - **B.** Keep Race fully out of cost — the "race feels different to raise" effect already emerges softly from Flavor's starting nudges (a Dense-Frame race already leans toward STR/END) without touching the cost formula itself.
   - A related, still-open design intent: the user does not want to foreclose a race being *generally* stronger in an attribute, or generally strong but *extremely* strong specifically in its flavor direction (amplification where general strength and flavor align) — this needs its own resolution pass, not assumed by either A or B above.
2. **Exact attribute cost formula.** N→N+1 costs N points is proposed, not locked — produces a steep curve (1–12 costs 66 points total, back-loaded).
3. **Flavor Axes have no stated interaction with Ignition at all** — intentional separation or a gap, not yet decided.
4. **Level trigger specifics** — what generates XP, and the threshold that unlocks a Level event.
5. **Tree-depth power curve** — if Class Tree cost is flat (1 pt = 1 gain) but later perks are presumably stronger, what paces that growth if not cost? (prerequisite chains, attribute thresholds, tier-gating — unresolved.)
6. **Master Trainer mechanism** — has a home (`26` Levers) but no designed cost or access condition yet.

---
*Status: Foundational spark — consolidates decisions made across two sessions that previously existed only in conversation. §2 and §3's framing are settled; §5's items are not. Last Updated: 2026-11-09.*
