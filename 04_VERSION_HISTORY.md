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

## Version 11 — 2026-07-20

**Questions added:** 15 (PK2059-ON-2011-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. Two topic files received their first-ever entry this
version: `02-liaquat-ali-khan.md` (Q4(b)) and
`03-united-states-of-america.md` (Q5(a)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2011 sessions/variants
field corrected from "May/June, V1" to "May/June, V1 + Oct/Nov, V1" (status
remains Complete).
**Reason:** Eighth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2011, single variant. Source was the official mark scheme
only. Every one of the 15 parts under the 2010–2014 extraction pattern was
presented with clickable topic options and allocated strictly per the user's
picks. Notable decisions: Q1(a) ("Who was Titu Mir?") and Q2(c) (Hajji Shariat
Ullah's contribution) both went to Religious Reformers; Q1(c) (educational vs
other British reforms 1773–1856) went to East India Company over Decline of
the Mughal Empire; Q3(c) ("Montague-Chelmsford reforms... 1909 and 1919")
went to **Multiple Topic Questions (1905–1926)** per explicit user instruction,
overriding the recommended "Montagu–Chelmsford Reforms & Other Events of 1919"
topic — establishing a new precedent that this multi-event 1909–1919 content
type defaults to the bucket topic rather than the Montagu-Chelmsford-named one
(the 2014/01 Q2(c) equivalent had already independently landed in this same
bucket); Q4(b) (difficulty agreeing the 1950 Constitution) went to Liaquat Ali
Khan — its first-ever entry — over Initial Problems of Pakistan, since the
draft-constitution dispute falls within his premiership; Q5(a) (Pakistan's
role in the 1960 U2 crisis) went to United States of America — its first-ever
entry — over Ayub Khan, establishing that leader-era foreign-policy events can
be filed under the country-relationship topic instead of the leader when the
user so chooses; Q5(b) ("Why did General Musharraf come to power in 1999?")
went to Nawaz Sharif over Multiple Regime Questions, consistent with the
existing 2013/01 entry in the same file (no dedicated Musharraf topic exists,
as Section 3A's Nationhood scope is framed as 1947–1999). One source anomaly
preserved verbatim: Q5(c)'s LEVEL 4 band prints as "[11–13]" rather than the
"[9–13]" pattern used elsewhere in this bank — not corrected. All 15 parts
required under the 2010–2014 extraction pattern were present and extracted;
none skipped.
**Date:** 2026-07-20

## Version 12 — 2026-07-20

**Questions added:** 15 (PK2059-ON-2012-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. One topic file received its first-ever entry this
version: `04-ussr-russia.md` (Q4(c)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2012 sessions/variants
field corrected from "May/June, V1" to "May/June, V1 + Oct/Nov, V1" (status
remains Complete).
**Reason:** Ninth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2012, single variant. Source was the official mark scheme
only. Every one of the 15 parts under the 2010–2014 extraction pattern was
presented with clickable topic options and allocated strictly per the user's
picks. Notable decisions: Q1(a) ("Hindu-Urdu Controversy") went to Sir Syed
Ahmad Khan over Urdu Language Controversy, since the stem and MS frame it
through Sir Syed's reaction and its role in shaping his Two Nation Theory;
Q2(c) (Lucknow Pact vs other 1909–1919 attempts) went to Multiple Topic
Questions (1905–1926), consistent with the Version 11 precedent; Q3(c) ("Day
of Deliverance... Jinnah's greatest achievement 1929–1947", spanning six of
Jinnah's achievements) went to **Iqbal, Rehmat Ali & Jinnah for Pakistan**
(topic #29) per explicit user instruction, its first entry evaluating Jinnah's
achievements rather than a biography or leader-comparison question; Q4(b)
("Why was Martial Law declared by Ayub Khan in 1958?") went to Ayub Khan, as
named in the question stem, despite the MS's own content centering partly on
Iskander Mirza's motives. One notable source-content anomaly (not a printing
error, an internal MS inconsistency) preserved verbatim: Q1(c)'s Successes/
Failures lists are framed from the Indian-resistance perspective (power of
local Nawabs, Tipu Sultan/Ranjit Singh's early successes listed as
"Successes"; British army strength and eventual conquest listed as
"Failures") — the inverse of how the same content is framed in this bank's
May/June 2010 and Oct/Nov 2010 Q1(c) entries — reproduced exactly as printed,
not reconciled. All 15 parts required under the 2010–2014 extraction pattern
were present and extracted; none skipped.
**Date:** 2026-07-20

## Version 13 — 2026-07-20

**Questions added:** 15 (PK2059-ON-2013-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. Two topic files received their first-ever entry this
version: `20-quit-india-movement.md` (Q3(a)) and `04-iskander-mirza.md`
(Q4(a)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2013 sessions/variants
field extended to add "+ Oct/Nov, V1" alongside the existing May/June, V1
(original series) and 2059/41 resit entries (status remains Complete).
**Reason:** Tenth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2013, single variant. This is a standard single sitting for
this session, distinct from the May/June 2013 series which required both an
original paper (2059/01) and a Pakistan-only security-breach resit (2059/41).
Source was the official mark scheme only. Every one of the 15 parts under the
2010–2014 extraction pattern was presented with clickable topic options and
allocated strictly per the user's picks. Notable decisions: Q2(c) (Muslim
League founding 1906) went to Creation of the All-India Muslim League; Q4(a)
("Describe the 1956 Constitution?") went to Iskander Mirza — its first-ever
entry — since the 1956 Constitution installed him as President, and no
exact-name topic exists for the constitution itself; Q4(c) (problems of
Partition 1947–1948) went to Initial Problems of Pakistan & Quaid-e-Azam,
near-identical to the existing May/June 2012 entry but with three additional
Failures bullets not present there, reproduced as its own distinct instance;
Q5(c) (Pakistan-India relations 1947–1999) went to India and the Kashmir
Issue, consistent with the May/June 2012 precedent. Minor source anomalies
preserved verbatim: Q1(c)'s MS reads "vast wealth ad profit" (likely a
printed typo for "and profit"); Q3(c) spells "Bande Matram" (single-t),
matching the 2012/01 and 2013/41 entries in this bank rather than the
Oct/Nov 2010 entry's "Bande Mattram" (double-t) — neither corrected. All 15
parts required under the 2010–2014 extraction pattern were present and
extracted; none skipped.
**Date:** 2026-07-20

## Version 14 — 2026-07-20

**Questions added:** 15 (PK2059-ON-2014-V1-Q1A through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 15 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2014 sessions/variants
field corrected from "May/June, V1" to "May/June, V1 + Oct/Nov, V1" (status
remains Complete).
**Reason:** Eleventh paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2014, single variant, and the fifth Oct/Nov-session paper
processed in this batch (completing the Oct/Nov coverage for 2010–2014).
Source was the official mark scheme only. Every one of the 15 parts under
the 2010–2014 extraction pattern was presented with clickable topic options
and allocated strictly per the user's picks. Notable decisions: Q2(c)
("Were the Montague–Chelmsford Reforms the main reason for the outbreak of
violence across India in 1919?") went to the direct-match Montagu–Chelmsford
Reforms & Other Events of 1919 topic rather than the Multiple Topic Questions
(1905–1926) bucket, since the question centers specifically on the MC
Reforms with the Rowlatt Act/Amritsar as supporting context, not a broad
multi-decade comparison; Q4(a) (terms of the 1973 Constitution) went to
Zulfiqar Ali Bhutto, since it was his own initiative; Q4(b) ("Why were there
so many governments between 1951 and 1958?") went to Multiple Regime
Questions (1947–1999) over Liaquat Ali Khan, since the content spans general
political instability across several unnamed governments rather than one
leader's story. Two entries in this paper are substantively near-duplicate
content of earlier entries already in this bank, each reproduced separately
and verbatim as its own distinct paper instance rather than merged: Q2(b)
(Muslim League 1906) closely parallels the May/June 2012 Q2(b); Q5(c)
(Pakistan-Afghanistan relations 1947–1999) is near word-for-word identical
to the May/June 2010 Q5(c). Minor source anomalies preserved verbatim: Q2(c)'s
MS states the MC Reforms "were proposed in 1918" (dated 1919 everywhere else
in this bank); Q3(c)'s LEVEL 1 band carries no printed mark range (every
other LEVEL 1 band in this bank does); Q4(c)'s LEVEL 2 band lists "Hudood,
Zina, and Zakat Ordinances" (omitting "Qafq," present in this file's other
entries); Q5(a) spells "Zardani" rather than "Zardari." None corrected. All
15 parts required under the 2010–2014 extraction pattern were present and
extracted; none skipped.

**This completes Oct/Nov coverage for the entire 2010–2014 extraction-pattern
era for 2059/01**, alongside the already-complete May/June coverage: every
year 2010–2014 now has both May/June and Oct/Nov sittings extracted (2013
additionally has the 2059/41 security-breach resit). Total: 165 questions
across 11 papers. Remaining in this batch: 2015–2025 May/June and Oct/Nov
papers for 2059/01 (14-part pattern), still to come.
**Date:** 2026-07-20

## Version 15 — 2026-07-20

**Questions added:** 14 (PK2059-MJ-2015-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated. `01_PAPERS_TRACKER.md` — 2015 added as
"May/June, V1" with status "In progress" (Oct/Nov 2015 still pending in this
batch).
**Reason:** Twelfth paper processed — Cambridge O Level 2059/01, Paper 1,
May/June 2015, single variant, and the **first paper processed under the
2015–2025 extraction pattern**. This paper introduced a structural change not
previously seen in this bank: a Section A / Section B split, with Section A
(Q1) now containing four parts. Q1(a) and Q1(b) are source-based questions
(referencing "Source A" and "Source B" — an image/document insert not
included in the mark scheme) and were excluded per `EXTRACTION_RULES.md`,
which had already anticipated this exact structure. Only Q1(c) and Q1(d) were
extracted from Q1, plus the full three-part Q2–Q5 as before, for 14 parts
total. A second structural change: Section A's essay question, Q1(d), caps at
**10 marks** rather than the usual 14 (LEVEL 5 tops out at [10]) — reproduced
exactly as printed, including an internal overlap between LEVEL 3 [5–7] and
LEVEL 4 [6–9]. Every one of the 14 parts was presented with clickable topic
options and allocated strictly per the user's picks. Notable decisions: Q2(a)
("Who was Tipu Sultan?") went to East India Company, as no dedicated topic
exists for Tipu Sultan; Q3(b) ("Why did Jinnah produce his 14 Points in
1929?") went to Jinnah's Fourteen Points — its second-ever entry, and the
first time a question was allocated to this topic purely on a direct-match
basis since the original Version 3 entry; Q4(a) ("What was the 'Afghan
Miracle'?") went to **General Zia-ul-Haq** per explicit user instruction,
overriding the recommended Afghanistan country-relationship topic; Q4(b)
("Why was Islamabad chosen as the new capital of Pakistan?") went to Ayub
Khan, since the MS explains the decision as his. Three entries in this paper
are substantively near-duplicate content of earlier entries already in this
bank, each reproduced separately and verbatim as its own distinct instance:
Q2(b) (Urdu as national language) closely parallels the Oct/Nov 2011 entry;
Q3(c) (Round Table Conferences) and Q5(b) (Musharraf's 1999 rise) both
closely parallel their May/June 2010 and Oct/Nov 2011 counterparts
respectively. All 14 parts required under the 2015–2025 extraction pattern
were present and extracted; none skipped.
**Date:** 2026-07-20

## Version 16 — 2026-07-20

**Questions added:** 14 (PK2059-ON-2015-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No brand-new topic files were created, but two
previously-empty topic files received their first-ever entries this version:
Delhi Proposals & Simon Commission (Q3(a)) and Gulf Countries (Q4(b)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 179 → 193). `01_PAPERS_TRACKER.md` — 2015
row updated to "May/June, V1 + Oct/Nov, V1" with status "Complete."
**Reason:** Thirteenth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2015, single variant, and the second paper processed under
the 2015–2025 extraction pattern (Section A/B split; Q1(a)/(b) source-based
and excluded; Q1(d) capped at 10 marks). Every one of the 14 parts was
presented with clickable topic options and allocated strictly per the user's
picks. Notable decisions: Q4(a) ("What was Operation Searchlight?") went to
**Yahya Khan**, consistent with every prior decision on equivalent
Bangladesh-creation questions in this bank; Q4(b) ("Why did Pakistan support
the Palestinian cause between 1947 and 1999?") went to **Gulf Countries** per
explicit user override, over the recommended United Nations & Other World
Organisations topic — the first-ever entry in this topic file; Q3(a) ("What
was the Simon Report?") is the first-ever entry in the Delhi Proposals &
Simon Commission topic file. Two entries in this paper are substantively
near-duplicate content of earlier entries already in this bank, each
reproduced separately and verbatim as its own distinct instance: Q1(c)
(Cripps Mission opposition) closely parallels the May/June 2012 Q3(b); Q5(b)
(Benazir Bhutto's second dismissal) and Q5(c) (Kashmir issue) closely
parallel their Oct/Nov 2012 and Oct/Nov 2011 counterparts respectively.
Minor source anomalies preserved verbatim: Q2(b) spells "Shah Waliullah" (one
word) versus "Shah Wali Ullah" (three words) used elsewhere in this bank;
Q2(c) spells "Auranzeb" (missing "g"); Q1(d) has a stray full stop mid-phrase
("the 3 June Plan. of 1947"); Q5(a) has a missing space (".Financed"); Q5(c)'s
LEVEL 5 band carries no printed mark value. None corrected. All 14 parts
required under the 2015–2025 extraction pattern were present and extracted;
none skipped.

**This completes all sessions/variants uploaded for 2015** (both May/June and
Oct/Nov). Total: 193 questions across 13 papers. Remaining in this batch:
2016–2025 May/June and Oct/Nov papers for 2059/01 (14-part pattern), still to
come.
**Date:** 2026-07-20

## Version 17 — 2026-07-20

**Questions added:** 14 (PK2059-MJ-2016-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No brand-new topic files were created, but the
previously-empty Bangladesh topic file received its first-ever entry this
version (Q1(d)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 193 → 207). `01_PAPERS_TRACKER.md` — 2016
row added as "May/June, V1" with status "In progress" (Oct/Nov 2016 still
pending in this batch).
**Reason:** Fourteenth paper processed — Cambridge O Level 2059/01, Paper 1,
May/June 2016, single variant, and the first paper processed for 2016 under
the 2015–2025 extraction pattern (Section A/B split; Q1(a)/(b) source-based
and excluded; Q1(d) capped at 10 marks). Every one of the 14 parts was
presented with clickable topic options and allocated strictly per the user's
picks. Notable decisions: Q1(c) ("Why did the victory of the Awami League in
the 1970 elections in Pakistan cause a constitutional crisis?") went to
**Yahya Khan**, consistent with every prior decision on equivalent
Bangladesh-creation questions in this bank; Q1(d) ("How successful have
relations between Pakistan and Bangladesh been from 1971 to 1999?") went to
**Bangladesh** — the first-ever entry in this topic file, since its scope
(post-1971 diplomatic relations) is distinct from the Bangladesh-creation
content consistently filed under Yahya Khan; Q4(a) ("What was the 'One Unit'
Scheme?") went to Iskander Mirza, its second entry, since the MS credits him
directly as the scheme's author. Several entries in this paper are
substantively near-duplicate content of earlier entries already in this
bank, each reproduced separately and verbatim as its own distinct instance:
Q2(a) (Cawnpore) parallels the May/June 2011 "battle of Kanpur" entry; Q2(b)
(EIC appeal) parallels several prior "why did the EIC become involved"
entries; Q2(c) (Shah Waliullah's contribution) parallels the May/June 2013
and Oct/Nov 2011 entries; Q3(b) (Partition of Bengal causes) parallels the
Oct/Nov 2012 entry; Q4(b) (Ayub Khan's Martial Law) parallels the Oct/Nov
2012 and Oct/Nov 2013 entries; Q5(b) (Zia-ul-Haq's late-1980s difficulties)
parallels the May/June 2013 (2059/41) entry. Minor source anomaly preserved
verbatim: Q4(a)'s MS has a missing space ("challengedif"). None corrected.
All 14 parts required under the 2015–2025 extraction pattern were present and
extracted; none skipped.

**2016 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 207 questions across 14 papers. Remaining in this batch: 2016
Oct/Nov, plus 2017–2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-20

## Version 18 — 2026-07-20

**Questions added:** 14 (PK2059-ON-2016-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No brand-new topic files were created, but the
previously-empty 3rd June Plan topic file received its first-ever entry
this version (Q4(a)).
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 207 → 221). `01_PAPERS_TRACKER.md` — 2016
row updated to "May/June, V1 + Oct/Nov, V1" with status "Complete."
**Reason:** Fifteenth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2016, single variant, and the second paper processed for
2016 under the 2015–2025 extraction pattern (Section A/B split; Q1(a)/(b)
source-based and excluded; Q1(d) capped at 10 marks). Every one of the 14
parts was presented with clickable topic options and allocated strictly per
the user's picks. Notable decisions: Q3(c) ("Was the partition of Bengal the
main reason for the formation of the Muslim League in 1906?") went to
**Creation of the All-India Muslim League** over Partition of Bengal (1905),
since the question is fundamentally about the League's formation, weighing
Partition of Bengal against other causes; Q4(a) ("What was the 3 June
Plan?") went to the **3rd June Plan** topic — its first-ever entry; Q5(a)
(Musharraf's rise to power) went to **Nawaz Sharif**, consistent with every
prior decision on equivalent questions; Q5(b) ("Why was there a
constitutional crisis between 1954 and 1955?") went to **Malik Ghulam
Muhammad**, since although the MS content also touches Jinnah, Liaquat Ali
Khan, Nazimuddin, and Bogra, its central active figure is Ghulam Muhammad's
own decisions (dissolving the Assembly, declaring emergency, prevailing in
court) — consistent with the May/June 2012 Q4(a) precedent already in that
topic file. Several entries in this paper are substantively near-duplicate
content of earlier entries already in this bank, each reproduced separately
and verbatim as its own distinct instance: Q2(a) (Nana Sahib) parallels the
May/June 2016 "Cawnpore" entry; Q2(b) (Britain's success 1750–1850)
parallels several prior EIC entries; Q2(c) (Sir Syed's western-education
achievement) parallels the May/June 2013 and May/June 2015 entries; Q3(a)
(Lucknow Pact) parallels the May/June 2012 entry; Q3(c) (Muslim League
formation) parallels the May/June 2010 and Oct/Nov 2013 entries; Q4(c)
(Iqbal vs. Rahmat Ali) parallels the May/June 2011 entry; Q5(a) (Musharraf's
rise) parallels the May/June 2013 entry; Q5(c) (UK/Commonwealth relations)
parallels the May/June 2013 entry, here with several additional aid/trade
figures not present there. This paper's mark scheme consistently uses
bullet-point formatting rather than the continuous-prose style of earlier
papers — reproduced as printed throughout. Minor source anomalies preserved
verbatim: several LEVEL 1 bands in this paper carry no printed example
statement (Q2(c), Q3(c), Q5(c)); Q5(b) refers to "Khan Liaquat Ali Khan"
(name order reversed); Q4(c)'s question stem spells "Rahmat Ali" rather than
this bank's usual "Rehmat Ali." None corrected. All 14 parts required under
the 2015–2025 extraction pattern were present and extracted; none skipped.

**This completes all sessions/variants uploaded for 2016** (both May/June
and Oct/Nov). Total: 221 questions across 15 papers. Remaining in this
batch: 2017–2025 May/June and Oct/Nov papers for 2059/01 (14-part pattern),
still to come.
**Date:** 2026-07-20

## Version 19 — 2026-07-20

**Questions added:** 14 (PK2059-MJ-2017-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No new or previously-empty topic files were touched
this version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 221 → 235). `01_PAPERS_TRACKER.md` — 2017
row added as "May/June, V1" with status "In progress" (Oct/Nov 2017 still
pending in this batch).
**Reason:** Sixteenth paper processed — Cambridge O Level 2059/01, Paper 1,
May/June 2017, single variant, and the first paper in this batch presented
in Cambridge's newer tabular Question/Answer/Marks mark scheme format
(rather than the earlier LEVEL-band prose style used in 2010–2016 papers) —
reproduced faithfully in that structure throughout. Every one of the 14
parts required under the 2015–2025 extraction pattern (Section A/B split;
Q1(a)/(b) source-based and excluded; Q1(d) capped at 10 marks) was presented
with clickable topic options and allocated strictly per the user's picks.
Notable decisions: Q2(a) ("Who were zamindars?") went to **East India
Company** per explicit user override of the recommended Decline of the
Mughal Empire, since the MS content also covers zamindars' later oppression
of Muslims in British-era East Bengal; Q4(c) (comparing Khwaja Nazimuddin,
Malik Ghulam Muhammad, and Iskander Mirza's domestic-policy contributions)
went to Multiple Regime Questions (1947–1999), the same bucket used for the
equivalent May/June 2013 three-leader comparison (there featuring Liaquat
Ali Khan instead of Nazimuddin); Q5(a) ("What was SEATO?") went to United
Nations & Other World Organisations, as an international/regional body
Pakistan joined. Several entries in this paper are substantively
near-duplicate content of earlier entries already in this bank, each
reproduced separately and verbatim as its own distinct instance: Q4(a)
(Basic Democracies) parallels the Oct/Nov 2011 entry; Q5(c)
(Pakistan-Afghanistan relations) parallels the May/June 2010 and Oct/Nov
2014 entries, here adding several new bullets (Zahir Shah's 1965 neutrality,
Bhutto/Zia/Daud visits, Taliban-era militancy). Minor source anomaly
preserved verbatim: Q2(c)'s MS spells "Paniplat" (elsewhere in this bank
"Panipat"); Q3(c)'s LEVEL 1 example ("They were always fighting each other")
is a generic template line unrelated to the Khilafat Movement. None
corrected. All 14 parts were present and extracted; none skipped.

**2017 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 235 questions across 16 papers. Remaining in this batch: 2017
Oct/Nov, plus 2018–2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-20

## Version 20 — 2026-07-20

**Questions added:** 14 (PK2059-ON-2017-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 235 → 249). `01_PAPERS_TRACKER.md` — 2017
row updated to "May/June, V1 + Oct/Nov, V1" with status "Complete."
**Reason:** Seventeenth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2017, single variant, and the second paper in this batch
presented in Cambridge's newer tabular Question/Answer/Marks mark scheme
format — reproduced faithfully in that structure throughout. Every one of
the 14 parts required under the 2015–2025 extraction pattern (Section A/B
split; Q1(a)/(b) source-based and excluded; Q1(d) capped at 10 marks) was
presented with clickable topic options and allocated strictly per the
user's picks. Notable decisions: Q1(d) (comparing the Nehru Report, Jinnah's
14 Points, and the Government of India Act 1935) went to Multiple Topic
Questions (1927–1947), the same bucket used for the equivalent May/June 2013
(2059/41) three-factor comparison there substituting the Simon Commission
for the Nehru Report; Q2(a) ("Who were the Thuggee?") went to East India
Company, consistent with the "zamindars" precedent from the May/June 2017
paper, since the EIC's 1830 suppression action is the MS's central focus;
Q5(a) ("What happened at Pucca Qila?") went to Benazir Bhutto, matching the
established precedent for this recurring massacre/dismissal event. Several
entries in this paper are substantively near-duplicate content of earlier
entries already in this bank, each reproduced separately and verbatim as
its own distinct instance: Q2(b) (EIC's seventeenth-century involvement),
Q2(c) (Haji Shariatullah's contribution), Q3(c) (Indian resistance to
British expansion), Q4(a) (Direct Action Day), Q4(b) (Gandhi-Jinnah Talks),
Q4(c) (Pakistan's world-organisation membership), Q5(b) (1947 refugee
problem), and Q5(c) (Pakistan-USSR relations) all parallel earlier entries
in their respective topic files. Minor source anomalies preserved verbatim:
Q1(d)'s question stem prints "193" instead of "1935" for the Government of
India Act; Q3(a)'s MS dates Warren Hastings's Governor-Generalship to 1782
(historically 1773); Q5(a) spells "Muhajir Quami Movement" (elsewhere in
this bank "Mohajir Qaumi Movement"); Q5(b)'s MS heading is printed as
"Level 1: Simple stateme" (truncated). None corrected. All 14 parts were
present and extracted; none skipped.

**This completes all sessions/variants uploaded for 2017** (both May/June
and Oct/Nov). Total: 249 questions across 17 papers. Remaining in this
batch: 2018–2025 May/June and Oct/Nov papers for 2059/01 (14-part pattern),
still to come.
**Date:** 2026-07-20

## Version 21 — 2026-07-20

**Questions added:** 14 (PK2059-MJ-2018-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 249 → 263). `01_PAPERS_TRACKER.md` — 2018
row updated to "May/June, V1" with status "In progress."
**Reason:** Eighteenth paper processed — Cambridge O Level 2059/01, Paper 1,
May/June 2018, single variant, presented in Cambridge's newer tabular
Question/Answer/Marks mark scheme format (plus an initial "Generic Marking
Principles" boilerplate page correctly recognised as non-content and
skipped). Every one of the 14 parts required under the 2015–2025 extraction
pattern (Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d)
capped at 10 marks) was presented with clickable topic options and
allocated strictly per the user's picks. Notable decisions: Q4(a) ("What was
the Radcliffe Award?") went to Initial Problems of Pakistan &
Quaid-e-Azam as Governor-General, an unprompted user override of both
offered options (the recommended "3rd June Plan" and the alternate
"Multiple Topic Questions (1927–1947)"), on the reasoning that the
boundary award fed directly into Pakistan's founding-era territorial
problems; Q4(b) ("Explain why Pakistan has given continued support to the
Palestinian cause") went to Gulf Countries, again matching the established
Oct/Nov 2015 precedent for this recurring question over the recommended
United Nations & Other World Organisations option; Q4(c) (Gandhi-Jinnah
talks vs other 1940s partition factors) went to Multiple Topic Questions
(1927–1947) rather than the recommended Gandhi–Jinnah Talks single-topic
file, since the MS content spans six distinct named events (the talks,
Lahore Resolution, 1945–46 elections, Cabinet Mission Plan, Direct Action
Day, 3rd June Plan); Q5(b) (1958 constitutional crisis) went to Iskander
Mirza, matching the MS's central focus on his loss of political support.
Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q2(a) (Titu Mir), Q2(b) (Sir Syed
Ahmad Khan improving Muslim-British relations), Q3(a) (Swadeshi Movement),
and Q3(c) (Round Table Conferences comparison) all parallel earlier entries
in their respective topic files. Minor source anomalies preserved verbatim:
Q1(d)'s MS states Pakistan-Bangladesh trade negotiations "brought an extra
$40 billion a year into Pakistan by 1986" (plausibly a printed error for a
smaller figure); Q2(a)'s MS names Titu Mir "Syed Mir Nisar" (commonly
rendered "Mir Nisar Ali" elsewhere); Q2(b) spells "The Loyal Mohammadens of
India" (elsewhere in this bank "The Loyal Mohammedans of India"); Q2(c)'s
MS reads "Missionaries came to covert people to Christianity" (likely a
typo for "convert"); Q3(b)'s MS refers to the "Simla Agreement" (elsewhere
in this bank "Simla Declaration"; this bank's dedicated topic is titled
"Simla Deputation"); Q5(c) spells "Muhajir Quami Movement" (elsewhere in
this bank "Mohajir Qaumi Movement"). None corrected. All 14 parts were
present and extracted; none skipped.

**2018 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 263 questions across 18 papers. Remaining in this batch: 2018
Oct/Nov, plus 2019–2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-20

## Version 22 — 2026-07-20

**Questions added:** 14 (PK2059-ON-2018-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4 process.
`questions/INDEX.md` updated (total 263 → 277). `01_PAPERS_TRACKER.md` — 2018
row updated to "May/June, V1 + Oct/Nov, V1" with status "Complete."
**Reason:** Nineteenth paper processed — Cambridge O Level 2059/01, Paper 1,
October/November 2018, single variant, presented in Cambridge's newer
tabular Question/Answer/Marks mark scheme format (plus an initial "Generic
Marking Principles" boilerplate page correctly recognised as non-content
and skipped). Every one of the 14 parts required under the 2015–2025
extraction pattern (Section A/B split; Q1(a)/(b) source-based and excluded;
Q1(d) capped at 10 marks) was presented with clickable topic options and
allocated strictly per the user's picks. Notable decisions: Q1(c) ("Why was
India not granted self-rule by Britain in 1919?") went to Montagu–Chelmsford
Reforms & Other Events of 1919, matching this topic's established scope for
the 1919-cluster events; Q1(d) (comparing the Morley-Minto Reforms, the
reversal of the Partition of Bengal, and the Lucknow Pact) went to Multiple
Topic Questions (1905–1926), following the precedent set in the Oct/Nov 2011
Q3(c) entry already in that file; Q3(a) ("What was the Communal Award?")
went to Round Table Conferences, since the MS ties it directly to the
Second RTC's outcome — first entry in this file naming the Communal Award
specifically; Q4(b) ("Why did educational reform become such an important
issue between 1947 and 1999?") went to Multiple Regime Questions
(1947–1999), matching the precedent set by the May/June 2013 (2059/41)
education-policy entry already in that file, since no dedicated "education"
topic exists in the 57-topic taxonomy and the question spans the whole
period rather than one leader; Q4(c) (comparing Zulfikar Ali Bhutto's own
armed-forces, constitutional, and education/health reforms) went to
Zulfiqar Ali Bhutto rather than the Multiple Regime bucket, since all three
compared factors are his own reforms, not a cross-leader comparison; Q5(a)
("What was the Eighth Amendment?") went to General Zia-ul-Haq, its first
entry as the sole subject of a question in that file (the Amendment had
only been referenced as background in earlier entries there). Several
entries in this paper are substantively near-duplicate content of earlier
entries already in this bank, each reproduced separately and verbatim as
its own distinct instance: Q3(c) (Wardha Scheme/Congress rule), Q4(a)
(1947 refugee crisis), Q5(b) (Urdu as national language), and Q5(c)
(Pakistan-China relationship, which parallels this bank's very first China
entry from Oct/Nov 2010) all parallel earlier entries in their respective
topic files. Minor source anomalies preserved verbatim: Q1(c)'s Level 1
descriptor reads "(One mark for each identification)" rather than the usual
"(One mark for any simple statement)" pattern; Q2(c)'s MS contains a stray
empty bullet point between the British-expansion exemplar and the "Other
reasons" subheading; Q3(a) spells "Ramsey MacDonald" (commonly "Ramsay
MacDonald"); Q3(c) reads "were taught in Hindi, This was resented" (a
comma followed by a capitalised "This," likely a printing error for a full
stop); Q4(a) reads "Communal violence lead to many deaths" (likely a
printing error for "led"). None corrected. All 14 parts were present and
extracted; none skipped.

**This completes all sessions/variants uploaded for 2018** (both May/June
and Oct/Nov). Total: 277 questions across 19 papers. Remaining in this
batch: 2019–2025 May/June and Oct/Nov papers for 2059/01 (14-part pattern),
still to come.
**Date:** 2026-07-20

## Version 23 — 2026-07-20

**Questions added:** 14 (PK2059-MJ-2019-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None held for the full-job audit per the Version 4
process — except for one correction made this version: `questions/INDEX.md`'s
Khilafat Movement row was found to be undercounting by 2 (listed as 9,
later 10, against an actual 11-then-12 UQID entries in the file itself) —
a pre-existing arithmetic error from an earlier version, not introduced
this session. Corrected to the true count (12) after cross-checking every
topic file's actual UQID count against the INDEX total (291), which now
reconciles exactly.
`questions/INDEX.md` updated (total 277 → 291, plus the Khilafat Movement
correction above). `01_PAPERS_TRACKER.md` — 2019 row updated to "May/June,
V1" with status "In progress."
**Reason:** Twentieth paper processed — Cambridge O Level 2059/01, Paper 1,
May/June 2019, single variant, presented in Cambridge's newer tabular
Question/Answer/Marks mark scheme format (plus an initial "Generic Marking
Principles" boilerplate page correctly recognised as non-content and
skipped). Every one of the 14 parts required under the 2015–2025 extraction
pattern (Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d)
capped at 10 marks) was presented with clickable topic options and
allocated strictly per the user's picks. Notable decisions: Q1(c) (Robert
Clive's success at Plassey) and Q1(d) (India Act of 1784 vs other
expansion factors) both went to East India Company, consistent with this
topic's established scope for EIC conquest/administration content; Q2(a)
(Ahmad Shah Durrani) went to Decline of the Mughal Empire, matching the
established Afghan/Persian-invasions precedent; Q3(a) (Lord Wellesley) went
to East India Company, his subsidiary-alliance policy already referenced in
this same paper's Q1(d) entry; Q4(a) ("Who was Rahmat Ali?") went to Iqbal,
Rehmat Ali & Jinnah for Pakistan, this topic's dedicated home despite the
MS's alternate "Rahmat Ali" spelling; Q5(b) (many governments 1951–1958)
went to Multiple Regime Questions (1947–1999), near-identical to the
Oct/Nov 2014 entry already there. Several entries in this paper are
substantively near-duplicate content of earlier entries already in this
bank, each reproduced separately and verbatim as its own distinct instance:
Q2(b) (why the British wanted to trade in India), Q2(c) (three-way
religious-reformer comparison), Q3(b) (why 1857 failed), Q3(c) (Sir Syed's
most important contribution), Q4(b) (Congress rule 1937–1939 grievances),
and Q5(c) (Ayub Khan's Decade of Progress reforms) all parallel earlier
entries in their respective topic files. Minor source anomalies preserved
verbatim: Q1(d)'s Level 4 band [6–9] overlaps Level 3's [5–7], the same
overlap pattern already flagged in this file's May/June 2015 entry; Q4(b)
names a "Widdia Mandar scheme" as distinct from the Wardha Scheme (elsewhere
in this bank these are used interchangeably for the same policy); Q4(c)
gives a specific "18 000" figure for Khilafat-era hijrat migrants versus
the vaguer "thousands" used elsewhere in this bank; Q5(c)'s Level 4
descriptor mistakenly reads "one on the challenges in Sindh and one on
another reason" — an apparent copy-paste artifact from a Benazir Bhutto
question, left uncorrected in this Ayub Khan entry. None corrected. All 14
parts were present and extracted; none skipped.

**2019 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 291 questions across 20 papers. Remaining in this batch:
2019 Oct/Nov, plus 2020–2025 May/June and Oct/Nov papers for 2059/01
(14-part pattern), still to come.
**Date:** 2026-07-20
