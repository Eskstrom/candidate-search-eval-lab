# Problem and Users

## Problem

Semantic candidate search can look impressive while failing recruiters in consequential ways: strong candidates are missed, weak matches are ranked too highly, and the team cannot explain whether a new retrieval change improved the experience.

Candidate Search Evaluation Lab makes search quality observable before a retrieval approach is shipped.

## Primary user: talent-product manager

Owns search quality and needs to decide whether a retrieval change should be released.

### Needs

- Compare a baseline and a proposed ranking on the same query set.
- See quality metrics alongside individual failure cases.
- Document a decision, rationale, and follow-up experiment.

## Secondary user: search engineer

Needs fast feedback on embedding, ranking, filtering, and query-understanding changes.

## Intended decision

The product answers: “Does this retrieval version meet the quality bar for this query class, and what does it still get wrong?”

## Out of scope

- Automated hiring decisions.
- Candidate scoring or suitability recommendations.
- Production applicant-tracking-system integrations in the MVP.
