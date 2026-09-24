# Candidate Search Evaluation Lab

**Status: Concept brief with supporting scope and measurement notes.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=product-service-design#library)

## Product brief

An evaluation workbench for semantic candidate search. Users run recruiter-style queries against a synthetic candidate set, inspect ranked results, label relevance, and compare retrieval versions with precision@5 and recall@5.

## Design focus

Compare semantic and keyword retrieval against labeled synthetic examples.

## Proposed scope

- Synthetic candidate profiles and 25 realistic recruiter queries.
- Baseline keyword search and embedding-based search.
- Relevance labels, top-five result view, precision@5, recall@5.
- Failure-case page and experiment log.

## Validation targets

- Every query has a documented relevance judgment.
- Improvement is measured against a baseline, not asserted.
- The UI explains why a candidate was retrieved.

## Potential implementation

Python, FastAPI, SQLite/Postgres, a vector store, React or Streamlit.

## Guardrails

Use synthetic profiles only. Do not score people or make hiring recommendations.

## Supporting documentation

- [measurement plan](docs/MEASUREMENT_PLAN.md)
- [mvp scope](docs/MVP_SCOPE.md)
- [problem and users](docs/PROBLEM_AND_USERS.md)

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Deprioritize; consider retirement only if inactive.

Preserve useful material in the existing retrieval benchmark's future evaluation notes instead of committing to another active product roadmap.

### Next scope

- [ ] Save relevance labeling, baseline comparison and measurement design before any retirement decision.
- [ ] Check current use, unique branches/assets and incoming links before proposing archive or deletion.
- [ ] No deletion is authorized by this note and the repository's current status is unchanged.

### Validation and decision criteria

Reopen a PRD only for a specific recruiting-retrieval user need, with a scoped synthetic evaluation. Inactivity has not been established; retaining the repository remains an option.
<!-- portfolio-future-plans:end -->
