---
title: "Pitfalls and Artefacts"
nav_order: 12
description: "Recognising, preventing, and managing the common pitfalls and artefacts that compromise CTCA interpretation."
---

A clean, well-performed CT coronary angiogram can quickly answer the clinical question, but most "difficult" studies are difficult because of preventable pitfalls and correctable artefacts. This chapter focuses on what commonly goes wrong, how to recognise it, and how to fix or work around it. The goal is to give trainees practical thresholds and decision points for keeping studies diagnostic and reports safe.

{% tabs chapter-12 %}
{% tab chapter-12 Prevention %}

## Pre-scan Set-up and Patient Preparation

### Heart rate and rhythm control
- <<Target heart rate: <60 bpm is ideal; 60–65 bpm often adequate; >70 bpm increases motion artefact risk.>>
- Regular sinus rhythm is preferred; frequent ectopy or AF reduces diagnostic yield, especially with prospective ECG-triggering.
- β-blockade options:
  - Oral metoprolol 50–100 mg, 60–90 min before.
  - IV metoprolol 5 mg aliquots every 2–3 min up to 15–20 mg as tolerated; or esmolol 0.5 mg/kg bolus then infusion.
- <<Absolute contraindications to β-blockers: severe asthma/bronchospasm, decompensated heart failure, second- or third-degree AV block, severe hypotension, allergy.>>
- Alternative: diltiazem 0.25 mg/kg IV if β-blockers contraindicated; avoid with significant LV dysfunction or hypotension.

### Vasodilation
- <<Glyceryl trinitrate 400–800 micrograms sublingual 1–2 min pre-scan to improve luminal size.>>
- <<Nitrate contraindications: severe aortic stenosis, hypotension, recent PDE-5 inhibitors (sildenafil within 24 h, tadalafil within 48 h), HOCM with dynamic LVOT obstruction, allergy.>>

### Breath-hold coaching
- Use a gentle, end-expiratory breath-hold; avoid deep inspiration and Valsalva.
- Script: "Breathe in normally, breathe out, then a small breath in and hold very still."
- Aim for a stable 8–12 s hold; practise once before scanning.

### Vascular access and contrast
- <<Large-bore peripheral cannula 18–20G in the antecubital fossa; prefer right arm injection to reduce left brachiocephalic vein streak over aortic root and left main.>>
- Remove or avoid ipsilateral central lines where possible.
- Typical contrast: 50–70 mL iodinated contrast (≥350 mg I/mL) at 5–6 mL/s plus 30–50 mL saline chaser at 5–6 mL/s.
- <<Bolus tracking: ROI in ascending aorta; trigger threshold 120–150 HU above baseline; start scan after 3–5 s delay.>>
- <<Diagnostic luminal attenuation target: ≥250–300 HU in proximal coronaries.>>

### Pre-scan checklist
- HR <60–65 bpm and regular? If not, treat or change mode.
- Nitrates given and safe?
- Right arm 18–20G cannula; test injection smooth.
- Breath-hold rehearsed; end-expiratory.
- Protocol matched to patient (kVp/mAs/BMI; gating mode).

{% endtab %}
{% tab chapter-12 Acquisition Artefacts %}

## Acquisition-related Artefacts

### Cardiac motion
- Appearance: blurring or duplication of segments, "tram-track" edges, pseudo-stenosis, often at mid-distal RCA and mid LAD.
- Cause: HR too high or variable, suboptimal gating.
- Scanning mode selection:
  - <<Prospective step-and-shoot: regular HR ≤65 bpm with adequate padding (e.g., ±100–150 ms).>>
  - <<High-pitch spiral: HR ≤60 bpm with a very regular rhythm only.>>
  - Retrospective gating: irregular rhythms or high HR when diagnostic information essential (accept higher dose; use dose modulation).
- Troubleshooting:
  1. Reconstruct multiple phases at 2–5% R–R increments.
  2. <<Use diastolic phases (65–80%) for low HR; try systolic phases (35–45%) for high or variable HR.>>
  3. Apply motion-correction algorithms if available.
  4. If critical segments remain non-diagnostic, repeat with better rate control or switch to retrospective gating.

