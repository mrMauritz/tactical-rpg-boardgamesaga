> **WHEN TO READ:** Only when **calculating 3-stage rolls**, determining **defensive capacity**, or **raising a skill** (Ch.3).

# PART II — SKILLS & PROGRESSION (BGS)

## Chapter 1 — The Skill Tier Ladder
Skills represent practiced competency and provide the primary static modifiers for the **3d6 Resolution Ladder**.

| Tier | Name | Bonus | Description |
| :--- | :--- | :--- | :--- |
| **0** | **Raw** | +0 | No meaningful exposure. |
| **1** | **Able** | +1 | Basic competency. Starting tier. |
| **2** | **Practiced** | +2 | Reliable in standard conditions. |
| **3** | **Proven** | +3 | Confident under pressure. |
| **4** | **Hardened** | +4 | Professional capability. |
| **5** | **Renowned** | +5 | **Soft Max.** Regional mastery. |
| **6** | **Legendary** | +6 | Beyond the natural ceiling. |
| **7** | **Elder** | +7 | Near the absolute limit of achievement. |
| **8** | **Saga-Named** | +8 | **Hard Cap.** The Wyrd has taken notice. |

### Skill Availability: The Attribute Gate
A Skill under a given Attribute is only trainable once that Attribute's **Bonus** is +1 or higher (per `01_system_foundations.md` Ch.2, this means Attribute Value ≥ 4). Below that, the Skill is locked, regardless of desire to train it. A **Master Trainer** can bypass this gate for a cost — see `26_CAMPAIGN_ECONOMY_WIP.md` Levers. Full composition detail: `01c_CHARACTER_BUILD_PIPELINE_WIP.md`. A locked Skill can still be attempted at Raw (+0), but it gains no skill XP (Ch.3).

---

## Chapter 2 — The "Natural" Skill Roster
Following the organic growth policy, only skills explicitly required for the core battle system are listed here.

### 1. Defensive Skills
*Governing Attributes provide their **Attribute Bonus** to the 3d6 check (END: Block, DEX: Parry/Dodge).*

- **Shield Fighting**: Governs **Active Blocking** and **Geometric Coverage** (Scaling protected facing).
- **Parrying**: Governs **Active Parry** capacity with weapons.
- **Dodging**: Governs **Active Dodge** capacity and evasion.
- **Stealth**: Moving unseen and setting up ambushes.
- **Athletics**: Total physical coordination ([Skiing], [Swimmer], [Climber]).
- **Navigation & Awareness**: Covers map-reading, weather-reading, and "reading the beat" (identifying enemy SP/Segments/Facing weaknesses) on the battlefield.

> **Detection (Opposed Check):** Stealth vs. Navigation & Awareness forms a symmetric opposed check — the same procedure applies whether a player is detecting a hidden enemy or an enemy is detecting a hidden player. See Chapter 12, `06_adventure_and_prep.md`, for its Prep Phase application.

### 2. Offense (Weapon Arts)
*Governing Attributes: STR or DEX.*

- **Blades / Heavy / Spears**: Proficiency with specific weapon classes.
- **Archery**: Proficiency with bows, crossbows, and slings.
- **Mounted**: Fighting and moving from the back of a mount. Has its own tree (`99_CLASS_TREES_WIP.md`, Mounted).

### 3. Utility & Adventure
*Governing Attributes: INT or DEX.*

- **Medicine**: Direct health intervention and stabilization.
- **Maintenance & Appraisal**: Repairing gear AND identifying physical weaknesses/condition of enemy equipment.
- **Engineering**: Structural knowledge, siege mechanics, and [Masonry].
- **Survival**: Foraging, hunting ([Tracking]), and field fire-starting.
- **Herbalism**: Identification of flora and [Toxicology].
- **Animal Handling**: Working with animals — [Falconry], [Herding].

### 4. Leadership & Legacy
*Governing Attributes: CHA or INT.*

- **Command**: Battlefield coordination. **Tier 3 unlocks Tactical Formations** (Shield-Wall, Wedge), allowing the player to apply group-level physical logic to the hex-map. 
- **Intimidation**: Attacking an opponent’s **Moral BP** through presence and threat.
- **Skaldic Art**: Recording deeds into the saga; influencing faction reputation.
- **Bartering**: Negotiating exchange rates in the Weight-and-Barter economy.
- **Lore**: General knowledge of the world, including [Law].
- **Rite Lore**: Knowledge of rites and sacrifice.

### 5. Mystic Arts
*Governing Attributes: WIL (Galdr), INT (Rúnar), CHA (Seiðr).*

Every spell includes a skill check. The skill is the technique only — power comes from Óðr ignition and a bond, and alignment decides how the caster reaches the Wyrd, not which technique (`01_INTERNAL_ARCHITECTURE_WIP.md` Axis 2, LOCKED 2026-11-21).

- **Galdr**: Spoken and sung charms (*Hávamál* 146–163).
- **Rúnar**: Carved runes (*Sigrdrífumál* 6–13; *Egils saga* 44, 72).
- **Seiðr**: The trance-travel rite (*Ynglinga saga* 7; *Eiríks saga rauða* 4).

