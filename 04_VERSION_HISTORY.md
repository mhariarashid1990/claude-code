# Version History

## Version 1 — 2026-07-19

**Questions added:** 0
**Questions moved:** 0
**Audit updates:** Initialized all six audit layers at zero state.
**Reason:** Project scaffold creation — folder structure, Golden Rules, extraction
rules, classification framework (56 topics across 4 sections), question entry
template, command reference, papers tracker (2010–2025, both 2059/01 and 0448/01),
and audit layers. No past paper has been uploaded yet; no question content has been
extracted, invented, or allocated.
**Date:** 2026-07-19

## Version 2 — 2026-07-19

**Questions added:** 0
**Questions moved:** 0
**Audit updates:** Coverage audit (Audit 5) year range corrected.
**Reason:** Correction to project scope: the first extraction-pattern year range in
`00_SYSTEM/EXTRACTION_RULES.md` changes from 2009–2014 to 2010–2014 (the 2015–2025
pattern is unchanged). 2009 is dropped from project scope entirely — removed from
`01_PAPERS_TRACKER.md`, and the 2009–2025 references in `README.md` and the coverage
audit updated to 2010–2025. No question content existed for 2009, so nothing was
lost.
**Date:** 2026-07-19

## Version 3 — 2026-07-19

**Questions added:** 15 (PK2059-MJ-2010-V1-Q1A through Q5C)
**Questions moved:** 0
**Audit updates:** All six audit layers updated — Extraction (1 paper, 15/15 parts),
Allocation (15 Allocated, 0 pending), Metadata (0 missing fields), Coverage (15
topics now populated), Final QA (per-paper checks pass, overall still NOT READY).
`01_PAPERS_TRACKER.md` — 2059/01, 2010 marked Complete (May/June, V1).
`questions/INDEX.md` counts updated for the 15 affected topics.
**Reason:** First paper processed — Cambridge O Level 2059/01, Paper 1, May/June
2010, single variant. Source was the official mark scheme only (no separate
question paper supplied); question text extracted verbatim as reprinted in the MS,
per explicit user confirmation. Two questions had genuine topic overlaps —
Q2(a) "What was the Wardha Scheme?" (Congress Rule 1937–1939 vs Elections of 1937)
and Q4(a) "What was the Canal Water Dispute?" (Initial Problems of Pakistan vs
India and the Kashmir Issue) — both stopped for user decision per Golden Rule 2 and
were resolved before allocation. All 15 parts required under the 2010–2014
extraction pattern (Q1–Q5, parts a/b/c) were present and extracted; none skipped.
**Date:** 2026-07-19

## Version 4 — 2026-07-19

**Questions added:** 0
**Questions moved:** 0
**Audit updates:** None — this version is a workflow/process change, not a content
change.
**Reason:** Standing operating procedure change per explicit user directive: (1)
Recommend/Allocate never auto-classifies regardless of confidence — every extracted
question part must be presented as clickable topic options and wait for the user's
choice, superseding the previous "auto-allocate if Very High confidence" behaviour;
(2) the six audit layers (`02_AUDITS/`) are no longer refreshed after each
individual paper — they are run once, in full, only once the entire upload job
(every required paper, 2010–2025, both 2059/01 and 0448/01) is 100% extracted and
allocated. `00_SYSTEM/GOLDEN_RULES.md` (Rule 2) and `00_SYSTEM/COMMANDS.md`
(Recommend, Allocate, Audit definitions and the per-paper workflow) updated
accordingly.
**Date:** 2026-07-19

## Version 5 — 2026-07-19

**Questions added:** 15 (PK2059-MJ-2011-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 1 — "Iqbal, Rehmat Ali & Jinnah for Pakistan" added to Section 2
as Primary Topic #29, at the user's explicit direction, for ideological-contribution
questions about Iqbal, Rehmat Ali, and Jinnah with no existing named home.
**Audit updates:** None — per the Version 4 process change, `02_AUDITS/` is not
refreshed per paper; it will be run in full once the entire upload job is complete.
`questions/INDEX.md`, `00_SYSTEM/CLASSIFICATION_FRAMEWORK.md`, and
`01_PAPERS_TRACKER.md` (2059/01, 2011 marked Complete) updated.
**Reason:** Second paper processed — Cambridge O Level 2059/01, Paper 1, May/June
2011, single variant. Source was the official mark scheme only (no separate
question paper supplied), as with Version 3. Per the Version 4 workflow change,
every one of the 15 parts was presented with clickable topic options and allocated
strictly per the user's picks — no auto-allocation was applied even where
confidence would have been Very High. Two notable user decisions: Q3(c) ("Partition
or reversal?") went to Multiple Topic Questions (1905–1926) rather than either
single-event topic; Q5(c) (creation of Bangladesh, 1971) went to Yahya Khan rather
than the recommended Bangladesh topic. All 15 parts required under the 2010–2014
extraction pattern (Q1–Q5, parts a/b/c) were present and extracted; none skipped.
**Date:** 2026-07-19
