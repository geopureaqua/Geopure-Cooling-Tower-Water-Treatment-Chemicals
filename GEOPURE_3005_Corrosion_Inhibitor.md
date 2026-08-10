# Geopure®3005: Corrosion Inhibitor (Multi-Metal Corrosion Inhibitor — RO Permeate/DM Makeup)

## Product Overview

Neutral-pH, multi-metal corrosion inhibitor purpose-built for cooling systems where makeup is **RO permeate or DM (demineralized) water** — i.e., hardness and alkalinity are already stripped out, so scale/threshold inhibition is not the design driver. The formulation exists to solve the corrosion problem that near-zero-TDS makeup actually creates: aggressive, poorly buffered water with negligible natural corrosion resistance, circulating against **mixed metallurgy — SS304/316, copper, mild steel, and galvanized iron (GI)** — each with a different, sometimes conflicting, pH and inhibitor requirement.

The **pH 7.0–8.0 as-supplied** target (vs. the acidic 2.5–3.5 concentrates of Geopure 2000/3000) is a deliberate design choice, not a formulation accident: GI corrodes rapidly outside roughly pH 6.5–9.5, so a near-neutral product protects the galvanized surfaces this system contains without requiring a separate pH-adjustment step. The trade-off is that keeping zinc in solution at pH 7–8 is chemically harder than in an acidic concentrate — see Manufacturing Procedure and the zinc-solubility note under Dosage Guidelines.

Target performance: corrosion rate <3 mpy (mild steel), <0.1 mpy (copper), no measurable pitting/crevice attack on 304/316 stainless at controlled chloride levels, no accelerated GI coating loss.

## Chemical Composition

*(Basis: % w/w as supplied — matches Manufacturing Procedure charge quantities directly)*

| Component | CAS Number | % w/w | Functional Role |
|---|---|---|---|
| Sodium Gluconate | 527-07-1 | 3.0 | Metal-ion sequestrant — keeps Zn²⁺ complexed and in solution at neutral pH; also general corrosion support |
| Sodium Benzoate | 532-32-1 | 4.0 | Ferrous-metal (mild steel) corrosion inhibitor |
| Sodium Molybdate | 7631-95-0 | 2.0 | Anodic corrosion inhibitor; also supports passive-film stability on 304/316 stainless |
| Zinc Oxide | 1314-13-2 | 1.5–2.0 | Cathodic corrosion inhibitor (Zn²⁺) |
| 1,2,3-Benzotriazole (BTA) | 95-14-7 | 0.5 | Copper/brass protection |
| HEDP (60% solution) | 2809-21-4 | 2.0 | Anodic film support; residual scale-threshold action for any incidental hardness ingress |
| Polyacrylic Acid (40–45% solution) | 9003-01-4 | 2.0 | Dispersant |
| AMPS/Acrylate Copolymer (~40% active) | 40623-75-4 | 2.0 | Dispersant, iron-oxide particulate control |
| Sodium Hydroxide (48% solution) | 1310-73-2 | q.s. to pH 7.0–8.0 (~3.0, see manufacturing note) | pH adjustment |
| RO / DM Water | 7732-18-5 | Balance | Solvent |

## Inhibition Mechanism

- **Anodic**: HEDP and orthophosphate contribution jointly support a protective iron film on mild steel; sodium molybdate additionally reinforces the native passive oxide layer on SS304/316, improving resistance to chloride-induced pitting
- **Cathodic**: Zn²⁺, held in solution by gluconate complexation at neutral pH, precipitates as Zn(OH)₂ at cathodic sites, blocking oxygen reduction
- **Copper protection**: BTA forms a chemisorbed Cu(I)-BTA film on copper/brass surfaces, preventing oxidative (blue-water) attack
- **GI compatibility**: operating near neutral pH avoids both the acid-side and caustic-side corrosion zones of zinc-coated steel; the zinc already present in solution reduces the driving force for the galvanizing itself to dissolve
- **Dispersion**: polyacrylic acid and AMPS/acrylate copolymer keep zinc-hydroxide colloids and iron oxide particulates suspended for blowdown removal rather than depositing on heat-transfer surfaces

## Manufacturing Procedure

### Batch Size: 100 kg

