# Recurrent Networks, LSTMs, and Transformers

My coursework on sequence modeling, progressing from a recurrent neural network implemented in NumPy to character-level language models built with PyTorch.

## Contents

| Notebook | Topics |
|---|---|
| [A1](lstm/A1.ipynb) | Recurrent network initialization and forward pass, numerically stable binary cross-entropy, and computational graphs |
| [A2](lstm/A2.ipynb) | Backpropagation through time, numerical gradient checking, gradient descent, and long-term dependency experiments |
| [A3](lstm/A3.ipynb) | Character-level LSTM language modeling, model selection, top-k accuracy, temperature sampling, and adaptive Huffman coding |
| [A4](lstm/A4_Notebook.ipynb) | A small GPT-style transformer with causal multi-head attention, positional embeddings, residual connections, and autoregressive generation |

## Highlights

- Implementing recurrent network training and gradients directly in NumPy.
- Investigating the difficulty of learning long-term dependencies.
- Training an LSTM for next-character prediction.
- Generating text using temperature-controlled sampling.
- Using LSTM predictions to explore adaptive text compression.
- Building transformer components and a training loop in PyTorch.
