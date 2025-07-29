# 🤖 QA-BOT

Welcome to the **QA-BOT** repository! This document serves as the comprehensive guide for understanding, using, and contributing to this project. It covers all important aspects including project explanation, setup instructions, cloning the repository, usage guidelines, contribution instructions, and licensing details.

---

## 📚 Table of Contents

- [Introduction](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-introduction)
- [Features](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-features)
- [Installation](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-installation)
- [Cloning the Repository](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-cloning-the-repository)
- [Usage](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-usage)
- [Configuration](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-configuration)
- [Contributing](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-contributing)
- [Testing](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-testing)
- [License](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-license)
- [Support & Contact](https://github.com/dhruv-2615p/QA-BOT?tab=readme-ov-file#-support--contact)

---

## 📌 Introduction

This repository contains the source code and logic for **QA-BOT**, a Retrieval-Augmented Generation (RAG) based Question Answering chatbot. The goal of this project is to enable context-aware answering by combining information retrieval from your documents with generative AI models. This approach is perfect for answering questions based on custom knowledge, such as PDFs, TXT files, and other unstructured documents.

---

## 🚀 Features

- **LangChain Integration**: Uses LangChain for chaining retriever and LLM.
- **Embeddings**: Google Generative AI embeddings used for high-quality semantic understanding.
- **Vector Store**: ChromaDB for fast and efficient similarity search.
- **PDF Support**: Easily load and parse PDFs using `pypdf` and `unstructured`.
- **Gradio Interface**: Clean and simple UI to interact with the bot.
- **Environment Configuration**: `.env` file support for API keys and secrets.

---

## 🛠️ Installation

To install and set up the project locally, follow these steps:

1. **Prerequisites**: Ensure you have the following tools installed:
   - [Python 3.9+](https://www.python.org/)
   - [Git](https://git-scm.com/)
   - Your favorite Python environment (e.g., venv, conda)

2. **Install Dependencies**:
   - Use the included requirements.txt file:
     ```bash
     pip install -r requirements.txt
     ```

3. **Setup Environment Variables**:
   - Create a .env file in the root directory and add your Google GenAI API key:
     ```bash
     GOOGLE_API_KEY=your_google_genai_api_key_here
     ```
---

## 🔄 Cloning the Repository

To clone the repository to your local machine, use the following command in your terminal:

   ```bash
   git clone https://github.com/dhruv-2615p/QA-BOT.git
   cd QA-BOT
   ```
---

## ⚙️ Usage

After installing and cloning the repository, you can start using the project:

- **Run the Application**: 
  ```bash
  python RAG_QA.ipynb
  ```
---

## ⚙️ Configuration

Modify your settings using the following:

- .env: For API keys (e.g., GOOGLE_API_KEY)
- **Retrieval settings**: Change k in retriever.get_relevant_documents(query) for top-K results

---

## 🤝 Contributing

We welcome contributions from the community! To contribute:

1. **Fork the Repository**: Use the GitHub fork button to create your copy.
2. **Create a Branch**: Use a descriptive name for your branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Commit your changes with clear commit messages.
   ```bash
   git commit -am "Add new Feature"
   ```
   
4. **Submit a Pull Request**: Push your branch and open a pull request (PR) against the main repository.
   ```bash
   git push origin feature/your-feature-name
   ```
   
---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

> Copyright © 2025

---

## 💬 Support & Contact

If you encounter any issues or have questions:
- Open an [issue](https://github.com/dhruv-2615p/QA-BOT/tree/main/.github/ISSUE_TEMPLATE).
- Contact the maintainers directly via email or through GitHub discussions.

Thank you for your interest in **QA-BOT**. We hope you find it useful and look forward to your contributions!

---

Happy Coding!