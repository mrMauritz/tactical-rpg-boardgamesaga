# Tactical RPG BoardGameSaga — Development Tracking

This document tracks features that have been discussed or partially implemented, but require a "Deep Dive" or specific design phase before being finalized.

## 1. High-Priority Design Deep-Dives
| Date | Feature | Status | Notes |
| :--- | :--- | :--- | :--- |
| 2026-04-18 | **Internal Architecture & Magic** | SOLIDIFIED | Fused Soul-Trio (Önd, Óð, Lá) with 6 Pillars and Historical Laws. |
| 2026-04-18 | **Universal Alignment Physics** | SOLIDIFIED | Replaced generic class mechanics with 3 universal alignment physics (Law, Chaos, Wild). |
| Upcoming | **The Rule of Wild (Trade-off Mutations)** | PENDING | Design physical and mystic wild mutations across the 6 attributes. |
| Upcoming | **Resource Consumption** | STAGED | Definition of HP/SP/MG/Madness tactical expenditure. |

## 2. Advanced Tactical Content (Restricted to Classes/Monster Trees)
- [x] **Simple Perk Design:** Document created ([02_perks_and_traits.md](file:///c:/Workspace/tactical-rpg-boardgamesaga/rules/02_perks_and_traits.md)) with Organic Growth policy and three seed perks (*Unyielding*, *Hard Head*, *Nerves of Steel*).
- [ ] **The "Saga Choice" Blocks:** Systems for allowing characters to "Sacrifice" gear or take permanent injuries to avoid lethal blows.
- [ ] **Advanced Momentum Carry-over:** "Cleave" or "Momentum follow-up" rules for specific heavy-weapon classes.
- [ ] **Expanded Hit Table (3d6):** Assign specific mechanical meanings or activations to every value (1-20+), potentially triggered by weapons, skills, or perks.
- [ ] **Impulse/Momentum Tracking (Suggestion):** Evaluate as an alternative to the AP Segment system to increase fluid tactical pressure.
- [x] **Balance System Overhaul:** Shifted from flat recovery to **Balance States** (Stable, Unstable, Stumbling) with Defense-only penalties. Implemented **BP Soak (Steadfast/Grounded)** and stability-based resistance loss.

## 3. Cosmological Layer System (New — 2026-05-25)

The three cosmological layers (Önd/Life-Current, Wyrd, Oaths) have been established as the world-scale architecture. The following design questions need resolution before these layers have mechanical expression.

| Priority | Question | Notes |
| :--- | :--- | :--- |
| **HIGH** | **Wyrd Pressure — how does it manifest in play?** | Deep Óðr-tree investment stirs the Wyrd. Does this create a passive field effect on the battlefield hex? A GM-facing tracker? A visible status? Needs a mechanic that is atmospheric, not a combo table. |
| **HIGH** | **Oath Web — individual vs. party oaths** | Oaths already carry moral gravity. Design question: do inter-character oaths create a shared mechanical bond (e.g., linked SP recovery, shared fate-resistance), or is the effect purely narrative/campaign-level? |
| **MEDIUM** | **Life-Current disturbance (combat)** | When many beings bleed and die on a hex, the Life-Current is disturbed. Does this affect subsequent battles on that hex? Healing rolls? Spirit/Wyrd interaction? Relevant to both monster design and campaign-layer. |
| **MEDIUM** | **Non-human beings and the three layers** | Trolls, spirits, giants, undead — how do they relate to each layer differently? A spirit may exist purely in the Wyrd layer with no Önd anchor. An undead may have severed Önd but retained Lá. This affects which tree perks they can access. |
| **MEDIUM** | **The Frenzy anomaly — involuntary Wyrd contact** | The Frenzy tree at high tiers touches the Wyrd without intent. Design the threshold: at what investment level does this trigger, what does it look like mechanically, and who else on the battlefield feels it? |
| **LOW** | **Oath-breaking cosmological cost** | Established that a broken oath tears both the Life-Current and Wyrd simultaneously. Needs a mechanical expression beyond faction standing loss. Permanent Wyrd-mark? Attraction of hostile fate-attention? |
| **LOW** | **All-Lá party — mythic silence** | A party running exclusively Lá trees becomes fate-invisible. This is a feature, not a bug. Design the tradeoff: what do they lose (saga-renown, Wyrd-assistance, divine attention) and what do they gain (resistance to fate-manipulation)? |

## 4. World & Narrative Synergies
- [ ] **Character Progression and Body:** System for how Body, Frame, and Size evolve with character growth and training.
- [ ] **Wyrd Layer Integration (Combat):** How "Blessed" or "Cursed" weapon states modify the weapon impact tables.
- [ ] **Generational Gear:** Rules for how armor damage (Chapter 11) persists across saga generations if not repaired.

## 4. Monster Design
- [ ] **Rules for Massive Impact:** Handling impacts that significantly exceed the target's Body scale (Overrun/Momentum).
- [ ] **Character Progression and Body:** System for how Body, Frame, and Size evolve with character growth and training.
- [ ] **Non-Human Impact Tables:** Unique tables for claws, bites, and giant blunt impacts (e.g., trolls).

---
*Created: 2026-04-10*
