# Generative AI & Transformers

This repository contains a collection of hands-on implementations and in-depth analyses of foundational Natural Language Processing (NLP) and Generative AI architectures. The projects span the entire pipeline of modern language modeling: from raw text tokenization and word embeddings to training autoregressive Transformer models from scratch.

## 📂 Repository Contents

This repository is divided into four core projects, each contained within its own Jupyter Notebook:

### 1. Byte Pair Encoding (BPE) From Scratch (`Byte Pair Encoding.ipynb`)
A pure Python implementation of the BPE tokenization algorithm, built without external NLP libraries.
* **Key Concepts:** Frequency-based subword tokenization, vocabulary initialization, greedy merging, and inference tokenization for out-of-vocabulary (OOV) handling.
* **Tech Stack:** Python.

### 2. Word Embedding Quest (`Word Embedding Quest.ipynb`)
An exploration of distributed word representations, implementing the **Word2Vec** algorithm from scratch.
* **Key Concepts:** Skip-gram with Negative Sampling (SGNS), sliding window context generation, custom stochastic gradient descent, and semantic similarity analysis.
* **Tech Stack:** Python, NumPy, NLTK.

### 3. Transformer Implementation & Attention Analysis (`Transformer_Attention.ipynb`)
A deep dive into the Transformer architecture and the mechanics of multi-head attention.
* **Key Concepts:** Building a decoder-only language model from scratch, extracting and visualizing attention matrices from pretrained BERT models, and exploring the interpretability of attention mechanisms.
* **Tech Stack:** PyTorch, Hugging Face `transformers`, Matplotlib, Seaborn.

### 4. NanoGPT Implementation (`NanoGPT.ipynb`)
A complete, from-scratch PyTorch implementation of a miniature Generative Pre-trained Transformer (GPT). 
* **Key Concepts:** Causal multi-head self-attention, positional encoding, autoregressive text generation, and custom training loops with gradient clipping and learning rate scheduling.
* **Tech Stack:** PyTorch, `tiktoken`.

## How to Setup and Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/mbh2006/generative-ai-transformers.git](https://github.com/mbh2006/generative-ai-transformers.git)

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Navigate to any project subfolder and launch Jupyter to run the notebooks:
   ```bash
    jupyter notebook
