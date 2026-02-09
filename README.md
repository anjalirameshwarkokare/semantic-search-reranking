# Semantic Search with Re-ranking

This project demonstrates a two-stage semantic search pipeline:
1. Initial retrieval using semantic similarity (simulated embeddings)
2. Re-ranking of top candidates for higher precision

## Live API Endpoint (Deployed)
POST https://ai-cache-system.free.beeceptor.com/search

## Sample Request
```json
{
  "query": "machine learning applications",
  "k": 8,
  "rerank": true,
  "rerankK": 5
}
