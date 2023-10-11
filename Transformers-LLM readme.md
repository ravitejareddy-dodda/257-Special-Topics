a)
NanoGPT with TensorFlow: https://colab.research.google.com/drive/14ACCK-HZMX8mXt1sAl1eZZghgN9HuRiy#scrollTo=2oDYQc1GrNr6

NanoGPT using TensorFlow
This repository contains an implementation of the NanoGPT model using TensorFlow 2.x. NanoGPT, inspired by OpenAI's GPT, is a smaller variant tailored for specific applications and is designed to be lightweight and efficient.

Steps Covered:
Environment Setup:

TensorFlow 2.x is the primary library used for building and training the model.
Model Definition:

Transformer Block: A fundamental building block of the GPT architecture, the transformer block utilizes multi-head self-attention mechanisms. It contains a residual connection followed by a dense layer.
NanoGPT Model: The overall model consists of an embedding layer, followed by the transformer block, and finally a dense layer. This architecture allows the model to capture sequential patterns in textual data.
Data Preparation:

For demonstration purposes, a placeholder text is used to mimic "Pride and Prejudice". However, users can replace this with any textual data of their choice.
The data is tokenized using TensorFlow's Tokenizer, converting textual data into numerical sequences.
Model Initialization and Compilation:

The model is initialized with specified hyperparameters: vocabulary size, model dimensions, and the number of attention heads.
It's compiled using the Adam optimizer, sparse categorical cross-entropy as the loss function, and accuracy as a metric.

NanoGPT in JAX/Flax: https://colab.research.google.com/drive/15t-eM5P3KiipXrhjSAYxAAm-AvGuIrwd?usp=sharing

NanoGPT using PyTorch: https://colab.research.google.com/drive/1KCXBM3F1_5WV4Y51xRcHSUJUt0Ty5wTW?usp=sharing

Model Architecture:
Embedding Layer: Converts token IDs into continuous vectors.
Transformer Block: The heart and soul of the model.
Multi-head Self Attention: Enables the model to focus on different parts of the input text.
Feed-forward Neural Network: A straightforward fully connected neural network.
Output Layer: Produces probability distributions over the vocabulary for each token in the sequence.

medium article explaining sections of code in depth: https://medium.com/@ravitejareddy.dodda/large-language-models-and-transformers-building-nanogpt-04a2097f7280


