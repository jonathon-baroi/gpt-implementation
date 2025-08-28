# Transformer-based Character-Level Language Model

This project implements a **mini GPT-style transformer** from scratch in PyTorch, inspired by Andrej Karpathy’s tutorials.  
It trains a character-level language model on a given text corpus (Beatles lyrics in this case) and can generate new text samples.

---

## 📖 Features
- Character-level tokenization (no external tokenizer required).
- Implements **multi-head self-attention** and **transformer blocks** manually.
- Training loop with train/validation split and periodic loss evaluation.
- Text generation using autoregressive sampling.
- Works with any plain text dataset (`input.txt`).

