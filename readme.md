# Project Setup Guide (Pipenv + Python 3.14)

This project uses **Pipenv** for dependency management and virtual environment isolation.

---

## 📌 Prerequisites

Ensure the following are installed on your system:

- **Python 3.12**
- **pip**
- **pipenv**

Verify installations:
```bash
pipenv install
pipenv --version
# Install the required packages
pipenv --python 3.12
pipenv install --python 3.12
pipenv install beautifulsoup4 black tiktoken openai unstructured nltk fastapi jinja2 uvicorn streamlit streamlit-chat tqdm isort langchainhub firecrawl-py langchain-community langsmith pillow certifi langchain-chroma python-dotenv langchain-tavily langchain-pinecone
```

To activate the virtual env run the following command
```bash
run pipenv shell
```

To run the streamlit app
```commandline
pipenv run streamlit run main.py
```

