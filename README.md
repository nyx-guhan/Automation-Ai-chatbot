# AI Chatbot with RAG using n8n

## Overview
An AI-powered FAQ chatbot built with n8n that automatically ingests documents from Google Drive, generates embeddings, stores them in Pinecone Vector Database, and answers user queries using Retrieval-Augmented Generation (RAG).

## Features
- Automatic document ingestion from Google Drive
- Document chunking and embedding generation
- Semantic search using Pinecone Vector Database
- Conversational AI responses using Google Gemini
- Real-time chat interface
- Knowledge base updates whenever new files are added

## Workflow Architecture
Google Drive → Document Loader → Text Splitter → OpenAI Embeddings → Pinecone Vector Store → AI Agent → User Response

## Technologies Used
- n8n
- Google Drive API
- OpenAI Embeddings
- Pinecone Vector Database
- Google Gemini
- Retrieval-Augmented Generation (RAG)

## Use Cases
- Company FAQs
- Internal Knowledge Base
- Documentation Assistant
- Customer Support Chatbot
- Product Information Assistant

## Setup
1. Import the workflow JSON into n8n.
2. Configure Google Drive credentials.
3. Configure OpenAI API credentials.
4. Configure Pinecone credentials.
5. Configure Google Gemini credentials.
6. Add documents to the Google Drive folder.
7. Start chatting with the AI assistant.

## Future Improvements
- Multi-document support
- Source citations in responses
- User authentication
- Conversation history storage

## Author
Guhan B
B.Tech CSBS
