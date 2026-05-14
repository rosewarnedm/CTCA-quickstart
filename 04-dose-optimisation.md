---
title: "Radiation Dose Optimisation"
nav_order: 4
description: "Practical strategies for minimising radiation dose during CTCA while maintaining diagnostic image quality."
---

CT coronary angiography uses ionising radiation, and stochastic cancer risk rises with dose — particularly in younger patients and women. Optimisation is both a legal duty under IR(ME)R and a daily practical skill. The biggest dose savings come from careful pre-scan preparation: a slow, regular heart rate enables prospective gating and narrow phase windows, which dwarf any individual scanner setting.

{% tabs chapter-4 %}
{% tab chapter-4 Dose Basics %}

## Why it matters

- CTCA delivers ionising radiation; stochastic risk is higher in young patients and women (breast dose).
- ALARP is mandatory under IR(ME)R: lowest dose reasonably achievable while preserving diagnostic quality.
- Pre-scan rhythm and breathing control save more dose than any scanner setting.

## Typical effective doses (optimised adult protocols)

| Acquisition mode | Effective dose |
|---|---|
| High-pitch spiral (dual-source) | ~0.5–1.5 mSv |
| Wide-detector single-beat volume | ~0.5–2 mSv |
| Prospective axial (step-and-shoot) | ~1–4 mSv |
| Retrospective helical with ECG modulation | ~5–12 mSv |
| Retrospective helical without modulation | ~12–20+ mSv (avoid) |

## Dose metrics

- **CTDIvol (mGy)**: scanner output per slice; for protocol comparison.
- **DLP (mGy·cm)** = CTDIvol × scan length.
- **Effective dose (mSv)** ≈ DLP × k. For ECG-gated cardiac CT, <<use k ≈ 0.026 mSv·mGy⁻¹·cm⁻¹ (adult)>>. Example: DLP 250 mGy·cm ≈ 6.5 mSv.
- **SSDE**: size-specific dose estimate, based on water-equivalent diameter; better reflects true patient dose.

## Audit

- Benchmark against local and national **Diagnostic Reference Levels** (75th percentile of practice).
- Document CTDIvol, DLP, kVp, mA/mAs, gating mode, padding, and scan length for every study.

## Special populations

- <<Pregnancy is generally a contraindication to CTCA; proceed only after MDT/MPE review with informed consent if life-threatening maternal indication.>>
- Very high BMI: consider alternatives if diagnostic quality requires excessive dose.
- Extra scrutiny in patients <40 and women of childbearing potential; avoid calcium scoring unless it will change management.

{% endtab %}
{% tab chapter-4 The Dose Levers %}

## 1. Heart rate and rhythm (the biggest lever)

- <<Prospective axial or high-pitch acquisition requires a regular HR <60 bpm (ideally ≤55 bpm).>>
- Retrospective helical: feasible up to ~75–80 bpm but dose rises with wider windows.

**Rate control regimens:**
- Oral metoprolol 50–100 mg, 1 hour pre-scan.
- IV metoprolol 5 mg slow bolus, repeat every 2–3 min to <<maximum 15–20 mg>>.
- IV esmolol 0.5 mg/kg bolus then infusion if needed.
- Sublingual GTN 400–800 µg immediately pre-scan after HR stabilised (unless contraindicated).

## 2. Acquisition mode

| Clinical scenario | Preferred mode |
|---|---|
| Regular, HR ≤60 | Prospective axial or high-pitch spiral |
| Regular, HR 60–65 | Prospective axial with narrow padding |
| Variable HR, ectopy, or multiphase needed | Retrospective helical with ECG mA modulation |

- Prospective trigger: 70–75% R-R (diastole) or 35–45% R-R (systole) if diastole unstable; padding ±5–10%.
- High-pitch: pitch ~2.5–3.4, single heartbeat coverage.
- Retrospective: <<reduce off-window mA to 20–30% of peak>>; keep full-mA window as narrow as clinically acceptable.

## 3. Tube potential (kVp)

Lower kVp reduces dose ~quadratically and boosts iodine attenuation.

| Patient size | Suggested kVp |
|---|---|
| <60 kg or BMI <22 | <<70–80 kVp>> |
| 60–90 kg or BMI 22–30 | <<90–100 kVp>> |
| >90 kg or BMI >30 | 100–120 kVp |

- 140 kVp is rarely indicated.

## 4. Tube current (mA)

- Use AEC with a CTCA-tuned noise/quality reference.
- Retrospective: enable ECG-based modulation, off-window minimum 20–30%.

## 5. Scan length and centring

- Cover from just above the coronary ostia to just below the apex (often 120–140 mm).
- <<Off-centring from isocentre can increase dose by >40% due to mis-calibrated AEC.>>
- Arms up where possible.

## 6. Other levers

- Iterative or deep-learning reconstruction at medium–high strength permits lower kVp/mA.
- Bolus tracking with **low-dose** monitoring series (10–20 mA), not high-dose test bolus.
- <<Calcium scoring must be performed at 120 kVp for standardised Agatston scoring>>; only add it if it will change management.
- Multi-beat volume scans: 2-beat ≈ 2× dose of 1-beat; 3-beat ≈ 3×.

{% endtab %}
{% tab chapter-4 Workflow %}

## Step-by-step low-dose CTCA

**1. Pre-scan assessment**
- Confirm indication and exclude pregnancy where relevant.
- Record baseline HR, rhythm, BMI; plan kVp.
- Secure IV access (18–20G antecubital).

