# Medical-Query-Answering-System-using-LLMs-and-Vector-Databases

This project is designed to provide accurate and contextually relevant answers to medical questions. It integrates several key technologies:

1. Large Language Models (LLMs): Utilizes the GooglePalm model from the LangChain library for natural language understanding and generation.
2. Data Loading and Encoding: Loads medical questions from a CSV file using CSVLoader, and detects character encoding using the chardet library.
3. Embeddings: Employs the HuggingFace BAAI/bge-large-en model to create dense vector representations of the text, ensuring high-quality embeddings.
4. Vector Database: Uses FAISS for efficient similarity search and retrieval of relevant documents.
5. Retrieval-based QA: Sets up a question-answering system that retrieves relevant documents and generates responses based on the context using the RetrievalQA chain type from LangChain.
6. Web Interface: Provides a user-friendly interface built with ipywidgets for submitting queries and viewing results interactively.

This setup enables the system to answer complex medical questions accurately by leveraging advanced natural language processing and retrieval techniques.
