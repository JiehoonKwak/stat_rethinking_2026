# Repository Instructions

Read [STATE.md](STATE.md) for the local curriculum, current evidence limits, and
next study step. The root README is preserved upstream course material.

## Purpose

This repository is for studying Statistical Rethinking 2026 and extending the
course material into applied Bayesian workflows for bioinformatics and genomics.
Use the course lectures, book chapters, scripts, and homework as grounding
material, then connect the ideas to real analysis settings such as CRISPR
screening, clone/cell-state inference, copy-number inference, and other
genomics workflows.

## Applied Case Studies

Use the existing method-group modules under `projects/` before adding a new case
study. Route questions through [the Q&A index](projects/_meta/qna-index.md);
for example, CRISPR screens belong in `projects/02-crispr-screens/` and
tumor-state inference in `projects/04-tumor-state-inference/`. Grouping related
methods avoids duplicated statistical explanations and supports comparisons.

Each case study should make the Bayesian question explicit: estimand, generative
assumptions, likelihood, priors, diagnostics, posterior checks, and the
biological interpretation. Preserve links back to the relevant Statistical
Rethinking lecture, chapter, script, or homework problem when useful.

## NotebookLM

The NotebookLM CLI is available in this environment. Use the `notebooklm` skill
or CLI when the task involves NotebookLM sources, summaries, Q&A, artifacts, or
adding course materials.

Read [source access](docs/source-access.md#notebooklm) for the previously recorded
notebook and sources; recheck them before relying on live availability.

Before relying on NotebookLM output, verify important claims against the local
course files, source PDFs, scripts, or primary genomics methods papers. Treat
NotebookLM as a retrieval and synthesis aid, not as the source of truth.

## Local Source Material

Read [source access](docs/source-access.md#local-textbook-material) for recorded
PDF paths and checkout availability. Check Git status before moving, renaming,
or committing local PDFs.

The [textbook index owner](book/rethinking2/README.md) documents metadata and
cache rebuild commands.

Search the index first, then the generated `book/rethinking2/cache/` text. Use
page markers in the cache to verify exact wording, equations, figures, and
tables against the source PDF.

## Study Artifacts

Use Markdown files as agent-facing source material and durable context. Use
single-file HTML under `site/` for human-facing study artifacts, especially
when explaining methods, statistical concepts, assumptions, pitfalls, or
interactive comparisons.

[Curriculum maintenance](docs/curriculum-maintenance.md) owns the publication
workflow and evidence limits; edit canonical Markdown before regenerating HTML.
