# 🌐 Website Content QA Bot (Multi‑User, Ollama + LangChain)

This is a **self-hosted, multi-user website crawler + QA chatbot** built using:
- ⚙️ **LangChain** for RAG (Retrieval-Augmented Generation)
- 🧠 **Ollama** to run open-source LLMs and embeddings locally
- 🌍 **Recursive URL loader** to crawl and scrape websites
- 💬 **Gradio** for an interactive chat interface

> ✅ No OpenAI key required  
> ✅ Runs locally (or in Colab)  
> ✅ Private: Crawled content never leaves your machine  
> ✅ Each user session is isolated with separate vector storage

---

## 🧠 What It Does

1. Crawls a given website up to 3 levels deep
2. Scrapes and cleans page text using BeautifulSoup
3. Splits and embeds documents using Ollama’s local embedding model
4. Answers user questions using an LLM (e.g. `mistral:7b`) via LangChain RAG
5. Responds through an interactive chat interface
6. Keeps sessions isolated so multiple users don’t mix queries

---

## 🔧 Requirements

- Linux/Ubuntu or Google Colab
- Python 3.8+
- [Ollama](https://ollama.com) installed
- A supported GPU (optional, but recommended for speed)

---