### Stair-step/banding
- Step-like misalignment at slab borders from HR variability in sequential scans.
- Fix: regular HR, adequate padding, overlapping slabs; avoid sequential mode with frequent ectopy.

### Respiratory motion
- Blurring or shifting diaphragm position between slabs.
- Fix: reinforce coaching; repeat if critical segments affected.

### Contrast timing pitfalls
- Low arterial enhancement (<250 HU): under-timing, low injection rate, extravasation, or Valsalva.
- Venous contamination:
  - Dense SVC (right arm) streaks the proximal RCA; dense left brachiocephalic vein (left arm) streaks aortic root and LM.
  - Saline chaser is mandatory; consider lower iodine load if streak is recurrent.
- Beam hardening from right-heart contrast pool: scanned too early; increase trigger threshold or small extra delay.

### Photon starvation (large habitus)
- Grainy images, shoulder streaks, reduced lumen contrast.
- <<kVp selection: BMI <25 use 100 kVp; BMI 25–30 use 100–120 kVp; BMI >30 use 120 kVp (scanner-specific; use automatic kV selection if available).>>
- Increase mAs, enable iterative reconstruction, narrow FOV to heart, arms elevated.
- If proximal segments remain non-diagnostic, escalate to alternative testing.

### Metallic/device artefact
- Sources: sternotomy wires, prosthetic valves, pacing leads, coronary stents.
- Mitigation: metal artefact reduction algorithm, thin slices (0.5–0.6 mm), sharp "stent" kernel, iterative reconstruction, precise axis alignment.
- <<In-stent assessment is often non-diagnostic if stent diameter ≤3.0 mm, with thick struts, or with overlapping stents — escalate to functional testing or invasive angiography if clinically important.>>

### Z-axis coverage
- Plan from above the carina to just below the cardiac apex; allow for large hearts.
- Missed distal RCA or high-origin LM: consider top-up acquisition only if clinically essential (dose trade-off).

{% endtab %}
{% tab chapter-12 Interpretation Pitfalls %}

## Reconstruction Choices

### Phase selection
- Low HR: start at 70–75% R–R; test 65–80%.
- High or variable HR: also try 35–45%.
- Use 2–5% increments when motion suspected.

### Slice, kernel, and display
- Slice thickness 0.5–0.75 mm; increment 0.3–0.5 mm.
- Medium "cardiac" kernel for general evaluation; sharper kernel for stents and dense calcium.
- <<Coronary window starting point: level 250 HU, width 850 HU (range level 200–300 HU, width 700–1,000 HU).>>
- Mediastinal windows (e.g., 40/350) under-represent plaque and lumen — avoid for coronary assessment.

### CPR and MPR pitfalls
- Off-centre tracking creates false eccentric stenosis or kinking.
- Always confirm any stenosis on **at least two orthogonal planes** (axial and short-axis cross-section).
- Thick MIPs across tortuous segments overestimate stenosis from partial volume; use thin MIPs (2–5 mm) only for overview.
- Multi-segment reconstruction artefact (ghosting) appears with HR variability — switch to single-segment or alternative phase.

## Interpretation Mimics

### Calcification and blooming
- Calcified plaque "blooms," overestimating stenosis.
- Mitigation: thin slices, sharper kernel, wider window; judge by residual contrast "napkin" rather than calcification diameter.
- Heavily calcified proximal segments that remain equivocal should be reported as non-diagnostic with onward recommendation.

### Stents
- Diagnostic evaluation limited for stents ≤3.0 mm, thick struts, or overlapped segments.
- Align along stent axis, use stent kernel, look for in-stent contrast thread.

### Normal variants mistaken for disease
- **Myocardial bridging**: intramyocardial mid-LAD with systolic pinching — assess in diastole; dynamic compression is not a fixed stenosis.
- High origin and acute take-off angles: confirm orthogonal.
- Small conus branch or diagonals: don't overcall tapering as stenosis.
- Pericardial recesses and epicardial fat may mimic soft plaque, but plaque sits within the vessel wall.

### High-risk plaque features (don't miss)
- <<Low-attenuation plaque <30 HU.>>
- <<Positive remodelling index >1.1.>>
- <<Spotty calcification <3 mm.>>
- Napkin-ring sign.
- These warrant reporting and intensified preventive therapy regardless of % stenosis.

