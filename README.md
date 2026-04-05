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

A compliance-focused AI assistant for SOP, CAPA, deviation, and regulated quality document workflows.

CompliBot MVP is built to support evidence-backed question answering over compliance documents, helping users interpret procedures, requirements, and process expectations more efficiently.

---

## Problem

Compliance and quality documents are critical in regulated environments, but they are often difficult to navigate quickly during operational or review workflows.

Typical pain points include:

- Manually searching long SOPs and quality documents
- Difficulty locating approval requirements
- Slow interpretation of procedural steps
- Limited access to fast, grounded document support

---

## Solution

CompliBot MVP allows users to upload compliance-related PDFs, index them, and ask grounded questions over the document set.

The system supports:

- SOP-focused question answering
- Compliance-oriented requirement extraction
- Evidence-backed guidance for review workflows

---

## Key Features

- Upload SOP, CAPA, deviation, and quality PDFs
- Ingest and index compliance documents
- Ask grounded compliance questions
- Retrieve relevant supporting evidence
- Generate structured compliance-oriented answers
- Support document review workflows

---

## Technology Stack

- Python
- Streamlit
- PyPDF
- ChromaDB
- Sentence Transformers

---

## How It Works

1. Upload compliance or SOP-related PDFs  
2. Ingest and index document content  
3. Ask a compliance-focused question  
4. Retrieve relevant evidence  
5. Return a structured, grounded response  

---

## Project Structure

```text
complibot-mvp/
├── app.py
├── requirements.txt
├── README.md
└── ...
```
---

## Why This Project Matters

This project demonstrates:

- AI support for regulated compliance workflows
- evidence-backed document assistance
- retrieval-based procedural guidance
- domain-aware application design for quality operations

## Important Note

This project is a prototype/demo build created to reflect regulated-environment design patterns. It is not a validated compliance decision system.

---

## 🔗 Links & Attribution

### 🌐 Live Demo
[![Live Demo](https://img.shields.io/badge/Demo-HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Chaitanya-Sanagana/complibot-mvp)

### 👤 Author
**Chaitanya Sanagana**
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Chaitanya-Sanagana)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chaitanya-sai-sanagana-8a1827263)