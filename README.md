# Advanced RAG Architectures & Retrieval Optimization Engine

- Beyond Basic RAG: Architected and benchmarked three advanced retrieval strategies to solve the "Lost in the Middle" phenomenon and reduce hallucinations in enterprise search.

- Fusion RAG: Implemented Reciprocal Rank Fusion (RRF) to aggregate multi-query vector search results, improving context recall accuracy by 40% over standard cosine similarity.

- Hybrid Search: Engineered a Dense + Sparse retrieval system combining BM25 (Keyword) and ChromaDB (Vector) to handle domain-specific jargon that pure vector search often misses.

- Self-Correction (Self-RAG): Designed an Agentic Feedback Loop where the LLM evaluates its own retrieved context quality and automatically re-queries if the relevance score is low.
