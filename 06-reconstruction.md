---
title: "Image Reconstruction and Postprocessing"
nav_order: 6
description: "How to reconstruct CTCA data, apply postprocessing tools, grade stenosis with CAD-RADS 2.0, and recognise high-risk plaque features."
---

Turning raw CTCA data into a diagnostic study depends as much on phase selection, reconstruction parameters, and postprocessing technique as on the acquisition itself. This chapter walks through the practical workflow from ECG-phase choice to CAD-RADS 2.0 reporting, with explicit thresholds for stenosis grading, plaque characterisation, and escalation.

{% tabs chapter-6 %}
{% tab chapter-6 Reconstruction %}

## Phase selection

- <<Primary diastolic phases: 70%, 75%, and 80% of the R–R interval, best for HR ≤65 bpm.>>
- <<Systolic phases at 35%, 40%, 45% are useful if HR ≥75 bpm, frequent ectopy, or diastolic blurring.>>
- HR 65–75 bpm or variable: reconstruct both diastolic and systolic sets and compare.
- Arrhythmia: reconstruct multiple phases (e.g. 30–90% every 5%) and pick the least motion-affected per segment.
- **Clinical trigger:** if a proximal segment is motion-degraded in diastole, always check systolic 35–45% before declaring non-diagnostic.

## Core reconstruction parameters

- **Slice thickness:** 0.5–0.75 mm (typical 0.6 mm).
- **Increment:** 0.25–0.4 mm (50% overlap; 0.3 mm for 0.6 mm slices).
- **Matrix:** 512×512 routine; 1024×1024 for stents/small vessels if available.
- **FOV:** tight cardiac 100–140 mm; 80–100 mm around stents.
- **Kernel:** medium-smooth for lumen/plaque; sharper edge-enhancing for stents/calcification.
- **Iterative reconstruction:** moderate strength — avoid extremes that blur plaque margins.
- **Dual-energy (if available):** 60–70 keV for iodine contrast; <<80–90 keV monoenergetic reduces beam hardening and blooming from calcium and stents.>>
- **Motion correction:** apply only if it visibly reduces blurring without creating edge artefacts; verify against raw phase recon.

## Window/level starting points

- Lumen: W 800 / L 300 HU
- Soft plaque: W 600 / L 150 HU
- Calcification/stents: W 1,200–1,500 / L 250–300 HU

## Quality checks

- <<Mean coronary luminal attenuation should be 250–350 HU; below 200 HU with marked noise is non-diagnostic.>>
- Verify SNR allows wall–lumen interface visualisation.

{% endtab %}
{% tab chapter-6 Postprocessing %}

## Centreline and CPR

- Auto-generate centrelines for RCA, LM, LAD, LCx; add D1/D2, OM1/OM2, PDA/PLV.
- Manually correct at sharp bends, calcified plaque, and across stenoses — auto-tracking commonly cuts corners or dives into plaque.
- Use a consistent segment model (e.g. SCCT 18-segment) and state it in the report.
- **Pitfall:** <<off-centre CPR exaggerates stenosis — always confirm lumen on true orthogonal cross-sections.>>

## CPR settings

- One CPR per main vessel and major branch.
- Synchronous perpendicular cross-sections at 0.5–1.0 mm intervals.
- Default CPR thickness 1–2 mm; 3–5 mm slab MIPs for overview only.

## MPR, MIP, VR

- **MPR (thin):** the primary diagnostic view for stenosis and plaque morphology.
- **MIP (3–5 mm):** good for course and graft overview; <<do not grade stenosis on MIP alone — it overestimates calcified disease.>>
- **VR:** orientation and communication only; not diagnostic.

## Calcium scoring (if non-contrast acquired)

- <<Calcified focus defined as >130 HU over an area ≥1 mm².>>
- <<Agatston categories: 0 (none), 1–10 (minimal), 11–100 (mild), 101–400 (moderate), >400 (severe).>>
- Report total and per-vessel scores; reference age/sex percentiles where available.

## Tailored stent recon

- Sharpest reasonable kernel, 0.5–0.6 mm slices, 0.25–0.3 mm increment.
- Tight FOV 80–100 mm; 1024 matrix if available.
- W 1,200–1,500 / L 250–300 HU.
- <<Stents ≤2.5–3.0 mm diameter are often non-diagnostic due to blooming — state the limitation explicitly.>>

{% endtab %}
{% tab chapter-6 Stenosis and CAD-RADS %}

## How to measure stenosis

- Identify minimal luminal diameter (MLD) on orthogonal cross-sections.
- Reference diameter = average of proximal and distal normal segments (avoid positive remodelling and tapering bias).
- **Diameter stenosis (%) = 100 × (1 − MLD / reference diameter).**

## CAD-RADS 2.0 categories

