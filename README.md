# Chatbot with Message History using LangChain and RAG

A conversational chatbot that retains conversation history and answers questions using Retrieval-Augmented Generation (RAG) powered by LangChain, Groq API, and Hugging Face embeddings.

## Features
- **Conversational Memory**: Retains chat history for contextual interactions.
- **Document Processing**: Splits and indexes text documents for RAG.
- **API Integration**: Uses Groq API for fast LLM inference and Hugging Face for embeddings.
- **Vector Database**: Stores embeddings in ChromaDB for efficient retrieval.

## Prerequisites
- Python 3.7+


## Installation
```bash
pip install langchain langchain-groq langchain-community huggingface_hub chromadb sentence-transformers python-dotenv
