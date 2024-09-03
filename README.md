# advanced_rag

advanced graph and vector-based RAG AI chatbot using LlamaIndex, LangChain, Hugging Face APIs, Haystack, Rasa, Wagtail, PostgreSQL, Neo4j, and Milvus. This setup includes:

A FastAPI application for the main chatbot logic
LlamaIndex and LangChain for RAG capabilities
Hugging Face Transformers for the language model
Haystack for document retrieval (integrated into the RAG service)
Rasa for intent classification
Wagtail for content management
PostgreSQL for general data storage
Neo4j for graph-based knowledge representation
Milvus for vector similarity search
Redis for rate limiting
User authentication
Background tasks for updating indexes
Error handling and logging
Dockerized application for easy deployment with terraform and aws
