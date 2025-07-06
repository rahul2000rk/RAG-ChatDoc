# RAG-ChatDoc
An intelligent chatbot built using Retrieval-Augmented Generation (RAG) that allows users to upload documents (PDF, TXT, DOCX) and ask natural language questions to get contextual answers. It leverages Groq's blazing-fast LLM backend and ChromaDB for efficient vector storage.

## 🚀 Features

- 📤 Upload and process PDF, TXT, or DOCX files
- 🤖 Ask questions from the uploaded document
- ⚡ Fast responses using Groq-hosted LLaMA 3
- 🔎 Contextual retrieval using Chroma vector store
- 🧠 Embedding with SentenceTransformers (MiniLM)
- 🧱 Built with LangChain + Streamlit

---

## 🖼️ UI Preview
![image](https://github.com/user-attachments/assets/0c4b6e28-d6c8-44ad-8ff8-648a7a061aa8)


---

## 🛠️ Tech Stack

| Component           | Tech                     |
|---------------------|--------------------------|
| Frontend            | Streamlit                |
| LLM Backend         | Groq API (LLaMA3, Gemma) |
| RAG Framework       | LangChain                |
| Embeddings          | SentenceTransformers     |
| Vector Store        | ChromaDB                 |


Set your Groq API key

In groq_chain.py, replace:

groq_api_key="YOUR_GROQ_API_KEY"

pip install -r requirements.txt

streamlit run app.py
