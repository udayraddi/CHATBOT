# CHATBOT

# Language Model (LLM):
Mistral 7B LLM is created using LlamaCpp.
Configured with specific parameters.

# Vector Store:
In-memory FAISS vector store is created using FAISS.
PDFs are processed using PyPDFLoader

# Text Processing:
PDF text content is extracted and split into chunks.
Chunks are transformed into embeddings using HuggingFaceEmbeddings

# Libraries and Dependencies:
Imports include os, tempfile, and tqdm.
External libraries: 'streamlit' , 'sentence-transformers', 'llama-cpp-python', 'faiss-cpu', 'pypdf'

