# LLM Agent Workflows

Two practical LLM agents implemented in a Jupyter notebook:

- a LangChain RAG study assistant that searches PDF materials with FAISS, explains concepts, remembers the conversation, and generates revision questions;
- a LangGraph movie recommender that extracts preferences from natural language, builds Kinopoisk API filters, and returns a curated top three.

## Stack

Python, LangChain, LangGraph, FAISS, Sentence Transformers, OpenRouter, and Kinopoisk API.

## Usage

Install `requirements.txt`, set the `OPENROUTER_API_KEY` and `KINOPOISK_API_KEY` environment variables, and open `llm_agent_workflows.ipynb`.

The RAG example expects a local PDF with study materials. The course document used during development is intentionally not included.
