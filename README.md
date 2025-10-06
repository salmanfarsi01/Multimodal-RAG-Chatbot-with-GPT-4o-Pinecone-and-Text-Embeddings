# Multimodal RAG Chatbot with GPT-4o, Pinecone, and Text Embeddings

## Overview

This project implements a **Retrieval-Augmented Generation (RAG) Chatbot** capable of processing and generating responses based on multimodal content, including PDFs, Docs, audio, and video files. The chatbot combines a powerful GPT-4o language model with Pinecone for efficient vector database storage and retrieval. The system is designed to process text data from various formats using embeddings from `text-embedding-3-small`, and text chunking is handled by `RecursiveCharacterTextSplitter`.

## Key Features

- **Multimodal Support**: Processes and responds to queries from PDFs, Docs, audio, and video files.
- **Pinecone Vector Database**: Uses Pinecone for fast and scalable vector search and retrieval.
- **GPT-4o Language Model**: Leverages GPT-4o for context-aware and intelligent responses.
- **Efficient Text Chunking**: Utilizes `RecursiveCharacterTextSplitter` to handle large documents and generate meaningful chunks.
- **Text Embeddings**: Uses `text-embedding-3-small` for effective semantic representation of content.

## Installation

To use this project, follow these steps:

### Prerequisites

Make sure you have Python 3.x installed. Additionally, you will need the following libraries:

- `pinecone`
- `openai`
- `text-embedding-3-small`
- `RecursiveCharacterTextSplitter`

You can install the necessary libraries using `pip`:
install langchain langchain-community==0.2.0 langchain-openai pinecone==3.2.2 tiktoken pypdf docx2txt langchain-pinecone openai-whisper
upgrade --force-reinstall numpy pillow pytesseract


