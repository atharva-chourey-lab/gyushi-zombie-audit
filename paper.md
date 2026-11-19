# The 75% That Nobody Measured: A Pre-Registered Pilot Audit of the Gyushi–Ashtanga Claim Dies at Its Own Reliability Gate

Author: Atharva Chourey
Affiliation: Atharva Chourey Lab (independent research lab)

*Registered report — negative result. Not yet peer-reviewed.*

## Abstract

A widely repeated claim holds that "~75% of the Gyushi (rGyud bzhi, the Tibetan Four Tantras) comes from the Aṣṭāṅgahṛdayasaṃhitā" — the foundational Ayurvedic compendium of Vāgbhaṭa. The lab's Citation Tracer could find no source for that figure: no method, no codebook, no dataset stands behind it in the indexed literature. It is a zombie statistic. This paper reports a pre-registered attempt to replace it with a measurement — and reports that the attempt failed at its own gate, before any estimate was produced. A 30-chapter pilot (the Explanatory Tantra, the part of the Gyushi where Indian influence is most plausible a priori) was coded for chapter-topic correspondence against the Ashtanga Hridaya by two blind, independent coders, with the Huangdi Neijing coded identically as a sham arm to measure generic premodern-medical overlap. The pre-registration fixed a reliability gate: the coding would support a percentage only if Cohen's κ reached 0.70. It returned κ = 0.68 (raw agreement 83.3%; all disagreements one-step boundary disputes). Under the registration, the pilot therefore dies: **no correspondence percentage is claimed, the registered predictions were not scored, and the full-corpus audit does not proceed.** The zombie 75% remains untraced and unusable — and, after this pilot, still unreplaced. The paper publishes the full record, including the passes' arithmetic explicitly labelled as unclaimed, because a gate that only fires in private is not a gate.

*Keywords:* Gyushi; rGyud bzhi; Ashtanga Hridaya; Tibetan medicine; Ayurveda; zombie statistic; pre-registration; inter-rater reliability; registered report; negative result

## 1. The claim under test

The claim that roughly three-quarters of the Gyushi derives from the Ashtanga Hridaya circulates in the secondary literature on Tibetan medicine as a settled quantity. When the lab's Citation Tracer (TRACE-1) walked it back, it found no origin: no source in the indexed literature states a method, a codebook, or a dataset behind the 75% figure. The lab's 2026-11-17 comparative report on Indian, Tibetan and Chinese medicine likewise noted the figure appears in a conference abstract "without a verifiable method" and declined to use it.

Prior art bounds the seam. Yang Ga (Harvard PhD dissertation, 2010) compared the Gyushi and the Ashtanga Hridaya at chapter level *qualitatively* — no percentage, no published codebook, no open dataset. Garang et al. (*Frontiers in Pharmacology*, 2025) published a quantitative *materia medica* extraction (227 shared materials) — a materials overlap, not a chapter/topic correspondence for the whole work.

The surviving seam is therefore a sham-corrected measurement of chapter-topic correspondence. This pilot tests whether that measurement is *codable at all* — inter-rater reliability — and would have given a first, pilot-only estimate had its gate passed.

## 2. What this pilot is and is not

This is a pilot: 30 chapters, one tantra. Its numbers would have been pilot results only, never the full-corpus correspondence of the Gyushi (156 chapters). The sample is the Explanatory Tantra (bShad rgyud), the theoretical tantra — the part of the Gyushi where Indian influence is *a priori* most plausible (embryology, anatomy, physiology, pharmacology of tastes and potencies). The design is therefore biased *toward* finding Ashtanga correspondence: a low number there would have been conservative evidence against the zombie figure; a high number would not have generalised to the clinical Instructional Tantra, where Tibetan clinical elaboration dominates by construction.

## 3. Design (frozen before coding)

The preregistration was frozen in git (commit `ebe2713`) before the coding dossier was used and before either coding pass began.

- **Sample (fixed, no discretion):** the first 30 chapters of the Explanatory Tantra in canonical order (chapters 2.01–2.30 in the BDRC MW30134 chapter index; English titles from *Fundamentals of Tibetan Medicine*, Men-Tsee-Khang, 1995, as reproduced in the open Rangjung Yeshe Wiki chapter index). Chapter 2.31 is excluded solely by the 30-chapter cap set in scouting. No chapter could be substituted, dropped, or reordered after registration. Text access was legal throughout — public-domain / open reference material only; no pirate sources were needed or used.
- **Arms:** a test arm (does the Ashtanga Hridaya, 120 chapters in 6 sthānas, contain corresponding topic treatment for each Gyushi chapter?) and a sham arm (the identical coding with the Huangdi Neijing — Suwen 81 + Lingshu 81 chapters — substituted). The sham measures generic premodern-medical overlap: any two large premodern medical canons share regimen, dietetics, seasonal theory and pulse lore, so the zombie claim is only meaningful for correspondence *above* this floor.
- **Codebook (frozen):** for each chapter × arm, one label — 2 = a dedicated chapter/section in the comparator; 1 = substantive treatment, no dedicated chapter; 0 = none or passing mention. Coders used only the frozen dossier (chapter titles/glosses and comparator outlines) — the same information set for both coders and both arms, and no full-text consultation: this is a topic-correspondence code, matching the level at which the zombie claim is made and at which Yang Ga's comparison was conducted.
- **Execution:** two coding passes, blind and in parallel, by two separate coders; neither saw the other's labels. Consensus, where needed, was registered as the *lower* label on disagreement.
- **Predictions (registered, not scored — see §5):** P1, sham-corrected Ashtanga correspondence ("any", label ≥ 1) of 38–55%; P2, strong correspondence (label = 2) below 30%.
- **The gate (§7 of the registration):** the pilot supports a percentage only if Cohen's κ for the test arm reaches **0.70**. Below that, the pilot dies: no percentage is claimed, predictions are not scored, and the full audit does not proceed. The registration explicitly forbids lowering the gate, renegotiating it, or swapping in another statistic after the labels are seen.

