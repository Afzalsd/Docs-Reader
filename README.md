# Docs-Reader

Docs-Reader lets you **chat with your documents**! Search, understand, and extract answers from your files using smart semantic search and AI, with grounded citations from your own knowledge base.

---

## 📖 What is Docs-Reader?

Docs-Reader processes your documents by splitting them into meaningful chunks, generating vector embeddings, and storing these in a ChromaDB vector database. When you ask a question, the system finds the most relevant sections, then generates a trustworthy answer using AI, citing sources within your files.

---

## 🚀 Quick Start

1. **Clone the repository**  
   ```
   git clone https://github.com/Afzalsd/Docs-Reader.git
   cd Docs-Reader
   ```

2. **Install dependencies**  
   ```
   pip install -r requirements.txt
   ```

3. **Set up environment variables**  
   ```
   cp .env.example .env
   # Edit .env and add your OpenAI API key and any other required settings
   ```

4. **Add your documents**  
   Place your files in the `data/` directory (ex: `data/books/`).

5. **Create your Chroma database**  
   ```
   python create_database.py
   ```

6. **Start querying your docs**  
   ```
   python query_data.py
   ```
   - Enter your questions and get answers with citations, all based on your documents.

---

## ✨ Features

- **Semantic Search:** Finds info by meaning, not just keywords.
- **Retrieval-Augmented Generation (RAG):** Combines semantic search and AI for accurate, grounded answers.
- **Answers with Citations:** Every answer is referenced with source links from your own files.
- **Automated Pipeline:** Effortlessly process, index, and query your documents.
- **Bring Your Own Knowledge:** Query anything you upload for a personalized experience.

---

## ⚡ Requirements

- Python 3.8+
- OpenAI API Key
- ChromaDB
- Libraries listed in `requirements.txt`

---

## 📁 Project Structure

```
Docs-Reader/
├── chroma/                   # ChromaDB config and modules
├── chroma.sqlite3            # ChromaDB database file
├── data/                     # Add your documents here
├── compare_embeddings.py     # Embedding comparison script
├── create_database.py        # Document processing and DB creation
├── query_data.py             # CLI for querying your docs
├── .env.example              # Example environment file
├── requirements.txt          # Python dependencies
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

---

## 🪪 License

MIT License

---

## 📚 Documentation

For detailed understanding, visit:  
👉 [Docs-Reader Documentation](https://searchprojecthere.notion.site/docs-reader?source=copy_link)

---

**Happy Document Chatting!**
```
