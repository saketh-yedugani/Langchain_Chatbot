# 🤖 Chatbot Projects Repository

[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-red?logo=openai&logoColor=white)](https://platform.openai.com/)
[![Groq](https://img.shields.io/badge/Groq-API-purple?logo=groq&logoColor=white)](https://www.groq.com/)


A collection of chatbot projects demonstrating conversational AI, vector databases, and retrieval-augmented generation (RAG).

---

## 📓 Notebooks Overview

### 1️⃣ Chatbot_with_conversation_history.ipynb
- **Description:** Chatbot with memory of the conversation. It remembers previous interactions and responds contextually.
- **Tools & Models:**
  - **API:** Groq
  - **Model:** LLaMA-3.3-70B Versatile
- **Features:**
  - Maintains conversation history.
  - Context-aware responses.

---

### 2️⃣ Initial_openai.ipynb
- **Description:** A simple chatbot using OpenAI API.
- **Tools & Models:**
  - **API:** OpenAI
  - **Model:** GPT-4o
- **Features:**
  - Single-turn chatbot functionality.
  - Quick and easy chatbot setup.

---

### 3️⃣ Simple_OpenAI.ipynb
- **Description:** Demonstrates **retrieval-augmented generation (RAG)** using vector embeddings.
- **Workflow:**
  1. Load online data.
  2. Convert data into Documents.
  3. Divide documents into chunks.
  4. Convert text chunks into vector embeddings.
  5. Store embeddings in a Vector Database.
  6. Retrieve relevant chunks from the Vector DB.
  7. Prompt GPT-4o with retrieved data to answer queries.
- **Tools & Models:**
  - **API:** OpenAI
  - **Model:** GPT-4o
  - **Database:** Vector Store (FAISS, Pinecone, or Chroma)

---

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/saketh-yedugani/Langchain_Chatbot.git

# Navigate to the repo
cd yourrepo

# Install dependencies
pip install -r requirements.txt

# Open notebooks in Jupyter or VSCode
jupyter notebook
