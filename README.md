# Misty Dream Count

An interactive dashboard for exploring dream-related language in *Misty* comic stories.

The dashboard is published here:

https://paulfdavies.github.io/MistyDreamCount/

## What It Shows

This page visualises mentions of terms such as `dream`, `nightmare`, `sleep`, `woke`, `awake`, `vision`, and `trance` across *Misty* stories and issues.

It is intended to help distinguish frequent dream references in comics story wording from mentions that occur in non-story pages such as letters, horoscopes, editorials, prose stories, features, and advertisements.

The dashboard includes:

- ranked story counts
- story-level detail
- issue and page heatmaps
- page-level inclusion/exclusion checks
- Julia's story summaries where available

## Data Notes

The underlying OCR is imperfect, so the counts should be treated as research prompts rather than final statistics.

Story start pages were scraped from the UK Comics Wiki / Bournemouth comics database issue records. Page classification was then refined locally, including a manual review of the back-page colour material, which is especially tricky because it can be a story continuation, a standalone comic story page, a prose story, Miss T, or non-story material depending on the issue.

The current public page is self-contained in `index.html`. It does not include scanned page images.

## Repository Contents

- `index.html` - the published dashboard

The working OCR, page ledger, extraction scripts, and scan-review tools are kept outside this public repository.

## Project Context

This is part of a larger project on dreams, truth, and modality in British girls' comics, with this dashboard focused specifically on *Misty*.
