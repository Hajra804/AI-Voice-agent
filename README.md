# AI-Voice-agent
n8n, Orchestrator

An intelligent AI-powered Dental Voice Assistant designed to automate patient interactions, answer dental-related questions, provide treatment information, assist with appointment scheduling, and retrieve accurate clinic information using Retrieval-Augmented Generation (RAG).
🚀 Features
🎤 AI Voice Assistant
💬 Natural Language Conversations
🧠 Retrieval-Augmented Generation (RAG)
🔎 Semantic Search using Pinecone
🌐 Website Knowledge Crawling
📄 Automatic Knowledge Base Creation
📅 Appointment Assistance
💲 Pricing Information
🏥 Treatment Information
🦷 Dental FAQs
💾 Conversation Memory
⚡ Real-Time AI Responses
                 User (Voice / Chat)
                         │
                         ▼
                  Speech-to-Text
                         │
                         ▼
                 n8n Orchestrator
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
   Intent Detection   Conversation   RAG Search
                         Memory
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                  AI Response Generator
                         │
                  Text-to-Speech
                         │
                         ▼
                      Patient


**Tech Stack
Artificial Intelligence
Google Gemini
Groq LLM
Retrieval-Augmented Generation (RAG)
Workflow Automation
n8n
Vector Database
Pinecone
Frontend
HTML
CSS
JavaScript
APIs
Google Gemini API
Pinecone API


**RAG Pipeline
User Question
      │
      ▼
Embedding
      │
      ▼
Pinecone Search
      │
      ▼
Relevant Chunks
      │
      ▼
Gemini LLM
      │
      ▼
Grounded Response


Author
Hajra Haseeb
