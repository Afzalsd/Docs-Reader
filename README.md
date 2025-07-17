# Docs-Reader

<<<<<<< HEAD
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
=======
## Description

This project helps you chat with your documents! It works by first processing your documents, breaking them into smaller pieces (chunks), and converting them into special numbers called embeddings. These embeddings and chunks are stored in a vector database. When you ask a question, the system finds the most relevant chunks in the database based on your question's embedding and then uses an AI model to generate an answer based only on those relevant chunks.

The project utilizes [list key technologies or frameworks used, e.g., OpenAI, Python, etc.].

## Table of Contents

* [Getting Started](#getting-started)
* [Project Structure](#project-structure)
* [Features](#features)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Documentation](#documentation)
* [Contributing](#contributing)
* [License](#license)

## Getting Started

To get started with the project, please follow these steps:

1. Clone the repository: git clone https://github.com/Afzalsd/Docs-Reader.git
2. Install dependencies: pip install -r requirements.txt
3. Set up environment variables: cp .env.example .env and modify as needed

## Project Structure

Project Structure
-----------------

project-root/
├── chroma/                      # Directory for Chroma-related modules or configuration
├── chroma.sqlite3               # ChromaDB local database file
├── data/                        # Folder for storing input documents
│   └── books/                   # Subfolder for books or markdown files
│       └── alice_in_wonderland.md  # Sample document
├── .gitignore                   # Git ignore rules
├── README.md                    # Project documentation
├── compare_embeddings.py        # Script to compare different embedding strategies
├── create_database.py           # Script to create and populate the ChromaDB
├── query_data.py                # Script to query the Chroma database using embeddings


## Features

- Semantic Search: Searches by meaning, not keywords.

- RAG Architecture: Retrieves then generates answers.

- Grounded Answers: Provides factual answers based only on your documents.

- Source Citations: Shows where the answers came from.

- Automated Pipeline: Automatically processes and indexes documents.

- Custom Knowledge: Lets you chat with your own files.
  
## Requirements

* Python 3.8+
* OpenAI API key
* Other dependencies listed in requirements.txt

## Installation

To install the project, follow these steps:

1. Install dependencies: pip install -r requirements.txt
2. Set up environment variables: cp .env.example .env and modify as needed

## Usage

To use the project, follow these steps:

1. Run the script: python script_name.py
2. Follow the prompts and instructions

## Documentation

For detailed documentation, please visit: https://searchprojecthere.notion.site/docs-reader

## Contributing

Contributions are welcome! Please submit a pull request with your changes.
>>>>>>> c11f4b082d2e0e8150c4dc99baae1bbd682b33f9
