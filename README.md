<div align="center">

# ✦ SYNORA

### AI-Powered Document Intelligence & RAG Assistant

**Understand documents. Extract knowledge. Ask anything.**

<br>

<a href="https://synora-qqtugyc2cut5bi7vmeqnap.streamlit.app/">
<img src="https://img.shields.io/badge/🚀_LIVE_DEMO-Try_Synora-6C63FF?style=for-the-badge">
</a>

<br><br>

<img src="assets/screenshots/Synora.png" width="90%" alt="Synora">

<br><br>

<img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white">
<img src="https://img.shields.io/badge/RAG-7C3AED?style=flat-square">
<img src="https://img.shields.io/badge/FAISS-Vector_Search-00A67E?style=flat-square">
<img src="https://img.shields.io/badge/Groq-LLM-F55036?style=flat-square">

<br><br>

> **Transform PDFs and scanned documents into searchable, summarized and grounded knowledge.**

</div>

---

## 🌌 What is Synora?

**Synora** is an AI-powered document understanding assistant that transforms
long PDFs, scanned documents, and images into concise, structured and
searchable knowledge.

Upload a document and Synora can:

- 📄 Extract text from PDFs and images
- 🔎 Perform OCR on scanned documents
- 🌐 Support multilingual OCR
- 📝 Generate intelligent summaries
- 🔑 Extract key points
- 🎯 Identify main ideas
- 💡 Suggest improvements
- 💬 Answer document-based questions
- 📌 Provide page-level sources

At its core, Synora uses a **Retrieval-Augmented Generation (RAG)** pipeline
to keep answers grounded in the uploaded document.

---

## 🚀 Try Synora

<div align="center">

### [✨ OPEN THE LIVE APPLICATION →](https://synora-qqtugyc2cut5bi7vmeqnap.streamlit.app/)

<br>

`📤 Upload` → `🌐 Select Language` → `🔍 Analyze`
→ `📝 Understand` → `💬 Ask`

</div>

---

## ✨ Core Features

<table>
<tr>

<td width="50%">

### 📄 Document Processing

- PDF, PNG, JPG & JPEG
- PyMuPDF text extraction
- Tesseract OCR fallback
- Scanned document support
- Page-aware extraction
- Text cleaning & normalization

</td>

<td width="50%">

### 🧠 AI Understanding

- Short / Medium / Long summaries
- Key Points
- Main Ideas
- Improvement Suggestions
- Large-document map-reduce
- Downloadable summaries

</td>

</tr>

<tr>

<td width="50%">

### 💬 RAG Q&A

- Semantic document search
- FAISS vector retrieval
- Top-K relevant chunks
- Groq-powered generation
- Grounded responses
- Page-number sources

</td>

<td width="50%">

### 🌐 Multilingual OCR

- 🇬🇧 English
- 🇮🇳 Hindi
- 🇮🇳 Telugu
- 🇮🇳 Tamil
- 🇮🇳 Bengali
- English + regional languages

</td>

</tr>
</table>

---

## 🔍 Why Synora?

<details>
<summary><b>Click to explore</b></summary>

<br>

| Traditional Document Reading | ✦ Synora |
|---|---|
| 📚 Read everything manually | ⚡ Content-proportional summaries |
| 🔎 Keyword search | 🧠 Semantic retrieval |
| 🧩 Separate OCR tools | 🔎 Built-in OCR |
| 🌍 Limited language support | 🌐 Multilingual OCR |
| 🤖 Generic chatbot answers | 🎯 Document-grounded answers |
| ❓ Difficult to verify answers | 📌 Page-level citations |
| 📖 Long documents are difficult | ✂️ Map-reduce processing |

</details>

---

## 🧩 How Synora Works

<details>
<summary><b>🔬 Explore the complete pipeline</b></summary>

<br>

```text
                 📄 PDF / IMAGE
                       │
                       ▼
              ┌─────────────────┐
              │  🔎 Extract/OCR │
              │                 │
              │ PyMuPDF /       │
              │ Tesseract       │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ 🧹 Clean &      │
              │    Chunk        │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ 🧠 Embeddings   │
              │ Sentence-       │
              │ Transformers    │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ ⚡ FAISS        │
              │ Vector Store    │
              └────────┬────────┘
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
       📝 AI ANALYSIS          💬 RAG Q&A
             │                   │
       ┌─────┼─────┐             ▼
       ▼     ▼     ▼        🔎 Retrieve
    Summary Points Ideas          │
       │     │     │              ▼
       └─────┴─────┘         🤖 Groq LLM
                                  │
                                  ▼
                         📌 Grounded Answer
                             + Sources