**2. Rate and rhythm optimisation**
- Withhold caffeine; quiet rest.
- Beta-blockade to <<target HR <60 bpm (ideal ≤55)>>.
- Sublingual GTN once HR stable and immediately pre-scan (unless contraindicated).

**3. Set-up**
- Arms up; ECG leads outside cardiac FOV if possible.
- Centre precisely at isocentre.
- Plan minimal z-axis on the topogram.

**4. Protocol selection**
- HR ≤60 regular → prospective axial or high-pitch; phase window 70–78%.
- HR 60–65 regular → prospective axial with ±5–10% padding.
- Irregular / multiphase → retrospective helical with aggressive mA modulation.

**5. Exposure settings**
- Lowest reasonable kVp for size (often 80–100 kVp).
- AEC enabled; off-window mA 20–30% for retrospective.
- Shortest acceptable rotation time.

**6. Contrast timing**
- Bolus tracking, ROI in ascending aorta.
- <<Trigger threshold typically 100–150 HU>> (adjust to local standard).

**7. Acquisition**
- Rehearse breath-hold; comfortable end-inspiration without Valsalva.
- Avoid deep inspiration spikes in HR.

**8. Reconstruction**
- Iterative/AI reconstruction; smooth–medium cardiac kernel.
- Diastolic phase first; add systolic only for segments with diastolic motion.

**9. Document**
- HR, rhythm, mode, kVp, mA/mAs, CTDIvol, DLP, window/padding, scan length. Compare to DRL.

## Worked examples

- **A:** Prospective axial, HR 54, 90 kVp, DLP 150 mGy·cm → ~3.9 mSv. Acceptable; consider trimming length.
- **B:** Retrospective helical, HR 72, 100 kVp, DLP 400 mGy·cm → ~10.4 mSv. Was retrospective essential? Narrow the full-mA window.
- **C:** High-pitch spiral, HR 50, 80 kVp, DLP 80 mGy·cm → ~2.1 mSv. Benchmark of excellent optimisation.

{% endtab %}
{% tab chapter-4 Pitfalls and Pearls %}

## Common pitfalls

- **Reflexive retrospective scanning** — always attempt rate/rhythm control first.
- **Over-padding the phase window** — start narrow (±5–10%); widen only if needed.
- **Defaulting to 120 kVp** — most average adults can be scanned at 80–100 kVp with iterative/AI reconstruction.
- **Excessive scan length** — overshoot into lung bases and upper abdomen adds dose with no diagnostic gain.
- **Poor centring or arms-down** — both increase dose and degrade quality.
- **Repeat scans for breath-hold/bolus errors** — rehearse breath-hold; use low-dose monitoring; if repeat needed, target a limited z-range.
- **Bismuth breast shields** — generally discouraged due to artefact; optimise by centring, collimation, and protocol instead.
- **Forgetting ECG modulation on retrospective scans** — confirm enabled with appropriate minimum mA.
- **Calcium scoring by default** — skip if it won't change management.

## Pearls

- Three actions deliver most dose savings: **slow regular HR, prospective/high-pitch mode, narrow phase windows**.
- Lower kVp with iterative reconstruction is your default friend in average-sized adults.
- Keep z-axis short and patient centred — simple but high-yield.
- Functional assessment? Confine full-mA to 30–80% R-R rather than 0–90%, or consider CMR.

## Escalation triggers

- <<Individual case DLP >2× local DRL without clear clinical justification — discuss with consultant and Medical Physics Expert.>>
- Monthly median DLP for routine prospective CTCA consistently exceeds local DRL — initiate protocol review.
- High proportion defaulting to retrospective helical — review HR control processes.
- Repeated non-diagnostic studies — service improvement (coaching, training, protocol tweaks).

## Pre-scan checklist

- [ ] Indication justified; pregnancy excluded where relevant.
- [ ] HR <60 bpm and regular.
- [ ] GTN given (after HR control; not contraindicated).
- [ ] Patient centred, arms up, breath-hold rehearsed.
- [ ] Lowest feasible acquisition mode chosen.
- [ ] kVp minimised for size; AEC and ECG modulation set.
- [ ] Scan range tight; phase window narrow.
- [ ] Low-dose bolus tracking configured.
- [ ] Only necessary reconstruction phases planned.
- [ ] Dose metrics recorded and benchmarked against DRL.

{% endtab %}
{% endtabs %}

## Key Take-Aways

- The three biggest dose levers are a **slow regular heart rate (<<<60 bpm>>)**, **prospective or high-pitch acquisition**, and a **narrow phase window**.
- Effective dose for cardiac CT ≈ <<DLP × 0.026 mSv·mGy⁻¹·cm⁻¹>>; record CTDIvol and DLP for every study and benchmark against local DRLs.
- Match kVp to patient size: <<70–80 kVp for small, 90–100 kVp for average, 100–120 kVp for large adults>>; combine with iterative/AI reconstruction.
- Use retrospective helical only when truly necessary, and always with <<ECG-based mA modulation reducing off-window current to 20–30% of peak>>.
- <<CTCA is generally contraindicated in pregnancy>> — proceed only after formal MPE review and informed consent if life-saving information is essential.
- Avoid avoidable repeats: rehearse breath-hold, use low-dose bolus tracking, centre at isocentre, and keep scan length tight.