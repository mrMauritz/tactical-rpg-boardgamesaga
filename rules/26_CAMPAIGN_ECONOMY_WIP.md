# Campaign Economy: Pull, Push, and Cohesion (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** Tolerance and Cohesion mechanisms are fixed (§3.1–3.2); exact growth/tension numbers are OPEN. See `20_CAMPAIGN_CORE_WIP.md` and `90_TODO_development_tracking.md` §5.

**Source:** `BG Saga — Bonds, Power, Freedom, Destiny and Legacy` handoff, §IX.

---

## 1. Pull Rather Than Constant Survival Pressure

**ESTABLISHED:** Survival is primarily a requirement, not the central motor of the game. Constant pressure produces reactive play and narrows freedom; pull is more interesting because it preserves choice.

| Sequence | Chain |
| :--- | :--- |
| **Push** | threat → necessity → reaction → temporary relief |
| **Pull** | encountered possibility → desire → chosen commitment → acquired power → new possibilities |

Survival pressure still gives the world weight, but the player should not need constant threat to keep moving.

> **Pressure tests freedom. Pull gives freedom direction.**

## 2. Sources of Pull

Companions worth finding/rescuing/recruiting/understanding; new forms of worldly or spiritual power; deeper factional, divine, or dedication bonds (`24_BONDS_AND_DEVOTION_WIP.md`); unknown places, sacred locations, ruins, cities, frontiers; mysteries, rumours, concealed histories; construction and mastery of new party configurations; recognition, honour, infamy, titles, office; belonging to a people, household, faction, tradition, cult, or cause; companion histories, lost kin, old enemies, unresolved oaths; rivals and recurring opponents; exceptional weapons, relics, land, ships, wealth, or refuge; transformation into something not initially imagined; protecting, founding, restoring, conquering, or destroying something lasting; signs of a greater but still unreadable destiny; legacy beyond the current company and playthrough (`25_LEGACY_WIP.md`).

The deepest common form is **promised possibility**: something exists in the world that could change what the company is capable of becoming.

## 3. Four Party Forces/Resources

| Party pressure | Answer/resource | Function |
| :--- | :--- | :--- |
| Wages | Money | Sustains paid service and costly parties |
| Hunger | Food | Sustains bodies and travel |
| Alignment friction | Tolerance | Allows unlike members to remain together |
| Loss of loyalty/common purpose | Cohesion | Holds the company together |

**Distinction:** Tolerance asks *can these people remain together despite their differences?* Cohesion asks *do they still have a reason to remain together?*

> **Push forces movement. Pull gives movement direction. Cohesion keeps the party together. Tolerance allows unlike members to remain within it.**

### 3.1 Tolerance & Fondness (Mechanism)

**ESTABLISHED:** Tolerance is a plain numeric buffer — visible, no hidden value, no chance roll. Taking an action that favors one companion at another's expense raises tension; whether to do so is a **conscious leader choice** against the visible buffer, not RNG. If tension exceeds Tolerance, one or more party members leave. Tolerance's capacity is raised by leader attribute/abilities.

**Fondness** is the opposite pole and a distinct mechanic, not Tolerance's inverse: specific companion pairs can hold a non-romantic affinity for each other, independent of the leader-driven Tolerance buffer.

### 3.2 Cohesion (Mechanism)

**ESTABLISHED:** Cohesion is built bottom-up from the individual companion, not tracked as one abstract party number in isolation:

- **Individual Cohesion** — every companion has their own Cohesion value, same transparent register as Money/Food/Tolerance (no hidden value, no chance factor). It grows from: time-in-party (their own tenure), shared victories, Party Bond rewards (`24_BONDS_AND_DEVOTION_WIP.md` §3–4), and **special events** — personal moments that earn that companion bonus Individual Cohesion beyond the passive sources.
- **Acceptance** — a newly hired member does not count immediately. They must earn the right to be considered part of the party before their Individual Cohesion contributes to anything. *Exact acceptance trigger (time served, a specific event, an Individual Cohesion floor) is OPEN.*
- **Party Cohesion** — the sum of Individual Cohesion across all *Accepted* members. An unaccepted new hire contributes zero to the party total, regardless of how much Individual Cohesion they may already be quietly earning.

**Design principle:** the player retains full freedom to kick and exchange party members for maximum utility — this is never restricted or taboo'd. But keeping a party intact instead of churning it is independently rewarded: stability itself grants Cohesion, and a long-tenured Accepted member's Individual Cohesion outweighs what any fresh hire can offer. The incentive is a soft pull toward continuity, not a hard block on roster optimization.

**ESTABLISHED relationship:** Bonds usually create drive/pull. Party bonds relate to Cohesion because they can provide a shared object of commitment; character bonds can create individual direction and friction, while party bonds can make direction common (`24_BONDS_AND_DEVOTION_WIP.md` §3).

**Battle-layer hook:** High Party Cohesion lowers the effective Moral Pressure DC against a party member's Route Check, auto-negating it entirely at a high enough threshold (`05_battle_core.md` Ch.8 §2) — the campaign layer's first direct tactical-layer effect.

## 4. Conditional Resource Possibilities — Not Universal Meters

Historical reflection raised possible party-specific demands: fodder for horses/pack animals/monsters; medicine/treatment for wounded, sick, or poisoned members; repair materials/services for equipment-intensive parties; reagents/materials for specific casters and rituals; maintenance/supplies for ships or specialized transport.

**Do not add these automatically** — existing systems may already cover them: fatigue/rest connects to SP recovery (`01_system_foundations.md` Ch.3); health is represented through wounds, poison, physicians, and healing (`11_injury_and_scars.md`); equipment exists as concrete objects (`07_weapon_and_armor_properties.md`); devotion is progression/power, not ordinary subsistence (`24_BONDS_AND_DEVOTION_WIP.md` §4); reputation/legitimacy primarily open or close possibilities rather than being consumed.

The universal hard-resource kernel currently remains closest to **money, food, tolerance, and cohesion** — composition-specific parties may generate additional demands beyond that kernel.

---
*Status: Foundational spark. Core four-resource kernel and Tolerance/Fondness/Cohesion mechanisms ESTABLISHED (§3.1–3.2); exact growth/tension numbers and conditional-resource tracking OPEN — see `90_TODO_development_tracking.md` §5. Last Updated: 2026-09-15.*
