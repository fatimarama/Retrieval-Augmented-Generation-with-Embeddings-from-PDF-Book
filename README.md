# Project Description
This project uses Retrieval-Augmented Generation (RAG) to create a powerful information retrieval system, by using embeddings generated from a PDF book. By combining state-of-the-art models for embedding generation and retrieval, this project aims to enhance the accuracy and relevance of the generated responses.

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

## Workflow:
  ### 1. Data Preparation:
  - Conversion of the PDF book into a suitable format for embedding generation.

  ### 2. Embedding Generation:
  - Utilization of Groq, and all-MiniLM-L6-v2 models to create embeddings from the text.
  - Storing embeddings in Qdrant for efficient retrieval.

  ### 3. Retrieval-Augmented Generation:

  - Implementing a retrieval system to fetch relevant embeddings from Qdrant based on user queries.
  - Generating responses by combining retrieved embeddings and Llama-3.1-70b-versatile model responses.

## Results and Performance:
  - **Accuracy:** The project aims to improve the relevance and accuracy of generated responses by combining embeddings and retrieval.
  - **Efficiency:** Utilization of embedding models and Qdrant ensures quick retrieval and generation processes.
