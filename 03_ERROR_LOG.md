# Error Log

Every extraction, allocation, or metadata error is logged here, regardless of how
minor.

| Error ID | Paper | Question | Issue | Status | Resolution | Date Fixed |
|---|---|---|---|---|---|---|
| E001 | 2059/01 MJ2014 | PK2059-MJ-2014-V1-Q3C | `questions/INDEX.md` row for "Khilafat Movement" (Section 2, #9) still read count `2` after this question was added at Version 9, instead of `3`. The question itself was correctly extracted, allocated, and present in `09-khilafat-movement.md` the whole time — only the INDEX.md summary row was stale (a bookkeeping miss when Version 9 was committed). The document-level "Total questions allocated: 90" header was unaffected and remained correct throughout. Discovered by a full mechanical recount of every topic file (`### UQID:` occurrences) against INDEX.md's declared per-row counts, while building the consolidated topical + mark-scheme PDF. | Fixed | Corrected the Khilafat Movement row in `questions/INDEX.md` from `2` to `3`. No question content changed. | 2026-10-18 |
