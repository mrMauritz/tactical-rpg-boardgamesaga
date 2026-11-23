# Events: Where the Party Meets the World

> **STATUS: LOCKED (2026-11-20).** This file fixes what an event *is*, how it responds to the party, its triggers, outcomes, and format (§10). Concrete events live in `events/`; open items owned by other files are tracked in `90_TODO_development_tracking.md` §7–8.

> **WHEN TO READ:** Before writing or resolving any event, mission, or event-driven consequence. The campaign kernel is `20_CAMPAIGN_CORE_WIP.md`; this file owns the event as a unit.

**Source:** User document *BG Saga — Accepted Event and Saga Design Points* (2026-11-17), point numbers kept as `[x.y]`. Point 2.2 was removed by the User and is not carried here.

---

## 0. Terms (LOCKED 2026-11-20)

| Term | Meaning |
|---|---|
| **Campaign map** | Where the party moves in the world; moving on it can trigger events (`20_CAMPAIGN_CORE_WIP.md` §2b) |
| **Event** | A meeting between party and world — a dinner, arriving at a bridge, reaching a tavern |
| **Action** | What the party does within an event — lockpick, bribe, pickpocket; offered through the paths of action (§10). Battle actions keep their prefixes (Major, Minor, Quick, Heavy — `05_battle_core.md`) and are timed in segments; an event action takes no prefix. The same act can be both: a lock picked at a dinner is an event action, a lock picked while sneaking past guards is a Heavy Action on the tactical map (`06_adventure_and_prep.md` Ch.13) |
| **Mission** | What an event can lead to — objectives on the tactical map; winning a battle is one kind, sneaking past guards another |
| **Tactical map** | Where missions take place (`20_CAMPAIGN_CORE_WIP.md` §2b; `00A_DESIGN_ATOMS.md` Part II §5.2) |

## 1. The Event as a Unit

**LOCKED 2026-11-18:** Events are their own unit. An event is where a particular party meets the world. Its existing touchpoints, not restated here:

| Aspect | Owner |
|---|---|
| Events sit on the campaign map, whose nodes are weighted beforehand | `20_CAMPAIGN_CORE_WIP.md` §2b |
| An event can lead to a **mission** on the tactical map, with its own objectives — a battle is one kind | `20_CAMPAIGN_CORE_WIP.md` §2b |
| Outcomes seed back onto the map (Reality and Wyrd layers) | `06_adventure_and_prep.md` Ch.15 |
| What events may do to a companion (awaken the past, reveal hidden character, move alignment, fracture loyalty…) | `21_COMPANIONS_WIP.md` §2 |
| A shared event pile across playthroughs; persistence decided by play mode | `20_CAMPAIGN_CORE_WIP.md` §4 |
| Eligibility (requirements and taboos) | `00A_DESIGN_ATOMS.md` Part II §7 |

### 1.1 Integration Principle [6.1]

**LOCKED 2026-11-17:** Everything in this file works through the **same event conditions, outcomes, and existing character and bond information** — no parallel subsystem. An earned name is both identity and an event condition. Failing a god can directly create an opening with its enemy. Several effects stay connected through a small amount of information (`20_CAMPAIGN_CORE_WIP.md` §8, Guardrail 10).

---

## 2. Events Respond to the Party

**LOCKED 2026-11-17:**

- **[1.1] Conditional aspects** — every event has aspects that depend on the party: what appears, what is possible, how people and creatures react, which rewards are available. The party's skill pool, specializations, alignment, and other qualities make different expressions of the same event possible.
- **[1.2] Interacting conditions** — some possibilities depend on combinations of qualities: a skill may make an action possible while a bond makes someone willing to entrust it to the party. Combinations resolve through the requirement logic of `00A_DESIGN_ATOMS.md` Part II §7 — every requirement must hold, no taboo may trigger.
- **[1.3] Partial recognition** — the party may recognize that something matters before understanding how to engage with it, giving the player something concrete to investigate. This is the event-scale form of the unreadable world (`20_CAMPAIGN_CORE_WIP.md` §3, Guardrail 11).

