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

## Design Aim (Agreed 2026-11-23)

**A tactical RPG with more viable ways to play than *Classified: France ’44*, while keeping the choices as easy to read.** What Saga takes from *CF44*: legible roles, different soldiers excelling on different missions, a visible build direction, and a small set of rules (suppression, holding overwatch fire, a Leader giving someone else an opportunity to act) that produces teamwork. The concern: **you would probably play it much the same way on a second or third run.**

| Design element | What Saga should do |
|---|---|
| **Companions** | Offer a larger choice of playable companions, with greater differences between them. Each should have **several distinctive skills, traits, or features**. Two companions can pursue the same tree and still give the player different reasons to bring them. |
| **Builds** | Let the best use of a tree depend on **equipment, available resources, other party members, and circumstances outside the player’s control**, as well as the strategy the player chose. Two companies pursuing the same strategy can reasonably develop the same companion differently. |
| **Mission solutions** | Keep the pleasure of recognizing that a particular companion excels in an encounter. Give a company that brought someone else another credible way through it. |
| **Mission goals and rewards** | Give missions several goals that can be **mutually exclusive**. A player can execute a plan well and deliberately sacrifice one outcome to secure another. This goes beyond a ladder of failure, success, and greater success with more of the same reward. |
| **Campaign choices** | Let conflicts between opportunities arise from **time, distance, and position**. Two events can both happen. The company’s whereabouts determine which it can influence. Even the choice of shelter tonight can change what is reachable tomorrow. |

**Constraint: a coherent tactical core.** Tactical trees govern **combat and the mission map**. Campaign professions and saga relationships have their own place; they can influence who is available, what is at stake, and what follows from the mission.

---

## How Progression Works (Agreed 2026-11-23)

| Element | Agreed meaning |
|---|---|
| **Attribute pillars** | Pillars give **attribute development a direction** (`97`). Comparison with *Jagged Alliance 3*: that function is distinct from the active abilities and passive perks housed in the trees. |
| **Multi-tree development** | Saga has no fixed classes. A character usually has **one primary tree, commonly a fighting style, and a secondary tree**. Their combination gives the character a tactical identity. Several individual features distinguish the companion further. |
| **Main role-tree** | Expresses a **strategy for winning a battle**. Its identity comes from what the fighter acts on: HP, SP, BP, movement, position, or morale. |
| **Supportive aspect or style-tree** | Changes **how a companion performs their main role**. A supportive tree can be aggressive: Fury and Ambush are both examples. |
| **Utility tree** | Holds smaller, complementary jobs performed on the mission map. The player may bring a fighter partly because they can also treat a casualty, operate a machine, or gain entry to a guarded place. |
| **Casting tree** | Each distinct way of using wyrd has its own tree, with active and passive abilities. A caster can develop a conduit as their primary investment, or a fighting style can be complemented by casting. |
| **Corners** | **Main trees: three corners each — 18 main archetypes** (LOCKED 2026-11-23, `tables/06_TREES_WIP.md` §1). Corners do some of the work subclasses do in other RPGs. **The player must be able to look in a direction and imagine who the companion could become.** The archetype should suggest how that person plays and why they might be remembered in the saga. |

- **The corner format is an agreed experiment** (begun as four corners). First establish which trees deserve to exist, then design their corners. Supportive and utility trees: three corners each, LOCKED 2026-11-23 (`tables/06_TREES_WIP.md` §2–3). Corner count for casting trees is OPEN.

**Character identity (LOCKED 2026-11-23):**
- **Ancestry** shapes physical and temperamental tendencies (`01c` §5.1).
- **Culture** shapes learned fighting traditions (cultures: `tables/04_RACES_WIP.md` §2).
- **Corners** should evoke recognizable archetypes.
- **Cultural training appears in the supportive trees**, through distinctive nodes and named archetypes — so elites with the same role fight differently. Culture usually **replaces an existing supportive corner** through its cultural name and training nodes; in rare cases a tradition has **its own supportive tree**. The six main trees and their corners are **shared across cultures**. An Elf and a Dwarf can both develop as Counterfighters under the same Defender tree; their supportive training gives them different techniques and culturally recognizable class identities.
- **LOCKED 2026-11-23 — no limit on trees held; tree points are limited.** A character may hold any number of trees; the limited tree points (`01c` §3) force the choice — spread them and become a jack of all trades, or concentrate for depth. Whether breadth is a real trade-off depends on the tree-depth power curve (`01c` §5.5).
- **OPEN:** spending allowances, and any restrictions between primary, secondary, utility, and casting investments.
- **Design method:** start from an actual fantasy RPG archetype (e.g. a Monk), ask what the player expects to do as that character, then see which Saga tree supports it. Saga-specific names carry the familiar fantasy equivalent in parentheses.

