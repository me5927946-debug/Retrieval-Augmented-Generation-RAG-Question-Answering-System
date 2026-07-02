# 📚 Retrieval-Augmented Generation (RAG) Question Answering System

A Retrieval-Augmented Generation (RAG) application that enables users to ask natural language questions about PDF documents. The system extracts text, creates vector embeddings, retrieves the most relevant content using semantic search, and generates accurate answers using a Large Language Model (LLM).

---

## Overview

This project combines document retrieval with generative AI to build an intelligent question-answering system. Instead of relying solely on the language model's knowledge, it first retrieves relevant information from uploaded PDF documents before generating a response.

---

## Features

- Extracts text from PDF documents
- Splits documents into semantic text chunks
- Generates embeddings using Sentence Transformers
- Stores embeddings in a FAISS vector database
- Retrieves relevant document context through semantic search
- Generates context-aware answers using Mistral-Nemo-Instruct
- Exposes the model through a FastAPI REST API
- Supports remote API access using ngrok

---

## Technologies

- Python
- FAISS
- Sentence Transformers
- Transformers (Hugging Face)
- Mistral-Nemo-Instruct
- PyTorch
- FastAPI
- PyPDF2
- ngrok

---

## Workflow

1. Load PDF document
2. Extract text
3. Split text into chunks
4. Generate embeddings
5. Build FAISS vector index
6. Receive user question
7. Retrieve relevant document chunks
8. Generate answer using Mistral LLM
9. Return response through FastAPI

---

## Project Structure

```
.
├── finaltask.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/RAG-Question-Answering-System.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Example Pipeline

```
PDF Document
      │
      ▼
Text Extraction
      │
      ▼
Text Chunking
      │
      ▼
Sentence Embeddings
      │
      ▼
FAISS Vector Database
      │
      ▼
Semantic Search
      │
      ▼
Mistral LLM
      │
      ▼
Generated Answer
```

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- FAISS Indexing
- Large Language Models (LLMs)
- Prompt Engineering
- Hugging Face Transformers
- FastAPI Development
- REST API Deployment

---

## Future Improvements

- Support multiple uploaded documents
- Add conversational memory
- Improve prompt engineering
- Deploy using Docker
- Integrate a web interface
- Add authentication and user management

---

## Author

**Mariam Essam**

Computer Engineering Student | Data Analyst | AI & Machine Learning Enthusiast
