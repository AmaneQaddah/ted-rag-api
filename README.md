# ted-rag-api
# TED Talk RAG API

This project implements a Retrieval-Augmented Generation (RAG) system over a TED Talks dataset.
The system answers questions strictly based on retrieved transcript chunks.

## Live Deployment
- Base URL: https://ted-rag-api-three.vercel.app
- API Docs (Swagger): https://ted-rag-api-three.vercel.app/docs

## Usage

### POST /api/prompt
Send a natural language question to the system.

**Request body:**
```json
{
  "question": "Your question here"
}
