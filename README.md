# 🧠 Retrieval-Augmented Generation with LLaMA 3 and Wikipedia

This project demonstrates a complete Retrieval-Augmented Generation (RAG) pipeline using **Meta's LLaMA 3.1** model and **Wikipedia** as the knowledge source. It includes document chunking, embedding generation, vector storage (FAISS), and natural language querying via a simple web interface.

## 🚀 Overview

1. **Load Wikipedia Data**
2. **Split into Chunks**
3. **Generate Embeddings**
4. **Store in FAISS Vector DB**
5. **Run Inference with LLaMA 3.1**
6. **Query via Gradio Interface**

## 🛠 Requirements

- **Python ≥ 3.8**
- **CUDA-enabled GPU**
- **Hugging Face Account** with access to LLaMA 3.1
- Required packages:
  - `datasets`, `sentence-transformers`, `langchain`, `transformers`, `faiss-cpu`, `gradio`, `torch`, `accelerate`

## 🔐 Hugging Face Access Token

To use Meta’s LLaMA 3.1, you must:
1. Accept the model license on [Hugging Face](https://huggingface.co/meta-llama).
2. Run:
   ```bash
   huggingface-cli login