# PDF Query Application Using Retrieval-Augmented Generation (RAG)

This project is a Streamlit-based application that lets users upload PDF files and ask questions about the content. It uses Retrieval-Augmented Generation (RAG) to fetch relevant information and answer user queries.

---

## Features

- 📄 **PDF Upload**: Upload any PDF file and process its content.
- 🧩 **Text Chunking**: Automatically splits the PDF content into manageable chunks for efficient processing.
- 🌐 **Embeddings**: Generates embeddings for the text using Google Generative AI.
- 🗂️ **Vector Store**: Stores embeddings in a Chroma vector database for retrieval.
- 🤖 **AI-Powered Answers**: Uses Google's Gemini language model to generate responses based on retrieved data.

---

## Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/) for the user interface.
- **Backend**: [LangChain](https://langchain.com/) for RAG pipeline.
- **Vector Store**: [Chroma](https://www.trychroma.com/).
- **Embeddings & LLM**: [Google Generative AI](https://ai.google/).

---

## Prerequisites

- Python 3.8 or higher
- Google API Key for Generative AI (set as `GOOGLE_API_KEY` in your environment)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt ```
3. Set up your Google API Key:

   ```bash
   export GOOGLE_API_KEY="your-google-api-key" ```
4.Run the application:

   ```bash
   streamlit run rag_app.py ```
