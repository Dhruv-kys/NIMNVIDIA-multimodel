# Nvidia NIM RAG PDF QA
A Streamlit-based **Retrieval-Augmented Generation (RAG)** application using Nvidia AI endpoints.  
This app allows you to ask questions from PDF documents using **NvidiaEmbeddings** and **ChatNVIDIA LLM**. FAISS is used as the vector store for efficient document retrieval.

## Features
- Load PDF documents from a folder and split into manageable chunks.
- Generate vector embeddings using **NvidiaEmbeddings**.
- Build and use a **FAISS** vector store for fast similarity search.
- Ask questions interactively through a **Streamlit UI**.
- Retrieve relevant document chunks and generate answers using **ChatNVIDIA**.
- Optionally view document similarity results.