# Statistical Rethinking documentary cleanup

Independent docs-only review passed all 7 questions; parent comparison accepted the retained reasons, corrections and explicit unknowns. Scoped delivery is recorded in the private receipt.

Date: 2026-10-08. Status: applied under the approved project-memory migration.

- **SR-M01:** Added STATE and AGENTS route to the existing curriculum, nine modules, generated site and dated verification limits. Replaced hypothetical package-folder examples with existing method-group modules.
- **SR-J02:** Kept completed SPEC at its existing path: dated metadata is sufficient, and moving adds no useful route. STATE identifies it as historical; living entrypoints own ongoing state rather than adopting its speculative CONTEXT promotion suggestion.

The previously observed NotebookLM inventory now has an explicit freshness limit. Upstream README, educational sources, all module prose, SPEC, generator code, PDFs and cache material are preserved. Verification is documentary and structural; no scientific analysis or site generation was run. Detailed source screening and exact backups are in the private migration receipt.


## D-20261010 memory index

Approval: the user approved the memory-index plan on 2026-10-10 (pilot on
`~/.agents`, then one Codex agent per project). Applied: commit `d11ba5a`. Recovery:
`git revert d11ba5a`.

Changed files:

```text
AGENTS.md                      | 30 ++++++++++--------------------
 STATE.md                       | 38 +++++++++++++++++++++++++-------------
 docs/curriculum-maintenance.md | 33 +++++++++++++++++++++++++++++++++
 docs/source-access.md          | 27 +++++++++++++++++++++++++++
 4 files changed, 95 insertions(+), 33 deletions(-)
```

Agent receipt:

Completed the documentation-only cleanup.

1. **Line counts:** `STATE.md` **25 → 37**; `AGENTS.md` **72 → 62**. STATE’s dense paragraphs became an index; its word count fell **421 → 225**.

2. **Moved items:**

| Fact | Destination |
|---|---|
| NotebookLM notebook ID, source inventory, freshness limit | [docs/source-access.md](docs/source-access.md) |
| Recorded PDF paths and current checkout availability | [docs/source-access.md](docs/source-access.md) |
| Markdown-to-HTML workflow and generator location | [docs/curriculum-maintenance.md](docs/curriculum-maintenance.md) |
| Artifact availability and historical verification limits | [docs/curriculum-maintenance.md](docs/curriculum-maintenance.md) |

3. **Removed duplication:** Statistical checklists remain in `projects/_meta/critic-rubric.md`; provenance rules remain in `projects/_meta/study-plan.md`; textbook rebuild instructions remain in `book/rethinking2/README.md`. Module counts and historical verification details remain in `SPEC.md` and Git history.

4. **New files:** The two linked documents above.

5. **Preserved and unresolved:** Upstream human-authored course text, all module prose, and every protected file remained unchanged. The learner’s next module is still undecided; recorded PDFs/cache are absent here, and NotebookLM live availability remains unchecked.

All **30 relative links and heading anchors** passed verification. No code, outputs, commits, branches, or Git state were changed.

Reviewer correction: the agent worked in a worktree without ignored files and wrote that the textbook PDFs and cache were absent; `STATE.md` and `docs/source-access.md` were corrected to describe them as Git-ignored local material before merge.
