# Cambridge Pakistan Studies — Topical Question Bank

A publication-quality topical past-paper resource for:

- **Cambridge O Level Pakistan Studies — History & Culture (2059/01)**
- **Cambridge IGCSE Pakistan Studies — History & Culture (0448/01)**

Built for **Learn with Haris**. Target coverage: every required question, 2010–2025.

## Status

**No papers have been uploaded yet.** This repository currently contains only the
system scaffolding — folder structure, taxonomy, templates, and audit trail — so that
extraction can begin the moment a paper and its mark scheme are provided.

See [`01_PAPERS_TRACKER.md`](01_PAPERS_TRACKER.md) for what's outstanding.

## How this works

1. Upload one past paper + its official mark scheme at a time.
2. I extract every required question and its official mark scheme, **verbatim**, per
   the year rules in [`00_SYSTEM/EXTRACTION_RULES.md`](00_SYSTEM/EXTRACTION_RULES.md).
3. Each question gets a Unique Question ID and full metadata (see
   [`00_SYSTEM/QUESTION_TEMPLATE.md`](00_SYSTEM/QUESTION_TEMPLATE.md)).
4. I recommend a Primary Topic against the taxonomy in
   [`00_SYSTEM/CLASSIFICATION_FRAMEWORK.md`](00_SYSTEM/CLASSIFICATION_FRAMEWORK.md).
   Anything below Very High confidence stops and asks you to choose.
5. Once allocated, the question is appended verbatim to its topic file under
   [`questions/`](questions/) — one permanent location, never duplicated.
6. All six audit layers in [`02_AUDITS/`](02_AUDITS/) are updated, plus
   [`03_ERROR_LOG.md`](03_ERROR_LOG.md) and [`04_VERSION_HISTORY.md`](04_VERSION_HISTORY.md).

Full rule set: [`00_SYSTEM/GOLDEN_RULES.md`](00_SYSTEM/GOLDEN_RULES.md).

## Commands

See [`00_SYSTEM/COMMANDS.md`](00_SYSTEM/COMMANDS.md) for the full list
(`Extract`, `Recommend`, `Allocate`, `Review`, `Audit`, `Search`, `Move`, `Compare`, `Export`).

## Repository layout

```
00_SYSTEM/              Rules, taxonomy, templates, command reference
01_PAPERS_TRACKER.md     Which papers (year/session/variant/paper) are processed
02_AUDITS/               The six audit layers
03_ERROR_LOG.md          Error tracking
04_VERSION_HISTORY.md    Version-by-version change log
questions/               One markdown file per topic — the actual question bank
```

## Next step

Upload the first past paper (PDF or text) and its official mark scheme, and specify
year, session, variant, and paper code (2059/01 or 0448/01). Extraction begins on
receipt — nothing is generated ahead of the source document.
