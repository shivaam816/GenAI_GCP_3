# GenAI_GCP_3
Created this repo for Assignment 3 purpose

# Assignment 3 — Simplified Agentic RAG System  

## Overview  
This project implements a **Simplified Agentic RAG System** using **LangGraph, Gemini (Vertex AI), and Pinecone**.  
The system retrieves knowledge snippets, generates an answer, critiques its completeness, and optionally refines the response.  

---

## Objectives  
- Build an **Agentic RAG workflow** with LangGraph  
- Use **Gemini for LLM and embeddings**  
- Store KB in **Pinecone vector DB**  
- Implement a **self-critique loop** for improved responses  

---

## Tech Stack  
- Python 3.10+  
- Libraries:  
  - `langchain`  
  - `langgraph`  
  - `pinecone-client`, `langchain-pinecone`  
  - `google-cloud-aiplatform`  
  - `pandas`, `pydantic`  
- Dataset: `self_critique_loop_dataset.json`  

---

## Install dependencies  
- pip install -r requirements.txt

---

## Test Queries

What are best practices for caching?

How should I set up CI/CD pipelines?

What are performance tuning tips?

How do I version my APIs?

What should I consider for error handling?

