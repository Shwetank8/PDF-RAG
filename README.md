# 📄 PDF Retrieval-Augmented Generation (RAG)  

A **Retrieval-Augmented Generation (RAG)** pipeline for interacting with PDF documents.  
This project lets you upload PDFs, store them in a **Qdrant vector database**, and ask questions about the content using **OpenAI’s API** with **LlamaIndex** as the orchestration layer.  

It also integrates with **Inngest** for background event-driven processing and uses **FastAPI** as the backend framework.  

---

## 🚀 Features  
- 📂 **PDF Ingestion** → Upload and parse PDFs.  
- 🧩 **Chunking & Embeddings** → Split PDFs into text chunks using LlamaIndex and embed them.  
- 📦 **Vector Store** → Store embeddings in **Qdrant** for fast semantic search.  
- 🤖 **RAG Pipeline** → Retrieve relevant chunks and augment prompts for the OpenAI API.  
- ⚡ **FastAPI Backend** → Serve endpoints for uploading, querying, and interacting.  
- 🪄 **Inngest Integration** → Handle background tasks like ingestion events.  

---

## 🛠️ Tech Stack  
- **Python** → Core language  
- **FastAPI** → Web framework  
- **Inngest** → Event-driven workflow orchestration  
- **Qdrant** → Vector database  
- **OpenAI API** → Large Language Model for answering queries  
- **LlamaIndex** → Document parsing, chunking, and retrieval orchestration  

---
