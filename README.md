# Chat-with-PFD
The code will process PDF files by extracting text, splitting it into chunks, and generating embeddings. It stores these embeddings in a FAISS vector database for efficient search. When the user asks a query, it retrieves relevant chunks and uses a QA model to generate responses based on the content.

STEP BY STEP PROCESS:
Import Libraries: Load tools for PDF text extraction, embeddings, and retrieval.
Set Directories Path: Define paths for PDFs and storing vector data.
Extract Text: Read and extract text from PDF pages.
Chunk Text: Split extracted text into smaller segments for better processing.
Generate Embeddings: Convert text chunks into vector embeddings.
Store Embeddings: Save embeddings and chunks in a FAISS vector database.
Handle Queries: Search for relevant chunks using user queries.
Generate Responses: Use a QA model to create answers from retrieved chunks.
