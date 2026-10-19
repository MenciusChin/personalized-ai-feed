# Personalized AI Feed

An end-to-end recommendation product that combines retrieval, ranking, generative recommendation, and production ML infrastructure.

This is the capstone repo: pieces learned in `generative-recsys` and `llm-serving-lab` will eventually converge here.

## Target architecture

```text
content ingestion
      ↓
feature / embedding pipeline
      ↓
candidate generation
 ├─ collaborative
 ├─ semantic
 └─ trending
      ↓
ranking
      ↓
diversity / freshness
      ↓
GenRec / LLM reranking
      ↓
personalized feed
```

## Product + systems focus

- retrieval and ranking quality
- freshness and diversity
- feature / embedding serving
- latency budgets
- observability
- offline-to-online evaluation
- experimentation / A-B testing

See [ROADMAP.md](ROADMAP.md).

## Status

**Planned capstone.** It will reuse components once the recommendation and serving labs are mature enough.
