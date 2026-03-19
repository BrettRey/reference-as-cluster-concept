# Decisions Log

Append-only record of project decisions. Agents: add an entry whenever a non-trivial decision is made during a session (structural changes, venue choices, theoretical commitments, scope changes, reviewer feedback acted on). Keep entries short.

Format: `## YYYY-MM-DD` then bullet points with **bold topic** and brief rationale.

---

## 2026-03-17

- **Author feedback received.** Dimitri Coelho Mollo responded to Brett's email (sent Mar 8) sharing the draft. Tone collegial, broadly sympathetic ("I quite like the part in which you differentiate the diverse mechanisms"). Three substantive corrections:
  1. **Causal-informational is part of teleosemantics**, not an independent component. Check whether the paper artificially separates what's unified in their framework.
  2. **Groundedness doesn't predict performance differences.** Dimitri says grounded vs. ungrounded LLMs don't show clear performance divergence. Reliability comes from world models (which can exist without grounding). Intrinsic meaning can exist without world models. This challenges the predictive/projectibility angle.
  3. **Thin notion of reference.** Their paper uses a deliberately thinner reference notion than linguistic reference — no communicative intents. Risk of straw-manning if our paper imports a thicker notion and critiques them for not meeting it.
- **Implication for timeline:** One revision session needed to address these three points before preprint posting or PhiMiSci submission. Corrections are pointed, not fundamental.

## 2026-03-17 to 2026-03-19 (extended session)

- **Thin/thick distinction adopted.** Thin grounding (CM&M's teleosemantic question) doesn't predict performance; the profile predicts the thicker package of robustness, corrigibility, and failure modes. New §3.5 added. Addresses Dimitri's point 2.
- **gcausal reframed as internal to teleosemantics** but tracked separately for predictive purposes (etiological/constitutive distinction justifies separation). Concrete worked case added (static vs retrieval/multimodal system). Addresses Dimitri's point 1.
- **gcomm framed as expanding scope**, not correcting CM&M. Title hedge added in introduction and conclusion. Addresses Dimitri's point 3.
- **Sycophancy reframed as conflict of targets**, not absence of target. Prediction market analogy rewritten with herding (Scharfstein & Stein 1990) replacing naive crowd-following, Hayek cited.
- **"Successor models" replaced with multi-channel inheritance.** Distillation, synthetic data, corpus contamination, RLHF preference data. Cultural transmission rather than biological reproduction. Strengthens Putnam connection.
- **Shallow-alignment evidence** (Qi et al. 2025, Arditi et al. 2024) scoped to safety routing; distinguished from truth-directed selection. Wang et al. 2025 activation-patching evidence cited for sycophancy mechanisms.
- **Magnus (2014) and Craver (2009)** engaged on HPC permissivity objection.
- **Model/system distinction** enforced throughout. Table column 3 relabelled "RLHF system." Footnote added.
- **Etiological/constitutive distinction** carried through all strands, octopus section, prediction market, and conclusion. ginfer's constitutive dominance now predicts its stability in Table 1.
- **Octopus section tightened.** Agentic/low-background-steel digression cut. Regime-sensitivity argument sharpened: which stabilisers → which capabilities.
- **Open taxonomy.** "At least four" in abstract, introduction, conclusion.
- **Oxford spelling** (-ize) adopted. Contractions added. En-dashes reduced to Bringhurst-approved.
- **Three rounds of internal review board** (R1: 4 R&R + 1 Accept → R2: 3 Accept + 1 R&R minor + 1 Conditional Accept → R3: 4 Accept minor + 1 Accept).

## 2026-03-19

- **PhilArchive posting completed.** Public preprint posted as `REYRAA-2`; project phase shifts from preprint housekeeping to submission prep.
- **Public metadata fixed at posting.** Current PhilArchive categories are `Computational Semantics`, `Representation in Connectionism`, and `Semantics, Misc`; keywords reflect the paper's VGP/teleosemantics/groundedness-profile framing.
