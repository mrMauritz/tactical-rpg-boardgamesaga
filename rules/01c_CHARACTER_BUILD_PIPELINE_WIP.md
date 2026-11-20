# Character Build Pipeline (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** This file maps how Attributes, Pillars, Flavor Axes, Skills, Class Trees, Devotion, and Magic actually compose at character creation and progression — the single picture that was previously scattered across seven files with no map tying them together. Several pieces are ESTABLISHED (cited to their source); several remain explicitly OPEN. Do not read an OPEN item as decided.

**Source:** Reconstructed across this session and the prior one, resolving one real contradiction and consolidating several design decisions that existed only in conversation until now (2026-11-09).

---

## 1. The Pipeline, Staged

| Stage | What happens | Source |
|---|---|---|
| **0. Race Tendencies** | Sets starting nudges on the six Flavor Axes (Frame/Load/Temper/Fortitude/Attention/Tempo). Also shapes attribute progression — general racial strength in an attribute, amplified where it aligns with flavor (mechanism open, §5). | `97b_ATTRIBUTE_FLAVOR_AXES_WIP.md` §10, `01_system_foundations.md` Ch.2 |
| **1. Scale** (static, set once) | Body (1–10), Size (−2/+2), Frame (−2/+2) — the "Container." | `01_system_foundations.md` Ch.4 |
| **2. Attributes** (progressive, "the Engine") | STR/DEX/END/WIL/INT/CHA, mortal cap 12 (Chaos uncapped). Bonus = `floor(Value/2) − 1` — −1 at Value 1, rises at even values. Odd values from 5 reach Pillars. Reaching value N costs N. | `01_system_foundations.md` Ch.2 |
| **3. Pillar Ignition** (per attribute pair) | A pair (Physical STR/DEX, System END/WIL, Mental INT/CHA) becomes eligible once **either** attribute reaches 5, and ignites through a saga/Bond event. Lá or Óðr is chosen **once per pair**, fixed. Pillars are neutral (`97` §12A) and open by value; igniting Óðr gives up the pair's Pillars. Any ignition grants the Triples Rule and a Bond consequence. Alignment (Order/Wild/Chaos) is a separate character-level bonus, not an ignition filter — §2. | `01_INTERNAL_ARCHITECTURE_WIP.md` "Ignition Logic" |
| **4. Flavor Axes refine** | Load/Temper/Fortitude/Attention/Tempo settle per attribute pair. **Frame does not change** — it is fixed at Stage 1. No stated interaction with Ignition — explicitly left open (§4 below). | `97b` |
| **5. Skills unlock** | A Skill under a given Attribute is trainable only once that Attribute's Bonus is ≥ +1 (Value ≥ 4). A Master Trainer can bypass this gate for a fee (`26_CAMPAIGN_ECONOMY_WIP.md` Levers). Skills then grow through **use**, not through spent points — see §3 below and `03_skill_system.md` Ch.3. | `03_skill_system.md` |
| **6. Class Trees & Perks** | 8 universal traditions (`99`: practices, offices, states); perks gated by [Social] / [Racial] / [Alignment] / [Skill] — the [Alignment] gate consumes the character-level alignment (§2), the [Skill] gate consumes Stage 5's tier, and [Social] can also be satisfied by Devotion Tree standing (`24b_BOND_AND_DEVOTION_PROGRESSION_TREE_WIP.md`). | `99_CLASS_TREES_WIP.md`, `02_perks_and_traits.md` |
| **7. Magic Casting** (drafted, not active) | `3d6 + Conduit Tier + Galdr Tier + Attribute Bonus vs Difficulty`, three tiers (Binding/Bending/Breaching). Whole system flagged "not currently part of the active rule system"; Conduit/Galdr Tier have no numeric formula anywhere. | `01_INTERNAL_ARCHITECTURE_WIP.md` |

---

## 2. Pillar Ignition — Unified Model

**LOCKED 2026-11-15; revised 2026-11-16** (neutral Pillars, Óðr forgoes Pillars, ignition = Triples Rule + Bond). Supersedes the 2026-11-09 "Gray at even → Ignite at odd" timing rule.

