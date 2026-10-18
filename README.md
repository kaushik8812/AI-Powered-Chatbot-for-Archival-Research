# AI-Powered Chatbot for Archival Research

An AI-powered chatbot that helps researchers explore approximately 5,400 digitised vocational training documents through natural-language questions.

## Project Overview

Developed as part of a Summer 2026 research lab at the University of Koblenz, this project extends the Berufearchiv digital archive with a Retrieval-Augmented Generation (RAG) chatbot.

Users can ask questions in German or English and receive answers grounded in relevant archival document passages.

## Key Features

- Natural-language question answering over archival documents.
- Retrieval of relevant document passages to support generated answers.
- Conversational follow-up questions with session history.
- Multilingual document retrieval using BAAI/bge-m3 embeddings.
- Qdrant vector search.
- FastAPI service integration.

## How It Works

1. Documents are split into smaller text chunks.
2. Chunks are converted into embeddings and indexed in Qdrant.
3. Relevant passages are retrieved for each user question.
4. Retrieved context is passed to a language model through the university's HAWKI API.
5. The chatbot returns an answer based on the retrieved context.

## Technology Stack

Python, FastAPI, LangChain, Qdrant, BAAI/bge-m3, RAG, Drupal, Islandora.

## My Contribution

This was a collaborative university research project.

- [Replace with components you personally implemented.]
- [Replace with your testing, evaluation, or integration contributions.]

## Project Context

- Institution: University of Koblenz, Germany
- Project: Summer Research Lab 2026
- Focus: AI, NLP, Information Retrieval, and Data Engineering

This repository presents a project overview. The original implementation is maintained in the university's private GitLab repository.
