# Events: Where the Party Meets the World (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** This file fixes what an event *is* and how it responds to the party. No concrete event roster, event-card format, or objective catalogue exists yet — open items live in `90_TODO_development_tracking.md` §8.

> **WHEN TO READ:** Before writing or resolving any event, mission, or event-driven consequence. The campaign kernel is `20_CAMPAIGN_CORE_WIP.md`; this file owns the event as a unit.

**Source:** User document *BG Saga — Accepted Event and Saga Design Points* (2026-11-17), point numbers kept as `[x.y]`. Point 2.2 was removed by the User and is not carried here.

---

## 1. The Event as a Unit

**LOCKED 2026-11-18:** Events are their own unit. An event is where a particular party meets the world. Its existing touchpoints, not restated here:

| Aspect | Owner |
|---|---|
| Events sit on the campaign map, whose nodes are weighted beforehand | `20_CAMPAIGN_CORE_WIP.md` §2b |
| A battle can be a **mission** arising from an event, with its own objectives | `20_CAMPAIGN_CORE_WIP.md` §2b |
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

**KEPT FOR DEVELOPMENT 2026-11-17 — [3.2] Others seek something from this party:** participants may ask for protection, offer terms, or issue a challenge because of the companions, bonds, or identity they meet. Valuable; implementation needs care (`90_TODO_development_tracking.md` §8).

> *The party's identity shapes both what the player pursues and what others seek from the party.*

---

## 4. Choosing Events Expresses the Party's Direction

**LOCKED 2026-11-17:**

- **[4.1] Choosing** — the campaign lets players choose events, sometimes through difficult decisions. Play style, bonds, and alignment impose **hard** and **soft** restrictions.
- **Hard restrictions** are taboos and unmet requirements (`00A_DESIGN_ATOMS.md` Part II §7; bond exclusivities, `24_BONDS_AND_DEVOTION_WIP.md` §5). They define commitments.
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

**LOCKED 2026-11-18 — one term, per [6.1]:** an **achievement** is an earned deed recorded on the character. A **bond achievement** (`24_BONDS_AND_DEVOTION_WIP.md` §4) is the case where the deed's outcome is devotion in a particular bond — not a second kind of thing.

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
*Status: Foundational spark. Event structure locked; content, carriers, and roster OPEN (`90_TODO_development_tracking.md` §8). Last Updated: 2026-11-18.*
