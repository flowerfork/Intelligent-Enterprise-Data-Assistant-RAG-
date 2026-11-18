# Intelligent Enterprise Data Assistant (RAG)

An AI-powered enterprise knowledge assistant that helps users retrieve information from organizational documents and answer questions using Retrieval-Augmented Generation (RAG).

## Overview

The Intelligent Enterprise Data Assistant is designed to simplify document-based information retrieval. Users can upload enterprise documents and interact with them through a conversational interface. The system extracts, preprocesses, indexes, and retrieves relevant information to generate context-aware responses grounded in the uploaded data.

## Objectives

- Enable intelligent search across uploaded enterprise documents.
- Extract and preprocess text from PDF, DOCX, and TXT files.
- Apply semantic search to retrieve relevant information.
- Generate context-aware responses using Retrieval-Augmented Generation (RAG).
- Provide source references to support answer verification.
- Analyze document collections and retrieval activity through visualizations.

## Proposed Workflow

1. Upload enterprise documents.
2. Extract and preprocess document content.
3. Split text into manageable chunks.
4. Generate embeddings for document chunks.
5. Store embeddings in a vector database.
6. Retrieve relevant chunks using semantic similarity.
7. Generate responses using a Large Language Model (LLM).
8. Display answers with supporting sources.

## Technology Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Frontend | Streamlit |
| Data Processing | Pandas, NumPy |
| Embeddings | Sentence Transformers |
| Vector Database | ChromaDB |
| Document Processing | PyPDF, python-docx |
| Machine Learning | Scikit-learn |
| Visualization | Plotly |
| Version Control | Git and GitHub |

## Data Mining Concepts

- Data preprocessing and cleaning
- Text transformation
- Feature representation using embeddings
- Semantic similarity analysis
- Information retrieval
- Knowledge discovery
- Retrieval performance evaluation

## Planned Features

- Document upload and management
- Multi-format document support
- Semantic search
- AI-powered question answering
- Context-grounded responses
- Source references
- Interactive analytics dashboard
- Retrieval performance evaluation

## Project Structure

```text
Intelligent-Enterprise-Data-Assistant-RAG/
│
├── app.py
├── requirements.txt
├── README.md
├── .env.example
├── .gitignore
│
├── data/
│   ├── uploads/
│   └── processed/
│
├── vectorstore/
│
├── src/
│   ├── ingestion/
│   ├── embeddings/
│   ├── retrieval/
│   ├── generation/
│   ├── database/
│   ├── analytics/
│   └── utils/
│
├── tests/
└── assets/
```

## Project Status

🚧 Under development

## Academic Information

**Course:** Data Warehousing and Mining (25AD2203E)  
**Academic Year:** 2026–2027  
**Team Number:** 20

## Team Members

- Mahathi Chekka
- Sahasra Y
- Mohit

## Guide

Dr. Dyuti Banerjee  
Department of AI and DS

---

This project is developed as part of the Data Warehousing and Mining course.