### Segment labelling
- Use the SCCT 18-segment model and document dominance.
- Common errors: confusing a large ramus intermedius with LAD/LCx disease; mislabelling distal RCA versus posterolateral branches in left-dominant systems.

{% endtab %}
{% tab chapter-12 Non-diagnostic and Escalation %}

## Recognising Non-diagnostic Segments

### Image quality grading (per-segment or per-vessel)
- 1 — Excellent (no artefact)
- 2 — Good (minor artefact; fully diagnostic)
- 3 — Adequate (diagnostic but limited confidence)
- 4 — Non-diagnostic (cannot exclude ≥50% stenosis)

<<If any proximal or mid segment of a major epicardial vessel (LM, proximal LAD, proximal LCx, proximal RCA) is grade 4, declare it non-diagnostic and recommend a clear next step (functional testing or invasive angiography) based on pre-test probability.>>

### When to escalate
- HR >75 bpm with irregular rhythm despite optimisation: avoid prospective modes; consider retrospective gating or alternative testing.
- Heavily calcified or stented proximal segments precluding assessment: advise functional testing or invasive angiography.
- <<Uncertain left main ≥50% stenosis after all reconstructions: urgent cardiology discussion and consideration of invasive angiography.>>
- Persistent motion at all phases obscuring key segments: re-scan after further HR control if safe; otherwise alternative test.
- Very high BMI with photon starvation rendering proximal segments non-diagnostic: advise alternative test.
- <<Any suspected acute coronary syndrome scenario with a non-diagnostic CTCA: urgent escalation per local acute pathway.>>

## Reporting Safely with Artefacts

- Be explicit: "Assessment of [segment] is non-diagnostic due to [motion/calcification/stent/beam hardening]."
- Avoid precise stenosis percentages when artefact precludes accurate measurement; use ranges.
- <<Use CAD-RADS 0–5 with the N (non-diagnostic) modifier when applicable — e.g., "CAD-RADS N: Non-diagnostic LM due to blooming calcification; invasive angiography recommended.">>
- Document heart rate, rhythm, reconstruction phase used, and key technical limitations to inform future scans.

## Quick Reference: Artefact Clues and Fixes

| Artefact | Visual clue | Fix |
|---|---|---|
| Motion blur | Segment "travels" between phases | Reconstruct 65–80% and 35–45%; increase padding; retrospective re-scan if critical |
| Stair-step | Abrupt level shift at slab junctions | Overlapping reconstructions; avoid sequential mode in irregular HR |
| Streak over LM/RCA | Ray-like dark/bright streaks from dense vein | Right arm injection; saline chaser; adjust timing |
| Low enhancement | Coronary lumen grey, <250 HU | Verify cannula; increase rate; re-trigger; avoid Valsalva |
| Calcium blooming | Plaque larger than expected, "cotton-wool" edges | Thin slices, sharper kernel, wider window; orthogonal MPR |
| Stent non-diagnostic | Only struts visible, no contrast thread | Stent kernel, thin slices, exact axis; escalate if ≤3.0 mm or overlapped |

{% endtab %}
{% endtabs %}

## Key Take-Aways

- Most CTCA failures are preventable at the set-up stage — <<HR <60–65 bpm, regular rhythm, right arm 18–20G cannula, sublingual GTN, and rehearsed end-expiratory breath-hold>> deliver the biggest gains.
- Always reconstruct multiple phases (diastolic 65–80% and systolic 35–45%) before declaring motion artefact non-correctable, and confirm any stenosis on at least two orthogonal planes.
- Heavily calcified plaque and stents ≤3.0 mm are inherently limited — mitigate with thin slices, sharper kernels, and wider windows, but escalate honestly when the proximal LM or major vessel remains equivocal.
- Don't anchor on % stenosis alone — record high-risk plaque features (LAP <30 HU, remodelling index >1.1, spotty calcium <3 mm, napkin-ring sign) as they alter prognosis and management.
- Use the CAD-RADS N modifier and a clear escalation pathway (functional testing or invasive angiography) for every non-diagnostic critical segment.
- An acute coronary syndrome presentation with a non-diagnostic CTCA always warrants urgent clinical escalation, not a softened report.