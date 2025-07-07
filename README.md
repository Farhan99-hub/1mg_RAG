# 1mg_RAG
End-to-end medical RAG pipeline using crawled 1mg data, FAISS, and Gemma-2B LLM for symptom-based question answering.


# 1mg RAG-based Medical Chatbot
This project implements a Retrieval-Augmented Generation (RAG) pipeline for answering medical questions related to drugs and diseases. The data is scraped from the 1mg platform and processed for efficient retrieval and generation.

## Project Overview
- **Web Scraping**: Medicinal and symptomatic data scraped using Crawl4AI.
- **Data Processing**: Cleaning and preprocessing of scraped text data.
- **Vector Store**: FAISS is used to store document embeddings for fast retrieval.
- **Language Model**: Google Gemma-2B model is used for text generation via LangChain.
- **RAG Pipeline**: Combines retrieval from FAISS with answer generation using Gemma-2B.

## Key Features
- Fast and relevant document retrieval using FAISS.
- Contextual answer generation using the Gemma-2B model.
- Modular pipeline for easy customization and extension.
- Designed for efficient deployment on cloud platforms.

## Tools Used
- Python
- LangChain
- FAISS
- Hugging Face Transformers
- Google Gemma-2B
- Crawl4AI (for web scraping)
- Pandas, NumPy, JSON

