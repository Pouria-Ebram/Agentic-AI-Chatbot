# ChatbotLangChain Project

This project demonstrates how to build a chatbot using LangChain, LangGraph, and related libraries in Python. The main development is done inside the `chatbotlangchain.ipynb` Jupyter notebook.

## Features
- Utilizes LangChain and LangGraph for building conversational AI workflows
- Integrates with multiple LLM providers (OpenAI, Anthropic, Groq, HuggingFace, etc.)
- Uses `.env` file for API key management
- Example code and usage in a Jupyter notebook

## Requirements
- Python 3.8+
- The following Python packages (see `requirements.txt`):
  - python-dotenv
  - pydantic
  - langchain
  - langgraph
  - langchain-core
  - langchain-community
  - langchain-groq
  - arxiv
  - wikipedia
- Jupyter Notebook or JupyterLab

## Setup Instructions

1. **Clone the repository** (if not already):
   ```sh
   git clone <your-repo-url>
   cd windsurfproj
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   pip install notebook  # if you don't have Jupyter already
   ```

4. **Set up your API keys:**
   - Copy the provided `.env` file or create one with the following variables:
     - `OPENAI_API_KEY`
     - `ANTHROPIC_API_KEY`
     - `HF_TOKEN`
     - `GROQ_API_KEY`
     - `TAVILY_API_KEY`

5. **Start Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```
   Then open `chatbotlangchain.ipynb` in your browser.

6. **Select the correct kernel:**
   - Make sure to select the kernel associated with your virtual environment (e.g., `Python (windenv)`).

## Usage
- All code and documentation are in `chatbotlangchain.ipynb`.
- Follow the notebook cells for examples on setting up LangChain, using various models, and building conversational workflows.

## Troubleshooting
- If you do not see your environment as a kernel, install and register it:
   ```sh
   pip install ipykernel
   python -m ipykernel install --user --name=windenv --display-name "Python (windenv)"
   ```
- If you have issues with API keys, check your `.env` file and environment variables.

---

## License


## Author
Pouria Ebrahimnezhad
06/04/2025
