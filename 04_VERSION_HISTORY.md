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

## Version 6 — 2026-07-19

**Questions added:** 15 (PK2059-MJ-2012-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0 — Q3(a) ("Who was Chaudri Rehmat Ali?") became the second
question allocated into the Version-5-created topic #29 (Iqbal, Rehmat Ali &
Jinnah for Pakistan).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` and `01_PAPERS_TRACKER.md` (2059/01, 2012 marked Complete)
updated.
**Reason:** Third paper processed — Cambridge O Level 2059/01, Paper 1, May/June
2012, single variant. Source was the official mark scheme only, as with prior
papers. Every one of the 15 parts was presented with clickable topic options and
allocated strictly per the user's picks. Two parts had no exact-name taxonomy
topic and were resolved by user decision: Q4(a) (constitutional crisis of 1954–55)
went to Malik Ghulam Muhammad over Multiple Regime Questions; Q4(b) (Pakistani
migration 1947–1999) went to United Kingdom & the Commonwealth over Gulf
Countries. Two minor source-printing anomalies were preserved verbatim rather than
corrected: Q1(c)'s LEVEL 4 band prints as "[9–10]" and Q5(b)'s LEVEL 3 band prints
as "[3–6]", both inconsistent with the syllabus's usual banding but reproduced
exactly as printed. All 15 parts required under the 2010–2014 extraction pattern
were present and extracted; none skipped.
**Date:** 2026-07-19

## Version 7 — 2026-07-19

**Questions added:** 15 (PK2059-MJ-2013-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. Two topic files received their first-ever entry this
version: `11-multiple-regime-questions-1947-1999.md` (Q4(c)) and
`07-zulfiqar-ali-bhutto.md` (Q4(a)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2013 set to "In progress"
at this point: this original 2059/01 series paper (sat by candidates outside
Pakistan) is done, but a separate resit paper, 2059/41, was administered only to
candidates inside Pakistan following a security breach and was still pending (see
Version 8, which completes it and marks 2013 fully Complete).
**Reason:** Fourth paper processed — Cambridge O Level 2059/01, Paper 1, May/June
2013 series, the ORIGINAL paper (not the Pakistan-only resit — see next version
for that). Source was the official mark scheme only. Every one of the 15 parts
was presented with clickable topic options and allocated strictly per the user's
picks. One part had no exact-name taxonomy topic: Q4(a) ("Describe the Simla
Agreement," the 1972 Bhutto–Indira Gandhi accord, distinct from the existing 1945
"Simla Conference" topic) went to Zulfiqar Ali Bhutto over India and the Kashmir
Issue. Q4(c) (comparing Liaquat Ali Khan, Malik Ghulam Muhammad, and Iskander
Mirza) went to Multiple Regime Questions (1947–1999) — its first-ever entry — over
filing under a single leader. Q5(b) (East Pakistan's wish for independence) went
to Yahya Khan, consistent with the equivalent decision in the 2011 paper. All 15
parts required under the 2010–2014 extraction pattern were present and extracted;
none skipped.
**Date:** 2026-07-19

## Version 8 — 2026-07-19

**Questions added:** 15 (PK2059-MJ-2013-V41-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. Two topic files received their first-ever entry this
version: `02-simla-deputation-1906.md` (Q2(a)) and
`05-morley-minto-reforms-1909.md` (Q2(b)); `28-multiple-topic-questions-1927-1947.md`
went from empty to 2 entries in this version (Q2(c) and Q3(c)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2013 now marked Complete
(both the original 2059/01 series and the 2059/41 resit are extracted).
**Reason:** Fifth paper processed — Cambridge O Level **2059/41**, the Pakistan-only
resit of the May/June 2013 series, administered after a security breach affecting
the original 2059/01 sitting. This is a distinct paper with its own question set
(not a re-issue of 2059/01's questions), tracked separately by component code per
the front matter of the source mark scheme itself. Source was the official mark
scheme only. Every one of the 15 parts was presented with clickable topic options
and allocated strictly per the user's picks. Notable decisions: Q1(a) ("Who was
Ranjit Singh?") went to East India Company, as no exact-name topic exists for
Anglo-Sikh relations; Q2(c) (Simon Commission vs 14 Points vs GoI Act 1935) and
Q3(c) (WWII-era independence negotiations, spanning five named topics) both went
to Multiple Topic Questions (1927–1947); Q4(a) ("How did Ayub Khan achieve
power?") went to Ayub Khan over Iskander Mirza despite the stem's Mirza-heavy
context; Q4(b) (general education policy) went to Multiple Regime Questions
(1947–1999); Q5(a) (Sheikh Mujib-ur-Rahman) went to Yahya Khan, consistent with
prior Bangladesh-creation placements. One source anomaly preserved verbatim:
Q3(b)'s mark scheme names "the Widdia Mander Scheme" where the equivalent scheme
is called "the Wardha Scheme" elsewhere in this bank — reproduced exactly as
printed, not corrected. All 15 parts required under the 2010–2014 extraction
pattern were present and extracted; none skipped.
**Date:** 2026-07-19

## Version 9 — 2026-07-19

**Questions added:** 15 (PK2059-MJ-2014-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. Three topic files received their first-ever entry this
version: `15-elections-of-1937.md` (Q2(a)), `06-reversal-of-partition-of-bengal-1911.md`
(Q2(b)), and `24-cabinet-mission-plan.md` (Q3(a)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2014 marked Complete.
**Reason:** Sixth paper processed — Cambridge O Level 2059/01, Paper 1, May/June
2014, single variant, and the fourth of the four papers uploaded together in this
batch. Source was the official mark scheme only. Every one of the 15 parts was
presented with clickable topic options and allocated strictly per the user's
picks. Q2(c) (political developments 1909–1919, spanning Lucknow Pact,
Morley–Minto, Montagu–Chelmsford, and the Rowlatt Act) went to Multiple Topic
Questions (1905–1926). Three overlap decisions on Section 3 content: Q5(a)
("What was the Kargil Conflict?") went to India and the Kashmir Issue over Nawaz
Sharif, despite the equivalent 2013/01 question going to Nawaz Sharif — this
stem does not name a Prime Minister, unlike that one; Q5(b) (Zulfiqar Ali
Bhutto's execution) went to General Zia-ul-Haq over Zulfiqar Ali Bhutto, since
the mark scheme's final point centers on Zia's motive; Q5(c) (Bangladesh
creation, 1971) went to Yahya Khan, consistent with every prior equivalent
decision in this bank. All 15 parts required under the 2010–2014 extraction
pattern were present and extracted; none skipped.

**This completes the 2010–2014 extraction-pattern era for 2059/01**: 2010, 2011,
2012, 2013 (both components), and 2014 are all now marked Complete in
`01_PAPERS_TRACKER.md` — 90 questions total across 6 papers. Remaining work:
2059/01 2015–2025 (the reduced Q1(c)/(d) + Q2–5(a/b/c) pattern), and all of
0448/01 (IGCSE) 2010–2025.
**Date:** 2026-07-19

## Version 10 — 2026-07-20

**Questions added:** 15 (PK2059-ON-2010-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. Two topic files received their first-ever entry this
version: `01-partition-of-bengal-1905.md` (Q3(a)) and
`02-china.md` (Q5(c)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2010 sessions/variants
field corrected from "May/June, V1" to "May/June, V1 + Oct/Nov, V1" (status
remains Complete).
**Reason:** Seventh paper processed, and the first of a new 27-paper batch —
Cambridge O Level 2059/01, Paper 1, **October/November 2010**, single variant.
This is the first Oct/Nov-session paper processed in this project, resolving
Open Question #1 from the prior handoff document: yes, Oct/Nov sittings exist
for 2059/01 (this batch includes Oct/Nov papers for 2010 through 2025). Because
2010 had previously been marked "Complete" based on May/June coverage alone, its
tracker status is retroactively understood to have only ever reflected the
May/June sitting; it is corrected here to record both sessions now that Oct/Nov
2010 is also extracted. Source was the official mark scheme only. Every one of
the 15 parts under the 2010–2014 (15-part) extraction pattern was presented with
clickable topic options and allocated strictly per the user's picks — content is
closely parallel to the May/June 2010 paper already in this bank (same five
question themes: Faraizi Movement, EIC, Balochi language promotion, Mughal
decline, Sir Syed, Swadeshi Movement, Simla Deputation, Khilafat Movement, Iqbal,
Congress Rule, WWII negotiations, Simla Agreement, Benazir Bhutto, China) but
extracted and logged as its own fully distinct paper, never merged or treated as
a duplicate. No topic overlaps required tie-breaking beyond established
precedent (Q1(c) → East India Company over Decline of the Mughal Empire; Q3(a)
→ Partition of Bengal (1905) over the Multiple Topic Questions bucket; Q4(c) and
Q5(a) followed the same precedents set in the May/June 2010 and 2013 papers).
Minor source-printing anomalies preserved verbatim rather than corrected: Q1(b)'s
LEVEL 3 band prints as "(9–13)" despite the question being worth only 7 marks;
Q2(c) is printed as worth [13] marks while its own mark scheme's top band reaches
(14); Q4(b) spells "Bande Mattram" (double-t) versus "Bande Matram" (single-t) in
other papers in this bank. All 15 parts required under the 2010–2014 extraction
pattern were present and extracted; none skipped.
**Date:** 2026-07-20
