<div align="center">

# 🚀 NVIDIA NIM RAG Chatbot

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&pause=1000&color=76B900&center=true&vCenter=true&width=900&lines=Retrieval-Augmented+Generation+(RAG);Powered+by+NVIDIA+NIM;LangChain+%2B+FAISS+%2B+Streamlit;Chat+with+your+Documents+in+Seconds" />

<br>

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-NIM-76B900?style=for-the-badge&logo=nvidia)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-VectorDB-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

---

# 📖 Overview

This project demonstrates a complete **Retrieval-Augmented Generation (RAG)** pipeline using:

- 🟢 NVIDIA NIM LLMs
- 🟢 NVIDIA Embeddings
- 🟢 LangChain
- 🟢 FAISS Vector Database
- 🟢 Streamlit UI

Upload your documents, generate embeddings, and ask questions directly from the document context.

---



---

# 🎥 Demo

<p align="center">

<img src="assets/demo.gif" width="900">

</p>

> Replace `assets/demo.gif` with your project demo GIF.

---

# ✨ Features

### 📄 PDF Document Processing

- Load PDFs dynamically
- Extract text efficiently
- Split large documents into chunks

### 🧠 NVIDIA Embeddings

Generate semantic embeddings using:

```python
NVIDIAEmbeddings()
```

### ⚡ FAISS Vector Store

Fast similarity search using:

```python
FAISS.from_documents(...)
```

### 🤖 NVIDIA NIM LLM

Powered by:

```python
meta/llama-3.1-70b-instruct
```

### 🔍 Context-Aware Retrieval

- Relevant chunk retrieval
- Reduced hallucinations
- Accurate responses

### 🎨 Interactive Streamlit UI

- Question Input
- Embedding Creation
- Similarity Search Viewer

---

# 🏗️ Architecture

```mermaid
flowchart LR

A[PDF Documents]
--> B[PyPDF Loader]

B --> C[Text Splitter]

C --> D[NVIDIA Embeddings]

D --> E[FAISS Vector Store]

F[User Question]
--> G[Retriever]

E --> G

G --> H[Relevant Context]

H --> I[NVIDIA Llama 3.1]

I --> J[Final Answer]
```

---

# 📂 Project Structure

```bash
.
├── app.py
├── requirements.txt
├── .env
├── .gitignore
├── us_census/
│   └── documents.pdf
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/nvidia-rag-chatbot.git

cd nvidia-rag-chatbot
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file:

```env
NVIDIA_API_KEY=YOUR_API_KEY
```

Get your API Key from:

https://build.nvidia.com

---

# ▶️ Run Application

```bash
streamlit run app.py
```

---

# 🧠 Example Questions

```text
What information does the document contain?

Summarize the population trends.

What are the key findings?

Explain the statistics in simple terms.
```

---

# 📊 Tech Stack

| Technology | Purpose |
|------------|----------|
| Streamlit | Frontend UI |
| LangChain | RAG Framework |
| NVIDIA NIM | LLM Inference |
| NVIDIA Embeddings | Vector Embeddings |
| FAISS | Vector Database |
| PyPDFLoader | PDF Parsing |

---

# 🌟 Future Improvements

- [ ] Multi-PDF Upload
- [ ] Chat History
- [ ] Memory Support
- [ ] Source Citations
- [ ] Hybrid Search
- [ ] Docker Deployment
- [ ] Authentication

---

# 🤝 Contributing

Contributions are welcome!

```bash
fork ➜ create branch ➜ commit ➜ push ➜ pull request
```

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the project

📢 Share it with others

---

<div align="center">



<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=76B900&center=true&vCenter=true&width=600&lines=Happy+Coding!;Powered+by+NVIDIA+AI;Retrieval-Augmented+Generation" />

</div>