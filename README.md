# Learn LangChain

> A personal, hands-on learning journey through [LangChain](https://www.langchain.com/).  
> I’m following publicly available LangChain courses and expanding with my own experiments, notes, and mini-projects.

---

## What You’ll Find Here

I’m completing each module step by step — rewriting, experimenting, and building as I learn.

| # | Topic | Highlights |
|---|-------|-----------|
| 1 | **Chat Models** | Explored `gpt-3.5-turbo`, GPT-4, Claude Sonnet, added memory to conversations |
| 2 | **Prompt Templates** | Designed dynamic templates, tested temperature & logit bias |
| 3 | **Chains** | Built sequential/custom chains with error handling |
| 4 | **Retrieval Augmented Generation (RAG)** | Implemented FAISS vector store, metadata filtering |
| 5 | **Agents & Tools** | Created simple multi-step agents (e.g., weather API) |

---

## Getting Started

1. **Clone this repo**

   ```bash
   git clone https://github.com/rakeshkommineni/Learn_LangChain.git
   cd Learn_LangChain

2. **Set up a virtual environment**

        ```bash
        python -m venv myvenv 
        # Activate (choose one depending on your shell):
        # PowerShell
        .\myvenv\Scripts\Activate.ps1
        # Git Bash / WSL
        source myvenv/Scripts/activate

3. **Install dependencies**

    ```bash
    pip install -r requirements.txt

4. **Open in VS Code**

    Select the Python interpreter from VENV.
    Open the modules or notebooks in the Explorer.

5. **Run & experiment**

    Follow the modules to jump around.
    Fork, modify, and add your own notes as you learn.
### Tech & Tools

- Python 3.11+,
- LangChain
- OpenAI API
- VS Code
- Git / GitHub for version control

## Future Plans
Add unit tests for chains and agents
Build a FastAPI demo using RAG
Experiment with different vector databases (FAISS → Pinecone, Qdrant)

 This repo is my public devlog— not a finished product, but it's just a record of my growth as a data engineer exploring LLM application development with LangChain.