# Low-Rank Adaptation (LoRA)

A hands-on exploration and implementation of **LoRA (Low-Rank Adaptation)** for parameter-efficient fine-tuning of a pre-trained language model. This notebook demonstrates how to adapt a model using a small number of trainable parameters while preserving the knowledge stored in the frozen base model.

## 🚀 Overview

In this notebook, we explore LoRA in two parts:

- **LoRA Layer Implementation:**  
  Build LoRA layers from scratch and apply them to a simple linear layer to understand the core idea behind low-rank updates.

- **LoRA for Language Model Fine-Tuning:**  
  Apply LoRA to a pre-trained causal language model and compare the base model with the LoRA-adapted version on a text classification / language modeling task.

The project includes:

- Implementing a LoRA layer from scratch
- Creating LoRA-adapted linear layers
- Replacing attention projection layers with LoRA modules
- Freezing base model parameters
- Training only the low-rank adaptation weights
- Comparing parameter counts and model performance
- Evaluating token-level accuracy

## 🛠 Prerequisites

To run this notebook, you will need Python 3 installed along with the following libraries:

```bash
pip install torch transformers datasets numpy matplotlib