# AI-Assistant

A simple Python-based AI assistant powered by LangChain and OpenAI. This project provides a command-line interface where you can chat with an AI model, perform calculations, and extend functionality with custom tools. Environment variables and virtual environments are managed for security and reproducibility.

<img width="583" height="366" alt="Screenshot (500)" src="https://github.com/user-attachments/assets/0143dee7-6269-44b7-a71b-5b13a0dd5145" />

---

## Quick Start

### 1. Install [uv](https://github.com/astral-sh/uv) (if you don’t have it)
```sh
pip install uv
```

### 2. Install dependencies with uv
From the project root:
```sh
uv pip install -r Assistant/pyproject.toml
```
*Or, if you have a `requirements.txt`:*
```sh
uv pip install -r requirements.txt
```

### 3. Set your OpenAI API key
Create a `.env` file in the `Assistant` folder with:
