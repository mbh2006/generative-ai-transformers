# Word Embedding Quest

A hands-on exploration and implementation of the **Word2Vec** algorithm using the **Skip-gram with Negative Sampling (SGNS)** approach. This project guides you through the process of building semantic word embeddings from raw text data.

## 🚀 Overview

In this notebook, we transform raw textual data (specifically an excerpt from *The Lord of the Rings*) into dense vector representations. This involves:
- **Data Preprocessing:** Cleaning, tokenization, and vocabulary building.
- **Sliding Window:** Implementing the Skip-gram windowing strategy to generate center-context word pairs.
- **Model Implementation:** Building a Word2Vec model with negative sampling from scratch using NumPy.
- **Training & Evaluation:** Training the model using Stochastic Gradient Descent and visualizing loss trends.

## 🛠 Prerequisites

To run this notebook, you will need Python 3 installed along with the following libraries:

```bash
pip install numpy nltk matplotlib