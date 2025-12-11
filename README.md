📘 SLM‑RAG: Lightweight Retrieval‑Augmented Generation on Colab

A minimal, fast, and efficient Retrieval‑Augmented Generation (RAG) pipeline built using Small Language Models (SLMs), MiniLM embeddings, and ChromaDB, fully optimized to run on Google Colab’s free GPU tier.

This notebook shows how to combine a 4‑bit‑quantized TinyLlama model with semantic retrieval to produce grounded, low‑latency answers using minimal compute.

✅ Features:

Small Language Model (TinyLlama‑1.1B) in 4‑bit quantization

MiniLM‑L6‑v2 embeddings for fast semantic search

ChromaDB vector store for retrieval

Strict prompt design to reduce hallucination

Retrieves only the most relevant document

Runs entirely on free Colab GPU

🚀 How It Works: 

Embed documents using MiniLM

Store vectors in ChromaDB

Encode the query

Retrieve the top relevant document

Build a strict context‑only prompt

Generate the final answer using TinyLlama
