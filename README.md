# DigammaAttention

This repository contains a PyTorch implementation of a Transformer-based language learning model with optional digamma integration. It's released under the MIT open source license.

Key Features:

Utilizes a Transformer encoder architecture for language modeling tasks.
Offers the option to incorporate a digamma function for potential performance enhancements.
Implements safe sine operations for numerical stability.
Enforces causality constraints through attention masking.
Provides a clear and concise implementation for ease of understanding and modification.
Getting Started:

Install dependencies:
Bash
pip install torch transformers
Use code with caution. Learn more
Import the model:
Python
from llm import LLM
Use code with caution. Learn more
Instantiate the model:
Python
model = LLM(vocab_size, embed_dim, hidden_dim, num_layers, dropout, use_digamma=True)
Use code with caution. Learn more
Pass input sequences to the model:
Python
logits = model(inputs)
Use code with caution. Learn more
