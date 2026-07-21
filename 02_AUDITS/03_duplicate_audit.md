# Audit 3 — Duplicate Audit

Tracks exact and near-duplicate questions/mark schemes across the bank.

_Last updated: Version 37 (full job pass — 473 questions checked)_

| Metric | Count |
|---|---|
| Duplicate UQIDs found | 0 |
| Duplicate question text (verbatim) found | 1 group (2 entries) — legitimate recurrence, not an error |
| Duplicate mark schemes found | 0 |
| Near duplicates flagged for review | 0 |

## Log

- **PK2059-ON-2019-V1-Q3B** and **PK2059-ON-2020-V1-Q3B** — both read
  "Explain why there were three Round Table Conferences between 1930 and 1932."
  This is the same question set by Cambridge in two consecutive Oct/Nov sittings
  (2019 and 2020), each with its own mark scheme extracted verbatim from its own
  paper. Both entries are retained as distinct, correctly-tagged instances under
  Round Table Conferences — this reflects genuine question recurrence across
  exam series, not a duplication error in the bank.
- No other exact or near-duplicate question text was found across the 473 entries.
- No two entries share an identical mark scheme.
- No two entries share a UQID (`grep -rh "^### UQID:" | sort | uniq -d` returns
  empty).
