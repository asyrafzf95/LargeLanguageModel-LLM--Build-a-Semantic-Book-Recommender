# 📚 LLM-Powered Semantic Book Recommender

This project leverages **Large Language Models (LLMs)** and **vector search** to build a smart, emotion-aware **book recommendation engine**. From genre classification and emotional tone analysis to semantic search and a beautiful **Gradio dashboard**, this system allows users to find books that *feel* just right — emotionally, thematically, and stylistically.

---

## 🔍 Features

### ✅ Semantic Search
Find books based on natural language queries (e.g., “a story about forgiveness” or “science fiction with emotional depth”), using OpenAI embeddings and vector similarity search.

### 🏷️ Zero-Shot Genre Classification
Automatically classifies book descriptions into **Fiction** or **Nonfiction**, using a transformer-based zero-shot classification model.

### 💬 Emotion & Sentiment Analysis
Analyzes book descriptions to detect dominant emotional tones like **joy**, **sadness**, **fear**, **surprise**, and more using an emotion-aware transformer model.

### 🖼️ Interactive Gradio Dashboard
Explore books through a clean UI:
- Search by natural language
- Filter by genre
- Refine by emotional tone
- Browse recommendations visually with book covers and summaries

---

## 🧠 Tech Stack

- **LLMs & Transformers**: OpenAI, Hugging Face (BART, RoBERTa)
- **Embeddings**: `OpenAIEmbeddings`
- **Vector Database**: `Chroma`
- **Document Pipeline**: `LangChain`
- **UI**: `Gradio`
- **Data**: Cleaned book metadata and descriptions
- **Environment Management**: `python-dotenv`

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/asyrafzf95/LargeLanguageModel-LLM--Build-a-Semantic-Book-Recommender
