# 🧠 AI Web Scraper & News Agent

An intelligent AI-powered assistant that performs **contextual web scraping** or switches to **API-based search** depending on the user's query. Built using Langchain, LangGraph, and Groq's LLM, this agent empowers users to gather deep, up-to-date insights from the internet with ease.

---

## 🚀 Project Goals

- Build an AI agent that dynamically chooses between real-time **web scraping** and **API-based search**.
- Allow users to retrieve **context-rich**, **structured**, and **latest information** from the internet.
- Provide easy access to **AI news summaries**, **website analysis**, and **custom data extraction**.
- Export all results in user-friendly formats like **CSV**, **JSON**, and **PDF**.

---

## 🛠️ Key Features

### ✅ Smart Query Handling
- Uses **TaivlySearch API** for simple, definition-based or conversational queries.
- Switches to **custom web scraping** for time-sensitive or in-depth data queries.

### 🌐 Website Understanding
- Accepts any URL, scrapes the full page including sub-links.
- Converts scraped content into markdown and stores it as **vector embeddings** using **OllamaEmbeddings + FAISS**.
- Enables **LLM-based question answering** with full reasoning and deep context.

### 📊 Targeted Data Extraction
- Supports queries like: “Find all hotels in Goa with price, ratings, reviews.”
- Scrapes multiple sources, structures the data into a table format.
- Allows exporting results in **CSV**, **JSON**, or **PDF** formats.

### 📰 AI News Summarizer
- Fetches and summarizes the latest AI news based on time filters (week, month, year).
- Provides downloadable summaries in **PDF**, **Text**, or **Markdown**.

---

## 🧩 Tech Stack

| Component           | Tool/Library                     |
|--------------------|----------------------------------|
| Programming Lang.   | Python                           |
| LLM Provider        | Groq (`llama-3.1-8b-instant`)    |
| Frameworks          | Langchain, LangGraph             |
| Web Scraping        | Requests, BeautifulSoup          |
| Vector Database     | FAISS                            |
| Embeddings          | OllamaEmbeddings                 |
| Search API          | TaivlySearch                     |
| Memory Handling     | LangGraph Checkpointer           |

---
