🚀 RAG PIPELINE AND CHATBOT

An AI-powered RAG (Retrieval-Augmented Generation) chatbot workflow built with n8n, Pinecone, Google Gemini Embeddings, and OpenRouter.

This workflow automatically ingests documents from Google Drive, converts them into embeddings, stores them in Pinecone, and enables intelligent conversational querying over uploaded documents.

✨ Features
Automated document ingestion
Google Drive monitoring
Pinecone vector database integration
Gemini embeddings generation
Conversational AI chatbot
Semantic document search
Retrieval-Augmented Generation (RAG)
AI Agent orchestration
Fully automated indexing pipeline


🧠 Workflow Flow
Google Drive Upload
        ↓
Download File
        ↓
Document Loader
        ↓
Gemini Embeddings
        ↓
Pinecone Vector Store
        ↓
--------------------------------
        ↓
User Chat Message
        ↓
AI Agent
        ↓
Pinecone Retrieval
        ↓
OpenRouter LLM
        ↓
AI Response


⚙️ Tech Stack
n8n
Google Drive
Pinecone
Google Gemini Embeddings
OpenRouter
LangChain Nodes


🔑 Required Credentials
Google Drive OAuth2
Pinecone API
Google Gemini API
OpenRouter API


🛠️ Setup Instructions
1. Import Workflow
Open n8n
Import the JSON workflow file


2. Configure Credentials

Reconnect:

Google Drive
Pinecone
Gemini
OpenRouter


3. Configure Pinecone

Create:

Index: demo
Namespace: data


4. Activate Workflow

Enable the workflow and start uploading files to Google Drive.

💡 Use Cases
AI Knowledge Base
Internal Company Assistant
AI PDF Chatbot
Document Search System
Research Assistant
AI Customer Support



🔒 Security Notes

This workflow does not export actual credentials or API keys.
Only credential references are included inside the JSON export.

Always review workflows before sharing publicly.

📄 License

Free to use and modify.