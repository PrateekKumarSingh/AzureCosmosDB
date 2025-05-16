# A Movie Chatbot powered by Azure Cosmos DB and Azure OpenAI Service.

In this sample, we'll demonstrate how to build a RAG (Retrieval Augmented Generation) pattern application with Unified Memory (Vector Search & Chat History)

Using a subset of the popular [Movie Lens 1M dataset](https://grouplens.org/datasets/movielens/1m/). This sample performs RAG over movie data with vector search, stores conversational chat history, and leverages a semantic cache, all using Azure Cosmos DB and its built-in vector search capability. Azure OpenAI Service is used to generate embeddings and LLM completions.
