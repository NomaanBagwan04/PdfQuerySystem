📄 PdfQuerySystem

A lightweight, FastAPI-powered AI system that lets users ask questions about PDFs and receive accurate, context-aware answers. <br>
Powered by OpenAI embeddings, ChromaDB for vector search, and LangChain for Retrieval-Augmented Generation (RAG).<br>

🚀 Features

✅ Upload PDF and extract content

🤖 Ask natural language questions based on PDF content

🧠 Uses vector search (ChromaDB) + OpenAI for accurate, grounded answers

⚡ Built with FastAPI for speed and simplicity

🔌 Modular RAG pipeline using LangChain

💠 Tech Stack

Python 3.10+
FastAPI – API framework
LangChain – RAG orchestration
OpenAI API – Embeddings + Answer generation
ChromaDB – In-memory vector store
PyMuPDF / pdfplumber – PDF parsing

📦 Installation

- Clone the repository:

git clone https://github.com/NomaanBagwan04/PdfQuerySystem.git
cd PdfQuerySystem

- Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

- Set your OpenAI API key in a .env file:
OPENAI_API_KEY=your_openai_key_here

▶️ Usage

Run the FastAPI server:
uvicorn main:app --reload
Visit http://localhost:8000/docs for the Swagger UI to test the API.

📁 Project Structure

.<br>
├── main.py              # FastAPI entry point <br>
├── rag_pipeline.py      # PDF processing, embeddings, and QA logic <br>
├── utils.py             # Utility functions for text chunking, etc. <br>
├── requirements.txt <br>
└── README.md <br>

<br>
🧪 Sample Workflow
+ Upload a PDF
+ Automatically extract and embed content
+ Ask questions like:
 + "What is the summary of the document?"
 + "Who is the author?"
 + "What are the key findings?"

🙌 Acknowledgements

LangChain
ChromaDB
OpenAI

---

