
# LangChain RAG – Extracting Information from a Text Collection

*(Metin Koleksiyonundan Bilgi Çıkarma Sistemi)*

This project demonstrates a **Retrieval-Augmented Generation (RAG) system built with LangChain**, designed to extract and answer questions from a **collection of text documents** using Large Language Models (LLMs).

---

## 📌 Project Overview

Large text collections (PDFs, documents, articles, reports) are difficult to search using traditional methods.

This project solves that problem using a **LangChain-based RAG pipeline**, enabling:

* Semantic understanding of user queries
* Retrieval of relevant document chunks
* Context-aware answer generation using LLMs
* Efficient information extraction from unstructured text

---

## 🧠 What is RAG?

Retrieval-Augmented Generation (RAG) combines:

1. **Retrieval**

   * Finds relevant parts of documents using vector similarity search

2. **Generation**

   * Uses an LLM to generate answers based on retrieved context

This ensures:

* More accurate answers
* Reduced hallucinations
* Better grounding in real data

---

## 🚀 Features

* 📄 Text collection-based question answering system
* 🔎 Semantic search over document chunks
* 🧠 LLM-powered response generation
* ⚡ LangChain-based modular RAG pipeline
* 📚 Document chunking and embedding workflow
* 💬 Natural language querying over large text sets

---

## 🏗️ System Architecture

The system follows a standard **LangChain RAG pipeline**:

### 1. Document Loading

A collection of text documents is loaded into the system.

### 2. Text Splitting (Chunking)

Large documents are split into smaller chunks for better retrieval.

### 3. Embedding Generation

Each text chunk is converted into vector embeddings.

### 4. Vector Store Creation

Embeddings are stored in a vector database for similarity search.

### 5. Query Embedding

User query is converted into vector form.

### 6. Retrieval Step

Most relevant chunks are retrieved from the database.

### 7. LLM Generation

Final answer is generated using retrieved context + LLM.

---

## 🛠️ Technologies Used

* Python 🐍
* LangChain 🦜
* OpenAI / LLM APIs 🤖
* FAISS / Chroma (Vector Database)
* Jupyter Notebook 📓
* NumPy / Pandas

---

## 📂 Project Structure

```bash id="l1k9rr"
LangChain-RAG-extracting-information-from-a-text-collection/
│
├── langchain-rag-metin-koleksiyonundan-bilgi-ekme.ipynb
├── data/
├── embeddings/
├── vectorstore/
├── utils/
└── README.md
```

---

## ▶️ Getting Started

### 1. Clone Repository

```bash id="q2v8aa"
git clone https://github.com/sumeyrakarsavran/LangChain-RAG-extracting-information-from-a-text-collection.git
cd LangChain-RAG-extracting-information-from-a-text-collection
```

---

### 2. Install Dependencies

```bash id="t7x1zz"
pip install -r requirements.txt
```

---

### 3. Run Notebook

```bash id="c9p3kk"
jupyter notebook
```

Open:

```id="n8d2mm"
langchain-rag-metin-koleksiyonundan-bilgi-ekme.ipynb
```

---

## 🔑 API Configuration

If using OpenAI or similar LLM APIs:

```python id="a1x9pp"
import os
os.environ["OPENAI_API_KEY"] = "your_api_key"
```

---

## 💡 Use Cases

* 📚 Document search systems
* 🏢 Enterprise knowledge base assistants
* 📄 Legal / policy document analysis
* 🔎 Research paper exploration
* 💬 Internal company Q&A systems

---

## 📈 Why LangChain + RAG?

This architecture allows:

* Easy integration of document pipelines
* Modular and scalable retrieval systems
* Better accuracy than keyword search
* Context-aware LLM responses

---

## ⚠️ Limitations

* Depends on quality of embeddings and chunking
* Retrieval quality affects final answer
* Requires tuning for domain-specific documents
* Can be slower with large document sets



