# Tactical RPG BoardGameSaga — Development Tracking

This document tracks features that have been discussed or partially implemented, but require a "Deep Dive" or specific design phase before being finalized.

## 1. High-Priority Design Deep-Dives
| Date | Feature | Status | Notes |
| :--- | :--- | :--- | :--- |
| 2026-04-18 | **Internal Architecture & Magic** | SOLIDIFIED | Fused Soul-Trio (Önd, Óð, Lá) with 6 Pillars and Historical Laws. |
| 2026-04-18 | **Universal Alignment Physics** | SOLIDIFIED | Replaced generic class mechanics with 3 universal alignment physics (Order, Wild, Chaos). |
| Upcoming | **The Rule of Wild (Trade-off Mutations)** | PENDING | Design physical and mystic wild mutations across the 6 attributes. |
| Upcoming | **Resource Consumption** | STAGED | Definition of HP/SP/MG/Madness tactical expenditure. SP pool = `END × 3` + mods (locked 2026-11-16; Body/Frame removed from the formula). |

## 2. Advanced Tactical Content (Restricted to Classes/Monster Trees)
- [x] **Simple Perk Design:** Document created ([02_perks_and_traits.md](file:///c:/Workspace/tactical-rpg-boardgamesaga/rules/02_perks_and_traits.md)) with Organic Growth policy and three seed perks (*Unyielding*, *Hard Head*, *Nerves of Steel*).
- [ ] **The "Saga Choice" Blocks:** Systems for allowing characters to "Sacrifice" gear or take permanent injuries to avoid lethal blows.
- [ ] **Advanced Momentum Carry-over:** "Cleave" or "Momentum follow-up" rules for specific heavy-weapon classes.
- [ ] **Expanded Hit Table (3d6):** Assign specific mechanical meanings or activations to every value (1-20+), potentially triggered by weapons, skills, or perks.
- [ ] **Impulse/Momentum Tracking (Suggestion):** Evaluate as an alternative to the AP Segment system to increase fluid tactical pressure.
- [x] **Balance System Overhaul:** Shifted from flat recovery to **Balance States** (Stable, Unstable, Stumbling) with Defense-only penalties. Implemented **BP Soak (Steadfast/Grounded)** and stability-based resistance loss.
- [ ] **Structural Resistance (Body + Frame):** Body + Frame provide passive resistance against HP/SP/BP damage (`01_system_foundations.md` Ch.7 §3), stacking on top of Natural Armor and Physical Weight/BP Soak. Frame additionally reduces avoidance capability and raises the SP cost of avoidance actions as it increases. Formulas for all three effects undecided — pending Deep Dive.
- [ ] **Tempo (Mental/Readiness) Initiative Integration:** Tempo's Control↔Execution poles modify Readiness/Initiative and defend-against-N-attackers capacity (`97b_ATTRIBUTE_FLAVOR_AXES_WIP.md`). Needs Deep Dive on how this composes with the existing Initiative formula (`01_system_foundations.md` Ch.6) and how the opponent-count thresholds are set.
- [ ] **Poison (Weapon Tag):** Triggers whenever the wielder's attack confirms a **Bleed** application on the target (regardless of source). Effect magnitude and duration undecided — pending Deep Dive.
- [ ] **Panic/Frenzy/Freeze Aftermath (Category D):** None of the Flee/Frenzy/Freeze branches (Controlled, Desperate, Disciplined) have a defined exit or cost. Known source: the *berserksgangr* crash — extreme physical weakness, shivering, deep depression (`95_HISTORICAL_COMBAT_WIP.md`, Entry 38). Open questions: does Frenzy Tree investment (Controlled/Disciplined Frenzy) reduce or exempt the crash, or does it only buy back target-discrimination *during* the fight and not the aftermath? Does Desperate Flee have any rally/recovery path back into the fight (no such mechanic currently exists), or is Controlled Flee's exit simply cost-free since it's a voluntary choice? Desperate Freeze (tonic immobility) recovery condition also undefined.

## 3. Cosmological Layer System (New — 2026-05-25)

The three cosmological layers (Önd/Life-Current, Wyrd, Oaths) have been established as the world-scale architecture. The following design questions need resolution before these layers have mechanical expression.

| Priority | Question | Notes |
| :--- | :--- | :--- |
| **HIGH** | **Wyrd Pressure — how does it manifest in play?** | Deep Óðr-tree investment stirs the Wyrd. Does this create a passive field effect on the battlefield hex? A GM-facing tracker? A visible status? Needs a mechanic that is atmospheric, not a combo table. Conceptual chain now fixed (2026-11-15): Wyrd-legibility → Wyrd-Pressure → Troth-Gravity → Saga-Renown/Wyrd-Scar (`01_INTERNAL_ARCHITECTURE_WIP.md` Soul Trio) — this entry is about the mechanical manifestation of stage 2 specifically, still open. |
| **HIGH** | **Oath Web — individual vs. party oaths** | *MOVED TO `96_OATHS_WIP.md`* |
| **MEDIUM** | **Life-Current disturbance (combat)** | When many beings bleed and die on a hex, the Life-Current is disturbed. Does this affect subsequent battles on that hex? Healing rolls? Spirit/Wyrd interaction? Relevant to both monster design and campaign-layer. |
| **MEDIUM** | **Non-human beings and the three layers** | Trolls, spirits, giants, undead — how do they relate to each layer differently? A spirit may exist purely in the Wyrd layer with no Önd anchor. An undead may have severed Önd but retained Lá. This affects which tree perks they can access. |
| **MEDIUM** | **The Frenzy anomaly — involuntary Wyrd contact** | The Frenzy tree at high tiers touches the Wyrd without intent. Design the threshold: at what investment level does this trigger, what does it look like mechanically, and who else on the battlefield feels it? |
| **LOW** | **Oath-breaking cosmological cost** | *MOVED TO `96_OATHS_WIP.md`* |
| **LOW** | **All-Lá party — mythic silence** | A party running exclusively Lá trees becomes fate-invisible. This is a feature, not a bug. Design the tradeoff: what do they lose (saga-renown, Wyrd-assistance, divine attention) and what do they gain (resistance to fate-manipulation)? |

## 4. World & Narrative Synergies
- [ ] **Character Progression and Body:** System for how Body, Frame, and Size evolve with character growth and training.
- [ ] **Wyrd Layer Integration (Combat):** How "Blessed" or "Cursed" weapon states modify the weapon impact tables.
- [ ] **Generational Gear:** Rules for how armor damage (Chapter 11) persists across saga generations if not repaired.

## 4b. Monster Design
- [ ] **Rules for Massive Impact:** Handling impacts that significantly exceed the target's Body scale (Overrun/Momentum).
- [ ] **Non-Human Impact Tables:** Unique tables for claws, bites, and giant blunt impacts (e.g., trolls).

## 5. Campaign Layer (New — 2026-09-14)
Tracks concrete content and open decisions for `20_CAMPAIGN_CORE_WIP.md` through `26_CAMPAIGN_ECONOMY_WIP.md`, and their touchpoints in `96_OATHS_WIP.md` and `00A_DESIGN_ATOMS.md` §7.

**Required concrete lists:**
- [ ] Complete race list and which races have devotional storylines/race bonds (`24_BONDS_AND_DEVOTION_WIP.md` §2.5).
- [ ] Complete attribute list for dedication paths (`24_BONDS_AND_DEVOTION_WIP.md` §2.3).
- [ ] Special historical classes requiring devotion/class bonds (`24_BONDS_AND_DEVOTION_WIP.md` §2.4).
- [ ] Exact worldly factions beyond the three Human Empire powers (`22_FACTIONS_WIP.md` §2).
- [ ] Final five Norse divinities and their trees (`23_DIVINITIES_WIP.md` §2).
- [ ] Concrete bond achievements, trees, Traits, costs, requirements, taboos, exclusivities per bond (`24_BONDS_AND_DEVOTION_WIP.md` §8; tree skeletons in `24b_BOND_AND_DEVOTION_PROGRESSION_TREE_WIP.md`).
- [ ] Concrete strategic challenges/opportunities testing each form of power (`20_CAMPAIGN_CORE_WIP.md` §4).
- [ ] Possible destinies without converting them into selectable linear paths.

**Mechanically open:**
- [ ] Exact terminology/interface distinction between available devotion, tree points, and unspent devotion (`24_BONDS_AND_DEVOTION_WIP.md` §4).
- [ ] Exact recovery/regaining rules after total-devotion loss (`96_OATHS_WIP.md` §12, item 2).
- [ ] Exact consequences of destroying vs. abandoning a bond.
- [ ] Exact mathematical scaling of devotion-dependent benefits (`f(TotalDevotion)`).
- [x] Exact relationship between party bonds and the Cohesion mechanic/resource, and Cohesion's mechanical nature — RESOLVED: plain numeric value, grows from time-in-party/shared victories/Party Bond rewards; keeping a party intact (vs. churning it) independently grants Cohesion (`26_CAMPAIGN_ECONOMY_WIP.md` §3.2).
- [ ] Exact numeric values: growth rate per source, Tolerance capacity per leader attribute/ability, tension cost per friction-causing action.
- [ ] Acceptance trigger — what specifically promotes a new hire from unaccepted to Accepted, so their Individual Cohesion starts contributing to Party Cohesion (`26_CAMPAIGN_ECONOMY_WIP.md` §3.2).
- [ ] Exact Cohesion → Moral Pressure DC-reduction curve and the auto-negate threshold for Route Checks (`05_battle_core.md` Ch.8 §2).
- [ ] Whether conditional supplies (fodder, medicine, repair materials, reagents, ship maintenance) become tracked resources or remain event/equipment effects (`26_CAMPAIGN_ECONOMY_WIP.md` §4).
- [ ] How persistent-world time advancement transforms factions, places, divinities, and unresolved events (`25_LEGACY_WIP.md` §2).

## 6. Character Build Pipeline (New — 2026-11-09)
Tracks open decisions for `01c_CHARACTER_BUILD_PIPELINE_WIP.md`, consolidating the three-currency progression model (Skill/Attribute/Tree-Faction).

- [x] Race-modifies-attribute conflict — resolved 2026-11-15: race shapes both expression and progression; general strength + flavor-direction amplification allowed (`01c` §5.1).
- [ ] Racial progression mechanism — cost modifier, starting-value offset, or both; how flavor-direction amplification is computed (`01c` §5.1).
- [x] Exact attribute cost formula — locked 2026-11-15; revised 2026-11-20: reaching value N costs N points (`01c` §5.2).
- [x] Skill progression — locked 2026-11-20: skill XP pool, insight test at 100, 5 × N progress points per tier, parallel +1 sources (`03_skill_system.md` Ch.3).
- [x] Unified Pillar/Ignition model — locked 2026-11-15 (`01c` §2): new Bonus formula, pair ignition via saga/Bond, Lá/Óðr per pair, Pillar I Triples Rule, character-level alignment bonuses.
- [ ] Whether Flavor Axes interact with Pillar Ignition at all (`01c` §5.3).
- [x] Neutral-path revision — locked 2026-11-16 (`01c` §2): Lá Pillars are the neutral path, Óðr ignition forgoes Pillars, any ignition = Triples Rule + Bond consequence.
- [x] Lá/Óðr cost of mixing — resolved 2026-11-16: off-path rule + predefined penalties incl. Cross-Strain (`01c` §5.7).
- [x] Whether Pillars II–V each need their own saga/Bond event — resolved 2026-11-16: no, neutral Pillars open by value (`01c` §5.8).
- [ ] Re-home parked material: archetype Mechanical Filters (access/friction locked 2026-11-21; Óðr Matrix removed to `98b`) (`01_INTERNAL` Axis 2) (`01c` §5.9). Lá value-5 row re-homed as Pillar I.
- [x] Conduit stats on every ladder vs. magic only via Óðr ignition — resolved 2026-11-22: the Conduit is the technique's Attribute Bonus (`01c` §5.10).
- [ ] Óðr pair and Pillar V for Chaos (`01c` §5.11).
- [ ] Three Faces of Óðr vs. "Óðr loses Pillars" — the rule fits travel only (`01c` §5.12).
- [ ] Rewrite per-pair ignition mechanics to the whole-self principle (`01c` §5.13).
- [ ] Önd's role as the third gift; "The Breath" = önd; læti/litr vs. CHA's Lá side (`01c` §5.14).
- [x] Saga framing of identity, earned names, traditions as practice/office/state, Frame fixed — locked 2026-11-16 (`01c` §6; `99` "Traditions in the Sources"; `97b` §3.1).
- [x] What generates *reynsla* (experience) — resolved 2026-11-21: missions, events, and interactions with both realms (`01c` §4).
- [ ] *Þroski* (level-up) threshold value (`01c` §5.4).
- [ ] Tree-depth power curve — if Class Tree cost is flat, what paces perk strength growth (`01c` §5.5).
- [ ] Master Trainer mechanism — cost and access condition undesigned (`01c` §5.6, `26_CAMPAIGN_ECONOMY_WIP.md` Levers).

## 7. Core Vision Pillars (New — 2026-11-15)
Tracks open items surfaced while implementing `00E_CORE_VISION_AND_PILLARS_WIP.md`'s four Pillars.

- [ ] **Trader** has no Class Tree mapping at all (`99_CLASS_TREES_WIP.md` — Bartering exists only as a Skill, no tree behind it) — distinct from and smaller than the general 9th-Tree/Craft question.
- [ ] Belief/Direction tier (`96_OATHS_WIP.md` §8b) — mechanism entirely undesigned: what it grants, if anything, and how/whether it's tracked.
- [ ] **In-play time resolution** — how campaign time passes *during* a saga (real-time, per stretch of campaign time, or per party action). Distinct from between-saga persistent-world time advancement (§5, `25_LEGACY_WIP.md` §2). Must preserve the tactical significance of time: party speed decides which opportunities are within reach.
- [ ] **Faction clock** — mechanism by which factions move on their own clock (`22_FACTIONS_WIP.md` §1); "Faction Pulse" (`06_adventure_and_prep.md` Ch.12) undefined.
- [ ] **Mission objectives** — the frame is set (objectives are two-way and can change inside the event, `27_EVENTS.md` §3); no objective content or catalogue exists yet (`20_CAMPAIGN_CORE_WIP.md` §2b).
- [ ] Campaign Map weighting — "cities, nodes, and places of interest carry particular weight beforehand" (`20_CAMPAIGN_CORE_WIP.md` §2b) has no formula or numeric representation yet.

## 8. Events (New — 2026-11-18)
Tracks open items for `27_EVENTS.md`.

- [x] **Divine-recognition carrier** — RESOLVED 2026-11-18: an event reward; with a bond, also a bond achievement. Favour needs no bond (`27` §6).
- [x] **Worldly recognition terms** — RESOLVED 2026-11-18: three forms of *orðstírr* (`27` §6).
- [ ] **Praise-verse** (*erfidrápa*) — no canon home for verse that carries fame onward (`27` §6).
- [x] **Enmity data** — RESOLVED 2026-11-18: source table in `23_DIVINITIES_WIP.md` §4; the event decides which kind applies.
- [x] **[3.2] Others seek something from this party** — RESOLVED 2026-11-20: own events in `events/10_SOUGHT_OUT_TRIGGER_WIP.md` (`27` §3).
- [x] **Event with several triggers** — RESOLVED 2026-11-20: triggers are tags; the event is written under its first tag (`27` §7).
- [x] **Event-card format** — RESOLVED 2026-11-20: tags + Opening, Paths, Choices, Battle or peace, Resolution (`27` §10).
- [x] **Outcome summary format** — RESOLVED 2026-11-20: part of Resolution; how much it shows depends on the party (`27` §10).
- [x] **Knowledge & rumour** — RESOLVED 2026-11-20: works as conditions (`27` §8).
- [ ] **Scar and injury content** — post-battle resolution frame locked (`11_injury_and_scars.md` §1); the scars themselves, and how the *meiri sár* grading enters play, are OPEN.

## 9. Trees and Progression (New — 2026-11-23)
Tracks open items for `99_CLASS_TREES_WIP.md` and `tables/06_TREES_WIP.md`.

- [ ] Corners for every tree — confirmed so far: Mounted Combat (Momentum), Artillerist (Machine), Scout and Thief (Fieldcraft).
- [x] Number of trees a character may access — locked 2026-11-23: no limit; tree points are limited (jack of all trades vs. depth) (`99` How Progression Works).
- [ ] Spending allowances; restrictions between primary, secondary, utility and casting investments.
- [ ] Whether receiving a charge deserves its own Momentum corner; a progression rule for flight.
- [ ] Physic & Poison fourth corner; the scope of Alchemy.
- [ ] Parley's tree placement (skill in `03` Ch.2 §4).
- [ ] Home for campaign professions (Craft, Trade) — outside the tactical trees (`99`).
- [ ] Remap `tables/07_CLASSES_WIP.md` tree columns to the new roster.
- [ ] New homes for the seed perks — Twin Ward (Defender or Formation Fighting), Detection (Fieldcraft or Skirmisher) (`99` Locked Seed Perks).
- [ ] **Morale as a resource** beside HP/SP/BP. Tactical identity set through Commander, Fury and Intimidation. Working proposal: individual morale influenced by perceptible events, incl. what happens to nearby companions; at depletion a fighter may yield or try to withdraw. Open: spendable or not, what ordinary hits do to it, how yielding, withdrawal and recovery work. Three different losses: a companion can lose the ability to act, the company the field, the party what it came for.
- [ ] **Company, shelter and progression between missions.** Chosen: a company with hosts and allies; shelter for the night is a campaign-level tactical choice (who can receive it, what it reaches, where it can be tomorrow, what passes while it stays). A longer stay gives time for training and reflection — experience gained during events, integrated afterward. Open: the place and timing of level-up (`01c` §4).

---
*Created: 2026-04-10*
