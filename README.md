# RAG-Powered CV Enhancement Agent 🤖

## Overview
An intelligent CV enhancement agent that uses RAG (Retrieval Augmented Generation) 
to automatically enhance CVs based on job descriptions.

## Features
- 📄 Reads CV and job description files automatically
- 🔍 Uses vector similarity search to find relevant context
- ✍️ Enhances CV using only real information (no hallucination)
- 🔎 Built-in hallucination detection
- 🔄 Self-reflection loop until quality score >= 8/10
- ✅ Checks CV length and sections automatically

## Tech Stack
- Python
- LangChain
- ChromaDB (vector database)
- Groq LLM API (free)
- HuggingFace Embeddings
- Google Colab

## How it works
1. Upload your CV file (.docx, .pdf, .txt)
2. Upload job description file
3. Enter target job title
4. Agent automatically enhances your CV
5. Loop runs until CV scores 8+/10

## Setup
1. Open the notebook in Google Colab
2. Add your Groq API key to Colab secrets as 'GroqKey'
3. Run all cells in order
4. Upload your CV and job description files

## Results
- Automatically retrieves relevant context using RAG
- Detects and removes hallucinated content
- Iteratively improves CV with self-reflection
- Achieves quality score of 8+/10
