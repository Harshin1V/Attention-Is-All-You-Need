# Transformer from Scratch in PyTorch

This project implements a Transformer model from the paper ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762) from scratch using PyTorch. The implementation includes key components like multi-head self-attention, position-wise feedforward layers, and positional encoding. A basic training pipeline with an optimizer and loss function is also integrated.

## Features 🚀
- Full Transformer architecture including:
  - Multi-head Self-Attention
  - Positional Encoding
  - Feedforward Network
  - Layer Normalization
  - Skip Connections
- Training pipeline with dummy data
- Adam optimizer & Cross-Entropy Loss
- Easily extensible for real NLP datasets

## Installation 📦
Make sure you have Python 3.8+ and PyTorch installed. Then install dependencies:
```sh
pip install -r requirements.txt
```

## Usage 🛠️
Run the script to train the Transformer on dummy data:
```sh
python train.py
```


## References 📚
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- PyTorch Documentation: https://pytorch.org/docs/stable/


