---
title: Multi Tool Agent
emoji: 🤖
colorFrom: blue
colorTo: purple
sdk: docker
pinned: false
---

# Multi-Tool Agent — Agentic AI with Tool Routing

A multi-tool AI agent that routes questions to the right tool: calculator for math, web search for current information, and RAG retrieval for knowledge base queries. Built with Groq, FastAPI, FAISS, and Tavily.

## API Endpoints

- `POST /ask` — Send a question, get a routed answer
- `GET /health` — Health check
- `GET /docs` — Swagger UI

## Tools

- **Calculator** — Precise arithmetic using Python eval with safety restrictions
- **Web Search** — Live internet search via Tavily API
- **RAG Retrieval** — Semantic search over AI/ML knowledge base using FAISS

## Stack

Groq (Llama 3.3 70B) · FastAPI · Pydantic · sentence-transformers · FAISS · Tavily · Docker