# RAG Pipeline Implementation from Scratch

#### Overview
I have implemented a pipeline from scratch based on a YouTube video for Reference Augmented Generation (RAG). The pipeline involves several steps including book downloading, PDF reading, sentence splitting, grouping sentences into chunks, embedding preparation, semantic search, reranking, and feeding the query and embeddings into an open-source LLM (Large Language Model).

#### Pipeline Steps
1. **Book Downloading**
   - Implemented functionality to download books from online sources or local storage.

2. **PDF Reading**
   - Utilized libraries to read PDF files, extracting text for further processing.

3. **Sentence Splitting**
   - Segmented text into individual sentences for granular analysis.

4. **Sentence Grouping**
   - Aggregated sentences into groups of 10 sentences each for efficient processing.

5. **Embedding Preparation**
   - Utilized the Hugging Face all-mpnet-base-v2 model to prepare embeddings for the text data.

6. **Embedding Saving**
   - Saved the embeddings as CSV files for later retrieval and analysis.

7. **Semantic Search**
   - Implemented semantic search functionality to retrieve relevant information based on query embeddings.

8. **Reranking**
   - Utilized the Hugging Face mixedbread-ai/mxbai-rerank-large-v1 model to rerank retrieved embeddings for improved accuracy.

9. **Integration with Open Source LLM**
   - Fed queries and embeddings into an open-source Large Language Model (LLM) for better output.

**Thanks to 🫡: Daniel Bourke [Youtube](https://youtu.be/qN_2fnOPY-M?si=Y9DwTiOLt7RfNvPV)**