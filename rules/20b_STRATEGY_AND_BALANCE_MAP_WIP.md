# Strategy & Balance Map (WIP)

> [!WARNING]
> **DEVELOPMENT STATUS: FOUNDATIONAL SPARK.** This file maps every distinct strategy the current rules already support, across six zoom levels, from a **player-motivation** lens (when/why to choose it, when/why not to) rather than a raw mechanical-effect lens. It is a balance-audit tool, not new mechanics — no numbers here are invented. ⚠️ marks a strategy whose "why avoid" column has **no stated cost anywhere in the rules yet** — these are the concrete balance gaps, not an exhaustive design decision that the path should stay free. §7 re-indexes the same material by **category and dial** (Gear, Spatial, Alignment, etc.) rather than by zoom level — a second index over the same ground, not a replacement for §1–6.

**Source:** Synthesis of `05_battle_core.md`, `06_adventure_and_prep.md`, `07_weapon_and_armor_properties.md`, `95_HISTORICAL_COMBAT_WIP.md`, `97_ATTRIBUTE_IMPACT_WIP.md`, `01_INTERNAL_ARCHITECTURE_WIP.md`, `02_perks_and_traits.md`, `03_skill_system.md`, `94_RULE_OF_WILD_MUTATIONS_WIP.md`, `97b_ATTRIBUTE_FLAVOR_AXES_WIP.md`, `10_reference_tables.md`, `20_CAMPAIGN_CORE_WIP.md` through `26_CAMPAIGN_ECONOMY_WIP.md`, `96_OATHS_WIP.md`, `99_CLASS_TREES_WIP.md`, `01b_archetype_matrix.md`. Three-agent research pass, 2026-11-08.

**How to read Links:** cross-references by ID to strategies at *other* zoom levels that combine with or depend on this one. Illustrative, not exhaustive — add more as they're noticed.

---

## 1. Battle Zoomed Out — Winning the Encounter