| Step | Action | Duration | Notes |
|---|---|---|---|
| 1 | Charge 50 kg RO/DM water | – | Ambient |
| 2 | Start agitator at 100 RPM | – | – |
| 3 | Add 3.0 kg sodium gluconate | 10 min | Dissolve completely — this chelates zinc ahead of Step 6 |
| 4 | Add 4.0 kg sodium benzoate | 10 min | Dissolve completely |
| 5 | Add 2.0 kg sodium molybdate | 10 min | Dissolve completely |
| 6 | Add 1.8 kg zinc oxide slowly | 15 min | Batch is still mildly acidic from upcoming HEDP addition sequence; if ZnO does not fully clear, proceed to Step 7 and recheck — full dissolution typically completes once HEDP is added |
| 7 | Add 0.5 kg BTA | 10 min | – |
| 8 | Add 2.0 kg HEDP (60% solution) | 10 min | Confirm batch is a clear solution (no ZnO haze) before proceeding |
| 9 | Add 2.0 kg polyacrylic acid (40–45% solution) | 10 min | – |
| 10 | Add 2.0 kg AMPS/acrylate copolymer (~40% solution) | 10 min | – |
| 11 | Slowly add sodium hydroxide (48% solution) to pH 7.0–8.0 | 20–30 min | Add in small increments (~0.5 kg), hold, and check for turbidity after each addition. **Do not exceed pH 8.0** — zinc complexation capacity is finite and excess alkalinity will precipitate Zn(OH)₂. If haze appears, back off and hold at the lower end (pH 7.0–7.3). Estimated total ~3.0 kg — confirm and record actual quantity on first production run |
| 12 | Makeup to 100 kg with RO/DM water | 5 min | Adds ~29.7 kg based on estimated NaOH charge |
| 13 | Mix 15 min | 15 min | Clear, colorless to pale straw liquid |
| 14 | QC sampling | – | – |

**Mass balance check:** Steps 1–11 total ≈70.3 kg raw charge (based on the estimated NaOH quantity); Step 12 makeup adds the balance to close at 100 kg. Confirm and lock the exact NaOH charge after the first titrated batch, then update this SOP with the verified figure rather than the estimate.

**Formulation caution — read before scaling up:** Unlike Geopure 2000/3000 (acidic concentrates, pH 2.5–3.5, where Zn²⁺ is freely soluble), this product holds zinc in solution at near-neutral pH entirely through gluconate/polymer complexation. That complexation capacity is finite. Do not add NaOH faster than the increments above, do not skip the gluconate/dissolution sequencing, and do not substitute a different chelant without re-verifying zinc solubility across the full pH 7.0–8.0 window.

### QC Specifications

| Parameter | Specification | Test Method |
|---|---|---|
| Appearance | Clear, colorless to pale straw liquid | Visual |
| pH (as supplied) | 7.0–8.0 | pH meter |
| Specific gravity (25°C) | 1.05–1.10 *(estimated — confirm against first production batch; lower than 2000/3000 due to lower total active loading and no excess free acid/caustic)* | Hydrometer |
| Total phosphonate (as PO₄) | 0.9–1.3% | UV spectrophotometry (acid/persulfate digestion required — see Monitoring Schedule note) |
| Zinc (as Zn) | 1.2–1.6% | AAS or EDTA titration |
| Polymer (as actives) | 1.3–2.0% | Turbidimetric |
| Microbial plate count | Report result *(see Storage and Handling note)* | Standard plate count |

*Basis for phosphonate spec: 2.0 kg HEDP 60% solution = 1.2 kg pure HEDP = 1.2% w/w; × PO₄-equivalent factor ≈0.92 → ≈1.10% as PO₄.*

*Basis for zinc spec: 1.8 kg ZnO (midpoint of 1.5–2.0% range) × Zn/ZnO mass ratio 0.8034 → ≈1.45% Zn; the stated 1.5–2.0% ZnO composition range converts to 1.2–1.6% Zn.*

*Basis for polymer spec: polyacrylic acid (2.0 kg at ~42.5% actives ≈0.85 kg) + AMPS/acrylate copolymer (2.0 kg at ~40% actives ≈0.80 kg) ≈1.65% total actives.*

## Dosage Guidelines

### Calculation Basis

