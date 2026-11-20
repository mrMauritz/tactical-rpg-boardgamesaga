# Event Trigger: Place (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** Trigger defined; first event written (test event, accepted 2026-11-20).

> **WHEN TO READ:** Before writing an event set off by this trigger. The event as a unit, its conditions, and the trigger/condition distinction are owned by `../27_EVENTS.md` (§2, §7). Write each event in the format of `27` §10, tagged with every trigger that can set it off.

---

## 1. What Moves

The party moves: it goes somewhere — a node on the campaign map.

## 2. Owning System

Campaign Map nodes, weighted beforehand (`20_CAMPAIGN_CORE_WIP.md` §2b); choosing events (`27_EVENTS.md` [4.1]). This file points to that system — it does not restate its rules.

## 3. Saga Inspiration

Arriving as guests at a hall — Bárðr's feast at Atley (*Egils saga* ch. 44). Saga events are inspiration, not templates (`../27_EVENTS.md` §7).

## 4. Dependencies

Campaign Map weighting has no formula yet (`90_TODO_development_tracking.md` §7).

## 5. Events

### Outlaws on the Heath

**Tags:** `Place` · `Short` · Outlaws

*Inspiration: the Hellismenn, outlaws of the cave Surtshellir (Hellismanna saga).*

**1. Opening** — Smoke rises from the lava field where no farm stands.
- *Strong scouting:* "Your scout read the fresh tracks in the moss. They have not seen you yet."
- *An earned name they know:* "A voice calls out from the rocks. They have heard of [the name]."

**2. Paths of action** — Ride on · Parley (if they know the name) · Ambush (if the party saw them first) · Attack.

**3. Choices**
- *Parley* ends in: pay them · take a recruit (if a companion was once outlawed: "He knows her from the winters in the hills") · break off.
- *Ambush / Attack* end in: how to strike.

**4. Mission or peace** — Short event: Ambush and Attack go straight to pre-battle (`06_adventure_and_prep.md` Ch.12). Parley can end in peace.

**5. Resolution** — Salvage and stolen goods (Material); a recruit (Recruitment). A full outlaw has no legal protection, so killing one draws no claim (*Grágás*, Vígslóði). Aftermath: post-battle scars (`11_injury_and_scars.md` §1). Consequences: Renown; the hideout cleared (Map seed).

---
*Status: Foundational spark. Last Updated: 2026-11-20.*
