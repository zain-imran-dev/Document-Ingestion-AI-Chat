This project consists of two interconnected n8n workflows that create a complete RAG (Retrieval-Augmented Generation) pipeline for document analysis and intelligent querying:

Document Ingestion Pipeline - Automated document processing and vector storage
AI Chat Interface - Interactive conversational AI with document retrieval capabilities

DOCUMENT PROCESSING WORKFLOW

<img width="1144" height="566" alt="Document Processing Workflow" src="https://github.com/user-attachments/assets/4eb908a3-2031-4505-b0a6-27b51b74d4dd" />

AI CHAT WORKFLOW 

<img width="1043" height="492" alt="AI Chat Workflow" src="https://github.com/user-attachments/assets/9df012d1-d633-4c96-bc11-46399edcecc6" />


 Features
Document Processing Workflow

Automated File Retrieval: Downloads documents from Microsoft OneDrive
Intelligent Text Processing: Splits documents using recursive character text splitting
Vector Embeddings: Generates OpenAI embeddings for semantic search
Vector Storage: Stores processed documents in Supabase vector database
Scalable Architecture: Handles various document formats efficiently

AI Chat Workflow

Conversational Interface: Public chat trigger for real-time interactions
Intelligent Agent: AI-powered agent with memory and tool capabilities
Document Retrieval: Semantic search through processed documents
Context Awareness: Maintains conversation history with buffer window memory
Specialized Knowledge: Configured for Sony stock data analysis

 Technology Stack

Automation Platform: n8n
AI/ML Services: OpenAI (GPT-4.1-mini, Embeddings API)
Cloud Storage: Microsoft OneDrive
Vector Database: Supabase
Memory Management: Buffer Window Memory (20 context length)

 Architecture
Document Flow:
OneDrive → Document Loader → Text Splitter → OpenAI Embeddings → Supabase Vector Store

Chat Flow:
User Query → AI Agent → Vector Retrieval → OpenAI LLM → Response
📊 Use Cases

Financial Analysis: Query and analyze Sony stock documentation
Document Q&A: Ask questions about uploaded documents
Research Automation: Extract insights from large document collections
Knowledge Management: Build searchable knowledge bases from unstructured data

 Setup Requirements

n8n instance (self-hosted or cloud)
OpenAI API key
Microsoft OneDrive account with API access
Supabase account with vector extension enabled

 Benefits

Automated Processing: Eliminates manual document handling
Semantic Search: Find relevant information using natural language
Conversational Interface: Intuitive chat-based interaction
Scalable Solution: Handles large document collections efficiently
Memory Retention: Maintains context across conversations

 Applications
Perfect for:

Financial research and analysis
Document management systems
Customer support automation
Knowledge base creation
Research and development workflows

 Workflow Status
Both workflows are configured and ready for deployment with proper credential setup completed.
