# Commands

- **Extract** — Extract questions and mark schemes from the uploaded paper, per the
  year rules in `EXTRACTION_RULES.md`.
- **Recommend** — Suggest the best topic(s) for extracted questions and present them
  as clickable options for every single part — never allocate automatically,
  regardless of confidence level (user directive, 2026-07-19).
- **Allocate** — Move a question into the topic the user selected and update
  metadata, indexes, and statistics. Audit layers are NOT refreshed per paper — see
  `Audit` below.
- **Review** — Recheck previous allocations for errors or inconsistencies.
- **Audit** — Display the current status of extraction, allocation, duplicates,
  metadata, coverage, and QA (all six layers). Per user directive (2026-07-19), the
  six audit layers are only run/refreshed once the entire upload job — every
  required paper, 2010–2025, both 2059/01 and 0448/01 — is 100% extracted and
  allocated. They are not updated after each individual paper.
- **Search** — Find questions by year, topic, keyword, marks, paper, or tag.
- **Move** — Reassign a question to a different topic while preserving its complete
  history.
- **Compare** — Show similar questions across years.
- **Export** — Generate the current topical collection while preserving verbatim
  wording and metadata.

## Standard workflow per uploaded paper

1. Read the paper.
2. Read the official mark scheme.
3. Extract only the required questions according to the year rules.
4. Preserve every question and mark scheme verbatim.
5. Generate metadata.
6. For every single extracted part, present clickable Primary Topic options
   (Suggested Primary Topic first, then other plausible topics, then
   "Allocate elsewhere" / "Unsure") and wait for the user's pick. No exceptions for
   high confidence — this replaces the old "auto-allocate if Very High" behaviour.
7. Allocate only after the user's selection for that part.
8. Update `questions/INDEX.md`, `01_PAPERS_TRACKER.md`, and
   `04_VERSION_HISTORY.md` for the paper just processed.
9. Do **not** refresh `02_AUDITS/` for this paper — audits are run once, in full,
   only after every required paper (2010–2025, both 2059/01 and 0448/01) has been
   uploaded and allocated.
10. Wait for the next uploaded paper.

When the upload job reaches 100% completion, run a full `Audit` pass updating all
six layers in one go.

Never skip a step. Never invent information. Never paraphrase official content.
