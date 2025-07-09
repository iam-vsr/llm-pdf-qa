# 🧠 PDF Question Answering System using LLMs

This project demonstrates how to build a document-based Question Answering (QA) application using a Large Language Model (LLM). Users can upload a PDF file and ask questions based on its content. The system retrieves relevant chunks from the document using semantic search and feeds them into an LLM to generate accurate, context-aware answers.

---

## 🚀 Features

- 📄 **PDF Parsing**: Reads and processes any PDF file.
- ✂️ **Chunking**: Splits text into overlapping token-based chunks.
- 🔍 **Semantic Search**: Uses `FAISS` and sentence embeddings for relevant context retrieval.
- 🧠 **LLM-Powered QA**: Utilizes HuggingFace LLM (LLaMA 2) to answer user queries.
- 🌐 **Gradio Interface**: Clean and simple web UI for interaction.

---

## 🛠️ Tech Stack

| Component        | Tool/Library                         |
|------------------|--------------------------------------|
| LLM              | `meta-llama/Llama-2-7b-chat-hf`      |
| Embeddings       | `thenlper/gte-base`                  |
| PDF Reading      | `PyPDF`                              |
| Vector Store     | `FAISS`                              |
| Prompt Handling  | `LangChain`                          |
| UI               | `Gradio`                             |

---