Maintain in recirculating water:
- Zinc: 1–2 mg/L as Zn *(primary control parameter for this product — see note below)*
- Phosphonate: report as achieved (see note)
- Polymer: 2–5 mg/L actives

```
Product dose in makeup (mg/L) = Target recirculating concentration / (CoC × product active fraction)

Example (zinc as controlling parameter):
Target Zn = 1.5 mg/L in recirc, CoC = 10, product Zn fraction = 0.0145
Makeup dose = 1.5 / (10 × 0.0145) = 10.3 mg/L product in makeup
```

**Important note on dosing basis — this is not interchangeable with the 2000/3000 approach:** in Geopure 2000/3000, phosphonate residual is the practical dosing target and zinc follows along safely below it. In Geopure 3005, the Zn:phosphonate ratio is different, and at the high CoC this product is designed for, dosing to the classic 5–15 mg/L phosphonate window would push recirculating zinc to roughly 12–13 mg/L — well above the solubility ceiling this product's gluconate/polymer package can hold at neutral pH, producing zinc hydroxide haze and eventual heat-exchanger deposition instead of protection.

**Dose this product to the zinc target, not the phosphonate target.** The resulting phosphonate residual will typically run below the 5–15 mg/L range used for hardness-driven makeup — this is expected and is compensated by molybdate, benzoate, and BTA carrying more of the anodic/copper protection load in this formulation. Track phosphonate as a reporting parameter, not a control setpoint, for this product.

### Dosing by Makeup Hardness (Maximum Level — corrosion-limited, not scale-limited)

Because RO permeate and DM water carry negligible hardness, the ceiling on cycles of concentration here is **not** an LSI/scale limit — it is set by chloride buildup (stress-corrosion and pitting risk on 304/316 stainless) and by overall conductivity. The table below reflects that:

| Makeup Water Quality | Typical Hardness (mg/L CaCO₃) | Typical Conductivity (µS/cm) | Maximum CoC *(chloride-limited — assumes makeup Cl⁻ low enough to hold recirc Cl⁻ <250 mg/L for 304 SS; confirm against actual makeup analysis and tighten further if 316 SS operates above ~60°C)* | Product Dose in Makeup (mg/L) |
|---|---|---|---|---|
| RO Permeate | <5 | 10–50 | 8–10 | 12–15 |
| DM Water (Mixed Bed) | <2 | 1–10 | 10–12 | 10–13 |

*These CoC ceilings and the 250 mg/L chloride benchmark are practical engineering assumptions, not a substitute for a site-specific chloride/SCC assessment — confirm against actual makeup chloride analysis, operating temperature, and the specific 316 grade in service before locking a system's operating CoC.*

### Dosing Point
- Makeup water line or cooling tower basin
- Continuous dosing via metering pump
- Use conductivity-based blowdown control to maintain CoC (hardness-based blowdown control is not meaningful on this makeup quality)

## Application Methodology

### Startup (New System)
1. Fill system with RO permeate/DM water
2. Begin circulation
3. Slug dose GP-3005 at 3x normal rate for first 24 hours (passivation)
4. Reduce to maintenance dose set by the zinc-target calculation above
5. Begin biocide program after 24 hours

