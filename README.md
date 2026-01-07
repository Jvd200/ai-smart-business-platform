# AI-Powered Smart Business Management Platform

A full-stack web application with AI-powered automation, intelligent insights,
and document-based question answering to help businesses manage operations efficiently.

## Key Features
- Role-based authentication (Admin, Manager, User)
- Business task and data management
- Interactive dashboards
- AI-powered assistant for smart insights
- Document intelligence using RAG and vector embeddings

## Tech Stack
- Frontend: React, Tailwind CSS
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT
- AI: LLM APIs, RAG, Vector Search

## System Architecture
 # High-Level Architecture
[ React Frontend ]
        |
        |  REST APIs (JWT)
        v
[ Node.js + Express Backend ]
        |
        |  Mongoose
        v
[ MongoDB Database ]

        |
        |  AI Requests
        v
[ LLM API + Vector Store ]

## API Design
-- Auth APIs
   -POST /api/auth/register
   -POST /api/auth/login
--Business APIs
  -GET    /api/items
  -POST   /api/items
  -PUT    /api/items/:id
  -DELETE /api/items/:id
--AI APIs
  -POST /api/ai/chat
  -POST /api/ai/document

## Database Schema
   # Core Collections
   --User Collection
     User {
  name,
  email,
  password,
  role
}

--BusinessItem Collection
BusinessItem {
  title,
  description,
  status,
  assignedTo,
  createdBy
}
--Document Collection
Document {
  fileName,
  extractedText,
  embeddings,
  uploadedBy
}


## UI & UX Design
--Core Screens
    -Login
    -Register
    -Dashboard
    -Business Items (Tasks / Records)
    -AI Assistant
    -Document Upload & Q&A

- Wireframes for core screens