## 4. Reliability results

| Arm | Raw agreement (Po) | Chance agreement (Pe) | Cohen's κ |
|---|---|---|---|
| Ashtanga Hridaya (test) | 0.833 (25/30) | 0.480 | **0.6795** |
| Huangdi Neijing (sham) | 0.833 (25/30) | 0.434 | 0.7053 |

All 10 disagreements (5 per arm) are **one-step boundary disputes** (2↔1 or 1↔0); there is not a single 2↔0 disagreement in either arm. The test-arm disagreements — the summary chapter (is a meta chapter codable at all), primordial causes, entry of diseases, curability assessment, general healing techniques — share one fault line: the codebook's 2/1 boundary, "a chapter devoted to the topic" versus "substantive treatment inside broader material", which several Ashtanga chapters straddle.

Why κ lands at 0.68 despite 83% agreement: the test-arm marginals are heavily skewed (both coders put ≥1 on 28 of 30 chapters), which inflates chance agreement (Pe = 0.48) and depresses κ. This is recorded as a design observation only — per the preregistration it does not reopen the gate. That the sham arm cleared 0.70 while the test arm missed it underlines that the failure sits in the test code's boundary cases, not in coder carelessness.

## 5. Gate verdict

**Cohen's κ for the Ashtanga Hridaya arm = 0.68 (0.6795), below the pre-registered kill gate of 0.70. The pilot dies as registered.** The gate was not lowered, renegotiated, or swapped for another statistic after the labels were seen — the preregistration forbids all three, and none was done. No correspondence percentage is claimed by this project, the registered predictions (P1, P2) were not scored, and the project stops at the pilot.

What the verdict does and does not mean:

- It does **not** vindicate the zombie 75% figure. That figure remains what the Citation Tracer found it to be: an untraceable statistic with no method behind it. This pilot simply failed to produce a *reliable replacement measurement* on its first attempt.
- It does **not** show the Gyushi–Ashtanga relationship is weak or strong. It shows a 3-point topic code, applied at chapter level from titles and glosses, does not yet clear the lab's reliability bar.

## 6. Unclaimed arithmetic (for the record — NOT findings, NOT to be quoted as results)

Computed exactly as registered (consensus = lower label on disagreement), but **invalid as estimates** because the gate fired. These numbers are published only because the lab publishes its negative results in full, and for the use of any future redesigned study:

| Quantity | Pass A | Pass B | Consensus |
|---|---|---|---|
| AH-any % (label ≥ 1) | 93.3% | 93.3% | 90.0% |
| AH-strong % (label = 2) | 66.7% | 56.7% | 56.7% |
| HNJ-any % (sham floor) | 76.7% | 66.7% | 66.7% |
| Sham-corrected (any) | — | — | 23.3 pp |
| Sham-corrected (strong) | — | — | 46.7 pp |

Two honest observations about this arithmetic, neither of which rescues the pilot:

1. The registered predictions (P1: AH-any 38–55%; P2: strong < 30%) would have **failed badly** had the gate passed — at chapter-*topic* level, the Explanatory Tantra's contents correspond to Ashtanga topics almost line for line. That is consistent with the sample's registered bias, and topic correspondence at title level is the weakest, most generous form of "comes from": it says nothing about textual derivation, which is what the zombie claim asserts and what a materials/verse-level study (cf. Garang et al. 2025) would be needed to measure.
2. The sham floor is very high (HNJ-any ≈ 67–77%): at topic level, even the Chinese canon "corresponds" to two-thirds of these chapters. That is exactly why the lab insisted on a sham arm — and it means any future uncorrected topic-level percentage, from anyone, is close to meaningless.

The full per-chapter coding table (both passes plus consensus for all 30 chapters, both arms) and the per-chapter justifications are in the project record (`PILOT_RESULTS.md` §4; `coding/passA.csv`, `coding/passB.csv`).

## 7. Is the full audit warranted?

**No — not on this design.** The full-corpus audit (156 chapters) must not proceed from this pilot: its instrument failed its own reliability gate, and scaling an unreliable code to 156 chapters would only manufacture a precise-looking zombie of our own — the exact failure this project exists to kill.

What a *future, newly pre-registered* attempt would need (recorded for the record; none of it is authorised or started by this paper):

1. A sharpened 2/1 boundary rule with worked examples for the straddling cases (treatment-principles chapters; meta/summary chapters — either exclude summary chapters by rule or define their coding explicitly).
2. A reliability statistic and gate chosen for skewed marginals, registered in advance — the choice must be made before labels exist, not after.
3. Serious consideration of dropping from chapter-topic level to a stricter unit (coded topic items within chapters, or verse/material-level sampling in the Garang et al. direction), since topic-level correspondence saturates: both the test and sham arms sit above 65%, leaving little discriminative room for any "comes from" claim.

**Pilot status: DEAD as registered (κ gate). Zombie claim status: still untraced, still unusable — and still unreplaced.**

## Sources

Every number in this paper is traced in [SOURCES.md](SOURCES.md) to the frozen preregistration (commit `ebe2713`), the pilot results record (`PILOT_RESULTS.md`), and the two blind coding passes (`coding/passA.csv`, `coding/passB.csv`) of the Gyushi zombie-audit project.
