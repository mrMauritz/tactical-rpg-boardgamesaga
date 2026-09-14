# Bonds & Devotion (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** The structure below is ESTABLISHED as intent; concrete bond trees, achievements, Traits, and scaling math are OPEN. See `20_CAMPAIGN_CORE_WIP.md` and `90_TODO_development_tracking.md` §5. Requirement/Taboo resolution logic is promoted to `00A_DESIGN_ATOMS_doctrine.md` §7 as a reusable Atom — not restated here.

**Source:** `BG Saga — Bonds, Power, Freedom, Destiny and Legacy` handoff, §IV–VIII.

---

## 1. Definition

**ESTABLISHED:** A bond is represented as a **card** in both the board-game and digital versions. A bond is a persistent concrete relationship or dedication that opens a particular power path and binds part of the bearer's future.

> **The company binds part of its future to a greater power.**

Bonds are a major source of drive/pull (`26_CAMPAIGN_ECONOMY_WIP.md`), progression, character/party differentiation, balance, and destiny.

## 2. Bond Families

### 2.1 Faction Bonds
A concrete relationship with an actual worldly faction (`22_FACTIONS_WIP.md`) — rewards, tree, and consequences manifest through that faction's real presence, not an abstract category. **PROVISIONAL** (not locked as final content): a faction reward tree may grant people, equipment, training, offices, privileges, services, locations, or direct intervention.

### 2.2 Divinity Bonds
A concrete relation to a particular entity, place, or force in the divine/spiritual world (`23_DIVINITIES_WIP.md`). Magic, healing, protection, and other supernatural capability arise from that specific relationship, not one universal pool.

### 2.3 Dedication Bonds
Function like study, science, discipline, or sustained practice rather than allegiance (Wild Magic given as an example). At least one dedication should connect to each attribute; dedications unlock in special ways; final count may exceed five (depends on the attribute list). Expands "bond" beyond relationships with conscious beings while retaining commitment, progression, cost, and path-shaping. Dedication is not necessarily worship — it may be disciplined practice.

### 2.4 Class Bonds
Only special classes that historically require devotion receive fixed class bonds — ordinary classes do not automatically produce one. Some such classes come with a fixed, specific bond set. (The Blessed Guard, `96_OATHS_WIP.md` §10, is a working example of this family.)

### 2.5 Race Bonds
Only special races with a devotional storyline receive race bonds; some races have fixed or strongly limited bond possibilities. Being treated as a worldly faction (`22_FACTIONS_WIP.md` §2) does not by itself grant a race bond.

## 3. Character and Party Scope

**ESTABLISHED:** Every bond is predefined as either a **Character bond** (attached to one specific character) or a **Party bond** (attached to the main character, affecting the whole party). The main character is the sole bearer of party bonds — this gives party-level relationships continuity when other companions die, leave, or are replaced. One character is not punished for another's actions unless a specific event explicitly hard-codes that consequence.

## 4. Devotion Economy

**ESTABLISHED:** Devotion has two related values:

| Value | Function |
| :--- | :--- |
| **Available devotion** | A point that can be spent/placed within that bond's tree |
| **Total devotion** | Current depth/strength of the bond; controls progression, availability, and sometimes benefit strength |

Devotion is earned through **predefined bond achievements**. Current rule: **one earned devotion point = +1 total devotion + one point available for the bond tree.** Spending/allocating the tree point does not erase the corresponding total devotion — total devotion is the current depth of the relationship, not merely a lifetime sum.

### 4.1 Benefits Dependent on Total Devotion

- **Threshold-dependent:** `BenefitActive ⟺ TotalDevotion ≥ ActivationThreshold` — inactive below threshold.
- **Scaling:** `BenefitStrength = f(TotalDevotion)` — weakens as total devotion falls, but doesn't fully deactivate.

### 4.2 Breaking Oaths and Losing Devotion

**ESTABLISHED:** Breaking an oath can remove total devotion, which can: weaken scaling benefits, deactivate benefits whose threshold now exceeds total devotion, or in severe cases remove the entire bond card (losing the relationship and its power path entirely). This is the mechanical layer under `96_OATHS_WIP.md` §6 "The Sacrifice" — resolving that file's own open question on sacrifice economics. Whether lost devotion can be regained depends on later gameplay and the bond's continued existence.

## 5. Openness, Exclusivity, Depth

**ESTABLISHED:** No general numerical limit on worldly/spiritual bonds — a character or party may hold several. Limitations come from the specific bond and bearer, not universal "bond slots": most bonds are open; some restricted; some totally unique; some divinities are jealous and accept only one divine bond; some factions demand total loyalty and prohibit other faction bonds; some pairs are mutually exclusive; some class/race bonds are fixed. Eligibility and exclusion resolve via the Requirement/Taboo Atom (`00A_DESIGN_ATOMS_doctrine.md` §7).

Natural depth limit (not a hard cap): **you may bind yourself widely, but you cannot go deeply everywhere.** Breadth preserves flexibility; depth grants greater power but commits more time, identity, and future possibility. The specific opportunity cost of a path is defined by its bond card.

## 6. Bond Grants, Cost, and Irreversibility

**ESTABLISHED:**
- Most bond grants are **Traits**, not Quirks (`02_perks_and_traits.md`); most bond trees contain benefits that come with costs. Progression transforms the bearer instead of merely stacking positive bonuses.
- The character/party build is mainly cumulative and irreversible: bonds are gained through picks or gameplay and paths abandoned through gameplay, not free respecification; breaking oaths can remove devotion or the whole card; changing class is very rare and prior class development cannot be undone; acquired Traits can only rarely be removed or transformed; dead/departed companions are replaced through recruitment; party bonds persist with the main character.

## 7. Strategic Approaches Opened by Bonds

**Core principle:** bonds should not simply supply bonuses — they open access to resources, relationships, capabilities, and paths from which distinct strategic parties emerge.

> **Bond → access → resources/capabilities → viable strategic approach → different possible destiny**

| Bond | Concrete opening | Strategic possibility |
| :--- | :--- | :--- |
| Faction bond: enhanced wealth | Supports high wages/major costs | Costly/elite party |
| Faction bond: unique materials | Enables unique equipment | Equipment-focused party |
| Faction bond: underworld access | Enables black markets | Illicit/covert/outlaw party |
| Racial bond: influence within a race | Enables unique monsters/characters | Race-centred party |
| Divine bond: influence with a divinity | Party bonuses and protection | Divinely supported party |
| Dedication bond: unique path | Character unlocks | Specialist/transformative development |

**PROVISIONAL extension categories** (blueprints, not locked content): factional military/political/knowledge/logistics access; divine channeling and revelation; racial heritage Traits; attribute dedication paths; forbidden-knowledge dedication; devotion-defined class bonds. When implemented, factional effects must come from the actual faction and divine effects from the actual spiritual bond — never generic.

## 8. Standard Bond-Card Data Blueprint

Useful common structure (exact presentation OPEN): name/identity of bonded power or dedication; bond family (§2); character or party scope (§3); access/unlock conditions; compatibility and exclusions; requirements; taboos; predefined bond achievements; total devotion; allocatable/spendable tree points; power-path thresholds; scaling rules; granted Traits/abilities; benefits and attached costs; concrete opportunities/resources opened; obligations and prohibited actions; consequences of violation or abandonment; conditions for devotion loss or card destruction.

---
*Status: Foundational spark. Family structure, devotion economy, and strategic-blueprint pattern ESTABLISHED; concrete trees/achievements/numbers OPEN — see `90_TODO_development_tracking.md` §5. Last Updated: 2026-09-14.*
