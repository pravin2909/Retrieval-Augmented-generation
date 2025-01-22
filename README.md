# Retrieval-Augmented Generation (RAG) Project

This repository demonstrates a Retrieval-Augmented Generation (RAG) pipeline using **LangChain**, **Flan-T5 Large**, **ChromaDB**, **sentence-transformers/all-MiniLM-L6-v2**,**Gradio** and other supporting libraries to answer user queries based on a custom dataset.

---

## Overview

Retrieval-Augmented Generation (RAG) combines the strengths of information retrieval and language models. In this project:

1. **Retrieval**: Relevant context is retrieved from a custom dataset using **ChromaDB**.
2. **Generation**: The retrieved context is passed to the **Flan-T5 Large** model via **LangChain** to generate context-aware responses.
3. **Embedding Generation**: Embeddings for document similarity and efficient retrieval are created using **sentence-transformers/all-MiniLM-L6-v2**.

---

## Key Features

- **PDF Integration**: Users can upload PDF files for indexing and querying.
- **Interactive UI**: A user-friendly interface is built with **Gradio**.
- **Custom Dataset Retrieval**: Relevant context is retrieved using **ChromaDB** and **sentence-transformers/all-MiniLM-L6-v2**.
- **Context-Aware Responses**: **Flan-T5 Large** model is used for generating accurate, context-based answers via **LangChain**.
- **Embedding Generation**: **sentence-transformers/all-MiniLM-L6-v2** is used to generate embeddings for efficient document retrieval and similarity measurement.

---



