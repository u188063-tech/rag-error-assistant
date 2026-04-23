# Architecture

## 流程
User Error Input
→ Embedding
→ Vector DB (FAISS)
→ Top-K Retrieval
→ Reranker
→ LLM
→ Answer

## Data Ingestion
- 收集錯誤資料（Python / C++）
- 清理與切分

## Embedding
- BGE-M3

## Vector DB
- FAISS

## 關鍵點
- 向量化：Embedding 階段
- Reranking：生成前
