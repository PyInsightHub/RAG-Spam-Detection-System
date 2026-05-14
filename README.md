# 🧠 RAG-Based Spam Detection System

A Retrieval-Augmented Generation (RAG) pipeline for intelligent spam detection
using FAISS vector search, Sentence Transformers, and Google Gemini LLM.

---

## 🚀 Project Overview

This system retrieves semantically similar messages from a vector database and
uses LLM-powered reasoning to classify and explain spam predictions.

**Tech Stack:**
- 🔤 Sentence Transformers (`all-MiniLM-L6-v2`)
- 🗃️ FAISS Vector Database
- 🤖 Google Gemini LLM (`gemini-1.5-flash`)
- 📊 Streamlit UI
- 🐼 Pandas, NumPy, Scikit-learn

---

## 🏗️ Architecture

User Query → Text Cleaning → Sentence Transformer Embeddings
→ FAISS Vector Search → Top-k Semantic Retrieval
→ Gemini LLM Reasoning → Spam/Ham Prediction

---

## 📦 Installation

```bash
git clone https://github.com/YOUR_USERNAME/RAG-Spam-Detection-System.git
cd RAG-Spam-Detection-System
pip install -r requirements.txt
```

---

## 🔑 Setup

1. Get your [Gemini API Key](https://aistudio.google.com/)
2. Create a `.env` file:
