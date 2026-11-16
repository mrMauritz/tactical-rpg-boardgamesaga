# Core Vision: Pillars, Values, and Presentation (WIP)

> [!IMPORTANT]
> **DEVELOPMENT STATUS: FOUNDATIONAL, THEMATIC.** This file sits alongside `00A_DESIGN_ATOMS.md` — it states what the game fundamentally *is*, more foundational than any single layer (Battle/Campaign/Saga). Authored from this session's conversation, 2026-11-15. The Agent should not bend or invent against this without explicit User approval, same bar as `00A_DESIGN_ATOMS.md`.

---

## 1. The Four Pillars (what the game is built from)

| Pillar | States |
|---|---|
| **1. Twin Layers** | Battle and Campaign are near-independent core systems, each coherent enough to almost stand alone, unified by one shared engine — expressed spatially as two differently-weighted hex maps. |
| **2. Three-Layer Character Roles** | Every character carries a Battle function (combat role), a Campaign function (civilian role), and a Saga function (relational — the "constellation" of companions opens paths in the Wyrd without a dialogue/relationship-management system). |
| **3. World Cosmology** | The Wyrd underlies everything; every thing and creature belongs to it and carries weight in the alignment system. The tree and its branches is the image for directions within the world. "Guardian" is used broadly — merely believing in or heading toward a branch's direction already serves it. Tone anchored between Iceland-800s and the realm of the gods, closer to Yggdrasil than historical Europe. |
| **4. The Interconnected Whole That Reacts** | Every faction, event, and character is part of one system. Player choice changes the conditions events arise from. The same choice can carry different consequences for different parties depending on who's present, what weight they carry, and what bonds already exist. |

A pre-simulated world (position + weight + randomness, run before play to test for balance) is a **technique** in service of Pillar 4 — not a pillar itself.

## 2. The Six Values (what the game must feel like — the test the Pillars are measured against)

1. The Icelandic saga aspect and historical anchor.
2. Physical realism — "feels real," minimal/no generic RPG concepts.
3. Multiple ways to overcome events and challenges — not only battles, though battles remain central.
4. Multiple ways to win a fight, or directions for characters/party members.
5. Roleplaying register — feels like a saga; a merge of a Saga-flavored visual novel and an 80s solo adventure book.
6. Classic tabletop RPG world — hex environments tactically interactive beyond cover/height.

These are not separately engineered — if the Pillars are built right, the Values follow. Physical realism in particular is not a feature to add, it's the lens the Pillars are already built through.

## 3. The Presentation Feature (not a pillar — a display commitment, cross-cutting)

A three-level information-disclosure toggle:
1. **To play** the game — minimal information shown.
2. **To understand** the game — mechanical transparency increases.
3. **To master / min-max** the game — full transparency.

The rules, numbers, and resolution are **identical** at all three levels — only what's displayed changes. The system does not need simplifying to be intuitive; it is already intuitive because it models real, bodily-understood phenomena directly (weight, fatigue, loyalty, fear, distance). This is a UI/display question, not a rules-complexity question — do not design a simplified ruleset for Level 1.

## 4. Pillar Implementation Status

| Pillar | Status |
|---|---|
| 1. Twin Layers | Partial — Battle (`05`) and Campaign (`06`, `20`–`26`) both strong; shared-engine statement (`01_system_foundations.md` Ch.1; `20` §2b) and the two-map distinction (`20` §2b) added 2026-11-15. |
| 2. Three-Layer Roles | Partial — Battle-function covered by the 8 Class Trees (`99`); Campaign-function and the explicit "three roles" statement added 2026-11-15 (`21` §0); Campaign-function tree homes still open (`99` "The Open Question"). |
| 3. World Cosmology | Partial — Wyrd/Oath/Devotion infrastructure strong (`01_INTERNAL_ARCHITECTURE_WIP.md`, `96`, `24`); tree/branches framing (`01_INTERNAL` Axis 2) and the Belief/Direction tier added 2026-11-15. |
| 4. Interconnected Whole | Refined this session — the Troth-Gravity rename, bidirectional legibility, and the four-stage chain (legibility → pressure → Troth-Gravity → Renown/Scar) are written into `01_INTERNAL_ARCHITECTURE_WIP.md` and `96_OATHS_WIP.md`. |

---
*Status: Foundational, thematic — treat with the same weight as `00A_DESIGN_ATOMS.md`. Last Updated: 2026-11-16.*
