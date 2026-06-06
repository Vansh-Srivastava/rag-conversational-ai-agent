# 🤖 RAG-Powered Conversational AI Agent

An intelligent Retrieval-Augmented Generation (RAG) chatbot that combines semantic search, vector databases, and Large Language Models to deliver accurate, context-aware responses from custom knowledge sources.

---

## 📌 Project Overview

This project implements a Retrieval-Augmented Generation (RAG) architecture that enhances AI responses by retrieving relevant information from a knowledge base before generating answers.

The system leverages Pinecone for vector storage, Google Gemini for response generation, and LangChain for orchestration. Buffer Window Memory is incorporated to maintain conversational context and improve multi-turn interactions.

---

## 🚀 Features

- 🔍 Semantic Search using Vector Embeddings
- 📚 Retrieval-Augmented Generation (RAG)
- 🧠 Context Preservation with Buffer Window Memory
- 💬 Multi-turn Conversation Support
- 📄 Document-Grounded Responses
- ⚡ Fast Retrieval using Pinecone Vector Database
- 🔗 LangChain-Based Workflow Orchestration
- 🤖 Google Gemini Integration

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Backend Development |
| LangChain | LLM Orchestration |
| Pinecone | Vector Database |
| Google Gemini | Response Generation |
| Vector Search | Semantic Retrieval |
| n8n | Workflow Automation |

---

## 🏗 Architecture

```text
User Query
    │
    ▼
Embedding Model
    │
    ▼
Pinecone Vector Database
    │
    ▼
Relevant Context Retrieval
    │
    ▼
Google Gemini + LangChain
    │
    ▼
Generated Response
```

---

## 📂 Project Structure

```text
rag-conversational-ai-agent/
│
├── app.py
├── requirements.txt
├── config.py
├── vector_store/
├── data/
├── assets/
│   ├── screenshots/
│   └── diagrams/
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/rag-conversational-ai-agent.git
```

### Navigate to Project

```bash
cd rag-conversational-ai-agent
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key
PINECONE_API_KEY=your_api_key
```

### Run Application

```bash
python app.py
```

---

## 📷 Screenshots

<img width="1003" height="563" alt="image" src="https://github.com/user-attachments/assets/55386fca-e6bd-4d71-b788-6c1d8757676a" />

<img width="778" height="492" alt="image" src="https://github.com/user-attachments/assets/12a9faf9-229e-4dfa-a709-ed9cd27023d9" />


---

## 👨‍💻 Author

**Vansh Srivastava**

B.Tech CSE (Data Science)  
Raj Kumar Goel Institute of Technology, Ghaziabad

---

## 📜 License

This project is licensed under the MIT License.
