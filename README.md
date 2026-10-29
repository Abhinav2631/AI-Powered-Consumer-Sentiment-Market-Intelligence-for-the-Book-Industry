# AI-Powered Consumer Sentiment & Market Intelligence for the Book Industry

This project repository covers a data pipeline and prototype interface for analysing consumer feedback about books and publishing. The documented workflow includes data collection, cleaning, sentiment/topic/aspect labels, and an exploratory retrieval-augmented generation (RAG) interface.

## Workflow documented in this repository

1. **Data collection:** public YouTube book-review comments, news articles, and book metadata.
2. **Preprocessing:** clean and normalise text into a common format.
3. **Sentiment and topic analysis:** organise feedback into sentiment, topic, and aspect fields.
4. **RAG exploration:** retrieve relevant feedback to support question answering and prototype market-insight views.

## Technology stack

Python, Requests, Pandas, NLTK, YouTube Data API, NewsAPI, LangChain, ChromaDB, Hugging Face Sentence Transformers, Groq API, and Streamlit.

## Setup

1. Create a Python virtual environment.
2. Install the packages listed in `requirements.txt`.
3. Configure the API credentials listed in `.env.example` using your own provider keys.
4. Start the Streamlit application with the command documented by the project setup.

Never commit private API keys or credentials.

## Project status

This repository includes source files and datasets for the documented workflow. The RAG/dashboard integration and deployment status should be checked against the current code before treating the project as production-ready.

## Source and attribution

This repository is a GitHub fork of [AI-Powered Consumer Sentiment & Market Intelligence for the Book Industry by Shahya1310](https://github.com/Shahya1310/AI-Powered-Consumer-Sentiment-Market-Intelligence-for-the-Book-Industry). The current public fork retains the upstream implementation and datasets with a revised project README; it should not be represented as a fully independent implementation from scratch. Credit for the upstream source remains with its original creator.

Any original code, data transformations, experiments, or modules added later should be documented clearly in the relevant files and commits.
