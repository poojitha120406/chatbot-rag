# AI PDF Chatbot (RAG)

A command-line PDF question-answering project using Sentence Transformers,
ChromaDB, and OpenRouter.

## Setup

1. Create and activate a Python virtual environment.
2. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

3. Copy `.env.example` to `.env` and set your OpenRouter API key.
4. Put the PDF you want to query at `data/sample.pdf`.
5. Run the chatbot:

   ```sh
   python app.py
   ```

The PDF, `.env`, virtual environments, and generated ChromaDB data are excluded
from Git.