- <<0%: no plaque — CAD-RADS 0.>>
- <<1–24%: minimal — CAD-RADS 1.>>
- <<25–49%: mild — CAD-RADS 2.>>
- <<50–69%: moderate — CAD-RADS 3.>>
- <<70–99%: severe — CAD-RADS 4A.>>
- <<Left main ≥50% or three-vessel obstructive disease — CAD-RADS 4B.>>
- <<100% occluded — CAD-RADS 5.>>

## Special considerations

- <<Left main ≥50% diameter stenosis is haemodynamically significant by convention.>>
- Ostial lesions: measure in both axial and orthogonal planes.
- <<Minimal lumen area (MLA) <4.0 mm² in proximal segments suggests functional significance but is less validated on CT than IVUS.>>

## CAD-RADS 2.0 modifiers

- **N** non-diagnostic
- **S** stent present (state assessability)
- **G** graft present
- **V** vulnerable/high-risk plaque features
- **C** severe coronary calcium burden affecting interpretation
- <<**F** CT-FFR performed; + result ≤0.80 (functionally significant), − result >0.80.>>

## High-risk plaque features (modifier V)

- <<Low-attenuation plaque: <30 HU.>>
- <<Positive remodelling: remodelling index >1.1.>>
- Napkin-ring sign: central low-attenuation core with thin hyperattenuating rim.
- <<Spotty calcification: calcific foci <3 mm in maximum length with arc <90° around the lumen.>>

Any V feature in a 50–69% lesion lowers the threshold for CT-FFR or functional testing.

{% endtab %}
{% tab chapter-6 Pitfalls and Escalation %}

## Common pitfalls and fixes

- **Diastolic motion:** check 35–45% systolic phases; consider motion-correction recon.
- **Stair-step/banding (prospective):** review adjacent phases; if persistent in a critical segment → declare N and suggest alternative imaging.
- **Centreline misregistration:** manually adjust; confirm stenosis on perpendicular cross-sections.
- **Calcification blooming overcalls:** avoid MIP for grading; use sharper kernel, 80–90 keV monoenergetic, tighter FOV, 1024 matrix; diagnose on thin MPRs.
- **Venous contamination:** narrow window or use later phase recon; trace carefully on CPR.
- **Heterogeneous contrast:** choose the phase with most uniform enhancement; target mean coronary HU ≥250.
- **Over-smoothing:** reduce iterative strength if plaque margins look "melted".

## Non-diagnostic triggers (declare in report)

- <<Lumen non-assessable across ≥50% of the length of a clinically important segment due to motion or blooming.>>
- <<Stent diameter ≤2.5 mm with severe blooming precluding lumen visualisation.>>
- <<Mean coronary attenuation <200 HU with marked noise.>>

## CT-FFR and advanced analysis

- <<CT-FFR is unreliable/contraindicated if mean coronary attenuation is <250–300 HU or there is severe motion/blooming.>>
- <<Consider CT-FFR for indeterminate or 50–69% stenoses where image quality is adequate and vessel diameter ≥2.0–2.5 mm; ≤0.80 indicates functional significance.>>

## Escalation decisions

- <<Left main ≥50% or multi-vessel severe disease: discuss invasive coronary angiography.>>
- Non-diagnostic prox LAD/LM/RCA: recommend alternative testing or ICA based on pre-test probability and symptoms.
- High-risk plaque (V) with non-severe stenosis: consider functional testing or CT-FFR; intensify preventive therapy regardless.
- Suspected >50% in-stent restenosis or non-diagnostic stent: recommend ICA.

## Bypass grafts

- Reconstruct with larger FOV to include full graft course and anastomoses.
- CPR each graft; 3–5 mm MIPs for overview.
- Assess patency, anastomoses, native run-off, and competitive flow.
- Vein graft disease is often diffuse — even moderate (50–69%) may be clinically relevant; correlate with stress imaging.

{% endtab %}
{% endtabs %}

## Key Take-Aways

- Always reconstruct both diastolic (70–80%) and systolic (35–45%) phases when heart rate is not low and regular.
- Diagnose stenosis on thin MPRs with orthogonal cross-sections; CPRs for navigation, MIPs for overview only — never grade stenosis on MIP alone.
- <<Apply CAD-RADS 2.0 thresholds consistently: 50–69% moderate (3), 70–99% severe (4A), left main ≥50% or 3-vessel obstructive (4B), 100% occluded (5).>>
- Report high-risk plaque using explicit thresholds: <<LAP <30 HU, remodelling index >1.1, spotty calcification <3 mm with arc <90°.>>
- Use sharper kernels, tighter FOV, 1024 matrix, and 80–90 keV monoenergetic imaging to mitigate blooming in calcified disease and stents.
- Declare non-diagnostic segments explicitly with the N modifier and recommend alternative testing — do not over-interpret compromised data.