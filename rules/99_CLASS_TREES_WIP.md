# Class Trees — WIP Sketch

---

## Structure Note

Trees are **universal**. Every being — human, troll, spirit, giant — can invest in any tree. The tree defines the *mechanical domain* of power. What changes between beings is which **perks** are accessible within that tree.

Perk access is gated by four types of restriction:
- **[Social]** — Requires a specific cultural background, rank, or oath (e.g., only a Gothi-ordained character may take a sacrificial rite perk)
- **[Racial]** — Requires a specific body type or nature (e.g., a troll's stone-hide regeneration is not available to a human in the Wall tree)
- **[Alignment]** — Requires ORDER, WILD, or CHAOS alignment standing
- **[Skill]** — Requires a minimum Skill Tier (`03_skill_system.md`) as a prerequisite — the standing rule behind the one worked example already locked in (Twin Ward requires Shield Fighting 3+, §"Locked Seed Perks" below)

A [Social] restriction can also be satisfied by standing in a Faction/Divinity/Dedication Devotion Tree (`24b_BOND_AND_DEVOTION_PROGRESSION_TREE_WIP.md`) instead of a narrative background alone — this is a read-only dependency, not a shared point pool.

The Norse names below are the **human cultural expression** of each tree. Other beings arrive at the same tree through entirely different traditions — same mechanics, different flavor, different perk pool.

---

## The 8 Trees

*Trees carry no attribute pair (removed 2026-11-21 — no rule used it). Attributes reach a tree through its skills: skills have governing attributes (`03` Ch.2), and perks gate on skill tier ([Skill]).*

| # | Tree | Human Name | Tactical Role |
|---|---|---|---|
| 1 | **The Wall** | Skjaldborg | Frontline mass, formation holding |
| 2 | **The Blade** | Víkingr | Aggressive offense, weapon arts |
| 3 | **The Frenzy** | Berserkr | Disruptor, pain immunity, unstoppable |
| 4 | **The Hunt** | Bogmaðr | Ranged precision, skirmisher |
| 5 | **The Voice** | Skald | Support, morale, battlefield legacy |
| 6 | **The Rite** | Gothi | Sacred favor, recovery, divine law |
| 7 | **The Chant** | Galdrmaðr | Spoken charms — healing, warding, binding, command |
| 8 | **The Staff** | Seiðr | Foresight, travel, reaching into others |

*The Staff (renamed 2026-11-21 from the agent-made "Distaff"): the völva is the staff-bearer (*völr*, staff); Þorbjörg carries her staff to the rite (*Eiríks saga rauða* 4). Its role follows Odin's seiðr — knowing fate, travelling out, taking wit or strength (*Ynglinga saga* 7).*

---

## Traditions in the Sources (LOCKED 2026-11-16)

The traditions are **practices, offices, or states**, true to the sources. Work from this table.

| Tree (human name) | What it is in the sources | Kind | How one comes to it (source) | This world / Óðr |
|---|---|---|---|---|
| Skjaldborg (The Wall) | Battle formation | **Practice** | Trained together | This world |
| Víkingr (The Blade) | "Going a-viking" | **Practice** (activity) | By going | This world |
| Berserkr (The Frenzy) | Fury from Odin (*Ynglinga saga* 6) | **State** | Comes upon you; often inherited (Kveldúlfr, *Egils saga* 1) | **Óðr — fury** |
| Bogmaðr (The Hunt) | Skill / occupation | **Practice** | By doing | This world |
| Skáld (The Voice) | Poetry — the mead of Óðrerir | **Practice + gift** | Óðinn's gift, grown by use | **Óðr — inspiration** |
| Goði (The Rite) | Chieftain-priest | **Office** | Inherited, bought, shared, given (a *goðorð* is property) | This world (office) |
| Galdrmaðr (The Chant) | Spoken charms, runes | **Practice** | Learned; Óðinn won the runes hanging (*Hávamál* 138–145) | **Óðr — inspiration** (word) ⚠️ between |
| Seiðr (The Staff) | Trance-travel rite | **Practice** | Learned; Óðinn from Freyja (*Ynglinga saga* 7); needs singers (*Eiríks saga rauða* 4) | **Óðr — travel** |

- **Each Óðr face has its tradition:** fury → Berserkr; inspiration → Skáld (and Galdr); travel → Seiðr.
- **The three kinds match how the sources say you come to them:** practice is learned and grows by doing; office is given by society; state comes upon you or runs in the blood.
- **Each kind already has a home in the core rules:** practice → skills grow by use (`03`, `01c` Stage 5); office → Faction Bonds and [Social] gates (`24` §2.1); state → race/lineage, ignition, Wild mutation.
- **The sources mark some as outlawed or shameful:** berserk fury (Grágás), seiðr as *ergi* for men — see Notes below.
- **The current 8 trees mix all three kinds** (6 practices, 1 office, 1 state) under one "tree" structure and one point cost.

---

## Classes: Where Identities Emerge

The class list — cross-investment identities and role mapping, with primary/secondary tree and restrictions — lives in `tables/06_CLASSES_WIP.md`.

---

## The Cosmological Field: Where Synergy Lives

The trees are the investment structure. The three cosmological layers are the field those investments operate within. Synergy is not designed between trees — it emerges from how different tree investments disturb or resonate within the same layer.

| Layer | Nature | How Trees Touch It |
|---|---|---|
| **Önd — The Life-Current** | The medium. The animating substrate under Yggdrasil shared by all living things. | This-world traditions (Wall, Blade, Hunt; Rite as an office) operate primarily here — mastery of the physical medium through body, mass, and breath. *(Revised 2026-11-16 to follow the sources — see "Traditions in the Sources".)* |
| **The Wyrd** | The fate-pattern pressed into the Life-Current. Responds to density of action and mythic weight. | Óðr traditions reach this layer through their face — Frenzy (fury), Voice and Chant (inspiration), Staff (travel). Deep investment stirs it — creating Wyrd Pressure that others on the battlefield feel. |
| **Oaths** | The only layer with direction. Will imposed on both layers simultaneously. | The Voice also sits here (its root is Óðr's inspiration face, the mead of Óðrerir) — not by touching the Wyrd directly, but by binding the Life-Currents of others through word, song, and saga-weight. |

### The Frenzy Anomaly

> **Revised 2026-11-16 (follows the sources):** Frenzy is Óðr's **fury** face, not a Lá tree — Óðr floods the body (`01_INTERNAL_ARCHITECTURE_WIP.md` "The Three Faces of Óðr"). The involuntary onset described below is normal for the state, not an anomaly.

The Frenzy tree is the system's most interesting edge case: it is a Lá tree (body-level, Life-Current) that, at its highest tiers, punches involuntarily into the Wyrd. A berserkr does not reach for the Wyrd — the Wyrd reaches for them when their Önd burns hot enough. This is the historical basis: the berserkr-going was not a controlled state.

### Emergent Synergy: How the Field Works

Synergy is not tagged or designed. It emerges from what different characters are doing to the same layer simultaneously:

- Two characters both generating heavy Wyrd Pressure (Staff + Rite) create interference in the fate-layer that neither controls — the GM reads this as the battlefield becoming fate-dense, attracting Wyrd attention that could help or harm anyone.
- A character with deep Oath-weight (Voice) standing beside a character whose Önd is heavily disturbed (Frenzy at extremity) creates a pull between the directional layer and the raw life-current — morally and cosmologically unstable.
- A party running all Lá trees becomes nearly invisible to the Wyrd — low fate-signature, high physical coherence. Effective but mythically silent. They will not attract saga-attention.

---

## The Open Question: A 9th Tree?

**The Craft** — smiths, engineers, alchemists, poisoners — currently all map into **The Chant**. This works if The Chant is understood broadly as *the tree of knowledge and ordered making*, not only as magic. Runic craft and siege engineering share the same root: imposing human order on raw material.

The argument **for** a separate Craft tree: if crafting has meaningful combat and campaign-level mechanical weight (siege engines, poisoned weapons, enchanted armor), it may be too large to share a tree with ordered magic.

The argument **against**: in a low-fantasy world, the smith and the rune-worker are not separate traditions — Völund was both. Splitting them creates an artificial divide the sagas don't support.

**DECIDED 2026-11-21:** there will be **Craft trees** (plural) — The Chant does not absorb craft. **Trade belongs to the Craft trees** — it is not a class of its own. How many, and their structure, are OPEN. Craft classes: `tables/06_CLASSES_WIP.md`.

**DECIDED 2026-11-21 — Mounted:** mounted combat is important. It is a **skill** and will have **its own tree**. Structure OPEN; the skill: Mounted (`03_skill_system.md` Ch.2 §2).

This question is also the live edge of Pillar 2 (`00E_CORE_VISION_AND_PILLARS_WIP.md`) — every character's Campaign-function role (healer, scout, trader, armorer, smith, scholar) needs a tree home the same way Battle-function roles already have one. Smith/armorer/engineer/alchemist/scholar all land somewhere above (mostly The Chant). **Trader does not currently map to any tree at all** — Bartering exists only as a Skill (`03_skill_system.md`, Leadership & Legacy), with no Class Tree behind it. Flagged, not resolved.

---

## Locked Seed Perks (Cross-Reference)
- **The Wall** — **Twin Ward** (`02_perks_and_traits.md`): grants a second simultaneous Active Defense charge, resolving the Engagement Cap (Attention, `95_HISTORICAL_COMBAT_WIP.md`).
- **The Hunt** — Intended mastery path for **Detection** (Stealth vs. Navigation & Awareness opposed check, `03_skill_system.md` / `06_adventure_and_prep.md`). Signature perks not yet seeded.

## Notes / Open Questions

- The Staff should carry a built-in world-restriction, not just a perk lock. Historically seiðr was socially condemned (argr). Does that manifest as a faction standing cost? An oath requirement? A permanent social marker?
- The Frenzy tree was outlawed in Iceland (Grágás). Does the human perk pool reflect that — i.e., ORDER-aligned humans cannot access certain frenzy perks without breaking standing?
- Where does **Úlfhéðinn** (wolf-warrior) sit? High-tier branch inside The Frenzy, or its own tree? Different enough tactically (pack movement, DEX component) to split?
- **The Voice** may need two named internal branches: *the morale branch* (battlefield inspiration) and *the law branch* (negotiation, oath-brokering). Same tree, different perk pools.

---
