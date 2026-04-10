# 📚 Contextual AI RAG (Vibe Version)

A simple Retrieval-Augmented Generation (RAG) system that:
- Accepts a document
- Splits it into chunks
- Creates embeddings
- Retrieves relevant context
- Generates accurate answers

---

## ⚡ Build

1. Open:
   https://cursor.sh  
   OR  
   https://replit.com  

2. Paste the Vibe Coding Prompt  
3. Run the project

---

## 🧾 Requirements

- Python 3.9+
  https://www.python.org/downloads/

Install dependencies:

pip install -r requirements.txt

---

## 🔑 API KEY

Provider: OpenAI

Get your API key:
https://platform.openai.com/signup

Set environment variable:

OPENAI_API_KEY=your_key_here

OR paste it when prompted on first run

---

## ▶️ Run

python main.py

---

## ⚡ First Run

- App asks for API key (if not set)
- Paste a document into terminal
- Press CTRL+D to finish input
- Ask questions interactively

---

## 💬 What It Does

- Splits document into chunks
- Uses OpenAI embeddings (text-embedding-3-small)
- Stores vectors in FAISS index
- Retrieves top relevant chunks
- Uses GPT-4o-mini to answer using context

---

## 🔥 Why This Version

- Same OpenAI API
- Same embedding + chat models
- Same FAISS-based retrieval
- Minimal and beginner-friendly
- Fully local vector search

---


## 🏷️ Tags

rag, openai, faiss, embeddings, llm, question-answering

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/238c02ae-b483-4a68-bdd2-1564cb013bb0" />






