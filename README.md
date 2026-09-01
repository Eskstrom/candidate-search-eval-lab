# Candidate Search Evaluation Lab

## Product brief

An evaluation workbench for semantic candidate search. Users run recruiter-style queries against a synthetic candidate set, inspect ranked results, label relevance, and compare retrieval versions with precision@5 and recall@5.

## Why this belongs in your portfolio

It directly extends your Projects Yard work and turns AI search into a measurable product decision. It demonstrates evaluation design, failure analysis, and iteration—not just a chat interface.

## MVP

- Synthetic candidate profiles and 25 realistic recruiter queries.
- Baseline keyword search and embedding-based search.
- Relevance labels, top-five result view, precision@5, recall@5.
- Failure-case page and experiment log.

## Success measures

- Every query has a documented relevance judgment.
- Improvement is measured against a baseline, not asserted.
- The UI explains why a candidate was retrieved.

## Suggested stack

Python, FastAPI, SQLite/Postgres, a vector store, React or Streamlit.

## Guardrails

Use synthetic profiles only. Do not score people or make hiring recommendations.

## Chat kickoff

“Build the Candidate Search Evaluation Lab described in this README. Start with synthetic data, baseline and semantic retrieval, and a reproducible precision@5/recall@5 evaluation.”
