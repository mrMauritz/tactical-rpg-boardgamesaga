# Session Journal: 2026-05-02

## Accomplishments
- **Finalized Attribute Progression Architecture**: Established a standardized 15-level ladder for all 6 core attributes (STR, DEX, END, WIL, INT, CHA) with no "dead levels."
- **Dual-Matrix Mastery (Lá & Óðr)**: Defined rule-breaking mechanics for both the Physical (Vessel) and Mystic (Metamagic) realms across all 5 Pillar tiers.
- **The Rule of Raw Values (1:1 Identity)**: Mapped every attribute to a fundamental tactical hardware pool (Carry, Initiative, SP Max/Recovery, Stability Threshold, Reaction Window, Presence DC).
- **Linear Specialization Scaling**: Integrated a +1 per even level specialization bonus (Heavy, Light, Galdr, Seer, Shaman) that peaks at +7 at the Mastery level.
- **System Terminology Alignment**: Standardized "Pressure" as a WIL (Bellows) internal mechanic and "Presence" as a CHA (Gaze) external mechanic.

## Handoff State
- All core attribute impact rules are committed to `rules/97_ATTRIBUTE_IMPACT_WIP.md`.
- **Next immediate task**: Review the *Alignment Filter* (Champion/Godless/Beast-Marked) to ensure consistency with the new 5-Pillar system and integrate these masteries with the Weapon/Magic resolution pipelines.
- **TODO Roadmap**: Hybrid Masteries and Environmental Interactions are queued for the next development phase.

## Lessons Learned & Patterns
- **Negation > Addition**: Reinforcing the "Saga Pattern"—negating a fundamental rule (e.g., Negate Displacement) feels more "Legendary" than simply adding numerical bonuses.
- **Hardware/Software Split**: 1:1 raw values provide the "Biological Reality" (Hardware) while the Ladder provides the "Technique/Mastery" (Software).
- **Terminology Precision**: Distinguishing between internal metabolic pressure (WIL) and external moral presence (CHA) is critical for mechanical clarity in high-stakes resolution.

---

# Session Journal: 2026-04-16

## Accomplishments
- **"Heartbeat" Progression Pattern**: Implemented a rhythmic attribute model where Odd values increase the **Bonus** (Efficiency) and Even values (starting at level 4) unlock **Pillar Slots** (Architecture).
- **Attribute Rebalancing**: Reconciled the 3d6 Resolution Ladder by using **Attribute Bonuses** for rolls while retaining **Raw Values** for vitality pools (SP/HP/BP) and kinetic thresholds (Force/Initiative).
- **The Dual-Layer Architecture**: Expanded the 6 Pillars to include a **Mystic Layer (The Wyrd)**. Defined physical physiology (Fascia/Marrow) alongside its mythic manifestation (The Loom/The Well).
- **The Spirit Layer (WIP)**: Defined **MG (Megin)** as the spiritual vessel and **ÓÐ (Óðr)** as the alignment/doorway to the spiritual realm.
- **The Hallowing**: Codified a spiritual progression philosophy where magic capacity grows through a cycle of breakdown and recovery (survival of the **Hollowed** state).

## Handoff State
- Core attribute and pillar slot logic is committed to `rules/01_system_foundations.md`.
- Advanced Magic/Wyrd logic (conduits, bout mechanics, and Óðr alignment) is stored in the WIP section of `rules/01_INTERNAL_ARCHITECTURE_WIP.md`.
- **Next immediate task**: Develop the **Wyrd-Bout** resolution tables and define the **Óðr Archetypes/Tiers**.

## Lessons Learned & Patterns
- **The Value vs. Bonus Split**: Essential for maintaining 3d6 ladder accuracy as characters scale. Raw values provide physical granularity; bonuses provide mathematical stability.
- **Progressive Destruction (Anti-Pattern)**: Discovered that consolidating descriptive lists into tables can cause a "sneak deletion" of lore and philosophy. New mantra: **Magic and Lore integration must be strictly additive.**
- **The Heartbeat Mechanic**: Creating a predictable "Odd/Even" reward cycle makes every attribute point valuable and removes the feel of "dead levels."

---

# Session Journal: 2026-04-15

## Accomplishments
- **Pillar Evolution (Potential vs. Realization):** Codified the philosophy that Attributes are the "Hardware/Potential" while Pillars are the "Extraordinary/Realization."
- **Ignition Logic:** Defined the "System Circuit" requirement—Pillars must be ignited via both an Attribute Threshold and a Mythic/Wyrd Trigger.
- **Conceptualized the Block System:** Visualized the character sheet as a set of toggles where "Pillar Blocks" glow/activate when conditions are met.
- **Deep-Dive Example:** Established a conceptual map linking the 6 Pillars from physical roots (STR, DEX, etc.) to mythic rule-breakers (Gravity-Lock, Action-Sight, etc.).
- **Development Tracking:** Logged the "Wyrd Layer & Internal Architecture" connection and "Hidden Reward System" into the development roadmap.