| ID | Strategy | When/Why Choose It | When/Why Avoid It | Links |
| :-- | :--- | :--- | :--- | :--- |
| BO1 | Shield-Wall Formation | You're fielding mixed-armor units and want the party's best shield to protect everyone in the line. | Your plan needs mobility, flanking, or heavy swinging weapons — any of those breaks the wall. | BI5 (Anchor build) |
| BO2 | Swine-Array (Wedge) | You want one unit (the Point) to punch through a line with a momentum bonus. | ⚠️ No stated cost — flank exposure and an interrupted charge aren't addressed. Pick it when you can't yet see a reason not to. | BI5, BI6 |
| BO3 | Rear-Guard (Shared Cover) | You have a fragile ranged/caster unit you want shielded without them investing in Shield Skill. | Only covers front-facing ranged/reach — useless against flank/rear threats. | BI9 (Timer/caster-adjacent) |
| BO4 | Ambush/Surprise | You've invested in Scouting/Stealth and want to strip the enemy's defenses before the fight starts. | It's a symmetric opposed check — the enemy can win it and ambush *you* instead. ⚠️ No stated cost for a failed attempt beyond losing the bonus. | BI4 (Moral Collapse opens easier) |
| BO5 | Direct Assault | You want Renown and are willing to trade attrition risk for it. | You can't afford to lose HP/SP/BP reserves before a harder fight ahead. | CO3 |
| BO6 | Infiltration | You want to remove specific dangerous units from the fight without risking Battle Core at all. | ⚠️ No stated cost — presumably less Renown than Direct Assault, but this isn't written anywhere. | GO3 |
| BO7 | Numbers / Engagement-Cap Stacking (Swarm) | You have more bodies than the enemy and want to strip Active Defense from everyone but one attacker per target. | You need the headcount to pull it off — more companions to feed and pay (see the chain below). | **CI1 → BO7 → CO1** (the designer's own worked example) |
| BO8 | Negotiation (Pre-Battle) | You've built WIL/CHA and want to end the conflict with zero strikes. | ⚠️ No stated failure cost for trying and failing. | GI7, GI8 |
| BO9 | Terrain/Sabotage Prep | You have Prep-Phase time and want to shape the field (chokepoints, denial) before engaging. | Dynamic terrain changes are persistent and can hurt you too once triggered. | BI3 |
| BO10 | Leader-Targeting (Decapitation) | You can reach the enemy leader and want one kill to collapse the whole formation's morale. | ⚠️ No stated cost — leaders aren't written as harder to reach than anyone else. | BI10, BI4 |

## 2. Battle Zoomed In — Winning the Fight

| ID | Strategy | When/Why Choose It | When/Why Avoid It | Links |
| :-- | :--- | :--- | :--- | :--- |
| BI1 | HP Attrition (Kill Path) | You want the simplest, always-available win — no setup, no prerequisite state. | The enemy's armor is specifically built to soak this path (Table 7). | BO5 |
| BI2 | Systemic/SP Collapse | You want a "clean" win (Disabled, not dead) and can stack shock faster than they recover. | Armor SP Soak still mitigates it; raw HP output per die is lower than Blade/Axe. | — |
| BI3 | Positional/BP Collapse | You want a path armor *never* reduces, and can stomach being slower to land. | Explicit −1 Initiative / −1 Accuracy on the toolkit that gets you there. | BO9 |
| BI4 | Moral/Route Collapse | The target is already Unstable/Rattled+ and you want to end it without more damage. | Can't open a fight with this alone — it needs one of the other three paths to soften the target first. | BO4, BO10, CI4/GI's Cohesion-Route hook (`05_battle_core.md` Ch.8 §2) |
| BI5 | Anchor Build (STR) | You want to dominate the mass/RF comparison and force opponents out of Block/Parry entirely. | ⚠️ No stated cost for the pure-STR investment itself. | BO1, BO2 |
| BI6 | Connector Build (DEX) | You want the highest Initiative/Dodge ceiling — act and react before being meaningfully engaged. | ⚠️ No stated cost. | BO2 |
| BI7 | Vessel Build (END) | You want to win the SP-economy war of attrition outright. | ⚠️ No stated cost. | BI2 |
| BI8 | Engine Build (WIL) | You want to keep functioning through punishment others couldn't survive. | Explicit: The Relentless *spends your own HP* to buy back SP — burns the resource that feeds the HP-Collapse path against you. | BI1 |
| BI9 | Timer Build (INT) | You want to win the tempo war and react before the opponent's action resolves. | Low-INT failure state is written (Telegraphed/Lagging); a *committed* high-INT build's cost is silent. ⚠️ | BO3 |
| BI10 | Master Build (CHA) | You want to shortcut straight to Moral Collapse once a target is softened. | Has no self-sufficient way to reach the "already weakened" prerequisite — depends on another path first. | BO10, BI4 |
| BI11 | Alignment Power (Order/Wild/Chaos) | You want the power-ceiling or bonus-die upside each alignment grants. | Explicit, asymmetric costs per alignment — Oath-bound restriction / zero divine safety net / mirrored Law-of-Inversion penalty. | GI1–GI3 |
| BI12 | Crossed Architect (Lá+Óðr Hybrid) | You want both physical and mystic rule-breaks on one character. | Explicit: fatigue, chronic pain, lower max vitality when casting crossed. | GI10 |
| BI13 | Precision/Anatomical Specialist | You want a reliable debuff/control effect instead of a damage-variance spike. | Forfeits the IS Dice bonus entirely, needs a Skill 3+/5+ prerequisite, and only triggers on an 18+ roll (sub-1% band). | — |
| BI14 | Active-Defense Specialist | You want to answer more simultaneous attackers and beat the Engagement Cap. | Twin Ward needs a Progression Perk *and* Shield Fighting 3+ — not available by default. | BO7 |

## 3. Campaign Zoomed In — Managing the Party

| ID | Strategy | When/Why Choose It | When/Why Avoid It | Links |
| :-- | :--- | :--- | :--- | :--- |
| CI1 | Large Roster (Numbers) | You want enough bodies to run Swarm/Engagement-Cap tactics in battle. | Scales your draw against the Money/Food resource kernel — more mouths to feed. | **CI1 → BO7 → CO1** |
| CI2 | Small/Elite Roster | You want a tight, high-investment party and lower baseline upkeep. | Fewer bodies for Numbers tactics; no Engagement-Cap-stacking option. | CO3 (Elite/Costly economy pairs naturally with this) |
| CI3 | Roster Churn | You want unrestricted freedom to swap companions for maximum utility — never taboo'd. | Forfeits the Individual Cohesion a kept veteran would've earned; new hires don't count until Accepted. | GO2 (build experimentation) |
| CI4 | Party Stability | You want the real tactical payoff — high Party Cohesion lowers Moral Pressure DC, can auto-negate Route Checks. | ⚠️ No stated cost — a pure soft incentive, nothing is lost by staying put beyond foregone churn-flexibility. | BI4 |
| CI5 | Tolerance-Spending Leadership | You want decisive, favoritism-driven choices with full visibility (no hidden roll). | Exceeding the buffer costs you one or more members outright. | — |
| CI6 | Tolerance-Preserving Leadership | You want to avoid desertion risk entirely. | ⚠️ No stated cost for restraint itself. | — |
| CI7 | Fixed Class/Race Bond (e.g. Blessed Guard) | You want a potent, pre-loaded devotional bond without building it yourself. | Maximally irreversible — class change is explicitly "very rare"; Order-flavored versions risk Structural Collapse on misstep. | GI1, GI7 |
| CI8 | Alignment-Flavored Saga-Knot Bonding | You want a loyalty bond mechanically flavored to your alignment (shared defense / shared HP / volatile pact). | Break-cost matches your alignment's general cost (Structural Collapse / Organic Infection / Volatile Release). | GI1–GI3 |
| CI9 | All-Lá (Physical-Only) Composition | You want to stay mythically invisible and safe. | Explicitly forgoes the Pull/Destiny/Legacy hooks that mythic visibility opens. | GI10, GO4 |
| CI10 | Fondness Pairing | — | Named only — ⚠️ zero mechanism, benefit, or cost written yet. Not a usable strategy today, just a label. | — |

## 4. Campaign Zoomed Out — Running the Economy

| ID | Strategy | When/Why Choose It | When/Why Avoid It | Links |
| :-- | :--- | :--- | :--- | :--- |
| CO1 | Four-Resource Kernel Management | You want full transparency — Money/Food/Tolerance/Cohesion are all visible, no hidden rolls. | Stated as a floor, not a ceiling — specialized parties (casters, cavalry, ships) carry extra unmodeled overhead. | CI1, BO7 |
| CO2 | Push-Survival Orientation | — | Explicitly the game's own *disfavored* default: "produces reactive play, narrows freedom." Not a neutral alternative. | GI/GO pull contrast |
| CO3 | Pull-Chasing Orientation | It's the stated preferred mode — converts pursued possibilities into real capability via Bonds. | ⚠️ No stated cost anywhere — presented as strictly preferred, not balanced against anything. | GO1 |
| CO4 | Elite/Costly Economy (wealth bond) | You've committed to a Small/Elite roster and need a bond to subsidize high wages. | ⚠️ No stated cost beyond the universal bond doctrine (Traits w/ costs, irreversibility). | CI2 |
| CO5 | Equipment-Focused Economy (materials bond) | You want unique gear access through a faction relationship. | ⚠️ No stated cost specific to this path. | BI13, BI14 |
| CO6 | Illicit/Covert Economy (underworld bond) | You want black-market access for an outlaw-flavored strategy. | ⚠️ No stated cost specific to this path. | BO6 |
| CO7 | Race-Centred Economy (racial influence) | You want unique monsters/characters through racial bond influence. | ⚠️ No stated cost specific to this path. | CI7 |
| CO8 | Divinely-Supported Economy (divine bond) | You want party bonuses/protection from a divinity's favour. | The one Faction/Divinity path with an **explicit** cost: jealous divinities accept only one divine bond. | GI8 |
| CO9 | Bond Breadth Diversification | You want several strategic pipelines open at once, hedged. | Caps how strong any single bond's benefits can scale. | CO10 |
| CO10 | Bond Depth Concentration | You want full-strength benefit activation and the highest power-path thresholds. | Stakes more time/identity/future possibility on fewer bonds — costlier if one breaks. | GI7–GI9 |
| CO11 | New-World Legacy Restart | You want a fresh possibility-horizon next playthrough. | Purely structural in the text — no stated advantage/disadvantage language at all. | GO5 |
| CO12 | Continued-World Legacy | You want compounding history — later companies inherit this one's marks. | Same — purely structural, mechanism unaddressed. | GO5, GO6 |

## 5. Game Zoomed In — What Drives the Main Character

| ID | Strategy | When/Why Choose It | When/Why Avoid It | Links |
| :-- | :--- | :--- | :--- | :--- |
| GI1 | Order Alignment | You want Divine Intervention bonus dice and structural/passive protection. | Strictly Oath-Bound; Pious Conduit fails entirely outside its god's domain; Structural Collapse on betrayal. | BI11, CI7, CI8 |
| GI2 | Wild Alignment | You want low-friction, symbiotic power that negotiates rather than submits or steals. | Power fluctuates with local hex civilization level; every mutation has a hard-coded mirrored drawback; Organic Infection on betrayal. | BI11, CI8 |
| GI3 | Chaos Alignment | You want broken progression caps and immunity to Wyrd manipulation. | Zero divine safety net, can never wield Wyrd-magic (Godless); magnified backlash (Sejd-Thief); breaking a tether accelerates your own isolation. | BI11, CI8 |
| GI4 | Necessity Oath | You're backed against a cliff and need the exchange *now*. | Explicitly "the most fragile" — the thread outlives the need that created it. | — |
| GI5 | Custom Oath | You want the social/political integration of an inherited bond. | The Wyrd doesn't care that it's unfelt — it snaps for the same cost as a heartfelt vow. | CO4–CO8 |
| GI6 | Conviction-Oath | You want an oath that needs no external validation — the only kind a Chaos character can swear without contradiction. | Named "the most dangerous kind"; name and mechanical cost both still OPEN. | GI3 |
| GI7 | Faction Bond Devotion | You want to become "part of history" through a concrete political relationship. | Betrayal consequences run through real people/institutions; devotion loss can destroy the bond card outright. | CO4–CO7 |
| GI8 | Divine Bond Devotion | You want to become "part of meaning" through a concrete spiritual relationship. | Consequences are deliberately uncertain (curses/signs) — real cost, epistemically murky by design. | CO8 |
| GI9 | Dedication Bond Devotion | You want bond-style progression without needing a social or spiritual patron. | ⚠️ No dedication-specific cost written yet, beyond the universal bond doctrine. | — |
| GI10 | Destiny/Wyrd-Pressure Pursuit | You want the Wyrd to notice you and reveal a mythic destiny. | The same legibility that invites destiny makes you "a bright thread" — physically brittle, a target. | BI12, CI9 |
| GI11 | Heroic Resolution Pursuit | You want permanent Saga-Renown that outlives the character. | Bought with Physical Attrition and risk of Spiritual Burnout (Hollowing); full resolution requires death. | GI10 |

## 6. Game Zoomed Out — What Drives the Player

| ID | Strategy | When/Why Choose It | When/Why Avoid It | Links |
| :-- | :--- | :--- | :--- | :--- |
| GO1 | Pull Economy Engagement | You want proactive, choice-driven play instead of reactive survival. | ⚠️ No stated cost — text doesn't address what happens if pull sources run dry. | CO3 |
| GO2 | Power-Construction Experimentation | You want to theory-craft across many non-military power-forms. | Builds are "mainly cumulative and irreversible" — real opportunity cost, no free respec. | CI3 |
| GO3 | Archetype/Identity Collection | You want a legible "complete the build" meta-goal (36 named identities). | ⚠️ No stated cost or cross-playthrough tension specific to pursuing several. | BI11, GI1–GI3 |
| GO4 | Replayability via Divergent Destiny | You want fresh sagas from the same rules without needing new scripted content. | By design, withholds a calculable optimization target — you can't min-max destiny on purpose. | GI10 |
| GO5 | Legacy & Unlocks Pursuit | You want a finished saga to produce concrete future-facing content. | Flagged explicitly: no concrete unlock content or persistent-world save mechanics exist yet. | CO11, CO12 |
| GO6 | Persistent-World Continuation | You want an accumulating, authored-by-play world instead of a reset. | Mechanism for time-advancement effects on factions/divinities/events is an acknowledged open problem. | CO12 |
| GO7 | Roster/Cohesion Stewardship | You want the transparent, no-RNG reward of cultivating a long-term roster. | Churn's only cost is the foregone soft bonus — not a prohibition, so this is a preference, not a requirement. | CI3, CI4 |
| GO8 | Recognition/Status Accumulation | You want an accumulating, visible scoreboard of past deeds. | No player-facing cost beyond GI11's in-fiction Lá-brittleness/Hollowing risk. | GI11 |

---

## 7. Dial Taxonomy (Category View)

A **Dial** trades quality for quality — choosing one pole costs you the other. Arity isn't forced to two: a dial is as many-way as the rules actually support (Alignment is 3-way, Collapse-Path Targeting is 4-way). A **Lever** (§7.11) is different in kind — a one-way resource sink with no opposing pole of its own; its only cost is whatever else the same finite pool (Money/Food/Prep-time) didn't get spent on.

### 7.1 Gear (sub)
- **Weapon Weight** — Heavy/2H (reroll 1s, +1 IS Die, but −1 Initiative/−1 Accuracy) ↔ Versatile (no bonus, no penalty) ↔ Light/Agile (full Initiative/Accuracy, no mass bonus)
- **Hand Configuration** — Shield (BP/HP soak from the shield) ↔ Dual-Wield (extra Parry capacity, no soak) ↔ Two-Handed (max damage, no off-hand option)
- **Distance Control** — Reach/Spear (controls a zone; enemy must bind/displace to close) ↔ Close/Sword-Axe (short zone, relies on grapple-range once distance collapses)
- **Penetration** — Standard (full Armor Soak applies) ↔ Armor-Piercing Tag (bypass at 4+ threshold) ↔ Precision-Gap-Targeting (skill-gated full bypass on a high roll)
- **Headwear** — Helmed (head protection, blind/deaf to flank-rear) ↔ Open-Faced (full peripheral awareness, exposed to called shots)
- **Logistics** — Backup-Gear Carried (keeps fighting after gear breaks; costs carry-weight/Money) ↔ Travel-Light (mobile, but one Shield Sacrifice/weapon-bend ends your toolkit)
- **Ranged Tactics** — Suppression/Volley (forces shield-raise, opens gaps for allies, not meant to kill outright) ↔ Precision Sniping (aims to down one specific high-value target)

### 7.2 Body (sub)
- **Stamina Pacing** — Fatigue-Banked (keeps SP high, avoids Rattled/Staggered) ↔ All-Out Tempo (spends SP fast for more output now)
- **Range Discipline** — Grapple-Range (*Glíma* — control/pin, finish with a knife) ↔ Weapon-Range Maintained (keeps striking distance, avoids being grabbed)
- **Footing** — Footing-Aware (checks terrain, avoids slip/Critical-Fail) ↔ Reckless Mobility (moves fast/aggressively, risks the terrain's fail-space)

### 7.3 Spatial/Formation (sub)
- **Formation Shape** — Shield-Wall (shares the line's best BP Soak) ↔ Wedge (+1 IS Die on the Point's charge) ↔ Rear-Guard (extends a shield's BP to a non-shield ally) ↔ Skirmish-Loose (no shared bonus, but no formation-break risk)
- **Formation Discipline** — In-Formation (protected, thrust-only weapons) ↔ Stepped-Out (full weapon choice, exposed/breaks the formation)
- **Field Choice** — Terrain-Exploit (passive BP Soak from Stable Position, can reshape hexes) ↔ Open-Field (no terrain bonus, but no reshape-backfire either)

### 7.4 Psychological (sub)
- **Morale Pressure** — Terror/Intimidate (forces a Route Check via Terror-Gaze) ↔ Stealth-Avoid (removes the need for morale pressure entirely)
- **Verbal Warfare** — Taunt/Provoke (baits a reckless mistake) ↔ Silent Discipline (gives away nothing, creates no opening either)
- **Battle Opener** — Champion-Duel Opener (one duel sets the whole force's morale) ↔ Mass-Engagement Opener (no single-point morale risk, but no single-point morale win either)
- **Command Posture** — Lead-From-Front (triggers the Battle Opener, but exposed to Leader-Targeting) ↔ Command-From-Cover (safe from Decapitation, but can't open with a champion duel)
- **Combat State** — Berserker/Altered-State (stimulant/trance power boost now, pays with the *berserksgangr* crash after) ↔ Sober Discipline (steady output, no crash, no boost)

### 7.5 Combat Process (sub)
- **Initiative Timing** — First-Strike/Ambush (strips Active+Anticipated Defense if won) ↔ Open Engagement (no setup bonus, but no risk of losing the opposed check)
- **Fight Pacing** — Decisive-Kill (ends it fast, less exposure) ↔ Prolonged Attrition-With-Pauses (mutual rests, grinds the SP economy instead of HP)
- **Action Commitment** — Heavy Action (big guaranteed effect, e.g. Structural Collapse, costs 4 segments) ↔ Light/Multiple Actions (flexible, more options per turn, no single big payoff)
- **Engagement Timing** — Wait-for-Favorable-Conditions (sun/wind at your back) ↔ Engage-Immediately (no prep, but no delay risk)

### 7.6 Social/Aftermath (main)
- **Objective** — Lethal (no prisoner logistics, no ransom income) ↔ Ransom/Capture (income/political leverage, but must manage captives)
- **Aftermath Behavior** — Loot/Trophy (income/Renown, opens a counter-ambush window) ↔ Scorched-Earth/Destroy (denies the enemy everything, no income for you either) ↔ Disciplined Withdrawal (safe, nothing gained)
- **Feud Resolution** — Weregild-Settlement (ends the conflict with compensation) ↔ Blood-Feud Continuation (keeps the Blood-Tether thread alive, risks escalation)
- **Salvage** — Scavenge/Salvage (recovers gear/Money post-fight, costs time) ↔ Travel-Light (moves on fast, no salvage income)

### 7.7 Build/Flavor (main — already-locked canon, `97b_ATTRIBUTE_FLAVOR_AXES_WIP.md`)
- **Frame** — Light (−1 BP resist, −1 SP avoidance cost) ↔ Dense (+1 BP resist, +1 SP avoidance cost)
- **Load** — Pressure (sustained/maintained impact) ↔ Impulse (sudden/initial impact)
- **Temper** — Mobilization (+1 SP generation, −1 SP resist) ↔ Containment (+1 SP resist, −1 SP generation)
- **Fortitude** — Mental (+1 mental resist, −1 HP resist) ↔ Physical (+1 HP resist, −1 mental resist)
- **Attention** — Diffuse (+1 field awareness, −1 accuracy) ↔ Selective (+1 accuracy, −1 field awareness)
- **Tempo** — Control (+1 Readiness, −1 Initiative) ↔ Execution (+1 Initiative, −1 Readiness)

### 7.8 Alignment/Spiritual (main)
- **Alignment** — Order (Divine Intervention bonus dice, but Oath-Bound/Structural Collapse risk) ↔ Wild (symbiotic low-friction power, but fluctuates with hex civilization + mirrored mutation drawback) ↔ Chaos (broken caps/full Wyrd immunity, but zero divine safety net + accelerating isolation)
- **Oath Origin** — Necessity (secures survival now, most fragile — outlives its own justification) ↔ Custom (social integration, costs the same whether felt or not) ↔ Conviction (needs no external validation, only Chaos-compatible oath, still unnamed/unresolved)
- **Mythic Visibility** — Destiny-Seeking (Wyrd notices you, narrative payoff, but makes you brittle/a target) ↔ Mythically-Invisible (safe, but forgoes Pull/Destiny/Legacy hooks)

### 7.9 Campaign/Strategic Posture (main)
- **Build Synergy** — Streamlined/Mono-Alignment (internal synergy, less Tolerance friction, but one systemic weakness hits everyone at once) ↔ Diverse/Mixed (no single point of failure, but costs Tolerance/Cohesion capacity)
- **Headcount** — Swarm (Engagement-Cap numbers tactics, cheap replace, but strains the resource kernel) ↔ Gear-Elite (peak per-unit output, but no numbers tactics)
- **Devotion** — Deep (highest power-thresholds, strongest identity, but no redundancy if the bond breaks) ↔ Broad (resilient, hedged, but never peaks)
- **Combat Philosophy** — Attrition (durable, HP/SP-for-SP builds, but burns Food/healing fast) ↔ Rogue/Covert (avoids the fight, but nothing to fall back on if caught)
- **Tolerance Use** — Spend (decisive favoritism, no hidden roll) ↔ Preserve (avoids desertion risk, no stated cost for restraint)
- **Roster Approach** — Churn (unrestricted optimization) ↔ Stability (Individual Cohesion accrues, lowers Moral Pressure DC in battle)
- **World Continuity** — New-World (fresh possibility-horizon) ↔ Continued-World (compounding inherited history)

### 7.10 Win-Condition Targeting (main — core resolution choices)
- **Collapse-Path Targeting** — HP/Kill (universal, no prerequisite) ↔ SP/Shock (Disabled without killing, Glance Rule snowballs) ↔ BP/Stagger (armor never reduces it, but −1 Init/−1 Accuracy toolkit) ↔ Moral/Route (bypasses remaining damage once triggered, but needs the target already softened)
- **Defense Mode** — Active (Parry/Block, Engagement-Cap-limited) ↔ Passive (always available, weaker) ↔ Dodge-Only (forced at RF≥+4)
- **Damage vs. Control** — Raw IS-Dice Bonus (more damage on a Great/Perfect hit) ↔ Precision Effect Swap (guaranteed Stun/Bypass/Blind instead, forfeits the dice)
- **Battlefield Control vs. Direct Damage** — Grapple/Hook/Pin/Push (restrains/repositions, no direct damage) ↔ Strike (direct damage, no positional control)

### 7.11 Levers (not dials — one-way resource sinks against the shared pool)
Poison (ingredients/application vs. Food/Money) · Medicine/Healing Supplies (vs. Food/Money) · Repair Materials (vs. Money/Prep-time) · Fodder (vs. Food) · Reagents (vs. Money) · Ship/Transport Maintenance (vs. Money/Prep-time) · Bribes/Informants (vs. Money) · Purification/Ritual Cost (vs. Prep-time) · Scouting/Detection Investment (vs. Rest/other prep) · Sabotage Materials (vs. Money/Prep-time)

---

## The Pattern (Read This Before Filling ⚠️ Gaps)

Trade-offs exist almost everywhere the system **forces a choice between two named things** — an alignment, a resource, a tag, a prerequisite state. Trade-offs go missing almost everywhere a strategy is **just "pick this, it's good"** with no gate attached. The ⚠️ rows above aren't scattered oversights — they're one recurring shape. Closing them means asking, for each ⚠️: *what does choosing this cost, that choosing something else wouldn't?* — not inventing a number, but naming the missing axis.

---
*Status: Foundational spark — a balance-audit cross-reference, not new canon. Rows marked ⚠️ are tracked as the open balance work; the earlier dev-status flags on each source file (e.g. "Foundational Spark," "Strong direction") still govern how locked the underlying mechanic itself is. §7 adds a category/dial index (10 categories, ~40 dials, 10 Levers) over the same material — several dials there (Win-Condition Targeting, Ranged Tactics, Combat State, Action Commitment, Engagement Timing, Scorched-Earth, Hand Configuration's Versatile pole, Penetration's Precision-Gap pole) are newly named here and not yet cross-checked against §1–6's rows line-for-line. Last Updated: 2026-11-08.*
