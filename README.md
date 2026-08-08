---
title: CompliBot MVP
emoji: 📋
colorFrom: blue
colorTo: indigo
sdk: streamlit
sdk_version: "1.39.0"
python_version: "3.11"
app_file: app.py
pinned: false
---

# 📋 CompliBot MVP

A compliance-focused document assistant for SOP, CAPA, deviation, training, and regulated quality workflows.

CompliBot demonstrates grounded question answering over uploaded compliance documents, with structured outputs designed for review-oriented workflows.

## What it demonstrates

- Compliance-focused RAG-style retrieval
- SOP/CAPA/deviation question classification
- PDF parsing with PyPDF
- Chunking and document-group metadata
- Sentence Transformer embeddings
- ChromaDB vector storage
- Evidence-backed answer synthesis
- Streamlit workflow interface

## Why it matters

Quality and compliance documents are often operationally important but hard to navigate quickly. CompliBot shows how a grounded AI assistant can help users locate evidence, identify procedural guidance, and review compliance-related requirements.

## Features

- Upload SOP, CAPA, deviation, training, and quality PDFs
- Ingest uploaded documents into a vector store
- Ask compliance-focused questions
- Retrieve supporting document evidence
- Generate structured answer sections
- Show question type, evidence, source, and compliance note

## Tech stack

- Python
- Streamlit
- PyPDF
- ChromaDB
- Sentence Transformers
- NumPy
- Pandas

## Project structure

```text
complibot-mvp/
├── app.py
├── compli_pipeline.py
├── requirements.txt
├── .env.example
├── .gitignore
├── DEPLOYMENT_CHECKLIST.md
└── README.md
```

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
streamlit run app.py
```

## Environment variables

The default demo does not require API keys. Embeddings run locally through Sentence Transformers.

Use `.env.example` as a safe template only. Do not commit a real `.env` file.

## Deployment notes

This project is compatible with Hugging Face Spaces using the Streamlit SDK metadata at the top of this README.

Suggested Space name:

```text
complibot-mvp
```

## Limitations

- This MVP is a prototype and is not a validated GxP, Part 11, or production quality-management system.
- Outputs must be reviewed against approved internal procedures.
- PDF extraction quality depends on the source document.
- Scanned PDFs may require OCR, which is not included.

## Roadmap

- Add richer document metadata and versioning
- Add reviewer approval queue
- Add auditable export of answer/evidence pairs
- Add optional LLM synthesis with strict citations
- Add retrieval evaluation dashboard

## Author

**Chaitanya S.**  
Applied AI Engineer | Generative AI · RAG · Agentic AI · AI Platform Engineering

- GitHub: `github.com/ChaitanyaAI-Dev/complibot-mvp`
- LinkedIn: `linkedin.com/in/chaitanyaai-dev`
- Hugging Face: `huggingface.co/ChaitanyaAI-Dev`
- Portfolio: `chaitanyaai-dev-portfolio.vercel.app`

## Disclaimer

This is a prototype/demo project for AI engineering portfolio purposes. It is not medical, legal, regulatory, or compliance advice.