> *Players discover more within a single playthrough as they come to understand how their particular party encounters the world.*

---

## 3. Goals Emerge Between Party and Event

**LOCKED 2026-11-17:**

- **[3.1] Two-way goals** — goals appeal differently to different parties, and the party's prior decisions within an event trigger different goals: what the party finds attractive in the event, and what the event responds to in the party.
- **[3.3] Goals change inside the event** — commitments and actions can introduce or change objectives as the event develops. For a mission, objectives define *what* the mission requires; how the fight is won stays with `20b_STRATEGY_AND_BALANCE_MAP_WIP.md` §1 and §7.10.
- **[3.4] Hidden identity** — events and gameplay can reveal a character's hidden identity (`21_COMPANIONS_WIP.md` §2, "Reveal hidden character").

**LOCKED 2026-11-20 — [3.2] Others seek something from this party:** participants may ask for protection, offer terms, or issue a challenge because of the companions, bonds, or identity they meet. It has its own events, in their own trigger file (`events/10_SOUGHT_OUT_TRIGGER_WIP.md`).

> *The party's identity shapes both what the player pursues and what others seek from the party.*

---

## 4. Choosing Events Expresses the Party's Direction

**LOCKED 2026-11-17:**

- **[4.1] Choosing** — the campaign lets players choose events, sometimes through difficult decisions. Play style, bonds, and alignment impose **hard** and **soft** restrictions.
- **Hard restrictions** are taboos and unmet requirements (`00A_DESIGN_ATOMS.md` Part II §7; bond exclusivities, `24_BONDS_AND_DEVOTION_WIP.md` §5). They define commitments. **LOCKED 2026-11-20 — play style** restricts through what play has left behind, since every outcome can become a condition (§8): outlawry — none may feed, shelter, or aid the outlaw, who has no standing at the Þing (*Grágás*, Vígslóði; *Grettis saga*); a broken oath (`24_BONDS_AND_DEVOTION_WIP.md` §4.2; `96_OATHS_WIP.md` §7); alignment moved by deeds (`96_OATHS_WIP.md` §4); an earned name or repute ([2.3]). No separate play-style tracker (`20_CAMPAIGN_CORE_WIP.md` §8, Guardrail 10).
- **[4.2] Soft restrictions** are concrete: acting against a bond may require compensation, create an obligation, weaken support, or put something valued at risk. They let commitments be tested through play.

**LOCKED 2026-11-18 — the event decides:** a soft cost takes whatever form makes sense in that event. Nothing is fixed in advance. Forms already present in canon and the sources:

