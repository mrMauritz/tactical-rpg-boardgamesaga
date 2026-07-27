# 00C Meta-Methodology: Findings About the Investigation Process Itself

> **WHEN TO READ:** When diagnosing recurring friction, a new complaint about agent behavior, or auditing the instruction layer (`CLAUDE.md` / memory / this file / `00_FACTORY_ENGINE.md`) against itself.

This file tracks findings about the *process* of investigating and building BG Saga — not the game content itself (see `rules/` generally) and not how to run an investigation (see the `phenomenological-methodology` memory and `00_FACTORY_ENGINE.md`). It's what the investigation reveals about thought, abstraction, AI collaboration, and method — the third of three levels (Phenomena / Methodology / Meta-methodology).

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

**A named correction is production-mode, not investigation-mode.** "Fix X in file Y" / "correct A and B" is a lock-in-adjacent instruction — the scope is already decided by the user. Applying investigation-grade habits (exhaustive re-verification, hunting the whole file for related inconsistencies, re-auditing tables that weren't named) to a production instruction is the same root failure as unprompted invention — doing work the user didn't ask for — just approached from the opposite direction: over-verification instead of over-creation.
*How to apply:* on a named correction, execute the minimal diff for exactly what was named, then stop. Don't expand into a consistency sweep of the surrounding file unless the user's phrasing asks for that ("check the whole doc," "audit for consistency") or a lock-in step explicitly requires it.

---
*Created: 2026-07-26*
