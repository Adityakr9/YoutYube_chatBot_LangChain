# 🎥 YouTube Chatbot using LangChain (GenAI Project)

## 📌 Overview
This project is an AI-powered chatbot that can answer questions from YouTube videos using **LangChain** and **LLMs**.  
It uses **Retrieval-Augmented Generation (RAG)** to provide accurate answers based on video transcripts.

---

## 🚀 Features
- 🔍 Extracts YouTube video transcripts  
- 🤖 Answers user queries using AI  
- 📚 Uses RAG (Retrieval-Augmented Generation)  
- ⚡ Fast and context-aware responses  
- 💬 Conversational chatbot interface  

---

## 🛠️ Tech Stack
- Python  
- LangChain  
- Hugging Face / OpenAI API  
- FAISS (Vector Database)  
- YouTube Transcript API  
- Streamlit (optional UI)  

---

## 📂 Project Structure

project/
-│── app.py
-│── requirements.txt
-│── .env
-│── utils/
-│── data/
-│── README.md
---

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows

pip install -r requirements.txt

OPENAI_API_KEY=your_api_key
HUGGINGFACEHUB_API_TOKEN=your_token

python app.py

