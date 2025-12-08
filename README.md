# Multi-modal Semantic Search Engine (SSE)

A Retrieval-Augmented Generation (RAG) system that performs semantic search across unstructured image datasets using OpenAI's CLIP model and ChromaDB.

## Features
*   **Multi-modal Embedding:** Aligns text and images in a shared latent space using CLIP (Contrastive Language-Image Pre-Training).
*   **Vector Search:** Utilizes ChromaDB for efficient approximate nearest neighbor retrieval.
*   **Normalization:** Implements L2 vector normalization to ensure cosine similarity accuracy across high-variance inputs.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1.  Place your images in the `images/` folder.
2.  Run the main script:
    ```bash
    python main.py
    ```
3.  Enter a search query (e.g., "healthy green food").

## Tech Stack
*   **Python 3.10+**
*   **Transformers (HuggingFace)**
*   **ChromaDB**
*   **PyTorch**
