# Layer D — Eval Rubric (Agent Quality Gate)

> **WHEN TO READ:** The Agent MUST run this checklist internally before presenting **any** rulebook draft to the User. If any item fails, the draft is rejected and corrected before output. This is not optional.

---

## Pre-Output Checklist

Run every item below against the draft. Answer YES or NO. A single NO = reject and fix.

---

### Block 1 — Pipeline Integrity
*Drawn from `00_FACTORY_ENGINE.md` Layer A contract.*

- [ ] **Atom Traceability:** Can every mechanic in this draft be traced to an existing, User-approved Atom in `00A_DESIGN_ATOMS_soul.md` or `00A_DESIGN_ATOMS_doctrine.md`? If a rule relies on a modifier or numeric system not documented as an Atom → **FAIL.**
- [ ] **No Invention:** Did the Agent introduce any new dice type, new modifier, or new resource not defined in Layer A? → **FAIL if yes.**
- [ ] **Terminology Lock:** Does the draft use only approved Saga terminology (e.g., "Balance Points", "Impact Severity", "Wyrd Strain")? No substitution with generic RPG terms (e.g., "stamina", "hit points", "mana") → **FAIL if substituted.**

---

### Block 2 — Structural Integrity
*Drawn from `00A_DESIGN_ATOMS_soul.md` Laws 1–3, 7.*

- [ ] **NEAT & CLEAN:** Does this draft add a new roll or a new modifier? → **FAIL.**
- [ ] **CORE-FIRST:** Is every tactical depth an extension of the 3-Stage Pipeline (`Relative Force → Success Ladder → Result Swap`)? Or does it add a new layer on top? → **FAIL if new layer.**
- [ ] **RESULT-SWAP Compliance:** Do high-tier successes (18+, 20+) trade IS for Special Effects only — no additional math steps? → **FAIL if new math added.**
- [ ] **NO PLACEHOLDERS:** Are there any empty sections, "TBD", or "future work" markers? → **FAIL.**

---

### Block 3 — Content Preservation
*Drawn from `00A_DESIGN_ATOMS_soul.md` Law 9 — Detail Preservation.*

- [ ] **No Pruning:** Did the draft accidentally delete historical rationale, approved deep-dives, Pillar mastery equations, or Methodology detail? → **FAIL.**
- [ ] **Line Count Audit:** If a document shrank during revision, perform a **Detail Integrity Audit** immediately. Was any "Flesh" lost from the "Skeleton"? → **FAIL if yes.**
- [ ] **DRY Check:** Does the draft re-explain a rule already defined in another chapter? → **FAIL. Cross-reference instead.**

---

### Block 4 — Thematic Integrity
*Drawn from `00A_DESIGN_ATOMS_soul.md` Law 10 and `00A_DESIGN_ATOMS_doctrine.md` §3.*

- [ ] **Saga Voice Intact:** Does the draft preserve evocative naming ("The Sejd-Thief", "The Godless", "Wyrd Strain")? No stripping of thematic flavor to save quota → **FAIL if stripped.**
- [ ] **Lore Is Rule:** Are mythological worldbuilding and tactical mechanics still presented together, not separated into "dry mechanics" and "optional lore"? → **FAIL if split.**
- [ ] **Pillar of Mystery:** Is the Wyrd treated as an intrusive force affecting all beings — not a player-controlled mana pool? → **FAIL if misrepresented.**

---

### Block 5 — Physical Realism
*Drawn from `00A_DESIGN_ATOMS_soul.md` Law 6 and Doctrine §3.*

- [ ] **Physics Test:** Does every mechanic make sense as a collision between two physical bodies? If it doesn't hold up physically, it does not belong in the core → **FAIL.**
- [ ] **Toolbox Philosophy:** Does the draft avoid "gamey" floating modifiers? Does it favor Physical Pre-Conditions and Material Tags instead? → **FAIL if floating modifiers added.**
- [ ] **Player-Driven Geometry:** Does tactical advantage come from hex positions and situational awareness — not stat-sheet bonuses? → **FAIL if stat bonuses substituted.**

---

### Block 6 — System Consistency
*Drawn from `00A_DESIGN_ATOMS_soul.md` Law 8 and Doctrine §4.*

- [ ] **Unified Constitution:** Is this rule consistent between the computer version (`thesaga`) and the board game (`boardgamesaga`)? Any deviation is a bug → **FAIL.**
- [ ] **Hardware Assumptions:** Does the rule assume Interactive Character Sheets for tracking Bleeding, SP recovery, BP resets, and Dynamic Initiative? → **FAIL if it assumes manual tracking of new resources.**
- [ ] **Organic Growth:** Was this rule triggered by a real tactical Need from the User — not pre-designed in anticipation? → **FAIL if pre-designed without User spark.**

---

## On Failure

Do not present the draft. Fix the failing items first. Only present when all blocks pass.

> "The variance in review should only be: *did the Agent capture the Atom correctly* — not *did the Agent invent a new kind of dice roll.*"
