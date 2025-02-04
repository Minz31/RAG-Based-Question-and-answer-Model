# 🌍 Climate Change PDF Q&A System 🔍📄  

This repository contains a **Retrieval-Augmented Generation (RAG) Q&A system** that allows users to ask questions about **climate change** based on the contents of a PDF document. Using **state-of-the-art NLP techniques**, the system retrieves **relevant document chunks** and generates **detailed, contextual responses** using a **large language model (LLM)**.

---

## 🚀 Features
- 📚 **PDF-Based Knowledge Retrieval** – Extracts and processes text from climate-related PDFs.  
- 🔍 **Semantic Search with Embeddings** – Uses **sentence-transformers (all-mpnet-base-v2)** for **vector-based** document retrieval.  
- 🧠 **LLM-Powered Answer Generation** – Utilizes **Google's FLAN-T5 Large** for **natural language understanding** and response generation.  
- ✅ **RAG (Retrieval-Augmented Generation)** – Enhances factual accuracy by retrieving **relevant document sections** before answering.  
- 🔗 **Transparent Source Referencing** – Displays source **page numbers** for credibility.  
- 💬 **Interactive Chatbot Interface** – Supports user queries in a simple, conversational format.  

---

## ⚙️ Tech Stack
- **Language Model:** Google **FLAN-T5 Large** (Hugging Face Hub)  
- **Vector Database:** **DocArrayInMemorySearch** for efficient **semantic search**  
- **Text Processing:** **LangChain** for document chunking and retrieval  
- **Embeddings Model:** **sentence-transformers/all-mpnet-base-v2**  
- **PDF Parsing:** **PyPDFLoader**  
- **Backend:** Python, LangChain  

---

## 📂 How It Works
1. **PDF Loading** – The system reads and extracts text from a **climate change-related PDF**.  
2. **Chunking** – Splits text into **manageable, overlapping chunks** for better retrieval.  
3. **Embedding & Vector Storage** – Converts chunks into **vector embeddings** for efficient similarity search.  
4. **Retrieval & Answer Generation** – When a user asks a question, the system:  
   - Finds the **top 5 most relevant document sections**.  
   - Generates a **detailed answer** using **FLAN-T5 Large**.  
   - Displays **source document references** for verification.  
5. **Interactive Q&A** – Users can query the system in a **chat-like loop**.  

---
