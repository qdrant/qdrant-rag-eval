This Repo contains all Qdrant based RAG Evaluation Reference material , notebooks and contents.
## Building & Evaluating Retrieval Augmented Generation (RAG) with QDRANT

This repository contains various implementations of Retrieval Augmented Generation (RAG) using QDRANT, an open-source vector search engine. The project showcases different approaches to build RAG with QDRANT for efficient and effective information retrieval and generation. Additionally, the repository includes comprehensive evaluation tools to assess the performance of the implemented RAG application.

### RAG Implementations with EVALs

- **[workshop-rag-eval-qdrant-arize](https://github.com/qdrant/qdrant-rag-eval/tree/master/workshop-rag-eval-qdrant-arize)** : RAG implementation showcasing Naive (using Dense Vectors) vs Hybrid RAG (using Sparse and Dense Vectors) through [Qdrant](https://qdrant.tech/) and [Llamaindex](https://www.llamaindex.ai/) and evaluating it using [Arize Phoenix.](https://phoenix.arize.com/) Youtube : https://www.youtube.com/watch?v=m_J0nFmnrPI <br/><br/>

- **[workshop-rag-eval-qdrant-quotient](https://github.com/qdrant/qdrant-rag-eval/tree/master/workshop-rag-eval-qdrant-quotient)**: RAG implementation showcasing Naive RAG implemented using [Qdrant](https://qdrant.tech/) and [Langchain](https://www.langchain.com/), incrementally evaluated and improved through rapid experimentation with Chunk size , Embedding model and LLM using [Quotient AI](https://www.quotientai.co/). <br/>
**Youtube**: https://www.youtube.com/watch?v=3MEMPZR1aZA <br>
**Article**: https://qdrant.tech/articles/rapid-rag-optimization-with-qdrant-and-quotient/ <br/><br/>

- **[workshop-rag-eval-qdrant-quotient-advance-hybrid-with-rerankers](https://github.com/qdrant/qdrant-rag-eval/blob/master/workshop-rag-eval-qdrant-quotient/notebook/quotient_qdrant_rag_eval_with_reranker.ipynb)**: RAG implementation showcasing Naive RAG and Hybrid RAG implemented using [Qdrant](https://qdrant.tech/) and [Langchain](https://www.langchain.com/) and Hybrid RAg implemented using [Llamaindex]([)](https://www.llamaindex.ai/) incrementally evaluated and improved through rapid experimentation with rerankers from [MixedBread](https://www.mixedbread.ai/blog/mxbai-rerank-v1) , [Jina Colbert](https://huggingface.co/jinaai/jina-colbert-v1-en) and [Cohere](https://cohere.com/blog/rerank-3) using [Quotient AI](https://www.quotientai.co/). <br/>
**Youtube**: TBD <br>
**Presented at [AI Engineer Wolrd Fair](https://www.ai.engineer/worldsfair)**: https://www.ai.engineer/worldsfair/2024/schedule/navigating-rag-optimization-with-an-evaluation-driven-compass <br/><br/>

- **[workshop-rag-eval-qdrant-ragas](https://github.com/qdrant/qdrant-rag-eval/tree/master/workshop-rag-eval-qdrant-ragas)**:  RAG implementation showcasing Naive RAG implemented using [Qdrant](https://qdrant.tech/) and [Langchain](https://www.langchain.com/) , experimentation and effects of Retrieval Window size evaluated through [RAGAS](https://docs.ragas.io/en/latest/index.html). <br/>
**Article** : https://superlinked.com/vectorhub/articles/retrieval-augmented-generation-eval-qdrant-ragas <br/><br/>

- **[workshop-rag-eval-qdrant-ragas-haystack](https://github.com/qdrant/qdrant-rag-eval/tree/master/workshop-rag-eval-qdrant-ragas-haystack)** :  RAG implementation showing Naive RAG implemented using [Qdrant](https://qdrant.tech/) and [Haystack](https://docs.haystack.deepset.ai/docs/ragasevaluator) , experimentation and improvement through [MixedBread AI Embedding model](https://www.mixedbread.ai/blog/mxbai-embed-large-v1)  and [Reranker model](https://huggingface.co/mixedbread-ai/mxbai-rerank-large-v1) + Retrieval Window Size , evaluated through [RAGAS](https://docs.ragas.io/en/latest/index.html). <br/>
**YouTube** : https://www.youtube.com/watch?v=6NTZqpc4V-k  <br/><br/>

- **[workshop-rag-eval-qdrant-ragas-DSPy](https://github.com/qdrant/qdrant-rag-eval/blob/master/workshop-rag-eval-qdrant-ragas/notebook/naive_rag_eval_qdrant_ragas-with-dspy.ipynb)**:  RAG implementation showcasing Naive RAG implemented using [Qdrant](https://qdrant.tech/), [Langchain](https://www.langchain.com/) and [DSPy](https://github.com/stanfordnlp/dspy), experimentation and effects of Retrieval Window size evaluated through [RAGAS](https://docs.ragas.io/en/latest/index.html). <br/>

- **[agentic_rag_with_unify/notebook](https://github.com/qdrant/qdrant-rag-eval/tree/master/agentic_rag_with_unify)** :  RAG implementation showing Naive RAG implementation using [Qdrant](https://qdrant.tech/) and improved through using Agent Routing and [Unify](https://unify.ai/).  <br/><br/>

- **[synthetic_qna/notebook](https://github.com/qdrant/qdrant-rag-eval/tree/master/synthetic_qna)** : Showing synthetic evaluation question generation or checkout https://www.fiddlecube.ai/ 

### Qdrant Integration
Each example is integrated with QDRANT to leverage its powerful vector search capabilities. Detailed instructions and code examples for each integration are provided in the respective directories.

### Evaluation Tools

We provide a suite of RAG evaluation tools to assess the performance of the implemented RAG models. These tools are designed to measure various aspects of the RAG systems, ensuring a thorough and robust evaluation process. 

### Datasets

The RAGs are built using [source dataset](https://huggingface.co/datasets/atitaarora/qdrant_doc) containing Qdrant’s documentation and evaluated using [Evaluation dataset](https://huggingface.co/datasets/atitaarora/qdrant_doc_qna).

### Usage

Follow the instructions in the respective directories to run the RAG implementations and perform evaluations using the provided tools.

### Contributing

We welcome contributions from the community! If you have any improvements or new RAG Evaluation tool cookbook to add, please submit a pull request or open an issue.


### Acknowledgements

We would like to thank the contributors and the open-source community for their support and collaboration.