---

## Chapter 3 — Skill Progression (LOCKED 2026-11-20)

A skill grows through use (`01c_CHARACTER_BUILD_PIPELINE_WIP.md` §3). Practice builds up quietly; the step up comes as a sudden insight on a strong roll.

### 1. What Counts
- **The check:** 3d6 + skill tier + governing Attribute Bonus, against difficulty (`01_system_foundations.md` Ch.1).
- **Where:** only checks made in events and missions count (`27_EVENTS.md` §0).
- **The map decides the rule**, not the skill: a check in event mode uses §2, a check on the tactical map uses §3. A lock picked while sneaking on the tactical map follows §3; a weapon used in a quarrel that stays inside the event follows §2.
- **Fail range:** the natural 3d6 results that still end in Fail on the ladder once skill, Attribute Bonus and difficulty are applied.
- **Attribute gate:** a locked skill (Ch.1) gains no skill XP until its Attribute Bonus reaches +1 or a Master Trainer opens the gate.

### 2. Event Mode
- Each check adds **2 XP per result in its fail range** to the skill's pool.
- Every choice that calls for a check adds; the same challenge twice in one event adds twice. The event's written choices limit how often a skill can be checked (`27_EVENTS.md` §10).

### 3. Tactical Map
Each attempt adds XP by the top of its fail range:

| Fail range up to | 3–5 | 6–8 | 9–12 | 13–15 | 16+ |
|---|---|---|---|---|---|
| Success | +0 | +1 | +2 | +3 | +4 |
| Non-success | −1 | −1 | −1 | −1 | −1 |

The pool never drops below 0.

### 4. Multiplier
| Check result | Multiplier |
|---|---|
| Fail | ×1 |
| Success | ×2 |
| Natural 18 | ×3 |

The multiplier applies both to the XP added and to the natural roll in the insight test (§5).

### 5. The Insight Test
On every counting check, after its XP is added to the pool:

**natural roll × multiplier + pool ≥ 100** → the skill earns **1 progress point** and its pool resets to 0.

The skill check is the test — no extra roll. While the pool is below 46 no roll can reach 100: practice only accumulates. From 46 a natural 18 can bring the insight, from 66 a strong success, from 97 any roll.

### 6. Recap
At the end of each event or mission, the progress made is summarised in the event's Resolution (`27_EVENTS.md` §10, step 5).

### 7. Raising the Tier
- **Cost:** reaching tier N costs **5 × N progress points** — 5 to reach tier 1, then 10, 15, 20, 25 (75 from Raw to Soft Max).
- **Use alone reaches tier 5** (Soft Max, Ch.1).
- **Parallel +1 sources:** an event reward (a saga reward is an event reward, `27_EVENTS.md` §5), master training (`26_CAMPAIGN_ECONOMY_WIP.md` Levers), or a bond reward (`24_BONDS_AND_DEVOTION_WIP.md`) each raise a skill by one tier. They work at any tier, and they are the only way past tier 5 to tiers 6–8.

---

## Chapter 5 — Skill Tags (Specializations)
While a **Skill Tier** represents your level of competency, a **Skill Tag** represents categorical knowledge. A character might be a master of Athletics (Tier 5), but without the correct tag, certain environmental maneuvers are impossible.

### 1. Function of Tags
- **Binary Requirement**: Some advanced maneuvers (e.g., Skiing) **require** a specific tag to attempt, regardless of Tier.
- **Specialization**: Tags provide **Advantage (+1 IS Die)** when applied to their specific niche.

### 2. Starting Tag Examples
| Skill | Example Tags |
| :--- | :--- |
| **Athletics** | [Skiing], [Swimmer], [Climber] |
| **Engineering**| [Masonry], [Shipwright], [Siege-Craft] |
| **Animal Handling** | [Falconry], [Herding] |
| **Herbalism** | [Toxicology], [Field-Poultice] |
| **Lore** | [Law] |
| **Galdr** | *Ljóðatal* charms (*Hávamál* 146–163): [Healing], [Blunting], [Unbinding], [Arrow-ward], [Curse-turning], [Fire-quenching], [Peace-making], [Sea-calming], [Battle-ward]; [Útiseta] (knowledge from the dead, *Hávamál* 157) |
| **Rúnar** | Rune kinds (*Sigrdrífumál* 6–13): [Sigrúnar] victory, [Ölrúnar] ale, [Bjargrúnar] birth, [Brimrúnar] sea, [Limrúnar] limb, [Málrúnar] speech, [Hugrúnar] mind |
| **Seiðr** | [Spá] foresight, [Weather], [Curse], [Hamfarir] shape-faring (*Ynglinga saga* 7) |
| **Navigation** | [Meteorology], [Sea-Farer] |

### 3. Acquisition
Tags are acquired through a character's **Culture** or **Background** at start. New tags can only be gained through rare downtime milestones or narrative legacy events.
