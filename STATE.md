# Statistical Rethinking local curriculum

Updated: 2026-10-17 00:59:35 (Asia/Seoul)

## Current goal

Study Statistical Rethinking and connect causal/Bayesian modeling habits to
bioinformatics, genomics, and medicine — [study plan](projects/_meta/study-plan.md).

## Active work

No learner-selected module or comprehension checkpoint is recorded. Available
curriculum artifacts do not establish learner completion or analysis reproduction
— [evidence limits](docs/curriculum-maintenance.md#evidence-and-maintenance-limits).

## Decisions in force

- Only exclusions marked `reproducible: true` in [.ctxdata.json](.ctxdata.json)
  carry rebuild evidence; local-only excluded artifacts retain their existing owner.

- [.ctxdata.json](.ctxdata.json) retains authored curriculum/source inputs pending Git tracking; textbook text caches and chapter splits are reproducible from the retained PDF via the documented index builder.

- Markdown is canonical; edit its owner before regenerating HTML — [publication workflow](docs/curriculum-maintenance.md#publication-workflow).
- Group related methods and route questions through existing modules — [Q&A index](projects/_meta/qna-index.md), [comparisons](projects/_meta/module-matrix.md).
- Expose estimands, models/proxies, assumptions, parameter roles, diagnostics, and Bayesian classification — [critic rubric](projects/_meta/critic-rubric.md).
- Track provenance and keep raw sources gitignored — [study plan](projects/_meta/study-plan.md#산출물-원칙), [metadata](projects/_sources/metadata/README.md).
- Keep community practice separate from scientific evidence — [field notes](projects/_sources/field-notes/README.md).
- Clinical content provides analysis guidance — [clinical boundary](projects/08-clinical-bayes/README.md).
- Verify source claims and NotebookLM availability before relying on them — [source rules](AGENTS.md#notebooklm), [textbook workflow](book/rethinking2/README.md).

## Open questions and blockers

- Which study question/module should come next?
- Textbook PDFs and cache are Git-ignored local material, absent from fresh clones — [source access](docs/source-access.md#local-textbook-material).
- Browser interaction and external-link liveness need checks when relevant — [maintenance limits](docs/curriculum-maintenance.md#evidence-and-maintenance-limits).

## Next step

Choose the study question with the learner and use the Q&A index and module
`qa-context.md`. Follow the [foundations-first order](projects/_meta/study-plan.md#학습-순서)
when no narrower question is selected; verify important claims through the module
source map and textbook pages.
