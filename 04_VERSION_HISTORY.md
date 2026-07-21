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

## Version 24 — 2026-07-20

**Questions added:** 14 (PK2059-ON-2019-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 291 → 305, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2019 row updated to "May/June, V1 + Oct/Nov, V1"
with status "Complete."
**Reason:** Twenty-first paper processed — Cambridge O Level 2059/01, Paper
1, October/November 2019, single variant, presented in Cambridge's newer
tabular Question/Answer/Marks mark scheme format (plus an initial "Generic
Marking Principles" boilerplate page correctly recognised as non-content
and skipped). Every one of the 14 parts required under the 2015–2025
extraction pattern (Section A/B split; Q1(a)/(b) source-based and excluded;
Q1(d) capped at 10 marks) was presented with clickable topic options and
allocated strictly per the user's picks. Notable decisions: Q1(c) ("Explain
how Jinnah transformed the Muslim League between 1937 and 1939") went to
Elections of 1937 by explicit user override of both offered options (Iqbal,
Rehmat Ali & Jinnah for Pakistan and Creation of the All-India Muslim
League), pairing it with this same paper's Q1(d) on the 1937 election
result itself; Q3(a) ("What was Satyagraha?") went to Montagu–Chelmsford
Reforms & Other Events of 1919, since the MS dates Gandhi's idea to 1919,
the cluster year this topic covers — its first entry on Satyagraha
specifically; Q3(c) (Simla Deputation 1906 vs other reasons for the Muslim
League's formation) went to Creation of the All-India Muslim League, the
first entry there to use the "Simla Deputation" wording rather than "Simla
Declaration"/"Simla Agreement" seen elsewhere in that file; Q4(c) (Jinnah's
14 Points vs Iqbal's Allahabad Address, Rahmat Ali's pamphlet, the
Government of India Act 1935, and the Lahore Resolution) went to Iqbal,
Rehmat Ali & Jinnah for Pakistan by explicit user choice, consistent with
that topic's role as the home for cross-figure Pakistan Movement
comparisons. Several entries in this paper are substantively near-duplicate
content of earlier entries already in this bank, each reproduced separately
and verbatim as its own distinct instance: Q2(a) (Sir Syed's "Loyal
Mohammedans of India"), Q2(b) (Mughal decline after Aurangzeb), Q2(c)
(educational reforms vs other British changes), Q3(b) (why three RTCs were
held), Q4(a) (Cabinet Mission Plan), Q4(b) (Cripps Mission failure), Q5(a)
(Karakoram Highway), Q5(b) (Pakistan's UN membership), and Q5(c) (Pakistan's
1949–1973 constitutional efforts) all parallel earlier entries in their
respective topic files. Minor source anomalies preserved verbatim: Q1(d)
gives "104/489" Muslim seats won by the Muslim League in the 1937
elections, versus "109" used elsewhere in this bank; Q4(c)'s MS spells the
same person "Rahmat Ali" in its Level 4 exemplars but "Rehmat Ali" in its
Level 2 exemplars, within the same mark scheme. None corrected. All 14
parts were present and extracted; none skipped.

**This completes all sessions/variants uploaded for 2019** (both May/June
and Oct/Nov). Total: 305 questions across 21 papers. Remaining in this
batch: 2020–2025 May/June and Oct/Nov papers for 2059/01 (14-part pattern),
still to come.
**Date:** 2026-07-20

## Version 25 — 2026-07-20

**Questions added:** 14 (PK2059-MJ-2020-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. However, this version supplied the **first-ever
entry** in `section-2-creation-of-pakistan/17-day-of-deliverance.md`
(Q4(a), "What was the 'Day of Deliverance'?") — that topic file had existed
in the taxonomy since it was scaffolded but had never previously received a
question.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 305 → 319, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2020 row updated to "May/June, V1" with status "In
progress" (Oct/Nov 2020 still outstanding).
**Reason:** Twenty-second paper processed — Cambridge O Level 2059/01,
Paper 1, May/June 2020, single variant.

⚠️ **COVID-19 cancelled series.** This mark scheme carries the following
notice, reproduced verbatim: "Students did not sit exam papers in the June
2020 series due to the Covid-19 global pandemic. This mark scheme is
published to support teachers and students for future examination series...
In the June series, Examiners were unable to consider the acceptability of
alternative responses, as there were no student responses to consider."
Because no candidates actually sat this paper, the mark scheme was never
validated against real student answers. The user was asked explicitly how
to handle this (extract normally and flag prominently, vs. skip the paper
entirely) and chose to **extract normally, flag prominently**. Every one of
this paper's 14 entries therefore carries a prominent COVID-cancellation
flag at the start of its Audit Status field, cross-referencing the fuller
explanation given in Q1(c) of
`section-1-mughal-decline-british-rule/02-east-india-company.md`.

Every one of the 14 parts required under the 2015–2025 extraction pattern
(Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d) capped at 10
marks) was extracted. Several parts had only one plausible topic and no
genuine alternative, so per the AskUserQuestion tool's own constraint
(rejecting single-option question batches), those allocations were stated
directly rather than offered as clickable options: Q1(d) (War of
Independence 1857 economic-reforms question), Q2(c) (Aurangzeb's policies
and Mughal decline), Q3(b) (why the Khilafat Movement ended in 1924), Q4(a)
(Day of Deliverance — first entry in that file), Q4(b) (opposition to the
Government of India Act 1935), Q4(c) (Iqbal and Rahmat Ali's contributions),
and Q5(a) (Fatima Jinnah, filed under Ayub Khan) and Q5(c) (BCCI collapse,
filed under Nawaz Sharif) were also single-option, consistent with
established precedent from earlier papers in this bank (no dedicated
Fatima Jinnah or Musharraf topics exist in the taxonomy). Remaining parts
(Q1(c), Q2(a), Q2(b), Q3(a), Q3(c), Q5(b)) were presented with clickable
options and allocated per the user's picks.

Notable source anomalies preserved verbatim, none corrected: Q2(c)'s MS
repeatedly spells "polices" for "policies" in its Level 3/Level 4 headings;
Q3(c)'s MS states "Bengal was the largest province in India. 54 million
people were Hindu, out of a population of 84 million," differing from this
same topic file's prior entries which state "Of the 54 million people in
Bengal 42 million were Hindus" (a different population total and a
different Hindu-population figure against the same 54 million base),
reproduced separately and not reconciled; Q5(b)'s MS reads "which reducing
the government's efficiency," a grammar slip left uncorrected. All 14 parts
were present and extracted; none skipped.

**This begins the 2020 papers.** Total: 319 questions across 22 papers.
Remaining in this batch: 2020 Oct/Nov, then 2021–2025 May/June and Oct/Nov
papers for 2059/01 (14-part pattern) — Oct/Nov 2020's mark scheme should
also be checked for any COVID-era anomalies before assuming normal
extraction applies.
**Date:** 2026-07-21

## Version 26 — 2026-07-21

**Questions added:** 14 (PK2059-ON-2020-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 319 → 333, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2020 row updated to "May/June, V1 + Oct/Nov, V1"
with status "Complete."
**Reason:** Twenty-third paper processed — Cambridge O Level 2059/01,
Paper 1, October/November 2020, single variant. This mark scheme carries
no COVID-19 cancellation notice — a normal series, extracted normally like
any pre-2020 paper.

This paper also marks a **mark scheme format change**: rather than
printing bespoke Level 1–5 descriptors under each part (c)/(b) question as
in every prior paper in this bank, the MS now references two reusable
generic grids ("Table 1" for Section A part (c) and Section B part (b)
questions targeting 7 marks; "Table 2" for Section B part (c) questions
targeting 14 marks) printed once at the front of the document, with each
question's own row simply saying "Mark according to the level of response
descriptors in Table 1/2" followed by indicative content. Each entry this
version reproduces the referenced generic table's descriptors inline
(quoted from the front-matter tables) alongside that question's own
indicative content, to keep the mark scheme text usable standalone
per-question, consistent with the verbatim-preservation goal of this
project. Section A Q1(d) is the one exception, still carrying a
bespoke Level 5–0 descriptor set specific to that question (capped at 10
marks), matching the established 2015+ pattern for that part.

Every one of the 14 parts required under the 2015–2025 extraction pattern
(Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d) capped at
10 marks) was extracted. All 14 parts this paper had only one plausible
allocation with no genuine alternative topic, so per the AskUserQuestion
tool's own constraint (rejecting single-option question batches), every
allocation was stated directly to the user rather than offered as
clickable options: Q1(c) (impact of railways, filed under East India
Company — no dedicated "Railways" topic exists in the taxonomy), Q1(d)
(War of Independence 1857), Q2(a) (Jizya tax, under Decline of the Mughal
Empire), Q2(b) (Shah Waliullah, under Religious Reformers), Q2(c) (Sir
Syed Ahmad Khan's Two-Nation Theory), Q3(a) (Hijrat Movement, under
Khilafat Movement per established precedent), Q3(b) (Round Table
Conferences), Q3(c) (Direct Action Day), Q4(a) (OIC, under United Nations
& Other World Organisations), Q4(b) (Ayub Khan's rise to power in 1958),
Q4(c) (UK & Commonwealth relations), Q5(a) (Security of Tenure scheme,
under Zulfiqar Ali Bhutto), Q5(b) (Zia-ul-Haq's late-1980s governing
challenges), and Q5(c) (Benazir Bhutto's privatisation policy and 1996
downfall).

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q2(b) (Shah Waliullah's importance),
Q3(a) (Hijrat Movement), Q3(b) (why three RTCs were held), Q4(b) (Ayub
Khan's rise to power), Q4(c) (UK/Commonwealth relations), and Q5(b)
(Zia-ul-Haq's late-1980s difficulties) all parallel earlier entries in
their respective topic files. Minor source anomalies preserved verbatim,
none corrected: Q3(a)'s MS gives a range "18000–20000 people" for the
Hijrat migrants, differing from the vaguer "thousands" and the specific
"18 000" figure used elsewhere in the Khilafat Movement file; Q4(a)'s MS
names the OIC "Organisation of Islamic Countries" in one bullet and
"Organisation of Islamic Conference" (the historically correct pre-2011
name) in another, within the same mark scheme; Q5(b)'s MS spells "Ojhri
Camp" here versus "Camp Ojhri" used in this bank's other Zia-ul-Haq
entries. All 14 parts were present and extracted; none skipped.

**This completes all sessions/variants uploaded for 2020** (both May/June,
V1 — COVID-cancelled series, flagged per user instruction — and Oct/Nov,
V1 — normal series). Total: 333 questions across 23 papers. Remaining in
this batch: 2021–2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-21

## Version 27 — 2026-07-21

**Questions added:** 14 (PK2059-MJ-2021-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files, though two
entries (Ranjit Singh under Decline of the Mughal Empire; Muhammad Khan
Junejo under General Zia-ul-Haq) are the first in their files to name that
particular historical figure as the sole subject of a question.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 333 → 347, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2021 row updated to "May/June, V1" with status "In
progress" (Oct/Nov 2021 still outstanding).
**Reason:** Twenty-fourth paper processed — Cambridge O Level 2059/01,
Paper 1, May/June 2021, single variant. This mark scheme carries no
COVID-19 cancellation notice — a normal series, extracted normally, using
the same generic Table 1/Table 2 levels-of-response format introduced in
the Oct/Nov 2020 paper.

Every one of the 14 parts required under the 2015–2025 extraction pattern
(Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d) capped at
10 marks) was extracted. Twelve of the 14 parts had only one plausible
allocation with no genuine alternative topic, so per the AskUserQuestion
tool's own constraint, those allocations were stated directly to the user:
Q1(c) (Lucknow Pact of 1916), Q1(d) (India's benefit from WWI support by
the early 1920s, under Montagu–Chelmsford Reforms & Other Events of 1919),
Q2(a) (Ranjit Singh's achievements, under Decline of the Mughal Empire — no
dedicated Sikh Empire topic exists), Q2(b) (Jinnah's choice of Urdu),
Q2(c) (Shah Waliullah, spread of Islam 1700–1850), Q3(a) (Allahabad
1930/Iqbal's address), Q3(b) (formation of the Muslim League in 1906),
Q3(c) (outcomes of the War of Independence), Q4(a) (Simla Agreement,
under Zulfiqar Ali Bhutto), Q4(b) (opposition to the Cripps Mission 1942),
Q4(c) (Ayub Khan's agricultural policies), and Q5(c) (Pakistan–USA
relations since 1947).

Two parts had genuine alternative topics and were presented via
AskUserQuestion: Q5(a) ("Describe the main events of Muhammad Khan
Junejo's political career") — no dedicated Junejo topic exists; the user
chose **General Zia-ul-Haq** (Recommended) over Multiple Regime Questions
(1947–1999), since Junejo was Zia's own appointee and was ultimately
dismissed by Zia. Q5(b) ("Explain why there were changes of government
between 1951 and 1958") — spans multiple short-lived governments rather
than one leader's story; the user chose **Multiple Regime Questions
(1947–1999)** (Recommended) over Iskander Mirza.

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q2(b) (why Urdu was chosen), Q2(c)
(Shah Waliullah's importance), Q3(b) (why the Muslim League formed), Q4(b)
(Cripps Mission opposition), Q4(c) (Ayub Khan's most effective domestic
policy), Q5(b) (why there were changes of government 1951–1958), and
Q5(c) (Pakistan–USA relations) all parallel earlier entries in their
respective topic files. Minor source anomaly preserved verbatim, not
corrected: Q2(c)'s MS reads "he promoted Islam through this writings and
education" (a grammar slip, likely intended "his writings"). All 14 parts
were present and extracted; none skipped.

**2021 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 347 questions across 24 papers. Remaining in this batch:
2021 Oct/Nov, then 2022–2025 May/June and Oct/Nov papers for 2059/01
(14-part pattern), still to come.
**Date:** 2026-07-21

## Version 28 — 2026-07-21

**Questions added:** 14 (PK2059-ON-2021-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 347 → 361, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2021 row updated to "May/June, V1 + Oct/Nov, V1"
with status "Complete."
**Reason:** Twenty-fifth paper processed — Cambridge O Level 2059/01,
Paper 1, October/November 2021, single variant. This mark scheme carries
no COVID-19 cancellation notice — a normal series, extracted normally,
using the same generic Table 1/Table 2 levels-of-response format
introduced in the Oct/Nov 2020 paper.

Every one of the 14 parts required under the 2015–2025 extraction pattern
(Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d) capped at
10 marks) was extracted. Thirteen of the 14 parts had only one plausible
allocation with no genuine alternative topic, so per the AskUserQuestion
tool's own constraint, those allocations were stated directly to the user:
Q1(c) (Hindu objections to the Jizya tax) and Q1(d) (Marathan rebellions
and Mughal decline), both under Decline of the Mughal Empire; Q2(a)
(battle of Buxar, under East India Company — first entry naming this
battle directly); Q2(b) (Sir Syed Ahmad Khan's post-1857 reconciliation
efforts); Q2(c) (imprisonment of leaders ending the Khilafat Movement);
Q3(a) (Jallianwalla Bagh 1919, under Montagu–Chelmsford Reforms & Other
Events of 1919); Q3(b) (Congress opposition to the Morley-Minto reforms
of 1909); Q3(c) (Pakistan's success solving Partition's challenges by
1948, under Initial Problems of Pakistan & Quaid-e-Azam as
Governor-General); Q4(a) (Quit India Resolution); Q4(b) (martial law
1958, under Ayub Khan); Q4(c) (Pakistan's effectiveness in world
organisations); Q5(b) (Zulfikar Ali Bhutto's education reforms
1971–1977); and Q5(c) (Zia-ul-Haq's Islamisation programme).

One part had a genuine alternative topic and was presented via
AskUserQuestion: Q5(a) ("Describe the 'cricket diplomacy' of 1987" —
Zia-ul-Haq attending a Pakistan–India test match in Jaipur and meeting
Rajiv Gandhi to ease tensions over Indian army exercises). The user
explicitly overrode the recommended option (General Zia-ul-Haq) and
directed this into **India and the Kashmir Issue** instead, since the
substance of the event is bilateral India–Pakistan diplomacy rather than
a domestic Zia policy — the first entry in that topic file to name the
1987 cricket-diplomacy meeting directly.

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q1(d) (Mughal decline after
Aurangzeb), Q2(b) (Sir Syed Ahmad Khan's reconciliation efforts), Q2(c)
(Khilafat Movement's end), Q3(a) (Jallianwalla Bagh/Amritsar, complementing
this bank's existing General Dyer entry), Q3(c) (Pakistan's post-Partition
challenges), Q4(a) (Quit India Resolution), Q4(b) (Ayub Khan's rise to
power), Q4(c) (Pakistan's world-organisation memberships), and Q5(c)
(Zia's most significant domestic policy) all parallel earlier entries in
their respective topic files. Minor source anomalies preserved verbatim,
none corrected: Q1(d)'s MS spells "Marathan" (elsewhere in this bank
"Maratha"/"Marathas"); Q2(a)'s MS dates the "Treaty of Allahabad" to 1768
(historically 1765); Q2(c)'s MS names "Mohammed Ali and Shaukat Ali-Maulana
Azad" as the Khilafat Movement's leaders, apparently running together
three distinct names without clear separation, and including Maulana Azad
who was a Congress rather than Khilafat Movement figure; Q3(a) spells
"Jallianwalla Bagh" (elsewhere in this bank usually "Jallianwala Bagh").
All 14 parts were present and extracted; none skipped.

**This completes all sessions/variants uploaded for 2021** (both May/June
and Oct/Nov). Total: 361 questions across 25 papers. Remaining in this
batch: 2022–2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-21

## Version 29 — 2026-07-21

**Questions added:** 14 (PK2059-MJ-2022-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 361 → 375, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2022 row updated to "May/June, V1" with status "In
progress" (Oct/Nov 2022 still outstanding).
**Reason:** Twenty-sixth paper processed — Cambridge O Level 2059/01,
Paper 1, May/June 2022, single variant. This mark scheme carries no
COVID-19 cancellation notice — a normal series, extracted normally, using
the same generic Table 1/Table 2 levels-of-response format used since
Oct/Nov 2020.

Every one of the 14 parts required under the 2015–2025 extraction pattern
(Section A/B split; Q1(a)/(b) source-based and excluded; Q1(d) capped at
10 marks) was extracted. Thirteen of the 14 parts had only one plausible
allocation with no genuine alternative topic, so per the AskUserQuestion
tool's own constraint, those allocations were stated directly to the user:
Q1(c) (Cripps Mission's limited success); Q1(d) (Gandhi–Jinnah talks
breakdown 1944); Q2(a) (battle of Balakot, under Religious Reformers) and
Q2(b) (Haji Shariatullah), both under Religious Reformers; Q2(c) (military
factors and the War of Independence 1857); Q3(a) (Mohammedan
Anglo-Oriental College, under Sir Syed Ahmad Khan); Q3(b) (Jinnah's 14
Points); Q3(c) (establishment of the All-India Muslim League 1906); Q4(a)
(Rowlatt Act terms, under Montagu–Chelmsford Reforms & Other Events of
1919); Q4(c) (Zulfikar Ali Bhutto's domestic policies 1971–1977); Q5(a)
(1956 Constitution, under Iskander Mirza — established precedent); and
Q5(c) (Pakistan–Bangladesh relations since 1971).

Two parts were presented via AskUserQuestion this version. Q4(b) ("Explain
why Pakistan becoming a nuclear power was significant") had no single
obvious home — its indicative content spans India-relations, US-relations,
and national pride without naming a specific leader or dated event. The
user explicitly overrode the recommended option (India and the Kashmir
Issue) and chose **United States of America (USA)** instead, since a
substantial share of the content concerns the effect on Pakistan's
relationship with Washington and its aid. Q5(b) ("circumstances that
brought General Pervez Musharraf into power in 1999") was allocated to
**Nawaz Sharif**, consistent with the strong established precedent in this
bank (every prior Musharraf's-rise question filed under Nawaz Sharif,
since no dedicated Musharraf topic exists) — this one was treated as
single-option given that precedent, and stated directly rather than
re-asked.

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q1(d) (Gandhi-Jinnah Talks
breakdown), Q3(a) (Aligarh college's purpose), Q3(b) (Jinnah's 14 Points),
Q3(c) (Muslim League's formation), Q4(c) (Bhutto's domestic policies —
this version adding specific inflation-rate figures), Q5(a) (1956
Constitution), and Q5(c) (Pakistan-Bangladesh relations) all parallel
earlier entries in their respective topic files. Minor source anomaly
preserved verbatim, not corrected: Q2(c)'s MS states "the East India
Company banned the export of cotton goods from India in 1800," an
unusually specific and early-dated claim not seen elsewhere in this bank.
All 14 parts were present and extracted; none skipped.

**2022 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 375 questions across 26 papers. Remaining in this batch:
2022 Oct/Nov, then 2023–2025 May/June and Oct/Nov papers for 2059/01
(14-part pattern), still to come.
**Date:** 2026-07-21

## Version 30 — 2026-07-21

**Questions added:** 14 (PK2059-ON-2022-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 375 → 389, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2022 row updated to "May/June, V1 + Oct/Nov, V1"
with status "Complete."
**Reason:** Twenty-seventh paper processed — Cambridge O Level 2059/01,
Paper 1, October/November 2022, single variant. This mark scheme carries
no COVID-19 cancellation notice — a normal series, extracted normally,
using the same generic Table 1/Table 2 levels-of-response format used
since Oct/Nov 2020.

**Procedural change this version, per explicit user instruction:** rather
than stating single-option allocations directly to the user (the pattern
used for Papers 23–26), every one of this paper's 14 parts was presented
via AskUserQuestion with a recommended primary option plus at least one
plausible secondary option, batched across five rounds (4+4+1
clarification+4+2 questions). The user confirmed the recommended
(primary) option in the great majority of cases; the process is now
expected to continue this way for all remaining papers through 2025.

One round required a clarification sub-question: the user's answer for
Q3(c) ("To what extent were the Morley-Minto reforms the most important
political development in India between 1909 and 1919?") came back as an
unrecognised value ("1905-26") that matched neither offered option. A
follow-up question was asked, adding a third option (Multiple Topic
Questions (1905–1926)) explicitly, and the user confirmed that was the
intended choice.

Final allocations this version: Q1(c) and Q1(d) (Ayub Khan's rise to
power and his "Decade of Development," both under Ayub Khan); Q2(a) (Nana
Sahib's military actions, under War of Independence (1857)); Q2(b)
(British expansion 1756–1856, under East India Company); Q2(c) (Sir Syed
Ahmad Khan's educational contribution); Q3(a) (Lord Curzon's impact,
under Partition of Bengal (1905) — first entry naming Curzon directly);
Q3(b) (Simon Commission's unpopularity, under Delhi Proposals & Simon
Commission); Q3(c) (Morley-Minto reforms 1909–1919, under Multiple Topic
Questions (1905–1926), per the clarification round above); Q4(a) (Nehru
Report terms); Q4(b) (why people joined the Khilafat Movement); Q4(c)
(Round Table Conferences); Q5(a) (Canal Water Dispute, under Initial
Problems of Pakistan & Quaid-e-Azam as Governor-General — established
precedent); Q5(b) (Benazir Bhutto's 1990 dismissal); and Q5(c)
(Pakistan–USSR relations, under USSR/Russia).

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q1(c) (Ayub Khan's rise), Q1(d)
(Decade of Development/Progress), Q2(a) (Nana Sahib), Q2(b) (British
expansion), Q2(c) (Sir Syed's contributions), Q4(a) (Nehru Report), Q4(c)
(Round Table Conferences), Q5(a) (Canal Water Dispute), Q5(b) (Benazir
Bhutto's dismissal), and Q5(c) (USSR relations) all parallel earlier
entries in their respective topic files. All 14 parts were present and
extracted; none skipped.

**This completes all sessions/variants uploaded for 2022** (both May/June
and Oct/Nov). Total: 389 questions across 27 papers. Remaining in this
batch: 2023–2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-21

## Version 31 — 2026-07-21

**Questions added:** 14 (PK2059-MJ-2023-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 389 → 403, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2023 row updated to "May/June, V1" with status "In
progress" (Oct/Nov 2023 still outstanding).
**Reason:** Twenty-eighth paper processed — Cambridge O Level 2059/01,
Paper 1, May/June 2023, single variant. This mark scheme carries no
COVID-19 cancellation notice — a normal series, extracted normally, using
the same generic Table 1/Table 2 levels-of-response format used since
Oct/Nov 2020.

Continuing the procedural change begun in Version 30, every one of this
paper's 14 parts was again presented via AskUserQuestion with a
recommended primary option plus at least one plausible secondary option,
batched across four rounds (4+4+4+2 questions). The user confirmed the
recommended (primary) option in most cases, but explicitly overrode the
recommendation twice: Q4(c) ("the referral of the Kashmir issue to the
United Nations") went to **India and the Kashmir Issue** rather than the
recommended United Nations & Other World Organisations; Q5(b) ("why
Pakistan decided to support the Palestinian cause") went to **Gulf
Countries** rather than the recommended United Nations & Other World
Organisations — consistent with this exact same override already
established as precedent in this file's Oct/Nov 2015 and May/June 2018
entries.

Final allocations this version: Q1(c) (Titu Mir, under Religious
Reformers); Q1(d) (Indian rulers limiting British expansion 1760–1840,
under East India Company); Q2(a) (aims of the All-India Muslim League);
Q2(b) (why the Round Table Conferences were considered a failure); Q2(c)
(Bengal's partition, "too large"); Q3(a) (Delhi Proposals of 1927 — first
entry naming the Proposals themselves as sole subject); Q3(b) (Iqbal as
"Architect of Pakistan"); Q3(c) (1937 election outcomes benefiting the
Muslim League); Q4(a) (U-2 incident, under United States of America);
Q4(b) (Zia-ul-Haq's Islamisation programme); Q4(c) (Kashmir's UN referral,
under India and the Kashmir Issue, per user override); Q5(a) (1973
Constitution's features, under Zulfiqar Ali Bhutto — first entry
describing its terms directly); Q5(b) (Palestinian cause, under Gulf
Countries, per user override matching established precedent); and Q5(c)
(Co-operative Societies scandal and Nawaz Sharif's 1993 dismissal).

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q1(c) (Titu Mir), Q2(b) (RTC
failure), Q3(b) (Iqbal's importance), Q3(c) (1937 election outcomes),
Q4(a) (U-2 incident), Q4(b) (Zia's Islamisation), Q5(b) (Palestinian
cause), and Q5(c) (Nawaz Sharif's 1993 downfall) all parallel earlier
entries in their respective topic files. Minor source anomalies preserved
verbatim, none corrected: Q1(c)'s MS reads "Titu Mir gave Muslim farmers a
cause the fight back" (likely intended "to fight back"); Q2(c)'s MS gives
"85 million" as the combined population of West Bengal, East Bengal and
Assam, differing from this bank's other Partition-of-Bengal entries which
give "54 million" for Bengal alone (not reconciled, since the 85 million
figure includes Assam and reflects the full partitioned territory). All 14
parts were present and extracted; none skipped.

**2023 is now in progress** (May/June done, Oct/Nov still pending in this
batch). Total: 403 questions across 28 papers. Remaining in this batch:
2023 Oct/Nov, then 2024–2025 May/June and Oct/Nov papers for 2059/01
(14-part pattern), still to come.
**Date:** 2026-07-21

## Version 32 — 2026-07-21

**Questions added:** 14 (PK2059-ON-2023-V1-Q1C through Q5C)
**Questions moved:** 0
**Topics created:** 0. No topic file received its first-ever entry this
version — all 14 parts landed in already-populated topic files.
**Audit updates:** None — held for the full-job audit per the Version 4
process. `questions/INDEX.md` updated (total 403 → 417, verified against
the actual UQID count across every topic file, which reconciles exactly).
`01_PAPERS_TRACKER.md` — 2023 row updated to "May/June, V1 + Oct/Nov, V1"
with status "Complete."
**Reason:** Twenty-ninth paper processed — Cambridge O Level 2059/01,
Paper 1, Oct/Nov 2023, single variant. This mark scheme carries no
COVID-19 cancellation notice — a normal series, extracted normally, using
the same generic Table 1/Table 2 levels-of-response format used since
Oct/Nov 2020. This paper introduces a new front-matter page not seen in
earlier sittings: an "annotation stamps" legend table (Tick, ^/Omission,
Cross, DEV, Highlighter, IRRL, L1–L5, NAQ, REP, SEEN, EVAL) explaining how
examiners annotate scripts in RM Assessor — correctly recognised as
examiner-annotation guidance, not question content, and skipped rather
than extracted, consistent with how the existing "Generic Marking
Principles" front-matter pages are handled.

Continuing the procedural change begun in Version 30, every one of this
paper's 14 parts was again presented via AskUserQuestion with a
recommended primary option plus at least one plausible secondary option,
batched across rounds. The user confirmed the recommended (primary) option
in most cases, but explicitly overrode the recommendation once: Q4(c)
("economic factors and increased tension between East and West Pakistan
by 1971") went to **Yahya Khan** rather than the recommended Bangladesh —
consistent with the established precedent in this bank of filing
Bangladesh-creation questions from the perspective of Yahya Khan's regime
(e.g. the May/June 2011, May/June 2013, May/June 2014, Oct/Nov 2015, and
May/June 2016 entries in that topic file).

Final allocations this version: Q1(c) (impact of the Khilafat Movement on
the Muslim community after 1924); Q1(d) (breakdown of Muslim–Hindu
collaboration and the Khilafat Movement's ending); Q2(a) (Hindi–Urdu
Controversy, under Sir Syed Ahmad Khan); Q2(b) (Aurangzeb's domestic
policies, under Decline of the Mughal Empire); Q2(c) (lack of support from
Indian rulers as the main reason the War of Independence ended); Q3(a)
(terms of the Lucknow Pact of 1916); Q3(b) (Hindu community's opposition
to the partition of Bengal, 1905–1911); Q3(c) (WWII and its aftermath
meaning Britain had little interest in the subcontinent's future before
1947 — filed under Multiple Topic Questions (1927–1947) since the MS spans
six distinct named topics: the Cripps Mission, Gandhi-Jinnah Talks, the
Simla Conference, the Cabinet Mission Plan, Direct Action Day, and the 3rd
June Plan); Q4(a) (Benazir Bhutto's foreign policy achievements,
1988–1990); Q4(b) (benefits to Pakistan of UN membership); Q4(c) (economic
factors and East-West Pakistan tension by 1971, under Yahya Khan, per user
override); Q5(a) (impact of the Pressler Amendment on Pakistan in 1990,
under United States of America — first entry with the Amendment's 1990
impact as the sole subject of a question); Q5(b) (why Zulfikar Ali
Bhutto's government ended in 1977); and Q5(c) (whether Pakistan
successfully implemented a new constitution by 1973, under Zulfiqar Ali
Bhutto).

Several entries in this paper are substantively near-duplicate content of
earlier entries already in this bank, each reproduced separately and
verbatim as its own distinct instance: Q1(c)/Q1(d) (Khilafat Movement
ending), Q2(a) (Hindi–Urdu Controversy), Q2(b) (Aurangzeb's policies),
Q3(a) (Lucknow Pact terms), Q4(a) (Benazir's foreign policy), Q4(b) (UN
membership benefits), Q5(a) (Pressler Amendment), Q5(b) (Bhutto's 1977
downfall), and Q5(c) (1973 Constitution) all parallel earlier entries in
their respective topic files. No source anomalies of note this version;
question and mark-scheme text reproduced exactly as printed. All 14 parts
were present and extracted; none skipped.

**2023 is now Complete** (May/June and Oct/Nov both done). Total: 417
questions across 29 papers. Remaining in this batch: 2024 May/June and
Oct/Nov, then 2025 May/June and Oct/Nov papers for 2059/01 (14-part
pattern), still to come.
**Date:** 2026-07-21
