# 🧠 A Simple Q&A Chatbot (LangChain + Chainlit + Ollama)

This is a simple interactive chatbot built with [LangChain](https://www.langchain.com/) and [Chainlit](https://www.chainlit.io/) that uses the `ChatOllama` integration to answer historical questions in a knowledgeable and eloquent manner.

## ✨ Features

- Uses the `gemma:2b` model via `langchain_ollama`.
- Streamed response generation.
- Role-based prompt design (historian system prompt).
- Beautiful UI powered by Chainlit.
- Easily switchable between Ollama and OpenAI models.

## 📦 Requirements

Make sure you have the following installed:

- Python 3.8+
- [Chainlit](https://docs.chainlit.io/installation)
- LangChain
- langchain_ollama
- Ollama installed and running locally with `gemma:2b` model pulled

## Install Python packages
```bash
pip install chainlit langchain langchain_ollama
```

## Run the Ollama model  (Optional)
```bash
ollama run gemma:2b
```

## 🚀 How to Run

1. Save your code in a Python file, e.g., `main.py`.

2. Start your Ollama server and pull the model (if not already done):

    ```bash
    ollama pull gemma:2b
    ```

3. Run the Chainlit app:

    ```bash
    chainlit run main.py
    ```

4. Open your browser and visit:

    ```text
    http://localhost:8000
    ```