> **Whole self (LOCKED 2026-11-16):** Lá / Óðr is a state of the whole self, per the sources (`01_INTERNAL_ARCHITECTURE_WIP.md` Axis 1). The per-pair rows below stand until rewritten (§5.13).

| Layer | Rule |
|---|---|
| **Bonus** | `floor(V/2) − 1`: −1 at V1, steps at even values (V4 +1 … V12 +5) |
| **Skill gate** | Bonus ≥ +1 → V ≥ 4 (`03_skill_system.md`) |
| **Cost** | Reaching value N costs N (§3) |
| **Cap** | Mortal 12. Chaos uncapped — the rising cost is the practical limit |
| **Alignment** (character level, separate from ignition) | **Order:** +12 attribute points, one-off at creation. **Wild:** one mutation at creation from a path-neutral pool (`94`). **Chaos:** cost −1 (min 1), uncapped |
| **Pillars** | The **neutral path**: the Lá Matrix (`97` §12A) at odd values 5 / 7 / 9 / 11, opened by value alone — no event needed. Identical for all alignments. Pillar V (13) legendary — Chaos only in practice |
| **Ignition** | Per pair (Physical / System / Mental). Eligible once **either** attribute reaches 5; ignited by a saga/Bond event (`24_BONDS_AND_DEVOTION_WIP.md`). Ignition is a specialization: a small bonus in its realm (Triples Rule) plus a Bond consequence |
| **Path** | Neutral until lit. Lá or Óðr, chosen once per pair at ignition, fixed |
| **Lit Lá** | Keeps the pair's Pillars; gains the Triples Rule and the Bond consequence |
| **Lit Óðr** | Leaves much of the material world: **loses the pair's Pillars** (including Pillar I already held). Gains the Triples Rule and the Bond consequence — access to magic. Magic is rare in the world, but everywhere for those who read it |
| **Triples Rule** (granted by any ignition) | Applies to all rolls once a pair is lit. On-path triples → +1d6. Off-path triples → remove one of the three dice |
| **Mixed paths** | If lit pairs disagree, the roll counts as off-path — the cost of mixing — plus predefined penalties (e.g., Cross-Strain, `01_INTERNAL` Axis 1) |
| **Bond consequence** | The igniting event grants or deepens a Bond card (`24` §6): its Traits, Devotion Tree branch (`24b`), costs and taboos. The archetype Ignition lines (`01_INTERNAL` Axis 2) give the kind of event |
| **Óðr Matrix** | `97` §12B is no longer Pillar content — parked as candidate material for the spell system |

---

## 3. The Three-Currency Progression Model

**ESTABLISHED (2026-11-09):** Skill, Attribute, and Tree/Faction progression are not one pool wearing three hats — they are three different currencies with three different earning logics, each matching a different kind of real growth:

| Currency | Represents | Earned by | Cost shape |
|---|---|---|---|
| **Skill** | How much you've *done* something | Usage/repetition over time — **no spendable currency at all**. Checks in events and missions build a skill XP pool; an insight on a strong roll turns it into a progress point (`03_skill_system.md` Ch.3, LOCKED 2026-11-20) | Rising: reaching tier N costs 5 × N progress points; tiers 6–8 only through event, master-training or bond rewards (`03` Ch.3) |
| **Attribute** | Effort and aim — deliberate investment | Spent points, granted at a Level (§4 below) | Rising: reaching value N costs N points (**LOCKED 2026-11-15; revised 2026-11-20**) |
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

