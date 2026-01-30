# 🧠 DocuMind AI  
**RAG-Powered PDF Question Answering System**

DocuMind AI is an intelligent document assistant that allows users to upload PDFs and ask natural-language questions.  
It uses **Retrieval-Augmented Generation (RAG)** to ground LLM responses in document content, ensuring accurate and context-aware answers.

---

## 🚀 Features
- 📄 Upload and process multiple PDF documents
- 🔍 Semantic search using vector embeddings
- 🧠 LLM-powered question answering with contextual grounding
- 📚 Source-aware answers (responses are based on uploaded PDFs)
- ⚡ FastAPI backend with Streamlit frontend
- 🔄 Modular, extensible architecture

---

## 🏗️ Architecture Overview
1. **PDF Ingestion** – PDFs are uploaded and chunked
2. **Embedding Generation** – Text chunks converted to vector embeddings
3. **Vector Store** – Stored and retrieved using similarity search
4. **RAG Pipeline** – Relevant chunks injected into LLM prompt
5. **Response Generation** – LLM produces grounded answers

---

## 🛠️ Tech Stack
- **Backend:** FastAPI  
- **Frontend:** Streamlit  
- **LLMs:** Open-source / API-based LLMs  
- **Embeddings:** Sentence Transformers / HuggingFace  
- **Vector Store:** ChromaDB  
- **Language:** Python  

---

## 📂 Project Structure
