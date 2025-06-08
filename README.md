# Codebase Analysis and UI Analysis Projects

This document provides READMEs for two distinct Active Persona:
1.  **Ollama Codebase Analysis:** Utilizes Ollama for automated code review.
2.  **OpenAI-powered UI Analysis:** Employs OpenAI's GPT-4o for UI screenshot analysis.

---

## 1. Ollama Codebase Analysis

This section details the setup and dependencies for the `Ollama codebase Analysis.ipynb` notebook.

### Dependencies and Setup

To run this notebook, you will need to install the following dependencies and set up the Ollama environment:

### 1.1 Python

Ensure you have Python 3.8 or newer installed. You can download Python from [python.org](https://www.python.org/downloads/).

### 1.2 Ollama Service

This project relies on the Ollama service to run the language models locally.

* **Download and Install Ollama:** Follow the official installation instructions for your operating system from the [Ollama website](https://ollama.com/download).

### 1.3 Ollama Models

Once Ollama is installed, you need to pull the specific language model used in the notebook. The default model configured is `llama3.2`, but you can change this in the `config` dictionary within the notebook.

* **Pull the model:** Open your terminal or command prompt and run:
    ```bash
    ollama pull llama3.2
    ```
    (Replace `llama3.2` with your desired model if you change it in the notebook configuration).

### 1.4 Python Libraries

Install the required Python packages using `pip`:


pip install ollama tqdm humanize

# OpenAI-powered UI Analysis

This repository contains a Jupyter Notebook (`GTP-4o computer vision.ipynb`) designed to analyze user interface screenshots using OpenAI's GPT-4o model. It processes images, generates detailed feedback based on a defined persona, and summarizes the findings into a user review.

## Dependencies and Setup

To run this notebook, you will need to install the following dependencies and configure your OpenAI environment:

### 1. Python

Ensure you have Python 3.8 or newer installed. You can download Python from [python.org](https://www.python.org/downloads/).

### 2. OpenAI API Key

This project requires an OpenAI API key to access the `gpt-4o` model.

* **Obtain an API Key:** Sign up on the [OpenAI platform](https://platform.openai.com/) and generate a new secret API key.
* **Configure API Key:** Replace `"sk-proj-..."` with your actual API key in the `API_KEY` variable within the notebook.

### 3. Python Libraries

Install the required Python packages using `pip`:

```bash
pip install openai
