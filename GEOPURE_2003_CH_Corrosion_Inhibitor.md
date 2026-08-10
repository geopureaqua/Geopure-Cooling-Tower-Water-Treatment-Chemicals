# Geopure®2003 CH: Corrosion Inhibitor for Chilled Water Systems (Open, High Oxygen Ingress)

## Product Overview

Zinc/molybdate/polymer-dispersant corrosion inhibitor combined with an oxygen scavenger, purpose-built for **open chilled water systems where atmospheric oxygen ingress is continuous** — typically via an open expansion/surge tank or other atmospheric-exposed point in an otherwise closed circuit. This is a materially different design problem from a cooling tower or a sealed chilled loop: the corrosion driver here is sustained dissolved oxygen rather than concentration-driven scaling, and the elevated dispersant loading (PASP + terpolymer) is sized to handle the higher iron-oxide corrosion-product load that continuous oxygen ingress generates — a well-oxygenated system produces meaningfully more particulate iron oxide than a well-sealed one, and that has to go somewhere other than the heat-transfer surfaces.

**This product bundles a passive corrosion-inhibitor package (BTA/zinc/molybdate/gluconate) with an oxygen scavenger (sodium bisulfite) in a single formulation — a deliberate choice made per your request, but worth naming directly: scavenger consumption is driven by variable, load-dependent O₂ ingress, while the passive-film package depletes on a much slower, system-loss-driven timescale. Dosing one product to satisfy both consumption patterns means either overdosing the passive-film components to keep enough scavenger residual, or underdosing the scavenger to avoid wasting zinc/BTA/molybdate. Many programs run these as separate products for exactly this reason — worth revisiting if field performance data suggests a mismatch.**

Target performance: corrosion rate <3 mpy (mild steel), <0.1 mpy (copper), dissolved oxygen residual maintained below the corrosion-relevant threshold for the system's actual O₂ ingress rate (site-specific — see Dosage Guidelines).

## Chemical Composition

