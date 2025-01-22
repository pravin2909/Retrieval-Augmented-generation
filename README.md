# Retrieval-Augmented Generation (RAG) Project

This repository contains a project demonstrating Retrieval-Augmented Generation (RAG) using the **Flan-T5 Large** model, **ChromaDB**, and the **sentence-transformers/all-MiniLM-L6-v2** model for embedding generation.

---

## Overview

Retrieval-Augmented Generation (RAG) is a method that enhances the capabilities of language models by integrating retrieval techniques. In this project, a retrieval system was used to find relevant context from a custom dataset and provide it as input to a language model, enabling the generation of accurate, context-aware responses.

---

## Key Features

- **Custom Dataset Retrieval**: Relevant information is retrieved from a custom dataset stored in **ChromaDB**.
- **Contextual Responses**: The retrieved data is combined with a language model (Flan-T5 Large) to generate precise and contextually relevant outputs.
- **Embedding Generation**: Sentence embeddings are generated using **sentence-transformers/all-MiniLM-L6-v2** for efficient similarity searches.

---

## Installation and Requirements

To run this project, you need the following:

- Python 3.8+
- PyTorch
- Transformers
- ChromaDB
- Sentence-Transformers
- NumPy

### Install Dependencies
```bash
pip install torch transformers chromadb sentence-transformers numpy
