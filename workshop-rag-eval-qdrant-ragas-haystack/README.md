# rag-eval-workshop-qdrant-ragas-haystack

This repository contains the notebooks and instructions for a RAG evaluation workshop using [Qdrant](https://qdrant.tech/) as a vector database along with Deepset [Haystack](https://docs.haystack.deepset.ai/docs/ragasevaluator) and [RAGAS](https://docs.ragas.io/en/latest/index.html) as the evaluation framework.

The Jupyter notebooks guide you step-by-step building RAG on Qdrant's documentation and walking through optimizations and tweaks along with evaluating using Phoenix.

## Prerequisites

Please clone the repository and install all the dependencies to run the notebooks.

```bash
git clone https://github.com/qdrant/qdrant-rag-eval.git
```

### Poetry

This project uses [Poetry](https://python-poetry.org/) to manage its dependencies. You can install it by following the instructions on the [official website](https://python-poetry.org/docs/#installation).
Once you have it, the dependencies can be installed by running:

```bash
cd workshop-rag-eval-qdrant-ragas
poetry install --no-root
poetry shell
```

## Running the notebooks

Once all the dependencies are installed, Jupyter notebook might be started by running the following command:

```bash
jupyter notebook
```

The default browser should open automatically.
