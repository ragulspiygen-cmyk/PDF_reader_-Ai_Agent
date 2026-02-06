# personal PDF reader AI Agent
AI PDF Reader Agent is an intelligent AI-powered system that can read PDF documents, understand the content, and answer user questions based strictly on the information present in the PDF.

This project demonstrates the integration of:

Large Language Models (LLMs)

Document parsing

Context retrieval

Question answering over documents

The agent ensures responses are grounded in the document content instead of generating unrelated answers.
🧠 How It Works
Step 1 — PDF Ingestion

The system loads the PDF and extracts text content.

Step 2 — Text Processing

The extracted text is split into smaller chunks for better context retrieval.

Step 3 — Embedding & Storage

Text chunks are converted into vector embeddings and stored in a vector database.

Step 4 — Query Processing

When a user asks a question:

The system converts the query into embedding

Retrieves relevant text chunks

Sends context + query to LLM

Generates grounded answer

🛠️ Tech Stack
Language:
Python

AI / ML:
LLM API

Embeddings Model

Document Processing

PDF Parser Libraries
