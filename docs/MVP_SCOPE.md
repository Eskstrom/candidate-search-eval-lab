# MVP Scope

## In scope

- A synthetic candidate corpus with skills, experience, preferences, and structured metadata.
- Twenty-five labeled recruiter-style queries across distinct query classes.
- Keyword baseline and semantic retrieval comparison.
- A top-five result view with relevance judgments and rationale fields.
- Precision@5, recall@5, and query-level failure inspection.
- A versioned experiment record for every comparison.

## Deliberately deferred

- Resume parsing from uploaded documents.
- Live recruiter or applicant data.
- Personalized ranking or user-level behavioral learning.
- Automated changes to ranking production traffic.

## MVP acceptance criteria

1. A user can run the same query set against two retrieval versions.
2. Every metric is traceable to stored relevance labels.
3. A user can inspect the specific results behind an aggregate metric.
4. The app warns when a query class has too little labeled evidence for a release decision.
