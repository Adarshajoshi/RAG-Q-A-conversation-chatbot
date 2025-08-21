Conversational RAG with PDF & Chat History

A Streamlit app that lets you upload PDFs and chat with their content using Retrieval-Augmented Generation (RAG). The app uses Groq LLMs, HuggingFace embeddings, and ChromaDB to deliver concise, context-aware answers, while keeping session-based conversational history.

🚀 Features

📂 Upload one or multiple PDFs

💬 Ask natural language questions about their content

🔄 History-aware retrieval for follow-up questions

🧠 Session-specific conversational memory

⚡ Powered by Groq (Gemma2-9b-It) + HuggingFace (all-MiniLM-L6-v2)

⚙️ Setup

Clone the repo

git clone https://github.com/Adarshajoshi/RAG-Q_A_conversation-chatbot.git
cd RAG-Q_A_conversation-chatbot


Install dependencies

pip install -r requirements.txt


Set up environment variables
Create a .env file in the project root and add:

HF_TOKEN=your_huggingface_token


Run the app

streamlit run app.py


Enter your Groq API key in the Streamlit UI and start chatting 🚀
