<div align="center">

# 🔎 Semantic Search with Cohere & Pinecone

**Find questions with the same meaning, even when they share no words, using Cohere embeddings and a Pinecone index.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"> <img src="https://img.shields.io/badge/Cohere-39594D?style=for-the-badge" alt="Cohere"> <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge" alt="Pinecone"> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face">

<a href="https://colab.research.google.com/github/KamranUmer/Cohere-and-Pinecone/blob/main/Cohere_AI%27s_LLM_for_Semantic_Search_in_Python.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>

</div>

<p align="center"><img src="https://github.com/KamranUmer/Cohere-and-Pinecone/assets/86089489/a8edded3-6681-4fd8-89c6-f7014512444d" alt="Semantic Search with Cohere & Pinecone screenshot" width="85%"></p>

## 📌 Overview

Keyword search fails when two questions mean the same thing but use different words. This notebook embeds questions with Cohere's language model, stores the vectors in Pinecone, and retrieves the most semantically similar questions for any query.

## 🔬 Pipeline

- **Data:** TREC question classification dataset (first 1,000 of 5.5K labelled questions)
- **Embeddings:** Cohere `embed` endpoint
- **Index:** Pinecone vector index with cosine similarity
- **Query:** embed a new question and return the closest matches with similarity scores

## 🚀 Getting Started

```bash
# Open the notebook in Google Colab (badge above), choose a GPU runtime,
# then run the cells from top to bottom.
# You need Cohere and Pinecone API keys (both have free tiers).
```

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
