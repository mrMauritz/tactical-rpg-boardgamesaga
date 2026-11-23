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
| Loss of heart | Party morale | Sets the level each member's Warlust builds toward (§3.3) |

**Cohesion is not a resource but an indicator** (§3.2): it shows how well the party fits together.

**Distinction:** Tolerance asks *can these people remain together despite their differences?* Cohesion shows *how well they fit together.* Party morale asks *do they still have the heart to go on?*

> **Push forces movement. Pull gives movement direction. Morale keeps the party going. Cohesion shows how well it fits together. Tolerance allows unlike members to remain within it.**

### 3.1 Tolerance & Fondness (Mechanism)

**ESTABLISHED:** Tolerance is a plain numeric buffer — visible, no hidden value, no chance roll. Taking an action that favors one companion at another's expense raises tension; whether to do so is a **conscious leader choice** against the visible buffer, not RNG. If tension exceeds Tolerance, one or more party members leave. Tolerance's capacity is raised by leader attribute/abilities.

**Fondness** is the opposite pole and a distinct mechanic, not Tolerance's inverse: specific companion pairs can hold a non-romantic affinity for each other, independent of the leader-driven Tolerance buffer.

### 3.2 Cohesion (Indicator) — LOCKED 2026-11-23

- **Derived from composition:** Cohesion is a number derived directly from the party's composition. It tells how much party tension there is from inviting members who do or do not fit together. It is visible, with no hidden value and no chance factor.
- **Not a resource:** nothing earns or spends it. Victories and similar events affect party morale (§3.3), not Cohesion.
- **Effects:** it affects party morale (§3.3). In the Rout Check it gives a buffer and a lifeline — the option *I must stay with my friends* (`05_battle_core.md` Ch.8 §2).
- **Freedom of roster:** the player keeps full freedom to change members; the composition they choose sets Cohesion.
- **Superseded (2026-11-23):** Individual Cohesion, Acceptance, and Cohesion growth from tenure, shared victories, Party Bond rewards, and special events.

**ESTABLISHED relationship:** Bonds usually create drive/pull. Party bonds relate to Cohesion because they can provide a shared object of commitment; character bonds can create individual direction and friction, while party bonds can make direction common (`24_BONDS_AND_DEVOTION_WIP.md` §3).

### 3.3 Party Morale — LOCKED 2026-11-23

- **A party resource:** the level each member's Warlust builds toward (`01_system_foundations.md` Ch.3). Warlust above it is *megin*.
- **Affected by Cohesion** (§3.2).
- **Raised by** victories, finding treasure, and the like.
- **Lowered by** a failed mission, losing a member, party-unfriendly choices in events, and the like.
- Events change it through their outcomes (`27_EVENTS.md` §8, Party resources).

## 4. Conditional Resource Possibilities — Not Universal Meters

Historical reflection raised possible party-specific demands — the list lives in `catalogues/06_SUPPLIES_WIP.md`.

**Do not add these automatically** — existing systems may already cover them: fatigue/rest connects to SP recovery (`01_system_foundations.md` Ch.3); health is represented through wounds, poison, physicians, and healing (`11_injury_and_scars.md`); equipment exists as concrete objects (`07_weapon_and_armor_properties.md`); devotion is progression/power, not ordinary subsistence (`24_BONDS_AND_DEVOTION_WIP.md` §4); reputation/legitimacy primarily open or close possibilities rather than being consumed.

The universal hard-resource kernel currently remains closest to **money, food, tolerance, and party morale** — composition-specific parties may generate additional demands beyond that kernel.

---
*Status: Foundational spark. Core four-resource kernel, Tolerance/Fondness, Cohesion (indicator) and Party Morale ESTABLISHED (§3.1–3.3); exact growth/tension numbers and conditional-resource tracking OPEN — see `90_TODO_development_tracking.md` §5. Last Updated: 2026-09-15.*
