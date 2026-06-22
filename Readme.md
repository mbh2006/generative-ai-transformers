# Generative AI & Transformers

This repository contains a collection of hands-on implementations and in-depth analyses of foundational Natural Language Processing (NLP) and Generative AI techniques. The projects cover the full pipeline of modern language modeling: from raw text tokenization and word embeddings to Transformer-based architectures and parameter-efficient fine-tuning.

## 📂 Repository Contents

This repository is organized into five core projects, each contained within its own Jupyter Notebook:

### 1. Byte Pair Encoding (BPE) From Scratch (`Byte Pair Encoding.ipynb`)
A pure Python implementation of the BPE tokenization algorithm, built without external NLP libraries.

**Key Concepts**
- Frequency-based subword tokenization
- Vocabulary initialization
- Greedy merging
- Inference tokenization for out-of-vocabulary (OOV) handling

**Tech Stack**
- Python

### 2. Word Embedding Quest (`Word Embedding Quest.ipynb`)
An exploration of distributed word representations, implementing the **Word2Vec** algorithm from scratch.

**Key Concepts**
- Skip-gram with Negative Sampling (SGNS)
- Sliding window context generation
- Custom stochastic gradient descent
- Semantic similarity analysis

**Tech Stack**
- Python
- NumPy
- NLTK

### 3. Transformer Implementation & Attention Analysis (`Transformer_Attention.ipynb`)
A deep dive into the Transformer architecture and the mechanics of multi-head attention.

**Key Concepts**
- Building a decoder-only language model from scratch
- Extracting and visualizing attention matrices from pretrained BERT models
- Exploring the interpretability of attention mechanisms

**Tech Stack**
- PyTorch
- Hugging Face `transformers`
- Matplotlib
- Seaborn

### 4. NanoGPT Implementation (`NanoGPT.ipynb`)
A complete, from-scratch PyTorch implementation of a miniature Generative Pre-trained Transformer (GPT).

**Key Concepts**
- Causal multi-head self-attention
- Positional encoding
- Autoregressive text generation
- Custom training loops with gradient clipping and learning rate scheduling

**Tech Stack**
- PyTorch
- `tiktoken`

### 5. LoRA Fine-Tuning (`LoRA.ipynb`)
A practical implementation of **Low-Rank Adaptation (LoRA)** for parameter-efficient fine-tuning of language models.

**Key Concepts**
- LoRA layer implementation from scratch
- Freezing base model weights
- Training only low-rank adaptation parameters
- Parameter-count comparison
- Evaluation of adapted vs. base model performance

**Tech Stack**
- PyTorch
- Hugging Face `transformers`
- `datasets`
- NumPy
- Matplotlib

## 🧠 Topics Covered

- Tokenization and subword modeling
- Word embeddings and representation learning
- Self-attention and Transformer architectures
- Autoregressive language modeling
- Attention visualization and interpretability
- Parameter-efficient fine-tuning with LoRA
- Text generation and model evaluation

## 🎯 Project Motivation

The goal of this repository is to understand the core algorithms behind modern language models by implementing 

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
