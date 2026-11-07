# FinGPT – Offline Personal Finance Assistant

## Project Overview
FinGPT is a privacy-focused, offline personal finance assistant powered by Small Language Models (SLMs). It processes bank statements, extracts financial transactions, and answers natural-language questions without requiring internet access or a GPU.

## Objectives
- Extract transactions from PDF, CSV and Excel bank statements.
- Normalize and categorize financial transactions.
- Store transaction data locally using SQLite.
- Answer questions about spending, income, SIPs and cash flow.
- Use a locally hosted SLM for natural-language understanding.
- Fine-tune smaller models for faster CPU and mobile inference.

## Technology Stack
- **Language:** Python
- **Data Processing:** Pandas
- **PDF Extraction:** PyMuPDF
- **Database:** SQLite
- **SLM Inference:** llama.cpp
- **Model Format:** GGUF
- **Fine-tuning:** Hugging Face, PEFT, LoRA/QLoRA
- **Interface:** Streamlit

## Development Roadmap
1. Python, Pandas and SQL refresher.
2. PDF extraction and transaction parsing.
3. Financial transaction ETL pipeline.
4. SQLite database and financial analytics.
5. Local CPU-based SLM inference.
6. Natural-language-to-SQL integration.
7. RAG implementation.
8. Model evaluation and benchmarking.
9. Fine-tuning using LoRA.
10. Quantization and mobile deployment.

## Privacy
All document processing, database operations and model inference will run locally. No bank statements or financial information will be sent to external APIs.

## Initial Goal
Build a fully functional offline finance chatbot that can accurately answer questions such as:
- How much did I spend on Amazon?
- How much did I invest in SIPs?
- What were my total credits and debits?
- What were my monthly expenses?

**Long-term vision:** A lightweight, fine-tuned financial SLM that runs entirely on a laptop CPU or smartphone.