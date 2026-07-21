# Audit 1 — Extraction Audit

Tracks which papers have been uploaded and processed, and question-level extraction
completeness against `00_SYSTEM/EXTRACTION_RULES.md`.

_Last updated: Version 37 (full job pass)_

| Metric | Count |
|---|---|
| Papers uploaded | 33 |
| Papers fully extracted | 33 |
| Questions extracted (total) | 473 |
| Questions remaining (papers in progress) | 0 |
| Missing questions flagged | 0 |

## Papers processed — Cambridge O Level 2059/01 (2010–2025)

| Paper | Year | Session | Variant | Rule applied | Parts required | Parts extracted |
|---|---|---|---|---|---|---|
| 2059/01 | 2010 | May/June | 1 | 2010–2014 (15 parts: Q1–Q5 a/b/c) | 15 | 15 |
| 2059/01 | 2010 | Oct/Nov | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2011 | May/June | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2011 | Oct/Nov | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2012 | May/June | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2012 | Oct/Nov | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2013 | May/June | 1 | 2010–2014 | 15 | 15 |
| 2059/41 | 2013 | (Pakistan-only security-breach resit) | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2013 | Oct/Nov | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2014 | May/June | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2014 | Oct/Nov | 1 | 2010–2014 | 15 | 15 |
| 2059/01 | 2015 | May/June | 1 | 2015–2025 (14 parts: Q1(c)/(d), Q2–Q5 a/b/c) | 14 | 14 |
| 2059/01 | 2015 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2016 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2016 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2017 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2017 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2018 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2018 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2019 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2019 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2020 | May/June | 1 (⚠️ COVID-cancelled series — MS extracted and flagged per user instruction; students did not sit this exam) | 2015–2025 | 14 | 14 |
| 2059/01 | 2020 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2021 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2021 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2022 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2022 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2023 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2023 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2024 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2024 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2025 | May/June | 1 | 2015–2025 | 14 | 14 |
| 2059/01 | 2025 | Oct/Nov | 1 | 2015–2025 | 14 | 14 |

**Arithmetic check:** 11 papers × 15 parts (2010–2014, incl. the 2013 resit) = 165, plus
22 papers × 14 parts (2015–2025) = 308. 165 + 308 = **473**, matching
`questions/INDEX.md` exactly and the live `grep -rc "^### UQID:"` count. No parts
missing, no parts over-extracted.

## Cambridge IGCSE 0448/01 (2010–2025)

Not extracted. Per user confirmation (2026-07-21) that 0448/01 and 2059/01 "have same
papers despite their different codes," this syllabus is not being separately
extracted — the 2059/01 corpus above is treated as covering both paper codes for the
purposes of this audit and the completion protocol in `PROJECT_MEMORY.md`. If a
0448/01 PDF is supplied later with content that diverges from the corresponding
2059/01 paper, it will be extracted and audited separately at that time.

## Missing questions log

_None._
