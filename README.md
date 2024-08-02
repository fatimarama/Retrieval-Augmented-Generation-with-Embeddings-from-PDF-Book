# Project Description
This project demonstrates the use of Retrieval-Augmented Generation (RAG) to create a powerful information retrieval system, by using embeddings generated from a PDF book. By combining state-of-the-art models for embedding generation and retrieval, this project aims to enhance the accuracy and relevance of the generated responses.

## Key Components:
### 1. PDF Book Embeddings:
  - **Source:** A comprehensive PDF book used to generate embeddings.
  - **Embedding Models:**
    - **Groq:** Utilized for high-performance embedding generation.
    - **all-MiniLM-L6-v2:** A lightweight model for creating efficient and effective embeddings.
    - **Llama-3.1-70b-versatile:** Used for geenrating relevant responses.

### 2. Retrieval-Augmented Generation (RAG):

  - **Retrieval Module:** Efficiently retrieves relevant information based on the query.
  - **Generation Module:** Uses retrieved information to generate accurate and contextually relevant responses.

### 3. Qdrant:
  - **Vector Database:** Used for storing and retrieving embeddings efficiently. Qdrant provides high-performance, real-time vector similarity search capabilities, making it an ideal choice for this project.
