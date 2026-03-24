# 🚀 RAG API with FastAPI

A lightweight, modular, and production‑ready **Retrieval‑Augmented Generation (RAG)** API built with **FastAPI**. This project enables intelligent, context‑aware responses by combining vector‑based document retrieval with LLM generation. It’s designed for developers who want a simple, extensible, and high‑performance RAG backend.

---

## 📌 Overview

This API provides a complete RAG workflow:

- Ingest documents  
- Chunk and embed text  
- Store embeddings in a vector database  
- Retrieve relevant context  
- Generate grounded responses using an LLM  

Everything is exposed through clean, async FastAPI endpoints.

---

## ✨ Features

- ⚡ **FastAPI-powered REST API**  
- 📄 **Document ingestion & preprocessing**  
- 🔍 **Vector search** using FAISS/Chroma/Pinecone  
- 🧠 **RAG workflow** combining retrieval + LLM generation  
- 🔧 **Configurable embedding + LLM providers**  
- 🐳 **Docker-ready** for deployment  
- 📁 **Clear project structure** for maintainability  

---

## 🧱 Tech Stack

- **Python 3.x**  
- **FastAPI**  
- **Vector DB** (FAISS, Chroma, Pinecone, etc.)  
- **LLM Provider** (OpenAI, Azure OpenAI, etc.)  
- **Docker** (optional)

---

## 📂 Project Structure

```
├── app/
│   ├── api/            # Route handlers and API endpoints
│   ├── core/           # Config, settings, and initialization logic
│   ├── models/         # Pydantic models and schemas
│   ├── services/       # RAG pipeline, embeddings, vector DB, LLM logic
│   ├── utils/          # Helper functions and shared utilities
│   └── main.py         # FastAPI entrypoint
├── data/               # Source documents or embeddings (optional)
├── requirements.txt     # Python dependencies
└── README.md
```
---

## 🚦 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Prbn/RAG_API_w_FastAPI.git
cd RAG_API_w_FastAPI
```

### 2. Install dependencies
```
uvicorn app.main:app --reload
```

### 5. Access API docs
```
http://localhost:8000/docs
```

## 📚 Use Cases

- **Domain‑specific chatbots**  
- **Internal knowledge base search**  
- **Customer support automation**  
- **AI‑powered search for documents, PDFs, logs, etc.**  

## 🤝 Contributing
Contributions, issues, and feature requests are welcome.
Feel free to open a PR or start a discussion.



