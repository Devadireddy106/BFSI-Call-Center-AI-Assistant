BFSI-AI-Assistant/
│
├── BFSI_AI_Assistant.ipynb
├── alpaca_dataset.json
├── README.md
├── architecture.png (optional but awesome)
└── requirements.txt (optional)

BFSI Call Center AI Assistant
Overview
This project builds a lightweight and compliant AI assistant for BFSI customer queries such as loan eligibility, EMI information, interest rates, and transaction problems.
The design is based on a multi-tier architecture that emphasizes deterministic answers and financial safety.

 Architecture
 
User Query
↓
Guardrails (Security Filter)
↓
Tier-1: Dataset Similarity (FAISS)
↓
Tier-3: RAG (Financial Knowledge Retrieval)
↓
Tier-2: Local Small Language Model
↓
Final Response

Key Features

200+ curated BFSI Alpaca dataset
Semantic similarity search using FAISS
Local Small Language Model (FLAN-T5)
Retrieval Augmented Generation (RAG)
Guardrails for sensitive data blocking
Fully local execution (No external APIs)
Interactive Gradio demo

 Technology Stack

Python
Sentence-Transformers
FAISS
FLAN-T5
Gradio
Google Colab

 Why This Design?

Deterministic answers for compliance
Grounded financial responses
Prevents hallucination
Safe for BFSI use cases
Modular & scalable architecture

 How to Run

Open the Colab notebook and run all cells.
Launch the Gradio interface to test the assistant.

NOTE: Gradio interface run only 7 days free Trail. After that it will End Free version.
