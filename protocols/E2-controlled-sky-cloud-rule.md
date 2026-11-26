# E2 — Controlled-Sky Test of the Cloud-Visibility Rule

> **Status: PROTOCOL ONLY. No data collected. No results claimed. Ethics NOT YET APPROVED.**
> Project: EAV-SDT-001 | Manuscript: EAV-SDT-001-M01 | Version 1.0 | 27 October 2026
> Earth Angel Ventures Research Standard: "The standard is not how extraordinary a claim sounds, but how reliably the evidence supports it and how well others can examine, challenge, reproduce, and build upon the work."
> Verse: 1 Corinthians 10:31 | Philippians 2:13

## Claim in Plain Language
When clouds are visible, the observer is not in the sixth-dimension state. In a controlled dome sky, no verified episode should combine visible cloud (V = 1) with the state (D = 1) beyond the pre-set tolerance.

## Formal Prediction
- Strong form: k = 0 verified counterexamples, where k = count of episodes with V = 1 and D = 1.
- Operational form: `P(D = 1 | V = 1) ≤ ε = 0.05`, tested by `pU = BetaQuantile(1 − α; k + 1, neff − k) ≤ 0.05`.
- Predicted P(D = 1 | V = 0) with MVIS-1: π0 = 0.40. Predicted P(D = 1 | V = 1): ~0.

## Falsification Threshold — Decided in Advance
- **Strong form falsified** by ONE verified counterexample (audited per Figure 11).
- **Operational form rejected** if pU > 0.05.
- If fewer than 59 effective V = 1 episodes achieved, Eq. 16 cannot reach 0.05 and operational form is rejected for E2.
- Power: designed to support rule with probability 0.76 if true violation rate = 0.02, and probability < 0.0001 if true violation rate = 0.10.

## Design
- Within-participant, Latin-square / randomised dome-sky conditions: clear sky, visible cloud at multiple fractions, sub-threshold cloud, controls.
- V measured by calibrated camera + blinded automatic pipeline. V constant from sky settle to end of state window (210 s) for H3 episodes.
- 720 trials across 60 participants (12 trials per participant).
- Also tests H2(a) (field/lab induction rate) and H7 (environmental independence).

## Apparatus / Materials
- Dome as in E1. Calibrated camera for V. Photometer for Lc, Ls, Cw. Environmental sensors: magnetic field, temperature, pressure, illuminance, acceleration.
- Same EEG / probe / PSQ-6 / MVIS-1 specification as E1.

## Step-by-Step Procedure
1. Screen, consent (after approval + registration), baseline, probe calibration.
2. For each trial: present assigned sky condition → sky settle → MVIS-1 → state window (probes + 16 events) → PSQ-6 + source test → rest.
3. Camera records sky continuously. Automatic pipeline scores V blind to D.
4. Audit every V = 1 + D = 1 episode: check camera frames, EEG quality, probe data, source-test log, gaze. Only verified counterexamples count as k.
5. Environmental sensors logged per episode for H7.

## Sample Size + Power
- **N = 60 independent adults (18–65).** 720 trials.
- Clustering: `DE = 1 + (m − 1)·ICC`; `neff = n / DE`. ICC = larger of estimate and 0.20 floor.
- nmin = 59 effective episodes when k = 0 (Eq. 17).

## Blinding
- D scored automatically, blind to V. V scored automatically, blind to D. Condition log sealed. Audit is pre-specified, not post-hoc selection.

## Frozen Analysis Plan
- Compute k, n, neff, pU per Eq. 16, 18.
- H2(a): induction rate in clear condition.
- H7: for each sensor j, `dj = (mj,1 − mj,0) / sj`; equivalence if 90% CI inside (−0.30, +0.30).
- No change to thresholds after seeing data.

## Confounds
- Luminance matched within 5%; contrast controlled; order (Latin square); sun/glare flagged; gaze away flagged; horizon landmarks counted in Λ0; weather not present in dome (reason for E4).
- Circularity excluded: D defined by R, U, B, Q only — no cloud measure.

## Data Availability
- No data exist. Future data + camera V logs + audit trail deposited with registration, subject to privacy limits.

## Ethics / Safety
- **Ethics NOT YET APPROVED. Do not begin.** Same screening, stop word, psychologist, distress rule as E1.
- Contact: earthangelventuresph@gmail.com | +63 991 967 6122
