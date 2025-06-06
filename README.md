# Agentic AI in Practice: Official Code Repository

Welcome to the official code repository for the book **"Agentic AI: From Tools to Autonomous Agents"** by Mithun Kumar S R. This repository contains all the code snippets, examples, and capstone projects discussed in the book.

**[Link to where the book can be purchased or read]**

---

## About This Repository

This repository is designed to be a practical companion to the book, allowing you to run the code and experiment with the concepts you've learned. It uses a hybrid approach:
* **Google Colab Notebooks (`.ipynb`)** are used for foundational chapters to provide an interactive, zero-setup learning experience.
* **Standard Python Projects (`.py` files)** are used for advanced architectures and capstone projects to demonstrate professional, multi-file application structure.

## Getting Started

To run the Python projects locally, please follow the setup instructions in **Appendix A: Setting Up Your Development Environment**. The basic steps are:

1.  Clone this repository: `git clone https://github.com/mithunkumarsr/agentic-ai-in-practice.git`
2.  Navigate to a project directory: `cd agentic-ai-in-practice/projects/ch07-multi-agent-systems`
3.  Create and activate a virtual environment.
4.  Install dependencies: `pip install -r requirements.txt`
5.  Set up your `.env` file with your API keys.
6.  Run the main script: `python main.py`

---

## Project Index

### Part II: Core Technologies
* **[Chapter 4: Memory and RAG](./projects/ch04-memory-and-rag/)**: A notebook demonstrating a complete Retrieval-Augmented Generation pipeline. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/agentic-ai-in-practice/blob/main/projects/ch04-memory-and-rag/rag_pipeline_example.ipynb)
* **[Chapter 5: Tool Use](./projects/ch05-tool-use/)**: An interactive demonstration of the ReAct (Reason+Act) pattern. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/agentic-ai-in-practice/blob/main/projects/ch05-tool-use/basic_react_loop.ipynb)

### Part III: Agentic Architectures
* **[Chapter 7: Multi-Agent Systems](./projects/ch07-multi-agent-systems/)**: A full Python project demonstrating a hierarchical agent crew (CrewAI style).
* **[Chapter 8: Planner-Executor](./projects/ch08-planner-executor/)**: A complete Python project implementing the Planner-Executor architecture.

### Capstone Projects
* **[Capstone 1: The Autonomous Code Refactorer](./projects/capstone-01-code-refactorer/)**: A full project demonstrating an agent that can analyze and refactor code.
* **[Capstone 2: The Multi-Agent Research Assistant](./projects/capstone-02-research-assistant/)**: A complete multi-agent system that can research a topic and write a report.

---

## License

The code in this repository is released under the [MIT License](./LICENSE).
