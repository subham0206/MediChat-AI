# MediChat AI

## 📌 Project Overview
MediChat AI is an advanced **AI-powered medical chatbot** that assists healthcare professionals in retrieving and summarizing **patient medical history** based on user queries. It leverages **ChromaDB** for vector storage and **GPT-based AI** for intelligent response generation. 

**Running on public URL:** https://9e9d329bdf7b911ef8.gradio.live

## 🎯 Objectives
- **Efficient Patient Data Retrieval**: Store and retrieve structured patient medical records.
- **AI-Powered Chatbot**: Enable conversational interactions to assist in case search.
- **Moderation & Compliance**: Ensure user queries are ethical and safe using OpenAI's moderation API.
- **Scalable & Production-Ready**: Deploy a system that is **fast, secure, and user-friendly**.

## 🚀 Features
- **🔍 Semantic Search**: Retrieve patient records using **ChromaDB embeddings**.
- **💬 Conversational AI**: Chat with an AI that understands **medical history queries**.
- **🛡️ Query Moderation**: Uses OpenAI's moderation API for **safe and ethical conversations**.
- **📄 JSON-based Storage**: Stores structured patient data for efficient retrieval.
- **🌐 Gradio UI Integration**: User-friendly interface for easy interaction.

## 🏗️ Tech Stack
- **Backend**: Python, OpenAI API, ChromaDB
- **Vector Database**: ChromaDB (Persistent Storage)
- **AI Model**: OpenAI GPT-3.5 Turbo (Chat & Summarization)
- **Frontend**: Gradio (for chatbot UI)

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/subham0206/MediChat-AI.git
cd MediChat-AI
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Set OpenAI API Key
```bash
export OPENAI_API_KEY='your-api-key-here'
```
### 4️⃣ Run the Chatbot
```bash
python app.py
```

## 📦 Project Structure
```
MediChat-AI/
│── data/                     # Sample patient records (JSON format)
│── models/                   # AI embedding and chat models
│── app.py                    # Main application logic
│── requirements.txt           # Python dependencies
│── README.md                  # Project documentation
```

## 💡 Future Enhancements
- **🔄 Multi-turn conversations** for better interactions.
- **📊 Dashboard for Insights** (patient trends, common queries).
- **🛠️ API Endpoints** for external integrations.
- **⚡ Fine-tuning AI models** for improved medical relevance.

## 🤝 Contributing
Contributions are welcome! Feel free to **fork the repo**, create a branch, and submit a PR.

## 📜 License
This project is licensed.

---
🌟 **MediChat AI - Empowering Healthcare with AI-driven Insights** 🌟
