# rag-eval-workshop-oxford-llm2024

This repository contains the notebooks and instructions for a RAG evaluation workshop using [Qdrant](https://qdrant.tech/) as a vector database and [RAGAS](https://docs.ragas.io/en/latest/index.html) as the evaluation framework.

The Jupyter notebooks guide you step-by-step building RAG on Qdrant's documentation and walking through optimizations and tweaks along with evaluation.

## Prerequisites

Please clone the repository and install all the dependencies to run the notebooks.

```bash
git clone https://github.com/qdrant/qdrant-rag-eval.git
cd workshop-rag-eval-oxford-llm2024
```

## Optional (but advised!)

Please create a virtual environment for the workshop

```bash
python3 -m venv oxford-rag-eval
source oxford-rag-eval/bin/activate
```

### Poetry

This project uses [Poetry](https://python-poetry.org/) to manage its dependencies. You can install it by following the instructions on the [official website](https://python-poetry.org/docs/#installation).
Once you have it, the dependencies can be installed by running:

```bash
pip install poetry
poetry install --no-root
poetry shell
```

## Running the notebooks

Once all the dependencies are installed, Jupyter notebook might be started by running the following command:

```bash
jupyter notebook
```

The default browser should open automatically.
