# 📄 PDF Chatbot using LangChain, Gemini, and ChromaDB

This is a simple **PDF-based Question-Answering Chatbot** built using **LangChain**, **Gemini Pro**, **ChromaDB**, and **Hugging Face Embeddings**. It allows users to upload a PDF and ask questions about its content in a conversational way.

---

## 🚀 Features

- 🧠 Uses **Gemini Pro** (Google's LLM) for answering questions.
- 📚 Supports **PDF uploading** and processes it into chunks.
- 🧩 Embeds content using **Hugging Face embedding models**.
- 📦 Stores and retrieves document chunks using **ChromaDB** (a vector database).
- 💬 Interactive UI built using **Gradio**.
- 🧪 Works in a **Jupyter Notebook / Google Colab** environment.

---

## 🛠️ Technologies Used

| Technology       | Purpose                                |
|------------------|----------------------------------------|
| LangChain        | LLM orchestration & document QA        |
| Gemini Pro       | Large Language Model for generation    |
| ChromaDB         | Vector storage & retrieval             |
| Hugging Face     | Embeddings model for document chunks   |
| Gradio           | UI interface for chat interaction      |
| PyMuPDF (fitz)   | PDF reading and parsing                |

---

## 🧰 Setup Instructions

> ✅ Recommended: Run this in **Google Colab** (no local setup needed)

### 🔧 1. Install Dependencies

```python
pip install langchain chromadb gradio google-generativeai pdfplumber transformers langchain-google-genai langchain-community 
import os
os.environ["GOOGLE_API_KEY"] = "your_google_api_key"
os.environ["HUGGINGFACEHUB_API_TOKEN"] = "your_huggingface_api_key"
