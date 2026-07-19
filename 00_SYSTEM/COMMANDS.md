# Commands

- **Extract** — Extract questions and mark schemes from the uploaded paper, per the
  year rules in `EXTRACTION_RULES.md`.
- **Recommend** — Suggest the best topic(s) for extracted questions without
  allocating automatically, unless confidence is Very High.
- **Allocate** — Move a question into the selected topic and update all metadata,
  indexes, audits, and statistics.
- **Review** — Recheck previous allocations for errors or inconsistencies.
- **Audit** — Display the current status of extraction, allocation, duplicates,
  metadata, coverage, and QA (all six layers).
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
6. Recommend the best topic(s).
7. Ask if confidence is not Very High.
8. Allocate only after confirmation (or automatically if confidence is Very High).
9. Update all six audit layers.
10. Update indexes, statistics, and version history.
11. Wait for the next uploaded paper.

Never skip a step. Never invent information. Never paraphrase official content.