## Handoff State
- Current philosophy is consolidated in `rules/01_INTERNAL_ARCHITECTURE_WIP.md`.
- No specific mechanical "numbers" were implemented today, as per user direction to focus on concepts.
- **Next immediate task:** Explore the "Hidden Reward System" and how the Wyrd Layer feeds back into Pillar ignition.

## Lessons Learned & Patterns
- **Rule-Breaking > Number-Scaling:** Designing "Extraordinary Passives" that break fundamental rules (like ignoring flanking or counter-acting initiative) creates a more "Legendary" feel than simply increasing hit chances.
- **Hardware/Software Split:** Treating the body as hardware (Potential) and training/wyrd as software (Realization) simplifies the character progression logic significantly.
- **The Glow State:** A visual "Ignition" indicator on a character sheet is a powerful motivator for player progression.

---

# Session Journal: 2026-04-13

## Accomplishments
- **Static Body Progression**: Formalized the rule that **Physical Scale** (Body, Frame, Size) is status and does not change during progression.
- **Synthesized the 6 Pillars of Internal Architecture**:
    1. **The Center** (Stability / Axis)
    2. **The Web** (Fascia / Tensegrity)
    3. **The Pulse** (Nervous System / Synapse)
    4. **The Marrow** (Adaptation / Hormesis)
    5. **The Breath** (Flow / Metabolic Pressure)
    6. **The Attention** (Master & Emissary / McGilchrist)
- **Documented The Masters' Legacy**: Connected the principles of Miyamoto Musashi and Bruce Lee to the physiological pillars.
- **Reorganized WIP Documentation**: Created a dual-layer system to separate **Philosophy** ([01_INTERNAL_ARCHITECTURE_WIP.md](file:///c:/Workspace/tactical-rpg-boardgamesaga/rules/01_INTERNAL_ARCHITECTURE_WIP.md)) from **Perk Sketches** ([98_SKETCHES_AND_IDEAS_WIP.md](file:///c:/Workspace/tactical-rpg-boardgamesaga/rules/98_SKETCHES_AND_IDEAS_WIP.md)).
- **Reverted Premature Implementations**: Successfully restored Rule Files (02, 10, 90) to ensure final rules only include fully refined content.

## Handoff State
- All foundational philosophy is documented in the `rules/01` (Philosophy) and `rules/98` (Sketches) WIP files.
- **Current roadmap items**:
    - [ ] Rules for Massive Impact (Overrun/Momentum).
    - [ ] Wyrd Layer Integration (Weapon state modifiers).
    - [ ] Development of the Disabling Arts (Saga/UFC) based on the current sketches.

## Lessons Learned & Patterns
- **Architecture vs. Scale**: High-impact distinction. The "Container" (Body) is fixed; the "Engine" (Architecture) is what scales.
- **Pillar of Attention**: McGilchrist’s Master/Emissary model provides a superior way to handle combat awareness over generic "Perception" stats.
- **Systemic Shock**: Bruce Lee's "striking through" philosophy is the literal heart of the **SP / Glance Rule** logic.
- **WIP Separation**: Always separate deep foundational guides from experimental perk sketches to avoid rule-bloat and context pollution.

---
*End of Session*

# Session Journal: 2026-04-19

## Accomplishments
- **The Inversion System**: Designed the 12 "Rule of Wild" mutations following the Law of Inversion (+X to Physical Evolution means -X to Mystic Trade-off, and vice versa).
- **Mechanical Precision**: Translated atmospheric saga traits into concrete, mathematical modifications (+1d6 to IS, shift Action segments, ±1 Weapon Range, ±1 MG/SP generation).
- **Organized WIP Files**: Extracted the Wild Mutations into their own dedicated document (`01c_RULE_OF_WILD_MUTATIONS_WIP.md`) to prevent central rule bloat.
- **Development Tracking Fix**: Repurposed the main tracking file into `90_TODO_development_tracking.md`.

## Handoff State
- The 12 mutations are codified in `rules/01c_RULE_OF_WILD_MUTATIONS_WIP.md`.
- **Next immediate task**: Revisit the other TODO items connecting the Wyrd Layer to combat, including specific Wild tradeoff effects on Monster design, or resolving how these Wyrd changes integrate with the other Archetypes.

## Lessons Learned & Patterns
- **The Mage Within**: Trade-offs must punish *the caster's physical capabilities* or *the fighter's mystical capabilities* strictly, rather than vaguely punishing the ambient magic.
- **Symmetry via Inversion**: Forcing an absolute inversion for each attribute maintains mathematical purity and thematic contrast, highlighting the core themes of the "Torn" characters.

---
*End of Session*