**The roster** — 6 main role-trees, 8 supportive, 2 utility (working), 3 casting — and its corners live in `tables/06_TREES_WIP.md`.

---

## Superseded: The 8 Trees (2026-11-23)

The eight universal trees are replaced by the roster above. Where each went:

| Old tree | Human name | New home |
|---|---|---|
| The Wall | Skjaldborg | Defender (main); Formation Fighting (supportive) |
| The Blade | Víkingr | Assault (main) |
| The Frenzy | Berserkr | Fury (supportive) |
| The Hunt | Bogmaðr | Archer, Skirmisher (main) |
| The Voice | Skald | Commander (main) |
| The Rite | Gothi | No tactical tree — an office (Faction bonds, [Social] gates, `24` §2.1); magical healing goes to casting |
| The Chant | Galdrmaðr | Galdr, Rúnar (casting) |
| The Staff | Seiðr | Seiðr (casting) |

*The Staff (renamed 2026-11-21 from the agent-made "Distaff"): the völva is the staff-bearer (*völr*, staff); Þorbjörg carries her staff to the rite (*Eiríks saga rauða* 4). Its role follows Odin's seiðr — knowing fate, travelling out, taking wit or strength (*Ynglinga saga* 7).*

---

## Traditions in the Sources (LOCKED 2026-11-16)

The traditions are **practices, offices, or states**, true to the sources. Work from this table. *The tree column uses the superseded 8 (mapping above); the table stands as source evidence.*

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

The class list — cross-investment identities and role mapping, with primary/secondary tree and restrictions — lives in `tables/07_CLASSES_WIP.md`. Saga has no fixed classes (How Progression Works); the list is reference for how investment reads.

---

## The Cosmological Field: Where Synergy Lives

*Uses the superseded tree names (mapping above).*

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

## Craft, Trade and Mounted (Revised 2026-11-23)

- **Craft and Trade are campaign professions, not tactical trees.** This supersedes "Craft trees, with Trade in them" (DECIDED 2026-11-21). Their home is OPEN. The mission-map parts go to the utility trees **Machine** (Artillerist, Trapper, Wright) and **Physic & Poison** (Herbalist, Alchemist, Poisoner) (`tables/06_TREES_WIP.md` §3).
- **Mounted** is a **skill** (`03_skill_system.md` Ch.2 §2). **Mounted Combat is a corner of Momentum**, not its own tree. This supersedes "Mounted will have its own tree" (DECIDED 2026-11-21).
- **Pillar 2** (`00E_CORE_VISION_AND_PILLARS_WIP.md`): every Campaign-function role (healer, scout, trader, armorer, smith, scholar) needs a home. Healer and scout now have utility trees; trader, armorer, smith and scholar wait on the campaign-profession home. Bartering exists only as a Skill (`03`, Leadership & Legacy).

---

## Locked Seed Perks (Cross-Reference)
- **Old The Wall** (new home OPEN: Defender or Formation Fighting) — **Twin Ward** (`02_perks_and_traits.md`): grants a second simultaneous Active Defense charge, resolving the Engagement Cap (Attention, `95_HISTORICAL_COMBAT_WIP.md`).
- **Old The Hunt** (new home OPEN) — Intended mastery path for **Detection** (Stealth vs. Navigation & Awareness opposed check, `03_skill_system.md` / `06_adventure_and_prep.md`). Signature perks not yet seeded.

## Notes / Open Questions

- *(Old tree names; see the mapping.)* The Staff (now the Seiðr casting tree) should carry a built-in world-restriction, not just a perk lock. Historically seiðr was socially condemned (argr). Does that manifest as a faction standing cost? An oath requirement? A permanent social marker?
- The Frenzy (now Fury) was outlawed in Iceland (Grágás). Does the human perk pool reflect that — i.e., ORDER-aligned humans cannot access certain frenzy perks without breaking standing?
- Where does **Úlfhéðinn** (wolf-warrior) sit? High-tier branch inside The Frenzy, or its own tree? Different enough tactically (pack movement, DEX component) to split?
- **The Voice** may need two named internal branches: *the morale branch* (battlefield inspiration) and *the law branch* (negotiation, oath-brokering). Same tree, different perk pools.

---
