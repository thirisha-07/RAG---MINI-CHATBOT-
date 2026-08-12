# RAG---MINI-CHATBOT-
A RAG-based mini chatbot for answering Taj Mahal queries using custom text documents. It uses LangChain, FAISS, Hugging Face embeddings, and Qwen2.5-3B-Instruct for semantic retrieval and response generation, with Self-RAG verification to validate and revise answers based on retrieved context.

## Project Description
A Retrieval-Augmented Generation (RAG) based mini chatbot designed to answer questions about the Taj Mahal using a custom text-based knowledge base. The system uses LangChain, FAISS, Hugging Face embeddings, and Qwen2.5-3B-Instruct for context retrieval and response generation.

## Objectives
- Build a domain-specific question-answering chatbot.
- Retrieve relevant information from text documents.
- Generate context-based responses using an LLM.
- Verify generated responses using a Self-RAG approach.

## Dataset
The dataset consists of `.txt` documents containing information about the Taj Mahal. These documents are loaded, divided into text chunks, converted into embeddings, and stored in a FAISS vector database for semantic retrieval.

## Technologies Used
- Python
- LangChain
- FAISS
- Hugging Face Transformers
- Sentence Transformers
- Qwen2.5-3B-Instruct
- Google Colab

## Requirements
- Python 3.x
- LangChain
- FAISS
- Sentence Transformers
- Hugging Face Hub
- Transformers
- LangChain Community
- LangChain Hugging Face

## RAG Workflow
1. Load Taj Mahal text documents
2. Split documents into chunks
3. Generate text embeddings
4. Store embeddings in FAISS
5. Retrieve relevant context
6. Generate answer using Qwen LLM
7. Verify the generated answer
8. Revise the answer if required


## Model
- Embedding Model: `sentence-transformers/all-MiniLM-L6-v2`
- Language Model: `Qwen/Qwen2.5-3B-Instruct`
- Vector Database: FAISS

## Features
- Context-aware question answering
- Semantic document retrieval
- Vector similarity search
- LLM-based response generation
- Self-RAG answer verification
