# Original Docs Claim Audit

- Project: vector-grounding-problem_response
- Date: 2026-03-05
- Scope: `docs/source-notes/*.md` (excluding `INDEX.md`)
- Method: Heuristic string match against linked PDF text using normalized lead-phrase probes.
- Caveat: `NO MATCH` does not prove falsehood; OCR, hyphenation, and paraphrase can break string matching.
- Status: Superseded by `11-manual-note-verification.md` for page-anchored quote checks.

## Summary
- Notes scanned: 9
- Missing sources: 0
- Candidate quotations matched: 0 / 0
- Idea-seed bullets matched: 0 / 0

## Per-Note Results

| Note | Source status | Quotes matched | Idea seeds matched |
|---|---|---:|---:|
| arai_tsugawa_2024_inferentialism_llms.md | OK | 0/0 | 0/0 |
| bender_koller_2020_octopus_test.md | OK | 0/0 | 0/0 |
| clark_wilkes_gibbs_1986_referring.md | OK | 0/0 | 0/0 |
| coelho_mollo_milliere_2026_reply_core.md | OK | 0/0 | 0/0 |
| floridi_jia_tohme_2025_circumvent_grounding.md | OK | 0/0 | 0/0 |
| havlik_2023_meaning_understanding_llms.md | OK | 0/0 | 0/0 |
| millikan_1990_compare_contrast.md | OK | 0/0 | 0/0 |
| roloff_2025_teleosemantics_limits.md | OK | 0/0 | 0/0 |
| royal_society_2023_symbols_grounding.md | OK | 0/0 | 0/0 |

## Unmatched Candidate Quotes (Top 3 per note)

All candidate quotes matched heuristically.
## Next Actions

1. For each low-match note, manually verify in PDF with page-level anchors.
2. Replace OCR-fragment quote candidates with exact short quotes and add page numbers.
3. Mark ledger rows as `CHECKED` once page anchors are added.
