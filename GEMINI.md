# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A reply paper to Coelho Mollo & Milliere (2026) "The Vector Grounding Problem" (PhiMiSci). The reply argues that referential grounding should be modeled as a graded cluster property (a "groundedness profile") rather than a binary grounded/ungrounded verdict. Teleosemantic selection history is one central stabilizer among others (communicative calibration, inferential role, etc.).

**Target venue:** Philosophy and AI journals (PhiMiSci, Synthese, Philosophy & Technology). Venue not yet locked.

**Companion paper:** `hpc_to_vector` (general HPC/SPC-to-embedding framework). This reply is narrower: it intervenes in the VGP debate specifically and doesn't build a full ontology of embedding spaces.

## Current State

`main.tex` is a complete draft, not a skeleton. The paper has been posted as a PhilArchive preprint (`REYRAA-2`); remaining work is limited to any final external comments, journal-submission preparation, and optional public-metadata cleanup. The groundwork docs in `docs/groundwork/` now function as verification/control documents for the live draft and should still be consulted before substantive edits.

## Build

```bash
make              # Full build (xelatex + biber + 2x xelatex)
make quick        # Single xelatex pass
make clean        # Remove artifacts, keep PDF
```

Requires XeLaTeX. The house style uses `EB Garamond` as the main font and `Charis SIL` as an IPA fallback; pdfLaTeX is not supported.

## Intellectual Architecture

The paper's argument runs through six pressure points mapped in `docs/groundwork/06-claim-evidence-matrix.md`:

1. **Intro:** VGP as extra-linguistic aboutness for vector systems (Harnad 1990 lineage)
2. **Taxonomy:** Grounding notions are distinguishable and non-equivalent (referential, relational, communicative, epistemic)
3. **Core move:** Referential grounding as graded profile, not binary
4. **Communicative mechanism:** Social calibration as stabilizer (Clark & Wilkes-Gibbs 1986, Putnam 1975)
5. **Octopus reassessment:** Bender & Koller's test is regime-sensitive, not decisive
6. **Debate positioning:** Narrows elimination claims without rejecting teleosemantics

Key objections and planned responses: `docs/groundwork/05-objection-matrix.md`

## Groundwork System

Before drafting any section, consult these (in `docs/groundwork/`):

| File | Purpose |
|------|---------|
| `03-definitions-sheet.md` | Fixed term definitions; lock before drafting |
| `05-objection-matrix.md` | Objections, strongest sources, planned responses |
| `06-claim-evidence-matrix.md` | Section-by-section claim support with citekeys |
| `02-quote-bank.md` | Verified verbatim quotes with page anchors |
| `01-citation-ledger.md` | Source-level citation log; track page-level evidence |
| `04-contribution-boundary.md` | What this paper does/doesn't do vs `hpc_to_vector` |
| `08-structured-abstract.md` | Abstract scaffold |

Source notes for individual papers: `docs/source-notes/` (see `INDEX.md` for reading order).

## Key Terminology

These definitions (from `03-definitions-sheet.md`) must be used consistently:

- **Vector Grounding Problem:** How embeddings could acquire extra-linguistic reference without interpreter dependence
- **Referential grounding:** Representational states connected to worldly entities under correctness conditions
- **Relational grounding:** Intra-representational linkage (vector-to-vector) without direct referential anchoring
- **Communicative grounding:** Coordination/calibration in dialogue for shared usage and repair
- **Groundedness profile:** Degree-profile across multiple stabilizers (this paper's novel framing)
- **Teleosemantic function:** Success/failure norms from selection history and proper function

## Bibliography

`references.bib` currently has 18 entries, with additional local/supporting material in `references-local.bib`. The citation ledger (`01-citation-ledger.md`) tracks the core page-level evidence set and is now populated with page anchors for the tracked sources.

Local PDFs live in `literature/` (project-local) and `../../literature/` (portfolio-level).

## House Style and Source Grounding

LaTeX conventions and typography are defined in `.house-style/preamble.tex` and `.house-style/style-rules.yaml`. The critical rules for this project:

- **Source grounding (LAW):** Read PDFs before citing. No statistics, quotes, or claims from memory.
- **Rapoport's Rules:** This is a reply paper. Restate Coelho Mollo & Milliere's position charitably before criticizing.

## Multi-Agent Dispatch

Before dispatching multiple agents, ask Brett which model(s) and whether redundant outputs are wanted. If no local dispatch playbook is present, treat this as a hard coordination requirement rather than assuming a default workflow.

## Git

Pre-commit hook syncs CLAUDE.md, AGENTS.md, GEMINI.md. Build before committing.
