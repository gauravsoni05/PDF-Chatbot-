# RAG-based Chatbot for PDF and Excel Q&A with Streamlit Interface
This project implements a Retrieval-Augmented Generation (RAG) chatbot that answers user queries from PDF and Excel files. It uses open-source Large Language Models (LLMs) for natural language understanding and response generation. The interface is built using Streamlit, and text embeddings are created using Llama 3, indexed and stored in a Chroma vector database. Result reranking leverages Cohere’s multilingual rerank model for enhanced information retrieval.

### Features:
- Document Upload: Supports PDF and Excel files.
- Text Chunking: Splits documents into manageable text chunks for processing.
- Embeddings Generation: Uses Llama 3 to create embeddings.
- Vector Database: Stores embeddings in Chroma for efficient retrieval.
- Advanced Reranking: Applies Cohere’s rerank-multilingual model for precise query results.
- Interactive UI: User-friendly Streamlit interface for Q&A interactions.
