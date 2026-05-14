---
title: "Scanning Principles and ECG Gating"
nav_order: 3
description: "Practical principles for CTCA acquisition, ECG gating mode selection, contrast timing, and dose optimisation."
---

CTCA image quality depends on tight motion control and accurate ECG synchronisation. This chapter outlines a practical, step-by-step approach to heart rate optimisation, gating mode selection, phase choice, and contrast delivery so that scans are consistently diagnostic at the lowest achievable dose.

{% tabs chapter-3 %}
{% tab chapter-3 Pre-Scan Setup %}

## Indications and gating choice

- Stable chest pain / suspected CAD with low, regular HR → **prospective ECG-gated** acquisition (lowest dose).
- High or variable HR, frequent ectopy, AF → **retrospective gating** with arrhythmia rejection, or rate/rhythm optimisation then rescan.
- Functional assessment (EF, volumes), valves, complex congenital cases → **retrospective helical** acquisition.

## Pre-scan checklist

- Clarify indication and clinical question.
- Check allergies, contrast risk, renal function (<<discuss case-by-case if eGFR <30 mL/min/1.73 m²>>).
- IV access: <<18–20 G cannula in the right antecubital vein>> (reduces SVC streak).
- Baseline rhythm strip over 2–3 minutes; confirm regularity.
- Rehearse a <<gentle end-inspiratory breath-hold of 10–12 seconds>> (avoid deep inspiration — increases HR and reduces coronary attenuation).
- ECG lead placement optimised; large clean R-waves; minimal baseline wander.

## ECG lead placement

- Skin prep: shave, clean with alcohol, gently abrade to reduce impedance.
- Lead positions away from heart shadow and breast tissue:
  - RA — right upper chest below clavicle
  - LA — left lower lateral chest
  - LL — right lower costal margin/abdomen
- Secure cables off the bore to reduce noise.
- Confirm dominant R-wave with no T-wave oversensing and stable R–R intervals (<<variability ≤5 bpm preferred for prospective gating>>).

## Heart rate and rhythm targets

| HR / rhythm | Strategy |
|---|---|
| <<≤60 bpm and regular>> | Prospective diastolic or high-pitch spiral |
| 61–70 bpm regular | Prospective diastolic with wider padding |
| 70–80 bpm | Prospective systolic window or retrospective |
| <<>80–85 bpm or irregular>> | Retrospective with arrhythmia rejection, or defer |

## Rate control medications

- **Beta-blockers (first line):**
  - Oral metoprolol <<50–100 mg PO 1–2 h pre-scan>>
  - IV metoprolol <<5 mg over 1–2 min, repeat every 3–5 min to a maximum of 15–20 mg>>
  - IV esmolol 500 µg/kg bolus, then 50–200 µg/kg/min infusion
- **Contraindications to beta-blockade:** <<SBP <100 mmHg, HR <55 bpm, 2nd/3rd degree AV block, acute decompensated heart failure, severe bronchospasm, suspected cocaine use>>.
- **Ivabradine** 5–7.5 mg PO 2–3 h pre-scan — sinus rhythm only; avoid in AF or AV block.
- **Diltiazem** 0.25 mg/kg IV with caution (hypotension risk).

## Nitrates

- <<Sublingual GTN 400–800 micrograms (1–2 puffs) given 2–3 minutes before acquisition>>.
- Requires <<SBP ≥100 mmHg>>.
- **Contraindications:** <<severe aortic stenosis, hypotension, PDE5 inhibitor use within 24 h (sildenafil/vardenafil) or 48 h (tadalafil)>>; relative caution in HOCM.

{% endtab %}
{% tab chapter-3 Gating Modes %}

## Acquisition modes

### 1. Prospective ECG-triggered sequential (step-and-shoot)

- Tube on only during preselected RR phase(s); minimal dose.
- Best when <<HR ≤65 bpm and regular>>.
- Vulnerable to ectopy and HR variability.
- Typical effective dose: <<~1–3 mSv>>.

### 2. Prospective high-pitch spiral (dual-source "flash")

- Whole heart in ~250–400 ms during a single beat with <<pitch >3>>.
- Requires <<HR ≤60 bpm and very regular>>.
- Typical effective dose: <<often <1 mSv>>.
- Dual-source scanner only.

### 3. Retrospective ECG-gated helical

