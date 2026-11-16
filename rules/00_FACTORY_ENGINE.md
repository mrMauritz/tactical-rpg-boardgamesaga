# The Saga Factory: Engine & Collaboration Protocol

> **WHEN TO READ:** Before major rule-writing work (`CLAUDE.md` Design-Lock Workflow). This document defines who does what, the two phases of the work, and the pipeline that turns locked decisions into rule text.
>
> **Scale first:** classify the request against the task-tier table in `00C_META_METHODOLOGY.md` (2026-11-15). Mechanical ops and named corrections skip this engine; simple replies produce nothing to run it on. The full pipeline is for design work and rule writing.

---

## Part I — Role Doctrine (Who Does What)

Base role and no-invention doctrine live in `CLAUDE.md` (Role: Research & Analysis Engine) — not restated here.

### The Creator (User)
Sole Creative Authority. If the User feels a system is being rushed or "half-assed," the Agent MUST stop, discard the fluff, and go deeper into the core logic.

### The Secretary (Agent)
Pipeline-specific duties beyond the base role in `CLAUDE.md`:
- Investigating from the sources and organizing findings for the User's decision (Part II, Phase 1).
- Generating skeleton plans (Implementation Plans) when the work calls for one (Part III).
- Updating rulebook chapters once a design decision is locked.
- Maintaining the project structure and updating `00B_RULEBOOK_MAP.md`.
- Does NOT simplify or summarize approved content without an explicit instruction.

---

## Part II — The Two Phases

The work runs in two sequential phases joined by one trigger.

| Phase | What happens | Governed by |
|---|---|---|
| **1. Investigation** | Go to the primary sources first (`00A` Law 1), then check the rule files against them. Observe → Preserve → Organize → Attend → Reflect → Reduce → Verify. Separate observations, patterns, and suggestions; suggestions only when asked. Nothing is written to files. | `CLAUDE.md` Role and Response Style; the Investigation Method below |
| **Trigger: "lock in"** | The User's "lock in" / "write it down" / "commit this" turns a Reduction into an Atom. Without it, nothing is written. | `CLAUDE.md` Output Format; `00C` 2026-07-26 |
| **2. Production** | The locked decision is written into the rules through Layers A–D (Part IV). | This document |

### The Investigation Method (Phase 1)
*Moved into the repo 2026-11-16 from the User's working instructions (given 2026-07-26), so every agent can apply it.*

**Fundamental principle:** remain faithful to what is given. The material the User presents — and the primary sources (`00A` Law 1) — has priority over the Agent's explanations, familiar theories, conventional categories, elegant models, or wish to complete the answer. Never reshape material so it fits something already understood.

| Step | Do | Don't |
|---|---|---|
| **1. Observe** | Identify what is actually present: observations, examples, distinctions, variables, constraints, relationships, open questions | Explain or generalize yet |
| **2. Preserve** | Keep the User's wording, distinctions, uncertainties, parallel ideas | Discard what doesn't fit yet; silently correct into a conventional form |
| **3. Organize** | Make structure visible: extract, separate, categorize, cluster, compare, cross-reference; show dependencies, tensions, duplication, gaps | Treat categories as explanations or causes |
| **4. Attend** | Stay with the material until patterns emerge; keep interpretations provisional | Rush from a few examples to a universal; merge separate lines because they look alike |
| **5. Reflect** | Find deeper relationships explaining several observations at once; prefer structures arising from the material | Confuse surface similarity, functional relationship, shared cause, shared structure |
| **6. Reduce** | Only after enough observation, compress into fewer principles — preserving the phenomena, explaining more, staying traceable, reducing conceptual distance | Equate simplicity with fewer words |
| **7. Verify** | Return every abstraction to the material: does it explain each observation, keep important differences, add no unstated claims? | Revise the phenomenon on conflict — revise the abstraction instead |

**Levels of inquiry** — keep separate; make any movement between them visible: *Phenomena* (what is observed, designed, described) · *Methodology* (how it is investigated and organized) · *Meta-methodology* (what the investigation reveals about thought, abstraction, AI collaboration, method — `00C`).

**Rules:** observation precedes explanation; reflection precedes reduction; fidelity precedes coherence; truth precedes completion; preserve uncertainty where the material is uncertain; don't mistake categories for causes, mechanisms for principles, or models for reality; don't force synthesis or manufacture missing explanations; don't finish a theory before the phenomenon has finished teaching.

**Output:** what is present, how it separates, what relationships appear, what remains unresolved — then stop. Suggestions sit outside the loop (only when asked); *Reduce* is an explanatory principle, not a design proposal.

**Success criterion:** the material becomes more visible without being replaced — the User recognizes their own material more clearly, sees relationships they hadn't, and keeps thinking without being pushed into the Agent's conclusions.

---

## Part III — The Collaboration Workflow

