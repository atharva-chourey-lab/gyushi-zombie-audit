# Sources Map — Gyushi 75% Zombie Audit (30-chapter pilot, registered negative)

Author: Atharva Chourey
Affiliation: Atharva Chourey Lab (independent research lab)

*Registered report — negative result. Not yet peer-reviewed.*

This file maps every key number, verdict and reference in `paper.md` to the source file it was taken from. Nothing in the paper was taken from a source outside this list. The correspondence percentages in the paper's §6 are the **unclaimed arithmetic of the two coding passes**, reproduced from the pilot record and labelled unclaimed there and here; they are not findings.

## Primary sources

- `~/workspace/gyushi-zombie-audit/PREREGISTRATION.md` — frozen in git (commit `ebe2713`) before the coding dossier was used and before either coding pass began: the claim under test, the Citation Tracer's ZOMBIE verdict, prior-art bounds (Yang Ga 2010; Garang et al. 2025), the fixed 30-chapter sample, the two arms, the frozen 3-point codebook, the registered predictions, and the §7 kill gate (Cohen's κ ≥ 0.70) with its no-lowering / no-swapping clause.
- `~/workspace/gyushi-zombie-audit/PILOT_RESULTS.md` — the pilot record: gate verdict, reliability table, disagreement analysis, the unclaimed arithmetic (§3 of that file), the full per-chapter coding table (§4), and the "full audit not warranted on this design" assessment (§5).
- `~/workspace/gyushi-zombie-audit/coding/passA.csv` and `coding/passB.csv` — the two blind, independent coding passes (primary record; per-chapter labels + justifications for both arms).
- `~/workspace/gyushi-zombie-audit/reference/CHAPTER_DOSSIER.md` — the frozen dossier both coders worked from (chapter list with topic glosses; comparator outlines).
- `~/workspace/research-tools/campaigns/CAMPAIGN-TRACE-1-RESULTS.md` — Citation Tracer TRACE-1: the "~75%" claim's ZOMBIE verdict (no method, codebook or dataset in the indexed literature).

## Text access

Chapter index from the public-domain BDRC text (MW30134) / Men-Tsee-Khang titles via the open Rangjung Yeshe Wiki chapter index, per the preregistration and pilot record. Legal sources only; no pirate or shadow-library source was used.

## Key numbers and their sources

| Claim in paper | Value | Source |
|---|---|---|
| Reliability gate (pre-registered) | Cohen's κ ≥ 0.70 for the test arm | PREREGISTRATION.md §7 |
| Test-arm κ | **0.6795** (Po 0.833, Pe 0.480) — gate FAILS | PILOT_RESULTS.md §1 |
| Sham-arm κ | 0.7053 (Po 0.833, Pe 0.434) — gate would have passed | PILOT_RESULTS.md §1 |
| Disagreements | 10 total (5 per arm), all one-step (2↔1 / 1↔0), zero 2↔0 | PILOT_RESULTS.md §1, §4 |
| Sample | First 30 Explanatory Tantra chapters, canonical order | PREREGISTRATION.md §3 |
| Correspondence percentages | **None claimed** — predictions P1/P2 not scored, per the gate | PILOT_RESULTS.md, gate verdict |
| Unclaimed consensus arithmetic (record only) | AH-any 90.0%; AH-strong 56.7%; HNJ-any 66.7%; sham-corrected 23.3 pp (any) / 46.7 pp (strong) | PILOT_RESULTS.md §3 |
| Zombie claim status | "~75%" untraceable in the indexed literature; no method behind it | PREREGISTRATION.md §1; TRACE-1 results |
