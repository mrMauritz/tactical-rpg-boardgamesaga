# Bond & Devotion Progression Trees (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** This file fixes the tree-skeleton structure only — no concrete nodes/perks for any specific Faction, Divinity, or Dedication exist yet. Parallel in purpose to `99_CLASS_TREES_WIP.md`, which holds the Class Tree skeletons the same way.

**Source:** This session's conversation, 2026-11-09 — confirming Devotion Trees (Faction/Divinity/Dedication) as structurally separate from Class Trees, each following the "skeleton defines the tree-shape, nodes emerge organically" pattern already used elsewhere in this project.

---

## 1. Relationship to `24_BONDS_AND_DEVOTION_WIP.md` and `99_CLASS_TREES_WIP.md`

- **`24`** defines the devotion **economy** — Available/Total Devotion, the `BenefitActive ⟺ TotalDevotion ≥ Threshold` and `BenefitStrength = f(TotalDevotion)` formulas (§4–4.1). This is the shared math underlying every tree in this file.
- **`99`** defines the **Class Trees** — an achievement-point economy expressing the character's own direction, entirely separate from Devotion.
- **This file (`24b`)** defines the **tree skeletons** for the three Bond families below — fed by Devotion points, not achievement points, and aimed at what the bonded power cares about, not the character's own direction.

## 2. The Three Bond-Family Tree Types

| Tree Type | Instanced Per | Rewards Manifest As | Roster Source |
| :--- | :--- | :--- | :--- |
| **Faction Devotion Tree** | Each faction | That faction's real presence — people, offices, privileges, resources (`24` §2.1, §7) | `22_FACTIONS_WIP.md` |
| **Divinity Devotion Tree** | Each divinity | That god's specific domain — favour, magic, protection (`24` §2.2) | `23_DIVINITIES_WIP.md` |
| **Dedication Progression Tree** | Each dedication | Character unlocks via study/discipline, not allegiance (`24` §2.3) | `24` §2.3 (at least one per attribute, per its own note) |

Each bond is a **separate instance** of its type — a Thor-devotion tree and a Freyja-devotion tree are both Divinity Devotion Trees, but distinct trees with their own nodes once designed.

## 3. Cross-Link to Class Trees (Read-Only Dependency)

Faction/Divinity/Dedication standing can gate or scale Class Tree perks — the existing [Social]/[Alignment] perk-restriction categories in `99_CLASS_TREES_WIP.md` — by reading the same `BenefitStrength = f(TotalDevotion)` formula from `24` §4.1. This is a one-directional read: Class Trees may consume Devotion standing as an input, but the two point economies (achievement points vs. Devotion points) never merge.

## 4. Status

No concrete nodes/perks exist for any specific Faction, Divinity, or Dedication yet. This file fixes the distinction between the three tree types, and between all three and Class Trees — concrete content should emerge once specific bonds are fleshed out (see `90_TODO_development_tracking.md` §5's roster items: Norse divinities + worked Bond Card, faction roster beyond Trade/Nobility/Religion, attribute-to-dedication mapping).

---
*Status: Foundational spark — skeleton only. Last Updated: 2026-11-09.*
