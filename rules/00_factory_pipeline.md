# The Saga Factory: Rule Generation Pipeline

> **WHEN TO READ:** This document defines the engine by which the Agent and User collaborate to generate rulebook content. It is the tactical doctrine for preventing AI regression, rule-bloat, and hallucinated mechanics.

## 1. What This Is

The Saga Factory is a deterministic pipeline that turns raw User design decisions ("sparks", equations, historical precedents) into finalized, rule-bound markdown documents. 

The primary optimization target of this pipeline is **minutes of human review per accepted rule chapter**. The goal is to push the variance out of the review phase. The Agent should not be "inventing" the core mechanics during the writing phase; it should be *synthesizing* previously locked atomic truths.

## 2. Pipeline Layers

The documentation engine follows a strict four-stage process:

### Layer A — Data Producers (The Evidence Atoms)
Before a rule is written into the main rulebook, it must exist as a proven "Atom" of design logic. These are the immutable constraints set by the User.
*   **User Sparks:** The thematic vision (e.g., "The Wyrd is an intrusive force, not a mana pool").
*   **Math Constraints:** Adherence to the 1-20 Ladder / 3d6 curve.
*   **Physical Realisms:** Situational modifiers that obey real-world physics (e.g., Armor Weight vs. Movement).

*Contract:* The Agent cannot bend, invent, or compromise an Atom without explicit User approval. If a rule relies on a new modifier or numeric system not already documented as an Atom, it fails.

### Layer B — Composition (The Lenses)
We do not write the entire rulebook blindly. We compose specific atoms into focused "Lenses".
*   **The Main Rulebook Manifest (`MANIFEST.md`)** and specific chapter headers act as our lenses. 
*   When synthesizing a specific chapter (e.g., `05_battle_core`), the Agent filters and collects *only* the Layer A Atoms relevant to tactical combat resolution and collision.

### Layer C — Synthesis (The LLM Execution)
This is where the Agent writes the markdown. The Agent weaves the filtered Atoms (Layer B) together to form a cohesive, "Saga-voiced" manual.
*   **Input:** The Lens (Target Chapter) + Filtered Atoms + Audience Constraints.
*   **Output:** The drafted Markdown Rulebook module.
*   **Constraint:** The Agent uses the exact terminology provided in the Atoms (e.g., "Balance Points", "Severity Impact"). No substitution with generic RPG terms (e.g., "stamina", "hit points") is allowed unless defined in Layer A.

### Layer D — Audience Hygiene (The Eval Rubric)
Before presenting a final draft to the User, the Agent MUST run an internal evaluation check against the `00_ARCHITECTURAL_SOUL.md` and `00_design_doctrine.md`. 
*   **No Placeholders:** Are there empty sections waiting for "future work"?
*   **No Pruning:** Did this draft accidentally delete historical rationale or detailed subsystem math (e.g., Muscle Memory equations)? 
*   **No Rule-Bloat:** Did the draft add mathematical steps (e.g., +1 positional mod) that violate the 3-stage Action Pipeline?

## 3. The Caching Discipline

To avoid destroying old, hard-won rulings:
*   **When an Atom changes:** The Agent updates only the specific rulebook chapters (Lenses) that rely on that Atom.
*   **When a Chapter is rewritten:** The Agent *must* reference the stored Atoms. The Agent may not "summarize" a chapter down to a bullet list if it strips out the foundational Math Atoms that originally built it. 

## 4. Execution Workflow

1.  **User defines the Atoms:** "Here is how Fall Damage works mathematically..."
2.  **Agent confirms the Atoms:** Validates them against the Design Doctrine.
3.  **Agent Synthesizes the Lens:** Drafts the rulebook section using the Atoms.
4.  **Agent performs Eval:** Runs the Layer D checking rubric.
5.  **User Reviews:** The User reads the draft for mechanical accuracy. The variance in reading should only be "did the Agent capture the atom correctly," not "did the Agent invent a new kind of dice roll."
