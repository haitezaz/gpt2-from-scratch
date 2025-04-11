# GPT-2 From Scratch and Text Generation 

This project showcases how to build a GPT-2 language model completely from scratch using PyTorch and train it on custom data. It demonstrates the full training pipeline, text generation, and evaluation—perfect for anyone who wants to understand how transformer-based language models work under the hood.

---

 Project Overview

In this project, I implemented the GPT-2 architecture from scratch following the core concepts introduced by Andrej Karpathy in his educational series on building transformers. The model is trained using a custom dataset and can generate coherent text based on a given prompt. The goal was to learn, replicate, and deeply understand how GPT-2 works internally.

---

 Technologies Used:

- **Python** – Primary programming language.
- **PyTorch** – Deep learning framework used for model building and training.
- **NLP Concepts** – Tokenization, attention mechanism, causal masking, and transformer blocks.
- **Matplotlib** *(optional)* – For visualizing training and validation loss.
- **Tiktoken** – For efficient GPT-style tokenization (compatible with OpenAI tokenizers).

---

 Steps Covered :

### 1. Model Implementation
- Built the entire GPT-2 architecture from scratch using PyTorch.
- Implemented components like:
  - Multi-head self-attention
  - Positional encoding
  - Layer normalization
  - Feedforward network
  - Causal masking

### 2. Dataset and Training
- Trained the model using a custom dataset.
- Tracked training and validation losses across multiple epochs.
- Token counting and evaluation frequency were configurable.

### 3. Text Generation
- Used a context-based sampling function to generate creative, meaningful text.
- Input a prompt like `"Every effort moves you"` and the model generates continuation in natural language.

---