### Passivation Protocol
Initial film formation requires elevated zinc and inhibitor levels:
- Zinc: 4–6 mg/L for 72 hours *(lower ceiling than the 5–8 mg/L used on Geopure 2000/3000, reflecting this product's tighter zinc-solubility margin at neutral pH)*
- pH: 7.0–7.5 (hold the lower half of the operating band during passivation)
- After passivation, reduce to maintenance levels per the zinc-target dosing calculation

### Monitoring Schedule

| Parameter | Frequency | Method |
|---|---|---|
| pH | Continuous or 2x daily | pH meter |
| Conductivity | Continuous | Conductivity controller |
| Chloride | Weekly (increase to 2x/week if operating near the CoC ceiling) | Argentometric (Mohr) or ISE |
| Zinc (as Zn) | 3x/week | Zincon method or AAS |
| Phosphonate (as PO₄) | Weekly (reporting parameter only — see Dosage Guidelines note) | Field test kit — requires acid/persulfate digestion to hydrolyze phosphonate-bound P before molybdate colorimetry |
| Free chlorine / ORP | Continuous or 2x daily | DPD or ORP probe |
| Iron (dissolved) | Weekly | Phenanthroline method |
| Corrosion coupon rate | Monthly — run separate MS, copper, and 304/316 coupons given the mixed metallurgy | Weight loss method (ASTM D2688) |
| Microbiological (dip slides) | Weekly | TBC dip slides |

## Technical Data Sheet

| Property | Value |
|---|---|
| Product Name | Geopure® 3005 |
| Chemical Type | Zinc/molybdate/phosphonate blend — neutral pH, RO permeate/DM compatible |
| Appearance | Clear, colorless to pale straw liquid |
| pH (as supplied) | 7.0–8.0 |
| Specific Gravity (25°C) | 1.05–1.10 *(estimated — confirm on first batch)* |
| Total Phosphonate (as PO₄) | 0.9–1.3% |
| Zinc (as Zn) | 1.2–1.6% |
| Polymer Content (as actives) | 1.3–2.0% |
| Freezing Point | -3°C *(estimated — lower total dissolved actives than Geopure 2000/3000; confirm by lab measurement)* |
| Shelf Life | 12 months *(shorter than the 18-month rating on the acidic 2000/3000 products — see Storage and Handling)* |

## Safety Data Sheet (Summary)

### GHS Classification
- H315: Causes skin irritation *(revised down from H314 used on Geopure 2000/3000 — at pH 7.0–8.0 this product is not corrosive to skin in the way the acidic concentrates are; confirm against actual formulated-product testing rather than assuming)*
- H319: Causes serious eye irritation
- H410: Very toxic to aquatic life with long lasting effects (zinc)

### Environmental Note
Zinc discharge limits apply in most jurisdictions. India CPCB: Zn <5 mg/L in treated effluent. Size blowdown treatment accordingly.

### PPE
- Chemical-resistant gloves, splash goggles for bulk handling *(lower-severity PPE than the 2000/3000 acid-handling requirement, reflecting the neutral pH — verify against the finished-product SDS once lab-confirmed)*

## Storage and Handling

- HDPE containers preferred
- Temperature: 5–40°C
- Keep sealed to prevent evaporation and concentration increase
- **Microbial control note:** because this product is formulated near-neutral pH — unlike the self-preserving acidic Geopure 2000/3000 concentrates — it is more susceptible to microbial growth in storage, particularly in the gluconate and polymer fractions. Recommend either a low-dose preservative (e.g., BIT/MIT-based) in the formulation or a tightened shelf-life with routine microbial plate-count testing on stored drums/day tanks. This is reflected in the shorter 12-month shelf-life rating above pending preservative confirmation.
- Shelf life: 12 months (see note above)

## Troubleshooting Guide

| Problem | Probable Cause | Corrective Action |
|---|---|---|
| Zinc precipitation / milky concentrate or recirc water | pH exceeded 8.0 in manufacture or in the system, or zinc dosed against phosphonate target rather than zinc target (see Dosage Guidelines) | Reduce pH toward 7.0–7.5, redose based on the zinc-target calculation, do not chase phosphonate residual with this product |
| Pitting or crevice attack on 304/316 SS | Chloride has exceeded the CoC ceiling for the grade/temperature in service | Reduce CoC, verify makeup chloride, confirm 316 (not 304) is in service if operating above ~60°C |
| Accelerated GI coating loss | System pH has drifted outside ~6.5–9.5 | Check pH control point and dosing pump calibration; this product is designed to hold pH support within the GI-safe window when dosed correctly |
| Copper corrosion (blue water) | BTA underdosed or depleted by oxidizing biocide | Verify BTA residual, increase product dose, moderate oxidizing biocide feed rate |
| High corrosion rate on mild steel (>5 mpy) | Low zinc or molybdate residual, pH excursion low | Check residuals against zinc-target dose, verify pH |
| Persistent low phosphonate reading despite adequate corrosion protection | Expected for this formulation — see Dosage Guidelines note; also confirm field test digestion step was performed | No action needed if corrosion coupons and zinc residual are on target; if in doubt, re-test with digestion |
| Microbial growth / odor in stored concentrate | Near-neutral pH lacks the self-preserving effect of acidic concentrates | Run plate count, consider preservative addition, reduce storage interval between batches |
