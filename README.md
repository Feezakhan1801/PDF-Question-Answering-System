# 📄 PDF Question Answering System (RAG)

A Generative AI-powered PDF Question Answering system that allows users to upload PDF documents and ask natural language questions. The system uses Retrieval-Augmented Generation (RAG) to extract relevant context from PDFs and generate accurate answers using an LLM.

🚀 Features
📂 Upload PDF documents
🤖 Ask questions in natural language
🔎 Context-based retrieval from PDF content
🧠 AI-powered answer generation (RAG pipeline)
⚡ Fast and interactive UI (Streamlit)
📄 Supports multiple PDF documents

🏗️ Tech Stack
Python 🐍
Streamlit (Frontend UI)
FastAPI (Backend API)
LangChain / RAG Pipeline
Vector Database (FAISS / Chroma)
OpenAI / LLM API
PyPDF / PDF processing libraries

📌 How It Works
User uploads a PDF file 📂
Text is extracted from the PDF 📄
Text is split into chunks ✂️
Embeddings are created and stored in vector DB 🧠
User asks a question ❓
Relevant chunks are retrieved 🔍
LLM generates final answer 🤖

🖥️ Project Structure
pdf_qa_app/
│
├── app.py
├── requirements.txt
├── data/
│   └── temp.pdf
├── myvenv/
└── README.md
⚙️ Installation & Setup
# Clone repository
git clone https://github.com/your-username/pdf-qa-system.git

# Go to project folder
cd pdf_qa_app

# Create virtual environment
python -m venv venv

# Activate environment
venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Run app
streamlit run app.py


💡 Future Improvements
Multi-PDF chat history
Chat memory (conversational RAG)
Better UI with authentication
Support for images inside PDFs
Faster vector search optimization

👨‍💻 Author

Feeza Khan

GitHub: @Feezakhan1801
LinkedIn: linkedin.com/in/feeza-pathan-35802826a
⭐ Show Some Support

If you like this project, please ⭐ the repository and share it!

