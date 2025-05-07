# 📊 ITC Financial Assistant – AI-Powered Q&A App

This Streamlit-based application allows you to ask financial questions about **ITC Ltd.** using natural language. It uses a **Chroma vector database** and a **SentenceTransformer model** to find and answer questions from financial documents like annual reports and investor presentations.

---

## 🚀 Features

- ✅ Ask finance-related questions in plain English
- ✅ Retrieves answers from a local vector database (ChromaDB)
- ✅ Semantic search with `all-MiniLM-L6-v2`
- ✅ Fast and lightweight Streamlit app
- ✅ Built for Hugging Face Spaces

---

## 🧠 How It Works

1. Embedding of ITC documents using `SentenceTransformer`
2. Stored in `chroma_db/` using `Chroma` vector store
3. App encodes your query, compares embeddings
4. Returns the most relevant financial content

---

## 🗂️ Project Structure

