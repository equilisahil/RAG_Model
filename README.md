# RAG_Model
📚 First RAG (Retrieval-Augmented Generation) Project . This project demonstrates a simple RAG pipeline using Chroma as the vector store. 
HuggingFace embeddings for document indexing, and Groq-hosted LLMs (like LLaMA 3) for fast and accurate question answering. It takes input documents, embeds them, stores them in a vector database, and retrieves relevant chunks to generate responses using an LLM.

This project demonstrates a basic Retrieval-Augmented Generation (RAG) pipeline using:

🧱 **Chroma** for vector storage  
🔍 **HuggingFace Embeddings** (e.g. `all-MiniLM-L6-v2`) for semantic search  
⚡ **Groq-hosted LLMs** (e.g. LLaMA 3) for fast, high-quality inference

📦 Features:

- Document loading and chunking
- Embedding and vector storage in Chroma
- Context-aware retrieval
- Query answering using Groq LLMs

📌 Dependencies
langchain
chromadb
sentence-transformers
groq

Access to Groq API and an API key set as an environment variable:
- export GROQ_API_KEY=your_key_here
