# 🎯 RAG Ticket Resolution Bot (LangChain + FAISS + Groq)

💻 **Live Demo (Streamlit):** [https://rag-ticket-resolution-bot-kv6bxbc59b2vvpayjpgmw7.streamlit.app/](https://rag-ticket-resolution-bot-kv6bxbc59b2vvpayjpgmw7.streamlit.app/) 

A **Retrieval Augmented Generation (RAG)** based intelligent Support Ticket Resolution System built using **LangChain, FAISS Vector Database, Groq LLM and Streamlit UI.**

This project helps support teams automatically **retrieve similar past tickets and generate AI-based suggested solutions in real-time.**

---

## 🚀 Features

✅ Semantic Search using FAISS

✅ Fast LLM Response using Groq API

✅ Retrieval Augmented Generation (RAG) Architecture

✅ Streamlit Interactive UI

✅ Real-time Suggested Solution Generation

✅ Similar Ticket Retrieval

✅ Scalable Vector Store Architecture

✅ Modular Code Structure (Production Ready)

---

## 🧠 System Architecture

User Query → Embeddings → FAISS Vector DB → Retriever → Groq LLM → Final Suggested Solution

---

## 📂 Project Folder Structure

```
rag-ticket-bot/
│
├── app.py
├── requirements.txt
│
├── data/
│   └── tickets.csv
│
├── src/
│   ├── loader.py
│   ├── embeddings.py
│   ├── vector_store.py
│   ├── rag_chain.py
│   └── config.py
│
└── faiss_index/
```

---

## ⚙️ Installation Steps

### 1️⃣ Clone Repository

```
git clone https://github.com/yourusername/rag-ticket-bot.git
cd rag-ticket-bot
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Requirements

```
pip install -r requirements.txt
```

---

## 🔑 Setup Groq Free API Key

Get Free API Key from:

👉 https://console.groq.com/

Then create `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run Application

```
streamlit run app.py
```

Click **Create Vector DB** button first → Then Ask Ticket Query

---

## 💡 Example Query

```
My payment got deducted but order is not confirmed. What should I do?
```

---

## 🧰 Tech Stack

* LangChain
* FAISS
* Groq LLM (Llama3)
* HuggingFace Embeddings
* Streamlit
* Python

---

## 🎯 Use Case

* IT Support Automation
* Helpdesk AI Assistant
* Customer Support Bot
* Enterprise Knowledge Retrieval

---

## 📈 Future Improvements

⭐ Add PDF / CSV Knowledge Base Upload

⭐ Add Chat History Memory

⭐ Deploy on AWS / Render

⭐ Add Authentication

⭐ Improve Prompt Engineering

⭐ Add Hybrid Search (BM25 + Vector)

---

## 👨‍💻 Author

**Shubham Raut**
 GenAI Developer | RAG System Builder

---

## ⭐ If You Like This Project

Give ⭐ Star on GitHub and Share 🚀

---
