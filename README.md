# WRM Content Assets

A running library of standalone, give-away-worthy assets produced from
WhiskeyRiverMedia content — prompts, audits, and templates that work as
lead magnets because they're genuinely useful on their own, with no
bait-and-switch attached.

## Philosophy
Every asset in here should pass one test: would someone use this even if
they never became a client? If yes, it belongs here. If it only works as
a teaser for something else, it's marketing copy, not an asset — keep it
out of this repo.

## Index

| Asset | Description | Source content | Status |
|---|---|---|---|
| [`lead-magnets/router-audit-prompt.md`](./lead-magnets/router-audit-prompt.md) | A copy-paste prompt that has Claude audit a person's own chat history and flag where they're over- or under-spending on model tier vs. task complexity. | @whiskeyrivermedia TokScript on Fable 5's July 7 pricing cliff | Live |

## How to use an asset
Each file is self-contained: a copy-paste block for the end user, plus
context notes (why it works, how to deploy it, suggested follow-up) for
internal WRM use. Open the file — everything needed is inside it.

## Adding new assets
1. Drop the new `.md` file under `/lead-magnets/` (or a new folder if it's
   a different asset type — templates, checklists, etc.).
2. Add a row to the Index table above with a one-line description, the
   source content it came from, and its status (Live / Draft / Retired).
3. Commit directly to `main` — this repo doesn't need a PR workflow for
   a one-person operation.
