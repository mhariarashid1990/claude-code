# Question Entry Template

Every extracted question is recorded in its topic file under `questions/` using this
exact block format.

```
### UQID: PK<PAPER>-<SESSION>-<YEAR>-V<VARIANT>-Q<NUM><PART>

- **Year:** 
- **Session:** May/June | Oct/Nov | Feb/Mar
- **Variant:** 
- **Paper:** 2059/01 | 0448/01
- **Question Number:** 
- **Part:** 
- **Marks:** 
- **Question (Verbatim):**
  > 
- **Official Mark Scheme (Verbatim):**
  > 
- **Suggested Primary Topic:** 
- **Secondary Tags:** 
- **Confidence Level:** Very High | High | Medium | Low
- **Allocation Status:** Pending User Approval | Allocated | Needs Review | Rejected
- **Audit Status:** 
- **Version Number:** 
- **Allocation History:** 
- **Cross References:** 
```

## UQID format

`PK<PAPER>-<SESSION>-<YEAR>-V<VARIANT>-Q<NUM><PART>`

- `<PAPER>`: `2059` or `0448`
- `<SESSION>`: `MJ` (May/June), `ON` (Oct/Nov), `FM` (Feb/Mar)
- `<YEAR>`: four digits
- `<VARIANT>`: variant number as printed on the paper
- `<NUM><PART>`: question number + part letter, e.g. `Q3B`

Example: `PK2059-MJ-2018-V2-Q3B`

## Field notes

- **Question** and **Official Mark Scheme** must be copied verbatim — including
  original numbering/lettering, punctuation, and mark allocations shown in the
  source. No rewording, no summarizing.
- **Confidence Level** governs workflow: only "Very High" may be auto-allocated;
  anything else stops for a decision per `00_SYSTEM/GOLDEN_RULES.md` Rule 2.
- **Allocation History** and **Cross References** accumulate over time — e.g. record
  of a `Move` command, or a link to a similar question in another year via `Compare`.