*(Basis: % w/w as supplied. BTA corrected from submitted 5.0 kg to 0.8 kg. Terpolymer confirmed as **Maxinal/Maxinol 5400** — a proprietary carboxylate/sulfonate/nonionic terpolymer trade product with no single CAS number (normal for this class of specialty blend). The "Zinc Oxide Solution" is confirmed as an in-house preparation: 1 kg ZnO + 7 kg phosphoric acid (85% grade assumed) + 42 kg water = **50 kg total stock batch** — this is a materially more dilute stock than assumed in the prior revision of this file, which had incorrectly assumed no dilution water was added. Both the phosphate contribution and the NaOH requirement below are corrected accordingly — this supersedes the previous round's figures, which were themselves a correction of an even earlier, wronger assumption. **Confirm the "Zinc" charge is genuinely ZnO and not metallic zinc dust** — ZnO produces water on reaction with phosphoric acid; metallic zinc produces flammable hydrogen gas.)*

| Component | CAS Number | % w/w | Quantity (100 kg batch) | Functional Role |
|---|---|---|---|---|
| Polyaspartic Acid (liquid, ~40% assumed) | 25608-40-6 | 18.0 | 18.0 kg | Green dispersant — calcium carbonate/metal-oxide dispersion, sized for elevated iron-oxide load |
| Terpolymer (Maxinal/Maxinol 5400) | Proprietary blend — no CAS per SDS | 15.0 | 15.0 kg | Carboxylate/sulfonate/nonionic multifunctional scale/deposit dispersant, zinc-compatible |
| Sodium Bisulfite (40% solution) | 7631-90-5 | 4.0 | 4.0 kg | Dissolved oxygen scavenging |
| Zinc-Phosphate Stock (in-house: 1 kg ZnO + 7 kg H₃PO₄ 85% + 42 kg water → 50 kg stock) | 1314-13-2 (ZnO) / 7664-38-2 (H₃PO₄) | 4.0 | 4.0 kg | Cathodic corrosion inhibitor (Zn²⁺) with a modest incidental phosphate contribution |
| Sodium Molybdate | 7631-95-0 | 3.0 | 3.0 kg | Anodic inhibitor for carbon steel/iron |
| Sodium Gluconate | 527-07-1 | 3.0 | 3.0 kg | Metal-ion complexation, zinc stabilization, general corrosion support |
| Sodium Hydroxide (Caustic Lye, 48%) | 1310-73-2 | **1.0** *(corrected — the previous round's 5.1 kg assumed an undiluted, highly concentrated stock; the actual free-acid load at this dilution is much smaller)* | **1.0 kg** | pH adjustment to target 7.0–7.5 |
| 1,2,3-Benzotriazole (BTA) | 95-14-7 | **0.8** *(corrected from submitted 5.0 kg)* | **0.8 kg** | Copper, brass, and Cu-alloy corrosion inhibitor |
| DM/RO Water | 7732-18-5 | Balance (≈51.2) | 51.2 kg | Carrier |

## Inhibition Mechanism

- **Oxygen control**: sodium bisulfite reacts directly with dissolved O₂ (2NaHSO₃ + O₂ → 2NaHSO₄), removing the primary corrosion driver in this system before it can attack any metal surface. This reaction is uncatalyzed in this formulation — reaction kinetics at chilled-water temperatures (typically 7–12°C) are slower than a catalyzed (e.g., cobalt-catalyzed) sulfite/bisulfite system would achieve. Given the explicitly stated continuous, high O₂ ingress, **confirm this uncatalyzed system can keep pace with your actual measured ingress rate** — if not, a catalyzed scavenger or a mechanical fix (closing the atmospheric exposure point, nitrogen blanketing the expansion tank) may be a more effective root-cause solution than increasing chemical dose alone.
- **Anodic**: sodium molybdate adsorbs onto anodic sites, reinforcing the passive oxide layer on mild steel/carbon steel
- **Cathodic**: Zn²⁺, supplied as a pre-formed zinc solution and held complexed by sodium gluconate at neutral pH, precipitates as Zn(OH)₂ at cathodic sites, blocking oxygen reduction at any residual dissolved O₂ the scavenger hasn't yet consumed
- **Copper protection**: BTA forms a chemisorbed Cu(I)-BTA film on copper/brass/Cu-alloy surfaces
- **Dispersion**: PASP and the terpolymer jointly disperse calcium carbonate and — the more important role in this specific system — the elevated iron-oxide corrosion product generated by sustained oxygen exposure, keeping it suspended for removal at blowdown/drain points rather than depositing on chiller tube surfaces

## Manufacturing Procedure

### Batch Size: 100 kg

| Step | Action | Duration | Notes |
|---|---|---|---|
| 1 | Charge 40 kg DM/RO water | – | Ambient |
| 2 | Start agitator at 100 RPM | – | – |
| 3 | Add 3.0 kg sodium gluconate | 10 min | Dissolve completely — complexes zinc ahead of Step 6 |
| 4 | Add 18.0 kg polyaspartic acid (liquid) | 10 min | – |
| 5 | Add 15.0 kg terpolymer | 10 min | – |
| 6 | Add 4.0 kg zinc-phosphate stock (in-house preparation — see stock prep note above) | 10 min | This stock is now confirmed as a dilute (~2% ZnO, ~11.9% H₃PO₄) in-house preparation, not a concentrated commercial product — no special staged-dissolution discipline expected, but confirm the stock is visibly clear/stable before charging |
| 7 | Add 3.0 kg sodium molybdate | 10 min | Dissolve completely |
| 8 | Add 0.8 kg BTA | 10 min | Confirm full dissolution/clarity before proceeding |
| 9 | Slowly add sodium hydroxide (48% solution) to pH 7.0–7.5 | 15–20 min | **Corrected to ~1.0 kg** (the previous round's 5.1 kg estimate assumed an undiluted, over-concentrated stock — this batch's actual free-acid load is much smaller). Add in increments, check clarity/pH after each; confirm exact quantity by titration on the first batch |
| 10 | Add 4.0 kg sodium bisulfite (40% solution) | 5 min | **Add last, immediately before makeup and packaging.** Minimize agitation time after this addition — extended air-entraining agitation consumes scavenger before the product ever reaches the customer |
| 11 | Makeup to 100 kg with DM/RO water | 5 min | Adds ~11.2 kg |
| 12 | Mix briefly, 5–10 min only | 5–10 min | Shorter mixing window than prior products in this line — deliberately, to protect bisulfite residual |
| 13 | Package promptly into sealed HDPE drums, minimizing headspace air | – | Consider nitrogen-blanketing drums if extended storage before dispatch is expected |
| 14 | QC sampling | – | Sample and test promptly — do not let a sample sit open to air for extended periods before bisulfite/sulfite assay |

**Mass balance check:** Steps 1–10 total ≈88.8 kg raw charge (40 initial water + 3 gluconate + 18 PASP + 15 terpolymer + 4 zinc-phosphate stock + 3 molybdate + 0.8 BTA + 1.0 NaOH + 4 bisulfite); Step 11 makeup adds ≈11.2 kg to close at 100 kg. ✓ *(This is the third iteration of this balance — closes correctly now that both the BTA correction and the properly-diluted zinc-phosphate stock concentration are accounted for.)*

### QC Specifications

| Parameter | Specification | Test Method |
|---|---|---|
| Appearance | Clear, pale straw to light amber liquid | Visual |
| pH (as supplied) | 7.0–7.5 | pH meter |
| Specific gravity (25°C) | 1.10–1.18 *(estimated — confirm on first production batch)* | Hydrometer |
| Zinc (as Zn) | 0.05–0.08% *(corrected — basis: 4.0 kg of the properly-diluted 50 kg zinc-phosphate stock at 2.0% ZnO → 0.08% ZnO in the batch → ×0.8034 Zn/ZnO ratio → ≈0.064% Zn — much lower than either prior estimate, now that the stock's actual dilution is known)* | AAS or EDTA titration |
| Phosphate (as PO₄) | 0.35–0.55% *(corrected — basis: 4.0 kg stock × ~11.9% pure H₃PO₄ ≈0.476% H₃PO₄ in batch × 0.9691 conversion factor ≈0.46%)* | UV spectrophotometry |
| Molybdate (as MoO₄) | 1.7–2.2% *(basis: 3.0 kg sodium molybdate dihydrate × 0.661 conversion factor → ≈1.98%)* | Colorimetric (thiocyanate method) or ICP |
| Total dispersant actives (PASP + Maxinal 5400) | 11–15% *(basis: both assumed ~40% actives — confirm against actual raw material COAs)* | Turbidimetric or supplier COA cross-check |
| Sodium bisulfite (as NaHSO₃) | 1.4–1.8% | Iodometric titration |
| BTA content | 0.6–0.9% | HPLC or UV |
| Microbial plate count | Report result | Standard plate count |

## Dosage Guidelines

### Calculation Basis

*Reinterpreted from a continuous makeup/CoC framework: most chilled water systems, even "open" ones with an atmospheric-exposed expansion tank, are effectively fixed-volume, closed circuits without continuous blowdown — dosing is based on total system volume for the initial charge, with periodic top-up tied to measured water loss and residual decline, not a continuous makeup-stream calculation.*

**Initial system charge:**
```
Product required (kg) = System volume (L) × Target Zn concentration (mg/L) / (Product Zn fraction × 1,000,000)

Example:
System volume = 20,000 L
Target Zn = 1.5 mg/L
Product Zn fraction = 0.0064
Product required = 20,000 × 1.5 / (0.0064 × 1,000,000) = 4.7 kg
```

**Oxygen-scavenger sizing — requires your field O₂ data, not a rule of thumb:**
This product's bisulfite content gives it a scavenging capacity of roughly **2.2–2.5 g O₂ per kg of product** (based on the ~1.6% NaHSO₃ content and the standard ~6.5:1 NaHSO₃:O₂ mass reaction ratio). To size the maintenance/top-up dose correctly, you need the system's actual measured dissolved-oxygen ingress rate (mg O₂/day or similar) — this varies enormously by system and cannot be assumed. Recommend a field DO measurement (before and after a known dosing interval) on the first site this is deployed to, rather than applying a generic ppm target.

**Top-up dosing:** driven by measured water loss (leaks, minor evaporative loss at the open expansion point, sampling/blowdown) plus scavenger consumption from ongoing O₂ ingress — track both separately, since they deplete the product's two functions at different rates (see the bundling note in Product Overview).

### Dosing by System Condition (Maximum Level — corrosion-limited, not scale-limited)

*Reinterpreted from "Dosing by Makeup Hardness": a chilled water system doesn't concentrate via evaporation the way an open cooling tower does, so there is no CoC-driven hardness table to build here. The genuinely useful version of this table, given your own framing that this is about corrosion rather than scale, is dose scaled to oxygen-ingress severity — the actual driver in this system:*

| Oxygen Ingress Severity | Typical DO Residual (mg/L) | Initial Zn Target (mg/L) | Scavenger Top-Up Frequency |
|---|---|---|---|
| Moderate (intermittent atmospheric exposure) | 2–4 | 1.0–1.5 | Weekly, adjust to measured DO trend |
| High (continuous atmospheric exposure — as stated for this system) | 4–8+ | 1.5–2.5 | 2–3x/week, or continuous small-dose feed if practical |

*These bands are practical engineering assumptions, not derived from this specific site's DO data — confirm against actual field measurement before locking a top-up schedule.*

### Dosing Point
- Shot-feed via a pot feeder or chemical feed tank into the system return line, or dosed directly at the expansion/surge tank
- Not a continuous makeup-line application — batch/periodic dosing tied to system volume and measured residuals, not a continuous metering pump against a makeup stream

## Application Methodology

### Startup (New System)
1. Fill system with DM/RO or clean makeup water
2. Begin circulation
3. Charge initial slug dose at 2–3x the calculated maintenance concentration for the first 48–72 hours (passivation)
4. Reduce to maintenance/top-up dosing per the calculations above
5. Establish a DO monitoring baseline immediately — this is the parameter this program lives or dies on, more than in a typical closed chilled loop

### Passivation Protocol
- Zinc: elevated to 4–6 mg/L for 72 hours during initial passivation
- Molybdate: elevated to 30–50 mg/L for 72 hours
- pH: hold at 7.0–7.5
- Monitor DO closely during this window — passivation film formation is compromised if oxygen residual is not being controlled effectively during the same period
- After passivation, reduce to maintenance levels

### Monitoring Schedule

| Parameter | Frequency | Method |
|---|---|---|
| pH | Weekly (chilled systems change more slowly than cooling towers — daily monitoring is generally unnecessary here) | pH meter |
| Dissolved oxygen | 2–3x/week minimum, given the stated high-ingress condition — this is the primary control parameter for this product | DO meter/probe |
| Zinc (as Zn) | Weekly | Zincon method or AAS |
| Molybdate (as MoO₄) | Weekly | Colorimetric or ICP |
| Sulfite/bisulfite residual | 2–3x/week, tracked separately from the corrosion-inhibitor residuals | Iodometric titration |
| Iron (dissolved + particulate) | Weekly — expect this to run higher than a well-sealed system given the stated O₂ ingress | Phenanthroline method (dissolved); gravimetric or turbidity for particulate |
| Corrosion coupon rate | Monthly — run separate mild steel and copper coupons | Weight loss method (ASTM D2688) |
| Microbiological (dip slides) | Weekly | TBC dip slides |

## Technical Data Sheet

| Property | Value |
|---|---|
| Product Name | Geopure® 2003 CH |
| Chemical Type | Zinc/molybdate/dispersant blend with oxygen scavenger — neutral pH, for open chilled water systems |
| Appearance | Clear, pale straw to light amber liquid |
| pH (as supplied) | 7.0–7.5 |
| Specific Gravity (25°C) | 1.10–1.18 *(estimated)* |
| Zinc (as Zn) | 0.05–0.08% |
| Phosphate (as PO₄) | 0.35–0.55% |
| Molybdate (as MoO₄) | 1.7–2.2% |
| Total Dispersant Actives | 11–15% |
| Sodium Bisulfite (as NaHSO₃) | 1.4–1.8% |
| Freezing Point | -3°C *(estimated)* |
| Shelf Life | **9 months** — shorter than the rest of this product line because sodium bisulfite slowly self-oxidizes even in sealed storage; re-assay bisulfite residual before dosing any stock approaching this age |

## Safety Data Sheet (Summary)

### GHS Classification
- H315: Causes skin irritation
- H319: Causes serious eye irritation
- H411: Toxic to aquatic life with long lasting effects (zinc; lower severity than the H410 rating on the acidic zinc products given the much lower zinc loading here — confirm against actual finished-product testing)

### Environmental Note
Zinc discharge limits apply — India CPCB: Zn <5 mg/L in treated effluent. This product carries a modest phosphate contribution (~0.35–0.55% as PO₄) from the zinc-phosphate stock — confirm local total-phosphorus discharge limits if relevant, though the loading is much lower than initially estimated in an earlier draft of this document. Sulfite/bisulfite discharge also consumes oxygen demand in receiving water (COD contribution) — factor this into effluent planning if this product's blowdown/drain water goes to a sensitive discharge point.

### PPE
- Chemical-resistant gloves, splash goggles for bulk handling

## Storage and Handling

- HDPE containers only
- Temperature: 5–35°C
- Keep sealed, minimize headspace air — bisulfite content makes this more air-sensitive in storage than the rest of this product line
- **Critical incompatibility warning:** never store or mix this product near or with your acid-based descaling products (Geoclean 1050, etc.). Sodium bisulfite reacts with acid to release SO₂ gas — segregate physically in the warehouse, same category of hazard as the chlorine-gas warning already in place on the acid product line
- Shelf life: 9 months — re-assay bisulfite residual before use on any stock nearing this age

## Troubleshooting Guide

| Problem | Probable Cause | Corrective Action |
|---|---|---|
| DO residual not dropping despite regular dosing | Uncatalyzed bisulfite reaction too slow for the actual O₂ ingress rate, or ingress rate underestimated | Get an actual field DO ingress measurement; consider a catalyzed scavenger or mechanical fix (seal/blanket the atmospheric exposure point) rather than simply increasing dose |
| High iron (dissolved or particulate) despite adequate zinc/molybdate residual | Expected consequence of high O₂ ingress generating corrosion product faster than a sealed system — this is what the elevated dispersant loading is for | Confirm dispersant residual is adequate; if iron keeps climbing, the root issue is likely still oxygen control, not dispersancy |
| Zinc precipitation / haze | pH exceeded target range, or zinc solution stability limit exceeded (confirm with supplier) | Reduce pH toward 7.0, confirm zinc solution's stable pH range with supplier |
| Copper corrosion (blue water) | BTA underdosed | Verify BTA residual, increase dose |
| Bisulfite residual reads unexpectedly low on a fresh batch | Excess air entrainment during manufacture (Step 10–12), or extended storage before use | Review manufacturing mixing time; re-assay stock before use if storage interval is significant |
| SO₂ odor / gas evolution during storage or handling | Product has been contaminated with or stored near an acidic product | Stop use immediately, ventilate area — do not continue dosing from a compromised drum |