- Continuous helical scan; reconstructions across multiple phases.
- Robust to high or variable HR; allows functional analysis.
- Higher dose — **always use ECG-based tube current modulation**.
- Typical effective dose: <<~5–12 mSv with modulation (up to ~15 mSv on legacy systems)>>.

## Selection algorithm

- HR ≤60, regular → prospective diastolic ± narrow padding, or high-pitch spiral.
- HR 61–70, regular → prospective diastolic with wider padding; consider systolic backup.
- HR 71–80 or mild variability → prospective systolic window or retrospective with modulation.
- HR >80 or AF/frequent PVCs → retrospective with arrhythmia rejection, or defer after rate/rhythm control.

## Phase selection

- **Mid-diastole (70–80% RR, centre ~75%)** — most quiescent at low HR.
- **End-systole (35–45% RR, centre ~40%)** — fewer artefacts at higher HR, especially RCA.

| HR | Primary phase | Secondary recon |
|---|---|---|
| <60 | <<75% (70–80%)>> | — |
| 60–70 | 65–80% | Consider 35–45% for RCA |
| 70–80 | <<35–45%>> | 30–50% if dose allows |

## Padding

- Narrow (±5%) if HR very stable.
- Wider (60–80% or 30–50%) to allow phase selection when HR fluctuates.
- More padding = more dose — balance against likely benefit.

## Arrhythmia handling

- Enable arrhythmia rejection algorithms (typically reject beats >10% off the rolling RR average).
- For bigeminy/trigeminy, prospective acquisitions are often non-diagnostic — prefer retrospective or defer.

{% endtab %}
{% tab chapter-3 Contrast and Technique %}

## Contrast delivery

**Goals:** homogeneous coronary opacification with <<target attenuation ≥300 HU (ideally 350–450 HU) in the ascending aorta/left main>> and minimal venous contamination.

**Parameters:**

- Contrast concentration: <<350–400 mgI/mL>>
- Flow rate: <<5–7 mL/s>>
- Iodine delivery rate: <<~1400–1800 mgI/s>> (e.g., 350 mgI/mL × 5 mL/s = 1750 mgI/s)
- Volume: <<0.7–1.0 mL/kg>> (typical 55–90 mL), adjusted to scan duration and kVp
- Saline chaser: <<30–50 mL at the same flow>>

**Lower kVp** (70–100) needs less iodine for equivalent attenuation; obese patients may require greater volume or 120 kVp.

## Bolus timing

- **Bolus tracking (default):** ROI in ascending aorta, <<trigger threshold 100–120 HU, post-trigger delay 4–6 s>>.
- **Test bolus:** 10–20 mL contrast + 30 mL saline; measure TTP in ascending aorta; tailor main delay.

## Scan range

- Topogram from carina to just below cardiac apex.
- Include 1–2 cm above the left main origin to capture the coronary ostia.
- Bypass grafts: extend cranially to subclavian/innominate origins and caudally to distal anastomoses.

## Tube and reconstruction settings

**kVp by body habitus:**

- BMI <22–24: 70–80 kVp
- BMI 22–30: 100 kVp (most common)
- Large/obese, heavy calcification, stents: 120 kVp (occasionally 140)

**Reconstruction:**

- Slice thickness <<0.5–0.75 mm>>; increment 0.3–0.5 mm (~50% overlap)
- Small cardiac FOV <<~180–220 mm>> centred on the heart
- Medium–soft cardiac kernel
- Iterative reconstruction / DLR on (especially at low kVp)
- Curved MPRs along vessel centrelines; orthogonal sections for stenosis quantification

## Dose management

- Prefer prospective gating where feasible.
- Use lowest kVp appropriate to habitus.
- Minimise padding consistent with diagnostic aims.
- Always enable ECG-based tube current modulation in retrospective scans.
- <<Cardiac effective dose (mSv) ≈ DLP (mGy·cm) × 0.026>>.

## At-the-scanner workflow

1. Confirm indication, consent, allergies, renal function; place IV.
2. Baseline rhythm/vitals; plan HR control.
3. Optimise ECG leads; check signal.
4. Give beta-blocker/ivabradine; reassess HR.
5. Rehearse 10–12 s breath-hold.
6. Give SL GTN if SBP ≥100 mmHg; wait 2–3 minutes.
7. Topogram and scan range.
8. Select gating mode and phase window.
9. Set contrast protocol; bolus tracking 100–120 HU AAo, 4–6 s delay.
10. Coach: "breathe in normally, hold still, no swallowing or talking."
11. Acquire; monitor ECG for ectopy.
12. QA axial slab; reconstruct additional phases if motion (30–50% and 70–80% in 2–5% steps).
13. Generate cMPRs (LAD, LCx, RCA).
14. Record DLP and contrast volume; monitor patient for drug effects.

