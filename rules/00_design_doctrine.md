> **WHEN TO READ:** Only for **architectural patterns, 3d6 resolutions, and quota management** questions.

# Design Doctrine: tactical-rpg-boardgamesaga

## 1. Neat & Consistent Architecture
Every rule file is a discrete component. Avoid cross-referencing specific line numbers; reference **Chapter Titles** or **Functional Categories**.

## 2. 3d6 Ladder System (1-20 Scale)
The core resolution engine uses a **3d6 roll** mapped to a **1-20 ladder**. This provides a stable bell curve while maintaining compatibility with high-target thresholds.
- **Modifiers**: Static bonuses derived from Attributes and Skills.
- **The Modifier Barrier**: Without training, high-tier successes (e.g., Perfect Success) are unreachable.

## 3. Quota Effectiveness & Thematic Balance
- **Thematic Integration (No Dry Summaries)**: Do not strip evocative naming or "Saga Aspects" to save token quota. The thematic flavor and the "Saga Voice" are intrinsic to the system's identity. Mechanics and Lore must be presented together.
- **Content Generation:** Delay creation of extensive lists (weapons, monsters, spells) until the battle core is verified, BUT maintain high-quality thematic presentation for the core mechanics we do create.
- **The Toolbox Philosophy:** The core rules are a **toolbox** for implementing historically accurate, real physics, or saga-inspired moments. Avoid "gamey" floating modifiers; favor **Physical Pre-Conditions** and **Material Tags**.
- **The Pillar of Mystery:** Spirit and Fate are not player tools. Wyrd affects all beings. Vision (Wyrd layer) and Perception (Reality layer) are distinct and separate.
- **The Tension of Time:** Contrast the "Short-term Survival" (immediate tactical gain) with "Long-term Saga" (costly persistence with delayed mythic rewards).
- **The Living Record:** Every action leaves a mark. Combat is not a "reset."
    - **Reality Layer:** Physical destruction (e.g., broken bridge) immediately alters the campaign map.
    - **Wyrd Layer:** Mythic deeds are "seeded" and can inspire future saga characters.
- **Faction Breathing:** Factions are living pressures. They operate on an **Active Push** (proactive gain) and **Reactive Pull** (responding to player actions).
- **DRY (Don't Repeat Yourself):** If a rule is defined in `Foundations`, don't re-explain it in `Battle Core`.

## 4. Hardware Assumptions
Rules assume the use of **Interactive Character Sheets** to manage:
- Cumulative Bleeding (HP Drain).
- Shock/Stamina (SP) recovery and thresholds.
- Balance Points (BP) resets.
- **Dynamic Initiative** based on DEX and Armor Weight.

## 5. The Saga Adventure Pillars
These pillars ensure every map and challenge feels alive, creative, and grounded in old-school RPG adventure.

1. **Integrated Interactivity:** Maps are interactive, not as a "third faction," but through triggered events linked to the Campaign Map/Narrative.
2. **The Adventure Book Legacy:** Missions reward diverse skills (History, Engineering, etc.) on the tactical map, creating an "(Anti)Hero Party" feel.
3. **Strategic Pre-Battle Choices:** Story-style decisions (Negotiate, Flee, Sabotage) precede the tactical engagement.
4. **Maneuver-Based Interaction:** Environmental interaction is driven by Skills and Progression Tree abilities (e.g., Push, Pull, Hook).
5. **Mental/Social Utility:** CHA, WIL, and INT are primarily pre-battle and map-layer tools, but can be used as rare, high-impact Major Actions in combat.
6. **Dynamic Terrain States:** Hexes are mutable; fire, water, and destruction permanently alter the tactical landscape.
7. **The Camping Tool (Prep Phase):** Context-specific scouting and preparation provide tangible tactical advantages before the first segment begins.
