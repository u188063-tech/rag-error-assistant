# Programming Error Assistant RAG

## 專案目標

本專案建立一個 RAG 系統，用來分析程式錯誤訊息並提供解決方案。

## 功能

* 輸入錯誤訊息
* 回傳錯誤原因
* 提供修正方法與範例

## 技術

* Embedding: BGE-M3
* Vector DB: FAISS
* LLM: OpenAI / LLaMA

## 流程

1. 使用者輸入錯誤
2. 向量化
3. 搜尋資料庫（Top-K）
4. Reranking
5. LLM 生成答案

## 注意

僅供學習用途
