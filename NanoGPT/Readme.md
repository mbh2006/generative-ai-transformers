# NanoGPT Implementation

A from-scratch PyTorch implementation of a miniature Generative Pre-trained Transformer (GPT). This project demonstrates the core mechanics of autoregressive language modeling, self-attention, and text generation.

## 🚀 Overview

This notebook walks through the architecture and training loop of a decoder-only Transformer model. It is designed to take a sequence of tokens and predict the next token, effectively generating text character-by-character or word-by-word depending on the chosen tokenizer.

**Key Features Implemented:**
- Multi-Head Causal Self-Attention
- Transformer Blocks (Pre-LayerNorm architecture)
- Positional Encoding
- Custom PyTorch Training Loop with Optimizer Stepping
- Text Generation Functionality

## 🛠 Prerequisites

This project requires Python 3 and PyTorch. Due to the computational demands of Transformer models, **running this notebook on a machine with a CUDA-enabled GPU (or via Google Colab) is highly recommended.**

```bash
pip install torch numpy