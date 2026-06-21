# LangChain Document Summarizer

A simple NLP project that demonstrates document summarization using LangChain and Groq LLMs. This project implements three popular summarization techniques:

* Stuff Chain
* Map Reduce Chain
* Refine Chain

The application processes text documents and generates concise summaries using Large Language Models (LLMs).

## Features

* Text Summarization using LangChain
* Supports multiple summarization strategies
* Uses Groq LLMs for fast inference
* Easy-to-understand implementation
* Demonstrates practical use of LangChain chains

## Technologies Used

* Python
* LangChain
* Groq API
* Large Language Models (LLMs)

## Summarization Techniques

### 1. Stuff Chain

All document chunks are combined and sent to the LLM in a single request.

**Best for:** Small documents

### 2. Map Reduce Chain

Each document chunk is summarized individually, and the summaries are combined to generate a final summary.

**Best for:** Large documents

### 3. Refine Chain

An initial summary is created and then iteratively refined using additional document chunks.

**Best for:** Large documents where context preservation is important



## Author

Aditya G. Bhusawale

Computer Engineering Student
