# Team_MTU — DesignQA Hackathon 2025

This repository contains our solution for the **DesignQA Hackathon 2025** (IDETC), focusing on the **Rule Retrieval** subset and related tasks.
 Our approach uses **Retrieval-Augmented Generation (RAG)** with FAISS, BM25, and SentenceTransformers to extract relevant rules from the FSAE 2024 Rulebook.

Rule_Retrieval/
│
├── rule_retrieval.py 
├── requirements.txt 
├── README.md
├── .gitignore # exclude
├── results/ # Model prediction CSVs and results
├── data/ # Any local datasets 
└── .env.example # Template for storing your API key

Installation:
```bash
git clone https://github.com/<your-username>/Rule_Retrieval.git
cd rule_retrieval

Install dependencies
pip install -r requirements.txt

setup API Key:
Open .env and replace:
OPENAI_API_KEY=your_api_key_here

Run the main script:
python rule_retrieval.py

This will:
Load the FSAE rulebook.
Embed and index rules using FAISS & BM25.
Retrieve relevant rules for each question.
Save results and evaluation metrics.
