# Custom-GPT2-Model
End-to-End Training of a custom GPT2 model using Pytorch

Script trains a GPT (Generative Pre-trained Transformer) language model on story datasets. It implements a complete GPT architecture with multi-head self-attention and trains the model to predict the next character in text sequences.
The script:

Sets up a GPT model with configurable size (layers, attention heads, embedding dimensions)

Loads and processes text data from the STORIES dataset or fallbacks

Builds a character-level vocabulary from the dataset

Trains the model using autoregressive language modeling with cross-entropy loss

Uses mixed precision training when available for better performance

Periodically evaluates the model on validation data

Saves checkpoints of the best model during training

Generates sample text completions after each evaluation to demonstrate progress

Includes full error handling and resource management for reliable training

The trained model can be used to generate creative story text completions.
