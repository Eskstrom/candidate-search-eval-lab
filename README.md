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
