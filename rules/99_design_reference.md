# DESIGN REFERENCE — INTERNAL ONLY
> **WHEN TO READ:** Only when **generating interactive map features, building structures, or defining sabotage outcomes**.

## 1. Material Structural Baselines (Board Game Sync)
Calculated for a "Single Hex Scale" object.

| Material | HP (Structural) | BP (Stability) | Weight Tier | Common Tags |
| :--- | :--- | :--- | :--- | :--- |
| **Thatch / Wattle**| 5 | 5 | Light | `Flammable`, `Vulnerable` |
| **Wood (Aged)** | 15 | 10 | Medium | `Flammable`, `Splintering` |
| **Wood (Solid/Oak)**| 30 | 25 | Heavy | `Flammable`, `Resilient` |
| **Stone (Dry)** | 40 | 60 | V. Heavy | `Brittle`, `Unstable` |
| **Stone (Mortared)**| 80 | 100 | Massive | `Heavy`, `Resilient` |
| **Iron** | 120 | 150 | Massive | `Resist`, `Conductive` |

## 2. Physical Tag Interactivity (The Toolbox)
- **`Flammable`:** Gains `Burning` tag if hit by `Fire` or high IS.
- **`Brittle`:** Blunt/Heavy IS damage is doubled.
- **`Unstable`:** Surpassing BP threshold triggers **Collapse** (Physical displacement).
- **`Conductive`:** Elements (Electricity, Heat) propagate through this object to adjacent units.

## 3. Sabotage & Prep Phase Mapping
- *Cutting Rigging:* Removes `Resilient` / Adds `Unstable`.
- *Weakening Supports:* Reduces `BP` to 1/3 of max.
- *Oiling the Area:* Adds `Slippery` (BP Penalty) and `Flammable` to the hex.
- *Poisoning Wells:* Triggers a `SP Threshold 2/3` state on enemy units at start.
