# Enterprise RAG Customer Service Agent (LangChain + FAISS, $25K Annual Savings)

A production-style Retrieval-Augmented Generation (RAG) system that turns scattered enterprise docs into instant, cited answers for customer support. I built a full pipeline: document ingestion → smart chunking → vector search (FAISS) → LLM answering (Ollama) → validation + ROI analysis.

---

## Why this exists

Data lived across 18+ files and 4 departments. First responses took 4–6 hours; CSAT was 35%. This agent answers in seconds, cites sources, and projects $25K+ annual savings with a sub-3-month payback.

---

## Key features

- Multi-format ingestion (CSV, JSON, Markdown, TXT) with metadata enrichment  
- Smart chunking (1000 chars, 200 overlap) + quality analysis  
- Semantic search with FAISS and HuggingFace embeddings  
- Local LLM via Ollama (privacy, zero API cost) with customer-service prompt  
- Source attribution, conversation history, response time metrics  
- Scenario tests across Billing, Tech Support, and Legal/Privacy  
- Business impact & ROI calculator  


---

## Tech stack

- Python 3.10+  
- LangChain (modern imports)  
- FAISS  
- sentence-transformers/all-MiniLM-L6-v2 (HuggingFace)  
- Ollama (local LLM; tested with `llama3.2`)  
- NumPy, Unstructured, jq  

---

## Setup

### 1) Python environment

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt





