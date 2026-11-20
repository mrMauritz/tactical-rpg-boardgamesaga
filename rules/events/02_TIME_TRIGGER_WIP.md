# Event Trigger: Time (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** Trigger defined; first event written (test event, accepted 2026-11-20).

> **WHEN TO READ:** Before writing an event set off by this trigger. The event as a unit, its conditions, and the trigger/condition distinction are owned by `../27_EVENTS.md` (§2, §7). Write each event in the format of `27` §10, tagged with every trigger that can set it off.

---

## 1. What Moves

The world moves: something alters with time — season, deadline, a window that closes.

## 2. Owning System

Time-sensitive events (`27_EVENTS.md` [4.3]). This file points to that system — it does not restate its rules.

## 3. Saga Inspiration

The sacrificial feasts at the start of winter, at midwinter, and at summer (*Ynglinga saga* ch. 8); the Alþing at midsummer (*Grágás*, Þingskapaþáttr). Saga events are inspiration, not templates (`../27_EVENTS.md` §7).

## 4. Dependencies

In-play time resolution is OPEN (`90_TODO_development_tracking.md` §7).

## 5. Events

### Winter Nights at the Hall

**Tags:** `Time` · `Place` · `Long` · Feast · Winter Nights

*Inspiration: the sacrifice at the start of winter (Ynglinga saga ch. 8); Bergþóra and Hallgerðr's seating quarrel (Njáls saga ch. 35).*

**1. Opening** — The seating has been arranged with care, and one guest watches the party too closely.
- *Outlawed:* "No man here may shelter you." The event ends at the door (`27_EVENTS.md` §4, play style).
- *Bonded to the host's rival:* "Your patron will hear that you ate at this man's table."
- *An earned name:* "You are shown to the bench nearest the high seat" — or below a rival.

**2. Paths of action** — Seek alliance with the host · Trade · Take part in the sacrifice (if bonded to Freyr: "Because she is Freyr's friend") · Recite before the hall (if a skáld).

**3. Choices** — Each path ends in its own choice: accept the host's terms or not, a marriage offer, a price. If the seating insults the party: answer it (daring) · let it pass · leave.

**4. Mission or peace** — Answering the insult can turn into a hall fight through pre-battle (`06_adventure_and_prep.md` Ch.12). Every other path ends in peace.

**5. Resolution** — Parting gifts (gift); favour at the sacrifice, with or without a bond (Divine). Answering a stronger man before the hall is recognised as daring. Consequences: Worldly, Divine, Faction movement, and possibly Feud opened. No later event is named — a feud event elsewhere becomes possible because "feud opened" is now true.

---
*Status: Foundational spark. Last Updated: 2026-11-20.*
