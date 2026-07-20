# PROJECT MEMORY & HANDOFF FILE
## Cambridge Pakistan Studies Topical Question Bank Builder

**Purpose of this document:** This is the complete, self-sufficient memory of this project. If every prior conversation is lost, a brand-new Claude session should be able to read ONLY this file and continue the work with virtually zero loss of context. Read this entire document before doing anything else.

**Last updated:** 2026-07-19, after processing 6 papers (90 questions), end of Version 9.

**Repository:** `mhariarashid1990/claude-code` (GitHub) — this is a personal project repo belonging to the user, unrelated to Anthropic's actual claude-code project; it was empty before this project began.

**Branch:** `claude/cambridge-pakistan-studies-qbank-k6fwd8` — all work happens here. Do not create a new branch unless told to, and never push to any other branch without explicit permission.

**Local working directory (in this remote environment):** `/home/user/claude-code`

---

## 1. PROJECT OVERVIEW

### Objective
Build a publication-quality, commercially-viable **topical past-paper question bank** for two Cambridge syllabuses, by extracting every required question and its official mark scheme **verbatim** from uploaded PDF mark schemes, classifying each into a fixed topic taxonomy, and maintaining a fully auditable database as markdown files in this git repo.

### Exam boards / papers in scope
- **Cambridge O Level Pakistan Studies — History & Culture (2059/01)**
- **Cambridge IGCSE Pakistan Studies — History & Culture (0448/01)**

### Year range in scope
**2010–2025** (originally stated as 2009–2025 by the user, then explicitly corrected to 2010–2025 — see Section 14 Session Timeline, and Section 11 Permanent Decisions). 2009 is fully out of scope.

### Variants
Whatever variant/component number is actually printed on the source paper — never assumed or invented. So far every 2059/01 paper processed has been a single-variant paper (Variant 1, no separate variant digit on the paper). One paper (2013) had a second, distinct component: **2059/41**, a Pakistan-only security-breach resit — see Section 5.

### End goal / deliverable
A complete topical question bank where every extracted question has:
- Verbatim question text
- Verbatim official mark scheme
- Unique Question ID (UQID)
- Full metadata (year, session, variant, paper, question number, part, marks)
- Primary Topic (exactly one) + optional Secondary Tags
- Confidence rating / allocation method
- Full audit trail and version history

