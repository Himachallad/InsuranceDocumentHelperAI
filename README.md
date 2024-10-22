# Insurance Document Helper AI

## Installation
- We will be using Python `3.12.2` for this lab.
- Do `pip install -r requirements.txt`

## Project Overview

This project implements a robust **Generative Search System** for answering queries from complex insurance documents like policies and claims. Using **LlamaIndex**, the system performs semantic search to understand the context and provide precise answers to user queries.

### Key Features

- **Document Loading**: Uses `SimpleDirectoryReader` to efficiently load and parse PDFs.
- **Chunking and Splitting**: Utilizes default sentence splitting to break down documents logically.
- **Semantic Search**: Implements `VectorStoreIndex` for context-aware search based on semantic embeddings.
- **Top-k Results**: Configured the query engine to return the **top 3 most relevant** results (`similarity_top_k=3`).
- **Evaluation**: System quality was assessed using **human feedback**, resulting in accurate and satisfactory responses.

## Data Sources

The system processes **PDF documents** of insurance policies and claims, which are stored in a directory and loaded using **SimpleDirectoryReader**.
