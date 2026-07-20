# Building GPT from Scratch

This repository contains my implementation and notes from learning how GPT models work by building one from scratch in PyTorch.

The project starts with a simple character-level language model and gradually introduces the core concepts behind transformers, including self-attention, multi-head attention, positional embeddings, transformer blocks, and text generation.

The implementation follows Andrej Karpathy's "Let's Build GPT" tutorial and is intended for learning purposes.

## What this notebook covers

- Loading and preprocessing the Tiny Shakespeare dataset
- Character-level tokenization
- Building a Bigram Language Model
- Training a simple language model
- Understanding self-attention
- Implementing multi-head attention
- Building transformer blocks
- Training a GPT model
- Generating text

## Requirements

- Python 3.x
- PyTorch
- Jupyter Notebook or Google Colab

Install PyTorch:

```bash
pip install torch
```

## Running the notebook

Clone the repository:

```bash
git clone https://github.com/princeyadav27/GPT_DEMO
```

Open the notebook in Jupyter Notebook or Google Colab and run the cells in order.

## Dataset

The model is trained on the Tiny Shakespeare dataset:

https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt

## Reference

- Andrej Karpathy – Let's Build GPT
- Attention Is All You Need (2017)

## Note

This project was created as part of my learning journey to better understand how transformer-based language models work by implementing them from scratch instead of using high-level libraries,