{% endtab %}
{% tab chapter-3 Pitfalls and Pearls %}

## Common pitfalls

- **Deep inspiration** increases HR and reduces coronary enhancement → coach a *gentle* end-inspiratory hold.
- **Poor ECG signal** causes mis-triggering → meticulous skin prep, lead placement, and cable management.
- **Too-narrow padding** at borderline HR → widen padding or switch gating mode rather than accept a non-diagnostic study.
- **Under-dosed contrast** (<250 HU) → ensure ≥5 mL/s, large-bore cannula, adequate saline chaser, lower kVp if appropriate.
- **Incomplete coverage of ostia** → always include 1–2 cm above left main origin on planning.
- **Ignoring the systolic window at higher HR** → at HR ≥70 bpm always reconstruct 35–45% for the RCA.
- **Prospective gating in AF** → poor diagnostic yield; use retrospective with arrhythmia rejection or defer.
- **Failing to wait after GTN** → allow <<2–3 minutes for maximal coronary vasodilation>>.
- **Excessive dose in retrospective scans** → always enable ECG-based tube current modulation; tailor kVp.

## Escalation triggers

- HR persistently >75–80 bpm or irregular despite safe medication.
- Contraindications to both beta-blockers and ivabradine with CTCA still indicated.
- <<SBP <100 mmHg or severe aortic stenosis where GTN is unsafe>>.
- Frequent ectopy or AF where prospective yield will be poor.
- Contrast allergy without adequate premedication, or borderline renal function.
- Patient unable to breath-hold and high-pitch spiral unavailable.

## Pearls

- Right antecubital cannulation minimises SVC streak across the RCA origin.
- For RCA motion at higher HR, recon end-systole (35–45%) before declaring the study non-diagnostic.
- Reconstruct multiple phases in 2–5% steps if any motion is detected on the first review — cheap insurance against a repeat.
- Volume of contrast scales with scan time: Volume ≈ IDR × scan time ÷ concentration.
- Beware PDE5 inhibitor use before giving GTN — directly ask, do not assume.

## Quick-reference numbers

- HR targets: ≤60 ideal; ≤65 acceptable diastolic; 70–80 use systole; >80/irregular → retrospective or defer.
- Phase centres: diastole 75% (70–80%); systole 40% (35–45%).
- Contrast: 350–400 mgI/mL at 5–7 mL/s; 0.7–1.0 mL/kg; saline chaser 30–50 mL; trigger 100–120 HU AAo, 4–6 s delay.
- Recon: 0.5–0.75 mm slices, 0.3–0.5 mm increment, cardiac FOV 180–220 mm, iterative recon on.
- Dose: prospective 1–3 mSv; high-pitch <1 mSv; retrospective 5–12 mSv; mSv ≈ DLP × 0.026.

{% endtab %}
{% endtabs %}

## Key Take-Aways

- A **regular heart rate of <<≤60 bpm>>** is the single most important determinant of diagnostic CTCA — invest time in rate control and rhythm assessment before acquisition.
- **Prospective gating** is the default for low, regular HR and delivers <<~1–3 mSv (or <1 mSv with high-pitch spiral)>>; reserve retrospective gating for high/variable HR or functional assessment.
- Reconstruct **mid-diastole (75%) at low HR** and **end-systole (~40%) at HR ≥70 bpm**, particularly for the RCA; recon multiple phases when in doubt.
- Aim for **coronary enhancement ≥300 HU** with 350–400 mgI/mL contrast at 5–7 mL/s, bolus-tracked at <<100–120 HU in the ascending aorta with a 4–6 s delay>>.
- Always check **GTN contraindications** (hypotension, severe AS, recent PDE5 inhibitor) and **beta-blocker contraindications** (severe asthma, AV block, decompensated HF) before administering.
- Enable **ECG-based tube current modulation** and **iterative reconstruction**, and use the **smallest kVp** appropriate to body habitus to minimise dose without sacrificing diagnostic quality.