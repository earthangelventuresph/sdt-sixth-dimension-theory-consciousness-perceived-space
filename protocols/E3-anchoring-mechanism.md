# E3 — Mechanism of Anchoring, Visibility and Presence

> **Status: PROTOCOL ONLY. No data collected. No results claimed. Ethics NOT YET APPROVED.**
> Project: EAV-SDT-001 | Manuscript: EAV-SDT-001-M01 | Version 1.0 | 27 October 2026
> Earth Angel Ventures Research Standard: "The standard is not how extraordinary a claim sounds, but how reliably the evidence supports it and how well others can examine, challenge, reproduce, and build upon the work."
> Verse: 1 Corinthians 10:31 | Philippians 2:13

## Claim in Plain Language
Anchoring explains the Cloud-Visibility Rule. More visible cloud → more anchoring → lower ceiling on G. It is visibility, not mere physical presence, that matters. And any matched visual texture anchors as much as cloud does.

## Formal Prediction
- **H4:** G falls with cloud fraction c (Eq. 12–13). Mean G at c = cV is below frozen G*.
- **H5:** Physically present but non-visible cloud (Cw = 0.01, below Cmin = 0.02) behaves like clear sky. Visible cloud (Cw = 0.10) suppresses G.
- **H6:** Phase-scrambled texture matched on amplitude spectrum, mean luminance and RMS contrast anchors equally to cloud.
- Model ceiling at c = 0: ~0.942. At c = cV: ~0.633. At c ≥ cV: below G*.

## Falsification Threshold — Decided in Advance
- **H4 rejected** if G does not fall with c, OR mean G at c = 0.003 has upper bound ≥ frozen G*.
- **H5 rejected** if 90% interval of (clear minus Cw = 0.01) difference is NOT inside ±0.10, OR upper bound of (Cw = 0.10 minus clear) difference is ≥ −0.20.
- **H6 rejected** if 90% interval of (scrambled minus cloud) G difference is NOT inside ±0.10.
- If H4 fails: rule may remain as description, mechanism rejected. If H5/H6 fail: generality / visibility claim rejected as stated.

## Design
- Within-participant, Latin-square, dome conditions:
    - Clear (c = 0)
    - Cloud fractions: sub-threshold, at cV = 0.003, above cV, high
    - Cw = 0.01 (present but non-visible) vs Cw = 0.10 (visible), matched c
    - Phase-scrambled texture matched to cloud (spectrum, luminance, RMS contrast)
    - Luminance-matched controls
- 1,280 trials across 40 participants (32 trials per participant).

## Apparatus / Materials
- Dome, camera, photometer, EEG / probes / PSQ-6 / MVIS-1 as in E1–E2.
- Stimulus set pre-generated, luminance-matched within 5%, Weber contrast 0.10 unless condition states otherwise.

## Step-by-Step Procedure
1. Screen, consent (after approval + registration), baseline, calibration.
2. For each trial: assigned stimulus → settle → MVIS-1 → state window → PSQ-6 + source test → rest.
3. Camera + photometer log c, Cw, V per trial. Automatic D scoring blind to V.
4. Repeat across Latin-square order.

## Sample Size + Power
- **N = 40 independent adults (18–65).** 1,280 trials.
- Equivalence tests (Eq. 21): 90% CI inside (−δ, +δ), δ = 0.10 for H5/H6 equivalence parts.
- Mixed-effects models (lme4-style) with participant random effects, condition fixed effects, VVIQ covariate.

## Blinding
- D blind to V; V blind to D; stimulus condition sealed in log until analysis.

## Frozen Analysis Plan
- H4: G vs c curve; test monotonic fall; mean G at c = cV vs frozen G*.
- H5: two equivalence / difference tests as in thresholds above.
- H6: equivalence test scrambled vs cloud.
- No threshold changes after data inspection.

## Confounds
- Contrast rather than cloud meaning (scrambled condition); spectral content (matched spectrum); luminance (matched); presence without visibility (Cw = 0.01); order (Latin square); fatigue; VVIQ.

## Data Availability
- No data exist. Future stimulus set, camera logs, analysis code deposited with registration.

## Ethics / Safety
- **Ethics NOT YET APPROVED. Do not begin.** Same as E1.
- Contact: earthangelventuresph@gmail.com | +63 991 967 6122
