# Automotive LLM Assistant

## Overview
An AI-powered automotive assistant that uses Retrieval-Augmented Generation (RAG) to answer vehicle-related questions using company documentation and knowledge bases.

## Features
- Document ingestion
- Semantic search
- Vector embeddings
- AWS Bedrock integration
- LangChain orchestration
- RAG pipeline

## Tech Stack
- Python
- AWS Bedrock
- LangChain
- FAISS
- FastAPI
- Docker

## Architecture

User Query
    ↓
Embedding Model
    ↓
FAISS Vector Store
    ↓
AWS Bedrock LLM
    ↓
Generated Response

## Future Enhancements
- Multi-document support
- Chat history memory
- Fine-tuned domain-specific LLMs
- Real-time monitoring

## Author
Revanth Reddy