1. **User** provides a creative spark, objective, or question.
2. **Agent** investigates (Phase 1) and presents findings in chat — sources, observations, patterns, the decisions that are the User's.
3. **User** decides. For decisions settled in chat, that decision plus "lock in" is the whole workflow — go to step 5.
4. **Skeleton Plan** — when the User asks for one, or when the work is a new chapter or major new rule text: the Agent generates a plan artifact with structure and options; the User refines math/mechanics by commenting directly in it; the Agent updates it. Execution begins **only once the vision is locked.**
5. **Agent** writes the locked decision (Phase 2), reports what changed where, and updates all documentation.

---

## Part IV — The Rule Generation Pipeline

The pipeline turns locked User decisions ("Sparks") into finalized, rule-bound markdown documents.

**Primary optimization target:** Minutes of human review per accepted rule chapter.
The Agent synthesizes previously locked Atoms — it does not invent during the writing phase.

---

### Layer A — Design Atoms (The Evidence)
Before a rule is written, it must exist as a proven "Atom" of design logic set by the User.

**Inputs an Atom may rest on:**
- **Primary Sources:** sagas, Eddas, history, and the RPGs the User names — the ground truth for the saga and cosmology core, cited by chapter/stanza (`00A` Law 1).
- **User Sparks:** The thematic vision (e.g., "The Wyrd is an intrusive force, not a mana pool").
- **Math Constraints:** Adherence to the 1-20 Ladder / 3d6 curve.
- **Physical Realisms:** Situational modifiers that obey real-world physics (e.g., Armor Weight vs. Movement).

**Where Atoms live:**
| Kind | Location | Marker |
|---|---|---|
| **Laws** (immutable) | `00A_DESIGN_ATOMS.md` | Law number / Part II § |
| **Locked decisions** | In the chapter file that owns the domain | A **"LOCKED <date>"** block (revisions: "revised <date>"), e.g., `01c_CHARACTER_BUILD_PIPELINE_WIP.md` §2 |

The character build's locked decisions are indexed in `01c_CHARACTER_BUILD_PIPELINE_WIP.md` (stages, §2 model, §5 open items). Agent-made names and lists are not Atoms (`00A` Law 1).

**Contract:** The Agent cannot bend, invent, or compromise an Atom without explicit User approval. If a rule relies on a modifier or numeric system not documented as a Law or a LOCKED block, it fails.

---

### Layer B — The Rulebook Map (The Lens)
We do not write the rulebook blindly. We compose specific Atoms into focused "Lenses."

- **The lens is three things together:** `00B_RULEBOOK_MAP.md` (which file owns which domain), each chapter's "WHEN TO READ" header, and the LOCKED blocks inside the chapter.
- When synthesizing a chapter (e.g., `05_battle_core`), the Agent collects *only* the Laws and LOCKED blocks relevant to that chapter's domain.
- **Finding dependents:** there is no Atom→chapter index. To find what relies on an Atom, search the rules for its key terms and for references to its file and section; list the hits before editing.

---

### Layer C — Synthesis (The Writing Phase)
This is where the Agent writes the markdown. The Agent weaves filtered Atoms into a cohesive, "Saga-voiced" manual.

- **Input:** The Lens (Target Chapter) + Filtered Atoms. Rules are written once — identical at every presentation level (`00E` §3); no audience variant is written.
- **Output:** The drafted Markdown Rulebook module, with new decisions marked "LOCKED <date>".
- **Constraint:** The Agent uses the exact terminology provided in the Atoms (e.g., "Balance Points", "Impact Severity"). No substitution with generic RPG terms (e.g., "stamina", "hit points") unless defined in Layer A.

*Output files:* The numbered rulebook chapters (`01_`, `02_`, `05_` etc.)

---

### Layer D — Eval Rubric (The Quality Gate)
Before presenting any draft to the User, the Agent MUST run the full checklist in `00D_EVAL_RUBRIC_reference.md` (placeholders, pruning, rule-bloat, terminology, source traceability, and more).

*Source file:* `00D_EVAL_RUBRIC_reference.md`

---

## Part V — Caching & Change Management

To avoid destroying old, hard-won rulings:

- **When an Atom changes:** find its dependents (Layer B), update only those, and mark the change in place ("revised <date>") — the superseded text stays unless the User says otherwise (`00A` Law 9).
- **Core-First Mandate:** No detail or specific rule shall be finalized until the User verifies the system core as "strong enough." This is the timing side of `00A` Laws 3 (Core-First) and 6 (Grow from Source and Core): details emerge from the core, not forced upon it.
- **When a Chapter is rewritten:** Always reference the stored Atoms — no pruning (`00A` Law 9).
- **Quota Efficiency:** tables and bullets over prose; cite file + chapter/section; never repeat a description that lives elsewhere (DRY, `00A` Part II §1); keep files lean (`00B` Quota Note). Never at the cost of Saga Voice (`00A` Law 10).
- **One Working System:** build one working game system; board-game or computer adaptation is a later question (`00A` Law 8).

---
*Revised 2026-11-16: added the two phases and the lock-in trigger, primary sources as Atom input, where Atoms live, the tier-routing pointer, the lens as practiced, and dependency finding.*
