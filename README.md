RAG AI Agent for Policy-Based Customer Queries
n8n | OpenAI | Supabase Vector DB | Retrieval-Augmented Generation

This project implements a Retrieval-Augmented Generation (RAG) AI Agent that answers customer queries based strictly on verified business policies stored in a vector database — ensuring accurate, compliant, and hallucination-free responses.

The solution uses n8n to automate policy ingestion, embedding generation, vector storage, and real-time retrieval during chat interactions.

Key Capabilities

Automated Knowledge Updates
Upload a document → embeddings are generated & stored automatically

Context-Aware Response Generation
Chat memory improves relevance and user experience

Zero Hallucination Policy
Answers only from real documents retrieved via vector similarity

No-Code/Low-Code Implementation
Built entirely in n8n without LangChain requirement

System Architecture
Component	Purpose
Google Drive Trigger	Detects new policy docs
OpenAI Embeddings	Converts text → semantic vectors
Supabase Vector Store	Stores embeddings and metadata
AI Agent Node	Executes retrieval + response logic
Memory Node	Maintains conversation context
 
 Business Value

Accurate policy communication
Eliminates manual support lookups
Faster user response & better CX
Adaptable to manuals / SOPs / fraud rules / HR policies, etc.
Scales without additional staff

 Skills Demonstrated

RAG automation using vector DB retrieval

Endpoint-driven workflow automation with n8n

Prompt engineering + context memory handling

Knowledge ingestion orchestration

Supabase + OpenAI integration
