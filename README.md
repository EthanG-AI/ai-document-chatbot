# AI Document Chatbot

An enterprise Retrieval-Augmented Generation (RAG) chatbot that enables users to upload documents and ask natural language questions. Built with FastAPI, LangChain, FAISS, and OpenAI APIs.

## Features

- PDF document ingestion
- Semantic search with FAISS
- OpenAI GPT integration
- JWT Authentication
- REST API
- Docker support
- Easy deployment

## Tech Stack

- Python
- FastAPI
- LangChain
- OpenAI
- FAISS
- Docker

## Installation

```bash
git clone https://github.com/ethan-ai/ai-document-chatbot.git
cd ai-document-chatbot

pip install -r requirements.txt

uvicorn app:app --reload
```

## API

GET /

Returns API status.

## Roadmap

- User dashboard
- Multi-document support
- Conversation history
- PostgreSQL integration

## License

MIT