This will eventually become a commercial-quality print/digital topical revision book for "Learn with Haris" (the user's tutoring brand — see Section 12).

### Who is running this
The user is **Muhammad Haris Rashid**, an O Level/IGCSE educator (Pakistan Studies, Islamiyat, Geography) and Deputy Director at Benchmark School System, running the brand "Learn with Haris." He is meticulous, detail-oriented, and has explicitly rejected any automation shortcuts that could introduce classification errors — see Section 4 Rules and Section 11 Permanent Decisions.

---

## 2. FULL CONVERSATION MEMORY (chronological instructions/corrections)

1. **Initial master prompt** (see Section 3 for full text) — established the entire system: roles, golden rules, extraction rules by year, UQID format, classification taxonomy, audit layers, error log, version control, commands, operating procedure.
2. User uploaded no papers initially → Claude built the full scaffold (folder structure, taxonomy docs, empty topic files, tracker, audits, version history) and pushed it, explaining nothing could be extracted without a real source document (Golden Rule 5).
3. **Correction:** "THE YEARS THAT I TOLD YOU WERE 2009 TO 2014 FOR THE FIRST PART... CHANGE THE FIRST PART TO 2010 TO 2014." → First extraction-pattern range corrected from 2009–2014 to 2010–2014 everywhere (README, EXTRACTION_RULES.md, papers tracker, coverage audit). 2009 fully removed from project scope. Logged as Version 2.
4. First real paper uploaded: `2059_s10_ms_1.pdf` (2059/01, May/June 2010). Claude asked two clarifying questions before extracting (variant number — none printed on paper; and confirmation to treat the MS's reprinted question text as verbatim source since no separate QP was supplied) and two topic-overlap questions (Wardha Scheme, Canal Water Dispute). All 15 parts extracted and auto-allocated for Very-High-confidence items (this was the ORIGINAL workflow, later overridden — see #6 below). Logged as Version 3.
5. User asked: **"CAN I UPLOAD MORE THAN ONE PAPER AND IF YES, HOW MANY, SO THAT YOU DONT HALUCINATE AND ITS SAFE?"** → Claude explained hallucination risk is not affected by batch size (every PDF page is read in full regardless), but recommended **2–3 papers per upload** as a practical sweet spot for reviewability given the volume of clickable decisions the new workflow (see #6) generates. No hard limit — user can upload more if willing to answer more questions.
6. **Major workflow-changing correction, given immediately after the first paper's results were shown:** *"OKAY! YOU DONT HAVE TO USE YOUR BRAIN! ONCE YOU GET THE PAPER, ASK ME WHERE TO FIT EACH QUESTION PART WITH A DROP DOWN CLICKABLE OPTION. RUN THE AUDIT ONCE OUR UPLOAD JOB IS 100 COMPLETED FOR ALL PAPERS!"** → This permanently changed two things (logged as Version 4, and this is now **the standing operating procedure — never revert to the old behavior**):
   - **Never auto-classify, ever**, regardless of confidence level. Every single extracted question part — no exceptions, not even "obviously correct" ones — must be presented as a clickable multiple-choice question (via the `AskUserQuestion` tool) with Suggested Primary Topic first, then plausible alternates, then "Unsure / allocate elsewhere." Allocation only happens after the user's explicit pick.
   - **Audits are not refreshed per paper.** `02_AUDITS/*.md` is left untouched after each paper; only `questions/INDEX.md`, `01_PAPERS_TRACKER.md`, and `04_VERSION_HISTORY.md` are updated per paper. The full six-layer audit is only run once, in one pass, when the **entire** upload job (every required paper, 2010–2025, both 2059/01 and 0448/01) is 100% extracted and allocated.
   - `00_SYSTEM/GOLDEN_RULES.md` Rule 2 and `00_SYSTEM/COMMANDS.md` were rewritten to reflect this permanently.
7. Second paper uploaded: `2059_s11_ms_1.pdf` (2059/01, May/June 2011). Processed under the new workflow — 4 rounds of clickable-option questions (4+4+4+3 = 15) then allocation. One question (Iqbal vs Rehmat Ali comparison) had no matching topic; user responded **"CREATE ANOTHER TOPIC IN SECTION 2 WITH THE NAME: IQBAL, REHMAT ALI & JINNAH FOR PAKISTAN"** → new taxonomy topic #29 created (this exercised the "Future Flexibility" clause of the master prompt). Another question (Bangladesh creation) — user chose **"ADD THIS IN 'YAHYA KHAN'"** overriding the recommended "Bangladesh" topic — this became a **recurring precedent** applied consistently to every subsequent Bangladesh-creation-themed question except one explicit exception in the 2014 paper (see Section 5, precedent list). Logged as Version 5.
8. Four more papers uploaded together in one message: `2059_s12_ms_1.pdf`, `2059_s13_ms_1.pdf`, `2059_s13_ms_41.pdf`, `2059_s14_ms_1.pdf`. Claude processed them **one full paper at a time** (extract → 4 rounds of clickable questions → write all 15 entries → update INDEX/tracker/version history → commit → push → move to next paper), exactly as promised when discussing batch size. Logged as Versions 6, 7, 8, 9 respectively.
   - One `AskUserQuestion` tool call failed transiently with `AbortError: Tool permission stream closed before response received` — it was simply retried with the identical payload and succeeded. Not a data-loss event, just noted here so a future session doesn't panic if it recurs.
9. **This handoff file was requested** after Version 9 was committed and pushed — i.e., after 90 questions across 6 papers were fully processed and the 2010–2014 extraction-pattern era for 2059/01 was completed.

---

## 3. ALL PROMPTS (verbatim, in order)

### 3.1 — The Master Prompt (original, governing document — full text)

This is the single most important prompt in the project. It has NOT been superseded in its entirety — only specific clauses have been amended (see Section 11 Permanent Decisions for the diff). Reproduced in full below because every future session must operate under it:

> MASTER PROMPT – Cambridge Pakistan Studies Topical Question Bank Builder
>
> **ROLE:** You are not acting as a normal AI assistant. You are working as a professional team of Cambridge assessment specialists to build a publication-quality topical past paper resource for: Cambridge O Level Pakistan Studies – History & Culture (2059/01); Cambridge IGCSE Pakistan Studies – History & Culture (0448/01). This project will eventually become a commercial-quality topical book. Accuracy is more important than speed. Never sacrifice accuracy for efficiency.
>
> **YOUR TEAM:** You are simultaneously performing the role of: 1. Senior Cambridge Data Extraction Specialist, 2. Cambridge Curriculum & Syllabus Expert, 3. Question Classification Specialist, 4. Metadata & Database Architect, 5. Quality Assurance Auditor, 6. Error Detection Specialist, 7. Publication Designer, 8. Version Control Manager. Each specialist has an independent responsibility. Never invent information. Never guess.
>
> **PROJECT OBJECTIVE:** I will upload past papers and official mark schemes one paper at a time. Your job is to: 1. Extract every required question. 2. Extract the corresponding official mark scheme. 3. Preserve everything verbatim. 4. Recommend the most suitable topical allocation. 5. Ask me whenever there is uncertainty. 6. Maintain a complete audit trail. 7. Continue until every required paper from 2009–2025 has been processed. *(Note: year range later corrected to 2010–2025 — see Section 11.)*
>
> **GOLDEN RULES** (override every other instruction):
> - Rule 1: Never rewrite. Never simplify. Never paraphrase. Never improve wording. Questions and mark schemes must remain 100% verbatim.
> - Rule 2: Never classify automatically if confidence is not extremely high. Instead stop. Ask me. Wait for my decision. *(Note: superseded — see Section 11, now "never classify automatically, ever.")*
> - Rule 3: Never skip a question. Every required question must appear exactly once.
> - Rule 4: Never duplicate a question. One question = one permanent location.
> - Rule 5: Never invent missing text. If a page is unclear or missing, ask me.
> - Rule 6: If any ambiguity exists, ASK. Never assume.
>
> **PAPER EXTRACTION RULES:**
> - Papers 2009–2014 *(now 2010–2014)*: Extract ALL of Q1(a)(b)(c), Q2(a)(b)(c), Q3(a)(b)(c), Q4(a)(b)(c), Q5(a)(b)(c). Extract the official mark scheme for every extracted question.
> - Papers 2015–2025: Paper pattern changed. DO NOT collect Q1(a), Q1(b). Collect Q1(c), Q1(d). Also collect Q2(a)(b)(c), Q3(a)(b)(c), Q4(a)(b)(c), Q5(a)(b)(c). Extract the official mark scheme verbatim.
>
> **EXTRACTION FORMAT** — every extracted question must contain: Unique Question ID (auto-generated), Year, Session, Variant, Paper, Question Number, Part, Marks, Question (verbatim), Official Mark Scheme (verbatim), Suggested Primary Topic, Secondary Tags, Confidence Level, Allocation Status, Audit Status, Version Number.
>
> Example: `UQID: PK2059-MJ-2018-V2-Q3B` / Year: 2018 / Session: May/June / Variant: 2 / Paper: 2059/01 / Question: 3 / Part: (b) / Marks: 7 / Question: (Verbatim) / Official Mark Scheme: (Verbatim) / Suggested Topic: Ayub Khan / Secondary Tags: Importance Reforms Foreign Policy / Confidence: High / Status: Pending User Approval.
>
> **CHAPTER ALLOCATION FRAMEWORK** — see Section 16 Knowledge Base for the full current taxonomy (57 topics across 4 sections, including one user-created addition).
>
> **CLASSIFICATION RULES:** For every question provide Suggested Primary Topic (one only) and optional Secondary Tags (examples: Causes, Importance, Consequences, Political, Economic, Religious, Educational, Leadership, Successes, Failures, Comparison, Features, Reforms, Constitution, Foreign Policy, Domestic Policy).
>
> **IF A QUESTION OVERLAPS MULTIPLE CHAPTERS:** DO NOT decide automatically. Display Suggested Primary Topic, Other Possible Topics, then present clickable options, e.g.: "○ Allocate to Ayub Khan / ○ Allocate to Yahya Khan / ○ Allocate to Multiple Regime Questions / ○ Allocate elsewhere (specify) / ○ Unsure." Then STOP and wait for a decision. *(This mechanic was later extended, per the Version-4 correction, to apply to EVERY question part, not just overlapping ones.)*
>
> **AUDIT SYSTEM** — six layers: Audit 1 Extraction Audit (papers uploaded, questions extracted, remaining, missing), Audit 2 Allocation Audit (allocated/pending/needs review/rejected), Audit 3 Duplicate Audit (duplicate questions/mark schemes/near duplicates), Audit 4 Metadata Audit (missing year/session/variant/marks/topic/mark scheme), Audit 5 Coverage Audit (questions per topic, weak/heavy coverage, missing years, topic frequency), Audit 6 Final QA Audit (no missing questions, no missing mark schemes, no duplicates, no broken metadata, ready for publication). *(Per Version 4, these are now only run once at 100% job completion, not per paper.)*
>
> **ERROR LOG:** Whenever an error occurs, create: Error ID, Paper, Question, Issue, Status, Resolution, Date Fixed.
>
> **VERSION CONTROL:** Every major update creates a new version recording: Questions added, Questions moved, Audit updates, Reason, Date.
>
> **INTERACTION RULES:** Whenever confidence is below "Very High," STOP. Ask me. Present clickable choices. Never continue automatically. *(Superseded — now ALWAYS ask, regardless of confidence — see Section 11.)*
>
> **FUTURE FLEXIBILITY:** During the project the user may create new chapters, rename chapters, merge chapters, split chapters, move questions, add new tags, introduce new classifications. The system must support all of these without losing original question, mark scheme, metadata, audit history, or version history.
>
> **USER COMMANDS:** Extract, Recommend, Allocate, Review, Audit, Search, Move, Compare, Export (see Section 16 for updated definitions).
>
> **FINAL DELIVERABLE:** A professional Cambridge topical question bank where every question contains: Verbatim Question, Verbatim Official Mark Scheme, Unique Question ID, Year, Session, Variant, Paper, Question Number, Part, Marks, Primary Topic, Secondary Tags, Confidence Rating, Allocation History, Audit History, Version History, Search Metadata, Cross References.
>
> **OPERATING PROCEDURE** for every uploaded paper (updated version — see Section 9 Current Methodology for the exact current sequence, which differs from the original in steps 6–9).

### 3.2 — Follow-up correction prompts (verbatim)

1. *"OKAY! YOU DONT HAVE TO USE YOUR BRAIN! ONCE YOU GET THE PAPER, ASK ME WHERE TO FIT EACH QUESTION PART WITH A DROP DOWN CLICKABLE OPTION. RUN THE AUDIT ONCE OUR UPLOAD JOB IS 100 COMPLETED FOR ALL PAPERS!"* — the single most important standing-instruction change in the project. See Section 2 item 6 and Section 11.
2. *"CAN I UPLOAD MORE THAN ONE PAPER AND IF YES, HOW MANY, SO THAT YOU DONT HALUCINATE AND ITS SAFE?"* — see Section 2 item 5 for the answer given (2–3 recommended, no hard limit, batch size doesn't affect accuracy).
3. *"CREATE ANOTHER TOPIC IN SECTION 2 WITH THE NAME: IQBAL, REHMAT ALI & JINNAH FOR PAKISTAN"* — exercised the taxonomy Future Flexibility clause; new topic #29 created permanently.
4. *"ADD THIS IN 'YAHYA KHAN'"* — established the Bangladesh-creation → Yahya Khan precedent (see Section 5).
5. *"THE YEARS THAT I TOLD YOU WERE 2009 TO 2014 FOR THE FIRST PART AND 2015 TO 2025 IN THE SECOND HALF. CHANGE THE FIRST PART TO 2010 TO 2014."* — year-range correction (see Section 2 item 3).

### 3.3 — This handoff-generation prompt

The current instruction ("Create a Complete Project Memory & Handoff File...") requested this exact document, with 17 mandatory sections, explicit non-summarization requirements, and a final quality checklist. This document is the direct output of that request.

---

## 4. RULES (complete, current, governing)

### 4.1 Golden Rules (from `00_SYSTEM/GOLDEN_RULES.md` — current text)
1. **Never rewrite.** Never simplify, paraphrase, or improve wording. Questions and mark schemes must remain 100% verbatim, exactly as printed in the official Cambridge document.
2. **Never classify automatically — ever.** Regardless of confidence level, every extracted question part is presented with clickable topic options and the allocation waits for the user's choice before it is written anywhere. *(User directive, 2026-07-19 — supersedes any "Very High confidence" auto-allocate language elsewhere.)*
3. **Never skip a question.** Every required question (per the year rules) must appear exactly once.
4. **Never duplicate a question.** One question = one permanent location.
5. **Never invent missing text.** If a page is unclear, cropped, or missing, stop and ask rather than guessing or reconstructing.
6. **If any ambiguity exists, ASK.** Never assume.
- Accuracy is more important than speed. Never sacrifice accuracy for efficiency.

### 4.2 Extraction Rules by Year (from `00_SYSTEM/EXTRACTION_RULES.md`)
- **2010–2014:** Extract ALL of Q1(a)(b)(c), Q2(a)(b)(c), Q3(a)(b)(c), Q4(a)(b)(c), Q5(a)(b)(c) = **15 parts per paper.** Full mark scheme for each.
- **2015–2025:** DO NOT collect Q1(a) or Q1(b). Collect Q1(c), Q1(d), Q2(a)(b)(c), Q3(a)(b)(c), Q4(a)(b)(c), Q5(a)(b)(c) = **14 parts per paper.** Full mark scheme for each.
- Both 2059/01 and 0448/01 follow the same pattern for their respective year ranges — confirm paper code and year before applying a rule set; if unclear or the paper doesn't match the expected pattern, ask before extracting.

### 4.3 Verbatim / source-fidelity rules (established through practice)
- Only the **official mark scheme (MS)** PDF has been supplied for every paper so far — no separate question paper (QP) has been uploaded. Cambridge MS documents from this era reprint the full question text verbatim above the marking guidance, so the question text is extracted directly from the MS. **User explicitly confirmed this is acceptable** ("Use MS question text as verbatim (Recommended)") the first time this was raised, and it has not been re-asked since — treat it as standing permission, but continue to log in each entry's Audit Status that the source was MS-only.
- When the source document itself contains an internal inconsistency, typo, or non-standard mark band (e.g., a LEVEL band printed as `[9–10]` where every other equivalent question in the syllabus prints `[9–13]`; or a scheme name spelled differently between two papers, e.g. "Wardha Scheme" vs "Widdia Mander Scheme"), it is **reproduced exactly as printed** and flagged in the Audit Status field — **never silently corrected.**
- When a mark bracket (e.g. `[7]`) is not printed next to a question stem in the source (this happened for several (b) and (c) parts in the 2012 paper), the mark value is **inferred** from the standard level-band structure (3 levels topping out at 7 = a 7-mark question; 5 levels topping out at 14 = a 14-mark question) and this inference is noted in Audit Status. This is not treated as "inventing text" because it doesn't touch question/mark-scheme content — only a numeric metadata field, using a pattern that is 100% consistent across every paper processed so far.

### 4.4 Classification / allocation rules
- Every question belongs to **exactly one** Primary Topic. Optional free-text Secondary Tags may be added for search (examples: Causes, Importance, Consequences, Political, Economic, Religious, Educational, Leadership, Successes, Failures, Comparison, Features, Reforms, Constitution, Foreign Policy, Domestic Policy).
- A question must **never** physically appear in more than one topic file.
- **[SUPERSEDED — see 4.5]** Original rule: only overlapping/ambiguous questions get clickable options; Very-High-confidence questions may auto-allocate.
- New topics may be created, and existing topics renamed/merged/split, per the master prompt's "Future Flexibility" clause — but this always requires an explicit user instruction (as happened once, for topic #29), never an autonomous decision by Claude.

### 4.5 **CURRENT STANDING WORKFLOW RULE (overrides 4.4's original allocation logic) — from `00_SYSTEM/COMMANDS.md` and `00_SYSTEM/GOLDEN_RULES.md` Rule 2**
> For every single extracted question part — no exceptions — present clickable Primary Topic options (Suggested Primary Topic first, then other plausible topics, then "Allocate elsewhere / Unsure") via the `AskUserQuestion` tool, and wait for the user's explicit pick before writing the allocation anywhere. This applies **regardless of confidence level**, even for questions with an obvious, unambiguous, exact-name topic match. Never auto-allocate.

Practically, this means every paper (15 parts for 2010–2014-pattern papers, 14 for 2015–2025-pattern papers) requires **4 rounds of `AskUserQuestion` calls** (the tool allows a maximum of 4 questions per call), asked in Q-number order, before any file is written.

### 4.6 Audit-timing rule (current standing rule)
> The six audit layers (`02_AUDITS/*.md`) are **not** refreshed after each individual paper. Per paper, only `questions/INDEX.md` (topic counts), `01_PAPERS_TRACKER.md` (year/session completion status), and `04_VERSION_HISTORY.md` (new version entry) are updated. The full six-layer audit is run **once, in full**, only when the **entire** upload job — every required paper for 2010–2025, both 2059/01 and 0448/01 — is 100% extracted and allocated.

**⚠️ IMPORTANT FOR THE NEXT SESSION:** `02_AUDITS/*.md` currently reflects state as of **Version 3 only** (1 paper, 15 questions) — it has been frozen and NOT updated since the workflow change at Version 4. Do not read `02_AUDITS/` as current status. The live, trustworthy status sources are `questions/INDEX.md` and `01_PAPERS_TRACKER.md`.

### 4.7 UQID / naming rules
Format: `PK<PAPER>-<SESSION>-<YEAR>-V<VARIANT>-Q<NUM><PART>`
- `<PAPER>`: `2059` or `0448`
- `<SESSION>`: `MJ` (May/June), `ON` (Oct/Nov), `FM` (Feb/Mar)
- `<YEAR>`: four digits
- `<VARIANT>`: variant/component number as printed on the paper (e.g. `1`, `41` — note `41` was used for the 2059/41 component, not a "variant 41" of paper 01; treat differently-numbered components as genuinely distinct papers, not variants of one another)
- `<NUM><PART>`: e.g. `Q3B`
- Example: `PK2059-MJ-2018-V2-Q3B`

### 4.8 File/folder naming rules (established in practice, not explicitly stated by user but consistently applied)
- Topic files: `NN-kebab-case-topic-name.md` inside the relevant section folder.
- Section folders: `section-1-mughal-decline-british-rule/`, `section-2-creation-of-pakistan/`, `section-3a-nationhood/`, `section-3b-international-relations/`.
- System docs live in `00_SYSTEM/`.
- Numbered top-level files (`01_PAPERS_TRACKER.md`, `02_AUDITS/`, `03_ERROR_LOG.md`, `04_VERSION_HISTORY.md`) preserve a fixed reading order.

### 4.9 Git/commit rules (established in practice)
- One commit per paper processed (extraction + allocation + INDEX/tracker/version-history update), pushed immediately after each commit — never batch multiple papers into one commit.
- Commit messages describe what was extracted/changed, never reference the AI model identity.
- Never force-push, never amend, never push to a branch other than `claude/cambridge-pakistan-studies-qbank-k6fwd8` without explicit permission.
- No pull request has been created — none was requested. Do not create one unless explicitly asked.

---

## 5. UPLOADED FILES — COMPLETE INVENTORY

All 6 files uploaded so far are **official Cambridge mark schemes (MS) only** — no question papers (QP) have been supplied for any paper. All were for **2059/01 / O Level Pakistan Studies**, all **May/June (MJ) session**, all **single-variant** (Variant 1) except one distinct component (41).

| # | Filename (as uploaded) | Paper/Component | Year/Session | Variant | Parts | Status | UQID prefix |
|---|---|---|---|---|---|---|---|
| 1 | `2059_s10_ms_1.pdf` | 2059/01 | May/June 2010 | 1 | 15/15 | ✅ Fully processed — Version 3 | `PK2059-MJ-2010-V1-*` |
| 2 | `2059_s11_ms_1.pdf` | 2059/01 | May/June 2011 | 1 | 15/15 | ✅ Fully processed — Version 5 | `PK2059-MJ-2011-V1-*` |
| 3 | `2059_s12_ms_1.pdf` | 2059/01 | May/June 2012 | 1 | 15/15 | ✅ Fully processed — Version 6 | `PK2059-MJ-2012-V1-*` |
| 4 | `2059_s13_ms_1.pdf` | 2059/01 (**original series**, sat by candidates **outside** Pakistan) | May/June 2013 | 1 | 15/15 | ✅ Fully processed — Version 7 | `PK2059-MJ-2013-V1-*` |
| 5 | `2059_s13_ms_41.pdf` | **2059/41** (Pakistan-only **security-breach resit**, distinct question set from paper 01) | May/June 2013 | 41 (own component code, not a "variant 41" of paper 01) | 15/15 | ✅ Fully processed — Version 8 | `PK2059-MJ-2013-V41-*` |
| 6 | `2059_s14_ms_1.pdf` | 2059/01 | May/June 2014 | 1 | 15/15 | ✅ Fully processed — Version 9 | `PK2059-MJ-2014-V1-*` |

**Important note on files #4 and #5:** Both PDFs carried a front-matter notice: *"Due to a security breach we required all candidates in Pakistan who sat the paper for 2059/01 to attend a re-sit examination in June 2013. Candidates outside of Pakistan sat only the original paper and were not involved in a re-sit."* File #4 is the original 2059/01 paper (title page reads "2059/01 Paper 1"); file #5 is the actual resit paper, formally numbered as component **2059/41** (title page reads "2059/41 Paper 41"), with its own completely distinct question content — not a duplicate. Both were processed as fully separate papers with separate UQID variant tags (`V1` vs `V41`).

### Remaining work per file: none — all 6 uploaded files are fully processed (extracted, all 15 parts allocated per user's clickable choices, committed, pushed). No further action needed on these specific files.

---

## 6. WORK ALREADY COMPLETED

### 6.1 Scaffold (Version 1)
- **Objective:** Build the entire system infrastructure before any real paper content existed.
- **Output:** Full repo structure — `README.md`, `00_SYSTEM/` (5 docs: GOLDEN_RULES, EXTRACTION_RULES, CLASSIFICATION_FRAMEWORK, QUESTION_TEMPLATE, COMMANDS), `01_PAPERS_TRACKER.md`, `02_AUDITS/` (6 files, all zero-state), `03_ERROR_LOG.md`, `04_VERSION_HISTORY.md`, `questions/INDEX.md`, and **56 empty topic files** across 4 section folders.
- **Status:** ✅ Complete. Committed as `a201708`.
- **Decision made:** Since no papers had been uploaded, nothing was invented — only structure was built (Golden Rule 5 compliance).

### 6.2 Year-range correction (Version 2)
- **Objective:** Fix the 2009–2014 → 2010–2014 extraction-pattern boundary per user correction.
- **Output:** Updated `EXTRACTION_RULES.md`, `README.md`, `01_PAPERS_TRACKER.md` (2009 row removed), `02_AUDITS/05_coverage_audit.md`.
- **Status:** ✅ Complete. Committed as `9189359`.

### 6.3 Paper 1 — 2059/01 MJ2010 (Version 3)
- **Objective:** First real extraction under the (then-current) confidence-based auto-allocate workflow.
- **Output:** 15 question entries written across 15 topic files; `questions/INDEX.md`, `01_PAPERS_TRACKER.md`, all 6 files in `02_AUDITS/` updated (last time audits were touched); `04_VERSION_HISTORY.md` Version 3 entry.
- **Status:** ✅ Complete. Committed as `80c57e2`.
- **Notes/decisions:** Two topic-overlap questions resolved by user choice (Wardha Scheme → Congress Rule 1937–1939; Canal Water Dispute → Initial Problems of Pakistan). "Qafq Ordinances" anomaly first observed and preserved verbatim here.

### 6.4 Workflow-change commit (Version 4)
- **Objective:** Implement the user's "clickable options for every part, defer audits to 100%" directive.
- **Output:** Rewrote `00_SYSTEM/GOLDEN_RULES.md` (Rule 2) and `00_SYSTEM/COMMANDS.md` (Recommend/Allocate/Audit definitions, per-paper workflow steps). No question content changed.
- **Status:** ✅ Complete. Committed as `8b38007`.

### 6.5 Paper 2 — 2059/01 MJ2011 (Version 5)
- **Objective:** First paper processed fully under the new clickable-only workflow.
- **Output:** 15 entries across 15 topic files (one brand-new: topic #29). `CLASSIFICATION_FRAMEWORK.md` updated with new topic #29. `questions/INDEX.md`, `01_PAPERS_TRACKER.md`, `04_VERSION_HISTORY.md` updated (no audit refresh).
- **Status:** ✅ Complete. Committed as `99d1f27`.
- **Notes/decisions:** New topic "Iqbal, Rehmat Ali & Jinnah for Pakistan" (#29, Section 2) created per explicit user instruction. Bangladesh-creation → Yahya Khan precedent established here.

### 6.6 Paper 3 — 2059/01 MJ2012 (Version 6)
- **Objective:** Continue clickable-only workflow.
- **Output:** 15 entries (one landed in the new topic #29 as its second-ever entry: "Who was Chaudri Rehmat Ali?"). Two questions with no exact-name topic resolved by user choice (constitutional crisis 1954–55 → Malik Ghulam Muhammad; Pakistani migration → United Kingdom & the Commonwealth).
- **Status:** ✅ Complete. Committed as `dc60220`.
- **Notes:** Two more verbatim source anomalies preserved (`[9–10]` mark band; `[3–6]` overlapping band).

### 6.7 Paper 4 — 2059/01 MJ2013 original series (Version 7)
- **Objective:** Continue clickable-only workflow; this is the paper sat by candidates **outside** Pakistan.
- **Output:** 15 entries. Simla Agreement (1972, distinct from the 1945 "Simla Conference" taxonomy topic) → Zulfiqar Ali Bhutto. Three-leader comparison (Liaquat Ali Khan/Malik Ghulam Muhammad/Iskander Mirza) → new first-ever entry in "Multiple Regime Questions (1947–1999)."
- **Status:** ✅ Complete. Committed as `0d911b4`.

### 6.8 Paper 5 — 2059/41 MJ2013 Pakistan-only resit (Version 8)
- **Objective:** Process the distinct resit component, tracked separately from paper 4.
- **Output:** 15 entries with UQIDs using `V41` (not `V1`). Two brand-new topic files got their first-ever entries: "Simla Deputation (1906)" and "Morley–Minto Reforms (1909)." "Multiple Topic Questions (1927–1947)" went from empty to 2 entries.
- **Status:** ✅ Complete. Committed as `4c3a72c`. `01_PAPERS_TRACKER.md` — 2013 row marked fully **Complete** here (both components done).
- **Notes:** "Widdia Mander Scheme" vs "Wardha Scheme" naming anomaly preserved verbatim.

### 6.9 Paper 6 — 2059/01 MJ2014 (Version 9) — **final paper of this batch, completes the 2010–2014 era**
- **Objective:** Complete the last paper in the 2010–2014 extraction-pattern range.
- **Output:** 15 entries. Three brand-new topic files got their first-ever entries: "Elections of 1937," "Reversal of the Partition of Bengal (1911)," "Cabinet Mission Plan." Notable divergence from precedent: Kargil Conflict question → **India and the Kashmir Issue** (not Nawaz Sharif, unlike the equivalent 2013/01 question), because this stem does not name a specific Prime Minister. Zulfiqar Ali Bhutto's execution question → **General Zia-ul-Haq** (not Zulfiqar Ali Bhutto), because the mark scheme's final point centers on Zia's motive.
- **Status:** ✅ Complete. Committed as `7a9acd8`. `01_PAPERS_TRACKER.md` — 2014 row marked **Complete**.
- **Milestone:** With this paper, **2010, 2011, 2012, 2013 (both components), and 2014 are all marked Complete** for 2059/01. **Total: 90 questions extracted and allocated across 6 papers**, 100% per user's explicit clickable choices, zero auto-classification.

### 6.10 Cumulative totals as of now
- **90 questions** allocated across **51 of 57 topics** touched at least once (see `questions/INDEX.md` for exact per-topic counts).
- **9 version entries** in `04_VERSION_HISTORY.md`.
- **1 new taxonomy topic** created beyond the original 56 (topic #29).
- **9 git commits**, all pushed to `claude/cambridge-pakistan-studies-qbank-k6fwd8`.

---

## 7. REMAINING WORK (complete roadmap)

### 7.1 Immediate next step
Wait for the user to upload the next batch of papers. No action is needed until then.

### 7.2 Full roadmap, in recommended order

1. **2059/01, remaining 2010–2014-pattern gap-fill (if any).** Confirm with the user whether there are other sessions (Oct/Nov, Feb/Mar) or other variants for 2010–2014 that also need processing — the current tracker only reflects May/June, Variant 1 (or component 41) for each of these years. Do not assume May/June is the only session that exists for a given year; ask if uncertain, per Golden Rule 6.
2. **2059/01, 2015–2025 (14-part pattern: Q1c/Q1d + Q2–5 a/b/c).** This is a **different extraction pattern** — Q1(a) and Q1(b) are explicitly excluded starting 2015. Watch for this when the first 2015+ paper arrives; do not apply the 15-part pattern by habit.
3. **0448/01 (IGCSE), 2010–2025, both extraction patterns as applicable.** Not started at all yet — every row in the IGCSE table of `01_PAPERS_TRACKER.md` still reads "Not started." Confirm the same year-range split (2010–2014 = 15-part, 2015–2025 = 14-part) applies to IGCSE — the master prompt implies it does, but confirm rather than assume if it seems inconsistent with an actual paper's structure (Golden Rule 6).
4. **Final full six-layer audit** — only once every required paper across both papers and the full 2010–2025 range is 100% extracted and allocated. This is a large, one-time pass across `02_AUDITS/*.md` — do not attempt it prematurely; check with the user if unsure whether "100% complete" has been reached.
5. **Export** — generate the final publication-ready topical collection once everything is allocated and audited (see the `Export` command in Section 16).

### 7.3 Priorities / dependencies
- Steps 1–3 are pure data-entry work (extract → ask → allocate → commit) and can proceed paper-by-paper in any order the user chooses to upload them; no technical dependency between years or papers.
- Step 4 (final audit) **depends on** steps 1–3 being fully complete — do not run it early.
- Step 5 (export) **depends on** step 4 passing.

---

## 8. PROJECT STRUCTURE

```
/home/user/claude-code/                                    (repo root, branch claude/cambridge-pakistan-studies-qbank-k6fwd8)
├── README.md                                               Project overview, workflow summary, "next step" pointer
├── PROJECT_MEMORY.md                                        THIS FILE — read first in any new session
├── 00_SYSTEM/
│   ├── GOLDEN_RULES.md                                     6 golden rules (see Section 4.1)
│   ├── EXTRACTION_RULES.md                                 Year-based extraction patterns (see Section 4.2)
│   ├── CLASSIFICATION_FRAMEWORK.md                         Full 57-topic taxonomy + overlap-handling + future-flexibility clause
│   ├── QUESTION_TEMPLATE.md                                UQID format + per-question field template
│   └── COMMANDS.md                                         Command definitions + current per-paper workflow (post Version 4)
├── 01_PAPERS_TRACKER.md                                    LIVE status table — which year/session/paper is Complete/In progress/Not started
├── 02_AUDITS/                                               ⚠️ FROZEN at Version 3 state — do not trust as current
│   ├── 01_extraction_audit.md
│   ├── 02_allocation_audit.md
│   ├── 03_duplicate_audit.md
│   ├── 04_metadata_audit.md
│   ├── 05_coverage_audit.md
│   └── 06_final_qa_audit.md
├── 03_ERROR_LOG.md                                         Empty so far — no errors logged (source anomalies are logged inline per-question instead, not here)
├── 04_VERSION_HISTORY.md                                   LIVE — 9 version entries, full narrative of every change
└── questions/
    ├── INDEX.md                                             LIVE — per-topic question counts, the fastest way to see current state
    ├── section-1-mughal-decline-british-rule/               6 topic files
    ├── section-2-creation-of-pakistan/                      29 topic files (28 original + 1 user-created: #29)
    ├── section-3a-nationhood/                                11 topic files
    └── section-3b-international-relations/                   11 topic files
```

No temporary files, no generated exports, no PDFs are stored in the repo — source PDFs are uploaded per-session by the user and are not persisted to the repo (only their extracted content is).

---

## 9. CURRENT METHODOLOGY (exact step-by-step, as of Version 9 / current state)

This is the **actual current process** — it differs from the master prompt's original "Operating Procedure" section in steps 6–9 (see Section 11 for the diff).

For each uploaded paper:
1. **Read** the full PDF via the `Read` tool (every page, no skipping).
2. **Identify** paper code, year, session, variant/component from the document's own title page and header — never guess; if the paper doesn't state a variant, treat it as the single/default variant and note this in Audit Status; if genuinely ambiguous, ask.
3. **Determine which extraction pattern applies** (2010–2014 = 15 parts; 2015–2025 = 14 parts) based on the year.
4. **Draft** (internally, not shown to user as a separate step) a Suggested Primary Topic + plausible alternates for every part, using the taxonomy in `CLASSIFICATION_FRAMEWORK.md` and precedent from prior papers (see Section 5's precedent list).
5. **Ask** — present the parts to the user in Q-number order via `AskUserQuestion`, 4 questions per call (so 4 calls for a 15-part paper, i.e. 4+4+4+3), each question showing: the verbatim question text + marks, a "(Recommended)" labelled Suggested Primary Topic, 0–2 plausible alternates, and always an "Unsure / allocate elsewhere" option. **Wait for the user's answer before proceeding to write anything.**
6. **Write** — once all parts have a confirmed topic, read each target topic file (required before editing), then append a full question entry (UQID, all metadata, verbatim question, verbatim mark scheme, Suggested Primary Topic = the user's actual choice, Secondary Tags, Confidence Level = `N/A — allocated by direct user choice`, Allocation Status = Allocated, Audit Status noting source/anomalies/overlap reasoning, Version Number, Allocation History, Cross References to any alternate topics considered).
7. **Update** `questions/INDEX.md` (increment counts + total), `01_PAPERS_TRACKER.md` (mark the year/session Complete or In progress), `04_VERSION_HISTORY.md` (new version entry with full narrative: questions added, topics created if any, audit updates = "None — held for full-job audit," and a detailed Reason paragraph covering every notable decision made in that paper).
8. **Do NOT touch** `02_AUDITS/*.md` — this is deliberate, per the Version 4 rule.
9. **Commit** (one commit per paper, message describing what was extracted) and **push** immediately.
10. **Move to the next paper** if more were uploaded in the same batch, repeating from step 1; otherwise wait for the next upload.

### Quality control / cross-checking applied throughout
- Every `Edit` targeting an existing topic file is preceded by a `Read` of that file in the same or a very recent turn, to avoid overwriting or duplicating content.
- Verbatim text is copied character-for-character from the PDF extraction output, including preserving source-side inconsistencies (see Section 4.3) rather than "fixing" them.
- Marks values are cross-checked against the level-band structure when not explicitly printed.
- After every batch of file edits, a `git status --short` is run before committing to confirm the exact file list matches expectations (no unintended files, none missing).

---

## 10. LESSONS LEARNED

1. **Initial assumption that Very-High-confidence questions could auto-allocate was wrong for this user.** The user wants zero autonomous classification, full stop, regardless of how "obvious" a match seems. This was corrected immediately after the first paper and has held ever since. **Do not revert to auto-allocation under any confidence threshold.**
2. **Audits should not be treated as "keep them always current" by default** — this user explicitly wants them deferred to a single final pass, to reduce overhead on every single paper. Don't over-engineer by refreshing them anyway "to be safe" — that would contradict an explicit instruction.
3. **Cambridge mark schemes sometimes contain internal printing anomalies** (mismatched mark bands, inconsistent scheme names between sittings, missing mark brackets next to question stems). The correct handling, established through practice and never contradicted by the user, is: reproduce exactly as printed, never silently "fix," and flag the anomaly in that entry's Audit Status field.
4. **A paper's title page can reveal that what looks like one exam sitting is actually two distinct papers** (2013 had both 2059/01 and 2059/41 due to a security breach) — always read the front matter of every uploaded PDF carefully; don't assume same-year-same-session papers are duplicates or variants of each other without checking the component code.
5. **Batch uploads don't reduce extraction accuracy** (every PDF is always read in full regardless of batch size) but they do multiply the number of clickable-decision rounds the user must sit through — 2–3 papers per batch was recommended as a practical (not accuracy-driven) sweet spot.
6. **Tool calls can occasionally fail transiently** (`AbortError: Tool permission stream closed before response received` was observed once on an `AskUserQuestion` call) — the correct response is simply to retry the identical call, not to change approach or panic.
7. **No hallucination or missing-question incidents occurred** in this project so far — the disciplined "read full PDF → ask before allocating → verbatim only" process has held up cleanly across 90 questions and 6 papers with zero corrections needed to already-committed content.
8. **When a question stem doesn't repeat context from prior similar questions** (e.g., the 2014 Kargil Conflict question doesn't name a Prime Minister the way the 2013 equivalent did), **do not blindly apply the prior precedent** — re-evaluate based on that specific stem's actual content and present the divergence as an option, letting the user confirm or override. This is exactly what happened correctly with Kargil (→ India/Kashmir, breaking the Nawaz Sharif pattern) and Bhutto's execution (→ Zia, per that specific mark scheme's emphasis).

---

## 11. PERMANENT DECISIONS (must never be forgotten or reverted)

1. **Year range is 2010–2025, not 2009–2025.** 2009 is permanently out of scope. (Corrects the master prompt's original text.)
2. **Never auto-classify, ever — always present clickable options for every single question part**, regardless of confidence level. (Corrects/replaces master prompt Golden Rule 2 and the original "Interaction Rules" section.)
3. **Audits (`02_AUDITS/`) are only run once, in full, at 100% job completion** — not refreshed per paper. Per-paper updates are limited to `questions/INDEX.md`, `01_PAPERS_TRACKER.md`, and `04_VERSION_HISTORY.md`.
4. **Only official mark schemes have been supplied (no QPs) — this is accepted as the extraction source**, with the question text taken verbatim as reprinted within the MS. This was confirmed once explicitly and is standing permission, but every entry's Audit Status still notes "MS only; source QP not separately supplied."
5. **Source-document anomalies/typos are preserved verbatim, never silently corrected** — always flagged in Audit Status instead.
6. **New taxonomy topics may only be created on explicit user instruction**, never autonomously — even when a question clearly has no good existing home, the correct move is to ask, not to invent a topic.
7. **Bangladesh-creation-themed questions default to the "Yahya Khan" topic** (Section 3A) rather than the "Bangladesh" topic (Section 3B), per repeated user confirmation — **but this is a strong precedent, not an absolute rule**; when a stem's actual content diverges (as happened once with the Kargil Conflict question, which doesn't concern Bangladesh's creation at all and doesn't name a PM), re-present the choice rather than blindly applying the precedent.
8. **One commit per paper, pushed immediately** — never batch multiple papers' worth of work into a single commit.
9. **Branch is fixed:** `claude/cambridge-pakistan-studies-qbank-k6fwd8`. Never push elsewhere without explicit permission.
10. **No pull request** has been or should be created unless explicitly requested.

---

## 12. IMPORTANT CONTEXT (things that only existed in conversation memory)

- **Who the user is:** Muhammad Haris Rashid, an O Level/IGCSE tutor in Islamabad/Rawalpindi, Pakistan, running the "Learn with Haris" brand (Instagram: @muhammadharisrashid, YouTube: "Learn with Haris" — never any other name). He is also Deputy Director at Benchmark School System. He teaches Pakistan Studies (2059/0448), Islamiyat (2058/0493), and Geography. This question bank is being built as a future commercial revision resource tied to that brand, and reflects his general standard of wanting AI-assisted work to be exam-board-accurate and never hallucinated (a hard rule he applies across all his Claude projects, e.g. "never invent Quranic verses or Hadith" in his Islamiyat work).
- **Why the clickable-only workflow was adopted over confidence-based auto-allocation:** the user's own words ("YOU DONT HAVE TO USE YOUR BRAIN") indicate a preference for himself remaining the sole classification authority, treating Claude purely as an extraction/formatting engine for this specific decision, even at the cost of significant extra interaction volume. This is a deliberate trade of speed for control, not an oversight to be "optimized away" in a future session.
- **Why audits were deferred to job completion:** explicitly to reduce overhead/noise on every single paper, given how many papers remain (potentially 30+ more papers across both syllabuses and both year-pattern eras). This is a throughput decision, not a quality-reduction — the six-layer audit will still run comprehensively, just once at the end rather than 30+ times.
- **Special case — the 2013 resit:** this is the only instance so far of a single calendar year/session containing two genuinely distinct papers (different component codes, different content) rather than one paper with variants. If this recurs for other years, apply the same handling: separate UQID variant tags, separate tracker line-items, both processed as fully independent papers.
- **Edge case — Kargil Conflict (2014) vs Kargil-adjacent question (2013):** the 2013/01 paper's equivalent question explicitly named Nawaz Sharif in its stem and was allocated to his topic; the 2014 paper's Kargil question does not name a PM and was allocated to India and the Kashmir Issue instead. This is not an inconsistency to "fix" — it correctly reflects that each question's actual stem content, not just its general subject matter, drives topic choice.

---

## 13. FUTURE INSTRUCTIONS FOR THE NEXT SESSION

### Where to continue
Wait for the user to upload the next paper(s). Nothing else is pending. When papers arrive, follow the exact methodology in Section 9.

### What NOT to change without explicit new instruction
- Do not revert to confidence-based auto-allocation.
- Do not start refreshing `02_AUDITS/` per paper.
- Do not rename, merge, or restructure any existing taxonomy topic (including #29) without an explicit user instruction to do so.
- Do not assume the Bangladesh → Yahya Khan precedent applies to every future Bangladesh-adjacent question without re-checking that specific stem's content (see Section 10, lesson 8).
- Do not create a pull request unless asked.
- Do not push to any branch other than `claude/cambridge-pakistan-studies-qbank-k6fwd8`.

### What must always be verified before extracting a new paper
1. Confirm paper code (2059/01 vs 2059/41-style resit vs 0448/01) from the document's own title page — never assume from filename alone (though filenames have been a reliable hint so far, e.g. `_ms_41` correctly signaled the resit component).
2. Confirm year and session from the document's own header — never assume from filename alone (though so far filenames like `s10`, `s11` etc. have reliably meant "summer/May-June" + two-digit year).
3. Confirm which extraction pattern applies (15-part 2010–2014 vs 14-part 2015–2025) based on the confirmed year. **The very next new-pattern paper the user uploads will likely be a 2015+ paper — watch carefully for the Q1(a)/Q1(b) exclusion.**
4. Confirm variant/component number from the paper itself; if none is printed, ask what to use (this was previously answered as "whatever the variant is mentioned on the paper, call it that" — meaning: use exactly what's printed, and if nothing is printed, there is no separate variant to invent).
5. If only an MS is supplied (no QP), this is pre-approved (see Section 11, decision 4) — proceed without re-asking, but keep logging it per-entry.

### What must always be audited / cross-checked per paper (even though the six formal audit layers are deferred)
- Confirm all required parts for that year's pattern are present in the source MS before extraction (Golden Rule 3 — never skip).
- Confirm no question is being written into more than one topic file (Golden Rule 4 — never duplicate).
- Confirm every topic file targeted by an `Edit` has been `Read` first in the current session.
- Confirm `questions/INDEX.md` counts and `01_PAPERS_TRACKER.md` status are updated to match exactly what was written.
- Confirm `git status --short` shows exactly the expected file list before committing.

---

## 14. SESSION TIMELINE (chronological milestones)

1. **Master prompt received** — full system defined, 2009–2025 stated as year range, confidence-based auto-allocate assumed, per-paper audits assumed.
2. **Scaffold built and pushed** (Version 1) — no papers yet uploaded, full infrastructure only.
3. **Year-range correction received and applied** (Version 2) — 2009–2014 → 2010–2014.
4. **First paper uploaded and processed** (Version 3) — 2010, 15 questions, confidence-based auto-allocate workflow used for the only time in this project.
5. **User asked about safe batch upload size** — answered: 2–3 recommended, no hard limit, batch size doesn't affect accuracy.
6. **Major workflow-change instruction received** — clickable-only allocation for every part, audits deferred to 100% completion. Applied immediately (Version 4), permanently overriding the confidence-based approach used in step 4.
7. **Second paper uploaded and processed under new workflow** (Version 5) — 2011, 15 questions; new taxonomy topic #29 created per user instruction; Bangladesh→Yahya Khan precedent established.
8. **Four more papers uploaded together in one message** — 2012, 2013 original, 2013 resit (2059/41), 2014.
9. **Processed one at a time, each fully committed and pushed before starting the next** (Versions 6, 7, 8, 9) — 60 more questions, several more brand-new topic files populated for the first time, several notable precedent-consistent and precedent-divergent decisions.
10. **Milestone reached:** entire 2010–2014 extraction-pattern era for 2059/01 complete — 90 questions, 6 papers, 9 commits.
11. **This handoff document requested and produced** — current point in time.

---

## 15. OPEN QUESTIONS (unresolved — do not invent answers)

1. Are there other sessions (Oct/Nov, Feb/Mar) or other variants for 2059/01 2010–2014 that the user intends to upload, beyond the single May/June Variant-1 (or 2059/41) paper already provided per year? **Not yet asked or answered.**
2. Does the 0448/01 (IGCSE) syllabus follow the identical 2010–2014/2015–2025 extraction-pattern split as 2059/01, or does its pattern change on a different year boundary? **Not yet confirmed — the master prompt implies parity but this has never been tested against an actual IGCSE paper.**
3. Will more resit-style distinct-component situations (like 2059/41 in 2013) recur in other years? **Unknown — handle case-by-case as they're discovered, per the established precedent in Section 5.**
4. What exact final export format/structure is wanted for the "commercial-quality topical book" deliverable (the master prompt's Publication Designer role has not yet been actively exercised)? **Not yet discussed in any detail.**

---

## 16. KNOWLEDGE BASE (long-term reference — read repeatedly)

### 16.1 Full current Classification Framework (57 topics)

**Section 1 — The Decline of the Mughal Empire & the Establishment of British Rule** (file folder: `section-1-mughal-decline-british-rule/`)
1. Decline of the Mughal Empire
2. East India Company
3. Religious Reformers
4. War of Independence (1857)
5. Sir Syed Ahmad Khan
6. Urdu Language Controversy (Languages)

**Section 2 — The Creation of Pakistan (1905–1947)** (file folder: `section-2-creation-of-pakistan/`)
1. Partition of Bengal (1905)
2. Simla Deputation (1906)
3. Creation of the All-India Muslim League
4. Muslim League (1906–1908)
5. Morley–Minto Reforms (1909)
6. Reversal of the Partition of Bengal (1911)
7. Lucknow Pact & First World War
8. Montagu–Chelmsford Reforms & Other Events of 1919
9. Khilafat Movement
10. Delhi Proposals & Simon Commission
11. Nehru Report
12. Jinnah's Fourteen Points
13. Round Table Conferences
14. Government of India Act (1935)
15. Elections of 1937
16. Congress Rule (1937–1939)
17. Day of Deliverance
18. Lahore Resolution (1940)
19. Cripps Mission
20. Quit India Movement
21. Gandhi–Jinnah Talks
22. Simla Conference *(1945 — distinct from "Simla Deputation" #2, 1906, and also distinct from the 1972 "Simla Agreement" which has no dedicated topic and is filed under Zulfiqar Ali Bhutto in Section 3A)*
23. Elections of 1945–46
24. Cabinet Mission Plan
25. Direct Action Day
26. 3rd June Plan
27. Multiple Topic Questions (1905–1926)
28. Multiple Topic Questions (1927–1947)
29. **Iqbal, Rehmat Ali & Jinnah for Pakistan** *(user-created, Version 5, 2026-07-19 — for ideological-contribution questions about Iqbal/Rehmat Ali/Jinnah with no other named home)*

**Section 3A — Nationhood (1947–1999)** (file folder: `section-3a-nationhood/`)
1. Initial Problems of Pakistan & Quaid-e-Azam as Governor-General
2. Liaquat Ali Khan
3. Malik Ghulam Muhammad
4. Iskander Mirza
5. Ayub Khan
6. Yahya Khan
7. Zulfiqar Ali Bhutto
8. General Zia-ul-Haq
9. Benazir Bhutto
10. Nawaz Sharif
11. Multiple Regime Questions (1947–1999)

**Section 3B — International Relations** (file folder: `section-3b-international-relations/`)
1. India and the Kashmir Issue
2. China
3. United States of America (USA)
4. USSR / Russia
5. Iran and Turkey
6. Afghanistan
7. Bangladesh
8. Gulf Countries
9. United Nations & Other World Organisations
10. United Kingdom & the Commonwealth
11. Multiple Topic Questions (International Relations)

### 16.2 Question entry template (exact format used in every topic file)

```markdown
### UQID: PK<PAPER>-<SESSION>-<YEAR>-V<VARIANT>-Q<NUM><PART>

- **Year:** 
- **Session:** May/June | Oct/Nov | Feb/Mar
- **Variant:** 
- **Paper:** 2059/01 | 0448/01 | 2059/41 (etc. — whatever component is printed)
- **Question Number:** 
- **Part:** 
- **Marks:** 
- **Question (Verbatim):**
  > [full verbatim stem + sub-question text, exactly as printed]
- **Official Mark Scheme (Verbatim):**
  > [full verbatim mark scheme, all levels, exactly as printed]
- **Suggested Primary Topic:** [the user's actual final choice]
- **Secondary Tags:** [free text, e.g. Causes, Political]
- **Confidence Level:** N/A — allocated by direct user choice (clickable options), not auto-classified
- **Allocation Status:** Allocated
- **Audit Status:** [notes on MS-only source, any overlap resolved, any verbatim anomaly preserved]
- **Version Number:** [the version this was added in]
- **Allocation History:** Allocated on extraction, Version N, per user selection — no prior moves
- **Cross References:** [links to alternate topics considered, if any, else —]
```

### 16.3 Command definitions (current, from `00_SYSTEM/COMMANDS.md`)
- **Extract** — Extract questions and mark schemes from the uploaded paper, per year rules.
- **Recommend** — Suggest topic(s) and present as clickable options for every part — never auto-allocate, regardless of confidence.
- **Allocate** — Move a question into the user-selected topic, update metadata/indexes/statistics. Does NOT refresh audit layers.
- **Review** — Recheck previous allocations for errors/inconsistencies.
- **Audit** — Display full six-layer status. Only run once, at 100% job completion.
- **Search** — Find questions by year/topic/keyword/marks/paper/tag.
- **Move** — Reassign a question to a different topic, preserving full history.
- **Compare** — Show similar questions across years.
- **Export** — Generate the final topical collection, preserving verbatim wording/metadata.

### 16.4 Precedent decisions quick-reference (for consistent future allocation)

| Question theme | Precedent topic | Notes |
|---|---|---|
| Bangladesh creation (1971), general | Yahya Khan (Section 3A) | Strong precedent, but re-check stem — see Kargil exception |
| Wardha Scheme / Congress education reform | Congress Rule (1937–1939) | Over "Elections of 1937" |
| Canal Water Dispute | Initial Problems of Pakistan & Quaid-e-Azam | Over "India and the Kashmir Issue" |
| Simla Agreement (1972, Bhutto–Indira Gandhi) | Zulfiqar Ali Bhutto (Section 3A) | Distinct from "Simla Conference" (1945) and "Simla Deputation" (1906) topics |
| Comparing 3+ named leaders/events equally | The relevant "Multiple ... Questions" bucket topic | Never force into one single leader/event's topic |
| Constitutional crisis 1954–55 | Malik Ghulam Muhammad | Over Multiple Regime Questions |
| General Pakistani migration/diaspora | United Kingdom & the Commonwealth | Over Gulf Countries, when content is Britain-heavy |
| Ranjit Singh / Anglo-Sikh relations | East India Company | No dedicated topic exists |
| "How did Ayub Khan achieve power" (context-heavy on Iskander Mirza) | Ayub Khan | The question's actual subject, not its scene-setting context, drives topic |
| General education-policy questions (no single leader) | Multiple Regime Questions (1947–1999) | |
| Kargil Conflict, no PM named in stem | India and the Kashmir Issue | Compare: Kargil WITH Nawaz Sharif named in stem → Nawaz Sharif |
| Zulfiqar Ali Bhutto's 1979 execution | General Zia-ul-Haq | When mark scheme's substance centers on Zia's motive rather than Bhutto's actions |

### 16.5 Repo/environment quick facts
- Repo: `mhariarashid1990/claude-code`, branch `claude/cambridge-pakistan-studies-qbank-k6fwd8`.
- Local path in this remote environment: `/home/user/claude-code`.
- 9 commits so far, latest is `7a9acd8`.
- User email: mhariarashid1990@gmail.com.

---

## 17. RECOVERY INSTRUCTIONS

If this is a brand-new Claude session with no memory of this conversation, follow these steps exactly, in order:

1. **Read this entire file first**, top to bottom, before taking any action.
2. **Access the repository** at `mhariarashid1990/claude-code`, branch `claude/cambridge-pakistan-studies-qbank-k6fwd8` (clone or open it — it should already be present at `/home/user/claude-code` if this is a continuation of the same environment; otherwise clone fresh).
3. **Verify current state** by reading `questions/INDEX.md` (live topic counts) and `01_PAPERS_TRACKER.md` (live year/paper completion status) — these two files are always kept current and are the fastest way to confirm this document's Section 6/7 claims still match reality. If they've diverged (e.g., more papers were processed in a session after this document was written), trust the live files over this document's specific counts, but still follow all the **rules, methodology, and permanent decisions** in this document, which do not go stale.
4. **Do NOT read `02_AUDITS/*.md` as current** — it is deliberately frozen (see Section 4.6).
5. **Read `04_VERSION_HISTORY.md`** for the full narrative of every decision made, if more detail than this document provides is ever needed for a specific past paper.
6. **Adopt the exact methodology in Section 9** for any new paper the user uploads.
7. **Never deviate from the Permanent Decisions in Section 11** without an explicit new instruction from the user that clearly supersedes one of them (and if that happens, update this document accordingly, following the same "preserve both, mark which is final" principle used throughout this document).
8. **If the user asks "where were we" or "what's the status," answer from `questions/INDEX.md` + `01_PAPERS_TRACKER.md` + this document's Section 7 (Remaining Work) — do not guess or fabricate progress.**
9. **When in doubt about anything not explicitly covered here, ask the user — never assume, per Golden Rule 6, which governs this entire project including how this project itself should be continued.**

---

*End of PROJECT_MEMORY.md. This document was generated to be fully self-sufficient. A new Claude session reading only this file should be able to resume the project with no additional context required.*
