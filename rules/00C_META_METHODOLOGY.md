# 00C Meta-Methodology: Findings About the Investigation Process Itself

> **WHEN TO READ:** When diagnosing recurring friction, a new complaint about agent behavior, or auditing the instruction layer (`CLAUDE.md` / memory / this file / `00_FACTORY_ENGINE.md`) against itself.

This file tracks findings about the *process* of investigating and building BG Saga — not the game content itself (see `rules/` generally) and not how to run an investigation (see `00_FACTORY_ENGINE.md` Part II, "The Investigation Method"). It's what the investigation reveals about thought, abstraction, AI collaboration, and method — the third of three levels (Phenomena / Methodology / Meta-methodology).

---

## 2026-07-26

**Instruction-architecture accretes silently.** Independently-built instruction files (CLAUDE.md, memory, Factory Engine) don't self-reconcile — nothing in the tooling detects overlap or contradiction between them automatically.
*How to apply:* periodic cross-audit across all instruction-bearing files, not just when something visibly breaks.

**A complaint may be a known failure wearing new language.** "Garbage via unprompted invention" and "garbage via over-verification" are the same root problem (doing work the user didn't need) approached from opposite directions.
*How to apply:* before treating a new process complaint as a brand-new problem, check whether it's an existing one inverted.

**Audit-visibility effect.** Actively scrutinizing a layer surfaces more issues the longer you look — a rising find-count is evidence of scrutiny, not proof the underlying system is degrading.
*How to apply:* don't read "we keep finding problems" as "things are getting worse" without checking whether looking harder is the actual cause.

**"Lock in" is the connective trigger, not just a go-ahead.** It's the specific point where a phenomenological Reduction becomes a Factory Engine Atom — investigation and production are sequential phases of one pipeline, not competing frameworks.

---

## 2026-07-27

**A named correction is production-mode, not investigation-mode.** "Fix X in file Y" is lock-in-adjacent — the user has already decided the scope. Applying investigation habits to it (exhaustive re-verification, hunting the file for related issues, re-auditing unnamed tables) is the same root failure as unprompted invention — work the user didn't ask for — from the opposite direction: over-verification instead of over-creation.
*How to apply:* on a named correction, execute the minimal diff for exactly what was named, then stop. Don't expand into a consistency sweep of the surrounding file unless the user's phrasing asks for that ("check the whole doc," "audit for consistency") or a lock-in step explicitly requires it.

---

## 2026-11-15

**Process overhead should scale to task type, not apply uniformly.** The 2026-07-27 finding (named correction = production-mode) generalizes into a routing table rather than one isolated case:

| Tier | Example | Factory Engine | Personal preferences (tone/format) |
|---|---|---|---|
| Mechanical op | Rename a file, fix a typo | Skip | Skip — just do it |
| Named correction | "Fix X in file Y" | Skip | Keep — minimal diff, but still report back tight/cited |
| Simple reply | Answering a question, explaining a mechanic | N/A (nothing being produced) | Keep |
| Investigation | Survey, source research, analysis of a design question | Phase 1 only (`00_FACTORY_ENGINE.md` Part II) — no files until "lock in" | Keep |
| Design suggestion | New rule text, a Skeleton Plan | Full pipeline (Atoms → Map → Synthesis → Eval) | Keep |

*(Investigation row added 2026-11-16 when the Factory Engine gained its two-phase Part II.)*
*How to apply:* before reaching for the Factory Engine or investigation-grade rigor, classify the request against this table first. Don't run a mechanical op or a named correction through the full pipeline; don't skip personal-preference formatting on a simple reply just because it isn't "producing content."

**Safety and confirmation behavior is not a tier-scaled preference — it's constant.** Destructive-action checks, the git safety protocol, and confirmation before broad-blast-radius actions apply at every tier in the table above, including "mechanical op." Scaling down investigation rigor and the Factory Engine must never be read as scaling down safety behavior — they are different axes, not the same dial.

---

## 2026-11-16

**Drift from the source compounds into structural conflict.** The character-taxonomy conflicts (36 archetypes, six saga archetypes, Lá/Óðr labeled per attribute and per tree, Frenzy as a "Lá tree") traced back to earlier stages moving away from the sources — largely agents producing content: names, categories, label lists. Each later layer built on the previous agent-made layer, not on the sagas, so the conflicts could not be resolved by reasoning inside the files. Going back to the primary sources (*Völuspá* 18, *Ynglinga saga* 6–7, *Egils saga*, *Njáls saga*, *Hrólfs saga kraka*) resolved in one round what file-internal reasoning could not.
*How to apply:* codified as `00A_DESIGN_ATOMS.md` Law 1 (Source First) and checked by `00D` Block 4 (Source Traceability). In short: sources first, cited by chapter/stanza; agent-made names never extended or cited as evidence (`01c_CHARACTER_BUILD_PIPELINE_WIP.md` §6); keep source, file, and agent-made voices apart.
- The source-anchored core (locked 2026-11-16): `01_INTERNAL_ARCHITECTURE_WIP.md` "The Three Gifts", "The Three Faces of Óðr", Axis 1 whole self; `01c` §6; `99_CLASS_TREES_WIP.md` "Traditions in the Sources". Read these before touching Lá/Óðr, archetypes, or traditions.

---
*Created: 2026-07-26*