1. ~~Race-modifies-attribute-cost conflict~~ — **RESOLVED 2026-11-15:** Race shapes both expression and progression (`01_system_foundations.md` Ch.2 tagline updated). A race can be generally strong in an attribute *and* amplified further in its flavor direction. **Still open:** the mechanism — racial cost modifier, starting-value offset, or both — and how "amplified in flavor direction" is computed.
2. ~~Exact attribute cost formula~~ — **LOCKED 2026-11-15; revised 2026-11-20:** reaching value N costs N points (1–12 = 77 points total, back-loaded).
3. **Flavor Axes have no stated interaction with Ignition at all** — intentional separation or a gap, not yet decided.
4. **Level trigger specifics** — what generates XP, and the threshold that unlocks a Level event.
5. **Tree-depth power curve** — if Class Tree cost is flat (1 pt = 1 gain) but later perks are presumably stronger, what paces that growth if not cost? (prerequisite chains, attribute thresholds, tier-gating — unresolved.)
6. **Master Trainer mechanism** — has a home (`26` Levers) but no designed cost or access condition yet.
7. ~~**Lá/Óðr cost of mixing**~~ — **resolved 2026-11-16:** the off-path rule is the trade-off; Cross-Strain and other predefined penalties stack on it (§2).
8. ~~**Later Pillar triggers**~~ — **resolved 2026-11-16:** Pillars are neutral and open by value alone (§2).
9. **Parked material** — the former Lá value-5 row is re-homed as Pillar I (`97` §12A). Still parked: the Óðr Matrix incl. its value-5 row (`97` §12B, awaiting the spell system) and the archetype Mechanical Filters (`01_INTERNAL` Axis 2 — candidate home: Bond-card costs/taboos, unverified).
10. **Conduit stats on every ladder** — Galdr, Seer and Shaman grow with the Bonus for every character (`97` §14–15), though magic now opens only through Óðr ignition.
11. **Óðr and Pillar V** — a Chaos character with an Óðr pair cannot reach that pair's Pillar V (Lá Peak).
12. **Three Faces vs. "Óðr loses Pillars"** — the Óðr rule in §2 matches the travel face only; the fury face floods the body rather than leaving it (`01_INTERNAL_ARCHITECTURE_WIP.md` "The Three Faces of Óðr").
13. **Whole self vs. per-pair mechanics** — eligibility, path choice, Block System and mixed paths are written per pair (§2); the locked principle is the whole self.
14. **Önd's role** — the third gift (`01_INTERNAL` "The Three Gifts") has no mechanical role yet; END's Lá name "The Breath" is literally önd; Lóðurr's læti/litr overlap CHA's Lá side.

---

## 6. Character Identity — Saga Framing (LOCKED 2026-11-16)

A character is framed the way the sagas frame a person: by **description**, not class. Identity is described, not chosen.

| Element (*mannlýsing*) | Source example |
|---|---|
| **Lineage (ætt)** | Egill from Kveldúlfr, who was hamrammr — traits run in families |
| **Body & appearance** | *mikill ok sterkr*, *vænn* / *ljótr* — Egill huge, strong, ugly |
| **Accomplishments (íþróttir)** | Gunnar (*Njáls saga* 19): leaps his height in armour, fights with either hand, swims like a seal |
| **Mind** | Njáll (*Njáls saga* 20): *lögmaðr*, *vitr ok forspár* |
| **Temperament** | *skapmikill*, *ódæll*, *ójafnaðarmaðr* |
| **Standing / office** | *goði*, *bóndi*, *skáld*, *lögsögumaðr* — a position, not a type |
| **Earned name (viðrnefni)** | Eiríkr *rauði*, Skalla-Grímr, Önundr *tréfótr*, Hallgerðr *langbrók* — given by others, from body, deeds, or character |

- **Saga words for kinds of people are descriptors or offices** (hamrammr, berserkr, fjölkunnigr, forspár, völva, goði, skáld) — never classes.
- **Names are earned in play** — the world names the character from deeds (*viðrnefni*). Agent-made label lists (`01b`; `01_INTERNAL` Axis 2 archetypes; `99` Cross-Investment and Role Mapping) are provisional reference only; do not extend them.
- **The great saga figures mix** — Egill (strong body + poetry, runes, níð), Njáll (this-world lawyer + foresight), Gunnar (nearly pure Lá). The mix is what makes the saga; it is to be developed and balanced.
- **Berserkr as example (source):** fully in this world in body, the mind seized by Óðr — Óðr's fury face, a physical expression of Óðr (`01_INTERNAL` "The Three Faces of Óðr").

---
*Status: Foundational spark — consolidates decisions made across two sessions that previously existed only in conversation. §2 and §3's framing are settled; §5's items are not. Last Updated: 2026-11-16.*
