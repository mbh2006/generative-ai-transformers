# Byte Pair Encoding (BPE) From Scratch

This module contains a pure Python implementation of the Byte Pair Encoding (BPE) tokenization algorithm, built entirely from scratch without reliance on external NLP libraries.

## Overview
BPE is a fundamental, frequency-based subword tokenization strategy used by state-of-the-art language models (such as GPT-family models and BERT). It allows models to efficiently manage vocabulary size, gracefully handle out-of-vocabulary (OOV) and rare words, and capture semantic subword units like prefixes and suffixes.

## Implementation Features
* **Vocabulary Initialization:** Maps raw text corpora into character-level sequences appended with end-of-word markers (`</w>`).
* **Frequency Analysis:** Dynamically calculates and ranks the most frequently occurring adjacent symbol pairs across the entire corpus.
* **Greedy Merging:** Iteratively merges optimal symbol pairs to compress the vocabulary representation.
* **Inference Tokenization:** Accurately applies learned chronological merge rules to new, unseen text.

## Usage & Structure
The primary notebook (`Byte Pair Encoding.ipynb`) walks through the entire training and inference pipeline:
1. **Corpus Processing:** Loading and preprocessing a raw text corpus (*Alice's Adventures in Wonderland*).
2. **Tokenizer Training:** Training the algorithm to extract a specified number of optimal merge rules.
3. **Application:** Tokenizing full strings of unseen text based on the learned subword vocabulary.