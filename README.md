

#  ML-Book-QA-RAG

A Retrieval-Augmented Generation (RAG) project built to answer questions from the book  
**"Machine Learning for Absolute Beginners"** using embeddings and a language model.

---

##  Project Overview
This project demonstrates how to:
- Split a PDF book into chunks.
- Generate vector embeddings for each chunk.
- Store vectors for efficient retrieval.
- Use a **Retrieval-Augmented Generation (RAG)** pipeline to answer questions from the book content.

---

##  Tech Stack
- **Python**
- **LangChain** (for document loading, text splitting, and RAG pipeline)
- **FAISS / NumPy** (for vector storage & similarity search)
- **OpenAI API** (for generating responses)
- **Jupyter Notebook** (for experimentation)
- **dotenv** (to manage API keys securely)

---

##  Project Structure
```bash
ml-rag/
│
├── data/
│   └── Machine Learning for Absolute Beginners.pdf   # Source book
│
├── store/
│   ├── chunks.json        # Pre-processed text chunks
│   └── vectors.npy        # Stored embeddings
│
├── coding.ipynb           # Notebook for experimentation
├── main.py                # Script to run the RAG pipeline
├── requirements.txt       # Project dependencies
└── .env                   # Store your API keys here (not pushed to GitHub)
