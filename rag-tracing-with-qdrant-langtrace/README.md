# RAG System with Qdrant and Langtrace

This project demonstrates a Retrieval-Augmented Generation (RAG) system using Qdrant as the vector database and Langtrace for tracing operations.

## Setup

1. Ensure you have Python 3.8 or higher installed.

2. Install Poetry if you haven't already:

   ```bash
   curl -sSL https://install.python-poetry.org | python3 -
   ```

3. Clone this repository:

   ```bash
   git clone git clone https://github.com/qdrant/qdrant-rag-eval.git
   cd qdrant-rag-eval/rag-tracing-with-qdrant-langtrace
   ```

4. Install dependencies:

   ```bash
   poetry install --no-root
   ```

5. Activate the virtual environment:

   ```bash
   poetry shell
   ```

6. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

7. Open the `rag_qdrant_langtrace.ipynb` notebook in your browser.

8. Before running the notebook, make sure to replace the placeholder API keys with your actual OpenAI and Langtrace API keys.

## Usage

Follow the instructions in the Jupyter notebook to run the RAG system and analyze the results using Langtrace.
