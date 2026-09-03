# Measurement Plan

## Offline quality measures

| Metric | Purpose | Initial release bar |
| --- | --- | --- |
| Precision@5 | Are top results relevant? | Improve or preserve baseline for each major query class |
| Recall@5 | Are known relevant candidates found? | No material regression against baseline |
| Label coverage | Is the test set credible? | Every query has top-five relevance labels |
| Failure rate | Where does retrieval break? | Categorize every failed query before release |

## Qualitative review

Each experiment review includes five representative wins, five failures, the expected retrieval rationale, and the observed failure category.

## Release decision

Promote a retrieval change only when aggregate results improve without hiding regressions in important query classes. If evidence is mixed, segment the query type, adjust the hypothesis, and run a new experiment rather than averaging the issue away.

## Next milestone

Add a simple reviewer interface for relevance labeling and an experiment timeline that links a version, hypothesis, evidence, and decision.