- **Weaken support** — devotion loss (`24_BONDS_AND_DEVOTION_WIP.md` §4.2); Tolerance tension (`26_CAMPAIGN_ECONOMY_WIP.md` §3.1).
- **Create an obligation** — oath and the Oath-Web (`96_OATHS_WIP.md` §6–7).
- **Require compensation** (*bætr*, set by settlement or arbitration) — any of: silver or goods counted in ounces (*Grágás*, Baugatal; triple wergild for Höskuldr, *Njáls saga* ch. 123; Money, `26_CAMPAIGN_ECONOMY_WIP.md` §3); self-judgment, where the wronged side sets the terms (*sjálfdæmi*, *Hrafnkels saga*); exile or outlawry (*Grágás*; *Grettis saga*; *Gísla saga*); sacrifice to a wronged power (Þorkell's ox for Freyr, *Víga-Glúms saga* ch. 9; `96_OATHS_WIP.md` §6).
- **Put something valued at risk** — up to the bond card itself (`24_BONDS_AND_DEVOTION_WIP.md` §4.2, severe case).

- **[4.3] Time-sensitive events** — some events alter with time. Depends on in-play time resolution and the faction clock (`90_TODO_development_tracking.md` §7).

---

## 5. Identity Grows Through Play

**LOCKED 2026-11-17:**

- **[2.1] Deeds, names, achievements** — character identity develops through play. An achievement can have practical value, grant a small bonus, or give the character a name or epithet, giving the character's history weight.
- **[2.3] Recognition through event conditions** — an earned name or achievement itself serves as an event condition: the epithet that identifies the character can trigger a response when relevant.

**LOCKED 2026-11-18 — one term, per [6.1]:** an **achievement** is an earned deed recorded on the character. Achievements are bound to events and missions (LOCKED 2026-11-21); some Tree/Devotion unlocks come from them (`01c` §3). A **bond achievement** (`24_BONDS_AND_DEVOTION_WIP.md` §4) is the case where the deed's outcome is devotion in a particular bond — not a second kind of thing.

**LOCKED 2026-11-20 — the small bonus takes a grounded form** (`00A_DESIGN_ATOMS.md` Part II §3, no floating modifiers); the event decides which:

| Form | Grounding |
|---|---|
| **Gift** — a thing (Material, §8) | Helgi named and given a sword (*Helgakviða Hjörvarðssonar*, prose and st. 6–9); Æthelstan's gold ring and two chests of silver to Egill (*Egils saga* ch. 55) |
| **Access** — doors open | The earned name as event condition ([2.3]) |
| **Trait** — a lasting change | Bond grants are mostly Traits (`24_BONDS_AND_DEVOTION_WIP.md` §6; `02_perks_and_traits.md`) |
| **Effect through an existing pipeline** | As Cohesion lowers the Moral Pressure DC (`26_CAMPAIGN_ECONOMY_WIP.md` §3.2; `05_battle_core.md` Ch.8) |

**In the sources:** the earned name (*viðrnefni*) is already locked as part of character identity — given by others, from body, deeds, or character (`01c_CHARACTER_BUILD_PIPELINE_WIP.md` §6). Because a wound can name a person (Önundr *tréfótr*, for the leg lost at Hafrsfjörðr, *Grettis saga* ch. 2), a setback can become identity. A name is given with a gift: the valkyrie Sváva names the silent Helgi and gives him a sword (*Helgakviða Hjörvarðssonar*, prose before st. 6 and st. 6–9). A setback can therefore become identity, and identity a condition — the same small information doing several jobs [6.1].

> *A small benefit can carry considerable weight when the player remembers earning it.*

---

## 6. Daring, Achievements, and Setbacks Create the Saga

**LOCKED 2026-11-17:**

- **[5.1] Curiosity and daring** — no obvious right answer or universally correct direction; curiosity persists throughout play. Injuries and setbacks belong to the experience (`11_injury_and_scars.md`). High risks offer high rewards; achievements and setbacks together create the saga. **Daring can be rewarded among the gods even when the worldly outcome is costly.**
- **[5.2] Direct and immediate recognition** — recognition of daring is viable when the deed is directly and immediately identifiable. A possible implementation is to attach its recognition to the relevant event choice or result at resolution, using the conditions already available there.
- **[5.3] Setbacks reveal another direction** — a setback may lead toward something the party would otherwise never have pursued; failing a god could attract that god's enemy. Handled directly through the event and its consequences.
- **[5.4] Triumph has consequences** — success can bring outcomes unwelcome or harmful to that particular character or party.
- **[6.2] Balance principle** — divine recognition of daring can coexist with a lasting worldly loss and need not compensate it in full. The player can value the deed while still feeling its cost; choosing when to risk something stays meaningful.

> *"To dare is rewarded among the gods if not in the real world" gives this aspect its strongest direction. It allows a costly outcome to retain meaning.*

**Two registers of recognition** — [5.1] separates them, and so do the sources:

| Register | In the sources | In canon |
|---|---|---|
| **Worldly** — what people say | *Deyr fé, deyja frændr… en orðstírr deyr aldregi* — wealth and kin die, word-fame never (*Hávamál* 76–77) | *Orðstírr* (below) |
| **Divine** — what the gods regard | Odin takes the daring to Valhalla at the cost of their worldly life (*Eiríksmál*; *Hákonarmál*) | Event reward; with a bond, also a bond achievement (below) |

**LOCKED 2026-11-18 — Orðstírr, one fame in three forms:**

| Form | Source | Canon term |
|---|---|---|
| Fame in life — the repute a deed earns | *Hávamál* 76 (*orðstírr*) | **Renown** (`06_adventure_and_prep.md` Ch.12; `20b_STRATEGY_AND_BALANCE_MAP_WIP.md` BO5) |
| The judgment on the dead, which lasts | *Hávamál* 77 (*dómr um dauðan hvern*) | **Saga-Renown / Word-Fame** (`01_INTERNAL_ARCHITECTURE_WIP.md`, Heroic Resolution) |
| The name others give, attached to the person | *viðrnefni* (`01c_CHARACTER_BUILD_PIPELINE_WIP.md` §6) | **Earned name / epithet** (§5) |

Praise-verse that carries fame onward (*erfidrápa*; *Eiríksmál*, *Hákonarmál*) has no canon home yet (`90_TODO_development_tracking.md` §8).

**LOCKED 2026-11-18 — Favour without a bond:** a person can be rewarded or favoured by gods, factions, and other powers without holding a bond. A bond is a special connection — the sources' *fulltrúi*, the god one "fully trusts" (Hrafnkell and Freyr, *Hrafnkels saga* ch. 2; Þórólfr Mostrarskegg and Thor, *Eyrbyggja saga* ch. 3–4), or becoming a ruler's sworn man (*handgenginn*, *hirðmaðr*). Favour without one is common: Auðunn leaves King Sveinn with gifts without entering his service (*Auðunar þáttr vestfirzka*); Odin gives gifts to Starkaðr (*Gautreks saga* ch. 7). So recognition at resolution [5.2] is an ordinary **event reward**; where a bond exists, the same deed can also count as a **bond achievement** (`24_BONDS_AND_DEVOTION_WIP.md` §4). Unless a saga says otherwise for a particular power.

**Setback opening another direction [5.3]** — oppositions can be lasting enmity, rivalry among the gods, or gods taking sides over one person; **the event decides** which applies (source table: `23_DIVINITIES_WIP.md` §4). Examples:
- **God to god** — Víga-Glúmr offends Freyr, who turns against him (Þorkell's ox-sacrifice to Freyr, *Víga-Glúms saga* ch. 9; Glúmr's dream of the angry Freyr, ch. 26), while Glúmr's line and gifts tie him to Odin.
- **God to mythic enemy** — the Eddas pair each god with a fated opponent (Odin–Fenrir, Thor–the Serpent, Freyr–Surtr, Týr–Garmr, Heimdallr–Loki; *Völuspá* 53–56, *Gylfaginning* ch. 51).
- **Away from the gods** — Hrafnkell Freysgoði, his temple burned and his horse killed, judges it folly to trust in gods and rises again by his own strength (*Hrafnkels saga* ch. 7).

---

## 7. Triggers

**LOCKED 2026-11-19:** **Events are sorted by how they are triggered**, because each event can have several outcomes. Events are in general free and independent; their **triggers are not** — each trigger belongs to a system. One file per trigger, in `events/`. Inside each event, conditions shape how it plays (§2).

**LOCKED 2026-11-20 — the web builds as you play:**
- **Triggers are tags.** An event set off by several triggers carries several tags — no pointers, no copies.
- **An event knows nothing about other events.** It reads the state of party and world through its conditions and changes that state through its outcomes (§8). An event whose conditions now hold becomes possible; no link between events is written.
- **Files are for writing, not for play.** An event is written in the file of its first trigger tag; in play, events are found by their tags.

- **Trigger vs. condition:** a trigger brings the event about; a condition shapes how it plays for this party. The same information can do both — an earned name can trigger a response [2.3] and be a condition (§5).
- **Saga events are mainly inspiration.** A saga situation is a starting point, not a closed box; what one event leaves behind can make another possible (Consequence).

| Trigger | What moves | File |
|---|---|---|
| Place | The party goes somewhere | `events/01_PLACE_TRIGGER_WIP.md` |
| Time | Something alters with time | `events/02_TIME_TRIGGER_WIP.md` |
| Powers | A faction or divinity acts on its own clock | `events/03_POWERS_TRIGGER_WIP.md` |
| People | A companion's past wakes | `events/04_PEOPLE_TRIGGER_WIP.md` |
| Consequence | An earlier outcome comes back | `events/05_CONSEQUENCE_TRIGGER_WIP.md` |
| Bond / Oath | An obligation calls the party in | `events/06_BOND_AND_OATH_TRIGGER_WIP.md` |
| Name / Fame | Repute arrives before the party | `events/07_NAME_AND_FAME_TRIGGER_WIP.md` |
| Wyrd | Wyrd-Pressure stirs the world | `events/08_WYRD_TRIGGER_WIP.md` |
| Tactical Map | An event hex is triggered during a mission | `events/09_TACTICAL_MAP_TRIGGER_WIP.md` |
| Sought Out | Others come to the party for what they see in it [3.2] | `events/10_SOUGHT_OUT_TRIGGER_WIP.md` |

---

## 8. Outcomes

**LOCKED 2026-11-20:** **Events are the backbone of the campaign.** Outcomes return to the same systems triggers come from: system → trigger → event → outcome → system. Every outcome can also become a condition or trigger for later events (§1.1, [2.3], [5.3]) — a property of all outcomes, not a separate kind. One piece of information may land in several registers at once (a wound: Scars, Party Resources via compensation, Worldly via a name — `11_injury_and_scars.md` §1.2). The event decides which apply.

| Register | Covers | Owner | Trigger it returns to |
|---|---|---|---|
| **Worldly** | *Orðstírr* — Renown, Saga-Renown, earned names (§6) | `06` Ch.12; `01_INTERNAL_ARCHITECTURE_WIP.md`; `01c` §6 | Name / Fame |
| **Stories told** | Praise-verse that carries fame onward (*erfidrápa*) — no canon home yet | `20_CAMPAIGN_CORE_WIP.md` §5 | Name / Fame |
| **Divine** | Favour and rewards with or without a bond (§6); divine opposition drawn by the outcome | `23_DIVINITIES_WIP.md` §4 | Powers |
| **Divinity movement** | The divinity itself changes, or appears to — a different aspect, a misunderstanding, a changed relation | `23_DIVINITIES_WIP.md` §1 | Powers |
| **Faction movement** | A faction's orientation, resources, relations, or position shift | `22_FACTIONS_WIP.md` §1 | Powers |
| **Companion changes** | Past awakened, hidden character revealed, alignment moved, loyalty strengthened or fractured | `21_COMPANIONS_WIP.md` §2 | People |
| **Recruitment & departure** | A person joins, is accepted, refuses, departs, betrays, or dies | `21_COMPANIONS_WIP.md` §2; `26_CAMPAIGN_ECONOMY_WIP.md` §3.2 (acceptance) | People |
| **Bonds** | Card granted, deepened, weakened, or destroyed; thresholds crossed; ignition grants or deepens a card | `24_BONDS_AND_DEVOTION_WIP.md` §4, §4.2, §6; `01c` §2 | Bond / Oath |
| **Oaths & Wyrd-thread** | Oath sworn, kept, broken, severed; Troth-Gravity; the Traveling Rot; Wyrd-Scars (the spiritual scar) | `96_OATHS_WIP.md` §3–7 | Bond / Oath, Wyrd |
| **Feud** | Feud opened, escalated, or settled; Blood-Tether | `20b` §7.6; `96_OATHS_WIP.md` §8 | Bond / Oath, Consequence |
| **Scars** | Physical scars and lasting injury (the body) | `11_injury_and_scars.md` §1 | Tactical Map, Consequence |
| **Party resources** | Money (incl. compensation, wages, ransom), Food, Tolerance, Party morale; the company's growing soul | `26_CAMPAIGN_ECONOMY_WIP.md` §3–4; `20_CAMPAIGN_CORE_WIP.md` §5 | — (all) |
| **Material** | Things gained or lost: weapons, horses, ships, relics, land, refuge, captives, salvage | `20b` §7.6; `20_CAMPAIGN_CORE_WIP.md` §5 | Tactical Map, Place |
| **Map seeds** | Reality-layer hex changes and Wyrd-layer seeds | `06_adventure_and_prep.md` Ch.15 | Place, Tactical Map |
| **Knowledge & rumour** | What the party learns, or only partly grasps — something concrete to investigate. Works as conditions: what the party knows opens or shapes later events (LOCKED 2026-11-20) | This file, §2; `20_CAMPAIGN_CORE_WIP.md` §5; [1.3] | Place, Wyrd |
| **Time spent** | The event uses up time and opportunity | `20_CAMPAIGN_CORE_WIP.md` §6; [4.3] | Time |
| **Progression** | *Reynsla* (experience) toward *þroski* (level-up) — itself a reflection event; familiarity through use: every skill check in an event or mission adds skill XP (`03_skill_system.md` Ch.3) | `01c` §4; `03_skill_system.md` Ch.3; `20_CAMPAIGN_CORE_WIP.md` §6 | Consequence (Level event) |
| **Legacy** | What persists into later playthroughs | `25_LEGACY_WIP.md`; `20_CAMPAIGN_CORE_WIP.md` §7 | — (trans-saga) |

The *reynsla* threshold is OPEN (`01c` §4); in-play time is OPEN (`90_TODO_development_tracking.md` §7); Stories told has no mechanism yet (`90_TODO_development_tracking.md` §8).

---

## 9. Event Flow

**LOCKED 2026-11-20:**

- **Length varies.** An event can be short — "attacked by bandits" — and go straight to the pre-battle phase (`06_adventure_and_prep.md` Ch.12; `00A_DESIGN_ATOMS.md` Part II §5.3).
- **Transparency.** Most "extra" content — what a party's qualities open in an event (§2) — also explains the trigger or condition that opened it. Transparency explains *what opened* the content, not *what it means* or where it leads (`20_CAMPAIGN_CORE_WIP.md` §8, Guardrail 11; `00A_DESIGN_ATOMS.md` Part II §3, Pillar of Mystery). The explanation is narrative, as the sagas give it — "because he was Freyr's friend" (*Hrafnkels saga* ch. 2) — and is separate from the numeric disclosure toggle (`00E_CORE_VISION_AND_PILLARS_WIP.md` §3).
- **Rewards and summary** are given in Resolution (§10, step 5).

---

## 10. Event Format

**LOCKED 2026-11-20:** Every event is **self-explanatory**: everything happens and is explained inside it. Two limits: it explains *what opened* an option, not *what it means* (§9); and its effects name existing rules ("devotion with Freyr") without restating them (`00A_DESIGN_ATOMS.md` Part II §1, DRY).

**Tags on top** — Trigger(s) (§7) · Length (§9) · Situation · Time window, if any ([4.3]).

| Step | Holds | From |
|---|---|---|
| **1. Opening** | The introduction, plus the conditional information this party gets — each piece with what opened it | [1.1], [1.3], §9 |
| **2. Paths of action** | What is visible and available to this party; restrictions close paths here | §2, §4 |
| **3. Choices** | Each path leads in the end to its own choices; goals change as the party commits | §3 |
| **4. Mission or peace** | A choice leads to a mission on the tactical map (through pre-battle, `06_adventure_and_prep.md` Ch.12) — a battle, sneaking past guards, or another objective — or to a more peaceful outcome; a short event can reach this step at once | §9; `20_CAMPAIGN_CORE_WIP.md` §2b |
| **5. Resolution** | Rewards gained and explained, daring recognised, and a summary of the aftermath and consequences, including skill progress (`03_skill_system.md` Ch.3). After a mission with a battle, the post-battle resolution feeds in here (`11_injury_and_scars.md` §1) | §5, §6, §8 |

Conditions are not a step of their own: they shape what the Opening reveals and which paths the party sees. **How much of the consequences the summary shows depends on the party** — e.g., a foresighted member (*forspár*, `01c_CHARACTER_BUILD_PIPELINE_WIP.md` §6) or Wyrd-legibility (`01_INTERNAL_ARCHITECTURE_WIP.md`).

---
*Status: Event structure and format locked; concrete events grow in `events/`. Open items owned elsewhere are listed in `90_TODO_development_tracking.md` §7–8. Last Updated: 2026-11-20.*
