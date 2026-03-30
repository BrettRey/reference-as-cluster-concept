# STATUS.md — Vector Grounding Problem Response

## Phase: Preprint posted

Major revision complete. Dimitri Coelho Mollo's feedback addressed. Three rounds of internal review board passed (all Accept/Accept minor). Housekeeping blockers were cleared and the paper is now live on PhilArchive: `https://philarchive.org/rec/REYRAA-2` (archival date `2026-03-19`). Geoff has the revised draft; Ryan comments are still optional input rather than a blocker. Remaining work is submission prep and any metadata cleanup, not preprint prep.

## What's Done

- Full paper: ~7,650 words body, 18 pages, 1 table
- Dimitri's three points addressed: thin/thick distinction (§3.5), gcausal reframed (§3.3), gcomm as scope expansion not correction
- Three rounds of internal review board (R1→R3: 4 R&Rs → 5 Accepts)
- New material: asymmetric spillover prediction, prediction market test case (with Hayek and herding citations), sycophancy as conflict of targets, multimodal/retrieval second worked case, pipeline-audit subsection, concrete falsification conditions
- Mechanistic evidence: Wang et al. 2025 (activation patching for sycophancy), Qi et al. 2025 and Arditi et al. 2024 (shallow alignment, scoped to safety routing)
- HPC permissivity: Magnus 2014 and Craver 2009 engaged
- "Successor models" replaced with multi-channel cultural inheritance
- Etiological/constitutive distinction carried through all strands, octopus, prediction market, conclusion
- Model/system distinction enforced; Table footnote added
- Octopus section tightened (agentic digression cut, regime-sensitivity sharpened)
- "At least four" signals open taxonomy
- Oxford spelling, contractions, en-dashes (Bringhurst), confabulation not hallucination
- 8+ new bib entries in references-local.bib
- 5 interpretability PDFs downloaded and converted to markdown
- Proofread pass complete
- Clean build (xelatex + biber), all citations resolving
- Abstract trimmed to venue-compliant length
- Core citation ledger and claim/objection matrices updated with page anchors and addressed statuses
- Boyd, Clark \& Wilkes-Gibbs, and Roloff verification pass completed against local PDFs
- PhiMiSci submission constraints checked against `docs/groundwork/07-venue-constraints.md`
- Preprint/publication statuses reflected in bibliography metadata: Floridi et al. as arXiv preprint, Manheim as published in *Philosophy \& Technology*
- PhilArchive preprint posted: `REYRAA-2`
- Current PhilArchive categories: `Computational Semantics`, `Representation in Connectionism`, `Semantics, Misc`
- Current PhilArchive keywords: `Vector Grounding Problem`, `large language models`, `teleosemantics`, `referential grounding`, `extra-linguistic reference`, `groundedness profiles`, `communicative calibration`, `homeostatic property clusters`

## Note: Aryaman Arora (2026) on sparse circuits

Arora et al. (2026) "Language model circuits are sparse in the neuron basis" (arXiv:2601.22594) finds that ~100 MLP neurons control subject-verb agreement behaviour, and these are causally manipulable via gradient-based attribution. This strengthens the mechanistic evidence line alongside Wang et al. (2025) and Qi et al. (2025): grammatical structure in LMs is sparse, localisable, and causally active, not distributed noise. Consider citing in the next revision if the mechanistic evidence section is revisited.

## What's Next

1. **Prepare anonymized submission file** — keep self-citations and acknowledgements out of the journal-submission version as needed
2. **Wait for Geoff and Ryan comments** (Geoff sent revised draft 2026-03-19; Ryan pending)
3. **Choose active submission venue**
4. **Submit to venue**

## Last Updated

2026-03-19 — Preprint posted to PhilArchive; project phase moved to submission prep.
2026-03-30 — Journal submission version: added Wang & Bedny (2026) to §3.1 and Arora et al. (2026) to §3.2. Dropped Huh et al. (PRH) and Lupyan podcast.

### Literature: Many Minds podcast (Frank & Lupyan, 2026-03-26)
- **Symbol grounding problem:** Lupyan argues grounding is "a matter of degree rather than kind" — aligns with your graded cluster property framework. Bedny lab (congenital blindness + LLMs, Annual Reviews of Linguistics) as evidence for grounding-without-embodiment. Lupyan: "LLMs have shifted my own personal view... downgrade the importance of sensory input."
- **Platonic Representation Hypothesis:** Different learners converge to same representations. Adjacent to your argument.
- See `literature/many-minds-frank-lupyan-2026.md` for full notes + transcript.
