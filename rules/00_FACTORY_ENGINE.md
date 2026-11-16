# The Saga Factory: Engine & Collaboration Protocol

> **WHEN TO READ:** Before major rule-writing work (`CLAUDE.md` Design-Lock Workflow). This document defines who does what, and the deterministic pipeline that governs how all content is produced.

---

## Part I — Role Doctrine (Who Does What)

Base role and no-invention doctrine live in `CLAUDE.md` (Role: Research & Analysis Engine) — not restated here.

### The Creator (User)
Sole Creative Authority. If the User feels a system is being rushed or "half-assed," the Agent MUST stop, discard the fluff, and go deeper into the core logic.

### The Secretary (Agent)
Pipeline-specific duties beyond the base role in `CLAUDE.md`:
- Generating skeleton plans (Implementation Plans) for the User to comment on.
- Updating rulebook chapters once a design decision is locked.
- Maintaining the project structure and updating `00B_RULEBOOK_MAP.md`.
- Does NOT simplify or summarize approved content without an explicit instruction.

---

## Part II — The Collaboration Workflow

1. **User** provides a creative spark or objective.
2. **Agent** generates a **Skeleton Plan** (Implementation Plan) with structure and options, leaving room for User specifics.
3. **User** refines math/mechanics by commenting directly in the plan artifact.
4. **Agent** updates the plan. Execution begins **only once the vision is locked.**
5. **Agent** provides a final Walkthrough and updates all documentation.

---

## Part III — The Rule Generation Pipeline

The Saga Factory is a deterministic pipeline that turns raw User design decisions ("Sparks") into finalized, rule-bound markdown documents.

**Primary optimization target:** Minutes of human review per accepted rule chapter.
The Agent synthesizes previously locked Atoms — it does not invent during the writing phase.

---

### Layer A — Design Atoms (The Evidence)
Before a rule is written, it must exist as a proven "Atom" of design logic set by the User.

- **User Sparks:** The thematic vision (e.g., "The Wyrd is an intrusive force, not a mana pool").
- **Math Constraints:** Adherence to the 1-20 Ladder / 3d6 curve.
- **Physical Realisms:** Situational modifiers that obey real-world physics (e.g., Armor Weight vs. Movement).

**Contract:** The Agent cannot bend, invent, or compromise an Atom without explicit User approval. If a rule relies on a modifier or numeric system not already documented as an Atom, it fails.

*Source file:* `00A_DESIGN_ATOMS.md` (Part I Core Laws · Part II Mechanical Doctrine)

---

### Layer B — The Rulebook Map (The Lens)
We do not write the rulebook blindly. We compose specific Atoms into focused "Lenses."

- The `00B_RULEBOOK_MAP.md` and specific chapter headers act as our lenses.
- When synthesizing a chapter (e.g., `05_battle_core`), the Agent filters and collects *only* the Layer A Atoms relevant to that chapter's domain.

---

### Layer C — Synthesis (The Writing Phase)
This is where the Agent writes the markdown. The Agent weaves filtered Atoms into a cohesive, "Saga-voiced" manual.

- **Input:** The Lens (Target Chapter) + Filtered Atoms + Audience Constraints.
- **Output:** The drafted Markdown Rulebook module.
- **Constraint:** The Agent uses the exact terminology provided in the Atoms (e.g., "Balance Points", "Impact Severity"). No substitution with generic RPG terms (e.g., "stamina", "hit points") unless defined in Layer A.

*Output files:* The numbered rulebook chapters (`01_`, `02_`, `05_` etc.)

---

### Layer D — Eval Rubric (The Quality Gate)
Before presenting any draft to the User, the Agent MUST run the full checklist in `00D_EVAL_RUBRIC_reference.md` (placeholders, pruning, rule-bloat, terminology, source traceability, and more).

*Source file:* `00D_EVAL_RUBRIC_reference.md`

---

## Part IV — Caching & Change Management

To avoid destroying old, hard-won rulings:

- **When an Atom changes:** Update only the specific chapters (Lenses) that rely on that Atom.
- **Core-First Mandate:** No detail or specific rule shall be finalized until the system core is verified as "strong enough" by the User. Details must emerge naturally from the core, not be forced upon it.
- **When a Chapter is rewritten:** Always reference the stored Atoms — no pruning (`00A` Law 10).
- **Quota Efficiency:** tables and bullets over prose; cite file + chapter/section; never repeat a description that lives elsewhere (DRY, `00A` Part II §1); keep files lean (`00B` Quota Note). Never at the cost of Saga Voice (`00A` Law 11).
- **One Working System:** build one working game system; board-game or computer adaptation is a later question (`00A` Law 9).
