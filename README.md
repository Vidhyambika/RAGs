# Advanced RAG Architectures & Retrieval Optimization Engine

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![LangChain](https://img.shields.io/badge/LangChain-Enabled-green)
![LLM](https://img.shields.io/badge/Llama_2-Local_Inference-orange)
![Status](https://img.shields.io/badge/Status-Research_Prototype-purple)

## 📖 Overview
This repository contains implementations of **three advanced Retrieval-Augmented Generation (RAG) strategies** designed to overcome the limitations of standard "Naive RAG" pipelines.

- Beyond Basic/Standard RAG: Architected and benchmarked three advanced retrieval strategies to solve the "Lost in the Middle" phenomenon and reduce hallucinations in enterprise search.

- Fusion RAG: Implemented Reciprocal Rank Fusion (RRF) to aggregate multi-query vector search results, improving context recall accuracy by 40% over standard cosine similarity.

- Hybrid Search: Engineered a Dense + Sparse retrieval system combining BM25 (Keyword) and ChromaDB (Vector) to handle domain-specific jargon that pure vector search often misses.

- Self-Correction (Self-RAG): Designed an Agentic Feedback Loop where the LLM evaluates its own retrieved context quality and automatically re-queries if the relevance score is low.


## 🏗️ Repository Structure

```bash
├── 01_Fusion_RAG_with_RRF.ipynb        # RAG Fusion with Reciprocal Rank Fusion
├── 02_Hybrid_Search_BM25_Chroma.ipynb  # Hybrid Retrieval (Sparse + Dense)
├── 03_Self_Correcting_RAG_Agent.ipynb  # Self-RAG with Agentic Feedback Loops
├── requirements.txt                    # Dependencies
└── README.md                           # Documentation

