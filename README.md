# Mr.HelpMate AI – Building Effective Search Systems

## Overview

Mr.HelpMate AI is a Generative AI-powered Question & Answer application built using Retrieval-Augmented Generation (RAG).
The project demonstrates how to build an intelligent conversational chatbot capable of retrieving contextual information from external sources and answering user queries effectively.

This project uses:

* LangChain
* ChromaDB
* HuggingFace Embeddings
* Groq LLM (Llama3)
* Retrieval-Augmented Generation (RAG)
* Conversational Memory
* Vector Search

The chatbot retrieves relevant information from indexed documents/web content and generates accurate contextual responses.

---

## Features

* Conversational Q&A chatbot
* Retrieval-Augmented Generation (RAG)
* Context-aware responses
* Vector database integration using ChromaDB
* HuggingFace embedding models
* LangChain chains and retrievers
* Groq Llama3 model integration
* Semantic search implementation

---

## Tech Stack

| Technology                     | Purpose              |
| ------------------------------ | -------------------- |
| Python                         | Programming Language |
| LangChain                      | LLM Framework        |
| ChromaDB                       | Vector Database      |
| HuggingFace Embeddings         | Text Embeddings      |
| Groq API                       | Large Language Model |
| BeautifulSoup (bs4)            | Web Content Parsing  |
| RecursiveCharacterTextSplitter | Text Chunking        |

---

## Project Structure

```bash
Mr.HelpMate_AI/
│
├── conversationqa.ipynb
├── README.md
├── requirements.txt
├── .env
└── chroma_db/
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Mr.HelpMate_AI.git
```

### 2. Navigate to Project Folder

```bash
cd Mr.HelpMate_AI
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the project root folder.

```env
GROQ_API_KEY=your_groq_api_key
HF_TOKEN=your_huggingface_token
```

---

## Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
conversationqa.ipynb
```

Run all notebook cells sequentially.

---

## How It Works

1. Load web/document data
2. Split text into chunks
3. Convert chunks into embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant chunks based on user query
6. Send retrieved context to LLM
7. Generate contextual answer

---

## RAG Workflow

```text
User Query
     ↓
Retriever
     ↓
Vector Database (ChromaDB)
     ↓
Relevant Context
     ↓
LLM (Llama3 via Groq)
     ↓
Final Answer
```

---

## Learning Concepts Covered

* Retrieval-Augmented Generation (RAG)
* Vector Databases
* Semantic Search
* Conversational AI
* LangChain Chains
* Embedding Models
* Prompt Engineering
* Context Retrieval
* AI Search Systems

---

## Future Enhancements

* Streamlit UI integration
* PDF document upload support
* Multi-document retrieval
* Chat history memory
* Agentic AI workflow
* Production deployment
* API integration

---

## Author

Reshma Manu

QA Automation Engineer | Generative AI Learner

---

## License

This project is created for educational and learning purposes.
